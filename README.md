
.logo {
    font-family: 'Manrope', sans-serif;
    font-size: 19px;
    font-weight: 800;
    letter-spacing: -0.7px;
    color: var(--navy);
    white-space: nowrap;
}

.logo span {
    color: #c38b2e;
    margin-left: 5px;
}

.navigation {
    display: flex;
    gap: 28px;
    color: #526176;
    font-size: 14px;
}

.navigation a:hover {
    color: #b98428;
}

.header-buttons {
    display: flex;
    align-items: center;
    gap: 12px;
}

.btn-login,
.btn-primary,
.btn-secondary,
.btn-project {
    border-radius: 7px;
    padding: 12px 19px;
    font-weight: 700;
    font-size: 13px;
    transition: 0.2s ease;
}

.btn-login {
    background: transparent;
    border: 1px solid transparent;
    color: var(--navy);
}

.btn-login:hover {
    border-color: var(--border);
}

.btn-primary {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    background: var(--gold);
    color: var(--navy);
    border: 1px solid var(--gold);
}

.btn-primary:hover {
    background: var(--gold-light);
    transform: translateY(-1px);
}

.hero {
    min-height: 550px;
    padding: 95px 9%;
    background:
        radial-gradient(
            circle at 80% 25%,
            rgba(233, 185, 92, 0.13),
            transparent 30%
        ),
        var(--navy);
    display: grid;
    grid-template-columns: 1.2fr 0.8fr;
    align-items: center;
    gap: 65px;
    color: var(--white);
}

.eyebrow {
    font-size: 11px;
    font-weight: 800;
    letter-spacing: 2px;
    color: #b98428;
    margin-bottom: 17px;
}

.hero .eyebrow {
    color: var(--gold);
}

.hero h1 {
    max-width: 650px;
    font-family: 'Manrope', sans-serif;
    font-size: clamp(36px, 4.2vw, 57px);
    font-weight: 800;
    line-height: 1.15;
    letter-spacing: -2px;
}

.hero h1 span {
    display: block;
    color: var(--gold);
}

.hero-description {
    max-width: 560px;
    margin-top: 24px;
    color: #c2cedc;
    font-size: 15px;
    line-height: 1.9;
}

.hero-actions {
    display: flex;
    flex-wrap: wrap;
    gap: 14px;
    margin-top: 30px;
}

.btn-secondary {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    border: 1px solid #526176;
    color: var(--white);
}

.btn-secondary:hover {
    border-color: var(--gold);
}

.risk-notice {
    margin-top: 24px;
    color: #aebdcd;
    font-size: 11px;
}

.hero-card {
    padding: 29px;
    border: 1px solid rgba(233, 185, 92, 0.35);
    border-radius: 16px;
    background: linear-gradient(
        145deg,
        #132c45,
        #0b1c2f
    );
    box-shadow: 0 25px 60px rgba(0, 0, 0, 0.2);
}

.card-top {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 10px;
    font-size: 10px;
    letter-spacing: 1px;
    color: #c5d0dc;
}

.status {
    color: #a9d9bd;
    letter-spacing: 0;
}

.card-icon {
    display: grid;
    place-items: center;
    width: 58px;
    height: 58px;
    margin-top: 36px;
    border-radius: 14px;
    background: rgba(233, 185, 92, 0.12);
    color: var(--gold);
    font-size: 28px;
}

.hero-card h2 {
    margin-top: 24px;
    font-family: 'Manrope', sans-serif;
    font-size: 26px;
}

.hero-card > p {
    margin-top: 13px;
    color: #b7c4d2;
    font-size: 13px;
    line-height: 1.9;
}

.card-footer {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin-top: 27px;
}

.card-footer span {
    padding: 7px 10px;
    border-radius: 5px;
    background: rgba(255, 255, 255, 0.07);
    color: #e1e8ef;
    font-size: 10px;
}

.section {
    padding: 85px 8%;
}

.section-heading {
    display: flex;
    align-items: end;
    justify-content: space-between;
    gap: 30px;
    margin-bottom: 35px;
}

