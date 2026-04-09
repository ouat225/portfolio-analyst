---
layout: null
---
<style>
  body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; line-height: 1.6; color: #333; max-width: 1000px; margin: 0 auto; padding: 20px; background-color: #f9f9f9; }
  h1, h2, h3 { color: #111; text-align: center; }
  .section-title { font-size: 2em; margin-bottom: 5px; margin-top: 40px;}
  .section-line { width: 50px; height: 3px; background-color: #28a745; margin: 0 auto 30px auto; } /* Vert pour le côté Business/Analyst */
  
  /* Section Profil */
  .profile-container { display: flex; gap: 40px; background: white; padding: 40px; border-radius: 12px; box-shadow: 0 4px 6px rgba(0,0,0,0.05); margin-bottom: 50px; align-items: center; }
  
  .profile-image {
    flex: 0 0 200px;
    width: 200px;
    height: 200px;
    overflow: hidden;
    border-radius: 50%;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    border: 4px solid #fff;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .profile-image img {
    width: 100%;
    height: 100%;
    object-fit: cover; 
    object-position: center 15%;
  }

  .profile-text { flex: 2; }
  .profile-title { font-size: 1.5em; color: #28a745; font-weight: bold; margin-bottom: 5px; margin-top: 0;}
  .profile-subtitle { color: #666; font-weight: bold; margin-bottom: 20px; font-size: 1.1em; }
  .tech-stack { color: #666; font-size: 0.9em; margin-top: 20px; padding-top: 15px; border-top: 1px dashed #eee; }
  
  /* Section Projets (Cartes) */
  .projects-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(350px, 1fr)); gap: 30px; margin-bottom: 50px; }
  .project-card { background: white; padding: 30px; border-radius: 12px; box-shadow: 0 4px 6px rgba(0,0,0,0.05); border: 1px solid #eee; display: flex; flex-direction: column; }
  .project-title { color: #28a745; font-size: 1.4em; margin-top: 0; margin-bottom: 15px; text-align: left;}
  .project-desc { flex-grow: 1; margin-bottom: 20px; color: #555; }
  .project-tools { color: #888; font-size: 0.85em; margin-top: 20px; border-top: 1px dashed #eee; padding-top: 15px; }
  
  /* Section Background (Timeline) */
  .background-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 40px; margin-bottom: 50px; }
  .timeline-col h3 { text-align: left; color: #111; margin-bottom: 30px; font-size: 1.5em;}
  .timeline-item { border-left: 3px solid #28a745; padding-left: 20px; margin-bottom: 30px; position: relative; }
  .timeline-item::before { content: ''; position: absolute; left: -9px; top: 0; width: 15px; height: 15px; background: white; border: 3px solid #28a745; border-radius: 50%; }
  .timeline-date { color: #888; font-size: 0.9em; margin-bottom: 5px; font-weight: bold;}
  .timeline-title { font-weight: bold; color: #333; font-size: 1.1em; margin-bottom: 2px;}
  .timeline-subtitle { color: #555; font-style: italic; margin-bottom: 10px; font-size: 0.95em;}
  .timeline-desc { color: #555; font-size: 0.95em; margin-bottom: 5px;}
  .timeline-tools { font-size: 0.85em; color: #888; margin-top: 5px; font-style: italic;}

  /* Boutons */
  .btn-group { display: flex; gap: 15px; margin-bottom: 10px; }
  .btn { display: inline-block; padding: 8px 20px; border: 2px solid #28a745; color: #28a745; text-decoration: none; border-radius: 6px; font-weight: 600; font-size: 0.9em; transition: all 0.2s; }
  .btn:hover { background-color: #28a745; color: white; }
  .btn-solid { background-color: #28a745; color: white; border: none; padding: 12px 25px; border-radius: 8px; font-size: 1em; text-decoration: none; font-weight: bold;}
  .btn-solid:hover { background-color: #218838; color: white; text-decoration: none;}
  
  /* Section Contact */
  .contact-section { text-align: center; margin-top: 60px; padding: 40px 0; }
  .contact-buttons { display: flex; justify-content: center; gap: 20px; margin-top: 20px; }
  
  @media (max-width: 768px) {
    .profile-container { flex-direction: column; text-align: center; }
    .projects-grid, .background-grid { grid-template-columns: 1fr; }
    .timeline-col h3 { text-align: center; }
  }
</style>

<h1 class="section-title">Profil Analyste</h1>
<div class="section-line"></div>

<div class="profile-container">
  <div class="profile-image">
    <img src="images/photo.jpg" alt="Minan Jean-Marc Ouattara" onerror="this.style.display='none'">
  </div>
  <div class="profile-text">
    <p class="profile-title">Minan Jean-Marc OUATTARA</p>
    <p class="profile-subtitle">Data Analyst</p>
    <p>Je suis un data analyst spécialisé dans la transformation de données complexes en <strong>insights stratégiques actionnables</strong>.</p>
    <p>Fort d'une solide formation en analyse économique, j'accompagne les organisations dans leur prise de décision en identifiant les leviers de croissance et les tendances de marché cachées. Mon approche combine la rigueur statistique et la clarté visuelle pour rendre la donnée accessible à tous les niveaux de l'entreprise.</p>
    <p>Je me concentre sur la création de tableaux de bord à fort impact, le suivi d'indicateurs de performance (KPI) et l'analyse exploratoire avancée. Je maîtrise l'intégralité de la chaîne de valeur de l'analyse : de l'extraction et le nettoyage des données (SQL, Python) à la communication des résultats via des supports interactifs (Streamlit, Power BI).</p>
    <p><strong>Actuellement en Master 2 Statistiques, je recherche un stage de fin d’études pour mettre mes compétences en Business Intelligence au service de votre stratégie data.</strong></p>
    <div class="tech-stack"><strong>Expertise Data :</strong> SQL, Power BI, Python (Pandas, Plotly, Streamlit), R, Statistiques décisionnelles, Excel (VBA).</div>
  </div>
</div>

<h2 class="section-title">Analyses & Tableaux de Bord</h2>
<div class="section-line"></div>
<p style="text-align: center; margin-bottom: 40px; color: #666;">Focus sur la visualisation de données, le suivi de performance et l'interprétation métier.</p>

<div class="projects-grid">
  
  <div class="project-card">
    <h3 class="project-title">Stratégie NFL : Analyse de Performance</h3>
    <div class="project-desc">
      <strong>Dashboard interactif d'aide à la décision tactique basé sur 20 ans de données.</strong><br><br>
      Missions : Analyse des facteurs clés de succès offensif, identification des tendances historiques et création d'un outil de visualisation permettant aux décideurs d'explorer les probabilités de réussite par contexte de jeu.
    </div>
    <div class="btn-group">
      <a href="https://github.com/ouat225/the-redzone-predictor" class="btn" target="_blank">Consulter l'Analyse</a>
    </div>
    <div class="project-tools">Outils : Streamlit, Python (Pandas), Analyse de KPI.</div>
  </div>

  <div class="project-card">
    <h3 class="project-title">Observatoire Immobilier Parisien</h3>
    <div class="project-desc">
      <strong>Analyse exploratoire et visuelle du marché immobilier (10 000 logements).</strong><br><br>
      Missions : Analyse des corrélations de prix, détection des anomalies de marché et développement d'un outil interactif de segmentation pour faciliter l'estimation et la compréhension des dynamiques urbaines.
    </div>
    <div class="btn-group">
      <a href="https://github.com/ouat225/management-de-projets-digitaux" class="btn" target="_blank">Voir le Dashboard</a>
    </div>
    <div class="project-tools">Outils : Python, Pandas, Plotly, Visualisation de données.</div>
  </div>

  <div class="project-card">
    <h3 class="project-title">Visualisation de Dynamiques Simulées</h3>
    <div class="project-desc">
      <strong>Interface de pilotage pour la simulation d'écosystèmes complexes.</strong><br><br>
      Missions : Traduction de modèles mathématiques en graphiques temporels intuitifs. Création d'un tableau de bord de monitoring permettant de suivre l'évolution des populations et d'anticiper les ruptures d'équilibre.
    </div>
    <div class="btn-group">
      <a href="https://github.com/ouat225/ecosysteme-des-donnees" class="btn" target="_blank">Détails du Projet</a>
    </div>
    <div class="project-tools">Outils : NumPy, Streamlit, Reporting interactif.</div>
  </div>

</div>

<h2 class="section-title">Parcours & Expériences</h2>
<div class="section-line"></div>

<div class="background-grid">
  
  <div class="timeline-col">
    <h3>Formation</h3>
    
    <div class="timeline-item">
      <div class="timeline-date">2024 - 2026</div>
      <div class="timeline-title">Master 2 Statistiques (Prévision & Évaluation)</div>
      <div class="timeline-subtitle">Université de Reims Champagne-Ardenne</div>
    </div>
    
    <div class="timeline-item">
      <div class="timeline-date">2021 - 2024</div>
      <div class="timeline-title">Licence Économie, parcours Analyse Économique</div>
      <div class="timeline-subtitle">Université de Reims Champagne-Ardenne</div>
    </div>
  </div>

  <div class="timeline-col">
    <h3>Expérience en Analyse</h3>
    
    <div class="timeline-item">
      <div class="timeline-date">01/2024 - 03/2024</div>
      <div class="timeline-title">Analyste de Marché (Stage)</div>
      <div class="timeline-subtitle">ISLT, Troyes</div>
      <div class="timeline-desc">• Réalisation d'études de marché pour orienter la stratégie commerciale.</div>
      <div class="timeline-desc">• Conception de rapports de synthèse basés sur la veille concurrentielle.</div>
      <div class="timeline-tools">Outils : R, Python, Excel</div>
    </div>
    
    <div class="timeline-item">
      <div class="timeline-date">06/2022 - 09/2022</div>
      <div class="timeline-title">E-commerce Analyste (Stage)</div>
      <div class="timeline-subtitle">DASH, Abidjan</div>
      <div class="timeline-desc">• Analyse des comportements clients pour optimiser les performances marketing.</div>
      <div class="timeline-desc">• Mise en place et suivi de KPI pour le pilotage de la croissance digitale.</div>
      <div class="timeline-tools">Outils : SQL, Excel (Analyse BI)</div>
    </div>
    
    <div class="timeline-item">
      <div class="timeline-date">06/2020 - 08/2020</div>
      <div class="timeline-title">Stagiaire Comptabilité / Reporting</div>
      <div class="timeline-subtitle">Ambassade de Côte d'Ivoire, Addis-Abeba</div>
      <div class="timeline-desc">• Fiabilisation des bases de données et préparation des rapports financiers.</div>
      <div class="timeline-tools">Outil : Excel (Reporting)</div>
  </div>

</div>

</div>

<div class="contact-section">
  <h2 class="section-title">Discutons de vos enjeux Data</h2>
  <div class="section-line"></div>
  <p>Besoin d'un regard analytique sur vos données pour transformer vos chiffres en décisions ?</p>
  
  <div class="contact-buttons">
    <a href="mailto:ouattaramjeanmarc@gmail.com" class="btn-solid">Email</a>
    <a href="https://www.linkedin.com/in/minan-jean-marc-ouattara-809061291/" class="btn-solid" target="_blank">LinkedIn</a>
    <a href="https://github.com/ouat225" class="btn-solid" target="_blank">GitHub</a>
  </div>
</div>
