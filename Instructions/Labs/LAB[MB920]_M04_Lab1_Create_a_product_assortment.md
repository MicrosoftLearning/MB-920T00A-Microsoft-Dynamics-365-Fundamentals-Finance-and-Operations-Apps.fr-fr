---
lab:
  title: "Labo\_1\_: Créer un assortiment de produits"
  module: 'Module 4: Learn the Fundamentals of Microsoft Dynamics 365 Commerce'
---

## <a name="lab-1---create-a-product-assortment"></a>Labo 1 : Créer un assortiment de produits

## <a name="objectives"></a>Objectifs

Vous devez créer un assortiment de produits associés qui sont affectés à un canal commercial spécifique qui sera mis à disposition à une date ultérieure.

## <a name="lab-setup"></a>Mise en place du labo

   - **Durée estimée** : 10 minutes

## <a name="instructions"></a>Instructions

1. Sur la page Finance and Operations, en haut à gauche, sélectionnez le menu hamburger **Développer le volet de navigation**.

1. Dans le volet de navigation, sélectionnez **Commerce et vente au détail** > **Catalogues et assortiments** > **Assortiments**.

1. Sur la page Assortiments, sélectionnez **+ Nouveau**.

1. Dans le volet Nouvel enregistrement, développez **Général** si nécessaire.

1. Sélectionnez la zone **Date effective**, puis sélectionnez une date dans le futur.

1. Dans le champ **Nom de l’assortiment**, saisissez un nom. Par exemple, **Nouvelle saison de printemps**.

1. La date d’expiration peut être utilisée pour désactiver automatiquement un assortiment publié.

1. Développez **Canaux Commerce**.

1. Dans le menu des canaux de commerce, sélectionnez **+ Ajouter une ligne**.

1. Dans Choisir des nœuds d’organisation, sélectionnez le menu **Hiérarchie de l’organisation**, puis sélectionnez **Magasins de détail par type (Fabrikam)** .

1. Dans la liste NŒUDS D’ORGANISATION DISPONIBLES, sélectionnez En ligne, puis sélectionnez l’icône d’ajout ![Icône représentant une flèche pointant vers la droite](./media/d365-fo-add-org-node-icon.png) pour l’ajouter aux **NŒUDS D’ORGANISATION SÉLECTIONNÉS**.  
  Cela ajoute le nœud parent et tous les nœuds enfants.

1. Ajoutez le nœud parent **Centre commercial**, puis cliquez sur **OK**.

1. Vérifiez que les deux nœuds ont été ajoutés aux canaux Commerce.

1. Développez **Produits**.

1. Dans le menu Produits, sélectionnez **+ Ajouter une ligne**.

1. Sélectionnez le menu **Catégorie**, sélectionnez **Sports d’équipe (sports d’équipe)** , puis sélectionnez **OK**.

1. Cela ajoute tous les articles enfants de la catégorie parent.

1. Passez en revue la dernière colonne nommée **Type ligne**. Par défaut, tous les articles sont inclus.

1. Sélectionnez **+ Ajouter une ligne**, sélectionnez le menu **Catégorie**, développez **Sports d’équipe (sports d’équipe)** , sélectionnez **Baseball**, puis cliquez sur **OK**.

1. Pour exclure un article d’une catégorie plus large déjà incluse, dans ce cas Sports d’équipe, dans la colonne Type ligne, remplacez la valeur par **Exclure**.

1. À l’aide de la ligne de catégorie Baseball, sélectionnez le menu **Produits**.

1. Lorsque les produits d’une catégorie sont définis, vous pouvez sélectionner un produit spécifique à inclure ou à exclure. Sélectionnez **AdultBaseballInfield**.

1. Pour supprimer un produit ajouté, supprimez le contenu de la boîte du produit, puis appuyez sur la touche de tabulation de votre clavier ou sélectionnez une autre zone de la page.

1. Dans le menu en haut, sélectionnez **Enregistrer**.

1. Dans le menu en haut, sélectionnez **Publier**.

1. Vérifiez les informations dans la boîte de dialogue, puis cliquez sur **Oui**.

1. Le nouvel assortiment de produits sera disponible à la date d’effet.
