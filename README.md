# RESERVIA

Reservia - Openclassrooms : projet 2

Lien gitpages : https://ikeket.github.io/DelmasSarah_2_16102020/


Lien du projet : à venir

Description :
Transformez une maquette en site web

Démarrez sur HTML et CSS en intégrant une page Web, d'une plateforme de réservation de vacances.

Compétences évaluées
> Intégrer du contenu conformément à une maquette
> Mettre en place son environnement Front-End
> Utiliser un système de gestion de versions pour le suivi du projet et son hébergement
> Implémenter une interface responsive



Mise en situation (fictive) : 
Stagiaire développeur web dans une entreprise proposant un outil de planification de vacances.
L’UI Designer a proposé un nouveau design du site basé sur Material Design.
Mon rôle est de réaliser le prototype du site en intégrant les maquettes en HTML et CSS.

>> Cahier des charges <<

Fonctionnalités
(non-fonctionnelle) L'utilisateur peut chercher un hébergement dans la ville de son choix via un un champ de saisie. Le texte peut être édité par l'utilisateur.
(non-fonctionnelle) Les cartes d'hébergements sont toutes cliquables et les liens sont vides pour le moment.
(non-fonctionnelle) Les filtres de recherche permettent de choisir ses préférences. Ils changent également de visuel au survol et/ou au clic.
(fonctionnelle) Les champs "Hébergements" et "Activités" dans le menu de navigation sont des ancres qui redirigent sur les sections éponymes.

Assets (images + logo)
Icônes : Font Awesome free library
Charte graphique : bleu #0065FC - bleu clair #DEEBFF - gris #F2F2F2
Police : Raleway

Contraintes 
1) L'integration se fait en HTML5 & CSS3, sans framework.
2) Le site est responsive, il s'adapte aussi bien au mobile qu'à l'ordinateur (voir maquettes). Pour le design tablette, le choix est laissé au développeur.
3) Le HTML et le CSS sont séparés et le dossier est organisé.
4) Le code est versionné avec Git et un repository distant existe sur Github.
5) Le code a passé le test du validateur W3C HTML et CSS sans la moindre erreur.
6) Le site est compatible avec les dernières versions de Chrome et de Firefox.


Notes sur la réalisation du projet et les choix techniques
Mobile First
HTML 5
Balises sémantiques utilisées : <header> <section> <article> <aside> <footer>
Les icônes Font Awesome sont intégrées dans le HTML (utilisation du CDN officiel pour intégrer le CSS de Font Awesome)
CSS 3
Flexbox
Import de la police Raleway via CDN Google Font

Images : Sélection des images du dossier small. Taille suffisante pour l'affichage du site sans nécessiter de retouche par l'utilisation du "object-fit".

Dossier de rendu : 
HTML -- index.html
CSS -- lib/style.css
