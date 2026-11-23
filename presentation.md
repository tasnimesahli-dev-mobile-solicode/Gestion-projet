---
marp: true
theme: default
size: 16:9
paginate: true
---

<style>
section {
  box-sizing: border-box;
  padding: 48px 64px;
  background: #FFFFFF;
  color: #222222;
  font-family: "Aptos", "Trebuchet MS", sans-serif;
  font-size: 21px;
  line-height: 1.35;
}

section h1 {
  margin: 0 0 24px;
  padding-bottom: 12px;
  border-bottom: 5px solid #F9A826;
  color: #222222;
  font-family: Georgia, serif;
  font-size: 38px;
}

section h2 {
  color: #222222;
  font-size: 25px;
}

section p,
section ul,
section ol {
  margin-top: 12px;
  margin-bottom: 12px;
}

section li {
  margin: 8px 0;
}

section.cover {
  justify-content: center;
  background: linear-gradient(90deg, #F9A826 0 18px, #FFFFFF 18px 100%);
}

section.cover h1 {
  margin: 0 0 10px 38px;
  padding: 0;
  border: 0;
  font-size: 48px;
}

section.cover h2 {
  margin: 0 0 28px 40px;
  font-size: 26px;
  font-weight: normal;
}

.logo-row {
  display: flex;
  align-items: center;
  gap: 22px;
  margin: 0 0 30px 40px;
}

.logo-frame {
  box-sizing: border-box;
  display: flex;
  width: 220px;
  height: 100px;
  align-items: center;
  justify-content: center;
  padding: 12px;
  border: 1px solid #E5E5E5;
  border-bottom: 4px solid #F9A826;
  background: #FFFFFF;
}

.logo-frame img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}

.cover-meta {
  display: flex;
  gap: 36px;
  margin: 20px 0 0 40px;
  font-size: 19px;
}

.cover-meta p {
  margin: 0;
}

section.plan-slide ol {
  display: grid;
  grid-template-columns: 1fr 1fr;
  column-gap: 48px;
  padding-left: 32px;
}

section.plan-slide li {
  padding: 8px 0;
}

.intro-list {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 12px 24px;
  padding: 0;
  list-style: none;
}

.intro-list li {
  margin: 0;
  padding: 14px 18px;
  border-left: 5px solid #F9A826;
  background: #FFF4CC;
}

.question-list {
  padding: 8px 0 8px 30px;
}

.definition-band {
  margin: 0 0 22px;
  padding: 14px 18px;
  border-left: 6px solid #F9A826;
  background: #FFF4CC;
  font-size: 18px;
}

.daily-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 16px;
  align-items: stretch;
}

.daily-card {
  box-sizing: border-box;
  min-width: 0;
  min-height: 250px;
  padding: 18px;
  border: 1px solid #E5E5E5;
  border-top: 7px solid #F9A826;
  background: #FFF4CC;
  overflow-wrap: break-word;
}

.daily-card:nth-child(2) {
  border-top-color: #222222;
  background: #F7F7F7;
}

.daily-card:nth-child(3) {
  border-top-color: #F9A826;
  background: #FFFFFF;
}

.daily-card h2 {
  margin: 0 0 16px;
  font-size: 19px;
  line-height: 1.2;
}

.daily-card p {
  margin: 0;
  font-size: 18px;
  line-height: 1.4;
}

.blocker-list {
  margin: 20px 0;
  padding: 18px 24px 18px 44px;
  background: #FFF4CC;
  border-left: 6px solid #F9A826;
}

section.thanks {
  justify-content: center;
  text-align: center;
}

section.thanks h1 {
  align-self: stretch;
}

section.thanks h2 {
  margin-top: 70px;
  font-size: 34px;
}
</style>

<!-- _class: cover -->

<div class="logo-row">
  <div class="logo-frame"><img src="./ofppt-logo.png" alt="Logo OFPPT"></div>
  <div class="logo-frame"><img src="./solicode-logo.png" alt="Logo Solicode"></div>
</div>

# Gestion de projets

## Daily Scrum

<div class="cover-meta">
  <p><strong>Présenté par :</strong> Tasnime Sahli</p>
  <p><strong>Encadré par :</strong> ES-Sarraj Fouad</p>
</div>

---

<!-- _class: plan-slide -->

# Plan de la présentation

1. Introduction
2. Problématique
3. Solution
4. Projet Labs
5. Projet Blog
6. Projet Fil Rouge
7. Projet Technique
8. Veille Technologique
9. Où suis-je bloquée ?
10. Conclusion

---

# Introduction

Cette présentation montre mon évolution et l'avancement de mes activités.

