---
demo:
  title: 'Démonstration 2 : Créer une facture'
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
ms.openlocfilehash: 2c63541757afd9de3bea634353c739ed099d0bc6
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/27/2022
ms.locfileid: "137909450"
---
## <a name="demo-2---create-an-invoice"></a>Démonstration 2 : Créer une facture

1. Accédez à l’espace de travail **Gestion de projets**.  
    Dans cette démonstration, nous allons couvrir le processus de facturation d’un projet unique au sein de Project Operations. Bien que la facturation de masse soit proposée, nous allons nous concentrer sur un seul projet en régie pour les besoins de cette démonstration. Nous aborderons également la validation des résultats et les informations financières présentes sur le relevé de projet. Commençons par la facturation du projet. 

1. Vérifiez que vous êtes bien connecté à l’entité juridique **USSI** dans le sélecteur de société situé dans le coin supérieur droit. Si tel n’est pas le cas, sélectionnez l’entité juridique **USSI**.  
    Depuis l’espace de travail **Gestion de projets**, nous voyons tous les projets actifs. Nous pouvons effectuer une recherche à l’aide du filtre ou, comme dans cet exemple, sélectionner un ID projet connu. 

1. Dans le tableau **Projets actifs**, dans la colonne **ID projet**, sélectionnez **00000093 Contoso Consulting**.  

1. Ensuite, ouvrez la page **Propositions de facture du projet** pour consulter toutes les factures précédemment traitées pour Contoso Consulting. 

1. Dans le volet d’action, dans l’onglet **FACTURE**, sélectionnez **Propositions de facture du projet**. 

1. Sur la page **Propositions de facture du projet**, dans la barre de navigation, sélectionnez **Nouvelle**, puis **Proposition de facture**.  
    Puisqu’il s’agit d’une simple facture de régie, inutile de sélectionner l’option Proposition de facture à partir de la règle de facturation. 

    ![Capture d’écran de la page Propositions de facture du projet où la nouvelle proposition de facture est mise en surbrillance](./media/projops_invoice_1_new_invoice_proposal.png)

1. Dans le volet **Créer une proposition de facture**, pointez sur les zones sous **Sélectionner les transactions**.  
    Ici, nous pouvons sélectionner divers éléments, tels que la méthode de facturation, la date de facture, la source de financement et le projet. Nous pouvons également choisir d’inclure des sous-projets, comme incorporer les types de transaction, les dates de début et de fin pour les transactions ou toutes dimensions financières nécessaires. 

    ![Capture d’écran du volet Créer une proposition de facture où la section de sélection des transactions est mise en surbrillance](./media/projops_invoice_2_select_transactions.png)

1. Dans le menu déroulant **Projet**, sélectionnez **00000093 Contoso Consulting**. 

1. Dans cet exemple, assurez-vous que la **Date de facture** est définie sur **01/02/21**, la **Date de début** sur **01/02/21** et la date de fin sur aujourd’hui.  
    Une fois les sélections effectuées, sélectionnez le bouton de recherche pour afficher les transactions répondant à ces critères.

1. Sélectionnez **Recherche**.  
    Ensuite, sélectionnez l’option Sélectionner tout pour facturer toutes les transactions. Cela permet d’inclure les éléments que nous avons sélectionnés pour les dépenses et les heures.

1. Sous l’onglet **Transactions de projet**, sélectionnez **Sélectionner tout**.

1. Sélectionnez **OK**. 

1. Sur la page **Proposition de facture**, pointez sur la colonne **Montant de la ligne de facture**.  
    Ici, nous pouvons consulter un résumé de la facture et son montant, les transactions horaires et les dépenses.

    ![Capture d’écran de la page Proposition de facture où la colonne Montant de la ligne de facture est mise en surbrillance](./media/projops_invoice_3_invoice_line_amount_column.png)

1. Pointez sur l’onglet **Heure**. 

1. Pointez sur l’onglet **Dépense**.  
    Vous pouvez également choisir de passer à la transaction de dépense.  
Ensuite, intéressons-nous au bouton des totaux pour étudier la facture du point de vue des coûts et des produits.

