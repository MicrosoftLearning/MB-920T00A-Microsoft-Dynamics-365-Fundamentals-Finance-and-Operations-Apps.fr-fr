---
demo:
  title: "Démonstration\_2\_: Créer une facture"
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
---

## <a name="demo-2---create-an-invoice"></a>Démonstration 2 : Créer une facture

1. Accédez à l’espace de travail  **Gestion de projets**.  
    In this demo, we'll go over the process of invoicing a single project within project operations. Although it's possible to perform mass invoicing, for demonstration purposes we will focus on just a single time and material project. We'll also see the posting results and financial insights within the project statement. Let's start with project invoicing. 

1. In the top-right company picker, verify the legal entity you are connected to is<bpt id="p1"> **</bpt>USSI<ept id="p1">**</ept>. If it's not, change the legal entity to<bpt id="p1"> **</bpt>USSI<ept id="p1">**</ept>.  
    From the<bpt id="p1"> **</bpt>Project management<ept id="p1">**</ept> workspace, we can see all the active projects. We can search for projects using the filter, or in this example, we will select a known Project ID. 

1. Dans le tableau  **Projets actifs**, dans la colonne **ID du projet**, sélectionnez **00000093 Contoso Consulting**.  

1. Ensuite, ouvrez la page **Propositions de facture du projet** pour consulter toutes les factures précédemment traitées pour Contoso Consulting. 

1. Dans le volet Actions, sous l’onglet **FACTURE**, sélectionnez **Propositions de facture du projet**. 

1. Sur la page **Propositions de facture du projet**, dans la barre de navigation, sélectionnez **Nouvelle**, puis **Proposition de facture**.  
    Puisqu’il s’agit d’une simple facture de régie, inutile de sélectionner l’option Proposition de facture à partir de la règle de facturation. 

    ![Capture d’écran de la page Propositions de facture du projet où la nouvelle proposition de facture est mise en surbrillance](./media/projops_invoice_1_new_invoice_proposal.png)

1. Dans le volet **Créer une proposition de facture**,  pointez sur les zones sous **Sélectionner les transactions**.  
    From here, we can select things such as the invoicing method, the invoice date, the funding source, and the project. We can also choose to include sub projects, as well as incorporate transaction types, the start and end dates for transactions, and any financial dimensions we need. 

    ![Capture d’écran du volet Créer une proposition de facture où la section de sélection des transactions est mise en surbrillance](./media/projops_invoice_2_select_transactions.png)

1. Dans le menu déroulant **Projet**, sélectionnez **00000093 Contoso Consulting**. 

1. Dans cet exemple, assurez-vous que la **Date de facture** est définie sur **01/02/21**, la  **Date de début** sur **01/02/21** et la date de fin sur la date du jour.  
    Une fois les sélections effectuées, sélectionnez le bouton de recherche pour afficher les transactions répondant à ces critères.

1. Sélectionnez **Recherche**.  
    Dans cette démonstration, nous allons couvrir le processus de facturation d’un projet unique au sein de Project Operations.

1. Sous l’onglet **Transactions de projet**, sélectionnez **Sélectionner tout**.

1. Sélectionnez **OK**. 

1. Sur la page **Proposition de facture**, pointez sur la colonne **Montant de la ligne de facture**.   
    Ici, nous pouvons consulter un résumé de la facture et son montant, les transactions horaires et les dépenses.

    ![Capture d’écran de la page Proposition de facture où la colonne Montant de la ligne de facture est mise en surbrillance](./media/projops_invoice_3_invoice_line_amount_column.png)

1. Pointez sur l’onglet **Heure**.  

1. Pointez sur l’onglet  **Dépenses**.  
    Vous pouvez également choisir de passer à la transaction de dépense.  
Ensuite, intéressons-nous au bouton des totaux pour étudier la facture du point de vue des coûts et des produits.

1. Dans la barre de navigation, sélectionnez  **Totaux**.

1. Sur la page **Totaux**, pointez sur la colonne **COMPTABILITÉ GÉNÉRALE**, la colonne **CLIENT** et la  **colonne Remise ligne**.  
    Sur l’écran des totaux, nous pouvons constater l’impact sur la comptabilité générale, sur les informations client (par exemple, les limites de crédit, les remises ou les taxes de vente), ainsi que sur le net de la facture. 

1. Sur le côté droit de l’écran, sélectionnez le **X** pour fermer la page.  
    Bien que la facturation de masse soit proposée, nous allons nous concentrer sur un seul projet en régie pour les besoins de cette démonstration. 

1. Sur la page **Proposition de facture**, dans la barre de navigation, sélectionnez **Aperçu avant impression**. 

1. Dans la boîte de dialogue, sélectionnez **Aperçu avant impression**.  
    Voici un exemple d’aperçu avant impression de facture pro forma. 

1. Sélectionnez le**X** pour fermer la page.  
    Après avoir validé toutes les informations et une fois satisfait de l’aperçu avant impression de la facture, vous pouvez valider la proposition de facture.

1. Dans la barre de navigation, sélectionnez **Valider**.

1. Sélectionnez l’onglet **Paramètres**. 

1. Sous **PARAMÈTRE**, définissez **Validation** sur **Oui**.

1. Sous **OPTIONS D’IMPRESSION**, définissez **Imprimer la facture** sur **Oui**.

1. Sélectionnez **OK**.

1. Dans la page **Facture**, pointez sur le numéro de **Facture**.  
    Un numéro de facture a été généré.  
    Une fois la facture validée, nous pouvons passer en revue les informations dans le journal des factures et accéder aux écritures comptables.

1. Accédez à l’espace de travail  **Gestion de projets**.

1. Dans le tableau **Projets actifs**, sélectionnez le projet **00000093** **Contoso consulting**.

1. Dans le volet Actions, sous l’onglet **FACTURE**,  sélectionnez **Journaux des factures**.

1. Sur la page **Journal des factures**, dans la barre d’action, sélectionnez **Pièce justificative**.

1. Sur la page **Pièces comptables**, pointez sur la colonne **Compte général**.  
    Nous aborderons également la validation des résultats et les informations financières présentes sur le relevé de projet.

1. Accédez à l’espace de travail **Gestion de projets**.  

1. Dans le tableau **Projets actifs**, sélectionnez le **projet 00000093 Contoso consulting**.

1. Sur la page **Contoso Consulting**, dans la barre de navigation, sélectionnez **Contrôle**.  
    Ici, nous voyons tous les détails du projet.  
    À présent, intéressons-nous aux finances du projet sur un relevé de projet.

1. Sélectionnez **Statistiques de projet**.

1. Sur la page **Statistiques de projet**, pointez sur la section **DATE DU PROJET**.   
Vous pouvez créer un relevé pour la période de votre choix.

1. Sélectionnez la zone **De** et saisissez **2/1/2021**.
1. 
1. Sélectionnez la zone **À** et saisissez la date du jour.

1. Lorsque vous avez terminé, sélectionnez **Calculer**.

    ![Capture d’écran de la page Statistiques de projet où l’option Calculer est mise en surbrillance](./media/projops_invoice_4_calculate.png)

1. Pointez sur **Transactions**.  
    Commençons par la facturation du projet.
