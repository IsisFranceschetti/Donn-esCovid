# DonneesCovid
Lucie DUFLEIT 

Isis FRANCESCHETTI 

Théo MAZARS 

**L’évolution de la COVID-19 en PACA au prisme de l’isolement physique et du respect des gestes barrières de ses ressortissants**

** **

Notre ambition première était de comparer l'application des gestes barrières (et par extension, de l'isolement physique d'une population) et l'évolution du nombre de cas positifs à la COVID-19 pour une même population.  

Ainsi, nous avons décidé de travailler sur la région PACA, lourdement touchée par la propagation du virus. Pour ce faire, nous nous sommes basés sur les données issues des jeux de données librement accessibles de Datagouv, relatifs aux taux d’incidence dans les départements de la région PACA (Alpes de Haute Provence, Hautes Alpes, Alpes Maritimes, Var, Vaucluse et Bouches du Rhône) sur une période de deux mois s'étalant du 15 mai au 10 juillet. Le taux d'incidence correspond au nombre de tests positifs pour 100 000 habitants. 

Les données concernant la population des 6 départements proviennent des données de recensement officiel de l’INSEE.

Nous avons par la suite utilisé les jeux de données provenant du baromètre COVID-19, sondage mené par Ipsos et Datacovid, un projet d’initiative citoyenne visant à collecter des données sur la gestion à court et long terme de l’épidémie de Covid-19. Nous avons travaillé précisément sur la “vague 6” du 12 au 19 mai et sur la “vague 8” du 5 au 9 juin 2020. Nous nous sommes intéressés spécifiquement aux questions liées à l'isolement physique (éviter les regroupements, rester chez soi, respecter les distanciations sociales) et au respect des gestes barrières (se laver les mains, utiliser du gel hydroalcoolique, tousser dans un mouchoir, utiliser un mouchoir unique, pas d’embrassades), le nombre d’heures en dehors du domicile (dans une journée), le nombre de personnes rencontrées au cours des 24 dernières heures et enfin, le nombre de personnes rencontrées au cours des 7 derniers jours.  

D'un point de vue méthodologique, si l'extraction des données sur le nombre de cas de Covid fut longue et fastidieuse mais finalement sans grandes difficultés, l'utilisation des diverses données relatives à l'isolement physique fut plus complexe. Ainsi, nous avons fait le choix d'établir une note moyenne à chaque individu selon ses réponses au respect des pratiques mentionnées plus haut (respect des distanciations sociales, lavage des mains etc), et en agrégeant celles-ci, afin d'attribuer à chaque département une note attestant de la mesure avec laquelle sa population observe ou non un certain isolement physique. 

Il est primordial de noter que les données concernant le baromètre Covid-19 d’Ispos et de datacovid permettant d’établir une note du respect de la distance sociale et des gestes barrières se base sur des sondages et donc sur du déclaratif. Cela entraîne des biais. On peut noter par exemple qu’une personne peut surestimer son respect des gestes barrières et peut dans la réalité ne pas bien le faire (mauvais positionnement du masque, lavage des mains approximatif…) tandis qu’une personne peut sous-estimer son respect des gestes barrières
** **
[Cas de Covid et respect des gestes barrières] (<amp-iframe sandbox='allow-scripts allow-same-origin' layout=responsive resizable noloading title='Interactive or visual content' src='https://flo.uri.sh/visualisation/4400566/embed?auto=1' width=400 height=300><amp-img layout=fixed height=64 width=64 src='https://public.flourish.studio/resources/bosh.svg' placeholder style='margin: auto'></amp-img><div overflow></div></amp-iframe><p><a href='https://public.flourish.studio/visualisation/4400566/?utm_source=embed&utm_campaign=visualisation/4400566'><amp-img layout=fixed height=16 width=105 src='https://public.flourish.studio/resources/made_with_flourish.svg' alt='Made with Flourish'></amp-img></a></p>)
** **

Clé de lecture: de gauche à droite: Vaucluse, Var, Hautes-Alpes, Alpes Maritimes, Bouches du Rhône, Alpes de Haute-Provence. La taille des dots correspond à la population de chaque département. Plus l’indice d’isolement physique est proche de 1000, plus les gestes barrières et la distanciation sociale sont respectés.  

