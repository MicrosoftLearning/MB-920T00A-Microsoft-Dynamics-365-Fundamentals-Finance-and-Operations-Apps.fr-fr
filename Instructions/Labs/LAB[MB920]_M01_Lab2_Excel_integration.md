---
lab:
  title: 'Labo 2 : Intégration à Excel'
  module: 'Module 1: Explore the core capabilities of Dynamics 365 finance and operations apps'
ms.openlocfilehash: e5929571477cfcdbb1b2e81c72ebc566a96c56a4
ms.sourcegitcommit: 8e5a278c6e08abdcc3fb719796f79842e868606b
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/14/2022
ms.locfileid: "147116297"
---
# <a name="module-1-explore-the-core-capabilities-of-dynamics-365-finance-and-operations-apps"></a>Module 1 : Explorer les fonctionnalités principales des applications de finances et d’opérations Dynamics 365

## <a name="lab-2---excel-integration"></a>Labo 2 : Intégration d’Excel

Maintenant que vous vous êtes familiarisé avec les applications Finance and Operations, prenez le temps d’explorer le scénario d’intégration d’Excel.

### <a name="task-1-create-template"></a>Tâche n°1 : Créer un modèle

1. Ouvrez la page d’accueil Finance and Operations. 

2. Accédez à **Modules** > **Common** > **Common** > **Intégration Office** > **Classeur Excel** **Concepteur**. Notez que la majeure partie de la navigation s’effectue par le biais des modules, ce qui n’est habituellement pas spécifié.

3. Recherchez **Groupe de fournisseurs** dans le filtre.

4. Dans la liste des champs disponibles, sélectionnez les champs **Groupe de fournisseurs**, **Description** et **Conditions de paiement**, puis déplacez-les vers la zone de champ sélectionnée avec la flèche vers la droite.

5. Dans le volet Action, sélectionnez le bouton **Créer un classeur**.

6. À droite, dans le panneau **Enregistrer dans**, sélectionnez le bouton **Télécharger**.

7. Téléchargez le fichier en sélectionnant **Enregistrer sous** et stockez-le dans le dossier **Téléchargements**.

8. Accédez à **Common** > **Intégration Office** > **Modèles de** **document**.

9. Sélectionnez **Nouveau**.

10. Dans le volet droit, dans la section **Charger un modèle**, sélectionnez le bouton **Parcourir** et sélectionnez le fichier précédemment téléchargé (si vous avez utilisé le nom par défaut, il s’agit de DynamicsWorkbook).

11. Dans le champ **Nom du modèle**, entrez **CustomVendorGroup**.

12. Sélectionnez **OK**, puis cliquez sur **Enregistrer**.

### <a name="task-2-open-in-excel"></a>Tâche n° 2 : Ouvrir dans Excel

1. Accédez à **Approvisionnements** > **Configuration** > **Fournisseurs** > **Groupes de fournisseurs**.

2. Sélectionnez **Ouvrir dans Microsoft Office** > **Open dans Excel** pour rechercher le nouveau modèle, CustomVendorGroup, que vous avez chargé.

3. Sélectionnez **CustomVendorGroup** et téléchargez le modèle Excel.

4. Enregistrez, puis ouvrez le modèle Excel téléchargé, autorisez-le si nécessaire, fermez l’activation, puis sélectionnez **Activer la modification**. Approuvez ce complément, puis connectez-vous (avec vos mêmes informations d’identification, si vous y êtes invité).

Toutes les données existantes dans le tableau des groupes de fournisseurs s’affichent dans la feuille de calcul Excel.

5. Entrez un nouvel enregistrement.

6. Entrez **100** dans le champ **Groupe de fournisseurs**, **Fournisseur d’assurance** dans le champ **Description** et **Net10** dans le champ **Conditions de paiement**.

7. Sélectionnez le bouton **Publier** dans l’application Complément Microsoft Dynamics Office.

8. Ouvrez le formulaire **Groupe de fournisseurs** pour vérifier que le nouvel enregistrement est ajouté.

