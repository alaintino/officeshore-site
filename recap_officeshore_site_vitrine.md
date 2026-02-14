# Projet Site Vitrine — Officeshore

## Récapitulatif complet du projet

*Document mis à jour le 14/02/2026 (v2) — Synthèse de l'ensemble des échanges*

---

## 1. Contexte et positionnement

### La société

**Officeshore** est une société de conseil (SASU, basée en Île-de-France, intervention France entière en remote) spécialisée dans la structuration et la gestion du **Shadow IT** des entreprises — c'est-à-dire tous les développements bureautiques (VBA, Excel, Access, etc.) qui font tourner des processus métier critiques sans être dans le périmètre de la DSI.

### Le nom retenu

- **Officeshore** (domaine : officeshore.com) a été préféré à Proximdev (proximdev.com également détenu)
- Jeu de mots malin : offshore + Office → connivence avec la cible qui connaît le terme Shadow IT
- Fonctionne en français et en anglais

### Le slogan

> **Enlight your Shadow IT**

Cohérence parfaite avec le positionnement : "shadow" (caché) → "enlight" (éclairer, structurer).

### La cible

Tout type d'entreprise ayant des développements/macros VBA, outils Excel et bases Access non gérés par la DSI. Pas de restriction sectorielle, mais expérience forte dans : Énergie, Finance, Pharma, Industrie, Distribution.

### Ton de communication

- Vouvoiement (corporate, rassurant)
- "Nous" (pas "je")
- Direct, pragmatique, sans jargon inutile

---

## 2. Identité visuelle

### Logo

Concept retenu : **ampoule stylisée** (symbole "Enlight") avec le O de Officeshore dans le filament.

**Kit logo livré (4 fichiers SVG) :**

| Fichier | Usage |
|---------|-------|
| `officeshore_logo_full.svg` | Version complète avec slogan (documents, présentations) |
| `officeshore_logo_header.svg` | Sans slogan (header du site) |
| `officeshore_icon.svg` | Icône seule (favicon, réseaux sociaux) |
| `officeshore_logo_white.svg` | Version monochrome blanche (fonds sombres, footer) |

### Charte couleurs

| Élément | Hex | Usage |
|---------|-----|-------|
| Bleu principal | `#1E3A5F` | Titres, éléments forts |
| Bleu secondaire | `#3D5A80` | Sous-titres, accents |
| Or/Jaune (dégradé) | `#FFD700` → `#FF9500` | CTA, mise en avant, énergie |
| Or texte | `#FFB800` | Texte doré (logo, accents) |
| Gris texte | `#6B7280` | Corps de texte |
| Bleu clair fond | `#E8EEF4` | Arrière-plans clairs |
| Gris fond | `#F3F4F6` | Sections alternées |

### Typographies

- **Titres** : Space Grotesk (600-700)
- **Corps** : DM Sans (400-600)

---

## 3. Architecture du site

### Structure des pages

```
index.html (page unique, single-page avec ancres)
├── Hero (slogan + CTA)
├── Problèmes ("Votre Shadow IT vous échappe ?")
├── Services (7 services)
├── Technologies (6 catégories) ← NOUVEAU
├── Pourquoi nous (3 arguments + chiffres)
├── Clients (références)
├── Contact (formulaire)
└── Footer

mentions-legales.html (page séparée)
```

### Navigation

```
Services | Technologies | Pourquoi nous | Contact
```

---

## 4. Contenu validé — Section par section

### 4.1. Hero