1. Dans la barre de navigation, sélectionnez **Totaux**.

1. Sur la page **Totaux**, pointez sur la colonne **COMPTABILITÉ GÉNÉRALE**, la colonne **CLIENT** et la colonne **Remise ligne**.  
    Sur l’écran des totaux, nous pouvons constater l’impact sur la comptabilité générale, sur les informations client (par exemple, les limites de crédit, les remises ou les taxes de vente), ainsi que sur le net de la facture. 

1. Sur le côté droit de l’écran, sélectionnez le **X** pour fermer la page.  
    À présent, nous sommes prêts à créer un aperçu avant impression pour nous assurer que toutes les informations de facturation sont correctes. Certaines organisations utilisent cet aperçu pendant les réunions pour passer en revue le projet et s’assurer que tout le monde approuve les totaux avant de finaliser la facture. 

1. Sur la page **Proposition de facture**, dans la barre de navigation, sélectionnez **Aperçu avant impression**. 

1. Dans la boîte de dialogue, sélectionnez **Aperçu avant impression**.  
    Voici un exemple d’aperçu avant impression de facture pro forma. 

1. Sélectionnez le **X** pour fermer la page.  
    Après avoir validé toutes les informations et une fois satisfait de l’aperçu avant impression de la facture, vous pouvez valider la proposition de facture.

1. Dans la barre de navigation, sélectionnez **Valider**.

1. Sélectionnez l'onglet **Paramètres** .

1. Sous **PARAMÈTRE**, définissez **Validation** sur **Oui**.

1. Sous **OPTIONS D’IMPRESSION**, définissez **Imprimer la facture** sur **Oui**.

1. Sélectionnez **OK**.

1. Sur la page **Facture**, pointez sur le **numéro de la facture**.  
    Un numéro de facture a été généré.  
    Une fois la facture validée, nous pouvons passer en revue les informations dans le journal des factures et accéder aux écritures comptables.

1. Accédez à l’espace de travail **Gestion de projets**.

1. Dans le tableau **Projets actifs**, sélectionnez le projet **00000093** **Contoso Consulting**.

1. Dans le volet d’action, dans l’onglet **FACTURE**, sélectionnez **Journaux des factures**.

1. Sur la page **Journal des factures**, dans la barre d’action, sélectionnez **Pièce justificative**.

1. Sur la page **Pièces comptables**, pointez sur la colonne **Compte général**.  
    Voici les résultats validés dans la comptabilité générale. Les comptes généraux sont déterminés en fonction du paramétrage de compte et des dimensions financières appliquées à chaque projet.

1. Accédez à l’espace de travail **Gestion de projets**. 

1. Dans le tableau **Projets actifs**, sélectionnez le projet **00000093 Contoso Consulting**.

1. Sur la page **Contoso Consulting**, dans la barre de navigation, sélectionnez **Contrôle**.  
    Ici, nous voyons tous les détails du projet.  
    À présent, intéressons-nous aux finances du projet sur un relevé de projet.

1. Sélectionnez **Statistiques de projet**.

1. Sur la page **Statistiques de projet**, pointez sur la section **DATE DU PROJET**.  
Vous pouvez créer un relevé pour la période de votre choix.

1. Sélectionnez la zone **Date de début** et saisissez **01/02/2021**.
1. 
1. Sélectionnez la zone **Date de fin** et saisissez la date d’aujourd’hui.

1. Une fois terminé, sélectionnez **Calculer**.

    ![Capture d’écran de la page Statistiques de projet où l’option Calculer est mise en surbrillance](./media/projops_invoice_4_calculate.png)

1. Pointez sur **Transactions**.  
    Une fois les données actualisées, le chef de projets peut choisir de consulter les détails transactionnels pour prendre des décisions relatives au projet ou d’apporter les modifications nécessaires. Dans cette démonstration, nous avons traité une facture de régie avec une transaction horaire et de dépense. Nous avons vérifié et validé la facture dans l’aperçu, passé en revue la validation de la comptabilité et remarqué l’impact financier sur le relevé de ce projet.
