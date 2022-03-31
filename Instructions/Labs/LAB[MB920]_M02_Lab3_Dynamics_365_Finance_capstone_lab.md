---
lab:
  title: 'Labo 3 : Labo Capstone de Dynamics 365 Finance'
  module: 'Module 2: Learn the Fundamentals of Microsoft Dynamics 365 Finance'
ms.openlocfilehash: c6f655349c360df83fb064fe716cd712ff61c2aa
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/27/2022
ms.locfileid: "137909625"
---
## <a name="lab-3---dynamics-365-finance-capstone-lab"></a>Labo 3 : Labo Capstone de Dynamics 365 Finance

## <a name="objective"></a>Objectif

Au cours de ce labo, vous découvrirez les fonctions essentielles de Microsoft Dynamics 365 Finance. Vous apprendrez à gérer la comptabilité générale en créant une entité, en créant un compte et des valeurs de dimension, mais aussi en générant une balance comptable. Vous découvrirez également la comptabilité fournisseur en créant des fournisseurs et des commandes fournisseur, ainsi que la facturation et le règlement des factures. Enfin, vous apprendrez à gérer la comptabilité client en créant des clients, des factures, une balance âgée et en appliquant des paiements client.

## <a name="lab-setup"></a>Mise en place du labo

   - **Durée estimée** : 45 minutes

## <a name="exercise-1-explore-the-general-ledger"></a>Exercice 1 : Découvrir la comptabilité

### <a name="create-a-new-legal-entity"></a>Créer une entité juridique

1. À l’aide du volet de navigation, sélectionnez **Modules** > **Administration d’organisation** > **Organisations** > **Entités juridiques**.

1. Dans le volet Actions, sélectionnez **+ Nouveau** pour créer une entité juridique.

1. Dans le volet **Nouvelle entité**, créez une entité en utilisant les informations suivantes, puis sélectionnez **OK** :

    | **Paramètre** | **Valeur** |
    | :--- | :--- |
    | Nom | Contoso Training USA |
    | Company | USTR |
    | Pays/région | États-Unis |

1. Sur la page Entités juridiques, sélectionnez le raccourci **Adresses**, puis sélectionnez **Modifier**.

1. Dans le récapitulatif, entrez les informations suivantes, puis sélectionnez **OK** :

    | **Paramètre**| **Valeur**|
    | :--- | :--- |
    | Code postal| 98052|
    | Rue| 123 Main Street|
    | Principal pour le pays/région | Vérifiez que **Oui** est bien sélectionné. |

1. Sélectionnez le raccourci **Informations de contact**.

1. Sélectionnez **+ Ajouter**, puis entrez les informations de contact suivantes :

    | **Paramètre**| **Valeur**|
    | :--- | :--- |
    | Description| Main Office|
    | Adresse ou numéro de contact| 888-555-1234|
    | Principal| Cochez la case. |

1. Sélectionnez le raccourci **Immatriculation fiscale**.

1. Dans le champ **Numéro d’identification fiscale**, saisissez **88-1234567**.

1. Dans le volet Actions, sélectionnez **Enregistrer**.

1. Dans le volet de navigation, sélectionnez **Accueil**.

### <a name="create-a-new-account-in-an-existing-chart-of-accounts"></a>Créer un compte dans un plan de comptes existant

1. Sur la page d’accueil, dans la partie supérieure droite, vérifiez que l’entreprise **USMF** est sélectionnée.  
    Dans le cas contraire, sélectionnez l’entreprise affichée et modifiez-la pour passer à **USMF**.

1. Dans le volet de navigation, sélectionnez **Modules** > **Comptabilité** > **Plan comptable** > **Comptes** > **Comptes principaux**.

1. Dans le volet Actions, sélectionnez **+ Nouveau** pour créer un compte de produit.

1. Sur la page Comptes principaux, saisissez les informations suivantes :

    | **Paramètre**| **Valeur**|
    | :--- | :--- |
    | Compte principal| 401500|
    | Nom| Produit de formation|
    | Type de compte principal| Chiffre d’affaires |

1. Dans le volet Actions, sélectionnez **Enregistrer**.

### <a name="add-a-new-dimension-value"></a>Ajouter une valeur de dimension

1. Avec le volet de navigation, sélectionnez **Modules** > **Comptabilité** > **Plan de comptes** > **Dimensions** > **Dimensions financières**.

1. Dans la liste de navigation, sélectionnez **Ligne de service**.  
    Vous pouvez également utiliser le **Filtre** pour chercher **Ligne de service**.

1. Dans le volet Actions, sélectionnez **Valeurs de dimension**.

