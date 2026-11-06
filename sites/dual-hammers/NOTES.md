# Site Dual Hammers — travail en cours

Nouveau site Wix (codé, publié avec StartDeployWebsite) pour présenter Dual Hammers
à des partenaires, fabricants et investisseurs. Le site Wix actuel (éditeur classique) n'est pas modifié.

## État
- `index.html` : page complète (accueil, prototype, ergonomie, vidéo, état du projet, contact).
- Vérification `check.mjs` : tout passe sauf `hero-lines` (test de résistance à 45 caractères, le titre réel tient sur 3 lignes).
  Dernière correction appliquée (logo masqué dans la barre sur mobile) : à revérifier.
- Reste à faire : `consistency.mjs`, `perf.mjs`, captures, passe animations (skills Emil), audit impeccable, publication Wix.

## Tirages (taste-skill)
hero split (re-tiré : `photo` demandait une photo de 1920 px), nav-split, close-type, footer-columns,
brand-band, boutons pill, palette white-navy-tab, police Mona Sans. Voir `deal-css.txt`.

## Fichiers non sauvegardés (dépôt public)
Le dossier `media/` n'est pas dans le dépôt. À régénérer à partir des fichiers fournis par l'utilisateur
(présentation PDF, `video-new.mp4` 1080x1920, `video-site.mp4` 1440x1080) :
- `hero-accroupie.jpg` : video-new à 2,2 s, recadrage (0,330)-(1080,1680)
- `prototype-main.jpg` : video-new à 11,6 s, recadrage (0,60)-(1080,1140)
- `poster-demo.jpg` : video-new à 3,6 s, recadrage (0,330)-(1080,1680)
- `torsion-kettlebell.jpg` / `alignement-dual-hammers.jpg` : video-site à 1,5 s, recadrages (0,60)-(608,820) et (832,60)-(1440,820)
- `banc-changement.jpg` : video-site à 40 s, recadrage (438,140)-(1046,900)
- `logo-dual-hammers.png` : image 1 du PDF (`pdfimages`) + son masque alpha, 512 px
- `demo-dual-hammers.mp4` : video-new en 720p, x264 crf 26, faststart
Le dossier `assets/` est une copie de `.claude/skills/design-taste-frontend/assets`.
Ne pas utiliser les photos du prototype du PDF : elles portent un filigrane « CONFIDENTIAL ».
