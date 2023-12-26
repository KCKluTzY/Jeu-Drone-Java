Voici notre projet de Java

Le jeu fait apparaitre le joueur (intrus) sur l'un des bords de la carte. Le but du jeu est de retrouvé un tresor de 2x2 pixels dans toutes la carte. La carte est noir au debut de la partie et se devoile selon les mouvement du joueur qui retient la carte. Il y a deux types d'ennemies les mega drones et les petits drones qui peuvent respectivement voler au dessus du terrain normal et des petits arbres , et voler seulement au dessus du terrain normal. Quand l'intrus passe a moins de 3 cases d'un drones il va envoyer ces coordonnées a tous les autres drones qui vont alors s'envoler pour pousuivre le joueur. Si deux drones du meme type passe a moins d'une case il se rentre dedans et se desactive pendant 2 seconde avant d'avoir une immunité pour les 1,5 secondes suivantes. Les arbres sont placé aléatoirement selon un pourcentage d'apparition. Les sortie apparraissent au 4 coins de la cartes toujours au meme endroit. Le trésor apparait a un endroit aléatoire a plus de 5 cases des bords. la vitesse , le nombre de petit et grand drones ainsi que leurs vitesse , le pourcentage d'arbres et petit abres sont tous paramétrables. Le jeu ressemble a l'image ci dessous on peut voir deux types d'arbres selon la couleur , les points rouges sont des mega drones et les points roses des petits drones

![image](https://github.com/KCKluTzY/Jeu-Drone-Java/assets/128617444/e52fde0e-55d3-4eb9-9802-bf9bf17407ab)


Points d'amélioration :

les drones aire dans la carte sans réel intelligence on pourrait donc améliorer cela. De plus on pourrait implementer des algorithmes tel que Djistra pour que les drones évite les abres quand l'intrus est detecté . Le code pour ajouter les sorties n'est pas optimiser . On peut facilement ajouter un ajout de drones au fur et a messure de la partie ainsi que l'augmentation de leurs vitesses. L'interface est assez minimal et donc peut etre améliorer

Ce tp a été réaliser par Théo Morneau Quentin Molin et Pillot Lucas Sur une base du TP Fourmis de notre professeru Emmanuel Adam 
