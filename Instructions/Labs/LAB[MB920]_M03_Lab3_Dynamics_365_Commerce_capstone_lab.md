---
lab:
    title: 'Labo 3 : Labo Capstone de Dynamics 365 Commerce'
    module: 'Module 3 : Découvrir les principes de base de Microsoft Dynamics 365 Commerce'
---

## Labo 3 : Labo Capstone de Dynamics 365 Commerce

## Objectif

Au cours de ce labo, vous découvrirez les bases de la configuration d’un siège dans Commerce. Parmi les fonctionnalités clés, on peut citer la configuration de canaux de vente au détail, la création d’assortiments et la mise en place de réductions.

## Mise en place du labo

   - **Durée estimée** : 30 minutes 

## Instructions

## Exercice 1 : Découvrir Commerce Headquarters

### Créer un magasin

1. Sur la page d’arrivée, dans la partie supérieure droite, vérifiez que l’entreprise **USRT** est sélectionnée.

1. Dans le cas contraire, sélectionnez l’entreprise affichée et saisissez **USRT**.

1. À l’aide du volet de navigation, sélectionnez **Modules** > **Commerce et vente au détail** > **Canaux** > **Magasins** > **Tous les magasins**.

1. Dans le volet Actions, sélectionnez **+ Nouveau** pour créer un magasin.

1. Dans la fenêtre Nouvel enregistrement, utilisez les paramètres du tableau suivant pour mettre à jour les valeurs :

    | **Paramètre**| **Valeur**|
    | :--- | :--- |
    | Nom| Magasin principal de Seattle|
    | Numéro de magasin| 000098|
    | Entrepôt| Seattle|
    | Entrepôt d’expédition| Seattle|
    | Fuseau horaire du magasin| (GMT-08:00) Pacifique|
    | Profil de la fonctionnalité| FN001|
    | Inventaire des stocks| Oui|
    | Profil du canal| Par défaut|
    | Profil hors connexion| Par défaut|
    | Groupe de taxe de vente| WA|
    | Utiliser la taxe selon la destination| Oui|
    | Carnet d’adresses client| Client de vente au détail|
    | Carnet d’adresses employé| Seattle|
    | Client par défaut| 3002|

1. Dans le volet Actions, sélectionnez **Enregistrer**.

1. Sélectionnez le raccourci **Relevé/clôture**, puis saisissez les informations suivantes :

    | Paramètre| Valeur|
    | :--- | :--- |
    | Calcul du montant du relevé| Dernier|
    | Différence maximale > Comptabilisation| 100,00|

1. Sélectionnez le raccourci **Dimensions financières**, puis saisissez les informations suivantes :

    | Paramètre| Valeur|
    | :--- | :--- |
    | BusinessUnit| 004|
    | Canal de vente au détail| 000210|

1. Sélectionnez le raccourci **Mise en page de l’écran**.

1. Dans le champ **ID mise en page de l’écran**, saisissez **A2CP16:9C**.

1. Dans le volet Actions, sélectionnez **Enregistrer**.

1. Dans le volet Actions, sélectionnez **Paramétrer**, puis, sous l’onglet **COPIER**, sélectionnez **Tout copier**.

1. Dans le volet **Tout copier**, ouvrez le menu **Magasin de départ**, puis sélectionnez **ANNAPOL**.

1. Si nécessaire, ouvrez le menu **Magasin de destination** et sélectionnez **00098**.

1. Sélectionnez **OK**.

1. Vérifiez que le message de confirmation s’affiche, puis fermez la page.

### Ajouter un groupe de produits à un assortiment et le publier

1. À l’aide du volet de navigation, sélectionnez **Modules** > **Administration d’organisation** > **Organisations** > **Hiérarchies d’organisation**.

1. Dans la liste de navigation, sélectionnez **Magasins de vente au détail par région**.

1. Dans le volet Actions, sélectionnez **Affichage**.

1. Sur la page Concepteur de hiérarchies, sélectionnez **Éditer** dans le volet Actions.

1. Sur la vignette **Ouest**, sélectionnez l’icône représentant des points de suspension (**...**).

1. Sur la page Concepteur de hiérarchies, sélectionnez **Insérer** > **Canal de vente au détail**.

1. Dans le volet **Canal de vente au détail**, sélectionnez **Magasin principal de Seattle**, puis **OK**.

1. Dans le volet Actions, sélectionnez **Enregistrer**.

1. Dans la boîte de dialogue, passez en revue les informations, puis sélectionnez **Fermer**.

1. Dans le volet Actions, sélectionnez **Publier**.

1. Dans le volet **Publier des modifications**, dans le champ **Date d’effet**, sélectionnez le premier jour du mois.

1. Dans le champ **Décrire les modifications**, saisissez **Ajout du magasin principal de Seattle**, puis sélectionnez **Publier**.

1. Dans la boîte de dialogue, passez en revue les informations, puis sélectionnez **Fermer**.

