# 🧮 Simulateur de Retraite Progressive – Régime Général (Salarié du privé)

[![V01 Mode Expert](https://img.shields.io/badge/V01-Mode%20Expert-blue.svg)](https://github.com/J34NMY/simulateur-retraite-regime-general/blob/main/simulateur_retraite_progressive_regime_general_expert.html)
[![Statut : en développement](https://img.shields.io/badge/statut-en%20d%C3%A9veloppement-orange.svg)]()
[![Licence CC BY-NC-SA 4.0](https://img.shields.io/badge/licence-CC%20BY--NC--SA%204.0-lightgrey.svg)](LICENSE.md)

Outil pédagogique gratuit pour estimer la retraite progressive et définitive des **salariés du régime général** (secteur privé), régime de base **CNAV** + retraite complémentaire **Agirc-Arrco**.

> ⚠️ **Outil éducatif non officiel.** Pour votre estimation officielle, consultez le simulateur M@rel sur [info-retraite.fr](https://www.info-retraite.fr).

> 🚧 **Projet en développement.** GitHub Pages n'est pas encore activé — aucune version en ligne pour le moment. Le fichier HTML fonctionne en local (téléchargement + ouverture dans un navigateur).

---

## 📂 Périmètre

Ce simulateur couvre les **salariés du régime général**. Il ne couvre **pas** :
- Les **fonctionnaires** (CPCMR, CNRACL) → voir le projet [simulateur-retraite-progressive](https://github.com/J34NMY/simulateur-retraite-progressive)
- Les **professions libérales** (CNAVPL)
- Les **travailleurs indépendants** (SSI)
- Les **régimes spéciaux** (SNCF, RATP, marins, etc.)

---

## ✨ Fonctionnalités

- **Régime de base (CNAV)** : décote/surcote, taux plein automatique à 67 ans, barème âge légal/trimestres requis par génération (Circulaire Cnav 2026-07)
- **Retraite complémentaire (Agirc-Arrco)** : points, valeur de service du point, coefficient d'anticipation propre (distinct de la décote CNAV)
- **Retraite progressive** : éligibilité (60 ans + 150 trimestres), revenu combiné pendant la RP (salaire réduit + fraction de pension base et complémentaire), alerte sur le seuil de validation des trimestres
- **Comparateur de quotités** (40/50/60/70/80%) avec projection de la pension définitive par quotité
- **Pension à la retraite définitive** : projection après la RP, avec trimestres et points accumulés pendant la période
- **Analyse Rachat** (Versement Pour La Retraite) : barème officiel CNAV par âge/revenu/option, comparaison avec un placement (Livret A, PEA)
- 100% local : aucune donnée transmise, fonctionne hors ligne une fois la page chargée

---

## ⚡ Utilisation

1. Téléchargez `simulateur_retraite_progressive_regime_general_expert.html`
2. Ouvrez-le dans votre navigateur (double-clic ou glisser-déposer)
3. Renseignez vos données depuis votre **relevé de carrière**, disponible sur [info-retraite.fr](https://www.info-retraite.fr)
4. Consultez le [Mode d'emploi](mode-emploi.html) pour un guide détaillé

---

## 🗺️ Feuille de route

- [x] Moteur de calcul CNAV (base) — vérifié contre l'exemple officiel de la Circulaire Cnav 2026-07
- [x] Retraite complémentaire Agirc-Arrco
- [x] Retraite progressive (éligibilité, revenu combiné, comparateur, projection définitive)
- [x] Analyse Rachat + comparaison placement
- [x] Mode d'emploi
- [ ] Mode Guidé (assistant pas à pas)
- [ ] Publication en ligne (GitHub Pages)

---

## 🔗 Liens officiels

- [info-retraite.fr](https://www.info-retraite.fr) — Simulateur M@rel (officiel), relevé de carrière
- [lassuranceretraite.fr](https://www.lassuranceretraite.fr) — Assurance Retraite (régime de base)
- [agirc-arrco.fr](https://www.agirc-arrco.fr) — Retraite complémentaire

---

*Développé bénévolement par J34NMY avec l'assistance de Claude (Anthropic) · Licence CC BY-NC-SA 4.0 · Juillet 2026*
