# HEBERGEMENT DE SITE WEB

## Introduction

Pour qu’un site web soit visible sur Internet, il faut que la machine sur laquelle il se trouve se __connecte à Internet__. Tant qu’elle reste connectée, le site web est __visible sur Internet__.
C’est très contraignant pour la machine hôte, car le partage d’un site web en ligne __consomme une partie des ressources__ de la machine et du réseau, et requiert qu’elle soit allumée en permanence si l’on veut que le site web soit accessible à toute heure.
En hébergeant un site web sur notre machine, il devient plus fastidieux d’utiliser celle-ci, puisque ses ressources sont en partie mobilisées pour le maintien du site web en ligne.
Pour pallier à ce problème, il suffit d’__héberger__ le site web sur une __autre machine__. Pendant ce temps, nous pouvons disposer de toutes les ressources de la __notre__.
Plutôt que d’acheter une machine, nous faisons donc appel à des __services d’hébergement__; il s'agit de __louer__ une machine pour disposer de ses ressources. Des services d’hébergement permettent, pour un coût minime _(par rapport au fait d’acheter une machine)_, d’héberger des sites web.
Afin de répondre au mieux aux besoins de chaque site web, il existe 4 différents types d’hébergement:
__- dédié
- mutualisé
- VPS
- Cloud__

## Hébergement mutualisé

En hébergement __mutualisé__, le site web est hébergé en __colocation__ avec d’autres sites web sur la machine hôte. Ainsi, les ressources de la machine sont partagées entre les différents sites webs qui y résident. Il s’agit du plus simple à utiliser, et convient à des petits sites ayant un faible trafic. En revanche, il entraîne de __fortes limitations__ en terme de performance, et la machine hôte n'est pas du tout personnalisable.
__Note:__ de moins en moins d'hébergements mutualisés existente. En effet, il est facile d'abuser des ressources d'une machine aux dépends des autres serveurs hébergés. D'autres types d'hébergements remplacent petit à petit ce mode d'hébergement. On peut ainsi avoir un hébergement solide pour moins de 3 euros par mois. Par exemple, Scaleway propose des hébergements dédiés à 2.99 euros par mois.

Caractéristiques d’un serveur mutualisé:
- Accès à une portion des ressources hardware
- Préconfiguration disponible
- Configuration et personnalisation indisponibles
- Serveur fragile
- Prix faible (souvent moins d'1 euro)

En résumé: notre site web est hébergé __facilement et à bas coût__, mais les possibilités de personnalisation de la machine sont __très limitées voire inexistantes__ et notre site web est à la merci de pics de consommations de ressources de la part d'autres sites web.

## Hébergement dédié:

Lorsqu’un client acquiert un serveur __dédié__, il dispose de __toute la machine hôte__. Il peut donc la configurer et l’administrer de manière très précise, en fonction de ses besoins. Ce mode d'hebergement se démocratise de plus en plus aux dépends de l'hébergement mutualisé, car il est financièrement très accessible.

Caractéristiques d’un serveur dédié:
- Accès à la machine en entière
- Configuration très pointue possible
- Prix relativement élevé, en fonction de la qualité (certains, comme chez l'hébergeur Ikoula, coûtent plus de 1000 euros!)

En résumé: on a un accès __sans limitation__ aux ressources hardware et software du serveur. C’est généralement __plus cher__ qu'un hébergement mutualisé et ça requiert des __connaissances pointues__ pour le configurer et l’administrer. En revanche, notre site web est très stable car il ne subit pas les conséquences des abus de colocataires, comme c'est le cas en hébergement mutualisé.

## Hébergement en cloud

*TODO*

## Hébergement en VPS

*TODO*

## Exemples

Il existe de nombreux hébergeurs web, comme par exemple:
- OVH: https://www.ovh.com/fr/
- Kimisufi: https://www.kimsufi.com/fr/
- LWS: https://www.lws.fr/
- Scaleway: https://www.scaleway.com/pricing/
- Gandi: https://www.gandi.net/fr/simple-hosting
- soyoustart: https://www.soyoustart.com/fr/
