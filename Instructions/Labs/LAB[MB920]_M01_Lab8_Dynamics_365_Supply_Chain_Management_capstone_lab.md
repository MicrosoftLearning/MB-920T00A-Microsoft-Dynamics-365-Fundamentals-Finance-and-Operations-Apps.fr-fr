---
lab:
    title: 'Labo 8 : Labo Capstone de Dynamics 365 Supply Chain Management'
    module: 'Module 1 : Découvrir les principes de base de Microsoft Dynamics 365 Supply Chain Management'
---

## Labo 8 : Labo Capstone de Dynamics 365 Supply Chain Management

## Objectif

Au cours de ce labo, vous découvrirez la création de produits et la gestion des prix. Vous apprendrez également des processus métier essentiels des chaînes logistiques, comme la gestion des stocks et l’approvisionnement.

## Mise en place du labo

- **Durée estimée** : 45 minutes 

## Exercice 1 : Découvrir la gestion des produits

### Créer un produit

Dans Contoso Entertainment System USA (USMF), vous devez créer un article pour une nouvelle configuration d’enceinte à acheter auprès des fournisseurs.

1. Sur la page d’accueil, dans la partie supérieure droite, vérifiez que l’entreprise **USMF** est sélectionnée.

1. Dans le cas contraire, sélectionnez l’entreprise affichée et modifiez-la pour passer à **USMF**.

1. À l’aide du volet de navigation, sélectionnez **Modules** > **Gestion des informations produit** > **Produits** > **Produits lancés**.

1. Sur la page Détails des produits lancés, dans le volet Actions, sélectionnez **+ Nouveau**.

1. Dans le volet **Nouveau produit lancé**, dans le menu **Type de produit**, vérifiez qu’**Article** est sélectionné.

1. Dans le menu **Sous-type de produit**, vérifiez que **Produit** est sélectionné.

1. Dans le menu **Groupe de dimension de suivi**, sélectionnez **Aucun**.

1. Sous **IDENTIFICATION**, dans le champ **Numéro de produit**, saisissez **GTL201**.

1. Dans la zone **Nom du produit**, saisissez **Enceinte**.

1. Sous **IMPOSITION SUR LES VENTES**, sélectionnez le menu **Groupe de taxe de vente d’article**, puis sélectionnez **TOUT**.

1. Sous **IMPOSITION SUR LES ACHATS**, sélectionnez le menu **Groupe de taxe de vente d’article**, puis sélectionnez **TOUT**.

1. Sous **PRIX**, dans le champ **Prix d’achat**, saisissez **30,00**.

1. Dans le champ **Prix de vente**, entrez **30,00**.

1. Sous **GROUPES DE RÉFÉRENCE**, sélectionnez le menu **Groupe de modèles d’article**, puis sélectionnez **FIFO premier entré, premier sorti**.

1. Dans le menu **Groupe d’articles**, sélectionnez **CarAudio**.

1. Dans le menu **Groupe de dimensions de stockage**, sélectionnez **SiteWH**.

1. Sous **UNITÉS DE MESURES**, vérifiez que les valeurs suivantes sont définies :

    | **Paramètre**| **Valeur**|
    | :--- | :--- |
    | Unité de stock| pièce|
    | Unité d’achat| pièce|
    | Unité de vente| pièce|
    | Unité de nomenclature| pièce|

1. Cliquez sur **OK**.

1. Pour vous assurer que le produit est finalisé, dans le volet Actions, sélectionnez **Produit**, puis, sous **Mettre à jour**, sélectionnez **Contrôler**.

1. Vérifiez que vous voyez la bannière d’information confirmant que toutes les valeurs de champ requises ont été validées.

1. Fermez toutes les pages et revenez à la page d’accueil.

## Exercice 2 : Découvrir la gestion des entrepôts

### Créer un entrepôt

1. À l’aide du volet de navigation, sélectionnez **Modules** > **Gestion des stocks** > **Configuration** > **Décomposition du stock** > **Entrepôts**.

1. Sur la page des entrepôts, sélectionnez **Nouveau** dans le volet Actions.

1. Dans le champ **Entrepôt**, saisissez **150**.

1. Dans la zone **Nom**, entrez **Outpost Warehouse**.

1. Sélectionnez le menu **Site**, puis sélectionnez **1 Production d’enceintes**.

1. Sélectionnez le raccourci **Noms d’emplacement**.

1. Les options de cette section définissent le format par défaut des noms d’emplacement.

1. Définissez les options **Inclure allée** et **Inclure rayon** sur **Oui**.