1. Dans le volet Actions, sélectionnez **+ Nouveau**.

1. Dans les champs **Valeur de dimension** et **Description**, saisissez **Services de formation**.

1. Dans le volet Actions, sélectionnez **Enregistrer**.

### <a name="use-an-account-and-dimension-value-in-a-general-journal"></a>Utiliser un compte et une valeur de dimension dans un journal des opérations diverses

1. À l’aide du volet de navigation, sélectionnez **Modules** > **Comptabilité** > **Entrées de journal** > **Journaux des opérations diverses**.

1. Dans le volet Actions, sélectionnez **+ Nouveau**.

1. Sur la première ligne de la liste, dans la colonne **Nom**, sélectionnez le menu, puis sélectionnez **Journal des opérations diverses**.

1. Dans le volet Actions, sélectionnez **Lignes**.

1. Dans la liste, dans la colonne **Date**, sélectionnez l’icône représentant un calendrier et changez la date pour qu’elle corresponde au premier jour du mois.

1. Dans la colonne **Compte**, sélectionnez le menu, puis saisissez les informations suivantes :

    | **Paramètre**| **Valeur**|
    | :--- | :--- |
    | MainAccount| 601200|
    | BusinessUnit| 004|
    | department| 025|
    | CostCenter| 009|
    | ItemGroup| Services|

1. Dans le champ **Description**, saisissez **Expense Reclass**.

1. Dans le champ **Débit**, saisissez **1000,00**.

1. Faites défiler vers la droite et, dans la colonne **Compte de contrepartie**, sélectionnez le menu, puis saisissez les informations suivantes :

    | **Paramètre**| **Valeur**|
    | :--- | :--- |
    | MainAccount| 602200|
    | BusinessUnit| 004|
    | department| 025|
    | CostCenter| 009|
    | ItemGroup| Services|

1. Dans le volet Actions, sélectionnez **Enregistrer**.

1. Dans le volet Actions, sélectionnez **Contrôler** > **Contrôler**.  
    Attendez que le contrôle du journal se termine.

1. Consultez la bannière d’avertissement.  
    Dans le cadre de cet exercice, vous pouvez ignorer le message d’avertissement.

1. Dans le volet Actions, sélectionnez **Valider**.

### <a name="run-a-trial-balance-using-a-dimension-set"></a>Lancer une balance comptable à l’aide d’un ensemble de dimensions

1. À l’aide du volet de navigation, sélectionnez **Modules** > **Comptabilité** > **Recherches et états** > **Balance comptable**.

1. Sur la page Balance comptable, sélectionnez **Calculer des soldes**.

1. Le bouton **Calculer des soldes** est situé sous les paramètres **DATE À INCLURE**.

1. Dans le tableau, consultez les résultats.

1. Sur la page Balance comptable, sous **Vue standard**, développez les **Paramètres**.

1. Sous **DATE À INCLURE**, sélectionnez le menu **Ensemble de dimensions financières**, puis sélectionnez **MA-BU-DEPT-CC**.

1. Sélectionnez **Calculer des soldes** pour afficher les dimensions utilisées dans le journal.

1. Fermez la page.

## <a name="exercise-2-explore-accounts-payable"></a>Exercice 2 : Découvrir la comptabilité fournisseur

### <a name="create-a-vendor"></a>Créer un fournisseur

1. À l’aide du volet de navigation, sélectionnez **Modules** > **Comptabilité fournisseur** > **Fournisseurs** > **Tous les fournisseurs**.

1. Dans le volet Actions, sélectionnez **+ Nouveau** pour créer un fournisseur.

1. Sur la page Nouvel enregistrement, créez un fournisseur à l’aide des informations suivantes :

    | **Paramètre**| **Valeur**|
    | :--- | :--- |
    | Compte fournisseur| V00001|
    | Nom| ABC Training, Inc|
    | Group| 20|

1. Dans le volet Actions, sélectionnez **Enregistrer**.

1. Sélectionnez le raccourci **Adresses**, puis sélectionnez **+ Ajouter**.

1. Dans le volet Nouvelle adresse, entrez les informations suivantes, puis sélectionnez **OK** :

    | **Paramètre**| **Valeur**|
    | :--- | :--- |
    | Nom ou description| Main Office|
    | Code postal| 98052|
    | Rue| 123 Front Street|

1. Dans le volet Actions, sélectionnez **Enregistrer**.

1. Sélectionnez le raccourci **Paiement**.

1. Dans le menu **Mode de paiement**, sélectionnez **CHÈQUE**.

