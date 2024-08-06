---
lab:
  title: "Labo\_3.1\_: Créer un nouveau produit"
  module: 'Learning Path 3: Learn the fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Parcours d’apprentissage 3 : Découvrir les principes de base de Microsoft Dynamics 365 Supply Chain Management
# Module 2 : décrire le processus de vente et d’approvisionnement

## Labo 3.1 : Créer un nouveau produit

Votre organisation prévoit de créer un nouvel article, en l’occurrence une chemise. Ces chemises pourront être de couleurs et de tailles différentes. Dans ce labo, vous allez apprendre à créer un article avec plusieurs variantes et à le publier dans l’entité juridique USMF.

## Étapes de l’exercice

1. Dans le volet de navigation Dynamics 365 Supply Chain Management, sélectionnez **Modules**, puis sélectionnez **Gestion des informations sur les produits** > **Configuration** > **Groupes de dimensions et de variantes**. Ouvrez la page **Groupes de couleurs** et créez un enregistrement.

    - Groupe de couleurs : **ShirtColor**

    - Description : **Couleur de chemise**

2. Dans le raccourci **Lignes de groupes de couleurs**, entrez les trois enregistrements suivants :

| **Couleur**| **Nom de couleur** |
| - |
| Bleu| Bleu |
| White| Blanc |
| Noir| Noir |

3. Cliquez sur Enregistrer pour sauvegarder les enregistrements.

4. Sélectionnez **Gestion des informations sur les produits** > **Configuration** > **Groupes de dimensions et de variantes**. Ouvrez la page **Groupes de tailles** et créez un enregistrement.

    - Groupe de taille : **ShirtSize**

    - Description : **Taille de chemise**

5. Dans le raccourci **Lignes de groupes de tailles**, entrez les trois enregistrements suivants

| **Taille**| **Nom de taille** |
| - |
| S| Petite |
| M| Moyenne |
| L| grand |

6. Sauvegardez les enregistrements

7. Dans le volet de navigation Dynamics 365 Supply Chain Management, sélectionnez **Modules**, puis **Gestion des informations sur les produits**. Ensuite, dans le menu **Produits**, sélectionnez **Produits génériques**.

8. Dans la page **Produits génériques**, dans le menu du haut, sélectionnez **+ Nouveau**.

9. Dans la page **Nouveau produit**, dans le champ **Type de produit**, vérifiez qu’**Article** est sélectionné.

10. Dans le champ **Sous-type de produit**, vérifiez que **Produit****générique** est sélectionné.

11. Sous l’onglet **Identification**, dans la zone **Numéro de produit**, saisissez **SH001**.

12. Dans le champ **Nom du produit**, saisissez **Chemise**.

13. Dans le champ **Groupe de dimensions de produit**, sélectionnez **ColorSize**.

14. Cliquez sur le bouton **OK**.

15. Sous le menu **Produit** du volet Actions, sélectionnez **Groupes de dimensions** sous le groupe **Configurer**.

16. Dans la liste déroulante **Groupe de dimension de stockage**, sélectionnez **SiteWH**.

17. Dans la liste déroulante **Groupe de dimension de suivi**, sélectionnez **Aucun**.

18. Cliquez sur le bouton **OK**.

19. Sélectionnez **ShirtColor** dans la liste des **groupes de couleurs**.

20. Sélectionnez **ShirtSize** dans la liste des **groupes de tailles**.

21. Dans le volet Actions, sélectionnez **Variantes de produit**.

22. Dans la page **Variantes de produits**, dans le volet Actions, sélectionnez **Suggestions de variantes**.

23. Sélectionnez le bouton **Suggérer tout** dans la page **Suggestions de variantes**.

24. Sélectionnez les variantes suggérées en sélectionnant le bouton **Sélectionner tout** suivi du bouton **Créer** .

Les variantes seront créées sur la page Variantes de produits.

25. Sélectionnez le bouton **Lancer les produits** dans le volet Actions pour lancer le produit dans une entité juridique.

26. Une page s’ouvre, affichant la première étape sous la forme **Sélectionner les produits à lancer**.

27. Sélectionnez le bouton **Suivant** en bas de la page.

28. Sélectionnez les variantes que vous souhaitez lancer dans l’entité juridique, puis sélectionnez le bouton **Suivant**.

29. Dans la page **Sélectionner les sociétés vers lesquelles lancer**, sélectionnez l’entité juridique **USMF** où le produit doit être lancé.

30. Sélectionnez le bouton **Suivant** en bas de la page.

31. Dans la page **Confirmer la sélection**, définissez la valeur **Afficher la fenêtre Infos en cas d’échec** sur **Oui** et **Exécuter en tant que lot** sur **Non**.

32. Sélectionnez le bouton **Terminé** en bas de la page.

16. Dans le volet de navigation, sélectionnez **Modules**, puis **Gestion des informations produit**. Ensuite, dans le menu **Produits**, sélectionnez **Produits lancés**.

33. Dans la page **Lancer les produits**, recherchez le nouvel article **SH001** dans la grille.

34. Sélectionnez le lien du produit, puis accédez à la page **Détails du produit**.

35. Dans le raccourci **Général**, entrez les informations suivantes :

    - Groupe de modèles d’article : **FIFO**

36. Dans le raccourci **Achat**, entrez les informations suivantes :

    - Unité : **ea**

    - Groupe de taxe d’article : **TOUT**

    - Prix : **30**

37. Dans le raccourci **Vendre**, entrez les informations suivantes :

    - Unité : **ea**

    - Groupe de taxe d’article : **TOUT**

    - Prix : **35**

38. Dans le raccourci **Gérer le stock**, entrez les informations suivantes :

    - Unité : **ea**

39. Dans le raccourci **Ingénieur**, entrez les informations suivantes :

    - Unité BOM : **ea**

40. Dans le raccourci **Gérer les coûts**, entrez les informations suivantes :

    - Groupe d’articles : **audio**

41. Pour terminer la configuration, sélectionnez **Produit** dans le volet Actions. Sélectionnez le bouton **Valider** sous le groupe **Tenir à jour**.

42. Fermez toutes les pages et retournez à la page d’**accueil**.

 
