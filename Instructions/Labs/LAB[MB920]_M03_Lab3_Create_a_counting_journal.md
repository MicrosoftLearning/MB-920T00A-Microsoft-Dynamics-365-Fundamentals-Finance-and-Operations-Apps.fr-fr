---
lab:
  title: "Labo 3\_: Créer un journal d’inventaire"
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>Module 3 : Découvrir les principes fondamentaux de Microsoft Dynamics 365 Supply Chain Management

## <a name="lab-3---create-a-counting-journal"></a>Labo 3 : Créer un journal d’inventaire

1. Dans la page d’accueil Finance and Operations, en haut à droite, vérifiez que vous travaillez avec la société **USMF**. Si nécessaire, sélectionnez la société, puis dans le menu déroulant, sélectionnez **USMF**.

2. Dans le volet de navigation gauche, sélectionnez **Modules** > **Gestion des stocks** > **Entrées de journal** > **Inventaire des articles** > **Comptage**.

3. Sélectionnez le bouton **+Nouveau** dans le volet de l’action. Le formulaire de la boîte de dialogue **Créer un journal d’inventaire** s’affiche avec le bouton **OK** en bas. Cliquez sur le bouton **OK**.

4. Le formulaire du journal d’inventaire de stock s’affiche avec des informations d’en-tête et des détails.

    ![Capture d’écran du formulaire du journal d’inventaire de stock avec des informations d’en-tête et des détails renseignés.](./media/lp-scm-m-002-warehouse-inventory-mgmt-06.png)

5. Sélectionnez **Créer des lignes -&gt; Disponible** dans le volet Actions.

6. Dans le volet de la boîte de dialogue **Créer un journal d’inventaire disponible**, définissez les champs **Entrepôt**, **État du stock**, **Emplacement** et **Contenant** sur **Oui**. 

    ![Capture d’écran du volet de la boîte de dialogue Créer un journal d’inventaire disponible avec les champs définis comme décrit.](./media/lp-scm-m-002-warehouse-inventory-mgmt-07.png)

7. Développez la section **Enregistrements à inclure** et sélectionnez le lien **Filtre**. Pour le champ **Numéro d’article** , tapez **A0001** dans les critères, puis sélectionnez **OK**.

8. Sélectionnez **OK** au bas du formulaire de la boîte de dialogue **Créer un journal d’inventaire disponible**.

La quantité disponible de l’article A0001 apparaît dans la section **Lignes feuille** avec la répartition du site, de l’entrepôt, de l’emplacement et le contenant.

9. Dans la colonne **Compté** de la section **Ligne feuille**, entrez les nombres comptés dans chaque site/entrepôt/emplacement/contenant. Notez les points suivants :

    - Si la quantité **disponible** est identique à la quantité **comptée**, le champ **Quantité** est vide.

    - Si la valeur du champ **Compté** est supérieure à celle du champ **Disponible**, le champ **Quantité** contient une valeur positive.

    - Si la valeur du champ **Compté** est inférieure à celle du champ **Disponible**, le champ **Quantité** contient une valeur négative.

10. Sélectionnez le bouton **Valider** dans le volet Action, puis sélectionnez le bouton **Publier**.

11. Fermez la page et revenez à la page d’accueil.
