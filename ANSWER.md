# 1.
Qu'est-ce qu'une instance Virtual Machine ?

C'est un environnement virtuel qui fonctionne comme un système informatique virtuel, avec son processeur, sa mémoire, son interface réseau et son espace de stockage, mais qui est créé sur un système matériel physique.  
# 2.
Qu'est-ce qu'un VNET ? 

Il s'agit du virtual network qui est un réseau physique dans le cloud, utilisé par les entreprises. Il permet à un réseau de centres de données de fournir une structure de réseau la plus efficace pour les applications qu'il héberge. VNET permet également de protéger les données.  

# 3.
A quoi sert un NSG ?

Les Network Security Group ce sont des matrices de flux, qui sont sur Asure. Il s’agit d’un pare-feu logiciel qui s’applique sur différents éléments azure tels que:
Cartes réseaux/serveurs
Base de données
Passerelle VPN
Sous réseau
Tag/balise


# 4.
Quelles sont les 5 propriétés désirables du cloud ?

1) Accès aux services par l’utilisateur à la demande
La mise en œuvre des systèmes est entièrement automatisée et c’est l’utilisateur qui gère la configuration à distance.
2) Accès réseau large bande
Ces centres de traitement sont généralement raccordés directement sur le backbone Internet pour bénéficier d’une excellente connectivité. 
3) Réservoir de ressources (non localisées)
Il est souvent possible de choisir une zone géographique pour mettre les données “près” des utilisateurs.
4) Redimensionnement rapide (élasticité)
Toutes les opérations peuvent s’effectuer automatiquement par des scripts. Ces mécanismes de gestion permettent de bénéficier pleinement de la facturation à l’usage en adaptant la puissance de calcul au trafic instantané.
5) Facturation à l’usage
Il n’y a généralement pas de coût de mise en service (c’est l’utilisateur qui réalise les opérations). La facturation est calculée en fonction de la durée et de la quantité de ressources utilisées.

# 5.
Qu'est-ce que l'A/B Testing ?

L’A/B testing consiste à comparer deux versions d’une page web ou d’une application afin de vérifier laquelle est la plus performante. Ces variations, dénommées A et B, sont présentées de manières aléatoires aux utilisateurs. Une partie d’entre eux sera alors dirigée vers la première version tandis que l’autre sera affectée à la seconde.

# 6.
Comment programmer le cloud ?

Concernant la programmation du cloud, les approches sont différentes. 
Au niveau le plus bas, IaaS, il n’y a pas de pile logicielle prédéfinie.  On peut y installer un Windows Server ou un Linux avec une base Oracle ou MySQL, et développer ses applications dans le langage de son choix.
Au niveau le plus élevé, SaaS, il s’agit ici de solutions métier clés en main, hébergées sur le site de l’éditeur telles que les applications CRM de salesforce.com.
Le niveau intermédiaire, PaaS, il permet de créer ses propres applications en s’appuyant sur une plateforme logicielle. Le développeur se concentrer sur les langages, les API et les fonctionnalités.


# 7.
Quelle est la technique pour faire un déploiement sans interruption de service ?

Dans un premier temps il faut isoler les machines de production, ensuite découper les versions en un plus grand nombre de livraisons de moindre taille, puis automatiser au maximum les étapes de tests et passages en production d’une nouvelle version afin de réduire les cycles.


# 8.
Qu'est-ce que le Canary release ?

 Le canary release est un pattern qui permet de faire tester les dernières modifications réalisées (appelée version N+1) à une tranche de population restreinte avant de réaliser un déploiement général de cette version. Il permet d’améliorer considérablement la qualité des mises en production.

# 9.
Comment changer de taille de machine virtuelle ?

D'abord il faut cloner la  machine virtuelle, et après il y a deux commande à faire :
cd C:\Program Files\Oracle\VirtualBox\
VBoxManage.exe modifyhd C:\Users\Le Crabe\VirtualBox VMs\[Nom de la machine virtuelle]\[Nom du disque].vdi -–resize[Nouvelle taille du disque en Mo]



# 10.
Qu'est-ce que le Blue/Green deployment ?

Le Blue Green deployment propose d’avoir un environnement de production identique à celui qui est utilisé par les utilisateurs qui recevra une nouvelle version. Il sera essentiel d’avoir un outil de routage qui saura passer d’un environnement de production à l’autre afin d’avoir la nouvelle version de façon totalement transparente.

# 11.
Citez deux avantages du PaaS sur le IaaS ?

Les deux avantages: 

Une entreprise optant pour ce type de prestation bénéficie d’une plateforme et d’un environnement informatique hébergés accessibles via une simple connexion internet. Les outils fournis permettent aux utilisateurs de créer des applications logicielles.

Le fournisseur se charge d’assurer la gestion de l’infrastructure et des applications. Il peut éventuellement assister les développeurs.


# 12.
Quelle est la différence entre le PaaS et le Serverless ?

Les applications serverless peuvent être actives presque instantanément, dès qu'un événement déclenche une fonction d'application. Les applications construites en PaaS peuvent être opérationnelles rapidement, mais elles ne sont pas aussi légères que les applications serverless et prennent plus de temps à être opérationnelles. 

# 13.
Que veut dire Serverless ?

Serverless computing est un modèle de conception et de déploiement d'applications basé sur les événements dans lequel les ressources informatiques sont fournies sous forme de services cloud évolutifs. Le serverless computing n'élimine pas les serveurs, mais vise à reléguer au second plan les questions liées aux ressources de calcul pendant la phase de conception.

# 14.
Citez les trois propriétés désirable du Serverless ?

- Les applications Serverless évoluent instantanément, automatiquement et à la demande, sans configuration supplémentaire de la part du développeur ou du fournisseur. Une application Web Serverless peut évoluer jusqu'à arrêter son activité, puis redémarrer en réponse à un événement en quelques secondes ou millisecondes.
- La facturation Serverless est extrêmement précise et les développeurs ne paient que pour ce qu'ils utilisent.
- Le temps de lancement des applications Serverless est très rapide.


# 15.
Comment s'appelle la plus petite unité de compute déployable en Serverless ?

Il s'agit d'une fonction.
