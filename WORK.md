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

## Hébergement en VPS, ou Virtual Private Server

L'hébergement en VPS ressemble à l'hébergement mutualisé, en ce qu'il permet d'héberger __plusieurs sites web__ sur __une__ machine. Seulement, plutôt que de tous les héberger côte-à-côte, il s'agit de créer des __machines virtuelles__ sur lesquelles on héberge chaque serveur. Une machine virtuelle, c'est une __infrastructure logicielle__ qui permet de simuler un environnement informatique. Ainsi, avec plusieurs machines virtuelles sur une machine physique, on peut agir comme si on avait plusieurs petites machines physiques.
A chaque VPS est allouée une partie des ressources de la machine qui les contient. Ainsi, chaque site web se débrouille avec les ressources auxquelles il a accès sur son VPS, mais il ne __peut pas empiéter__ sur les ressources des autres sites web, comme c'est le cas dans un hébergement mutualisé.
De plus, le VPS est __fortement configurable__, car le client a accès à la racine du VPS, et donc à toute son __infrastructure__.
Finalement, __l'isolation complète__ du VPS par rapport aux autres VPS constitue un atout de __sécurité__ indéniable. Par exemple si un site web subit une attaque DDOS, qui constitue à le surcharger, cela n'aura d'influence que sur le VPS qui l'héberge, et aucune influence sur les performances des autres VPS.

Caractéristiques d'un serveur VPS:
- Accès aux ressources nécessaires, sans perturbation
- Configuration très pointue possible
- Bonne sécurité dûe à l'isolation de chaque serveur
- Prix faible (facilement moins de 3 euros)

## Hébergement en cloud

L'hébergement cloud se base sur le même principe de __virtualisation__ que l'hébergement VPS. Seulement, les différentes machines virtuelles ne sont pas créées sur une machine physique mais sur __plusieurs__. Les machines virtuelles ainsi créées sur plusieurs machines physiques permettent d'héberger un site web sur __plusieurs machines physiques__ en même temps. Cela permet d'héberger un site à très __fort trafic__ efficacement, et de limiter les __perturbations__ dûes à une panne.
L'hébergement cloud permet en outre au client de définir les performances __dont il a besoin__ à chaque instant. Ainsi, les ressources allouées par le serveur pour le site web seront plus ou moins importantes, __en fonction des besoins__. Le client paie uniquement pour les ressources qu'il __utilise__, en fonction du trafic sur son site web, ainsi l'hébergement cloud est __flexible__ et n'engendre __pas de gâchi__. En ce sens, on dit que l'hébergement en cloud est un __service__: nous ne payons pas pour le _bien_ qu'est la machine, mais pour le _service_ qu'est l'allocation dynamique de ressources pour notre site web.

Il existe trois services différents d'hébergement cloud :
- SaaS (Software as a Service) : l'utilisateur reçoit à travers le Cloud un accès à une ressource matérielle telle qu'un ordinateur, un réseau ou même un espace de sauvegarde. Il est libre d'utiliser les logiciels et est responsable de l'installation et de la surveillance.
- PaaS (Platform as a Sercive) : le fournisseur met à disposition de l'utilisateur un environnements de logiciels sous la forme de "frameworks" et s'occupe de sa maintenance. L'utilisateur peut développer et gérer ses propres applications sur cette plateforme.
- IaaS (Infrastructure as a Service) : L'utilisateur peut avoir accès à un logiciel mis à disposition, et ne doit ni en gérer les mises à jour, et ni les fonctionnalités.

Caractéristiques d'un serveur en cloud:
- solidité du serveur: comme le serveur est réparti sur plusieurs machines, si l'une d'entre elles tombe en panne, cela ne fait que diminuer les performances du serveur étant donné qu'il en reste plusieurs en fonctionnement
- flexibilité du site web: les ressources allouées au site web peuvent changer en temps réel en fonction du trafic
- flexibilité du prix: le client ne paie que ce qu'il utilise, pas plus

## Exemples

Il existe de nombreux hébergeurs web, comme par exemple:
- OVH: https://www.ovh.com/fr/
- Kimisufi: https://www.kimsufi.com/fr/
- LWS: https://www.lws.fr/
- Scaleway: https://www.scaleway.com/pricing/
- Gandi: https://www.gandi.net/fr/simple-hosting
- soyoustart: https://www.soyoustart.com/fr/
