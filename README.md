# ProjetDatavisualisation Les Radars en France 
![](https://media.istockphoto.com/id/507853623/fr/photo/radar-appareil-photo.jpg?s=612x612&w=0&k=20&c=JCp_aTvUbIASBtysuOdeHGikOg8x3WjVsUNbl8v6XKY=)

*Créateur : typhoonski, Droits d'auteur : typhoonski*

##Choix du sujet 
La sécurité routière a toujours été un 

## Origine et traitement des données sur les radars en france <a id="som1"></a>
### A. Jeu de données n°1 : Répartition des radars en France <a id="som1a"></a> 
Données concernant les quelques 3000 radars automatiques en France. Informe de l'emplacement précis, de la route, de la direction, du type (fixe, feu rouge, tronçon...), de la vitesse contrôlée, de la date d'installation. Vous pouvez en apprendre plus sur une page dédiée sur le site de la sécurité routière.

Ce jeu de données utilise comme source le site du Ministère de l'Intérieur https://radars.securite-routiere.gouv.fr.
 Les données concernats les radars a été extrait du site www.data.gouv.fr , j'ai pu effectuer un sprint qualité afin d'évaluer la qualité de ces données de pouvoir afin de les épurées,les données sont de qualité nous remarquons l'absence de certaines données pour les dernières ligne de monfichier ce qui n'est pas très impactant car c'est relatif à la diretion auxquel sont rataché les radars.J'ai retiré également,j'ai égalment retiré la colone "longueur_troncon_km" car elle n'était pas renseigné pour tout les radars
## Visalaisation de la répartition des radars sur l'ensemble du teriitoir francais 
Utilisation de umap pour une visualisation dynamyque fonctionnalité de zoom plus performante 
 
<iframe width="100%" height="300px" frameborder="0" allowfullscreen src="//umap.openstreetmap.fr/fr/map/repartition-des-radars-en-france_867205?scaleControl=false&miniMap=true&scrollWheelZoom=false&zoomControl=true&allowEdit=false&moreControl=true&searchControl=null&tilelayersControl=null&embedControl=null&datalayersControl=true&onLoadPanel=undefined&captionBar=true"></iframe><p><a href="//umap.openstreetmap.fr/fr/map/repartition-des-radars-en-france_867205">Voir en plein écran</a></p>

NB: la vitesse limité par le radar n'est pas renseigné pour les radars de type "feu rouge" mais plutot pour les radars "fixe"
## Visualisation des differents types de radars <a name="TypeRadars"></a>
![](file:///C:/Users/hp/Downloads/viz.svg)
  
### B. Jeu de données n°2 : les accidents de la route <a id="som1b"></a>

2) Les données sur les accidents de la route sont issues de ( à voir)
https://www.data.gouv.fr/fr/datasets/bases-de-donnees-annuelles-des-accidents-corporels-de-la-circulation-routiere-annees-de-2005-a-2021/
https://www.data.gouv.fr/fr/datasets/base-de-donnees-des-accidents-corporels-de-la-circulation/
## Pourquoi les radars 
1/La décision d’implanter un radar s’effectue sur des sites où se produisent un nombre d’accidents corporels supérieur à la moyenne, où la vitesse est souvent en cause dans la survenance de ces accidents et où les contrôles sont difficiles à réaliser avec des moyens humains.
2/Le déploiement de radars automatiques en France est intervenu dès 2003 dans l’optique de réduire le nombre de tués sur les routes.

Les dates-clés du contrôle automatisé
https://www.securite-routiere.gouv.fr/radars/chiffres-radars/historique-des-radars

## Radars et baisse de la mortalité routière
Les conducteurs ont considérablement réduit leur vitesse moyenne, passant de 91 km/h à 80 km/h. Cela a contribué à une baisse moyenne des accidents mortels à proximité des radars de 66 %. En 10 ans, entre 2003 et 2012, les radars ont permis de sauver 23 000 vies. 
#Utilisation des outils de datavisualiation 
##utilisation de l'outil paladio cependant les données traité par l'outil sont non exportablee donc en sois l'outil m'a permis de mieux comprendre et assimilité les données, avoir une première impression des données et vérifier la qualité de mes données = > capture video avec les filtres paladio 
je passe à l'utilisation de l'outil rawgraph avec l'avantage d'exporter les données


https://www.onisr.securite-routiere.gouv.fr/outils-statistiques/open-data
