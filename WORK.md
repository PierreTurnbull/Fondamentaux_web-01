# HEBERGEMENT DE SITE WEB

## Introduction

Pour qu’un site web soit visible sur Internet, il faut que la machine sur laquelle il se trouve se __connecte à Internet__. Tant qu’elle reste connectée, le site web est __visible sur Internet__.
C’est très contraignant pour la machine hôte, car le partage d’un site web en ligne __consomme une partie des ressources__ de la machine et du réseau, et requiert qu’elle soit allumée en permanence si l’on veut que le site web soit accessible à toute heure.
En hébergeant un site web sur notre machine, il devient plus fastidieux d’utiliser celle-ci, puisque ses ressources sont en partie mobilisées pour le maintien du site web en ligne.
Pour pallier à ce problème, il suffit d’__héberger__ le site web sur une __autre machine__. Pendant ce temps, nous pouvons disposer de toutes les ressources de la __notre__.
Plutôt que d’acheter une machine, nous faisons donc appel à des __services d’hébergement__; il s'agit de __louer__ une machine pour disposer de ses ressources. Des services d’hébergement permettent, pour un coût minime _(par rapport au fait d’acheter une machine)_, d’héberger des sites web.
Afin de répondre au mieux aux besoins de chaque site web, il existe 4 différents types d’hébergement:

- __dédié__
- __mutualisé__
- __VPS__
- __Cloud__

## Hébergement mutualisé

En hébergement __mutualisé__, le site web est hébergé en __colocation__ avec d’autres sites web sur la machine hôte. Ainsi, les ressources de la machine sont partagées entre les différents sites webs qui y résident. Il s’agit du plus simple à utiliser, et convient à des petits sites ayant un faible trafic. En revanche, il entraîne de __fortes limitations__ en terme de performance, et la machine hôte n'est pas du tout personnalisable.
__Note:__ de moins en moins d'hébergements mutualisés existente. En effet, il est facile d'abuser des ressources d'une machine aux dépends des autres serveurs hébergés. Pour cette raison, d'autres types d'hébergements gagnent en popularité, aux dépends de ce mode d'hébergement.

Caractéristiques d’un serveur mutualisé:
- Accès à une portion des ressources hardware
- Préconfiguration disponible
- Configuration et personnalisation indisponibles
- Serveur perturbé par une consommation excessive de ressources par certains sites web
- Prix faible (souvent moins d'1 euro)

En résumé: notre site web est hébergé __facilement et à bas coût__, mais les possibilités de personnalisation de la machine sont __très limitées voire inexistantes__ et notre site web est à la merci de pics de consommations de ressources de la part d'autres sites web.

## Hébergement dédié:

Lorsqu’un client acquiert un serveur __dédié__, il dispose de __toute la machine hôte__. Il peut donc la configurer et l’administrer de manière très précise, en fonction de ses besoins. Ce mode d'hebergement se démocratise de plus en plus aux dépends de l'hébergement mutualisé, car il est financièrement très accessible. Il est possible d'avoir un hébergement solide pour moins de 3 euros par mois. Par exemple, Scaleway propose des hébergements dédiés à 2.99 euros par mois.

Caractéristiques d’un serveur dédié:
- Accès à la machine en entière
- Configuration très pointue possible
- Prix relativement élevé, en fonction de la qualité (certains, comme chez l'hébergeur Ikoula, coûtent plus de 1000 euros!)

En résumé: on a un accès __sans limitation__ aux ressources hardware et software du serveur. C’est généralement __plus cher__ qu'un hébergement mutualisé et ça requiert des __connaissances pointues__ pour le configurer et l’administrer. En revanche, notre site web est très stable car il ne subit pas les conséquences des abus de colocataires, comme c'est le cas en hébergement mutualisé.

## Hébergement en cloud

L'hébergement cloud  est le stockage des données sur un parc de serveurs fourni par un prestataire.  
L'avantage est qu'on peut accéder aux données hébergées depuis n'importe où tant que l'on a une connexion à Internet.
L'hébergement cloud permet aux clients de définir les performances dont ils ont besoin à chaque instant. 
Celui ci peut à sa guise augmenter ou diminuer la performance des ses processeurs, sa capacité de mémoire ou d'espace disque. 
L'utilisateur paye uniquement ce qu'il utilise en fonction du trafic sur son site, ce qui rend l'hébergement cloud flexible et bon marché. 

Il existe trois services différents d'hébergement cloud : 
 - SaaS (Software as a Service) : l'utilisateur reçoit à travers le Cloud un accès à une ressource matérielle telle qu'un ordinateur,
     un réseau ou même un espace de sauvegarde. Il est libre d'utiliser les logiciels et est responsable de l'installation et de la surveillance. 
- PaaS (Platform as a Sercive) : le fournisseur met à disposition de l'utilisateur un environnements de logiciels sous la forme de "frameworks" 
     et s'occupe de sa maintenance. L'utilisateur peut développer et gérer ses propres applications sur cette plateforme. 
- IaaS (Infrastructure as a Service) : L'utilisateur peut avoir accès à un logiciel mis à disposition, et ne doit ni en gérer les mises à jour, et ni les 
     fonctionnalités.


## Hébergement en VPS

Un serveur VPS possède des caractéristiques spécifiques de stockage sur disque dur, quantité de RAM disponible et des performance des processeurs.
Ce serveur virtuel n'utilise pas de matériel dédié, seulement un disque dur ou un processeur mais il accède à une ou plusieurs parties des ressources 
matérielles. UN VPS possède des caractéristiques qui se distinguent des bases d'un serveur physique. 
L'avantage du VPS est la répartition flexible des ressources du serveur physique. Cela permet de créer un serveur au stockage adapté exactement selon 
les besoins. Il est ainsi souvent très avantageux de louer un VPS. Un VPS offre un accès à la racine du serveur et permet de définir soi même l'utilisation. 

## Exemples

Il existe de nombreux hébergeurs web, comme par exemple:
- OVH: https://www.ovh.com/fr/
- Kimisufi: https://www.kimsufi.com/fr/
- LWS: https://www.lws.fr/
- Scaleway: https://www.scaleway.com/pricing/
- Gandi: https://www.gandi.net/fr/simple-hosting
- soyoustart: https://www.soyoustart.com/fr/
