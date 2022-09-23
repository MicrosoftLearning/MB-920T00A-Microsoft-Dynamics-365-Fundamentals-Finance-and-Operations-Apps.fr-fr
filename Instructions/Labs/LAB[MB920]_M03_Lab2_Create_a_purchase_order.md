---
lab:
  title: "Labo\_2\_: Créer une commande fournisseur"
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>Module 3 : Découvrir les principes fondamentaux de Microsoft Dynamics 365 Supply Chain Management

## <a name="lab-2---create-a-purchase-order"></a>Labo 2 : Créer une commande fournisseur

## <a name="objectives"></a>Objectifs

It's more typical for purchase orders to be created automatically as result of master planning, direct delivery, and other processes. When created manually, a purchase order is usually created by a purchasing agent. Create a purchase order using the the USMF company.

## <a name="lab-setup"></a>Mise en place du labo

   - **Durée estimée** : 10 minutes

## <a name="instructions"></a>Instructions

1. Sur la page d’accueil de Finance and Operations, en haut à droite, vérifiez que vous travaillez avec la société USMF.

1. Si nécessaire, sélectionnez la société, puis, dans le menu, sélectionnez **USMF**.

1. En haut à gauche, sélectionnez le menu hamburger **Développer le volet de navigation**.

1. Sélectionnez **Modules** > **Approvisionnements** > **Commandes fournisseur** > **Toutes les commandes fournisseur**.

1. Sur la page Toutes les commandes fournisseur, dans le menu supérieur, sélectionnez **+ Nouvelle**.

1. Dans le volet Créer une commande fournisseur, sélectionnez le menu **Compte fournisseur**, puis sélectionnez **US-101**.

1. When you select a vendor, details from the vendor record, such as address, invoice account, delivery terms, and delivery mode, will be copied as default values into the order header. You can change these values at any time.

1. Développez la section **Général**.

1. Sous **DIMENSIONS DE STOCKAGE**, sélectionnez le menu **Site** et passez en revue la liste des sites.

1. The Site field, together with the Warehouse field, specifies where the procured goods or services must be delivered. The default delivery address is the site. Both fields can be populated with values set up for the selected vendor, or you can specify them manually.

1. Sous **DATES**, le champ Date de livraison permet de spécifier quand les biens et services achetés doivent être livrés.

1. You can specify a single delivery date for the order, or the individual order lines can be given unique delivery dates. If the delivery date specified here cannot be met for specific products or services because they have longer lead times, then those lines will be created with a later delivery date to accommodate for this.

1. Expand the <bpt id="p1">**</bpt>Administration<ept id="p1">**</ept> section. The <bpt id="p1">**</bpt>Orderer<ept id="p1">**</ept> box can be used to specify who is placing the order.

1. Les commandes fournisseur sont généralement créées automatiquement dans le cadre de la planification générale, de la livraison directe et d’autres processus.

1. Sélectionnez **OK**.

1. Une commande fournisseur créée manuellement est généralement créée par un agent d’achats.

    ![Image d’écran affichant l’emplacement du menu En-tête](./media/lp1-m3-purchase-order-header-option.png)

1. Sous **Lignes de commande fournisseur**, dans le menu, sélectionnez **Ligne de commande fournisseur**.

    ![Image d’écran montrant l’emplacement de l’option de menu Ligne de commande fournisseur](./media/lp1-m3-purchase-order-purchase-order-line-menu.png)

1. Sous **AFFICHAGE**, sélectionnez **Dimensions**.

1. Créez une commande fournisseur à l’aide de la société USMF.

1. Dans le volet d’affichage Dimensions, sous **DIMENSIONS DE PRODUIT**, cochez la case **Couleur**.

1. Facultatif : Si vous sélectionnez le bouton bascule Enregistrer le paramétrage, les dimensions que vous avez choisies s’afficheront également sur la grille des lignes de commande la prochaine fois que vous ouvrirez la page de commande fournisseur.

1. Sélectionnez **OK**.

1. Sélectionnez le menu de la cellule **Numéro d’article**, puis sélectionnez **T0004**.

1. N’oubliez pas que vous pouvez également taper dans la zone de filtre au lieu de faire défiler la liste.

1. Les lignes de commande sont créées pour les produits et services en spécifiant un numéro d’article ou en tant que dépenses en indiquant une catégorie d’approvisionnement.

1. Procurement category is used for adding lines where procured items are expensed directly, rather than going into inventory. This means that if you need to expense a purchase, you can do this by creating a purchase order line that specifies a procurement category, rather than creating a line with an item number. Items can also be associated with a procurement category and in this case, the procurement category is shown as informational only.

1. Sélectionnez le menu **Couleur**, passez en revue les options disponibles, puis sélectionnez l’une des couleurs ou combinaisons de couleurs.

1. Le site et l’entrepôt sont généralement renseignés avec les valeurs de l’en-tête commande, mais il est possible de remplacer les champs si certaines lignes doivent être livrées à des emplacements différents.

1. Dans la zone **Quantité**, saisissez **10**.

1. La quantité est automatiquement renseignée avec la quantité minimale de commande du produit si cela est bien configuré, ou avec la valeur 1.

1. Quelques informations supplémentaires :

    - <bpt id="p1">**</bpt>Unit<ept id="p1">**</ept>: Indicates the unit of measure for the ordered quantity. Normally, the unit is automatically provided from the purchasing unit on the product master data.

    - <bpt id="p1">**</bpt>Unit price<ept id="p1">**</ept>: Contains a value from either a purchase agreement or a trade agreement. It is possible to change the unit price on individual order lines—for example, if a unique price is negotiated with the vendor.

    - <bpt id="p1">**</bpt>Discount<ept id="p1">**</ept>: Represents a discount amount per unit. This discount therefore reduces the unit price by the discount. This discount is commonly supplied automatically from purchase agreements or trade agreements, but it is possible to override on individual lines if unique discounts have been negotiated with the vendor.

    - <bpt id="p1">**</bpt>Discount percentage<ept id="p1">**</ept>: When entered, this reduces the net amount for the line accordingly. The discount percent is often supplied automatically from purchase agreements or trade agreements, but it is possible to override on individual lines if a unique discount percentage has been negotiated with the vendor.

    - <bpt id="p1">**</bpt>Net amount<ept id="p1">**</ept>: Calculated from other fields on the line, including quantity, unit price, discount, and discount percent. It is possible to change the Net amount, but then the Unit Price, Discount, and Discount percent fields will be blank, and when you post toward the line, the amount posted will be proportional to the net amount. Generally, the Net Amount field is only used for displaying the net amount of the line.

1. Sous les lignes de la commande fournisseur, au bas de la page, sélectionnez **Détails de ligne**.

1. Sélectionnez l’onglet **Livraison**.

1. A unique delivery date can be assigned to each order line. The date is inherited from the field on the purchase order header, but you can change this.

1. Fermez la page Ligne de commande fournisseur.

1. Sur la page Toutes les commandes fournisseur, utilisez la fonctionnalité de filtre et recherchez votre nouvelle commande fournisseur.

1. Une fois terminé, fermez la page Toutes les commandes fournisseur et revenez à la page d’accueil.
