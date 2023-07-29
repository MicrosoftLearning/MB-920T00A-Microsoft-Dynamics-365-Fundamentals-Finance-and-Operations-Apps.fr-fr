---
lab:
  title: "Labo\_2\_: Créer une commande fournisseur"
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Module 3 : Découvrir les principes fondamentaux de Microsoft Dynamics 365 Supply Chain Management

## Labo 2 : Créer une commande fournisseur

## Mise en place du labo

   - **Durée estimée** : 15 minutes

## Objectif

Dans ce labo, vous vous familiarisez avec l’interface utilisateur et les différents champs disponibles dans le formulaire de commande fournisseur. Vous apprenez également à créer une commande fournisseur.


## Mise en place du labo

   - **Durée estimée** : 10 minutes

## Instructions

1. Dans la page d’accueil Finance and Operations, en haut à droite, vérifiez que vous travaillez avec la société **USMF**. Si nécessaire, sélectionnez la société puis, dans le menu déroulant, sélectionnez **USMF**.

2. En haut à gauche, sélectionnez le menu Hamburger **Développer le volet de navigation**.

3. Sélectionnez **Modules** > **Approvisionnements** > **Commandes fournisseur** > **Toutes les commandes fournisseur**.

4. Dans la page **Toutes les commandes fournisseur**, dans le menu du haut, sélectionnez **+Nouveau**.

5. Dans le volet **Créer une commande fournisseur**, sélectionnez la liste déroulante **Compte fournisseur**, puis sélectionnez **US-101**.

> [!NOTE]
> Lorsque vous sélectionnez un fournisseur, les détails de l’enregistrement du fournisseur, tels que l’adresse, le compte de facturation, les conditions de livraison et le mode de livraison, sont copiés comme valeurs par défaut dans l’en-tête de commande. Vous pouvez modifier ces valeurs à tout moment.

6.  Développez la section **Général**, si nécessaire.

7. Sous **DIMENSIONS DE STOCKAGE**, sélectionnez la liste déroulante **Site**, puis passez en revue la liste des sites.

Le champ **Site**, avec le champ **Entrepôt**, spécifient l’endroit où les biens ou services achetés doivent être livrés. Le site est l’adresse de livraison par défaut. Les deux champs peuvent être renseignés avec des valeurs configurées pour le fournisseur sélectionné, ou vous pouvez les spécifier manuellement.

8.  Sous **DATES**, le champ **Date de livraison** permet de spécifier quand les biens et services achetés doivent être livrés.

    Vous pouvez indiquer une date de livraison unique pour la commande, ou les lignes de commande individuelles peuvent recevoir des dates de livraison uniques. Si la date de livraison indiquée ici ne peut pas être respectée pour des produits ou services spécifiques en raison de délais plus longs, ces lignes sont créées avec une date de livraison ultérieure.

9. Développez la section **Administration**. La zone **Auteur commande** peut être utilisée pour indiquer qui passe la commande.

    Cela peut être pratique à partager avec le fournisseur au cas où il aurait besoin de contacter cette personne. La valeur peut être attribuée automatiquement si le compte d’utilisateur actuel est associé à un nom dans la page **Utilisateurs**.

10. Sélectionnez **OK**.

L’en-tête commande est maintenant créé. Lorsque vous travaillez avec des lignes de commande fournisseur, seul un résumé des informations d’en-tête s’affiche. Si vous avez besoin d’afficher le reste des informations, sélectionnez **En-tête**.

![Capture d’écran montrant l’en-tête de commande où le résumé des informations de commande est affiché. Le mot En-tête est mis en évidence.](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-17.png)

11. Sous **Lignes de commande fournisseur**, dans le menu, sélectionnez **Ligne de commande fournisseur**.

![Capture d’écran montrant les lignes de commande fournisseur.](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-18.png)

12. Sous **AFFICHAGE**, sélectionnez **Dimensions**.

    Les produits peuvent être déclinés en plusieurs variantes qui se différencient par des dimensions, telles que la couleur, la taille ou le style. Les produits peuvent également être configurés pour utiliser des dimensions de stockage, telles que le site et l’entrepôt. Il existe également des dimensions de suivi facultatives, telles que les numéros de lot et de série. Pour améliorer l’efficacité de la saisie des commandes, vous pouvez ajouter les champs de dimension que vous utilisez généralement directement dans la grille de commande.

