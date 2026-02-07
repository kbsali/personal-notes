## Fonctionnalités liées aux mises en place (création d’une vente) :

### Gestion des multi sites :
- Dans Krion pour une vente nous avons possibilité d’avoir plusieurs sites de livraisons alors que dans ClapClap aujourd’hui une vente est égale à un site de livraison, mais l’organisateur peux lancer plusieurs ventes en parallèle. Il faut qu’on regarde l’expérience utilisateur car les deux CMCAS que nous allons utiliser en tests utilisent plusieurs adresses. Le besoin de l’organisateur est de partager un seul lien (il sera présent sur les catalogues papiers) et qu’ensuite le commandeur puisse choisir la bonne adresse de livraison. Il faut arbitrer sur le moment du choix, est-ce avant ou après être rentré dans la vente ?
- Gestion des exigences clients en termes de livraison et **création des ventes par les commerciaux**
	- Pour certains de nos clients CSE avec un volume de commande suffisant nous offrons des services à la livraison :
		- **Impératif de livraison** = nous livrons au jour prêt sur un créneau d’une heure avec possibilité d’indiquer également des créneaux de distribution
		- **Présence Domaines & Villages** = nous mettons à dispositions du personnel D&V et des intérimaires pour faciliter la distribution
		- **Livraison en Roll** = nous livrons dans des chariots roulants plutôt qu’en palette pour faciliter la distribution
	- Ces services n’étant pas proposé « en libre-service » ce sont des fonctionnalités disponibles qu’à travers les mises en place réalisées par nos commerciaux. Il faut qu’on détermine comment nos commerciaux pourront demain créer des ventes sur ClapClap en choisissant ces options. Directement depuis ClapClap, synchro depuis Krion ?
- **Livraison en PDD**
	- Nous avons chaque saison une liste de Point De Distribution (PDD) ouvert. Cela peut être des points Agrikolis, La Poste, National Box… Lors de la création d’une mise en place, il doit être possible de sélectionner un ou plusieurs PDD, à la place ou en plus d’une adresse de livraison fournie par le client (PDL).
	- Il doit être également possible de sélectionner l’ensemble des PDD sur une vente, pour permettre à l’organisateur d’offrir la livraison sur n’importe lequel des PDD ouverts au moment où le client passe la commande.
- **Notification avant distribution**
	- Lors de la création d’une vente par nos commerciaux, ils ont la possibilité d’activer ou non des communications automatiques pour prévenir les clients. Nous avons 4 communications « transactionnel » qui partent depuis Krion
		- 2 mails à destination de l’organisateur à J-1 et J+5 du démarrage de sa vente.
		- 1 mail et 1 sms à destination des commandeurs à J-7, J-3 et J-1 de la date de distribution si un créneau de distribution a été défini lors de la MEP
- **Mise à disposition d’un code Promo**
	- Lors de la création d’une vente par nos commerciaux, ils ont la possibilité d’activer ou non des codes promotionnels (REDUC10, REDUC20…) qui pourront être utilisés par les commandeurs uniquement sur les ventes ou cela a été autorisé.
- **Cloture d’une commande groupée en dessous du Franco et gestion des frais de port**
	- Dans notre modèle nous validons la commande groupée quoiqu’il arrive et ensuite si le montant n’a pas atteint le franco de port, nous facturons à l’organisateur les frais correspondants. Dans notre modèle, nous essayons d’arranger au maximum les clients et donc nous regroupons les commandes pour éviter au maximum les frais… C’est très chronophage et source de nombreux problèmes. Il ne faudrait pas reproduire ce système, mais quand même s’assurer que la commande ne part pas en préparation si le frais de livraison n’ont pas été réglé en ligne au moment de la cloture.
- **Gestion des T3**
	- Nous avons certains clients qui commandent à la fois sur la boutique en ligne et à la fois par chèque avec saisie de bon de commande dans l’espace regroupeur. Quelle stratégie pour adresser ces clients demain ?

### Fonctionnalité espace regroupeur :
- Invitations à participer
	- Depuis son espace un organisateur peut inviter des gens par leur email ou téléphone à sa vente. Les personnes passent alors par une landing page pour qu’on puisse récupérer leur consentement et les inscrire dans les scénarios de marketing digital.
- Invitation à coadministrer
	- Depuis son espace un organisateur peut inviter un autre membre de son CSE, son association… à cogérer sa commande groupée.
