\# PROJET MONTAGNES RUSSES FINEAS DOLHA

Bienvenue sur mon projet ROLLER COASTERS. Ce projet a été réalisé en
utilisant mes connaissances en HTML et CSS.

\# Fichiers

démarrer le projet en créant tous les fichiers nécessaires :

\+ un \*fichier html\* appelé \*\*index.html\*\*

\+ un dossier contenant trois autres fichiers html représentant chaque
\*page\* du site web

\+ un dossier appelé \*medias\* contenant les images utilisées dans le
projet

\+ un dossier appelé \*styles\* contenant trois feuilles de style

+un fichier \*readme\* rédigé en \*markdown\*

\# HTML

\*\*page \*index.html\*\*\*

\* nommer la page en conséquence \"Les plus incroyables montagnes
russes\"

\* lier le favicon et la police google \"Raleway\"

\* lier les feuilles de style all.css et index.css

\* créer un H1 contenant le titre de la page

\* créer le conteneur principal

\* créer les boutons du pseudo-menu lié à chaque page

\* créer un pied de page contenant la revendication du droit d\'auteur

\*\*page \*page_1.html\*\*\*

\* nommer la page en conséquence \"L\'incroyable Kingda Ka\"

\* lier le favicon et la police google \"Raleway\"

\* lier les feuilles de style all.css et pages.css

\* créer un H1 contenant le titre de la page

\* créer une section avec une classe attribuée \*\*histoire\*\*

\* créer un titre avec la classe attribuée \*\*title-section\*\*

\* créer un \*\*article\*\* contenant la question et la réponse

\* créer une section avec la classe attribuée \*\*tableau\*\*

\* créer un titre avec la classe attribuée \*\*title-section\*\*

\* créer un tableau de 2 colonnes contenant des informations sur les
montagnes russes

\* créer une section avec une classe attribuée \*\*vidéo\*\*

\* créer un titre avec la classe attribuée \*\*title-section\*\*

\* créer une \*\*div\*\* qui contient la future vidéo youtube

\* ajouter une \*vidéo youtube\* à l\'aide de\*\* \< iframe \>
balise\*\*

\* créer une section avec une classe attribuée \*\*produits\*\*

\* créer un titre avec la classe attribuée \*\*title-section\*\*

\* créer les articles qui contiennent \*les divs\* contenant \*le prix
et les caractéristiques des billets\*

\* créer \*le div\* qui contiennent des \*\*boutons CTA\*\* (action)

\* Pour en savoir plus sur les prix, visitez la page officielle .

\* Retour à la page d\'accueil

\* créer un pied de page contenant la revendication du droit d\'auteur

\<sub\> \*appliquer les mêmes structures à la page_2.html et à la
page_3.html\*.

\# CSS

\## feuille de style \*all.css\*

\<sub\>représente la feuille de style appliquée globalement

\*\*tag\*\* \*html\*

\+ fixer la taille de la police à 20px pour pouvoir utiliser l\'unité de
mesure \*\*rem\*\* pur la responsivité

\*\*tag\*\* \*body\*

\+ définir la propriété \*box-sizing à border-box\* pour faciliter la
\*structure de flex-box\*

\+ suppression du padding et des marges pour pouvoir contrôler la
position des sections

\+ définir la famille de polices qui a été liée précédemment (Raleway)

\*\*tag\*\* \*header\*

\+ personnaliser l\'en-tête de la page de manière globale pour pouvoir
l\'utiliser ensuite

\+ définir le background et la propriéte \*height\*

\+ centrer le titre en utilisant les propriétés flex-box

\*\*tag\*\* \*header H1\*

\+ définir la taille de la police en utilisant \*\*rem\*\*

\+ styliser le titre à l\'aide de différentes propriétés

\+ ajout d\'une animation de 2s de type \*\*ease-out\*\*

\+ définir les keyframes de l\'animation en utilisant la position
relative du titre et le changement d\'opacité

\*\*tag\*\* \*section\*

\<sub\>étant la feuille de style globale, ces propriétés seront
appliquées par défaut pour chaque section de chaque page.

\+ fixer une hauteur minimale en utilisant \*\*vh\*\* pour avoir un
webdesign responsiv

\+ \*display flex\* avec la direction de la colonne et les éléments
centrés

\+ définir la couleur de back-ground #f5f5f5 pour \*\*chaque\*\* section

\+ fixer la bordure inférieure à 1px solid de la couleur #d4d4d4

\*\*sélecteur complexe\*\* \*section principale:nth-of-type(2n)\*

utiliser ce sélecteur pour automatiser l\'alternance de la couleur de
fond des sections

changer la couleur de back-ground

\*\*sélecteur complexe\*\* \*@media screen and (max-width:600px)\*

utiliser ce sélecteur pour diminuer la taille de la police de la racine
lorsque l\'écran de l\'appareil est inférieur à 600px

\## feuille de style \*index.css\*

