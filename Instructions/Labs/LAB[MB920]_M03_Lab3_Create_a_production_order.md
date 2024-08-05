---
lab:
  title: "Labo\_3.2\_: Créer un ordre de fabrication"
  module: 'Learning Path 3: Learn the fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Parcours d’apprentissage 3 : Découvrir les principes de base de Microsoft Dynamics 365 Supply Chain Management
# Module 4 : Décrire le processus de fabrication

## Labo 3.2 : Créer un ordre de fabrication

## Objectif

Les ordres de fabrication permettent de lancer le processus de production dans Supply Chain Management. Dans ce labo, vous allez vous familiariser avec l’interface utilisateur et les fonctionnalités du formulaire Ordre de fabrication. Vous apprendrez également à créer et traiter un ordre de fabrication à la fin de l’exercice.

## Étapes de l’exercice

1. Dans la page d’accueil de **Supply Chain Management** de Dynamics 365, en haut à droite, vérifiez que vous travaillez avec l’entreprise **USMF**.

2. Si nécessaire, sélectionnez la société, puis, dans le menu, sélectionnez **USMF**.

3. Dans le volet de navigation de gauche, sélectionnez **Modules** > **Contrôle de la production** > **Ordres de fabrication** > **Tous les ordres de fabrication**.

4. Dans le menu supérieur, sélectionnez **Nouvel ordre de fabrication** et saisissez les données suivantes.

    - Numéro d’article : **D0002**

    - Quantité : **10**

    - Site : **1**

    - Entrepôt : **11**

    - Livraison : [sélectionnez une date postérieure d’un mois à la date du jour]

    - Numéro de nomenclature : **D0002BOM**

    - Numéro de gamme : **000004**

5. Cliquez sur le bouton **Créer**.

Un nouvel ordre de fabrication est créé pour 10 copies de l’article D0002.

6. Sélectionnez **Ordre de fabrication (menu du volet Actions) &gt; Processus &gt; Estimation.**

7. Dans la boîte de dialogue **Estimation**, sélectionnez **Standard** dans le champ **Paramétrage de profit**, sélectionnez le champ **Références**, puis sélectionnez le bouton **OK**.

L’**état** de l’ordre de fabrication va passer à **Estimé**.

8. Sélectionnez **Planification (menu du volet Actions) &gt; Ordre de fabrication &gt; Planifier des opérations.**

9. Dans la boîte de dialogue **Planification des opérations**, sélectionnez **Transférer à partir d’aujourd’hui** dans le champ **Direction de planification**, puis sélectionnez le bouton **OK** .

10. Sélectionnez **Afficher (menu du volet Actions) &gt; Informations associées &gt; Réservation de capacité**.

11. Vérifiez les nouveaux enregistrements créés dans la page **Réservation de capacité**.

12. Revenez à la page **Tous les ordres de fabrication**. Notez que l’**état** de l’ordre de fabrication passe à **Planifié**.

13. Sélectionnez **Ordre de fabrication (menu du volet Actions) &gt; Processus &gt; Lancement**.

14. Dans la boîte de dialogue **Lancement**, sélectionnez le champ **Références** et sélectionnez le bouton **OK**.

15. L’**état** de l’ordre de fabrication va passer à **Lancé**.

16. Sélectionnez **Ordre de fabrication (menu du volet Actions) &gt; Processus &gt;Démarrer**.

17. Dans la boîte de dialogue **Démarrer**, sélectionnez l’onglet **Général**.

18. Saisissez les informations suivantes sous l’onglet **Général**.

    - Date : **date du jour**

    - Quantité : **10**

    - Démarrer la production : **OUI**

    - Valider fiche production maintenant : **NON**

    - Valider immédiatement les prélèvements : **NON**

19. Cliquez sur le bouton **OK**.

L’**état** de l’ordre de fabrication passe à **Démarré**.

20. Sélectionnez **Afficher (menu du volet Actions) &gt; Journaux &gt; Liste des prélèvements**.

Un nouveau journal des prélèvements est créé avec trois lignes.

21. Publiez le journal des prélèvements.

22. Revenez à la page **Tous les ordres de fabrication** et sélectionnez **Afficher (menu du volet Actions) &gt; Journaux &gt; Fiche production**.

Un nouveau journal des fiches productions est créé avec trois lignes.

23. Sélectionnez les trois lignes du champ **Opération terminée** et publiez le journal des fiches productions.

24. Revenez à la page **Tous les ordres de fabrication** et sélectionnez **Ordres de fabrication (menu du volet Actions) &gt; Processus &gt; Signaler comme terminé**.

25. Dans la boîte de dialogue **Signaler comme terminé**, entrez **10** dans le champ **Quantité de marchandise**. Sélectionnez le champ **Terminer le travail** et sélectionnez **OK**.

L’**état** de l’ordre de fabrication passe à **Terminé**. Le stock de l’article **D0002** augmente de 10 sur le site 1 et l’entrepôt 11.

26. Sélectionnez **Gérer les coûts (menu du volet Actions) &gt; Calculs &gt; Afficher les détails du calcul**.

Notez le coût final de l’article fabriqué sous l’onglet **Vue d’ensemble de l’évaluation des coûts** .

 
