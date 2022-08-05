---
lab:
  title: 'Labo 1 : Créer un nouveau produit'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
ms.openlocfilehash: e8fad0a9ddf0787c57ee7b98ddc6ef8363832ffc
ms.sourcegitcommit: 178a1e5d74c3902b0514276a3daf4a24c0c4ade7
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 08/01/2022
ms.locfileid: "147444366"
---
# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>Module 3 : Découvrir les principes fondamentaux de Microsoft Dynamics 365 Supply Chain Management

## <a name="lab-1---create-a-new-product"></a>Labo 1 : Créer un produit

## <a name="objectives"></a>Objectifs

Dans Contoso Entertainment System USA (USMF), vous devez créer un article pour une nouvelle configuration d’armoire à acheter auprès des fournisseurs.

## <a name="lab-setup"></a>Mise en place du labo

   - **Durée estimée** : 10 minutes

## <a name="instructions"></a>Instructions

1. Sur la page d’accueil de Finance and Operations, en haut à droite, vérifiez que vous travaillez avec la société USMF.

1. Si nécessaire, sélectionnez la société, puis, dans le menu, **USMF**.

1. En haut à gauche, sélectionnez le menu hamburger **Développer le volet de navigation**.

1. Dans le volet de navigation, sélectionnez **Modules** > **Gestion des informations sur les produits**, puis sous la catégorie **Produits**, **Produits lancés**.

1. Sur la page Détails des produits lancés, dans le menu du haut, sélectionnez **+ Nouveau**.

1. Dans le volet Nouveau produit lancé, dans le menu **Type de produit**, vérifiez qu’**Article** est sélectionné.

1. Dans le menu **Sous-type de produit**, vérifiez que **Produit** est sélectionné.

1. Dans le menu **Groupe de dimension de suivi**, puis sélectionnez **Aucun**.

1. Sous **IDENTIFICATION**, dans les zones **Numéro de produit** et **Numéro d’article**, saisissez **GTL007**.

1. Dans la zone **Nom du produit**, saisissez **Armoire 2**.

1. Sous **GROUPES DE RÉFÉRENCE**, sélectionnez le menu **Groupe de modèles d’article**, puis sélectionnez **FIFO premier entré, premier sorti**.

1. Dans le menu **Groupe d’articles**, sélectionnez **TV et vidéo**.

1. Dans le menu **Groupe de dimension de stockage**, puis sélectionnez **SiteWH**.

1. Sous **UNITÉS DE MESURES**, vérifiez que les valeurs suivantes sont définies :

    | **Paramètre**| **Valeur**|
    | :--- | :--- |
    | Unité de stock| ea Chaque|
    | Unité d’achat| ea Chaque|
    | Unité de vente| ea Chaque|
    | Unité de nomenclature| ea Chaque|

1. Sous **IMPOSITION SUR LES VENTES**, sélectionnez le menu **Groupe de taxe d’article**, puis sélectionnez **TOUT**.

1. Sous **IMPOSITION SUR LES ACHATS**, sélectionnez le menu **Groupe de taxe d’article**, puis sélectionnez **TOUT**.

1. Sous PRIX, dans le champ Prix d’achat, saisissez 30,00.

1. Dans le champ Prix de vente, entrez 30,00.

1. Votre nouvelle version du produit doit ressembler à ceci :

    ![Image d’écran affichant le formulaire de nouvelle version du produit complété](./media/lp1-m2-new-release-product.png)

1. Sélectionnez **OK**.

1. Pour vous assurer que le produit est finalisé, dans la barre de ruban, sous **Mettre à jour**, sélectionnez **Valider**.

    ![Image d’écran présentant la barre de ruban avec Valider en surbrillance](./media/lp1-m2-validate-ribbon-bar.png)

1. Vérifiez que vous voyez la bannière d’information confirmant que toutes les valeurs de champ requises ont été validées.

    ![Image d’écran de notification d’informations indiquant que tous les champs obligatoires ont été validés](./media/lp1-m2-confirmation-of-validation.png)

1. Fermez toutes les pages et revenez à la page d’accueil.