13.  Dans le volet **Affichage des dimensions**, sous **DIMENSIONS DE**activez ma case à cocher **Couleur**.

Facultatif : Si vous sélectionnez le bouton bascule **Enregistrer le paramétrage**, les dimensions que vous avez choisies s’afficheront également dans la grille des lignes de commande la prochaine fois que vous ouvrirez la page des commandes fournisseur.

14. Sélectionnez **OK**.

15. Sélectionnez la liste déroulante des cellules **Numéro d’article**, puis sélectionnez **T0004**.

N’oubliez pas que vous pouvez également taper dans la zone de filtre au lieu de faire défiler la liste.

Les lignes de commande sont créées pour les produits et services en spécifiant un numéro d’article ou en tant que dépenses en indiquant une catégorie d’approvisionnement.

La catégorie d’approvisionnement est utilisée pour ajouter des lignes à l’endroit où les articles achetés sont passés en charges directement, plutôt que d’entrer dans le stock. Si vous devez effectuer un achat, vous pouvez le faire en créant une ligne de commande fournisseur qui spécifie une catégorie d’approvisionnement, plutôt que de créer une ligne avec un numéro d’article. Les articles peuvent également être associés à une catégorie d’approvisionnement. Dans ce cas, celle-ci s’affiche à titre informatif uniquement.

16. Sélectionnez la liste déroulante **Couleur**, passez en revue les options disponibles, puis sélectionnez l’une des couleurs ou combinaisons de couleurs.

17. Les champs **Site** et **Entrepôt** sont généralement renseignés avec les valeurs de l’en-tête de commande, mais il est possible de remplacer les champs si certaines lignes doivent être livrées à des emplacements différents.

18. Dans la zone **Quantité**, saisissez **10**.

    Le champ **Quantité** est automatiquement renseigné avec la quantité minimale de commande du produit si celle-ci est configurée, ou avec la valeur **1**.

19. Quelques informations supplémentaires :

- **Unité** : Indique l’unité de mesure de la quantité commandée. Normalement, l’unité est automatiquement fournie à partir de l’unité d’achat sur les données principales du produit.

- **Prix unitaire** : Contient une valeur provenant d’un contrat d’achat ou d’un accord commercial. Il est possible de modifier le prix unitaire de lignes de commande individuelles, par exemple si un prix unique est négocié avec le fournisseur.

- **Remise** : Représente un montant de remise par unité. Cette remise réduit donc le prix unitaire. Elle est généralement fournie automatiquement à partir d’accords d’achat ou d’accords commerciaux, mais il est possible de la remplacer sur des lignes individuelles si des remises uniques ont été négociées avec le fournisseur.

- **Pourcentage de remise** : Une fois saisi, il réduit le montant net de la ligne en conséquence. Le pourcentage de remise est souvent fourni automatiquement à partir de contrats d’achat ou d’accords commerciaux, mais il est possible de le remplacer sur des lignes individuelles si un pourcentage de remise a été négocié avec le fournisseur.

- **Montant net** : Calculé à partir d’autres champs de la ligne, notamment la quantité, le prix unitaire, la remise et le pourcentage de remise. Il est possible de modifier le Montant net, mais les champs Prix unitaire, Remise et Pourcentage de remise sont vides. Lorsque vous passez ensuite à la ligne, le montant affiché est proportionnel au montant net. Le champ Montant net n’est utilisé que pour afficher le montant net de la ligne.

20. Sous les lignes de la commande fournisseur, au bas de la page, sélectionnez **Détails de ligne**.

21. Sélectionnez l’onglet **Livraison**.

    Une date de livraison unique peut être affectée à chaque ligne de commande. La date est héritée du champ de l’en-tête de commande fournisseur, mais vous pouvez la modifier.

22.  Fermez la page **Ligne de commande fournisseur**.

23.  Dans la page **Toutes les commandes fournisseur**, utilisez la fonctionnalité de filtre et recherchez votre nouvelle commande fournisseur.

24. Quand vous avez terminé, fermez la page **Toutes les commandes fournisseur** et retournez à la page d’accueil.

