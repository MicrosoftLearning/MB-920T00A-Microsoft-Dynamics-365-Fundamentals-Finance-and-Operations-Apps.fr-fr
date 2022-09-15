---
lab:
  title: "Labo 3\_: Créer un journal d’inventaire"
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>Module 3 : Découvrir les principes fondamentaux de Microsoft Dynamics 365 Supply Chain Management

## <a name="lab-3---create-a-counting-journal"></a>Labo 3 : Créer un journal d’inventaire

1. On the Finance and Operations home page, in the top right, verify you are working with the <bpt id="p1">**</bpt>USMF<ept id="p1">**</ept> company. If necessary, select the company, and from the drop down, select <bpt id="p1">**</bpt>USMF<ept id="p1">**</ept>.

2. Dans le volet de navigation gauche, sélectionnez **Modules** > **Gestion des stocks** > **Entrées de journal** > **Inventaire des articles** > **Comptage**.

3. Select the <bpt id="p1">**</bpt>+New<ept id="p1">**</ept> button in the action pane. The <bpt id="p1">**</bpt>Create inventory journal<ept id="p1">**</ept> dialog form will appear with the <bpt id="p2">**</bpt>OK<ept id="p2">**</ept> button in the bottom. Select the <bpt id="p1">**</bpt>OK<ept id="p1">**</ept> button.

4. Le formulaire du journal d’inventaire de stock s’affiche avec des informations d’en-tête et des détails.

![Capture d’écran du formulaire du journal d’inventaire de stock avec des informations d’en-tête et des détails renseignés.](../media/lp-scm-m-002-warehouse-inventory-mgmt-06.png)

5. Sélectionnez **Créer des lignes -&gt; En ligne** dans le volet Action.

6. Dans le volet de la boîte de dialogue **Créer un journal d’inventaire disponible**, définissez les champs **Entrepôt**, **État du stock**, Emplacement et **Contenant** sur **Oui**. 

![Capture d’écran du volet de la boîte de dialogue Créer un journal d’inventaire disponible avec les champs définis comme décrit.](../media/lp-scm-m-002-warehouse-inventory-mgmt-07.png)

7. Expand the <bpt id="p1">**</bpt>Record to include<ept id="p1">**</ept> section and select the <bpt id="p2">**</bpt>Filter<ept id="p2">**</ept> link. In the <bpt id="p1">**</bpt>Item number<ept id="p1">**</ept> field, select <bpt id="p2">**</bpt>A0001<ept id="p2">**</ept>, and then select <bpt id="p3">**</bpt>OK<ept id="p3">**</ept>.

8. Sélectionnez **OK** au bas du formulaire de la boîte de dialogue **Créer un journal d’inventaire disponible**.

La quantité disponible de l’article A0001 apparaît dans la section **Lignes feuille** avec la répartition du site, de l’entrepôt, de l’emplacement et le contenant.

9. In the <bpt id="p1">**</bpt>Counted<ept id="p1">**</ept> column of the <bpt id="p2">**</bpt>Journal line<ept id="p2">**</ept> section, enter the numbers counted in each Site/Warehouse/Location/License plate. Note the following:

    - Si la quantité **disponible** est identique à la quantité **comptée**, le champ **Quantité** est vide.

    - Si la valeur du champ **Compté** est supérieure à celle du champ **Disponible**, le champ **Quantité** contient une valeur positive.

    - Si la valeur du champ **Compté** est inférieure à celle du champ **Disponible**, le champ **Quantité** contient une valeur négative.

10. Sélectionnez le bouton **Valider** dans le volet Action, puis sélectionnez le bouton **Publier**.

11. Fermez la page et revenez à la page d’accueil.