\<sub\>représente le style utilisé uniquement pour la page d\'accueil

\*\*target\*\* \* button\* classe

la classe est utilisée pour les trois boutons de la page d\'accueil

\+ adapter les boutons à l\'ensemble de la page pour qu\'ils soient
visibles et pour produire un style minimaliste

\+ utiliser la propriété \*text-decoration\* afin de supprimer le
soulignement

\+ utiliser la propriété \*text-transform\* afin de mettre chaque lettre
en majuscule

\+ en ajoutant une position relative à la classe des boutons, ils seront
visibles lors du défilement en utilisant la propriété
\*\*animation-timeline : view()\*\*

\*\*sélecteur complexe\*\* \*@media screen and (max-width:600px)\*

\* Utilisez ce sélecteur pour assurer le bon fonctionnement du site web
dans une taille d\'écran inférieure à 600px.

\* supprimer l\'animation de scroll en changeant la valeur de
\*animation-timeline\* en \*\*auto\*\* .

\## feuille de style \*pages.css\*

\<sub\> représente le style partagé par les pages secondaires

\* définir des classes pour chaque section afin de pouvoir les styliser
différemment

\* Classes utilisées pour les sections : histoire, tableau, vidéo,
produits

\* définir différentes propriétés de flexion en fonction des besoins du
contenu

\*\*target\*\* \*titre-section\*

\* centrer le texte et régler la taille de la police sur \*\*rem\*\*
pour garder la responsivité

\* set \*flex: 1 0 100%\* pour s\'assurer que le titre s\'affiche sur
100% de la page

\* ajouter une animation de scroll à l\'aide de l\'animation-timeline

\*\*target\*\* \*histoire\*

\* changer le sens de \*flex\* en \*row\*

\* permettre au texte de s\'enrouler pour assurer la réactivité

\*\*target\*\* \*histoire\* article

\* fixer \*flex 1 0 30%\* pour assurer une répartition égale de
l\'espace entre les trois articles

\* fixer la propriéte min-height à \*\*vh\*\*

\* afficher \*flex\* en \*row\* avec les propriétés \*space between\* et
\*center\* pour s\'assurer que les éléments (questions, réponses)
s\'alignent correctement

\* assigner les classes \*\*.first\*\* et \*\*.second\*\* aux réponses
et aux questions pour pouvoir les manipuler séparément afin d\'ajouter
des bordures et de répartir l\'espace disponible dans la boîte.

\*\*target\*\* \*player\* div

\* définir la hauteur et la largeur en \*\*vh\*\*

\* ajuster \*margin\* , \*border-radius\* et \*box-shadow\*

\* scale le div à 80 % de sa taille actuelle

\* assurer une transition smooth entre les deux tailles en définissant
la propriété \"ease-in-out\".

\*\*target\*\* \*player\* div sur \*\*\*hover\*\*\*

\* redimensionner la div à 100% de sa taille d\'origine et assurer la
transition au survol

\*\*target\*\* \*produits\* section

\* définir la propriéte \*flex\* à \*row\* et permettre aux éléments de
\*wrap\* (envelopper)

\* Utilisez \*\*rem\*\* pour le padding afin de pouvoir contrôler la
responsivité.

\* \*\*target\*\* \*article\* de cette section

\* définir la hauteur en \*\*vh\*\*

\* définir \*max-width\* et \*min-width\* dans \*\*em\*\* pour conserver
les tailles indépendamment de la taille de la police racine

\* L\'affichage \*flex\* en \*colonne\* et \*centre\* le contenu

\* ajuster les propriétés \*margin\* et \*padding

\* scale l'article à 90 % de sa taille d\'origine

\* ajouter une transition de type \*ease-in-out\*

\* \* \*\*target\*\* \*article\* sur \*\*\*hover\*\*\* et increment la
taille à 100%

\* l\'élément article est séparé en deux divs de taille égale avec les
noms \*\*up\*\* et \*\*down\*\*.

j\'ai suivi cette solution pour être sûr de pouvoir manipuler le style
des cartes informatives

\* les deux boutons CTA y sont intégrés et l\'un est lié à la page
officielle du parc d\'attractions et l\'autre à la page d\'accueil

\*\*sélecteur complexe\*\* \*@media screen and (max-width:600px)\*

\* la \*classe\* \*\*player\*\* perd son animation pour les petits
écrans, a une marge plus petite et occupera 100% de la largeur de
l\'écran

\* la classe \*\*title-section\*\* perd son animation et a une taille de
police plus petite pour les écrans d\'une largeur maximale de 600px

\* les boutons CTA reçoivent une taille plus grande pour faciliter
l\'action sur les écrans plus petits

\* la \*classe \*\*article\*\* a reçu des marges différentes pour
s\'adapter à la taille de l\'écran

\* la \*classe \*\*article\*\* reçoit une taille plus grande pour les
petits écrans

\# Merci beaucoup pour votre attention !
