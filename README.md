# Planche de pictogrammes (ortho-aac-helper)

Petit outil web pour composer et imprimer des planches de pictogrammes [ARASAAC](https://arasaac.org), pensé pour l'orthophonie et la communication alternative et augmentée (CAA / AAC).

**👉 Utiliser l'outil : https://levraibaptiste.github.io/ortho-aac-helper/**

Tout tient dans un seul fichier `index.html` : pas d'installation, pas de compte, pas de serveur. La planche est sauvegardée automatiquement dans le navigateur.

> Pour l'export Word avec une police web (Andika, Lexend, Atkinson Hyperlegible, Playwrite), installer la police sur l'ordinateur depuis [fonts.google.com](https://fonts.google.com), sinon Word la remplacera.

## Fonctionnalités

- **Recherche de pictogrammes** dans la base ARASAAC, en français, anglais, espagnol, italien, allemand ou portugais.
- **Mes images** : utiliser ses propres images (photos, dessins…), avec une recherche par nom de fichier ou de dossier, comme pour ARASAAC.
  - Sous Chrome ou Edge, on lie un dossier : ses images et celles de ses sous-dossiers sont lues sur place, sans copie, et le dossier est retenu d'une visite à l'autre.
  - Sous Firefox ou Safari, les images du dossier sont copiées dans le navigateur, en version allégée.
  - On peut aussi ajouter une image seule par bouton, glisser-déposer ou copier-coller (Ctrl+V).
  - Tout reste sur l'ordinateur : rien n'est envoyé sur internet.
- **Deux modes de mise en page** :
  - **Grille** : le nombre de colonnes et de lignes se calcule tout seul à partir de la taille des cases (toujours carrées, la légende prend sa place sur l'image), des marges et de l'espacement. On échange deux pictos en les glissant l'un sur l'autre.
  - **Placement libre** : chaque picto se déplace et se redimensionne où l'on veut sur la feuille.
- **Légendes** : affichées ou non, modifiables, en écriture normale, MAJUSCULES ou minuscules.
- **Polices adaptées à la lecture** : Atkinson Hyperlegible, Andika, Lexend, Playwrite FR Moderne (cursive), ainsi que Arial, Verdana, Comic Sans MS, Times New Roman.
- **Lignes de découpe** en option, avec la taille des cartes une fois découpées.
- **Format A4** portrait ou paysage.
- **Impression** directe, ou **export Word (.docx)** pour retoucher la planche ensuite.
- **Thème clair / sombre** selon le réglage du système.

### Raccourcis clavier

| Touche | Action |
| --- | --- |
| Flèches | Grille : changer de case. Libre : déplacer le picto (Maj + flèche pour aller plus vite) |
| Suppr / Retour arrière | Retirer le picto sélectionné |
| Échap | Désélectionner |
| Ctrl+Z | Annuler la dernière modification (aussi avec le bouton ↶) |
| Ctrl+Maj+Z ou Ctrl+Y | Rétablir (aussi avec le bouton ↷) |

## Crédits et licence des pictogrammes

Pictogrammes : Sergio Palao. Origine : [ARASAAC](https://arasaac.org). Licence : [CC BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.fr). Propriété : Gouvernement d'Aragon (Espagne).

Les planches réalisées avec cet outil doivent donc rester à usage **non commercial** et conserver cette mention.

Bibliothèques utilisées : [docx](https://github.com/dolanmiu/docx) pour l'export Word, polices [Google Fonts](https://fonts.google.com).

## Licence

Projet entièrement open source, sous licence [GNU GPL v3](LICENSE) : libre à vous de l'utiliser, l'étudier, le modifier et le redistribuer, à condition que toute version modifiée et redistribuée reste elle aussi sous GPL v3, avec son code source. Les contributions (issues, pull requests) sont les bienvenues.

Cette licence couvre le code de l'outil. Les pictogrammes ARASAAC restent sous leur propre licence CC BY-NC-SA (voir ci-dessus).