<ul class="intro-list">
  <li>Les Labs</li>
  <li>Le projet Blog</li>
  <li>Le projet Fil Rouge</li>
  <li>Le projet Technique</li>
  <li>La veille technologique</li>
</ul>

---

# Problématique

Je travaille sur plusieurs projets et activités en même temps. Il est parfois difficile de savoir :

<ul class="question-list">
  <li>Quel travail a été réalisé ?</li>
  <li>Sur quel projet dois-je travailler maintenant ?</li>
  <li>Quelles sont les prochaines étapes ?</li>
</ul>

---

# Solution

Faire un suivi régulier de chaque projet pour connaître son avancement.

Répondre à trois questions :

1. Qu'est-ce que j'ai fait hier ?
2. Qu'est-ce que je vais faire aujourd'hui ?
3. Est-ce que je rencontre des obstacles qui m'empêchent d'avancer ?

---

# Projet Labs

<div class="definition-band"><strong>Définition :</strong> Les Labs sont des activités pratiques pour découvrir et tester de nouvelles technologies et compétences.</div>

<div class="daily-grid">
  <div class="daily-card">
    <h2>Dernière chose réalisée</h2>
    <p>Lab PHP</p>
  </div>
  <div class="daily-card">
    <h2>Travail en cours</h2>
    <p>Lab POO.</p>
  </div>
  <div class="daily-card">
    <h2>Prochaines étapes</h2>
    <p> Lab Architecture.</p>
  </div>
</div>

---

# Projet Blog

<div class="definition-band"><strong>Définition :</strong> Le projet Blog permet d'appliquer les compétences acquises pendant la formation.</div>

<div class="daily-grid">
  <div class="daily-card">
    <h2>Dernière chose réalisée</h2>
    <p>Réalisation du rapport du projet Blog.</p>
  </div>
  <div class="daily-card">
    <h2>Travail en cours</h2>
    <p>Préparation de la présentation du projet.</p>
  </div>
  <div class="daily-card">
    <h2>Prochaines étapes</h2>
    <p>Finaliser la présentation.</p>
  </div>
</div>

---

# Projet Fil Rouge

<div class="definition-band"><strong>Définition :</strong> Le projet Fil Rouge permet de mettre en pratique les compétences acquises pendant la formation.</div>

<div class="daily-grid">
  <div class="daily-card">
    <h2>Dernière chose réalisée</h2>
    <p>Préparation du plan du rapport Fil Rouge.</p>
  </div>
  <div class="daily-card">
    <h2>Travail en cours</h2>
    <p>Organisation du contenu du rapport.</p>
  </div>
  <div class="daily-card">
    <h2>Prochaines étapes</h2>
    <p>Commencer la rédaction du rapport.</p>
  </div>
</div>

---

# Projet Technique

<div class="definition-band"><strong>Définition :</strong> Le projet Technique permet de tester les compétences avec des exercices et des développements pratiques.</div>

<div class="daily-grid">
  <div class="daily-card">
    <h2>Dernière chose réalisée</h2>
    <p>Live Coding N°2 / Sprint 3 et création de la page Admin avec DAO, Service et architecture 3 tiers.</p>
  </div>
  <div class="daily-card">
    <h2>Travail en cours</h2>
    <p>Préparation du Sprint Backlog de la page Détail.</p>
  </div>
  <div class="daily-card">
    <h2>Prochaines étapes</h2>
    <p>Développer la page Détail.</p>
  </div>
</div>

---

# Veille Technologique

<div class="definition-band"><strong>Définition :</strong> La veille technologique consiste à rechercher de nouvelles technologies et à suivre leurs évolutions.</div>

<div class="daily-grid">
  <div class="daily-card">
    <h2>Dernière chose réalisée</h2>
    <p>Définir la liste des sujets de veille.</p>
  </div>
  <div class="daily-card">
    <h2>Travail en cours</h2>
    <p>Réaliser une veille sur jira.</p>
  </div>
  <div class="daily-card">
    <h2>Prochaines étapes</h2>
    <p>Préparer et présenter les résultats.</p>
  </div>
</div>

---

# Où suis-je bloquée ?

<ul class="blocker-list">
  <li>Je travaille sur plusieurs activités en parallèle.</li>
  <li>Je dois organiser les priorités entre les différents projets.</li>
  <li>Je dois identifier clairement les prochaines tâches à réaliser.</li>
</ul>

### Solution

Organiser mon travail et suivre régulièrement l'avancement de chaque projet.

---

<!-- _class: thanks -->

# Conclusion

- Suivre l'avancement de mes projets.
- Organiser mes tâches.
- Identifier les obstacles.
- Préparer les prochaines étapes.

## Merci pour votre attention !