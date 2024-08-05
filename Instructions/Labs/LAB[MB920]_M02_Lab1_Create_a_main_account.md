---
lab:
  title: "Labo\_2.1\_: Créer un compte principal"
  module: 'Learning Path 2: Learn the fundamentals of Microsoft Dynamics 365 Finance'
---

# Parcours d’apprentissage 2 : Découvrir les principes de base de Microsoft Dynamics 365 Finance
# Module 2 : Décrire la comptabilité

## Labo 2.1 : Créer un compte principal

## Mise en place du labo

   - **Durée estimée** : 5 minutes

## Objectif

Dans ce labo, vous allez effectuer les activités suivantes :

1. Créer une entité juridique.

2. Créer un calendrier fiscal.

3. Créer un plan comptable.

4. Créer les comptes principaux dans le plan comptable.

5. Créer une unité opérationnelle de type service et centre de coûts.

6. Créer une structure comptable à l’aide des principaux comptes et centres de coûts.

7. Configurer le registre.

# Étapes de l’exercice

## Créer une entité juridique

1. Dans le volet de navigation gauche de Dynamics 365 Finance, sélectionnez **Modules****&gt;****Administration d’organisation****&gt; Organisations &gt; Entités juridiques**.

2. Dans la page **Entités juridiques**, sélectionnez le bouton **Nouvelle** dans le volet Actions pour créer une entité juridique, puis entrez les informations suivantes :

    - Nom : **Systèmes de démonstration Contoso**

    - Société : **CDS**

    - Pays ou région : **États-Unis**

3. Sélectionnez **OK** en bas.

## Créer un calendrier fiscal

1. Dans le volet de navigation gauche de Dynamics 365 Finance, sélectionnez **Modules****&gt;****Comptabilité****&gt; Calendriers &gt; Calendriers fiscaux**. 

2. Dans la page **Calendrier fiscal**, sélectionnez le bouton **Nouveau calendrier** dans le volet Actions pour créer un calendrier fiscal, puis entrez les informations suivantes :

    - Calendrier : **CDS**

    - Description : **Calendrier des systèmes de démonstration**

    - Début de l’exercice fiscal : **10/1/2023**

    - Fin de l’exercice fiscal : **9/30/2023**

    - Nom de l’exercice fiscal : **2023-24**

    - Longueur de la période : **1**

    - Unité : **Mois**

3. Cliquez sur le bouton **Créer**.

Le système génère 14 périodes, dont une période d’ouverture et une période de fermeture et 12 périodes pour 12 mois.

## Créer un plan comptable

1. Dans le volet de navigation gauche de Dynamics 365 Finance, sélectionnez **Modules** > **Comptabilité****&gt;****Plan comptable****&gt; Comptes &gt; Plan comptable**.

2. Dans la page **Plan comptable**, sélectionnez le bouton **Nouveau** dans le volet Actions pour créer un nouveau plan comptable, puis entrez les informations suivantes :

    - **Plans comptables** : systèmes de démonstration

    - **Description** : Systèmes de démonstration Contoso

3. Sélectionnez le bouton **Nouveau** sur le raccourci **Comptes principaux** pour créer des comptes principaux avec les valeurs suivantes :

    - Compte principal : **1000**

    - Nom : **Disponibilités**

    - Type de dépense principale : **Bilan**

    - Catégorie de compte principal : **CASH**

    - DB/CR par défaut : **Débit**

4. Créez un autre compte principal :

    - Compte principal : **3000**

    - Nom : **Revenu**

    - Type de dépense principal : **Revenu**

    - Catégorie de compte principal : **REV**

    - DB/CR par défaut : **Crédit**

5. Créez un autre compte principal :

    - Compte principal : **6000**

    - Nom : **Frais de déplacements**

    - Type de dépense principal : **Dépenses**

    - Catégorie de compte principal : **EXP**

    - DB/CR par défaut : **Débit**

##  Créer une unité opérationnelle

1. Accédez à **Modules****&gt;****Administration d’organisation****&gt; Organisations &gt; Unités opérationnelles**.

2. Dans le volet Actions, sélectionnez le bouton **Nouveau** suivi du type d’unité **d’exploitation du service** et entrez la valeur suivante :

    - Nom : **CDS_Training**

