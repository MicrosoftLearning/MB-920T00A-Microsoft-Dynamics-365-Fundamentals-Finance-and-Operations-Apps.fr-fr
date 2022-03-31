---
lab:
  title: 'Labo 1 : Créer un produit avec une remise'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Commerce'
ms.openlocfilehash: 2d3a61398c6184a9b43e2fd0da9d28cb55f55ee5
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/27/2022
ms.locfileid: "137909576"
---
## <a name="lab-1---create-a-discount-product"></a>Labo 1 : Créer une réduction sur un produit

## <a name="objectives"></a>Objectifs

Le magasin de Boston de votre entreprise est prêt à stimuler les ventes de certains produits qui doivent être vendus afin de faire de la place pour la nouvelle gamme. Vous devez créer et activer une nouvelle remise de produit.

## <a name="lab-setup"></a>Mise en place du labo

   - **Durée estimée** : 10 minutes

## <a name="instructions"></a>Instructions

1. Sur la page Finance and Operations, en haut à gauche, sélectionnez le menu hamburger **Développer le volet de navigation**.

1. Dans le volet de navigation, sélectionnez **Espaces de travail** > **Gestion de la tarification et des remises**.

1. Sur la page Gestion de la tarification et des remises, consultez les **Remises actives** affichées.

1. Dans le menu, sélectionnez **Nouveau**, passez en revue les options disponibles, puis sélectionnez **Remise**.

1. Sur la page Remises, dans la zone **Nom**, saisissez un nom pour la remise. Par exemple, Nouvel An 20 %.

1. Dans l’onglet Général, vérifiez que le statut est défini sur **Désactivé**.

1. La remise ne peut être modifiée que lorsqu’elle est définie sur désactivée.

1. Sélectionnez le menu **Mode de simultanéité de la remise**, passez en revue les options disponibles, puis sélectionnez **Meilleur prix**.

    >[!NOTE] Lorsque vous choisissez entre les options de mode de simultanéité, gardez à l’esprit les éléments suivants :
    >
    >  - Lorsque plusieurs remises composées sont applicables, la remise la plus élevée sera toujours calculée en premier.  La remise la plus élevée suivante est ensuite calculée sur le montant restant.  Cette hiérarchie de calcul se poursuit jusqu’à ce que toutes les remises composées applicables aient été appliquées.  
    >    **Correct** : Réduction de 40 % + réduction de 20 % = réduction de 52 %  
    >      - (Réduction de 40 % sur 100 € = 40 €. Montant restant = 60 €.  Réduction de 20 % sur 60 € = 12 €. Montant restant = 48 €.)  
    >
    >    **Incorrect** : Réduction de 40 % + réduction de 20 % = réduction de 60 %
    >
    >  - Les remises exclusives s’appliquent toujours à un meilleur prix ou une remise composée, même s’il s’agit du pourcentage de remise le plus bas.
    >    - Lorsque plusieurs remises exclusives sont applicables, la plus élevée est utilisée.
    >  - Lorsque le meilleur prix et le prix composé sont tous deux applicables ou si des multiples du même prix sont applicables, la remise la plus élevée est utilisée.

1. Sélectionnez le menu **Compte de remise** et consultez la liste.

1. Dans la zone Compte de remise, saisissez **remise**.

1. La liste est filtrée automatiquement.

1. Dans les résultats, sélectionnez le numéro de compte de remise **403200**.

1. Passez en revue les autres options, puis développez **Détails**.

1. Dans la zone **Description**, saisissez une description de la remise. Par exemple, « Remise de 20 % pour le Nouvel An ».

1. Développez **Prix/remise**.

1. Dans la zone Pourcentage remise, tapez **20,00**.

1. Développez **Période de validation**.

1. Définissez la **Date d’effet** et la **Date d’expiration** de la remise.

1. Assurez-vous de définir la date d’expiration dans le futur, sinon la remise ne sera pas affichée dans la liste des remises actives.

1. Développez les **Lignes**.

1. Dans le menu, sélectionnez **+ Ajouter**.

1. Sélectionnez le menu **Catégorie**, puis **Mode (Mode)** .

1. La remise est alors appliquée à tous les produits de la catégorie Mode.

1. Développez **Détails de la ligne**, puis, dans la zone **Description**, saisissez une description pour les lignes de produits. Par exemple, tous les produits de la catégorie Mode sont inclus dans la remise.

1. En haut de la page, dans le menu, sélectionnez **Groupe de prix**.

1. Sur la page Groupes de prix, sélectionnez le menu **Groupe de prix**.

1. Consultez les groupes de prix disponibles, sélectionnez **Groupe de prix de Boston**, puis sélectionnez **Enregistrer**.

1. En haut à droite de la page Groupes de prix, sélectionnez l’icône **Fermer**.

1. Sur la page Remises, dans l’onglet Détails, sélectionnez le menu **Statut**, puis **Activé**.

1. Vous remarquerez que les paramètres de remise ne peuvent plus être modifiés.

1. Enregistrez vos modifications, puis fermez la page Remise.

1. Sur la page Gestion de la tarification et des remises, consultez l’onglet Remises actives et vérifiez que votre nouvelle remise est affichée en bas de la liste.

1. Si nécessaire, en haut à droite, sélectionnez l’icône **Actualiser** pour actualiser la liste des remises.
