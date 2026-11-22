# VPS pas cher : quel prix au mois, quelle configuration pour ce tarif, et quelles options font grimper la facture ? (comparatif des offres d'entrée de gamme)

Le VPS le moins cher en France se situe entre 4,50 € et 6 € TTC par mois. À 4,57 € TTC, OVHcloud annonce 2 vCores, 4 Go de RAM et 40 Go de NVMe. À 6,00 € TTC, GandiCloud annonce 1 cœur, 1 Go de RAM et 25 Go de disque. Entre les deux, 1,43 € d'écart mensuel et une machine quatre fois moins dotée en mémoire.

La comparaison des VPS pas chers se joue donc rarement sur le prix affiché. Elle se joue sur ce que la formule contient, sur ce qui s'ajoute en option et sur la possibilité de changer de formule sans tout migrer. Les trois points sont traités ci-dessous, avec les tarifs actuels des principales offres d'entrée de gamme du marché français.

> **Pour décider en trente secondes.** Site vitrine, bot Discord ou Telegram, script cron, environnement de test : une formule à 4–6 € TTC par mois avec 2 Go de RAM couvre l'essentiel, et la sauvegarde incluse pèse plus lourd dans la décision que 500 Mo de RAM en plus. Pour situer une offre précise dans ce paysage, 👉 [consultez les formules VPS d'AVA Hosting](https://my.ava.hosting/aff.php?aff=15562) et vérifiez la configuration annoncée au moment de la commande.

## Trois offres d'entrée de gamme comparées sur ce qu'elles contiennent

| Offre | Configuration annoncée | Prix affiché | Inclus dans le prix | Limites annoncées |
| --- | --- | --- | --- | --- |
| OVHcloud VPS-1 | 2 vCores, 4 Go RAM, 40 Go NVMe | 3,81 € HT = 4,57 € TTC/mois | Sauvegarde automatisée quotidienne, trafic illimité en Europe, 500 Mbit/s, anti-DDoS | Pas de baisse de configuration directe, montée en gamme limitée au même datacenter |
| PulseHeberg Economy Cloud | CPU « variable selon l'hôte », RAM et disque non détaillés sur la page | à partir de 6 €/mois TTC | NVMe, anti-DDoS Netrix, sans quota de trafic, jusqu'à 3 Gbps, hébergement en France | CPU non garanti, aucun snapshot, pas de SLA 99,99 %, Linux uniquement, France uniquement, pas de baisse de configuration |
| GandiCloud V-R1 | 1 cœur, 1 Go RAM, 25 Go | 6,00 €/mois TTC | 1 IPv4 + 1 IPv6, 250 Mbit/s, 3 To de trafic, API OpenStack, support e-mail 6 j/7 | Disque de base 25 Go, volume supplémentaire à 0,07 € TTC/Go/mois, disponibilité visée 99,95 % |

PulseHeberg est le seul des trois à ne pas publier la RAM et le disque de son offre d'entrée sur la page produit. La fiche précise en revanche que le modèle et la fréquence du processeur varient selon l'hôte et que le CPU n'est pas garanti, ce qui a une conséquence concrète : deux VPS Economy au même prix peuvent se comporter différemment selon la machine qui les héberge. Pour un site statique ou un script, la différence est marginale. Pour une compilation, un import de base de données ou un bot qui tourne en boucle, elle se sent.

OVHcloud reste la référence de prix sur ce segment, avec un écart net à configuration comparable. GandiCloud se positionne ailleurs : l'hébergeur l'écrit lui-même, il ne cherche pas à vendre des « VPS pas chers » mais des machines dont le prix finance le support et la qualité de service. À 6 € TTC pour 1 Go de RAM, la promesse n'est pas la quantité de ressources.

IONOS complète le tableau sans publier de tarif sur la page produit consultée. Ses arguments portent sur le choix du datacenter (Allemagne, Espagne, Royaume-Uni, États-Unis), une disponibilité annoncée à 99,99 %, Windows Server 2022 ou 2025, la console KVM et Plesk. Un point à noter pour les projets Windows : c'est le seul des quatre à afficher clairement une offre Windows sur son entrée de gamme.

## HT ou TTC : l'écart de prix se joue aussi là

OVHcloud affiche 3,81 € HT et 4,57 € TTC sur la même ligne. GandiCloud écrit « VAT incl. » dans son tableau. PulseHeberg annonce 6 €/mois TTC. Comparer 3,81 € à 6,00 € gonfle mécaniquement l'écart de 57 %, alors que la vraie différence est de 1,43 € par mois.

Sur douze mois, cela donne 54,84 € TTC pour le VPS-1 d'OVHcloud et 72 € TTC pour le V-R1 de Gandi comme pour l'Economy de PulseHeberg. L'écart annuel réel est de 17,16 €, pas 26,28 €. Sur un budget de particulier, 17 € sur l'année ne décident de rien ; sur dix serveurs, ça commence à compter, mais ça ne change toujours pas le choix technique.

La règle est simple : ramenez tout en TTC avant de comparer, et méfiez-vous des offres libellées en francs suisses, qui ne se convertissent pas à parité avec l'euro.

## Ce qui s'ajoute à la facture après le premier mois

C'est ici que les offres d'entrée de gamme se différencient vraiment. Cinq postes reviennent systématiquement.

**La sauvegarde.** OVHcloud l'inclut dans sa nouvelle gamme, à raison d'une sauvegarde automatisée par jour. PulseHeberg ne propose aucun snapshot sur Economy Cloud. IONOS vend Backup Cloud à partir de 0,05 € HT/Go/mois, soit environ 2 € HT par mois pour 40 Go. Sur un an, la sauvegarde peut coûter plus cher que l'écart de prix entre deux formules.

**Le panneau de contrôle.** Chez IONOS, la page mentionne l'édition Plesk Web Host comme incluse, puis affiche 5 € HT/mois sur la même ligne, avec un minimum de 20 Go de stockage sous Linux et 32 Go sous Windows, ce qui exclut le VPS Linux XS. Impossible de trancher à la lecture : à vérifier avant de compter sur Plesk gratuit. Chez OVHcloud, Plesk peut être préinstallé, mais vous en assurez l'administration et la maintenance, ce qui n'a rien à voir avec un hébergement Plesk managé.

**Les adresses IP.** IONOS facture 5 € HT (6 € TTC) par IPv4 supplémentaire. OVHcloud permet d'ajouter jusqu'à 16 IP, la tarification n'étant pas détaillée sur la page consultée.

**Le disque.** GandiCloud facture 0,07 € TTC par Go et par mois au-delà des 25 Go de base. Ajouter 50 Go revient à 3,50 € TTC mensuels, soit plus de la moitié du prix du serveur.

**Le système d'exploitation.** Windows Server chez IONOS implique une licence, à chiffrer selon la version et le nombre de cœurs avant de comparer avec une offre Linux.

Sur une formule à 5 €, ce sont ces lignes qui font passer la facture réelle de 5 à 10 € par mois. 👉 [Voir les formules VPS d'AVA Hosting et les options annoncées](https://my.ava.hosting/aff.php?aff=15562) donne un point de comparaison utile si vous voulez vérifier ce qui est inclus avant de valider.

## Monter en puissance est facile, redescendre beaucoup moins

Les trois hébergeurs ne traitent pas la flexibilité de la même façon, et c'est probablement le critère le plus sous-estimé au moment de l'achat.

OVHcloud permet de monter en configuration en un clic depuis l'espace client, à condition de rester dans le même datacenter et que celui-ci dispose des ressources nécessaires. La descente n'existe pas : pour passer d'un VPS-2 à un VPS-1, il faut commander un nouveau serveur, migrer les données et résilier l'ancien.

PulseHeberg ne permet pas non plus d'augmenter une seule ressource, ni de réduire la configuration. Faire évoluer un service signifie changer d'offre, avec la migration que cela suppose.

GandiCloud fait l'inverse : la configuration se modifie en quelques secondes, à la hausse comme à la baisse, depuis la console. Pour un projet dont la charge est incertaine (une appli qui décolle, un pic saisonnier, un test qui ne prend pas), cette souplesse vaut largement les quelques euros de différence à l'entrée.

Si vous démarrez un projet dont vous ne connaissez pas encore la charge, la question à poser avant de payer est donc : « si je me suis trompé de taille, combien me coûte la correction ? » Chez OVHcloud et PulseHeberg, la réponse est une migration. Chez Gandi, c'est un clic.

## « Trafic illimité » : trois définitions différentes

Le trafic illimité est un argument commun aux offres d'entrée de gamme, avec des réalités variables.

OVHcloud annonce du trafic illimité sur ses VPS européens, mais applique un quota mensuel sur la région Asie-Pacifique (Mumbai, Singapour, Sydney) : 500 Go pour le VPS-1, 1 To pour les VPS-2 et VPS-3, 3 To pour le VPS-4. Au-delà, la bande passante est bridée à 10 Mbit/s. Un site hébergé à Singapour pour toucher une audience asiatique n'a donc pas le même contrat qu'un site à Roubaix.

GandiCloud inclut 3 To de trafic avec une bande passante de 250 Mbit/s. PulseHeberg ne fixe pas de quota et annonce jusqu'à 3 Gbps, sur un réseau mutualisé entre les clients. IONOS annonce du trafic illimité et une connexion externe jusqu'à 1 GB/s.

Pour un site vitrine ou un blog, aucun de ces plafonds ne sera atteint. Pour du streaming, de la distribution de fichiers ou un proxy, le détail compte plus que le mot « illimité ».

## Sauvegardes et snapshots : le poste que les pages d'entrée de gamme oublient

Un snapshot reste stocké sur la même infrastructure que le serveur. Il protège d'une mauvaise manipulation, pas d'une suppression de compte ni d'un incident majeur. C'est une protection de confort, pas une sauvegarde.

Sur ce terrain, les écarts sont importants. PulseHeberg l'annonce clairement : pas de snapshot sur Economy Cloud, pas de SLA 99,99 %, pas de haute disponibilité. OVHcloud inclut une sauvegarde automatisée quotidienne sur sa nouvelle gamme et propose des options payantes (snapshots, sauvegarde Premium, stockage externe). GandiCloud affiche des snapshots « manuels et automatiques » dans son tableau, tandis que sa FAQ indique que la création de snapshots sera « disponible prochainement » et rappelle qu'un snapshot ne remplace pas une sauvegarde distante. Les deux affirmations figurent sur le même site : posez la question au support avant de compter dessus. IONOS vend Backup Cloud en option.

La conclusion pratique : sur une offre à 5 €, prévoyez soit une sauvegarde incluse, soit un budget option, soit votre propre script de sauvegarde vers un stockage externe.

## Quel VPS pas cher pour quel usage

Les règles qui suivent découlent des configurations et des limites vérifiées ci-dessus.

**Site vitrine, blog statique, portfolio.** 1 à 2 Go de RAM suffisent. Le VPS-1 d'OVHcloud à 4,57 € TTC avec 4 Go laisse de la marge pour un cache et quelques visiteurs simultanés.

**WordPress avec cache et extensions.** Visez 2 Go minimum, 4 Go pour être tranquille. Un panneau de contrôle comme Plesk consomme de la RAM avant même votre premier visiteur.

**Bot Discord ou Telegram, cron, petit conteneur.** 1 Go peut suffire, mais vérifiez que Docker est autorisé. Les VPS en Local Zone d'OVHcloud ne prennent en charge ni Windows, ni Plesk, ni cPanel, ni Docker, ni les Additional IP.

**Plusieurs services Docker, base de données, intégration continue.** Passez à 8 Go. Chez OVHcloud, le VPS-2 (4 vCores, 8 Go, 75 Go NVMe, 1 Gbit/s) est à 8,65 € TTC, le VPS-3 (6 vCores, 12 Go, 100 Go) à 12,48 € TTC et le VPS-4 (8 vCores, 24 Go, 200 Go) à 23,95 € TTC.

**Windows ou accès RDP.** OVHcloud Local Zone est exclu, PulseHeberg Economy est Linux uniquement. Reste IONOS avec Windows Server 2022 ou 2025, ou une formule supérieure ailleurs.

**Projet professionnel avec engagement de disponibilité.** Economy Cloud de PulseHeberg est hors jeu : pas de SLA. GandiCloud vise 99,95 % mensuel, IONOS annonce 99,99 %. Sur ce terrain, l'écart de prix à l'entrée n'est plus le sujet.

**Budget serré mais charge incertaine.** GandiCloud, malgré ses 6 € pour 1 Go, reste le seul des trois à permettre de redescendre en quelques secondes.

## Trois incohérences repérées sur les pages officielles

Elles méritent d'être signalées parce qu'elles changent la décision.

PulseHeberg présente Economy Cloud à 6 €/mois comme son « VPS Linux pas cher », mais sa FAQ indique Classic Cloud « à partir de 5 €/mois », avec SLA 99,99 %, snapshots et choix du datacenter. La page ne donne pas le détail complet des deux formules, impossible donc de dire laquelle est réellement la plus intéressante : demandez la fiche comparative avant de commander.

GandiCloud annonce des snapshots dans son tableau de spécifications et les présente comme « à venir » dans sa FAQ. Tant que ce n'est pas tranché, ne construisez pas votre plan de sauvegarde dessus.

OVHcloud affiche 3 Gbit/s pour le VPS-4 dans son tableau de formules et 2 Gbit/s dans le paragraphe consacré au trafic illimité de la même page. La valeur par formule est la plus fiable, mais le doute illustre pourquoi il faut vérifier la fiche au moment de la commande.

## Ce qu'il faut vérifier dans le tunnel de commande

Aucune des pages consultées n'affiche de prix de renouvellement distinct du prix courant, ni de durée d'essai, ni de conditions de remboursement. Ces trois informations se trouvent au moment du paiement, pas sur la page marketing.

Quatre vérifications avant de valider :

1. **Le prix de renouvellement**, surtout si le tarif affiché ressemble à une promotion de lancement.
2. **La durée d'engagement et les conditions de résiliation**, notamment pour les offres mensuelles sans engagement.
3. **La localisation du datacenter**, parce qu'elle détermine la latence pour votre audience et, dans le cas d'OVHcloud, le quota de trafic applicable.
4. **La TVA et la devise de facturation**, pour comparer ce qui est comparable.

Si vous hésitez entre deux formules à moins de 2 € d'écart, prenez celle qui inclut la sauvegarde et qui permet de redescendre. Une migration forcée coûte plus cher en temps que deux ans d'écart de prix. 👉 [Comparer les formules VPS d'AVA Hosting avant de choisir](https://my.ava.hosting/aff.php?aff=15562) permet de retrouver les configurations et les options annoncées au même endroit, ce qui évite de comparer un prix HT chez l'un avec un prix TTC chez l'autre.