.section-heading h2,
.how-section h2,
.cta-section h2 {
    font-family: 'Manrope', sans-serif;
    font-size: clamp(27px, 3vw, 36px);
    line-height: 1.3;
    letter-spacing: -1px;
}

.section-heading > p {
    max-width: 370px;
    color: var(--muted);
    font-size: 13px;
}

.projects-grid {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 23px;
}

.project-card {
    overflow: hidden;
    background: var(--white);
    border: 1px solid var(--border);
    border-radius: 12px;
    transition: transform 0.2s, box-shadow 0.2s;
}

.project-card:hover {
    transform: translateY(-4px);
    box-shadow: 0 15px 35px rgba(7, 21, 37, 0.07);
}

.project-image {
    min-height: 155px;
    padding: 18px;
    display: flex;
    align-items: start;
    background:
        linear-gradient(
            135deg,
            rgba(7, 21, 37, 0.15),
            rgba(7, 21, 37, 0.85)
        ),
        #254f44;
}

.commerce {
    background:
        linear-gradient(
            135deg,
            rgba(7, 21, 37, 0.2),
            rgba(7, 21, 37, 0.85)
        ),
        #526078;
}

.distribution {
    background:
        linear-gradient(
            135deg,
            rgba(7, 21, 37, 0.2),
            rgba(7, 21, 37, 0.85)
        ),
        #745b37;
}

.project-category {
    padding: 7px 10px;
    border-radius: 5px;
    background: var(--gold);
    color: var(--navy);
    font-size: 10px;
    font-weight: 800;
}

.project-body {
    padding: 23px;
}

.project-body h3 {
    min-height: 52px;
    font-family: 'Manrope', sans-serif;
    font-size: 17px;
    line-height: 1.5;
}

.project-body > p:not(.project-status) {
    min-height: 65px;
    margin-top: 10px;
    color: var(--muted);
    font-size: 12px;
}

.project-info {
    display: flex;
    flex-direction: column;
    gap: 4px;
    margin-top: 22px;
}

.project-info span {
    color: var(--muted);
    font-size: 11px;
}

.project-info strong {
    color: var(--navy);
    font-size: 19px;
}

.progress-track {
    height: 5px;
    margin-top: 15px;
    overflow: hidden;
    border-radius: 5px;
    background: #edf0f4;
}

.progress-fill {
    height: 100%;
    background: var(--gold);
}

.project-status {
    min-height: 38px;
    margin-top: 12px;
    color: #65758a;
    font-size: 10px;
}

.btn-project {
    width: 100%;
    margin-top: 13px;
    border: 1px solid var(--border);
    background: white;
    color: var(--navy);
}

.btn-project:hover {
    border-color: var(--gold);
    background: #fffaf0;
}

.how-section {
    padding: 85px 8%;
    background: #edf2f7;
    text-align: center;
}

.steps {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 25px;
    margin-top: 45px;
    text-align: left;
}

.step {
    padding: 28px;
    background: white;
    border: 1px solid var(--border);
    border-radius: 10px;
}

.step > span {
    color: #b98428;
    font-family: 'Manrope', sans-serif;
    font-size: 30px;
    font-weight: 800;
}

.step h3 {
    margin-top: 13px;
    font-family: 'Manrope', sans-serif;
    font-size: 17px;
}

.step p {
    margin-top: 10px;
    color: var(--muted);
    font-size: 12px;
    line-height: 1.9;
}

.cta-section {
    padding: 80px 8%;
    background: var(--navy-light);
    color: white;
    text-align: center;
}

.cta-section h2 {
    max-width: 700px;
    margin: 0 auto;
}

.cta-section > p:not(.eyebrow) {
    max-width:
}

.info-dialog[open] {
    display: block;
}

.info-dialog::backdrop {
    background: rgba(3, 13, 25, 0.7);
}

.info-dialog h2 {
    padding-right: 20px;
    font-family: 'Manrope', sans-serif;
    font-size: 23px;
}

