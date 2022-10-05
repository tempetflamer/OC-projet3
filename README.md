# OC-projet3
Openclassrooms Développeur d'application - JavaScript React - Projet 3 : Dynamisez une page web avec des animations CSS

## Étude de la marque
### Identité
Ohmyfood! est une entreprise de commande de repas en ligne. Notre concept permet aux utilisateurs de composer leur propre menu et réduire leur temps d’attente dans les restaurants car leur menu est préparé à l’avance. Plus de perte de temps à consulter la carte !

### Proposition
Nous souhaitons proposer à nos clients les menus de restaurants gastronomiques. Développé à New-York dans un premier temps, nous souhaitons désormais élargir notre concept à la capitale de la gastronomie (Paris).

### Positionnement
Nous nous positionnons sur un marché de niche, avec les restaurants luxueux des villes dans lesquelles nous sommes établis. Nous souhaitons être identifiés comme une entreprise proposant des services haut de gamme.

### Concurrence
| Nom de l'entreprise | Nombres de salariés | Domaine d'activité | Points positifs | Points négatifs |
| ------|-----|-----|-----|-----|
| Mylittlefoodie | Environ 50 d’après leur site web. | Réservation de tables dans les palaces parisiens. | <ul><li>Bonne implémentation en France.</li><li>Tarifs préférentiels sur les menus.</li><li>Site web très dynamique.</li><li>Bon référencement.</li></ul> | <ul><li>Pas de possibilité de voir les menus.</li><li>Dates de réservation limitées à 2 jours par semaine.</li></ul> |
| LebonParis | 15 salariés  | Classement des restaurants en fonction de leurs menus. | <ul><li>Beaucoup de choix de restaurants.</li><li>Menus très bien mis en avant sur la page d’accueil.</li></ul> | <ul><li>Pas de possibilité de réservation.</li><li>Pas de possibilité d’agrandir les menus.</li></ul> |

### Cible
Classes moyennes et supérieures, connectées et souvent pressées, souhaitant déguster des produits de qualité.

### Identité graphique
*Polices*
Logo et titres: Shrikhand
Texte: Roboto

*Couleurs*
Primaire : #9356DC
<!-- - ![#9356DC](https://via.placeholder.com/200x200/9356DC/969696?text=+) `#9356DC`
- https://via.placeholder.com/200x200/9356DC/969696?text=+ -->
<img src="./9356DC.jpg" alt="couleur #9356DC"/> 


Secondaire : #FF79DA
<img src="./FF79DA.jpg" alt="couleur #FF79DA"/> 

tertiaire : #99E2D0
<img src="./99E2D0.jpg" alt="couleur #99E2D0"/> 

### Problématique (enjeux)
Nous souhaitons ouvrir nos services à la capitale française. En passans par deux objectifs :
* Phase 1 : Développer un site proposant le menu de 4 grands restaurants parisiens.
* Phase 2 : Permettre la réservation en ligne et la composition de menus

## Cahier des charges
- L'intégration doit se faire uniquement en HTML5 et CSS3 sans JavaScript.
- Aucun framework doit être utilisé pour réaliser le site, mais l'utilisation de SASS est un plus.
- Le HTML et le CSS doivent être séparés (aucun code ne devra être appliqué via un attribut style dans une balise HTML). et le fichier doit être organisé.
- L'approche utilisée doit être mobile-first, cependant le site doit être responsibe sur tablette et desktop.
- Le code sémantiquement HTMl et CSS devrony être validé au validateur W3C.
- Le site doit être compatible avec les dernières versions de Chrome et Firefox.
- Le code doit être versionné sur GitHub.
- Le site doit être accesible sur Github Pages.

## Livrables attendus
### Contenu des pages
#### Page d'accueil (x1)
- Affichage de la localisation des restaurants (à terme, il sera possible de choisir sa localisation pour trouver des restaurants proches d’un certain lieu).
- Une courte présentation de l’entreprise.
- Une section contenant les 4 menus sous forme cartes (au clic sur la carte, l’utilisateur est redirigé vers la page du menu).

#### Pages de menu (x4)
- 4 pages contenant chacune le menu d’un restaurant.

#### Footer
-  Le footer est identique sur toutes les pages.
- Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.

#### Header
- Le header est présent sur toutes les pages.
- Sur la page d’accueil, il contient le logo du site.
- Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil.

### Effets graphiques et animations
Les effets accessibles au clic ou au survol sont visibles sur la maquette. Ils doivent utiliser les animations ou transitions CSS, pas de JavaScript ni de librairie.

#### Boutons
- Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir. L’ombre portée devra également être plus visible.
- À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se remplir progressivement. Pour cette première version, l’effet peut être apparaître au survol sur desktop au lieu du clic.

#### Page d’accueil
- Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini, toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte graphique du site.

#### Pages de menu
- À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe “Entrée”, “Plat” et “Dessert”. Un exemple de l’effet attendu est fourni.
- Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension. Un exemple de l’effet attendu est fourni.

## Compétences évaluées

- Mettre en œuvre des effets CSS graphiques avancés
- Assurer la cohérence graphique d'un site web
- Mettre en place son environnement Front-End
- Mettre en place une structure de navigation pour un site web
- Utiliser un système de gestion de versions pour le suivi du projet et son hébergement

## Note de fin de réalisation



