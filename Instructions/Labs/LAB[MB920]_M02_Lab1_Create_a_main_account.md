---
lab:
  title: "Labo\_1\_: Créer un compte principal"
  module: 'Module 2: Learn the Fundamentals of Microsoft Dynamics 365 Finance'
---

# Module 2 : Découvrir les principes fondamentaux de Microsoft Dynamics 365 Finance

## Labo 1 : Créer un compte principal

## Mise en place du labo

   - **Durée estimée** : 5 minutes

## Instructions


1.  Dans la page d’accueil **Finance and Operations**, en haut à droite, vérifiez que vous travaillez avec la société **USMF**.

2.  Si nécessaire, sélectionnez la société, puis, dans le menu, sélectionnez **USMF**.
3.  Dans le volet de navigation gauche, accédez à **Modules > Comptabilité > Calendriers > Calendriers fiscaux**.
4.  Sélectionnez Calendrier **fiscal**
5.  Si l’année civile en cours est déjà créée, quittez la page**Calendriers fiscaux**.
6. Dans le cas contraire, sélectionnez le bouton **Nouvelle année** dans le volet Actions et entrez l’année en cours comme indiqué dans la capture d’écran suivante. Sélectionnez le **bouton Créer** pour créer le calendrier de l’année en cours.

![La capture d’écran montre comment créer la nouvelle année dans le calendrier fiscal](./media/lab-create-a-main-account-04.png)


4.  Dans le volet de navigation gauche, sélectionnez **Modules** > **Comptabilité** > **Plan comptable** > **Comptes** > **Comptes principaux**.

5.  Dans le volet Actions, sélectionnez **+ Nouveau**.

6.  Entrez les valeurs suivantes dans la page **Compte principal** :

    - Compte principal : **601510**

    - Nom : **Frais d’appels internationaux**

    - Type de compte principal : **Dépenses**

    - Catégorie de compte principal : **TANDEEXP**

    - DB/CR par défaut : **Débit**

    ![Capture d’écran montrant la page Comptes principaux - Plan comptable : partagé, où différentes valeurs doivent être ajoutées.](./media/lab-create-a-main-account-01.png)

7.  Accédez à **Modules &gt; Comptabilité  &gt; Écritures feuille &gt; Feuilles comptabilité**.

8.  Dans le volet Actions, sélectionnez **+ Nouveau**.

9.  Entrez la valeur suivante dans la page **Feuilles comptabilité**, puis sélectionnez **Lignes** dans le volet Actions :

    - Nom : GenJrn

10.  Entrez les valeurs suivantes dans la page **N° document de journal** :

    - Type de compte : **Général**

    - Compte principal : **601510**

    - Débit : **10.00** 

    - Type de compte de contrepartie : **Général**

    - Numéro de compte de contrepartie : **110180** 

11. Sélectionnez le bouton **Enregistrer** dans le volet Actions.

12. Sélectionnez **Valider &gt; Simuler la validation**. 

13. Sélectionnez le bouton **Valider** dans le volet Actions. Le journal doit alors être publié.