.info-dialog p {
    margin: 18px 0 24px;
    color: var(--muted);
    font-size: 14px;
    line-height: 1.8;
}

.dialog-close {
    position: absolute;
    top: 12px;
    right: 16px;
    border: none;
    background: transparent;
    color: var(--muted);
    font-size: 28px;
}

@media (max-width: 1000px) {
    .header {
        flex-wrap: wrap;
    }

    .hero {
        grid-template-columns: 1fr;
        padding: 75px 7%;
    }

    .hero-card {
        max-width: 560px;
    }

    .projects-grid {
        grid-template-columns: repeat(2, minmax(0, 1fr));
    }
}

@media (max-width: 650px) {
    .header {
        padding: 17px 5%;
    }

    .navigation {
        order: 3;
        flex-basis: 100%;
        justify-content: space-between;
        gap: 12px;
        font-size: 12px;
    }

    .header-buttons {
        gap: 4px;
    }

    .header-buttons button {
        padding: 10px;
        font-size: 11px;
    }

    .hero {
        padding: 60px 6%;
        gap: 38px;
    }

    .hero h1 {
        font-size: 39px;
        letter-spacing: -1.5px;
    }

    .hero-actions {
        flex-direction: column;
        align-items: stretch;
    }

    .section,
    .how-section {
        padding: 60px 6%;
    }

    .section-heading {
        align-items: start;
        flex-direction: column;
        gap: 12px;
    }

    .projects-grid,
    .steps {
        grid-template-columns: 1fr;
    }

    .project-body h3,
    .project-body > p:not(.project-status) {
        min-height: auto;
    }

    .footer {
        flex-direction: column;
        align-items: start;
        padding: 30px 6%;
    }

    .cta-section {
        padding: 60px 6%;
    }
}"use strict";

const dialog = document.getElementById("infoDialog");
const dialogTitle = document.getElementById("dialogTitle");
const dialogMessage = document.getElementById("dialogMessage");

const closeDialog = document.getElementById("closeDialog");
const confirmDialog = document.getElementById("confirmDialog");

document.getElementById("year").textContent =
    new Date().getFullYear();

function showMessage(title, message) {
    dialogTitle.textContent = title;
    dialogMessage.textContent = message;

    if (!dialog.open) {
        dialog.showModal();
    }
}

document.getElementById("loginBtn").addEventListener("click", () => {
    showMessage(
        "Connexion",
        "L'espace de connexion sera activ� apr�s la mise en place de l'authentification s�curis�e."
    );
});

function openRegistration() {
    showMessage(
        "Cr�er un compte",
        "L'inscription sera disponible apr�s la configuration de la base de donn�es et de l'authentification."
    );
}

document.getElementById("registerBtn")
    .addEventListener("click", openRegistration);

document.getElementById("ctaRegisterBtn")
    .addEventListener("click", openRegistration);

document.querySelectorAll("[data-project]").forEach((button) => {
    button.addEventListener("click", () => {
        const projectName = button.dataset.project;

        showMessage(
            projectName,
            "Ce projet est fictif et sert � la d�monstration. Aucun investissement r�el n'est ouvert. Les d�tails du projet seront disponibles lorsque le syst�me de gestion des projets sera connect�."
        );
    });
});

function closeInfoDialog() {
    if (dialog.open) {
        dialog.close();
    }
}

closeDialog.addEventListener("click", closeInfoDialog);
confirmDialog.addEventListener("click", closeInfoDialog);

dialog.addEventListener("click", (event) => {
    if (event.target === dialog) {
        closeInfoDialog();
    }
});
eta
        name="description"
        content="Global Finance : d�couvrez des projets commerciaux et suivez leur financement."
    >

    <link rel="stylesheet" href="style.css">
</head>