3. Dans le volet Actions, sélectionnez le bouton Nouveau suivi du type d’unité d’exploitation du centre de coûts et entrez la valeur suivante :

    - Nom : **CDS_Purchase**

4. Ajoutez deux centres de coûts supplémentaires : **CDS_IT** et **CDS_Admin**.

## Créer une structure comptable

1. Dans la page d’accueil **Finance and Operations**, en haut à droite, vérifiez que vous travaillez avec la société **CDS**.

2. Si nécessaire, sélectionnez la société, puis, dans le menu, sélectionnez **CDS**.

3. Dans le volet de navigation gauche de Dynamics 365 Finance, sélectionnez **Modules** > **Comptabilité****&gt;****Plan comptable &gt; Structures &gt;Configurer les structures de compte**.

4. Dans le volet Actions, sélectionnez le bouton **Nouveau** pour créer une structure de compte avec les valeurs suivantes :

    - Structure de compte : **CDS_BS**

    - Description : **Bilan CDS**

    - Ajouter un compte principal : **OUI**

5. Cliquez sur le bouton **Créer**.

6. Dans le raccourci **Segments et valeurs autorisées**, sélectionnez le bouton **Ajouter** pour ajouter **la plage de comptes principaux 1000..2999**.

7. Sélectionnez le bouton **Activer** dans le volet d’action, suivi du bouton **Activer** dans la boîte de dialogue Traitement par lots.

8. Dans le volet Actions de la page **Structures de compte**, sélectionnez le bouton **Nouvelle** pour créer une autre structure de compte avec les valeurs suivantes :

    - Structure de compte : **CDS_Revenue**

    - Description : **Revenu CDS**

    - Ajouter un compte principal : **OUI**

9. Cliquez sur le bouton **Créer**.

10. Dans le raccourci **Segments et valeurs autorisées**, sélectionnez le bouton **Ajouter** pour ajouter **la plage de comptes principaux 3000..5999**.

11. Sélectionnez le bouton **Activer** dans le volet d’action, suivi du bouton **Activer** dans la boîte de dialogue Traitement par lots.

12. Dans le volet Actions de la page **Structures de compte**, sélectionnez le bouton **Nouvelle** pour créer une autre structure de compte avec les valeurs suivantes :

    - Structure de compte : **CDS_Expense**

    - Description : **Dépenses CDS**

    - Ajouter un compte principal : **OUI**

13. Cliquez sur le bouton **Créer**.

14. Dans le raccourci **Segments et valeurs autorisées**, sélectionnez le bouton **Ajouter** pour ajouter **la plage de comptes principaux 6000..9999**.

15. Sélectionnez le bouton **Segment** dans le raccourci **Segments et valeurs autorisées**.

16. Dans la boîte de dialogue **Ajouter un segment**, sélectionnez **CostCenter** suivi du bouton **Ajouter un segment** .

17. Dans le champ **CostCenter**, sélectionnez **253..255**. 

18. Sélectionnez le bouton **Activer** dans le volet d’action, suivi du bouton **Activer** dans la boîte de dialogue Traitement par lots.

## Configurer le registre

1. Dans la page d’accueil **Finance and Operations**, en haut à droite, vérifiez que vous travaillez avec la société **CDS**.

2. Si nécessaire, sélectionnez la société, puis, dans le menu, sélectionnez **CDS**.

3. Dans le volet de navigation gauche de Dynamics 365 Finance, sélectionnez **Modules** > **Comptabilité &gt; Configuration &gt; Page comptabilité** et configurez les éléments suivants :

    - Plan comptable : **Systèmes de démonstration**

    - Calendrier fiscal : **CDS**

    - Devise comptable : **USD**

    - Devise de déclaration : **USD**

    - Type de taux de change de devise comptable : **Par défaut**

    - Type de taux de change budgétaire : **Budget**

4. Dans le raccourci **Structure de compte**, sélectionnez le bouton **Ajouter** pour ajouter la structure de compte **CDS_BS**.

5. Ajoutez deux structures de comptes supplémentaires : **CDS_Revenue** et **CDS_Expense**.

Cette opération conclut la configuration de base du module Comptabilité. Vous pouvez maintenant planifier la configuration de vos journaux pour publier des journaux. 

 
