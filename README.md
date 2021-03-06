﻿# Projet E-commerce 

Le projet **E-commerce** est un projet de e-commerce. Il s’agit de concevoir et mettre en place un
site internet de vente privée pouvant gérer un très grand nombre de clients pour l’Australie.
Le projet comportera un front, soit un site visible à l’utilisateur :

 E-commerce : sera un site de vente en ligne tous produits.

Le front sera administrable par un même backoffice.



# Contraintes techniques
**Hébergement**

Dans un souci d’optimisation des performances réseau les serveurs seront hébergés
dans le pays émetteur du plus grand nombre de requêtes, soit l’Australie.

**Langues**

Le Front et le BackOffice sont en anglais, cependant il doit être pris en compte que
d’autres langues peuvent être amenées à être utilisées, ainsi nous nous orienterons vers une
solution pouvant gérer le multi langues.

**Référencement**

Les pages de produits étant privées elles ne sont pas référençables par les moteurs
de recherche, il faudra donc optimiser les pages visibles au maximum pour le référencement.

**Navigateurs**

Les navigateurs permettant d’utiliser le site seront Google Chrome, Firefox et Safari.
Doit être pris en compte également la possibilité d’accéder au site via les smartphones et
tablettes.

**Délais**

Le projet doit pouvoir être développé rapidement, quelques mois pour que le site soit
opérationnel.

## Pages et fonctionnalités

**Le Front**

