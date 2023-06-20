---
lab:
  title: "Labo\_2\_: Intégration à Excel"
  module: 'Module 1: Explore the core capabilities of Dynamics 365 finance and operations apps'
---

# Module 1 : Explorer les fonctionnalités principales des applications de finances et d’opérations Dynamics 365

## Labo 2 : Intégration à Excel

## Objectif

Dans ce labo, vous allez apprendre à copier des données de Finance and Operations dans Excel à l’aide de l’application complémentaire Office Connecteur de données Dynamics. Vous découvrirez aussi comment utiliser cette même application pour insérer des données dans Dynamics 365 Finance and Operations. 

## Mise en place du labo

   - **Durée estimée** : 5 minutes

## Instructions

Maintenant que vous vous êtes familiarisé avec les applications  de finances et d'opérations, prenez le temps d’explorer le scénario d’intégration d’Excel. 

1.  Dans la page d’accueil **Finance and Operations**, en haut à droite, vérifiez que vous travaillez avec la société **USMF**. 

2.  Accédez à **Approvisionnements** > **Configuration** > **Fournisseurs** > **Groupes de fournisseurs**.

3.  Dans le volet Actions, sélectionnez **Ouvrir dans Microsoft Office** puis, sous **Ouvrir dans Excel**, sélectionnez **Groupes de fournisseurs (usmf)** .

4.  Dans le volet **Ouvrir dans Excel**, sélectionnez **Télécharger**. 

5.  Le fichier modèle Excel est alors téléchargé et enregistré. **Ouvrez** le fichier modèle Excel téléchargé, ignorez ou autorisez les autres invites de sécurité standard si nécessaire, fermez l’activation, puis sélectionnez **Activer la modification**. Sélectionnez **Approuver ce complément**, puis connectez-vous (avec les mêmes informations d’identification, si vous y êtes invité). 

    Une fois la connexion établie, l’application Connecteur de données actualise les données existantes du tableau **Groupe de fournisseurs**, et celles-ci s’affichent dans la feuille de calcul Excel. 

6.  Pour créer un enregistrement, entrez `100` dans le champ **Groupe de fournisseurs**, `Insurance vendor` dans le champ **Description**, puis `Net10` dans le champ **Conditions de paiement**. 

7.  Sélectionnez le bouton **Publier** dans le volet Office Connecteur de données Microsoft Dynamics. 

8.  Actualisez la liste **Groupes de fournisseurs** dans Dynamics 365 Finance and Operations pour vérifier que le nouvel enregistrement a bien été ajouté. 

