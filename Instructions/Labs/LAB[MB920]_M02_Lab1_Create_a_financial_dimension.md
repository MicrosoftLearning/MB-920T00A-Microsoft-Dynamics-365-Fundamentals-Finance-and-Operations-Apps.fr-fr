---
lab:
    title: 'Labo 1 : Créer une dimension financière'
    module: 'Module 2 : Découvrir les principes de base de Microsoft Dynamics 365 Finance'
---

## Labo 1 : Créer une dimension financière

## Objectifs

Utilisez la page Dimensions financières pour créer des dimensions financières que vous pouvez utiliser comme segments de compte pour les plans de comptes. Il existe deux types de dimensions financières : les dimensions personnalisées et les dimensions reposant sur des entités. Les dimensions personnalisées sont partagées par plusieurs entités juridiques et les valeurs sont entrées et gérées par les utilisateurs. Pour les dimensions reposant sur des entités, les valeurs sont définies ailleurs dans le système, par exemple dans les entités Clients ou Magasins. Certaines dimensions reposant sur des entités sont partagées par plusieurs entités juridiques, tandis que d’autres sont spécifiques à une entreprise.

Vous devez créer une dimension financière personnalisée qui sera utilisée par votre entreprise.

## Mise en place du labo

   - **Durée estimée** : 5 minutes

## Instructions

1. Sur la page d’accueil de Finance and Operations, en haut à droite, vérifiez que vous travaillez avec la société USMF.

1. Si nécessaire, sélectionnez la société, puis, dans le menu, sélectionnez **USMF**.

1. Dans le volet de navigation de gauche, sélectionnez **Modules** > **Comptabilité** > **Plan de comptes** > **Dimensions** > **Dimensions financières**.

1. Dans le menu en haut sélectionnez **+ Nouveau**.

1. Sur la page Dimensions financières, sélectionnez le menu **Utiliser les valeurs de**, puis **< Dimension personnalisée >**.

1. Dans le champ **Dimension**, saisissez **Affliate_Revenue**.

1. Dans la zone **Nom de la colonne de rapport**, saisissez **Afflt**.

1. Dans le menu du haut, sélectionnez **Activer**.

    ![Capture d’écran affichant la nouvelle dimension financière personnalisée avec le menu Utiliser les valeurs à partir de, Nom de dimension, Nom de la colonne de l’état et Activer en surbrillance](./media/lp2-m3-new-financial-dimension.png)

1. Vérifiez les informations dans la boîte de dialogue, puis cliquez sur **Fermer**.

1. Consultez la bannière de notification d’avertissement.

    ![Capture d’écran affichant une bannière d’informations d’avertissement avertissant qu’il est nécessaire d’être en mode de maintenance pour activer une nouvelle dimension.](./media/lp2-m3-activation-warning-banner.png)

    >[!REMARQUE] Vous pouvez activer et désactiver le mode de maintenance directement au moyen de Lifecycle Services (LCS) dans vos environnements de bac à sable et de production. Plus d’informations sur la gestion de Lifecycle Services sont disponibles sur [https://docs.microsoft.com/en-us/dynamics365/fin-ops-core/dev-itpro/deployment/maintenanceoperationsguide-newinfrastructure](https://docs.microsoft.com/fr-fr/dynamics365/fin-ops-core/dev-itpro/deployment/maintenanceoperationsguide-newinfrastructure).