1. Dans le volet Actions, sélectionnez **Enregistrer**.

1. Dans la boîte de dialogue, passez en revue les informations, puis sélectionnez **Fermer**.

1. Fermez la page.

1. À l’aide du volet de navigation, sélectionnez **Modules** > **Commerce et vente au détail** > **Catalogues et assortiments** > **Assortiments**.

1. Sur la page Assortiments, sélectionnez **AW-Outlet**.

1. Dans le volet Actions, sélectionnez **Éditer**.

1. Dans la boîte de dialogue, sélectionnez **Oui** pour confirmer la sélection en vue de l’édition.

1. Sur la page AW-Outlet, sélectionnez le raccourci **Canal Commerce**.

1. Dans la barre d’outils, sélectionnez **+ Ajouter une ligne**.

1. Dans le volet **Choisir des nœuds d’organisation**, dans le menu **Hiérarchie d’organisation**, sélectionnez **Magasins de vente au détail par région**.

1. Sous **NŒUDS D’ORGANISATION DISPONIBLES**, sélectionnez **Magasin principal de Seattle**, puis sélectionnez l’icône représentant une flèche pointant vers la droite **Ajouter** pour l’ajouter aux **NŒUDS D’ORGANISATION SÉLECTIONNÉS**.

1. Sélectionnez **OK**.

1. Dans le volet Actions, sélectionnez **Publier**.

1. Dans la boîte de dialogue, passez en revue les informations, puis sélectionnez **Oui**.

1. Dans le volet Actions, sélectionnez **Éditer**.

1. Dans la boîte de dialogue de **confirmation**, sélectionnez **Oui**.

1. Sur la page AW-Outlet, sélectionnez l’onglet **Produits**.

1. Sur la page AW-Outlet, sélectionnez **+ Ajouter une ligne**.

1. Sélectionnez le menu **Catégorie**, sélectionnez **Sports d’équipe**, puis sélectionnez **OK**.

1. Dans le volet Actions, sélectionnez **Publier**.  

### Lancer une tâche du planificateur de vente au détail pour des produits

1. À l’aide du volet de navigation, sélectionnez **Modules** > **Commerce et vente au détail** > **Commerce et vente au détail informatique** > **Programme de distribution**.

1. Dans la liste de navigation, sélectionnez **1040 (Produits)**.

1. Dans le volet Actions, sélectionnez **Exécuter maintenant**.

1. Dans le volet **Synchronisation incrémentielle avec le planning « 1040 »**, vérifiez les informations et sélectionnez **OK**.

### Créer une remise de produit

1. À l’aide du volet de navigation, sélectionnez **Modules** > **Commerce et vente au détail** > **Tarification et remises** > **Toutes les promotions**.

1. Dans le volet Actions, sélectionnez **Nouveau** > **Remise**.

1. Sur la page Remises, dans la zone **Nom**, saisissez **Ouverture de boutique**.

1. Dans le raccourci **Détails**, dans le champ **Description**, saisissez **20 % de remise pour l’ouverture de la boutique**.

1. Dans le raccourci **Prix/remises**, dans le champ **Pourcentage de remise**, saisissez **20,00**.

1. Dans le raccourci **Période d’application**, dans le champ **Date d’effet**, saisissez une date appartenant au mois précédent.

1. Dans le champ **Date d’expiration**, saisissez une date ultérieure d’une semaine à la date du jour.

1. Dans le raccourci **Lignes**, dans la barre d’outils, sélectionnez **+ Ajouter**.

1. Sous la colonne **Catégorie**, sélectionnez le menu, puis **Sports d’équipe**, et sélectionnez **OK**.

1. Dans le volet Actions, sélectionnez **Enregistrer**.

1. Dans le volet Actions, sélectionnez **Groupes de prix**.

1. Sur la page Groupes de prix, sélectionnez le menu **Groupes de prix** et sélectionnez **Ouest**.

1. Dans le volet Actions, sélectionnez **Enregistrer**.

1. À l’aide du volet de navigation, sélectionnez **Modules** > **Commerce et vente au détail** > **Tarification et remises** > **Toutes les promotions**.

1. Dans la liste de navigation, sélectionnez **ST100101**.

1. Sur le raccourci **Général**, ouvrez le menu **Statut** et sélectionnez **Activé**.

1. Dans le volet Actions, sélectionnez **Enregistrer**.

1. Fermez le formulaire.

1. À l’aide du volet de navigation, sélectionnez **Modules** > **Commerce et vente au détail** > **Commerce et vente au détail informatique** > **Programme de distribution**.

1. Dans la liste de navigation, sélectionnez **1020 (Produits)**.

1. Dans le volet Actions, sélectionnez **Exécuter maintenant**.

1. Dans le volet **Synchronisation incrémentielle avec le planning « 1020 »**, vérifiez les informations et sélectionnez **OK**.
