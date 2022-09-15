---
demo:
  title: "Démonstration\_3\_: Découvrir les coûts de projet"
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
---

## <a name="demo-3---explore-project-costs"></a>Démonstration 3 : Découvrir les coûts de projet

In this demo, we will walk through the creation of a time and expense entry that will be charged to the Contoso Consulting project. We'll explore the entries in formats optimized for web and mobile presentation, and we'll see how a workflow is used to manage the approval process.

1. Dans le volet de navigation de **Dynamics 365 for Finance and Operations**, sélectionnez **Modules > Gestion et comptabilité des projets > Feuilles de temps > Mes feuilles de temps (optimisées pour mobile)** .  
    Avant toute chose, observons que les écrans affichés en sélectionnant l’option **Mes feuilles de temps (optimisées pour mobile)** sont compatibles avec les appareils mobiles, même si nous n’en utilisons pas en ce moment même.

    ![Capture d’écran du menu Gestion et comptabilité des projets où l’option Mes feuilles de temps (optimisées pour mobile) est mise en surbrillance.](./media/projops_costs_1_select_my_timesheets.png)  

    Cette optimisation représente un élément clé pour les applications Microsoft professionnelles et garantit une phase d’apprentissage réduite entre les versions web et mobile.

1. In the top right company picker, verify the legal entity you are connecting to is <bpt id="p1">**</bpt>USSI<ept id="p1">**</ept>. If it's not, change the legal entity to <bpt id="p1">**</bpt>USSI<ept id="p1">**</ept>.

1. Sur la page **Mes feuilles de temps**, sélectionnez **Nouveau**.  
    Nous allons maintenant créer une nouvelle feuille de temps que nous baserons sur des paramètres configurés.

1. Dans le volet **Nouvelle feuille de temps**, pointez sur la zone **Date**.  
    La date saisie déterminera la période de la feuille de temps.

1. Pointez sur **Créer à partir des favoris**.  
    Si vous avez des favoris enregistrés, vous pouvez les utiliser pour créer vos prochaines feuilles de temps et ainsi gagner du temps.

1. Quand vous avez terminé, sélectionnez **OK**.

1. Sur la page **Mes détails de feuilles de temps**, sélectionnez l’icône **Nouveau +** .

1. Dans le volet **Nouvelle ligne de feuille de temps**, pointez sur la zone **Entité juridique**.  
    The new timesheet line will be opened, with details such as the customer, the project, the category, the line properties, and tax parameters. You can also select a different legal entity if the time entry is on behalf of another company within your organization.

1. Sélectionnez le menu **ID projet**.

1. Sélectionnez l’un des projets disponibles, tel que le projet **Contoso Consulting**.

1. Quand vous avez terminé, sélectionnez **OK**.  
    L’écran optimisé pour les appareils mobiles et consacré à l’entrée de temps s’affiche. Vous pouvez commencer à réserver vos heures pour le projet et la catégorie, à savoir **Service** dans notre cas, et ce pour chaque jour.

1. Sur la page **Saisie de l’heure**, saisissez **8** dans la zone **Lun**.  
    Cette valeur représente les heures d’un seul jour.

    ![Capture d’écran de la page Saisie de l’heure](./media/projops_costs_2_mon_box.png)

1. Dans cette démonstration, nous allons voir comment créer une entrée de temps et de dépense qui sera facturée au projet Contoso Consulting.  
    Vous pouvez également saisir des commentaires internes ou externes pour le projet, afin que toutes les parties puissent comprendre les heures saisies.

1. Nous allons également découvrir les entrées dans des formats optimisés pour les appareils mobiles et le Web, ainsi que l’utilisation d’un workflow pour gérer le processus d’approbation.

1. Dans la barre de navigation, sélectionnez **Enregistrer**.

1. Dans le menu de navigation à gauche, sous **Feuilles de temps**, sélectionnez **Mes feuilles de temps**.

1. Sur la page **Mes feuilles de temps**, sélectionnez l’entrée d’heure créée précédemment.

1. Dans l’onglet **Feuille de temps**, pointez sur la colonne Catégorie.  
    Now assume we've returned to a computer and are reviewing our time from within the web timesheet form. We can still see the same information, such as the category and the hours.

1. Sous **Détails de ligne**, pointez sur **Commentaire interne** et **Commentaire externe**.  
    We can also review the comments we entered earlier. The information is there, but the layout format is just a bit different. This format is often used for final review because it can be easier for people to review and validate their time, especially when someone is assigned to multiple projects or categories.

1. Dans la barre de navigation, sélectionnez l’onglet **Workflow**.  
    If we're satisfied with the timesheet, we can submit it. The approvals required will be determined by each organization during the implementation phase based on their own company policies.

1. Dans le volet **Revoir un workflow de feuille de temps**, sélectionnez **Envoyer**.

1. Dans le volet **Revoir un workflow de feuille de temps – Envoyer**, ajoutez tout commentaire supplémentaire.

1. Sélectionnez **Envoyer**.

1. Browse to the <bpt id="p1">**</bpt>Hour transactions<ept id="p1">**</ept> page. If the <bpt id="p1">**</bpt>Hour transactions<ept id="p1">**</ept> tab is grayed out, browse to the <bpt id="p2">**</bpt>My timesheets page<ept id="p2">**</ept>, and select the previously created timesheet.

1. Passez en revue la page **Transactions horaires**.  
    Upon approval, the results will be posted and will be visible in the Hour transactions page. We can see all the relevant information, such as the legal entity, project, category, hours, and in this case, even a view of the cost price and the sales price.  

À présent, nous allons accéder aux pièces comptables.

1. Dans la barre de navigation, sélectionnez **Pièce justificative**.

1. Sur la page **Pièces comptables**, pointez sur les sections **Compte général** et **Nom du compte**.  
    Dans ces sections, nous pouvons constater l’impact sur la comptabilité et les comptes utilisés.  

À présent, créons une entrée de dépenses, toujours pour le projet Contoso Consulting.

1. Dans le volet de navigation, sélectionnez **Modules > Gestion des dépenses > Mes dépenses > États de dépenses**.

1. Sur la page **Gestion des dépenses**, dans l’onglet **États**, sélectionnez **+ Nouvel état de dépenses**.

1. Vérifiez que vous vous connectez bien à l’entité juridique **USSI** dans le sélecteur de société situé dans le coin supérieur droit.

1. Sélectionnez **OK**.

1. Sur la page **États**, sélectionnez **+ Nouvelle dépense**.  
Une nouvelle ligne de dépense s’affiche.

1. Dans la colonne **Catégorie de dépenses**, sélectionnez **Carburant** dans le menu déroulant **Catégorie**.  
Ici, nous pouvons saisir la nouvelle dépense, ainsi que des détails à son sujet.

1. Dans la colonne **Montant de la transaction**, saisissez **25,00**.

1. Dans la colonne **Devise**, sélectionnez **USD**.

1. Si tel n’est pas le cas, sélectionnez l’entité juridique **USSI**.  
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
    At this time, travel policies and expense approval flow will be activated. The costs have been posted and applied to the Contoso Consulting project and will be available later for invoicing if chargeable.

In this demo, we have processed a time and expense entry that was charged to the Contoso Consulting project. We saw samples in web and mobile formats and were able to see how workflows are used to manage the approvals required by the USSI organization.
