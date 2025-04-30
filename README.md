# ETUDE ET AMELIORATION D'UN DISTRIBUTEUR DE QUILLES

# Motivation 
En regardant une compétition de bowling à la télévision, j'ai remarqué qu'après que les joueurs aient effectué leur lancer et fait tomber les quilles, le système automatique qui les replaçait en position initiale prenait un certain temps pour effectuer cette opération, ce qui pouvait sembler long pour les joueurs.

# Ancrage
La satisfaction des joueurs est liée à leur plaisir pendant le jeu. Une réduction du temps d'attente peut positivement influencer leur satisfaction en améliorant l'efficacité et la qualité du jeu. Ma recherche sur le système automatique de rangement des quilles suggère qu'une amélioration spécifique pourrait réduire le temps de repositionnement.

# Positionnement thématique
SCIENCES INDUSTRIELLES (Génie Mécanique)

SCIENCES INDUSTRIELLES (Automatique)

# Mots-clés (en français)
Amélioration
Requilleur
Rapidité
Quilles
Distributeur

![brunswick 1](https://github.com/user-attachments/assets/f1dc32ce-0a91-4b6f-aed5-c0bd2ee8e57c)

## Bibliographie commentée

Le bowling est une activité de loisir, mais aussi une discipline sportive. Il s’agit d’un jeu d’intérieur dans lequel les joueurs lancent des boules sur une piste pour tenter de renverser des quilles. Le bowling est l’un des sports les plus populaires dans le monde, et son image est très utilisée par les publicitaires [1].

Les jeux de quilles font partie des premiers jeux que l’homme a créés, remontant à l’époque de l’Égypte ancienne [2]. Le bowling moderne s'est répandu aux États-Unis au 19ᵉ siècle, gagnant en popularité parmi les travailleurs de l'industrie. Dans les années 1930, les brasseries ont sponsorisé des équipes professionnelles pour promouvoir leurs marques, contribuant à la croissance du sport. Les ligues organisées ont émergé, favorisant la participation récréative. Le bowling a connu une forte croissance au 20ᵉ siècle, marquée par la création du Congrès International Féminin de Bowling dans les années 1950, favorisant la participation active des femmes [3]. Aujourd’hui, le bowling est pratiqué dans le monde entier, avec des compétitions de niveau professionnel et amateur organisées régulièrement.

Une fois les quilles renversées, elles doivent être remises en place. Avant l’invention des systèmes automatiques, cette tâche était effectuée par des enfants ou des jeunes (les *pin boys*) qui se tenaient derrière les pistes pour remettre les quilles et récupérer les boules. Cela prenait beaucoup de temps et d'énergie, et limitait le nombre de parties jouables en une journée. Les *pin boys* étaient souvent mal payés et travaillaient dans des conditions difficiles, mais leur travail était crucial pour le bon déroulement du jeu [4].

En 1937, Gottfried Schmidt a breveté le premier système de remplacement automatique de quilles, marquant une innovation majeure dans l'industrie du bowling. Ce système simplifiait considérablement le processus de remise en place, permettant aux joueurs de se concentrer davantage sur le jeu [5]. La société AMF a développé et breveté en 1952 le premier *Requilleur automatique* (ou *Pinsetter*), qui a rencontré un grand succès dans l’industrie. Il a été adopté dans de nombreuses salles de bowling aux États-Unis, contribuant à populariser davantage ce sport [6]. AMF a également acquis les droits du brevet de Schmidt et a produit en masse ces dispositifs [7].

Après que les quilles ont été renversées, le *Requilleur* les repositionne sur le *Pindeck* pour qu’elles soient prêtes pour le lancer suivant. Ce système récupère les quilles tombées, les trie, élimine celles endommagées, et renvoie la boule aux joueurs. Dans un système automatisé, le distributeur est un composant clé : situé à l’arrière de la zone de jeu, il reçoit les quilles depuis l’élévateur et les achemine vers dix alvéoles de stockage, prêtes à être transférées sur la table de pose. Chaque alvéole est équipée d’un taquet qui permet de retenir ou libérer la quille. L’ensemble permet d’avoir une configuration complète de quilles prête à l’emploi pour chaque nouveau lancer [8].

# Problématique retenue :
Comment améliorer le distributeur des quilles du système actuel en un autre qui achemine les quilles vers les 10 alvéoles en moins de temps, en suivant une trajectoire spécifique, tout en maintenant une précision définie.

# Objectifs du TIPE : 
Analyse du Requilleur Brunswick GS-X et de la conception de son distributeur de quille, incluant le calcul du temps requis pour charger l'ensemble des alvéoles.
Dimensionnement d'un nouveau distributeur, qui consiste en un bras automatique combinant deux mouvements de rotation, afin de remplir les 10 alvéoles de manière plus rapide que le premier.
Choix d'un vérin capable de déplacer le bras, ainsi que la détermination de son emplacement dans le système.
Asservissement en vitesse du moteur actionnant le bras pour garder sa vitesse constante malgré les perturbations, garantissant la stabilité indépendamment des influences extérieures.

# Références bibliographiques

1. **ROOKIE ROAD** – *Bowling History* (consulté le 12 février 2023). [Voir lien](https://www.rookieroad.com/bowling/history/)
2. **WIKIPÉDIA** – *Jeux dans l’Égypte antique* (consulté le 12 novembre 2023). [Voir lien](https://data.over-blog-kiwi.com/0/84/87/59/ob_714e88_histoire-du-bowling.pdf)
3. **WILLIAM MATTHEW FLINDERS PETRIE (1853–1942)** – *Inductive Metrology; or, The Recovery of Ancient Measures from the Monuments*. Publié par Cambridge University Press le 5 septembre 2013. Le chapitre IX, intitulé *Rude Stone Remains, America, India, &c*, traite de l’histoire du bowling.
4. **GEORGE BOWERING** – *Pinboy: A Memoir*. Dans la deuxième partie intitulée *Pinboy*, l’auteur raconte son expérience de travail en tant que pinboy dans les années 1950. Publié par Cormorant Books en 2012.
5. **FAO (Food and Agriculture Organization)** – *Agriculture 4.0 - Agricultural Robotics and Automated Equipment for Sustainable Crop Production*. Ce rapport mentionne le requilleur de quilles automatique comme un exemple d’innovation technologique ayant amélioré la productivité et la qualité du bowling.
6. **OLD BOWLING** – *Development of the Automatic Pinsetter* (consulté le 12 novembre 2023). [Voir lien](http://oldbowling.com/page2.html)
7. **WIKIPÉDIA** – *Pinsetter* (consulté le 19 novembre 2023). [Voir lien](https://en.wikipedia.org/wiki/Pinsetter)
8. **BOWLINGON** – *How Do Bowling Pinsetters Work? Step by Step Explained*. Cet article explique comment un pinsetter utilise des capteurs et des bras mécaniques pour installer et dégager automatiquement les quilles. [Voir lien](https://bowlingon.com)
