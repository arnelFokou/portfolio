# Portfolio - Documentation

## Presentation
Ce projet est un portfolio statique (HTML/CSS/JS) qui presente mon profil, mes projets, mon parcours et mes certifications. Il a ete concu pour etre simple a deployer, sans build ni dependances a installer.

## Structure du projet
- [index.html](index.html) : structure de la page (sections, contenus, liens)
- [styles.css](styles.css) : styles globaux, layout, responsive, animations CSS
- [main.js](main.js) : interactions (menu mobile, animations, effets)
- [assets/](assets/) : images et ressources (profil, projets, logos, certifications)

## Sections de la page
- Accueil : introduction, photo, CTA.
- A propos : description et telechargement du CV.
- Projets : cartes avec liens externes.
- Technologies : logos avec info-bulle au survol.
- Parcours professionnel : timeline responsive.
- Parcours academique : logos d'etablissements.
- Certifications : vignettes.
- Contact : liens mail, LinkedIn, GitHub.

## Fonctionnalites principales
- Menu mobile avec ouverture/fermeture et changement d’icone.
- Effet de frappe sur le titre (Typed.js).
- Animations d’apparition au scroll (ScrollReveal).
- Survol des cartes projets et technologies.
- Timeline adaptee aux ecrans mobiles.

## Dependances externes
Chargees via CDN dans [index.html](index.html) :
- Remix Icon
- Font Awesome
- Typed.js
- ScrollReveal

## Lancer en local
1. Ouvrir [index.html](index.html) dans un navigateur.
2. Conserver la structure des dossiers (surtout [assets/](assets/)).

## Personnalisation rapide
- Textes et liens : modifier directement [index.html](index.html).
- Images : remplacer les fichiers dans [assets/](assets/) ou mettre a jour les chemins.
- Couleurs et theme : variables CSS dans [styles.css](styles.css) (bloc :root).
- Animations JS : options dans [main.js](main.js) (Typed.js et ScrollReveal).

## Notes
- Site 100% statique, aucun build requis.
- Une connexion internet est necessaire pour charger les CDN d’icones et d’animations.