---------------------------------------------------------- **Login**------------------------------------------------------------------
![enter image description here](https://cdn.discordapp.com/attachments/397525296208805901/576425459500318730/Opera_Instantane_2019-05-10_170846_codekits.co.png)
C’est la page vitrine du site, elle permet à l’utilisateur de :
 Se connecter
 Accéder aux pages 

- Devenir membre
- Mot de passe oublié
- Qui sommes-nous ?
- Press Room

Mot de passe oublié
Cette page contient un formulaire qui permet d’envoyer un lien par mail à l’utilisateur qui lui
permettra de changer de mot de passe s’il le souhaite.

Devenir membre
Contient un formulaire d’inscription – données personnelles -, un lien vers les conditions
générales de vente, des cases à cocher pour :
 Les conditions générales de vente
 La newsletter
Il est possible de renseigner l’adresse email du parrain.

Conditions générales de vente
Texte des conditions générales de vente (Fourni par le client)

Menus
Il y a 2 menus :
 ACCUEIL, MON COMPTE, PARAINAGE, AIDE &amp; CONTACT, MES RENDEZ-VOUS,
MON PANIER
 LE BLOG, CHEQUE CADEAU

ACCUEIL
Sur la page d’accueil les collections sont affichées.
Une collection est caractérisée par :
 Un logo
 Une image
 Une date de début et de fin

6

Pour chaque collection il est possible :
 D’accéder à la VENTE (détail de la collection)
 D’inviter un ami à voir la collection
 De publier sur facebook/twitter
 De visualiser la bande d’annonce (vidéo)
Sont uniquement affichées les collections actives « Actuellement » qui correspondent au
niveau de la date de début et de fin et celles qui seront disponibles dans les x jours à venir
« Prochainement ».
Dans les collections à venir il est possible d’inscrire la collection choisie dans MES RENDEZ-
VOUS.
Un formulaire est présent permettant de parrainer un ami.

VENTE
La page VENTE contient une image de fond (background) sur laquelle est placé un logo et la
liste des catégories contenues dans la collection. Le nombre de membres connectés à cette
vente est affiché.
Les catégories contiennent des sous catégories - affichées via un clic sur la catégorie -
pointant vers la page PRODUITS correspondante.

PRODUITS
La page PRODUITS comprend les éléments de la page VENTE sans l’image de fond.
Il est possible d’effectuer une recherche par caractéristiques des produits (case à cocher)
La liste des produits correspondant à la sous-catégorie est affichée, un produit est
caractérisé par plusieurs éléments :
 Un titre
 Des caractéristiques
 Nom du produit - Modèle
 Un prix de vente
 Un prix barré (optionnel)
 Encore disponible / Plus disponible
 Une image
 Un lien vers la FICHE PRODUIT
 Un bouton permettant de faire un ACHAT EXPRESS
Pour chaque produit il sera possible d’enregistrer le détail des coûts logistique.

6

ACHAT EXPRESS
La page ACHAT EXPRESS comprend une galerie d’images et les éléments suivants :
 Un titre
 Des caractéristiques
 Prix conseillé
 Prix de vente
 Nom du produit - Modèle
A partir de ces informations il est possible de choisir la quantité et d’ajouter le produit au
panier.

FICHE PRODUIT
La FICHE PRODUIT comprend ACHAT EXPRESS ainsi que des caractéristiques.
Une caractéristique est composée de son nom et de son contenu (description, texte, image,
vidéo, …)

MON PANIER
On arrive sur la page MON PANIER lorsque l’on ajoute un élément au panier ou que l’on
clique sur le lien dans le menu.
MON PANIER est le début du tunnel de commande, il affiche dans un tableau la liste des
produits ajoutés au panier. Chaque élément du panier est composé de :
 Une photo miniature
 Nom du produit – Modèle
 Quantité
 Prix unitaire
 Prix total
Montant global de la commande apparait en fin de tableau.
Lien vers les conditions générales de vente.
Plusieurs actions sont possibles sur cette page :
 Annuler le panier : Renvoi vers MON PANIER avec un message d’annulation de
commande.
 Modifier le panier : Renvoi vers MON PANIER avec possibilité de modifier la quantité
des produits.

6

 Continuer le shopping : Renvoi à la dernière page PRODUITS visitée.
 Acheter : Passe à l’étape 2 « LIVRAISON » du tunnel de commande.
La durée de vie d’un panier est de 1 heure. (Dépassé ce délai, le client doit recommencer sa
commande)

Note : Le tunnel de commande est en 5 étapes.
MON PANIER &gt; LIVRAISON &gt; RECAPITULATIF &gt; PAIEMENT &gt; CONFIRMATION

LIVRAISON
Affichage des différentes adresses. Pour chaque adresse on peut :
 Modifier l’adresse
 Supprimer l’adresse
 Choisir l’adresse pour choisir le mode de livraison
Il est également possible d’ajouter une adresse à partir de cette page.
Arrivé au choix du mode de livraison, plusieurs possibilités sont proposées. Chaque choix
comporte :
 Un icone - Un titre
 Le nom et logo du transporteur
 Une description (avec tarif)

RECAPITULATIF
Cette page affiche :
 L’adresse de livraison
 Donne une estimation de la date de livraison
 Le tableau de la liste des produits en incluant cette fois le tarif des frais de
préparation et de livraison. Il est également affiché le prix économisé par rapport aux
prix estimés.
Le client peut alors sélectionner la carte de crédit supportée par le système de paiement
bancaire.

6

PAIEMENT
Dépend du système de la banque choisi pour le paiement en ligne, cette partie valide la
carte de crédit, effectue l’opération bancaire et donne un résultat positif ou négatif affiché
dans la CONFIRMATION.

CONFIRMATION
Selon le résultat :
 Positif : Un message de confirmation est affiché sur la page et est envoyé par mail au
client avec sa facture.
 Négatif : Un message d’erreur est affiché.
Un email de confirmation est envoyé automatiquement au client contenant la facture.

MON COMPTE
C’est la page permettant d’accéder à toutes ses informations pour pouvoir les configurer :
 Mes coordonnées
 Mes commandes
 Mon carnet d’adresses
 Mon mot de passe
 Mes filleuls
 Mes bons d’achat

Mes coordonnées
Permet de visualiser et modifier ses informations personnelles.

Mes commandes
Affiche la liste des commandes passées sur le site.

6

Mon carnet d’adresse
Affichage des différentes adresses. Pour chaque adresse on peut :
 Modifier l’adresse
 Supprimer l’adresse

Mon mot de passe
Permet de changer son mot de passe en renseignant l’ancien mot de passe.

Mes filleuls
Affiche la liste des filleuls : nom et date d’inscription.
Il est possible d’accéder à la page PARRAINAGE pour inviter un filleul.

Mes bons d’achat
Affiche la liste des bons d’achat. Ils sont caractérisés par :
 Un nom
 Une description
 Un montant
 Une date de validité
Restriction d’un bon d’achat maximum par vente.

PARRAINAGE
Envoie un e-mail au filleul, si celui-ci s’enregistre est passe commande sur le site le parrain
gagne un bon d’achat de x $. Valable uniquement pour la première commande.
Le formulaire d’envoi de mail contient 5 champs :
 4 champs email
 Un message personnel pré rempli mais modifiable par le parrain.

6

AIDE &amp; CONTACT
Cette rubrique réuni un ensemble de pages d’aide explicatives selon les thèmes, des
formulaires de contacts et fonctionnalités. Certains semblent essentiels :
 Mon espace &gt; Question relative à mon compte &gt; Résiliation de compte : Détruit le
compte.
 Nos engagements &gt; La livraison : Texte
 Nos engagements &gt; Condition générales de vente : Texte
 Nos engagements &gt; Condition générales d’utilisation : Texte
 Contact professionnel &gt; Contact fournisseurs : Formulaire de demande de contact
 Contact professionnel &gt; Contact Presse : Redirige vers pressroom.xyz.com

MES RENDEZ-VOUS
Affiche la liste des collections à venir x jours avant leur sortie. Il s’agit du logo de la
collection, d’une date de début et de fin, Inscrit/Pas inscrit. Il suffira de cocher celles
vivement attendues pour qu’un e-mail soit envoyé au client lors de la disponibilité de la
vente.

LE BLOG
Il s’agit d’un blog standard, des actualités sont affichées dans l’ordre du plus récent au plus
ancien billet. Chaque billet peut contenir :
 Un titre
 Une date
 Un texte
 Une image
Il est possible pour le client d’écrire des commentaires et de lire ceux des autres clients.

Chèque Cadeau
« Chèque Cadeau » est une fonctionnalité qui sert à offrir un bon d’achat de x * x $ à un
autre client enregistré sur le site.
La page contient un texte explicatif ainsi qu’un formulaire comprenant les champs :

6

 Prénom
 Email
 Quantité de bon d’achat
 Un message textuel prédéfini mais modifiable
 De la part de …
Lors de la validation le bon d’achat est ajouté au panier et l’utilisateur est redirigé vers l’étape
1 du tunnel de commande.
Lors de la l’étape de confirmation un email spécial est envoyé au client bénéficiaire du bon
d’achat contenant le message textuel du donneur.

Press Room

C’est un sous domaine contenant les communiqués en rapport avec l’entreprise. Cet espace
contient un menu :
 Actualités
 Communiqués de presse
 Support multimédia
 La presse en parle
 Management

Actualités
Contient une série d’articles récents. L’article comprend :
 Une date
 Un titre
 Un texte court
 Un lien vers l’article au complet (texte long)

Communiqués de presse
Contient tous les articles qui ont été postés dans actualité. Classement par années.

6

Support multimédia
Il comprend deux pages : Visuels et Vidéos
Les visuels sont affichés par thèmes.
Les vidéos sont caractérisées par un titre et une description.

La presse en parle
Affiche une série d’articles qui ont été publiés dans la presse.
L’article comprend :
 Une date
 Nom du média
 Auteur
 L’article
Si l’article dépasse une certaine longueur il comprend un lien permettant de le visualiser en
entier.

Management
Affiche la liste des manageurs/co-fondateurs caractérisés par :
 Une photo
 Nom
 Prénom
 Fonction
 Un lien vers la description

BackOffice

Le BackOffice permet de gérer le site. Il est accessible par plusieurs utilisateurs avec leurs
propres identifiants et mot de passe.

6

Il se divise en plusieurs parties dans la page d’accueil :
 Gestion des clients &amp; commandes (Admin 1, Super Admin)
 Gestion de xyz (Admin 2, Super Admin)
 Gestion de pressroom.xyz (Admin 3, Super Admin)
 Gestion des bons de commandes fournisseurs (Admin 4, Super Admin)

Gestion des clients
Permet de visualiser l’ensemble des clients triés par date d’inscription.
Il est possible de rechercher un client par son nom ou son adresse email.
Lorsqu’un client est sélectionné ses informations personnelles sont affichées. Il est
également possible de supprimer manuellement un client.

Gestion des commandes
La liste des commandes est affichée, une commande est caractérisée par :
 Un numéro identifiant unique
 Une date
 Un client
 Une adresse de livraison
 Le prix de la commande
 Le prix des frais de port
 Le prix du bon d’achat utilisé ou non
 Le transporteur choisis
 Confirmé ou non
 La liste des produits commandés
Actions possibles :
 Rechercher des commandes par plage de date
 Rechercher une commande par son identifiant
 Supprimer une commande
 Afficher le détail d’une commande
 Imprimer la facture pour le client
 Imprimer l’adresse du client
 Le Super Admin pourra voir les bilans financiers selon les critères définis.

6

Gestion de xyz
Cette partie permet d’administrer xyz, il y a plusieurs pages :
 Gestion des fournisseurs
 Gestion des collections
 Gestion des catégories
 Gestion des sous catégories
 Gestion des produits
 Gestion des modes de livraison
 Gestion du blog
Pour chacune des pages précédentes il est possible de visualiser, d’ajouter, modifier et
supprimer les éléments auxquels ils se rapportent.
Le mode de suppression en cascade sera mise en place, pour plus de clarté il faut bien
comprendre qu’une collection contient des catégories, que les catégories peuvent contenir
des sous catégories et que les catégories ou sous-catégories contiennent des produits.
Ainsi lors d’une suppression de collection ce sont tous les éléments sous-jacents à cette
collection qui sont supprimés.
Une option « visible admin uniquement » sera disponible pour les collections pour que les
administrateurs puissent voir si les éléments ajoutés de la vente leur convient.

Gestion de pressroom.xyz
Cette partie permet d’administrer xyz, il y a plusieurs pages :
 Actualité
 Support multimédia
 La presse en parle
 Management
Pour chacune des pages précédentes il est possible de visualiser, d’ajouter, modifier et
supprimer les éléments auxquels ils se rapportent.

Gestion des bons de commandes fournisseurs
Depuis cette page il sera possible de générer un fichier PDF par fournisseur contenant
toutes les commandes sur une plage de dates données.

6

Les clients seront identifiés dans ce document par leurs IDs.
Chaque bon de commande fournisseur sera identifié par l’identifiant de la commande, ainsi
facilement récupérable dans l’espace d’administration des commandes.

## Switch to another file

All your files are listed in the file explorer. You can switch from one to another by clicking a file in the list.

## Rename a file

You can rename the current file by clicking the file name in the navigation bar or by clicking the **Rename** button in the file explorer.

## Delete a file

You can delete the current file by clicking the **Remove** button in the file explorer. The file will be moved into the **Trash** folder and automatically deleted after 7 days of inactivity.

## Export a file

You can export the current file by clicking **Export to disk** in the menu. You can choose to export the file as plain Markdown, as HTML using a Handlebars template or as a PDF.


# Synchronization

Synchronization is one of the biggest features of StackEdit. It enables you to synchronize any file in your workspace with other files stored in your **Google Drive**, your **Dropbox** and your **GitHub** accounts. This allows you to keep writing on other devices, collaborate with people you share the file with, integrate easily into your workflow... The synchronization mechanism takes place every minute in the background, downloading, merging, and uploading file modifications.

There are two types of synchronization and they can complement each other:

- The workspace synchronization will sync all your files, folders and settings automatically. This will allow you to fetch your workspace on any other device.
	> To start syncing your workspace, just sign in with Google in the menu.

- The file synchronization will keep one file of the workspace synced with one or multiple files in **Google Drive**, **Dropbox** or **GitHub**.
	> Before starting to sync files, you must link an account in the **Synchronize** sub-menu.

## Open a file

You can open a file from **Google Drive**, **Dropbox** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Open from**. Once opened in the workspace, any modification in the file will be automatically synced.

## Save a file

You can save any file of the workspace to **Google Drive**, **Dropbox** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Save on**. Even if a file in the workspace is already synced, you can save it to another location. StackEdit can sync one file with multiple locations and accounts.

## Synchronize a file

Once your file is linked to a synchronized location, StackEdit will periodically synchronize it by downloading/uploading any modification. A merge will be performed if necessary and conflicts will be resolved.

If you just have modified your file and you want to force syncing, click the **Synchronize now** button in the navigation bar.

> **Note:** The **Synchronize now** button is disabled if you have no file to synchronize.

## Manage file synchronization

Since one file can be synced with multiple locations, you can list and manage synchronized locations by clicking **File synchronization** in the **Synchronize** sub-menu. This allows you to list and remove synchronized locations that are linked to your file.


# Publication

Publishing in StackEdit makes it simple for you to publish online your files. Once you're happy with a file, you can publish it to different hosting platforms like **Blogger**, **Dropbox**, **Gist**, **GitHub**, **Google Drive**, **WordPress** and **Zendesk**. With [Handlebars templates](http://handlebarsjs.com/), you have full control over what you export.

> Before starting to publish, you must link an account in the **Publish** sub-menu.

## Publish a File

You can publish your file by opening the **Publish** sub-menu and by clicking **Publish to**. For some locations, you can choose between the following formats:

- Markdown: publish the Markdown text on a website that can interpret it (**GitHub** for instance),
- HTML: publish the file converted to HTML via a Handlebars template (on a blog for example).

## Update a publication

After publishing, StackEdit keeps your file linked to that publication which makes it easy for you to re-publish it. Once you have modified your file and you want to update your publication, click on the **Publish now** button in the navigation bar.

> **Note:** The **Publish now** button is disabled if your file has not been published yet.

## Manage file publication

Since one file can be published to multiple locations, you can list and manage publish locations by clicking **File publication** in the **Publish** sub-menu. This allows you to list and remove publication locations that are linked to your file.


# Markdown extensions

StackEdit extends the standard Markdown syntax by adding extra **Markdown extensions**, providing you with some nice features.

> **ProTip:** You can disable any **Markdown extension** in the **File properties** dialog.


## SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                |ASCII                          |HTML                         |
|----------------|-------------------------------|-----------------------------|
|Single backticks|`'Isn't this fun?'`            |'Isn't this fun?'            |
|Quotes          |`"Isn't this fun?"`            |"Isn't this fun?"            |
|Dashes          |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|


## KaTeX

You can render LaTeX mathematical expressions using [KaTeX](https://khan.github.io/KaTeX/):

The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

> You can find more information about **LaTeX** mathematical expressions [here](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference).


## UML diagrams

You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:

```mermaid
sequenceDiagram
Alice ->> Bob: Hello Bob, how are you?
Bob-->>John: How about you John?
Bob--x Alice: I am good thanks!
Bob-x John: I am good thanks!
Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Bob-->Alice: Checking with John...
Alice->John: Yes... John, how are you?
```

And this will produce a flow chart:

```mermaid
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D
```