Sur ce graphique global, on constate un hiatus évident entre notre postulat (corrélation entre nombres de cas positifs et respect des gestes barrières) et la réalité.

En agrégeant les données sur l'isolement physique et les cas positifs pour les vagues 6 (12-19 mai) et 8 (5-9 juin), nous pensions obtenir une visualisation qui laisserait transparaître une logique plus évidente. A savoir, que les départements respectant les gestes barrières seraient plus à même de juguler la propagation de l'épidémie. Or il se trouve que c'est le département qui les respecte le moins (les Alpes-de-Hautes-Provence) qui possède le taux d'incidence le plus bas sur la période. Et à l'inverse, le Vaucluse, qui est le deuxième département en termes de respect des distanciations, possède le second taux d'incidence le plus élevé de la région.

Dans le même temps, le taux d’incidence n’est pas non plus lié uniquement à la taille de la population. Certes, le département des bouches du rhône qui a la population la plus grande a aussi le taux d’incidence le plus élevé, mais cette corrélation n’existe pas sur les autres départements. 

**Evolution de la propagation du virus et du respect des gestes barrières entre les vagues 6 et 8 pour tous les départements de PACA**




Clé de lecture : 1000 étant le respect le plus parfait des gestes barrières

Sur ces deux visualisations, on constate avec encore plus de précision ce que la visualisation précédente laissait entrevoir : pour la période et la population donnée, le respect des gestes barrières ne provoque pas nécessairement un ralentissement de la propagation du virus. 

On constate ici que 4 départements ayant un respect des distanciations moins strict pour la vague 8 que pour la 6 voient le nombre de cas positifs diminuer. 

A l'inverse, le Var, qui est le seul département à voir son nombre de cas positifs empirer sur la période, est le seul avec les Alpes-Maritimes à avoir accru le respect des gestes barrières sur son territoire entre les deux vagues. 



**Evolution du respect des gestes barrières entre les vagues 6 et 8 dans le Var, le Vaucluse et les Alpes-Maritimes



Lecture : Plus le nombre se rapproche de 1000, plus les gestes barrières sont respectés. 

**Evolution du nombre de cas positifs entre les vagues 6 et 8 dans le Var, le Vaucluse et les Alpes-Maritimes**



Cette  focale sur 3 départements permet de mettre en évidence de façon criante l'absence de corrélation entre les deux indicateurs. Alors que le respect des gestes barrières dans les Alpes-Maritimes chute de près de 20%, on note une diminution de près de 70% de la circulation du virus dans la même temporalité. 

A l'inverse, dans le Vaucluse où le respect des distanciations augmente sensiblement, on assiste à une augmentation importante du  nombre de cas positifs (+78%). 

**CONCLUSION **

Pour conclure, il est apparu au cours de nos recherches et de la construction de cette visualisation que nos idées communes sur la relation positive entre meilleur respect des gestes barrières et baisse du nombre de cas de Covid ne s'appliquent pas en tout temps ni en tout lieu. En effet, les cas étudiés dans la dernière partie de notre analyse montrent qu'une hausse des précautions n'entraîne pas automatiquement une baisse du nombre de tests positifs, et réciproquement qu'un moindre respect des consignes ne s'accompagne pas toujours d'un bond dans les chiffres sur la covid en région PACA. Le choix de cette région s'est donc avéré intéressant en permettant la découverte des éléments ici mentionnés, avec des zooms par département aux effets paradoxaux.

Limites:

Il nous a semblé difficile de définir un sujet: nous avons changé d'angle à plusieurs reprises, en raison d'un manque d'accès à des jeux de données pertinents. Nous avons finalement choisi de centrer l'analyse sur le lien entre le taux d'incidence (nombre de tests positifs/nombre de tests réalisés) et respect des gestes barrières. Néanmoins, l'extraction des données a aussi été complexe. L'analyse de données qualitatives à transformer en données quantitatives en fonction des questions formulées par datacovid nous a amenés à réaliser plusieurs opérations techniques peu intuitives. La gestion des non-réponses à l'étude de Datacovid a rajouté un niveau d'analyse dans la création d'une moyenne du respect des gestes barrières dans les régions choisies. Enfin, la sélection de deux régions dans les jeux de données nationaux a été longue, même si plus simple à réaliser sous workbench.

 

 

** **
