---
lab:
  title: 'Labo 6 : Créer un ordre de fabrication'
  module: 'Module 1: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
ms.openlocfilehash: 222c557f935bc0dcfaa4f2e96049774f141ea028
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/27/2022
ms.locfileid: "137909447"
---
## <a name="lab-6---create-a-production-order"></a>Labo 6 : Créer un ordre de fabrication

## <a name="objectives"></a>Objectifs

L’ordre de fabrication contient des informations sur ce qui doit être produit, la quantité et la date de fin prévue. Il contient également des informations sur les matériaux à utiliser et sur les processus à mettre en œuvre pour produire l’article.

Vous devez créer un ordre de fabrication pour votre entreprise.

## <a name="lab-setup"></a>Mise en place du labo

   - **Durée estimée** : 5 minutes

## <a name="instructions"></a>Instructions

1. Sur la page d’accueil de Finance and Operations, en haut à droite, vérifiez que vous travaillez avec la société USMF.

1. Si nécessaire, sélectionnez la société, puis, dans le menu, **USMF**.

1. Dans le volet de navigation de gauche, sélectionnez **Modules** > **Contrôle de la production** > **Ordres de fabrication** > **Tous les ordres de fabrication**.

1. Dans le menu supérieur, sélectionnez **Nouvel ordre de fabrication**.

1. Sous **IDENTIFICATION**, dans la zone **Numéro d’article**, saisissez **D0001**, puis sélectionnez l’article identifié.

1. Sous **PRODUCTION**, dans la zone **Livraison**, sélectionnez une date ultérieure d’un mois à la date du jour.  
    La date de livraison indique quand l’ordre de fabrication doit prendre fin pour une livraison dans les temps. Cette date peut être utilisée dans le processus de planification. Par exemple, vous pouvez planifier la commande à rebours à partir de la date de livraison.

1. Dans le champ **Quantité**, entrez **20**.

1. Sous **NOMENCLATURE/GAMME**, le champ Numéro de nomenclature affiche automatiquement le numéro de toute nomenclature active pour l’élément actuel, mais vous pouvez modifier la nomenclature de l’ordre de fabrication en sélectionnant une nomenclature active dans la liste des versions de nomenclature approuvées. Le champ Numéro de gamme affiche automatiquement le numéro de toute gamme active pour l’élément actuel, mais vous pouvez modifier la gamme de l’ordre de fabrication en sélectionnant une gamme active dans la liste des versions de gamme approuvées.

    ![Capture d’écran montrant le volet Créer un ordre de fabrication complet](./media/lp1-m4-new-production-order-pane.png)

1. Sélectionnez **Create** (Créer).