1. Définissez l’option **Inclure étagère** sur **Oui**.

1. Dans le champ **Format** pour l’étagère, saisissez **-##**.

1. Dans le volet Actions, sélectionnez **Entrepôt**.

1. Sous **Mettre à jour**, sélectionnez **Assistant Emplacement**.

1. Sur la page d’accueil, vérifiez les informations, puis sélectionnez **Suivant** dans le coin inférieur droit.

1. Décochez les cases **Quais de réception** et **Emplacements de stockage en gros**.

1. Sélectionnez **Suivant** et vérifiez les informations.

1. Continuez sur chaque page, puis une fois ce travail terminé, sélectionnez **Terminer**.

1. Fermez la page et revenez à la page d’accueil.

### Créer un accord commercial pour le prix de vente

1. À l’aide du volet de navigation, sélectionnez **Modules** > **Gestion des informations produit** > **Produits** > **Produits lancés**.

1. Sur la page de détails Produits lancés, cherchez le produit dont le numéro est **GTL201**.

1. À gauche du produit **GTL201**, cochez la case **Sélectionner ou désélectionner la ligne**.

1. Dans le volet Actions, sélectionnez **Vendre**, puis, sous **ACCORDS COMMERCIAUX**, sélectionnez **Créer des accords commerciaux**.

1. Dans le volet Actions, sélectionnez **+ Nouveau**.

1. Sélectionnez la colonne **Nom**, puis ouvrez le menu et sélectionnez **S_Price**.

1. Dans le volet Actions, sélectionnez **Lignes**.

1. Dans les Lignes de journal, sur la page de l’accord commercial, dans la colonne **Relation d’article**, ouvrez le menu et sélectionnez **GTL201**.

1. Il s’agit du numéro d’article du produit que vous avez créé.

1. Dans la colonne **Entrepôt**, sélectionnez le menu, puis sélectionnez **150**.

1. Vous devrez peut-être faire défiler l’écran vers la droite pour afficher la colonne.

1. Dans la colonne **Montant en devise**, dans le champ, saisissez **100,00**.

1. Dans la section Détails, dans le champ **Date de début**, saisissez la première date de l’année en cours.

1. Dans le volet Actions, sélectionnez **Contrôler** > **Contrôler toutes les lignes**.

1. Dans le volet **Validation du journal prix/remises**, sélectionnez **OK**.

1. Vérifiez qu’il n’y a aucune erreur.

1. Dans le volet Actions, sélectionnez **Valider**.

1. Dans le volet **Validation du journal prix/remises**, sélectionnez **OK**.

1. Vérifiez que l’opération est terminée.

1. Fermez la page.

1. Sur la page Détails des produits lancés, dans le volet Actions, sous **Vendre** > **ACCORDS COMMERCIAUX**, sélectionnez **Afficher les accords commerciaux**.

1. Normalement, l’accord commercial est validé. Vérifiez la ligne pour voir les informations relatives au prix.

1. Fermez les pages et revenez à la page d’accueil.

## Exercice 3 : Découvrir la gestion de la production

### Créer un ordre de fabrication pour un produit

1. À l’aide du volet de navigation, sélectionnez **Modules** > **Contrôle de la production** > **Ordres de fabrication** > **Tous les ordres de fabrication**.

1. Dans le volet Actions, sélectionnez **Nouvel ordre de fabrication**.

1. Dans le volet **Créer un ordre de fabrication**, sous **IDENTIFICATION**, dans le champ **Numéro d’article**, saisissez **D0004**, puis sélectionnez l’article identifié.

1. Sous **PRODUCTION**, dans la zone **Livraison**, sélectionnez une date ultérieure d’un mois à la date du jour.

1. La date de livraison indique quand l’ordre de fabrication doit prendre fin pour une livraison dans les temps. Cette date peut être utilisée dans le processus de planification. Par exemple, vous pouvez planifier la commande à rebours à partir de la date de livraison.

1. Dans le champ **Quantité**, saisissez **30**.

1. Sélectionnez **Créer**.

1. Fermez toutes les pages et revenez à la page d’accueil.

## Exercice 4 : Découvrir la gestion des stocks

### Créer un journal de comptage avec le produit pour l’entrepôt créé

1. À l’aide du volet de navigation, sélectionnez **Modules** > **Gestion des stocks** > **Entrées de journal** > **Inventaire des articles > Comptage**.

1. Dans le volet Actions, sélectionnez **+ Nouveau**.

1. Dans le volet **Créer le journal de stock**, sous **Comptage par**, utilisez l’option **Entrepôt** pour la définir sur **Oui**.