- **Badge** : Shadow IT Management
- **Titre** : Enlight your Shadow IT
- **Sous-titre** : "Vos macros Excel et bases Access font tourner votre activité. Nous les maintenons, les sécurisons et les faisons évoluer."
- **CTA primaire** : Demander un audit gratuit
- **CTA secondaire** : Découvrir nos services
- **Éléments flottants** (7 badges animés autour de l'ampoule) :
  - Excel / VBA (vert `#107C41`)
  - Access (rouge `#A4373A`)
  - VBA Macros (bleu `#185ABD`)
  - Office 365 (orange `#D83B01`)
  - Python (bleu `#3776AB`)
  - SQL Server (rouge `#CC2927`)
  - Azure (bleu `#0078D4`)

### 4.2. Section "Le problème"

**Titre** : Votre Shadow IT vous échappe ?

5 pain points identifiés :
1. La macro critique développée par un collaborateur parti depuis 3 ans
2. Le fichier Excel de reporting que personne n'ose toucher
3. La DSI qui ne veut/peut pas maintenir les outils Access
4. Un bug qui bloque la production sans personne pour intervenir
5. Une migration Office qui approche avec risque de casse

### 4.3. Section Services (6 services)

| # | Service | Tagline | Détails clés |
|---|---------|---------|-------------|
| 1 | **Exploitation & Maintenance** | Vos outils tournent, on s'en occupe | Rapports d'exploitation, corrections/évolutions, point mensuel |
| 2 | **AlloMacro** | Intervention rapide sur vos bugs | Diagnostic 24-48h, remote ou sur site, facturation transparente |
| 3 | **Création & Structuration** | Des outils sur mesure, bien organisés | Automatisation process, cartographie existant, prototype fonctionnel, documentation technique |
| 4 | **Migration Office** | Changement de version sans casse | Audit compatibilité, plan remédiation, tests post-migration |
| 5 | **Formation** | Montez en compétences | Intra-entreprise, sur vos fichiers, individuel ou groupe |
| 6 | **Trajectoire Web** | Vers des applications modernes | Analyse fonctionnelle, dev itératif Python/Django, cloud |

### 4.4. Section Technologies (NOUVEAU)

6 catégories avec badges colorés aux couleurs officielles de chaque produit :

| Catégorie | Technologies |
|-----------|-------------|
| **Microsoft Office** | Excel, VBA, Access, Office 365, PowerPoint, Word |
| **Bases de données** | SQL Server, T-SQL, Oracle, Access DB, PostgreSQL |
| **Langages & Scripting** | Python, Django, VBA, PowerShell |
| **BI & Reporting** | Power BI, Power Query, Tableau, Business Objects |
| **Automatisation** | UiPath, SSIS, SSAS, Power Automate |
| **Cloud & ERP** | Azure, SAP, SharePoint, Microsoft 365 |

### 4.5. Section "Pourquoi Officeshore ?"

**Sous-titre** : Le Shadow IT est partout. Nous sommes là pour l'éclairer.

3 arguments :
1. **20 ans d'expérience terrain** — Salles de trading, directions financières, équipes marketing, services réglementaires. Compréhension métier, pas seulement technique.
2. **Un interlocuteur, pas un dispositif** — Pas de comité de pilotage, pas de reporting à rallonge. Vous parlez directement à celui qui met les mains dans le code.
3. **Pragmatisme** — On maintient ce qui marche, on fait évoluer ce qui doit l'être, on migre quand c'est le bon moment — pas avant.

**Chiffres clés :**
- 20+ années d'expérience
- 15+ clients grands comptes
- 5 secteurs couverts (Énergie, Finance, Pharma, Industrie, Distribution)

### 4.6. Section Clients

Références : Dalkia, EDF, AXA XL, Pierre Fabre, Sony Pictures, Coca-Cola, Bosch, Nestlé, Reebok

**Logos** :
- PNG existants : AXA, Coca-Cola, Bosch, Reebok
- SVG texte stylisés : Dalkia, EDF, Pierre Fabre, Sony Pictures, Nestlé (couleurs de marque)

### 4.7. Section Contact

**Intro** : "Une macro qui plante ? Une base Access à reprendre ? Un projet de structuration ? Décrivez-nous votre situation, nous vous répondons sous 24-48h."

**Formulaire :**

| Champ | Type | Obligatoire |
|-------|------|-------------|
| Nom | Texte | Oui |
| Entreprise | Texte | Non |
| Email | Email | Oui |
| Téléphone | Texte | Non |
| Sujet | Liste déroulante | Oui |
| Message | Zone de texte | Oui |

**Options du sujet** : Demande d'audit gratuit, Dépannage urgent (AlloMacro), Maintenance/Exploitation, Nouveau développement, Migration Office, Formation, Trajectoire Web, Autre

**Coordonnées** : Basé en Île-de-France — Intervention France entière en remote

### 4.8. Mentions légales (page séparée)

Structure standard : Éditeur, Hébergement, Propriété intellectuelle, Données personnelles (RGPD), Cookies.
Placeholders à remplir : raison sociale SASU, capital, adresse, SIRET, RCS, nom hébergeur.

---

## 5. Choix techniques

### Stack

- **Site statique** : HTML/CSS/JS unique (tout en un seul fichier `index.html`)
- **Fonts** : Google Fonts (DM Sans, Space Grotesk)
- **Animations** : CSS (scroll reveal, éléments flottants, transitions)
- **Responsive** : Mobile, tablette, desktop
- **Formulaire** : Web3Forms (intégré)

### Hébergement

- **GitHub Pages** (choix actuel) — déploiement via git push
- Repo : github.com/alaintino/officeshore-site

### SEO

- Balises meta (title, description)
- Structure sémantique HTML5
- Performance optimisée (pas de dépendances JS lourdes)

---

## 6. Livrables produits

| Fichier | Description | Statut |
|---------|-------------|--------|
| `index.html` | Page principale complète | ✅ Livré + mis à jour |
| `mentions-legales.html` | Mentions légales (avec placeholders) | ✅ Livré |
| `officeshore_logo_full.svg` | Logo complet avec slogan | ✅ Livré |
| `officeshore_logo_header.svg` | Logo sans slogan (header) | ✅ Livré |
| `officeshore_icon.svg` | Icône seule (favicon) | ✅ Livré |
| `officeshore_logo_white.svg` | Logo blanc (footer/fonds sombres) | ✅ Livré |

---

## 7. Historique des modifications

### Version initiale (conversation "Formaliser la création du site vitrine")

1. Définition du positionnement et de la cible
2. Choix du nom Officeshore (vs Proximdev)
3. Validation du slogan "Enlight your Shadow IT"
4. Architecture des pages et contenu validé section par section
5. Création du kit logo (4 variantes SVG)
6. Définition de la charte couleurs
7. Développement du site complet (index.html + mentions-legales.html)
8. Déploiement sur GitHub Pages

### Version 05/02/2026

9. **Ajout de 3 éléments flottants** dans le hero (Office 365, Python, SQL Server) → total 6
10. **Nouvelle section "Nos technologies"** avec 6 catégories et badges colorés
11. **Ajout du lien "Technologies"** dans la navigation
12. **Débogage positionnement** des éléments flottants (problème overflow/position absolute)

### Version 14/02/2026

13. **Migration hébergement** : Netlify → GitHub Pages
14. **Simplification bloc "Création & Structuration"** : retrait "Outils de pricing et calcul" et "Bases de suivi et reporting" (passage de 7 à 6 services)
15. **Formulaire** : intégration Web3Forms
16. **Ajout Azure** dans les éléments flottants du hero → total 7 badges
17. **Correction logos clients** : remplacement des 5 logos manquants (Dalkia, EDF, Pierre Fabre, Sony Pictures, Nestlé) par des SVG texte stylisés

---

## 8. Points en suspens / Prochaines étapes

### À faire

- [x] **Formulaire** : Connecté à Web3Forms
- [x] **Éléments flottants hero** : 7 badges positionnés (Azure ajouté)
- [x] **Logos clients** : 5 logos manquants corrigés (SVG texte)
- [ ] **Favicon** : Convertir `officeshore_icon.svg` en favicon.ico et l'intégrer
- [ ] **Mentions légales** : Remplacer les placeholders par les vraies infos (SASU, SIRET, etc.)
- [ ] **Email** : Créer contact@officeshore.com

### Évolutions possibles (phase 2)

- [ ] Page dédiée AlloMacro avec formulaire d'urgence
- [ ] Cas clients anonymisés (3-4 exemples : secteur, problème, solution, résultat)
- [ ] Blog / Ressources (articles sur le Shadow IT, bonnes pratiques)
- [ ] Calendly / prise de RDV en ligne
- [ ] Tarification (afficher ou non — actuellement "devis sur demande")
- [ ] Google Analytics / Plausible Analytics

### Décisions non prises

- **Téléphone** : Afficher publiquement ou uniquement après premier contact ?
- **Calendly** : Intégrer un lien de prise de RDV directe ?
- **Tarification** : Afficher des indications de prix / forfaits / TJM ?
- **Cas clients** : Ajouter des mini-exemples concrets sous chaque service ?

---

## 9. Accès et liens

| Ressource | Lien |
|-----------|------|
| Conversation principale | [Formaliser la création du site vitrine](https://claude.ai/chat/e46fffd5-3521-496f-9acc-dfd9fcad22f9) |
| Domaine | officeshore.com |
| Hébergement | GitHub Pages (github.com/alaintino/officeshore-site) |
| Source du positionnement | Fichier `Verbatim_Officeshore.xlsx` (uploadé dans la conversation initiale) |
