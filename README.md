# Scénario

Vous avez intégré Ohmyfood en tant que développeur junior. Il s’agit d’une jeune startup qui voudrait s'imposer sur le marché de la restauration. Déjà présente à New-York, elle souhaite désormais faire sa place à Paris.
Votre mission est de développer un site “mobile first” qui répertorie les menus de restaurants gastronomiques. En plus des systèmes classiques de réservation, les clients pourront composer le menu de leur repas pour que les plats soient prêts à leur arrivée. Finis, les temps d'attente au restaurant !

L’équipe commerciale a déjà réussi à convaincre 4 restaurateurs d’utiliser la plateforme OhMyFood. Paul décide alors que le site contiendra 4 menus dans un premier temps.

Le projet va pouvoir commencer. Paul vous envoie les maquettes par e-mail :

" L’UX designer a finalisé les maquettes mobile et desktop du site ! Tu les trouveras en pièce jointe, en plus du dossier des sources du site (images et textes). Tu y trouveras également le prototype du site via Figma, incluant les animations et comportements à intégrer. Voici un extrait de ce à quoi devra ressembler le site :

![image](https://github.com/thealamenthed/p3/assets/90263288/89a45b45-d3f5-4cbe-b62f-412369591a36)

Il n’y a plus qu’à le développer pour mobile, tablette et desktop en s’appuyant rigoureusement sur les informations déterminées dans le brief créatif ! Pour rappel, le site doit être responsive et en “mobile first”. On veut aussi des animations soignées. Il faudra que tu m’expliques comment elles fonctionnent.

Hâte de voir le site terminé !

Bon courage !

Paul "

# Identité

Ohmyfood est une entreprise de commande de repas en ligne. Notre concept permet aux
utilisateurs de composer leur propre menu et de réduire leur temps d’attente dans les
restaurants, car leur menu est préparé à l’avance. Plus de perte de temps à consulter la
carte !

# Proposition

Nous souhaitons proposer à nos clients les menus de restaurants gastronomiques. Après
l’avoir développé à New-York dans un premier temps, nous souhaitons désormais élargir
notre concept à la capitale de la gastronomie : Paris.

# Positionnement

Nous nous positionnons sur un marché de niche, avec les restaurants luxueux des villes
dans lesquelles nous sommes établis. Nous souhaitons être identifiés comme une
entreprise proposant des services haut de gamme.

# Cible

Classes moyennes et supérieures, connectées et souvent pressées, souhaitant déguster des
produits de qualité.

# Identité graphique

Polices
Logo et titres : Shrikhand
Texte : Roboto
Couleurs
Primaire Secondaire Tertiaire
#9356DC #FF79DA #99E2D0

# Problématique

Nous souhaitons ouvrir nos services à la capitale française.

# Objectifs

- Phase 1 : Développer un site proposant le menu de 4 grands restaurants parisiens.
- Phase 2 : Permettre la réservation en ligne et la composition de menus.

# Technologies

- Le développement doit se faire en CSS, sans JavaScript.
- Le code CSS doit être disponible dans un ou plusieurs fichiers dédiés.
- Le site devra être réalisé en adoptant le Mobile First, c’est-à-dire qu’il faudra d’abord
  réaliser l'intégration de la maquette mobile, puis tablette, et enfin l'intégration du
  responsive vers le desktop.
- Aucun framework ne devra être utilisé ; en revanche l’utilisation de SASS serait un
  plus.
- Aucun code CSS ne doit être appliqué via un attribut style dans une balise HTML.
  4
- Tout le code doit être versionné sur GitHub avec des commits réguliers pour
  suivre l’avancement et publier le site en ligne plus facilement.
- Le site devra être accessible sur GitHub Pages une fois terminé.

# Compatibilité

La cible étant les personnes connectées et pressées, le site sera développé en utilisant
l’approche mobile-first.
Le site devra donc être intégré en suivant les maquettes mobile, puis le responsive suivra
pour les tablettes et ordinateurs en suivant les maquettes ordinateur données par notre
designer.

- L’ensemble du site devra être responsive sur mobile, tablette et desktop.
- Les pages devront passer la validation W3C en HTML et CSS sans erreur.
- Le site doit être parfaitement compatible avec les dernières versions desktop de
  Chrome et Firefox.

# Livrables attendus

🟣 Contenu des pages
Page d’accueil (x1)

- Affichage de la localisation des restaurants. À terme, il sera possible de choisir sa
  localisation pour trouver des restaurants proches d’un certain lieu.
- Une courte présentation de l’entreprise.
- Une section contenant les 4 menus sous forme de cartes. Au clic sur la carte,
  l’utilisateur est redirigé vers la page du menu.
  Pages de menu (x4)
- 4 pages contenant chacune le menu d’un restaurant.
  Footer
- Le footer est identique sur toutes les pages.
- Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.
  Header
- Le header est présent sur toutes les pages.
- Sur la page d’accueil, il contient le logo du site.
- Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil.

🟣 Effets graphiques et animations
Les effets accessibles au clic ou au survol sont visibles sur la maquette. Ils devront utiliser
les animations ou transitions CSS, pas de JavaScript ni de librairie. Pour toutes les
animations, afin de soigner le rendu du site, il est important que lorsque nous avons un effet
au hover ou lors d’un clic, nous ayons l’effet inverse lorsque l’on quitte le survol.
Boutons

- Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir.
  L’ombre portée devra également être plus visible.
- À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un
  bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se
  remplir progressivement. Pour cette première version, l’effet peut apparaître au
  survol sur desktop au lieu du clic.
  Page d’accueil
- Quand l’application aura plus de menus, un “loader” sera nécessaire. Sur cette
  maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à 3
  secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et
  utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini,
  toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte
  graphique du site.
  Pages de menu
- À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger
  décalage dans le temps. Ils pourront apparaître soit un par un, soit par groupe
  “Entrée”, “Plat” et “Dessert”.
- Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus.
  Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de
  la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol
  sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec
  des points de suspension.

# Organisation interne du projet

Circuit de validation : toutes les étapes du projet seront validées par Paul.

---

# Étapes pour configurer Sass dans votre projet :

## Installer Sass :

Si vous n'avez pas encore installé Sass, vous pouvez le faire en utilisant npm (Node Package Manager). Exécutez la commande suivante dans votre terminal :

```markdown
npm install -g sass
```

Cette commande installe Sass globalement sur votre système, ce qui vous permettra de l'utiliser n'importe où.

Créer la structure de fichiers Sass :

Créez un dossier pour vos fichiers Sass. Par exemple, vous pouvez créer un dossier scss à la racine de votre projet.

Créer un fichier Sass principal :

Dans le dossier scss, créez un fichier principal pour votre code Sass. Vous pouvez l'appeler main.scss. C'est dans ce fichier que vous importerez les autres fichiers Sass.

// Exemple de contenu dans main.scss

```markdown
@import 'partials/\_variables';
@import 'partials/\_styles';
// ... autres imports
```

- Créer des fichiers Sass modulaires :
  Dans le dossier scss, créez des fichiers Sass modulaires pour organiser votre code.
  Par exemple, vous pouvez créer un fichier \_variables.scss pour les variables Sass et un fichier \_styles.scss pour les styles principaux.

Compiler Sass en CSS :
Utilisez la commande suivante dans le terminal pour compiler votre fichier Sass principal (main.scss) en un fichier CSS.

Placez-vous dans le répertoire contenant le fichier main.scss et exécutez la commande :

```
sass main.scss output.css
```

Cela crée un fichier output.css à partir de votre fichier Sass.

Si vous souhaitez surveiller les changements et compiler automatiquement à chaque modification, utilisez la commande :

```
sass --watch main.scss:output.css
```

Inclure le fichier CSS dans votre HTML :

Dans votre fichier HTML, incluez le fichier CSS généré dans la section <head> :

```

<link rel="stylesheet" href="output.css">
```

Assurez-vous que le chemin est correct en fonction de l'emplacement du fichier CSS généré par Sass.

Configurer des options supplémentaires (optionnel) :

Si vous avez besoin de configurations spécifiques, comme la compression du code ou l'utilisation de fonctionnalités Sass avancées, consultez la documentation de Sass pour plus d'options : Sass Options.

Ces étapes de configuration vous permettront d'intégrer Sass dans votre projet et de commencer à écrire des styles en utilisant Sass. Vous pouvez également utiliser des gestionnaires de tâches comme Grunt, Gulp, ou Webpack pour automatiser davantage le processus de compilation de Sass en CSS.