<body>

    <header class="header">
        <a href="#" class="logo">
            GLOBAL<span>FINANCE</span>
        </a>

        <nav class="navigation">
            <a href="#accueil">Accueil</a>
            <a href="#projets">Projets</a>
            <a href="#fonctionnement">Fonctionnement</a>
        </nav>

        <div class="header-buttons">
            <button class="btn-login" id="loginBtn">
                Connexion
            </button>

            <button class="btn-primary" id="registerBtn">
                Cr�er un compte
            </button>
        </div>
    </header>

    <main>

        <section class="hero" id="accueil">

            <div class="hero-content">

                <p class="eyebrow">
                    FINANCEMENT � ENTREPRISES � OPPORTUNIT�S
                </p>

                <h1>
                    Construisons ensemble
                    <span>l'avenir financier.</span>
                </h1>

                <p class="hero-description">
                    D�couvrez des projets commerciaux, comprenez leurs
                    perspectives et participez � leur financement
                    dans un cadre transparent.
                </p>

                <div class="hero-actions">
                    <a href="#projets" class="btn-primary">
                        D�couvrir les proje�!
 ut investissement comporte des risques de perte.
                    Les b�n�fices ne sont pas garantis.
                </p>

            </div>

            <div class="hero-card">

                <div class="card-top">
                    <span>GLOBAL FINANCE</span>
 ivez leurs projets
                    gr�ce � une pr�sentation claire de leurs objectifs,
                    de leurs r�sultats et de leurs risques.
                </p>

                <div class="card-footer">
                    <span>Transparence</span>
                    <span>S�curit�</span>
                    <span>Suivi</span>
                </div>

            </div>

        </section>

        <section class="section" id="projets">

            <div class="section-heading">
                <div>
                    <p class="eyebrow">NOS OPPORTUNIT�S</p>
                    <h2>Projets � d�couvrir</h2>
                </div>

                <p>
                    Explorez les secteurs et les projets pr�sent�s
                    sur notre plateforme.
                </p>
            </div>

            <div class="projects-grid" id="projectsGrid">

                <article class="project-card">

                    <div class="project-image agriculture">
                        <span class="project-category">
                            Agriculture
                        </span>
                    </div>

                    <div class="project-body">

                        <h3>Distribution de produits agricoles</h3>

                        <p>
                            Exemple de projet commercial consacr�
                            � la distribution de produits agricoles.
                        </p>

                        <div class="project-info">
                            <span>Objectif indicatif</span>
                            <strong>5 000 000 FCFA</strong>
                        </div>

                        <div class="progress-track">
                            <div class="progress-fill" style="width: 0%"></div>
                        </div>

                        <p class="project-status">
                            Projet de d�monstration � financement non ouvert.
                        </p>

                        <button
                            class="btn-project"
                            data-project="Distribution de produits agricoles"
                        >
                            Consulter le projet
                        </button>

                    </div>

                </article>

                <article class="project-card">

                    <div class="project-image commerce">
                        <span class="project-category">
                            Commerce
                        </span>
                    </div>

                    <div class="project-body">

                        <h3>D�veloppement d'une entreprise commerciale</h3>

                        <p>
                            Exemple de projet destin� � d�velopper
                            une activit� d'achat et de revente.
                        </p>

                        <div class="project-info">
                            <span>Objectif indicatif</span>
                            <strong>3 000 000 FCFA</strong>
                        </div>

                        <div class="progress-track">
                            <div class="progress-fill" style="width: 0%"></div>
                        </div>

                        <p class="project-status">
                            Projet de d�monstration � financement non ouvert.
                        </p>

                        <button
                            class="btn-project"
                            data-project="Entreprise commerciale"
                        >
                            Consulter le projet
                        </button>

                    </div>

                </article>

                <article class="project-card">

                    <div class="project-image distribution">
                        <span class="project-category">
                            Distribution
                        </span>
                    </div>

                    <div class="project-body">

                        <h3>Fourniture de produits aux entreprises</h3>

                        <p>
                            Exemple de projet de distribution destin�
                            � r�pondre aux besoins des professionnels.
                        </p>

                        <div class="project-info">
                            <span>Objectif indicatif</span>
                            <strong>10 000 000 FCFA</strong>
                        </div>

                        
