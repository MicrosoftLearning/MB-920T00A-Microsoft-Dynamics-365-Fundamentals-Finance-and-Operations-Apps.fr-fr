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

1.  Dans la page d’accueil Finance and Operations, en haut à gauche, sélectionnez le menu Hamburger **Développer le volet de navigation**.

2.  Dans le volet de navigation, sélectionnez **Commerce et vente au détail** > **Catalogues et assortiments** > **Assortiments**.

3.  Attendez la fin du chargement de la page.

4.  Dans la page **Assortiments**, sélectionnez **+ Nouveau**.

5.  Dans le volet **Nouvel enregistrement**, développez **Général**.

6.  Sélectionnez la zone **Date effective**, puis sélectionnez une date dans le futur.

7.  Dans le champ **Nom de l’assortiment**, saisissez un nom. Par exemple, **Nouvelle saison de printemps**.

8.  Définissez **Date d’expiration** sur **Jamais**.

    La date d’expiration peut être utilisée pour désactiver automatiquement un assortiment publié.

9.  Développez **Canaux Commerce**.

10. Dans le menu **Canaux de commerce**, sélectionnez **+ Ajouter une ligne**.

11. Dans **Choisir des nœuds d’organisation**, sélectionnez le menu **Hiérarchie de l’organisation**, puis sélectionnez **Magasins de détail par type (Fabrikam)**.

12. Dans la liste **NŒUDS D’ORGANISATION DISPONIBLES**, sélectionnez **En ligne**, puis sélectionnez l’icône **Ajouter** ![Image 15](./media/04-learn-the-fundamentals-of-dynamics-365-commerce-17.png) pour l’ajouter aux **NŒUDS D’ORGANISATION SÉLECTIONNÉS**.

    Cela s’ajoute au nœud parent et à tous les nœuds enfants.

13. Ajoutez le nœud parent **Centre commercial**, puis cliquez sur **OK**.

14. Vérifiez que les deux nœuds ont été ajoutés aux canaux Commerce.

15. Développez **Produits**.

16. Dans le menu **Produits**, sélectionnez **+ Ajouter une ligne**.

17. Sélectionnez le menu **Catégorie**, sélectionnez **Sports d’équipe (Team Sports)**, puis **OK**.

    Cela ajoute tous les articles enfants de la catégorie parent.

18. Passez en revue la dernière colonne nommée **Type ligne**. Par défaut, tous les articles sont inclus.

19. Sélectionnez **+ Ajouter une ligne**, sélectionnez le menu **Catégorie**, développez **Sports d’équipe (sports d’équipe)** , sélectionnez **Baseball**, puis cliquez sur **OK**.

20. Pour exclure un article d’une catégorie plus large déjà incluse, dans le cas présent **Sports d’équipe**, dans la colonne **Type de ligne**, remplacez la valeur par **Exclure**.

21. À l’aide de la ligne de catégorie **Baseball**, sélectionnez le menu **Produits**.

22. Lorsque les produits d’une catégorie sont définis, vous pouvez sélectionner un produit spécifique à inclure ou à exclure. Sélectionnez **AdultBaseballInfield**.

23. Pour supprimer un produit ajouté, supprimez le contenu de la zone Produit, puis appuyez sur la touche **Tab** de votre clavier ou sélectionnez une autre zone de la page.

24. Dans le menu en haut, sélectionnez **Enregistrer**.

25. Dans le menu en haut, sélectionnez **Publier**.

26. Vérifiez les informations dans la boîte de dialogue, puis cliquez sur **Oui**.

    Le nouvel assortiment de produits créé devient disponible à la date d’effet.

