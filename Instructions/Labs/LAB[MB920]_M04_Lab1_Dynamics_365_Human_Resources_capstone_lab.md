---
lab:
    title: 'Labo 1 : Labo Capstone de Dynamics 365 Human Resources'
    module: 'Module 4 : Découvrir les principes de base de Microsoft Dynamics 365 Human Resources'
---

## Labo 1 : Labo Capstone de Dynamics 365 Human Resources

## Objectif

Au cours de ce labo, vous découvrirez le processus d’intégration des nouveaux employés, y compris la création d’un enregistrement employé. Vous découvrirez également le processus d’évaluation des performances, notamment la détermination d’objectifs et le classement de résultats. Vous utiliserez également les fonctionnalités en libre service pour envoyer un état de dépenses.

## Mise en place du labo

- **Durée estimée** : 20 minutes 

## Exercice 1 : Découvrir les ressources humaines

### Créer un enregistrement de nouvel employé

1. À l’aide du volet de navigation, sélectionnez **Modules** > **Ressources humaines** > **Postes** > **Postes**.

1. Dans le volet Actions, sélectionnez **+ Nouveau** pour créer un poste.

1. Dans la boîte de dialogue **Créer un poste**, dans le menu **Mission**, sélectionnez **Directeur de magasin**.

1. Sélectionnez **Créer un poste**.

1. À l’aide du volet de navigation, sélectionnez **Modules** > **Collaborateurs** > **Employés**.

1. Dans le volet Actions, sélectionnez **+ Nouveau** pour créer un employé.

1. Dans le volet **Engager un nouveau collaborateur**, saisissez les informations suivantes, puis sélectionnez **Engager et ajouter des détails**.

    | **Paramètre** | **Valeur** |
    | :--- | :---- |
    | Prénom | Bill |
    | Nom | Smith |
    | Date de début de l’emploi | Sélectionnez la date du jour|

### Créez un objectif pour le nouvel employé

1. Dans le volet Actions, sélectionnez **Collaborateur**.

1. Dans l’onglet **DÉVELOPPEMENT**, sélectionnez **Objectifs**.

1. Vous devrez peut-être faire défiler vers la droite pour voir l’onglet.

1. Dans le volet Actions, sélectionnez **+ Nouveau** pour créer un objectif.

1. Dans le raccourci **Général**, saisissez les informations suivantes :

    | **Paramètre** | **Valeur** |
    | :--- | :---- |
    | Nom | Objectif de ventes trimestriel |
    | Présentation | Aider l’équipe du magasin à atteindre l’objectif de ventes trimestriel |
    | Catégorie d’objectif | Ventes |
    | Date de début | Sélectionnez une date à une semaine à compter de la date du jour. |
    | Date de fin | Sélectionnez une date deux semaines à compter de la date de début. |

1. Dans le volet Actions, sélectionnez **Enregistrer**.

1. Fermez la page Objectif de ventes trimestriel.

1. Fermez les objectifs. | Page de Bill

### Assigner une formation au nouvel employé

1. Sur la page Employés pour Bill, dans le volet Actions, sélectionnez **Collaborateur**.

1. Dans l’onglet **COMPÉTENCES**, sélectionnez **Cours**.

1. Vous devrez peut-être faire défiler vers la droite pour voir l’onglet.

1. Dans le volet Actions, sélectionnez **+ Nouveau** pour créer un cours.

1. Dans la vue Grille, dans la colonne **ID cours**, sélectionnez le menu, puis sélectionnez **00004**.

1. Dans la boîte de dialogue **Transférer les données de cours**, sélectionnez **Oui**.

1. Dans la colonne **Date de début**, sélectionnez l’icône représentant un calendrier, puis sélectionnez la date du jour.

1. Dans la colonne **Date de fin**, sélectionnez l’icône représentant un calendrier, puis sélectionnez une date deux semaines à compter de la date du jour.

1. Dans le volet Actions, sélectionnez **Enregistrer**.

1. Fermer les cours | Page de Bill

### Créer une note de frais

1. À l’aide du volet de navigation, sélectionnez **Modules** > **Ressources humaines** > **Espaces de travail** > **Libre-service employé**.

1. Sous la section **Informations relatives à ma carrière**, sous la vignette **Dépenses**, sélectionnez **Nouvel état**.

1. Dans le volet **Nouvel état de dépenses**, sélectionnez le menu **Objectif**, puis **Formation**, et enfin **OK**.

1. Dans la grille **Dépenses**, sur la ligne de nouvelle dépense, saisissez les informations suivantes :

    | **Paramètre** | **Valeur** |
    | :--- | :---- |
    | Date de la transaction | Sélectionnez la date du jour |
    | Catégorie de dépenses | Location de voiture |
    | Marchand | LitWare Travel |
    | Montant de la transaction | 150,00 |

1. À l’aide de la machine virtuelle du labo, ouvrez le **Bloc-notes**.

1. Dans le bloc-notes, saisissez **Reçu LitWare Travel**.

1. Enregistrez le fichier sur le Bureau sous le nom **Reçu.txt**, puis fermez le Bloc-notes.

1. Ce fichier représente un reçu à joindre à un état de dépenses.

1. Revenez à l’onglet de navigateur de Microsoft Dynamics 365 Finance & Operations.

1. Dans le volet Actions, sélectionnez **Réceptions d’en-tête**.

1. Dans le volet **Réceptions d’en-tête**, sélectionnez **Télécharger et joindre un nouveau reçu**.

1. Sélectionnez **Parcourir**.

1. Sélectionnez le fichier **Reçu.txt** que vous avez créé précédemment, puis sélectionnez **Ouvrir**.

1. Dans le champ **Remarques**, saisissez **Location de voiture**, puis sélectionnez **Charger**.

1. Cochez la case **Reçu**, puis sélectionnez **Sélectionner des lignes**.

1. Dans le volet **Joindre des reçus à la ligne**, cochez la case **150,00 LitWare Travel**, puis sélectionnez **OK**.

1. Sélectionnez **Fermer**.

1. Dans le volet Actions, sélectionnez **Workflow**, puis **Envoyer**.

1. Dans le volet **État de dépenses - USMF - Envoyer**, dans le champ **Commentaires**, saisissez **Veuillez vérifier mon état de dépenses**.

1. Sélectionnez **Envoyer**.

### Journal d’enregistrement des performances

1. À l’aide du volet de navigation, sélectionnez **Modules** > **Ressources humaines** > **Performances** > **Journal des performances**.

1. Dans le volet Actions, sélectionnez **+ Nouveau**.

1. Sur la page **Nouveau journal**, saisissez les informations suivantes.


    | **Paramètre** | **Valeur** |
    | :--- | :---- |
    | Titre | Formation suivie |
    | Description | Formation métier suivie pour le poste de directeur de magasin |
    | Personne | Bill Smith |
    | Date de fin | Date du jour |

1. Dans le volet Actions, sélectionnez **Enregistrer**.

1. Dans le volet Actions, sélectionnez **Ajouter à l’objectif**.

1. Sélectionnez **Objectif de ventes trimestriel**, puis **OK**.

1. Fermez la page Journal des performances.