1. Sélectionnez **OK**.

1. Sur la page du journal d’inventaire de stock, dans le raccourci **Détails d’en-tête de journal**, sous la barre d’outils **Lignes de journal**, sélectionnez **+ Nouveau**.

1. Dans la colonne **Numéro d’article**, sélectionnez le menu, puis sélectionnez **GTL201**.

1. Dans la colonne **Entrepôt**, sélectionnez le menu, puis sélectionnez **150**.

1. Dans le champ **Compté**, entrez **100,00**.

1. Ceci définira le nombre d’articles stockés dans l’entrepôt pour ce produit.

1. Dans le volet Actions, sélectionnez **Contrôler**.

1. Dans le volet **Vérifier le journal**, sélectionnez **OK**.

1. Dans le volet Actions, sélectionnez **Valider**.

1. Dans le volet **Valider le journal**, sélectionnez **OK**.

1. Fermez toutes les pages et revenez à la page d’accueil.

### Consulter le stock disponible pour le produit

1. À l’aide du volet de navigation, sélectionnez **Modules** > **Gestion des stocks** > **Recherches et états** > **Liste disponible**.

1. Dans le volet Actions, sélectionnez **Dimensions**.

1. Dans le volet **Affichage de la dimension**, sous **DIMENSIONS DE STOCKAGE**, cochez les cases **Site** et **Entrepôt**, puis sélectionnez **OK**.

1. Dans le volet **Filtres**, sélectionnez **Appliquer**.

1. Localisez et consultez le stock disponible pour **GTL201**.

1. Fermez toutes les pages et revenez à la page d’accueil.

## Exercice 5 : Découvrir les approvisionnements

### Créer une commande fournisseur avec un produit

1. À l’aide du volet de navigation, sélectionnez **Modules** > **Approvisionnements** > **Commandes fournisseur** > **Toutes les commandes fournisseur**.

1. Sur la page Toutes les commandes fournisseur, dans le volet Actions, sélectionnez **+ Nouveau**.

1. Dans le volet **Créer une commande fournisseur**, sélectionnez le menu **Compte fournisseur**, puis sélectionnez **US-101**.

1. Lorsque vous sélectionnez un fournisseur, les détails de l’enregistrement du fournisseur, tels que l’adresse, le compte de facturation, les conditions de livraison et le mode de livraison, sont copiés comme valeurs par défaut dans l’en-tête commande. Vous pouvez modifier ces valeurs à tout moment.

1. Dans la section **Général**, sous **DIMENSIONS DE STOCKAGE**, sélectionnez le menu **Site**, puis sélectionnez **1 Production d’enceintes**.

1. Sous **DATES**, fixez la **Date de livraison** à une semaine à compter de la date du jour.

1. Sélectionnez **Administration**.

1. Sélectionnez le menu **Auteur de la commande**, puis sélectionnez **Lars Giusti** pour spécifier qui passe la commande.

1. Dans le volet **Créer une commande fournisseur**, sélectionnez **OK**.

1. Sur la barre d’outils, sélectionnez **Ligne de commande fournisseur**.

1. Sous **AFFICHAGE**, sélectionnez **Dimensions**.

1. Dans le volet **Affichage des dimensions**, sous **DIMENSIONS DE PRODUIT**, cochez la case **Couleur**.

1. Sélectionnez **OK**.

1. Dans la colonne **Numéro d’article**, sélectionnez le menu, puis sélectionnez **T0005**.

1. Dans la colonne **Numéro de variante**, sélectionnez le menu, puis sélectionnez l’une des couleurs.

1. Dans le champ **Quantité**, entrez **15**.

1. Sous les **Lignes de commande fournisseur**, au bas de la page, sélectionnez le raccourci **Détails de ligne**.

1. Il est possible que cet onglet soit déjà développé.

1. Sélectionnez l’onglet **Livraison**. Dans le champ **Date de livraison**, utilisez la date affectée actuelle ou saisissez une date à venir.  
    Une date de livraison unique peut être affectée à chaque ligne de commande. La date est héritée du champ de l’en-tête commande fournisseur, mais vous pouvez la modifier.

1. Notez votre numéro de commande fournisseur. Vous en aurez besoin ultérieurement.

1. Dans le volet Actions, sélectionnez **Enregistrer**.

1. Fermez la page Ligne de commande fournisseur.

1. Sur la page Toutes les commandes fournisseur, utilisez la fonctionnalité **Filtre** et recherchez votre nouvelle commande fournisseur.

1. Une fois terminé, fermez la page Toutes les commandes fournisseur et revenez à la page d’accueil.
