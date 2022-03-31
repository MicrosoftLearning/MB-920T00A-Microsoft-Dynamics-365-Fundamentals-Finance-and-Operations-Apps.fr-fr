---
demo:
  title: 'Démonstration 3 : Découvrir les coûts de projet'
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
ms.openlocfilehash: ca5f0816e2d018c01ab7e24b43219ff32c0e693e
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/27/2022
ms.locfileid: "137909414"
---
## <a name="demo-3---explore-project-costs"></a>Démonstration 3 : Découvrir les coûts de projet

Dans cette démonstration, nous allons voir comment créer une entrée de temps et de dépense qui sera facturée au projet Contoso Consulting. Nous allons également découvrir les entrées dans des formats optimisés pour les appareils mobiles et le Web, ainsi que l’utilisation d’un workflow pour gérer le processus d’approbation.

1. Dans le volet de navigation de **Dynamics 365 for Finance and Operations**, sélectionnez **Modules > Gestion et comptabilité des projets > Feuilles de temps > Mes feuilles de temps (optimisées pour mobile)** .  
    Avant toute chose, observons que les écrans affichés en sélectionnant l’option **Mes feuilles de temps (optimisées pour mobile)** sont compatibles avec les appareils mobiles, même si nous n’en utilisons pas en ce moment même.

    ![Capture d’écran du menu Gestion et comptabilité des projets où l’option Mes feuilles de temps (optimisées pour mobile) est mise en surbrillance.](./media/projops_costs_1_select_my_timesheets.png)  

    Cette optimisation représente un élément clé pour les applications Microsoft professionnelles et garantit une phase d’apprentissage réduite entre les versions web et mobile.

1. Vérifiez que vous vous connectez bien à l’entité juridique **USSI** dans le sélecteur de société situé dans le coin supérieur droit. Si tel n’est pas le cas, sélectionnez l’entité juridique **USSI**.

1. Sur la page **Mes feuilles de temps**, sélectionnez **Nouveau**.  
    Nous allons maintenant créer une nouvelle feuille de temps que nous baserons sur des paramètres configurés.

1. Dans le volet **Nouvelle feuille de temps**, pointez sur la zone **Date**.  
    La date saisie déterminera la période de la feuille de temps.

1. Pointez sur **Créer à partir des favoris**.  
    Si vous avez des favoris enregistrés, vous pouvez les utiliser pour créer vos prochaines feuilles de temps et ainsi gagner du temps.

1. Quand vous avez terminé, sélectionnez **OK**.

1. Sur la page **Mes détails de feuilles de temps**, sélectionnez l’icône **Nouveau +** .

1. Dans le volet **Nouvelle ligne de feuille de temps**, pointez sur la zone **Entité juridique**.  
    Cela permet d’ouvrir une nouvelle ligne de feuille de temps, qui contient des détails comme le client, le projet, la catégorie, les propriétés de ligne et les paramètres de taxe. Vous pouvez également sélectionner une autre entité juridique si l’entrée de temps est saisie pour le compte d’une autre société au sein de votre organisation.

1. Sélectionnez le menu **ID projet**.

1. Sélectionnez l’un des projets disponibles, tel que le projet **Contoso Consulting**.

1. Quand vous avez terminé, sélectionnez **OK**.  
    L’écran optimisé pour les appareils mobiles et consacré à l’entrée de temps s’affiche. Vous pouvez commencer à réserver vos heures pour le projet et la catégorie, à savoir **Service** dans notre cas, et ce pour chaque jour.

1. Sur la page **Saisie de l’heure**, saisissez **8** dans la zone **Lun**.  
    Cette valeur représente les heures d’un seul jour.

    ![Capture d’écran de la page Saisie de l’heure](./media/projops_costs_2_mon_box.png)

1. Dans la zone **Commentaire interne**, saisissez un commentaire. Par exemple : **Sujet de discussion potentiel : nouveaux vélos**.  
    Vous pouvez également saisir des commentaires internes ou externes pour le projet, afin que toutes les parties puissent comprendre les heures saisies.

1. Dans la zone **Commentaire externe**, saisissez un commentaire. Par exemple : **Ajustement des chaînes et alignement des roues avant de la flotte**.

1. Dans la barre de navigation, sélectionnez **Enregistrer**.

1. Dans le menu de navigation à gauche, sous **Feuilles de temps**, sélectionnez **Mes feuilles de temps**.

1. Sur la page **Mes feuilles de temps**, sélectionnez l’entrée d’heure créée précédemment.

1. Dans l’onglet **Feuille de temps**, pointez sur la colonne Catégorie.  
    À présent, supposons que nous revenons sur un ordinateur et que nous passons en revue nos heures au sein de l’écran de feuille de temps web. Nous retrouvons les mêmes informations, telles que la catégorie et les heures.