1. Sélectionnez le raccourci **Taxe sur les honoraires**, puis saisissez les informations suivantes :

    | **Paramètre**| **Valeur**|
    | :--- | :--- |
    | Générer la déclaration des honoraires| Oui|
    | ID taxe fédérale| 82-1234567|
    | Type d’ID taxe| Numéro d'identification d'employeur (EIN)|
    | Zone de déclaration des honoraires| MISC-03|

1. Dans le volet Actions, sélectionnez **Enregistrer**.

1. Fermez le formulaire.

### <a name="create-a-purchase-order-for-the-new-vendor"></a>Créer une commande fournisseur pour le nouveau fournisseur

1. Dans V00001 : Sur la page ABC Training, Inc, dans le volet Actions, sélectionnez **Approvisionnement**.

1. Dans le volet Actions, sous l’onglet **NOUVEAU**, sélectionnez **Commande fournisseur**.

1. Sur la page Commande fournisseur, sous **Lignes de commande fournisseur**, saisissez les informations ci-dessous :

    | **Paramètre**| **Valeur**|
    | :--- | :--- |
    | Numéro d’article| S0001|
    | Quantité| 2|

    >[!NOTE] Vous devrez faire défiler l’écran vers la droite pour afficher la colonne **Quantité**.

1. Dans le volet Actions, sélectionnez **Enregistrer**.

1. Dans le volet Actions, sélectionnez **Achats**, puis, sous l’onglet **ACTIONS**, sélectionnez **Confirmer**.

### <a name="record-vendor-invoice-for-the-purchase-order"></a>Enregistrer une facture fournisseur pour la commande

1. Dans le volet Actions, sélectionnez **Facture**.

1. Dans l’onglet **GÉNÉRER**, sélectionnez **Facture**.

1. Dans le volet Actions, sélectionnez **Valeur par défaut de : Quantité de l’accusé de réception de marchandises**.

1. Dans le menu **Quantité par défaut pour les lignes**, sélectionnez **Quantité commandée**, puis sélectionnez **OK**.

1. Sur la page Facture fournisseur, saisissez les informations suivantes :

    | **Paramètre**| **Valeur**|
    | :--- | :--- |
    | Number| INV001|
    | Description de la facture| Service d’installation initiale|
    | Date de facture| *entrez la date du jour*|

1. Dans le volet Actions, sélectionnez **Enregistrer**.

1. Dans le volet Actions, sélectionnez **Mettre à jour le statut de rapprochement**.

1. Dans le volet Actions, sélectionnez **Valider**.

### <a name="settling-the-vendor-invoice"></a>Régler la facture fournisseur

1. Dans le volet de navigation de gauche, sélectionnez **Modules** > **Comptabilité fournisseur** > **Paiements** > **Journal des paiements fournisseur**.

1. Dans le volet Actions, sélectionnez **+ Nouveau**.

1. Sur la page Journal des paiements fournisseur, sur la première ligne, dans la colonne **Nom**, ouvrez le menu et sélectionnez **Paiement fournisseur**.

1. Dans le volet Actions, sélectionnez **Lignes** pour enregistrer un paiement.

1. Sur la page Paiements fournisseur, dans le champ **Compte**, saisissez **V00001**.

1. Dans la barre d’outils, sélectionnez **Générer des paiements**.

1. Sur la page Régler les transactions pour ABC Training, Inc, cochez la case dans la colonne **Marquer**.

1. Dans le coin inférieur droit, sélectionnez **OK**.

1. Dans le volet Actions, sélectionnez **Générer des paiements**.

1. Dans le volet **Générer des paiements**, entrez les informations suivantes, puis sélectionnez **OK** :

    | **Paramètre**| **Valeur**|
    | :--- | :--- |
    | Mode de paiement| CHECK|
    | Compte bancaire| USMF OPER|

1. Dans le volet **Paiement par chèque**, vérifiez les informations et sélectionnez **OK**.

    >[!ALERT] Une erreur de type **L’imprimante ayant le chemin XXX est introuvable** s’affichera. Vous pouvez l’ignorer. Aucune imprimante n’est installée dans le labo.

1. Faites défiler vers la droite et vérifiez que la colonne **Statut de paiement** indique bien **Envoyé**.

1. Dans le volet Actions, sélectionnez **Contrôler** > **Contrôler**.

1. Dans le volet Actions, sélectionnez **Valider**.

## <a name="exercise-3-explore-accounts-receivable"></a>Exercice 3 : Découvrir la comptabilité client

### <a name="create-a-customer"></a>Créer un client

1. À l’aide du volet de navigation, sélectionnez **Modules** > **Comptabilité client** > **Clients** > **Tous les clients**.

