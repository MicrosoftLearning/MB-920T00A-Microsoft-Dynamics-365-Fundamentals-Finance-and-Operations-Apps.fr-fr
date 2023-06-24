---
lab:
  title: "Labo\_1\_: Créer un assortiment de produits"
  module: 'Module 4: Learn the Fundamentals of Microsoft Dynamics 365 Commerce'
---

# Module 4 : Découvrir les principes de base de Microsoft Dynamics 365 Commerce

## Labo 1 : Créer un assortiment de produits

## Objectif

Vous devez créer un assortiment de produits associés qui sont affectés à un canal commercial spécifique qui sera mis à disposition à une date ultérieure. 

## Mise en place du labo

   - **Durée estimée** : 10 minutes

## Instructions

1.  Dans la page d’accueil **Finance and Operations**, en haut à droite, vérifiez que vous travaillez avec la société **USMF**. 

1.  Si nécessaire, sélectionnez la société, puis, dans le menu, **USMF**. 

1.  Dans le volet de navigation de gauche, dans le module **Commerce et vente au détail**, sélectionnez **Catalogues et assortiments** > **Assortiments**. 

1.  Dans la page **Assortiments**, sélectionnez **+ Nouveau**. 

1.  Dans le formulaire **Nouvel enregistrement**, si nécessaire, développez le raccourci **Général**. 

1.  Sélectionnez le champ **Date d’effet**, puis sélectionnez une date future.  

1.  Dans le champ **Nom de l’assortiment**, attribuez un nom au nouvel assortiment. Par exemple : `New Spring Season`

    > **Remarque :** La **date d’expiration** peut être utilisée pour désactiver automatiquement un assortiment publié. 

1.  Développez le raccourci **Canaux de commerce**. 

1.  Dans la barre d’outils **Canaux de commerce**, sélectionnez **+ Ajouter une ligne**. 

1.  Dans le volet **Choisir des nœuds d’organisation**, pour **Hiérarchie d’organisation**, sélectionnez **Retail Stores by Type (Fabrikam)** [Magasins de détail par type (Fabrikam)]. 

1.  Dans la liste NŒUDS D’ORGANISATION DISPONIBLES, sélectionnez En ligne, puis sélectionnez l’icône d’ajout ![Icône représentant une flèche pointant vers la droite](./media/d365-fo-add-org-node-icon.png) pour l’ajouter aux **NŒUDS D’ORGANISATION SÉLECTIONNÉS**.

    Cela ajoute le nœud parent et tous les nœuds enfants. 

1.  Ajoutez le nœud parent **Centre commercial**, puis cliquez sur **OK**. 

1.  Vérifiez que les deux nœuds ont été ajoutés au raccourci **Canaux de commerce**. 

1.  Développez le raccourci **Produits**. 

1.  Dans la barre d’outils **Produits**, sélectionnez **+ Ajouter une ligne**. 

1.  Sélectionnez le menu **Catégorie**, développez **Team Sports (Team Sports)** [Sports d’équipe (Sports d’équipe)], puis sélectionnez **OK**.

    Cela ajoute tous les articles enfants de la catégorie parent.

1.  Passez en revue la dernière colonne nommée **Type ligne**. Par défaut, tous les articles sont inclus.

1.  Sélectionnez **+ Ajouter une ligne**, sélectionnez le menu **Catégorie**, développez **Sports d’équipe (sports d’équipe)** , sélectionnez **Baseball**, puis cliquez sur **OK**. 

1.  Pour exclure un article d’une catégorie plus large déjà incluse, dans le cas présent Team Sports (Sports d’équipe), dans la colonne **Type de ligne**, remplacez la valeur par `Exclude` 

1.  À l’aide de la ligne de catégorie Baseball, sélectionnez le menu **Produits**. 

1.  Lorsque les produits d’une catégorie sont définis, vous pouvez sélectionner un produit spécifique à inclure ou à exclure. Sélectionnez **AdultBaseballInfield** ou entrez `0013` 

    > **Remarque :** Pour supprimer un produit ajouté, supprimez le contenu du champ **Produit**, puis appuyez sur la touche Tab de votre clavier ou sélectionnez une autre zone de la page. 

1.  Dans le volet Actions, sélectionnez **Enregistrer**, puis **Publier**. 

1.  Cliquez sur **Oui** dans la boîte de dialogue de confirmation. Le nouvel assortiment de produits sera disponible à la **date d’effet**. 

