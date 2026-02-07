<p align="center">
  <img src="docs/images/Palks_Studio.png" alt="Palks Studio" width="600">
</p>

> 🇫🇷 Français | [🇬🇧 English](./README.md)

![Éditeur](https://img.shields.io/badge/Éditeur-VS%20Code-blue.svg)
![Python](https://img.shields.io/badge/Python-3.x-yellow.svg)
![Plateforme](https://img.shields.io/badge/OS-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey.svg)
![License](https://img.shields.io/badge/License-LICENSE.md-lightgreen.svg)

<p align="center">
  <a href="https://palks.gumroad.com/" target="_blank">
    <img src="https://img.shields.io/badge/Télécharger%20sur-Gumroad-orange?style=for-the-badge" alt="Télécharger sur Gumroad">
  </a>
</p>

# Pack de Formatage VS Code (Version Lite)

**Version 1.1 — Démo publique**

Un aperçu léger et **en lecture seule** du Pack de Formatage VS Code par **Palks Studio**.

Cette version Lite fournit un environnement **passif et non destructif**,  
conçu pour présenter la philosophie et la structure de la version complète,  
sans modifier aucun fichier.

Aucun formatage.  
Aucun nettoyage.  
Aucune automatisation.

---

## Structure (Version publique)

```
vcsode_pack_formatage_lite_v1.1/
├── README.md                 → Documentation publique de la version Lite
│                             (périmètre limité, aucune modification de fichiers)
│
├── LICENCE.md                → LICENCE.md — Conditions d’utilisation et cadre légal
│
├── version_publique/
│   └── .vscode/
│       ├── settings.json     → Réglages passifs de l’éditeur
│       │                       - UTF-8
│       │                       - fins de ligne LF
│       │                       - indentation visuelle (4 espaces)
│       │                       - affichage des marges
│       │                       - aucun formatage automatique
│       │
│       ├── keybindings.json  → Raccourci unique :
│       │                     Alt + M → afficher / masquer la minimap
│       │
│       └── tasks.json        → Tâche VS Code (lecture seule) :
│                               - Margin detection (read-only)
│                               - analyse des marges
│                               - aucun fichier modifié
│
├── example_structure.txt     → Aperçu de l’arborescence et des fonctionnalités
│                             de la version complète (Pro)
│
└── docs/
    └── images/
        └── Palks_Studio.png  → Visuel propriétaire (branding)
```


Les fichiers `.mp4` de ce dossier (convert_lf.mp4, indent_clean.mp4, etc.) sont volontairement inclus dans la version Lite — ce sont de vraies démonstrations issues du pack complet.

---

## Ce que fait cette version Lite

- Applique des **réglages passifs de l’éditeur** pour garantir cohérence et lisibilité
- Assure notamment :  
  - un encodage **UTF-8**  
  - des fins de ligne en **LF**  
  - une indentation visuelle (4 espaces)  
  - l’affichage des espaces significatifs  
- Fournit une **tâche de détection des marges en lecture seule**  
- Inclut un raccourci clavier minimal pour le confort de navigation

Cette version est destinée **uniquement à l’évaluation et à la démonstration**.

---

## Ce que cette version Lite ne fait PAS

- Aucun formatage de fichiers  
- Aucun nettoyage des marges  
- Aucune conversion des fins de ligne  
- Aucune sauvegarde automatique  
- Aucune action automatique à l’enregistrement  
- Aucune transformation à l’échelle du projet

Toute modification de fichiers est **réservée exclusivement à la version Pro**.

---

## Fonctionnalités incluses

### Configuration passive de l’éditeur

Le fichier `settings.json` applique des règles neutres et prévisibles :  

- Aucun formatage automatique  
- Aucun formateur imposé  
- Aucune automatisation spécifique par langage  
- Comportement identique sous Windows, macOS et Linux

Ces réglages sont appliqués **uniquement au dossier du projet**.

---

### Détection des marges (lecture seule)

Une seule tâche VS Code est disponible :  

Terminal → Exécuter une tâche… → Détection des marges (lecture seule)

Cette tâche :  

- Analyse les fichiers à la recherche de problèmes de marges et d’espaces  
- Affiche les résultats dans le terminal  
- **Ne modifie jamais les fichiers**

Elle permet **d’observer** les problèmes de formatage,  
sans chercher à les corriger.

---

### Raccourci clavier

- `Alt + M` → Afficher / masquer la minimap

Aucun raccourci de réindentation ou de formatage  
n’est inclus dans cette version Lite.

---

## Structure du pack

La version Lite contient une configuration publique minimale :  

- `.vscode/`  
  - `settings.json` — réglages passifs de l’éditeur  
  - `keybindings.json` — bascule de la minimap uniquement  
  - `tasks.json` — détection des marges (lecture seule)  
- `example_structure.txt`  
  - aperçu de la structure et des fonctionnalités de la version Pro  
- `docs/images/`  
  - visuel propriétaire Palks Studio

---

## À propos de la version Pro

La **version Pro** inclut notamment :  

- le nettoyage des marges (`clean.py`)  
- la normalisation des fins de ligne (`convert.py`)  
- l’analyse et le reporting détaillés (`space.py`)  
- les sauvegardes automatiques à l’enregistrement (`backup.py`)  
- plusieurs modes d’exécution  
  - (global / fichier actif / sélection personnalisée)  
- une documentation complète et des exemples réels d’utilisation

La version Lite est volontairement limitée  
afin de maintenir une frontière claire et honnête.

Cela garantit une expérience d’évaluation  
transparente et prévisible.

---

## Compatibilité

- Visual Studio Code (versions récentes)  
- Windows, macOS, Linux  
- Aucune extension payante requise  
- Aucun service externe utilisé  
- Fonctionne entièrement hors ligne

---

**Palks Studio — Version 1.1**  
Compatible avec Visual Studio Code (Prettier désactivé par défaut).

© Palks Studio — voir LICENSE.md  
- https://palks-studio.com
