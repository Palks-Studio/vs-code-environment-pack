<p align="center">
  <img src="docs/images/Palks_Studio.png" alt="Palks Studio" width="600">
</p>

> 🇫🇷 Français | [🇬🇧 English](./README.md)

![Éditeur](https://img.shields.io/badge/Éditeur-VS%20Code-blue.svg)
![Python](https://img.shields.io/badge/Python-3.x-yellow.svg)
![Plateforme](https://img.shields.io/badge/OS-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey.svg)
![Licence](https://img.shields.io/badge/Licence-LICENCE.txt-lightgreen.svg)

<p align="center">
  <a href="https://palks.gumroad.com/" target="_blank">
    <img src="https://img.shields.io/badge/Télécharger%20sur-Gumroad-orange?style=for-the-badge" alt="Télécharger sur Gumroad">
  </a>
  &nbsp;&nbsp;
  <a href="http://palks-studio.itch.io" target="_blank">
    <img src="https://img.shields.io/badge/Disponible%20sur-Itch.io-blue?style=for-the-badge" alt="Disponible sur Itch.io">
  </a>
  &nbsp;&nbsp;
  <a href="https://ko-fi.com/palksstudio" target="_blank">
    <img src="https://img.shields.io/badge/Acheter%20sur-Ko%E2%80%93fi-ff5f5f?style=for-the-badge" alt="Acheter sur Ko-fi">
  </a>
</p>

# VS Code – Pack de Formatage (Version Lite)

---

### Version 1.1 – Octobre 2025

**Version précédente** 1.0 (Octobre 2025) — Première démonstration publique sur GitHub, remplacée depuis par cette version unifiée et autonome.
Cette mise à jour unifie la documentation française et anglaise, supprime toutes les traces Git et garantit une structure totalement autonome.
Les anciennes versions de démonstration sur GitHub ont été nettoyées et remplacées par cette version vérifiée et unifiée.

---

Une configuration propre et prête à l’emploi pour Visual Studio Code, qui garde tes fichiers cohérents, correctement indentés et organisés — sans dépendre de Prettier, d’extensions externes ou de scripts personnalisés par projet.

Ce pack contient la version publique de démonstration.
La version complète (avec scripts prêts à l’emploi : clean.py, convert.py, space.py, tâches automatisées, guide d’installation, démonstrations…) est disponible sur Gumroad, Itch.io ou Ko-Fi.

## Ce que fait ce pack

- Maintient automatiquement ton code propre, aligné et cohérent  
- Fonctionne avec Python, HTML, CSS, JS et JSON  
- Normalise l’indentation, les marges, les fins de ligne (CRLF → LF) et l’encodage UTF-8  

- Ajoute des raccourcis et tâches utiles dans VS Code :  

  - **Ctrl + A** → sélectionne tout le fichier avant exécution  
  - **Alt + R** → réindente instantanément le texte sélectionné  
  - **Alt + M** → affiche ou masque la mini-carte  
  - **Formatage automatique optionnel** (Python uniquement : autopep8 + nettoyage des marges)

---

## Structure (Version publique)

```
VSCode_Pack_Formatage/ (Version Lite)
├── README_FR.md                 ← Documentation principale (publique)
├── LICENCE.txt                  ← Licence propriétaire (Palks Studio)
├── version_publique/
│   ├── .vscode/
│   │   ├── settings.json        ← Exemple minimal (UTF-8, LF, marges visibles)
│   │   ├── tasks.json           ← Structure uniquement (sans scripts internes)
│   │   ├── keybindings.json     ← Raccourcis Alt+R et Alt+M
│   │   └── launch.json          ← Optionnel : exécuter le fichier Python actif
│   └── exemple_structure.txt    ← Arborescence complète du pack commercial
│
└── docs/
    ├── images/
    │   └── Palks_Studio.png      ← Image propriétaire (Palks Studio)
    └── exemples/                 ← (Optionnel) Avant / Après détaillés de formatage
        ├── avant.py              ← Versions sales / déstructurées
        ├── apres.py              ← Versions propres générées par le pack
        ├── convert_lf.mp4        ← Fichiers CRLF reconvertis en LF automatiquement
        ├── indent_clean.mp4      ← Fichiers avec indentation/marges cassées + auto-correction instantanée
        ├── indent_python.mp4     ← Fichier Python mal indenté + correction automatique
        └── space_clean.mp4       ← Fichier volontairement désaligné + analyse des marges + auto-correction instantanée
```


Les fichiers `.mp4` présents dans ce dossier (convert_lf.mp4, indent_clean.mp4, etc.) sont volontairement inclus dans la version Lite : ce sont des démonstrations réelles du pack complet, pour montrer ce qu’il est capable de faire.

---

## Non inclus dans cette version (réservé à la version complète)

- `.vscode/extensions.json` — désactivation locale d’extensions (Prettier / RunOnSave)  
- `settings.json` — version complète avec toutes les règles d’édition  
- `keybindings.json` — ensemble complet des raccourcis  
- `tasks.json` — tâches reliées aux scripts du pack  
- `launch.json` — profils complets de débogage  
- `clean.py` — nettoyage global du projet  
- `convert.py` — conversion CRLF → LF dans tout l’espace de travail  
- `space.py` — détection de marges ou lignes superflues  
- `INSTALL.md` — guide d’installation et d’utilisation  
- `README_COMMERCIAL.md` — présentation du produit  
- `docs/README_TECHNIQUE.md` — notes techniques / maintenance  
- Archives de distribution (`*.zip`, `*.tar.*`)

---

## Utilisation rapide (Version d’aperçu)

1. Extrait l’archive ZIP

2. Copie le dossier `.vscode/` depuis `version_publique/` dans le projet de ton choix

3. Ouvre le projet dans VS Code → les réglages de base sont actifs immédiatement

---

## Ce que tu obtiens dans la version complète

- Scripts entièrement opérationnels :  

  - `clean.py` → nettoie tous les fichiers (supprime les marges inutiles + supprime les lignes vides uniquement à partir de 3)  
  - `convert.py` → convertit tous les CRLF en LF dans le projet  
  - `space.py` → analyse en lecture seule (détecte marges inutiles, tabulations, lignes vides — sans modifier les fichiers)  

- Tâches VS Code configurées (prêtes à l’emploi)  
- Installation en moins de 30 secondes  
- Documentation complète : INSTALL, README technique, README commercial  
- Exemples avant/après, vidéos de démonstration, support Discord

**Version complète disponible ici**  
- Gumroad : https://palks.gumroad.com  
- Itch.io : http://palks-studio.itch.io  
- Ko-fi : https://ko-fi.com/palksstudio

### Important — Comportement des scripts (version complète uniquement)

Les scripts de formatage (`clean.py`, `convert.py`, `space.py`) ne modifient pas seulement le fichier ouvert dans l’éditeur, mais peuvent traiter l’ensemble des fichiers présents à la racine du projet, pour les extensions suivantes :

| Script       | Action principale                                                           |
| ------------ | --------------------------------------------------------------------------- |
| `convert.py` | Convertit toutes les fins de ligne en **LF (Unix)**                         |
| `space.py`   | Analyse les fichiers et détecte les **marges inutiles**          |
| `clean.py`   | Supprime automatiquement les **marges superflues et lignes vides inutiles** |

Avant toute modification, un dossier `_backups/` est créé pour sauvegarder les fichiers d’origine.

**À propos du formatage Python**
Le formatage automatique Python via autopep8 ne fonctionne que si tu exécutes la tâche correspondante dans VS Code (Menu “Exécuter une tâche…”).
Cette action ne s’applique qu’au fichier Python actuellement ouvert, jamais à l’ensemble du projet.

**Reindentation manuelle (Ctrl + A puis Ctrl + R)**
Applique une réindentation uniquement sur le fichier actif (`HTML`, `CSS`, `JS`, `JSON`, etc.)
Exception : les fichiers `.py` ne sont pas réindentés par cette action — ils utilisent autopep8 à la place.

---

## Compatibilité technique

| Outil / Plateforme       | Supporté                |
| ------------------------ | ----------------------- |
| Visual Studio Code       | 1.90+                   |
| Systèmes d’exploitation  | Windows / macOS / Linux |
| Python installé          | Oui (requis)            |
| Fonctionne sans Prettier | Oui                     |
| Fonctionne hors ligne    | Oui                     |

---

## Crédits et licence

Ce pack est une création originale de **Palks Studio**.
Toute revente, redistribution ou modification publique sans autorisation préalable est strictement interdite.
L’usage personnel et professionnel est autorisé.

**Palks Studio**
Créateur indépendant d’outils digitaux utiles et autonomes.

- GitHub : https://github.com/Palks-Studio  
- Gumroad : https://palks.gumroad.com  
- Itch.io : http://palks-studio.itch.io  
- Ko-fi : https://ko-fi.com/palksstudio  
- Twitter (X) : https://x.com/Palks_Studio

---

## Signature

**Palks Studio — Version 1.1**  
Compatible with Visual Studio Code and Prettier