1. Dans le volet Actions, sélectionnez **+ Nouveau** pour créer un client.

1. Dans le volet **Créer un client**, créez le client en utilisant les informations suivantes, puis sélectionnez **Enregistrer** :

    | **Paramètre**| **Valeur**|
    | :--- | :--- |
    | Compte client| US-901|
    | Nom| Fabrikam Consulting Services|
    | Groupe de clients| 30|
    | Code postal| 98052|
    | Rue| 123 Middle Street|

1. Sur la page US-901 Fabrikam Consulting Services, sélectionnez le raccourci **Valeurs par défaut de paiement**.

1. Dans le menu **Mode de paiement**, sélectionnez **CHÈQUE**.

1. Sélectionnez le raccourci **Dimensions financières**.

1. Dans le champ **BusinessUnit**, saisissez **004**.

1. Dans le volet Actions, sélectionnez **Enregistrer**.

### <a name="create-a-free-text-invoice-for-the-new-customer"></a>Créer une facture financière pour le nouveau client

1. Dans le volet Actions, sélectionnez **Facture** et dans l’onglet **NOUVEAU**, sélectionnez **Facture financière**.

1. Sur la page US-901 Fabrikam Consulting Services, sous l’**en-tête** **Facture financière**, fixez la date de la **FACTURE** à la date du jour.

1. Sous **Lignes de facture**, apportez les modifications suivantes :

    | **Paramètre**| **Valeur**|
    | :--- | :--- |
    | Description| Consultant Service Training|
    | Compte principal| 401200|
    | Groupe de taxe de vente| WA|
    | Amount| 1500.00|

1. Dans le volet Actions, sélectionnez **Taxe de vente**.

1. Sur la page Transactions de taxe de vente, vérifiez l’enregistrement et sélectionnez **OK**.

1. Dans le volet Actions, sélectionnez **Valider**.

1. Dans le volet **Valider une facture de test vide**, sous **OPTIONS D’IMPRESSION**, définissez l’option **Imprimer la facture** sur **Oui**, puis sélectionnez **OK**.

1. Dans le volet **Paramètres de destination d’impression**, sélectionnez **OK** pour afficher la facture à l’écran.

1. Vérifiez-la, puis, une fois que vous avez terminé, fermez la facture.

1. Fermez le formulaire.

### <a name="run-an-accounts-receivable-aging-report-to-check"></a>Lancer une balance âgée de la comptabilité client à vérifier

1. À l’aide du volet de navigation, sélectionnez **Modules** > **Crédit et relances** > **Recherches et états** > **Clients** > **Balance âgée des clients**.

1. Dans le volet **Balance âgée des clients**, entrez les informations suivantes, puis sélectionnez **OK** :

    | **Paramètre**| **Valeur**|
    | :--- | :--- |
    | Agé tel que| Date du jour|
    | Définition d’une période antérieure| 30_60_90_180|
    | Détails| Années|

1. Dans la balance âgée des clients, sélectionnez l’icône représentant une flèche pointant vers le bas **Page suivante**, puis faites défiler jusqu’à la dernière page.
    Vérifiez la facture créée pour le client US-901.

1. Fermez le formulaire.

### <a name="apply-customer-payment-for-the-free-text-invoice"></a>Appliquer un paiement client à une facture financière

1. À l’aide du volet de navigation, sélectionnez **Modules** > **Comptabilité client** > **Paiements** > **Journal des paiements client**.

1. Dans le volet Actions, sélectionnez **+ Nouveau**.

1. Sur la page Journal des paiements client, dans la colonne **Nom**, ouvrez le menu et sélectionnez **Paiement client**.

1. Dans le volet Actions, sélectionnez **Entrer les paiements client**.

1. Dans le champ **Client**, saisissez **US-901**.  
    Attendez que les données soient chargées, puis cochez la case dans la colonne **Marquer**.

1. Au-dessus de la grille, dans le champ **Montant**, saisissez **1597,50**. Le montant indiqué dans le champ **Montant restant** doit automatiquement passer de **1597,50** à **0**.  
    Pour que cette valeur soit calculée, il est possible que vous deviez sélectionner un espace vide.

1. Dans le champ **Référence de paiement**, saisissez **Chèque n°123**.

1. Dans le volet Actions, sélectionnez **Enregistrer dans le journal**.

1. Fermez le formulaire.

1. Dans le volet Actions, sélectionnez **Lignes**.

1. Dans le volet Actions, sélectionnez **Contrôler** > **Contrôler**.

1. Dans le volet Actions, sélectionnez **Valider**.
