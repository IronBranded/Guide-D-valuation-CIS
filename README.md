# Guide d'Évaluation des PMEs — Contrôle CIS
### SMB CIS Controls Assessment Guide · v8.1 + IA · Bilingue FR/EN

> Outil d'évaluation de la maturité cybersécurité autonome, bilingue et gratuit pour les PME québécoises — fondé sur les 18 Contrôles CIS v8.1, la Loi 25 et le cadre PDRP.
>
> A free, standalone, bilingual cybersecurity maturity assessment guide for Québec SMBs — built on 18 CIS Controls v8.1, Law 25, and the PDRP framework.

---

![CIS Controls v8.1](https://img.shields.io/badge/Contrôle%20CIS-v8.1-0F1F3D?style=flat-square)
![AI Security](https://img.shields.io/badge/Sécurité%20IA-Extension-6C2BD9?style=flat-square)
![Loi 25](https://img.shields.io/badge/Loi%2025-Conforme-057A55?style=flat-square)
![Bilingual](https://img.shields.io/badge/Langue-FR%20%2F%20EN-1A56DB?style=flat-square)
![No dependencies](https://img.shields.io/badge/Dépendances-Aucune-718096?style=flat-square)
![Single file](https://img.shields.io/badge/Fichier%20unique-HTML-B45309?style=flat-square)

---
##  Démarrage rapide / Quick Start

Aucune installation requise.  /  No installation required.

<h3 align="center">
  <a href="https://ironbranded.github.io/Guide-PME-CIS/" target="_blank" rel="noopener noreferrer">
    🟢 ESSAYER LE GUIDE / TRY THE GUIDE 🟢
  </a>
</h3>

---

## Aperçu / Overview

Un seul fichier HTML. Aucun serveur. Aucune donnée transmise. Ouvrir dans le navigateur et commencer.

One HTML file. No server. No data transmitted. Open in a browser and start.

| | |
|---|---|
| **Domaines CIS** | 19 (Contrôles 1–18 + Extension IA) |
| **Questions** | 95 (5 par domaine) |
| **Piliers** | Protéger · Détecter · Répondre · Culture |
| **Langues** | Français · English |
| **Dépendances runtime** | Aucune / None |
| **Stockage des données** | Mémoire navigateur uniquement / Browser memory only |

---

## Couverture des Contrôles CIS v8.1 / CIS Controls Coverage

| # | Domaine (FR) | Domain (EN) | Pilier(s) |
|---|---|---|---|
| 01 | Inventaire et contrôle des actifs matériels | Inventory & Control of Enterprise Assets | 🔵 Protect |
| 02 | Inventaire et contrôle des actifs logiciels | Inventory & Control of Software Assets | 🔵 Protect |
| 03 | Protection des données | Data Protection | 🔵 Protect |
| 04 | Configuration sécurisée des actifs | Secure Configuration of Enterprise Assets | 🔵 Protect |
| 05 | Gestion des comptes | Account Management | 🔵 Protect |
| 06 | Gestion des contrôles d'accès | Access Control Management | 🔵 Protect |
| 07 | Gestion continue des vulnérabilités | Continuous Vulnerability Management | 🔵 Protect · 🟣 Detect |
| 08 | Gestion des journaux d'audit | Audit Log Management | 🟣 Detect |
| 09 | Protection des courriels et navigateurs | Email & Web Browser Protections | 🔵 Protect · 🟣 Detect |
| 10 | Défenses contre les logiciels malveillants | Malware Defenses | 🔵 Protect · 🟣 Detect |
| 11 | Récupération des données et continuité | Data Recovery & Business Continuity | 🟢 Respond |
| 12 | Gestion de l'infrastructure réseau | Network Infrastructure Management | 🔵 Protect · 🟣 Detect |
| 13 | Surveillance et défense du réseau | Network Monitoring & Defense | 🟣 Detect |
| 14 | Sensibilisation et formation en cybersécurité | Security Awareness & Skills Training | 🟡 Culture |
| 15 | Gestion des fournisseurs de services | Service Provider Management | 🔵 Protect · 🟡 Culture |
| 16 | Sécurité applicative, physique et télétravail | Application Security, Physical & Remote Work | 🔵 Protect · 🟡 Culture |
| 17 | Gestion de la réponse aux incidents | Incident Response Management | 🟢 Respond |
| 18 | Tests de pénétration et exercices offensifs | Penetration Testing | 🔵 Protect · 🟡 Culture |
| 19 ** | Sécurité de l'intelligence artificielle | Artificial Intelligence Security | 🔵 🟣 🟡 Extension |

> ** Le domaine 19 est une extension hors cadre CIS v8.1 standard, couvrant la gouvernance IA, les risques de modèles et la conformité Loi 25/Loi 64.
> Domain 19 is an extension beyond standard CIS v8.1, covering AI governance, model risks, and Law 25/Bill 64 compliance.

---

## Échelle de maturité / Maturity Scale

Chaque question est évaluée sur une échelle de 0 à 4. / Each question is scored on a 0–4 scale.

| Score | Niveau (FR) | Level (EN) | Description |
|:---:|---|---|---|
| **0** | Inexistant | Non-existent | Aucun contrôle en place / No control in place |
| **1** | Partiel | Partial | Informel ou incomplet / Informal or incomplete |
| **2** | En développement | Developing | Initié mais non systématique / Initiated but not systematic |
| **3** | Défini | Defined | Documenté et appliqué / Documented and enforced |
| **4** | Optimisé | Optimized | Mesuré et continuellement amélioré / Continuously improved |
| **S/O** | Non applicable | N/A | Exclus du calcul / Excluded from scoring |

### Calcul / Scoring

```
Score pilier (%) = Somme des scores répondus / (Nb questions répondues × 4) × 100

Pillar score (%) = Sum of answered scores / (Number of answered questions × 4) × 100
```

Les réponses S/O sont exclues du numérateur et du dénominateur. La note globale est la moyenne non pondérée des 4 piliers.

N/A answers are excluded from both numerator and denominator. The overall score is the unweighted average of all 4 pillars.

| Plage / Range | Niveau / Level |
|:---:|---|
| 0–19 % | 🔴 Initial |
| 20–39 % | 🟠 Partiel / Partial |
| 40–59 % | 🟡 En développement / Developing |
| 60–79 % | 🟢 Défini / Defined |
| 80–100 % | 🔵 Optimisé / Optimized |

---

## Fonctionnalités / Features

### Interface

- **Écran de chargement** professionnel avec progression animée et statistiques
- **Barre latérale persistante** — 19 contrôles avec indicateurs de complétion en temps réel
  - ○ Vide = non commencé · 🟡 Partiel = en cours · ✅ Complet
- **Page dédiée par contrôle** avec accordéons par question
- **Navigation Précédent / Suivant** entre les contrôles
- **Barre de progression globale** en haut de l'écran

### Profil de l'organisation / Organization Profile

- Nom, secteur d'activité, taille, infrastructure principale
- Date d'évaluation, nom de l'auditeur, numéro de référence de dossier
- Responsable de la protection des données — RPRP (Loi 25)
- Portée et périmètre de l'évaluation

### Assurance cybersécurité / Cyber Insurance

- Sélecteur Oui / Non / Inconnu (code couleur)
- Assureur/courtier · couverture · numéro de police · date de renouvellement
- Franchise · délai de notification à l'assureur
- Notes et conditions particulières de la police

### Contacts d'urgence / Emergency Contacts

- Rôles prédéfinis : TI/MSSP · Direction · Assureur cyber · Conseiller juridique
- Champs : Rôle/Titre · Téléphone d'urgence · Courriel / Email
- Ajout et suppression dynamiques de contacts

### Questions

- Accordéon par question — fermé par défaut, s'ouvre à la sélection
- Badge de niveau coloré affiché dans l'en-tête une fois répondu
- Référence CIS explicite dans chaque question (ex. `CIS 6.2`, `CIS IA-3`)
- Indicateurs visuels de pilier (points colorés) par question
- Champ de notes d'audit et preuves pour chaque question
- Option S/O disponible pour toutes les questions

### Rapport d'évaluation / Assessment Report

- Score global et niveau de maturité sur les 4 piliers
- Score par pilier avec barre de progression et niveau nommé
- **Observations clés générées automatiquement** selon les réponses :

| Badge | Condition déclenchante |
|---|---|
| 🔴 CRITIQUE / CRITICAL | MFA absent, sauvegardes non isolées, logiciels EOL sans plan de migration |
| 🟠 ÉLEVÉ / HIGH | Plan RI absent ou informel, patching non structuré, logs non centralisés |
| 🟣 LÉGAL · LOI 25 | RPRP non désigné, notifications CAI non intégrées, rétention non documentée |
| 🟡 MOYEN / MEDIUM | Formation obligatoire absente, politique d'utilisation IA manquante |
| ⚪ INFO | Pentest non réalisé, assurance absente ou inconnue, questions sans réponse |

### Impression et export / Print & Export

- **Panneau d'impression** (icône 🖨 en haut à droite) avec 3 bascules :
  - Imprimer tous les contrôles vs. la page courante uniquement
  - Inclure / exclure les notes d'audit
  - Inclure / exclure les options de réponse
- Export PDF natif via `window.print()` du navigateur
- **Export CSV** — toutes les questions, scores, niveaux et notes (BOM UTF-8 pour Excel)

### Bilingue / Bilingual

- Bascule complète **FR ↔ EN** en temps réel sans rechargement
- 95 questions dans les deux langues
- Tous les libellés, niveaux de maturité, observations et rapports entièrement traduits

---

## Références réglementaires québécoises / Québec Regulatory References

| Règlement | Portée | Domaines CIS liés |
|---|---|---|
| **Loi 25** | Protection des renseignements personnels, désignation RPRP, notification CAI (72h) | 03, 05, 15, 17, 19 |
| **BSIF / OSFI E-21** | Institutions financières | 07, 12, 17 |
| **RAMQ / MSSS** | Secteur de la santé | 03, 17 |
| **CMR** | Organismes municipaux | 04, 08, 17 |
| **Loi 64 / Bill 64** | Systèmes décisionnels automatisés (IA) | 19 |

---

## Notes techniques / Technical Notes

- **HTML/CSS/JS pur** — aucun framework, aucune dépendance npm à l'exécution
- **État en mémoire uniquement** — les réponses ne persistent pas entre les sessions ; exporter en CSV avant de fermer l'onglet
- **Google Fonts** — DM Serif Display, DM Sans, JetBrains Mono chargées via CDN au premier lancement ; dégradation gracieuse si hors ligne
- **Export CSV** — BOM UTF-8 inclus pour l'affichage correct des caractères français dans Microsoft Excel
- **Impression** — CSS `@media print` avec `print-color-adjust: exact` pour préserver les couleurs des en-têtes
- **Navigateurs supportés** — Chrome, Firefox, Edge, Safari (Internet Explorer non supporté)
---

## Feuille de route / Roadmap

- [ ] Sauvegarde locale (`localStorage`) optionnelle pour reprendre une évaluation en cours
- [ ] Export PDF côté client (html2pdf ou équivalent) sans passer par la boîte de dialogue d'impression
- [ ] Rapport HTML interactif avec graphiques radar par pilier
- [ ] Mode comparaison — deux évaluations côte à côte (avant/après)
- [ ] Questions personnalisées et domaines supplémentaires configurables

---

## Contribuer / Contributing

Les contributions sont les bienvenues. / Contributions are welcome.

---

<div align="center">
  <sub>Guide d'Évaluation des PMEs — Contrôle CIS · PME Québec · Loi 25 · CIS Controls v8.1</sub>
</div>