- Module communication avec Probance
	- Depuis son espace un organisateur peut s’envoyer des templates de communication pré renseignée pour assurer lui-même la communication. Cette fonctionnalité ne semble pas être très utilisée, à voir comment on donne plus de souplesse à la communication aux organisateurs.
- Suivi des chèques fidélités
	- Depuis son espace, un organisateur peut avoir accès à ses avantages accumulés sur ses précédentes ventes
- Historique commandeurs
	- Permet de visualiser l’historique de l’ensemble des commandeurs qui ont déjà commandés à travers le groupe. Voir comment cela pourrait être complété des personnes invitées, ou d’une base de contact de personne n’ayant pas déjà commandés.

### Fonctionnalité CRM (Krion) :
Pour les fonctionnalités Krion, nous avons je pense deux options.
1. Synchroniser les ventes (=MEP) entre ClapClap et Krion pour nous permettre de continuer à faire des mises en place depuis Krion et suivre le chiffre de chaque client.
2. Apporter un volet CRM à ClapClap pro pour permettre le suivi des organisateurs

Je ne pense pas que les autres fournisseurs seront intéressés par suivre leurs ventes de manière aussi détaillée dans ClapClap, donc je pencherai plutôt pour la solution numéro 1.

Afin d’avoir le débat voici quelques fonctionnalités présentes dans Krion :
- Création de fiche prospect pour les équipements de développement commercial
- Création des mises en place pour les clients avec toutes les spécificités pour les groupes pro (impératif, créneau de distribution…)
- Catégorisation des clients et affectation en masse à des secteurs commerciaux
- Suivi multi critères des fiches clients (volume d’affaire, type de livraison, département, type de commande, présence de la concurrence…)
- Gestion d’agenda et de prise de rendez vous
- Suivi des propositions d’offres commerciales
- …

### Fonctionnalité Prestashop :
- Gestion des réductions
	- Code réduction Reduc10/20 paramétrable par groupe d’achat
	- Règle panier pour réduction sur un produit en particulier
	- Utilisations des chèques fidélité en ligne en tant que code promo par l’organisateur
- Système de parrainage entre commandeurs
- Paiement en plusieurs fois avec Paypal
- Home page configurable par les équipes marketing avec mise en avant de produit best-seller et de catégories dynamique
- Gestion des catégories pour mise en avant produit (meilleures ventes, idées cadeaux, barbecues…)
- Gestion des ventes flash
- Gestion du cross selling sur les fiches produits et sur la mise au panier
- Fiche produit détaillé avec template différent suivant la nature du produit
	- Gestion des produits simples
	- Gestion des offres
	- Gestion des coffrets
- Gestion de banderoles publicitaires par catégories de produits administrables par les équipes marketing
- Recherche sur les produits sur plusieurs critères
- Filtre multicritère sur les pages listing (tranche de prix, région, cépages…)
- Mise en avant forte du prix à la bouteille sur les offres (car particuliers des offre 3 = 9 avec gratuité d’un carton)
- Navigation par univers produits (nous avons des pages par marque Maison Colin Seguin, Pierre Colin, Mathieu Hugonnot…)
- Numérotation des produits avec la référence catalogue
	- Gestion des remplaçants, produit avec id différent, mais la même référence catalogue. Affichage du type de remplacement.
	- Lien direct dans les mailings, les bannières vers les articles en utilisant la référence catalogue et non pas la référence produit.
- Réassurance avis vérifié avec interfaçage sur les demandes d’avis- Depuis Prestashop, nous renvoyons nos clients vers ZenDesk en cas de questions ou réclamation, est ce qu’il sera possible d’interfacer la messagerie de ClapClap avec Zendesk, ou bien faut-il imaginer une autre façon d’organiser le support demain.
- Fonctionnalité d’AB Test

### Fonctionnalité Marketing Digital :
- Interface entre Prestashop et Krion vers Probance pour remonter nos regroupeurs, commandeurs liés au bon groupe d’achat
- Scénario d’animation de campagne se basant sur les dates des mises en place
- Scénario d’animation des organisateurs en fonction de différents critères CA / Franco…
- Scénario e-commerce (ex : abandon de panier)
- Retargeting Facebook / Google / LinkedIn vers la home page du site boutique (problématique d’url dynamique incluant le code boutique)