1. Sous **Détails de ligne**, pointez sur **Commentaire interne** et **Commentaire externe**.  
    Nous pouvons également passer en revue les commentaires saisis précédemment. Les informations sont disponibles, seul le format d’affichage est légèrement différent. Ce format est courant lors des vérifications finales, car il permet de vérifier et valider facilement les heures, surtout quand la personne est affectée à plusieurs projets ou catégories.

1. Dans la barre de navigation, sélectionnez l’onglet **Workflow**.  
    Si la feuille de temps nous convient, nous pouvons l’envoyer. Les approbations requises sont déterminées lors de la phase d’implémentation, par catégorie et en fonction des stratégies des sociétés concernées.

1. Dans le volet **Revoir un workflow de feuille de temps**, sélectionnez **Envoyer**.

1. Dans le volet **Revoir un workflow de feuille de temps – Envoyer**, ajoutez tout commentaire supplémentaire.

1. Sélectionnez **Envoyer**.

1. Accédez à la page **Transactions horaires**. Si l’onglet **Transactions horaires** est grisé, rendez-vous sur la page **Mes feuilles de temps** et sélectionnez la feuille de temps créée précédemment.

1. Passez en revue la page **Transactions horaires**.  
    En cas d’approbation, les résultats seront validés et consultables sur la page Transactions horaires. Nous y trouvons toutes les informations pertinentes, telles que l’entité juridique, le projet, les heures et même, dans notre cas, un aperçu du prix de vente et du prix de revient.  

À présent, nous allons accéder aux pièces comptables.

1. Dans la barre de navigation, sélectionnez **Pièce justificative**.

1. Sur la page **Pièces comptables**, pointez sur les sections **Compte général** et **Nom du compte**.  
    Dans ces sections, nous pouvons constater l’impact sur la comptabilité et les comptes utilisés.  

À présent, créons une entrée de dépenses, toujours pour le projet Contoso Consulting.

1. Dans le volet de navigation, sélectionnez **Modules > Gestion des dépenses > Mes dépenses > États de dépenses**.

1. Sur la page **Gestion des dépenses**, dans l’onglet **États**, sélectionnez **+ Nouvel état de dépenses**.

1. Dans le volet **Nouvel état de dépenses**, saisissez un titre dans la zone **Objectif**. Par exemple, **Contoso - Fév2021**.

1. Sélectionnez **OK**.

1. Sur la page **États**, sélectionnez **+ Nouvelle dépense**.  
Une nouvelle ligne de dépense s’affiche.

1. Dans la colonne **Catégorie de dépenses**, sélectionnez **Carburant** dans le menu déroulant **Catégorie**.  
Ici, nous pouvons saisir la nouvelle dépense, ainsi que des détails à son sujet.

1. Dans la colonne **Montant de la transaction**, saisissez **25,00**.

1. Dans la colonne **Devise**, sélectionnez **USD**.

1. Dans la colonne **Date de transaction**, sélectionnez une date. Par exemple, **2/1/2021**.  
    Une fois les détails saisis, vous pouvez enregistrer la dépense.

1. Sélectionnez **Enregistrer**.

1. Dans le menu de navigation à gauche, sous **Espaces de travail**, sélectionnez **Gestion des dépenses**.

1. Sur la page **Gestion des dépenses**, sélectionnez l’état de dépenses que vous venez de créer.

1. Sur la page **État de dépenses**, sélectionnez la zone **ID projet** et sélectionnez **00000093 Contoso Consulting**.  

Ensuite, nous pouvons indiquer que le carburant sera facturé au projet Contoso Consulting, ainsi que des informations supplémentaires concernant la dépense.

1. Pointez sur la zone **Informations supplémentaires**.

1. Dans le coin inférieur droit de l’écran, sélectionnez **Enregistrer et continuer**.

1. Sur le côté droit de l’écran, sélectionnez **Envoyer**.

1. Dans la zone **Commentaire**, ajoutez des commentaire supplémentaires.

1. Sélectionnez **Envoyer**.

1. Sur la page **Gestion des dépenses**, pointez sur la colonne **Statut d’approbation**.  
    Le flux d’approbation relatif aux stratégies de déplacement et aux dépenses s’active à ce moment-là. Les coûts ont été validés et appliqués au projet Contoso Consulting. S’ils sont facturables, ils pourront être utilisés ultérieurement pour la facturation.

Dans cette démonstration, nous avons traité une entrée de temps et de dépense facturée au projet Contoso Consulting. Nous avons consulté des extraits dans les formats web et mobile et découvert l’utilisation des workflows pour gérer les approbations requises par l’organisation USSI.
