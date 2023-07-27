---
lab:
  title: "Labo\_1\_: Créer un nouveau produit"
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Module 3 : Découvrir les principes fondamentaux de Microsoft Dynamics 365 Supply Chain Management

## Labo 1 : Créer un nouveau produit

## Objectif

Dans Contoso Entertainment System USA (USMF), vous envisagez d’acheter une nouvelle configuration d’armoire auprès d’un fournisseur.  Vous devez créer un élément pour représenter la nouvelle configuration.  Dans ce labo, vous apprenez à créer un élément et des configurations d’éléments.

## Mise en place du labo

   - **Durée estimée** : 10 minutes

## Instructions

Dans Contoso Entertainment System USA (USMF), vous envisagez d’acheter une nouvelle configuration d’armoire auprès d’un fournisseur.  Vous devez créer un élément pour représenter la nouvelle configuration. 

1.  Dans la page d’accueil Finance and Operations, en haut à droite, vérifiez que vous travaillez avec la société **USMF**. Si nécessaire, dans la liste déroulante des sociétés, sélectionnez **USMF**.

2.  En haut à gauche, sélectionnez le menu Hamburger **Développer le volet de navigation**.

3.  Dans le volet de navigation, sélectionnez **Modules**, puis **Gestion des informations sur les produits**. Ensuite, dans le menu **Produits**, sélectionnez **Produits**.

4.  Dans la page **Produits**, dans le menu du haut, sélectionnez **+ Nouveau**.

5.  Dans la page **Nouveau produit**, dans le champ **Type de produit**, vérifiez qu’**Article** est sélectionné.

6.  Dans le champ **Sous-type de produit**, vérifiez que **Produit** est sélectionné.

7.  Sous **IDENTIFICATION**, dans la zone **Numéro de produit**, entrez **GTL007**.

8.  Dans la zone **Nom du produit**, saisissez **Armoire 2**.

    ![Capture d’écran montrant la vue standard de la page de création du nouveau produit.](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-07.png)

9.  Cliquez sur le bouton **OK**.

10. Sous le menu **Produit** du volet Actions, sélectionnez **Groupes de dimensions** sous le groupe **Configurer**.

    ![Capture d’écran montrant l’option Configurer sous le menu Produit où les détails des différents groupes de dimensions peuvent être ajoutés.](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-08.png)

11. Sélectionnez la liste déroulante **Groupe de dimension de stockage**, puis **SiteWH**.

12. Sélectionnez la liste déroulante **Groupe de dimension de stockage**, puis **Aucun**.

13. Cliquez sur le bouton **OK**.

14. Sélectionnez le bouton **Lancer des produits** dans le volet Actions pour lancer le produit dans une entité juridique.

15. Une page s’ouvre, affichant la première étape sous la forme **Sélectionner les produits à lancer**.

    ![Capture d’écran montrant la vue standard de la page Lancer des produits.](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-09.png)

16. Sélectionnez le bouton **Suivant** en bas de la page.

17. Dans la page **Sélectionner les sociétés vers lesquelles lancer**, sélectionnez l’entité juridique **USMF** où le produit doit être lancé.

18. Sélectionnez le bouton **Suivant** en bas de la page.

19. Dans la page **Confirmer la sélection**, définissez la valeur **Afficher la fenêtre Infos en cas d’échec** sur **Oui** et **sur Exécuter en tant que lot** sur **Non**.

20. Sélectionnez le bouton **Terminé** en bas de la page.

21. Dans le volet de navigation, sélectionnez Modules, puis Gestion des informations sur les produits. Ensuite, dans le menu Produits, sélectionnez **Produits lancés**.

22. Dans la page **Produits** **lancés**, recherchez le nouvel élément **GTL007** dans la grille. 

23. Sélectionnez le lien du produit, puis accédez à la page **Détails du produit**.

24. Dans le raccourci **Général**, entrez les informations suivantes :

    - **Groupe de modèles d’article** : FIFO

25. Dans le raccourci **Achat**, entrez les informations suivantes :

    - **Unité** : ea

    - **Groupe de taxe d’article** : Tout

    - **Prix** : 30

26. Dans le raccourci **Vendre**, entrez les informations suivantes :

    - **Unité** : ea

    - **Groupe de taxe d’article** : Tout

    - **Prix** : 35

27. Dans le raccourci **Gérer le stock**, entrez les informations suivantes :

    - **Unité** : ea

28. Dans le raccourci **Ingénieur**, entrez les informations suivantes :

    - **Unité de nomenclature** : ea

29. Dans le raccourci **Gérer les coûts**, entrez les informations suivantes :

    - **Groupe d’articles** : audio

30. Pour terminer la configuration, sélectionnez Produit dans le volet Actions. Sélectionnez le bouton Valider sous le groupe Tenir à jour.

    ![Capture d’écran montrant le groupe Tenir à jour sous le bouton Produit dans le volet Actions. Le bouton Valider du groupe Tenir à jour est sélectionné.](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-10.png)

31. Vérifiez que vous voyez la bannière d’informations confirmant que toutes les valeurs de champ nécessaires ont été validées.

    ![Capture d’écran montrant la bannière d’informations qui confirme que toutes les valeurs de champ nécessaires ont été validées. ](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-11.png)

32. Fermez toutes les pages et revenez à la page d’accueil.
