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

Les commandes fournisseur sont généralement créées automatiquement dans le cadre de la planification générale, de la livraison directe et d’autres processus. Une commande fournisseur créée manuellement est généralement créée par un agent d’achats. Créez une commande fournisseur au nom de la société USMF. 

## Mise en place du labo

   - **Durée estimée** : 10 minutes

## Instructions

1.  Dans la page d’accueil **Finance and Operations**, en haut à droite, vérifiez que vous travaillez avec la société **USMF**. 

1.  Si nécessaire, sélectionnez la société, puis, dans le menu, sélectionnez **USMF**. 

1.  En haut à gauche, sélectionnez le menu hamburger **Développer le volet de navigation**. 

1.  Dans le module **Approvisionnements**, sélectionnez **Commandes fournisseur** > **Toutes les commandes fournisseur**. 

1.  Dans la page **Toutes les commandes fournisseur**, dans le volet Actions, sélectionnez **+ Nouveau**. 

1.  Dans le volet **Créer une commande fournisseur**, sélectionnez le champ **Compte fournisseur**, puis entrez ou sélectionnez `US-101`

1.  Lorsque vous sélectionnez un fournisseur, les détails de l’enregistrement du fournisseur, tels que l’adresse, le compte de facturation, les conditions de livraison et le mode de livraison, sont copiés comme valeurs par défaut dans l’en-tête de la commande fournisseur. Vous pouvez changer ces valeurs, si nécessaire. 

1.  Développez la section **Général**. 

1.  Sous **DIMENSIONS DE STOCKAGE**, sélectionnez le menu **Site** et passez en revue la liste des sites. 

    > **Remarque :** Le champ **Site**, avec le champ **Entrepôt**, spécifie le lieu où les marchandises ou les services achetés doivent être livrés. L’adresse de livraison par défaut est tirée du champ **Site**. Les deux champs peuvent être renseignés avec des valeurs configurées pour le fournisseur sélectionné, ou vous pouvez les spécifier manuellement. 

1.  Pour **Entrepôt**, entrez ou sélectionnez `13`

1.   Sous **DATES**, le champ **Date de livraison** permet de spécifier quand les biens et services achetés doivent être livrés.

    > **Remarque :** Vous pouvez indiquer une date de livraison unique pour la commande, ou les lignes de commande individuelles peuvent recevoir des dates de livraison uniques. Si la date de livraison indiquée ici ne peut pas être respectée pour des produits ou services spécifiques en raison de délais plus longs, ces lignes sont créées avec une date de livraison ultérieure pour tenir compte de cela.

1.  Développez la section **Administration**. Le champ **Auteur de la commande** peut être utilisé pour préciser le nom de la personne qui passe la commande. 

    > **Remarque :** Il peut être judicieux de partager cette information avec le fournisseur au cas où il aurait besoin de contacter cette personne. La valeur peut être attribuée automatiquement si le compte d’utilisateur actif est associé à un enregistrement de **Personne** dans la page **Utilisateurs**. 

1.  Sélectionnez **OK**. 

1.  L’en-tête commande est maintenant créé. Lorsque vous travaillez avec des lignes de commande fournisseur, seul un résumé des informations d’en-tête s’affiche. Si vous avez besoin d’afficher le reste des informations, sélectionnez l’onglet **En-tête**. 

    ![Image d’écran affichant l’emplacement du menu En-tête](./media/lp1-m3-purchase-order-header-option.png)

1.  Sous **Lignes de commande fournisseur**, dans la barre d’outils, sélectionnez le menu **Ligne de commande fournisseur**. 

    ![Image d’écran montrant l’emplacement de l’option de menu Ligne de commande fournisseur](./media/lp1-m3-purchase-order-purchase-order-line-menu.png)

1.  Sous **AFFICHAGE**, sélectionnez **Dimensions**. 

    > **Remarque :** Les produits peuvent être déclinés en plusieurs variantes qui se différencient par des dimensions, telles que la couleur, la taille ou le style. Les produits peuvent également être configurés pour utiliser des dimensions de stockage, telles que le site et l’entrepôt. Il existe également des dimensions de suivi facultatives, telles que les numéros de lot et de série. Pour améliorer l’efficacité de la saisie des commandes, vous pouvez ajouter les champs de dimension que vous utilisez généralement directement dans la grille de commande. 

1.  Dans le volet **Affichage des dimensions**, sous **DIMENSIONS DE PRODUIT**, sélectionnez **Couleur**. 

1.  *Facultatif :* Si vous sélectionnez le bouton bascule **Enregistrer le paramétrage**, les dimensions que vous avez choisies s’afficheront également dans la grille des lignes de commande la prochaine fois que vous ouvrirez la page des commandes fournisseur. 

1.  Sélectionnez **OK**. 

1.  Sous **Lignes de commande fournisseur**, sélectionnez le champ **Numéro d’article**, puis sélectionnez **T0004**. 

    > **Remarque :** N’oubliez pas que vous pouvez également entrer `T0004` dans **Filtre** au lieu de faire défiler la liste. 

    > **Remarque :** Les lignes de commande sont créées pour les produits et services en spécifiant un **numéro d’article** ou en tant que dépenses en spécifiant une **Catégorie d’approvisionnement**.
    > 
    > La **catégorie d’approvisionnement** sert à ajouter des lignes pour indiquer que les articles achetés sont passés directement en charges plutôt que d’être ajoutés au stock. Cela signifie que si vous devez imputer un achat, vous pouvez le faire en créant une ligne de commande fournisseur qui spécifie une **catégorie d’approvisionnement**, plutôt que de créer une ligne avec un **numéro d’article**. Les articles peuvent également être associés à une catégorie d’approvisionnement et dans ce cas, celle-ci s’affiche à titre informatif uniquement. 

1.  Sélectionnez le menu **Couleur**, passez en revue les options disponibles, puis sélectionnez l’une des couleurs ou combinaisons de couleurs. 

    > **Remarque :** Les champs **Site** et **Entrepôt** sont reçoivent généralement les valeurs de l’en-tête de commande fournisseur, mais il est possible de remplacer les champs si certaines lignes doivent être livrées à des emplacements différents. 

1.  Dans le champ **Quantité**, entrez `10` 

    > **Remarque :** Le champ **Quantité** est automatiquement complété avec la **quantité minimale de commande** du **produit** si celle-ci est configurée, ou avec la valeur **1**. 

    > **Remarque :** Autres champs de détails de ligne disponibles : 
    >
    >    - **Unité** : Indique l’unité de mesure de la quantité commandée. Normalement, l’unité est automatiquement fournie à partir de l’unité d’achat sur les données principales du produit. 
    >
    >    - **Prix unitaire** : Contient une valeur provenant d’un contrat d’achat ou d’un accord commercial. Il est possible de modifier le prix unitaire de lignes de commande individuelles : par exemple si un prix unique est négocié avec le fournisseur. 
    >
    >    - **Remise** : Représente un montant de remise par unité. Cette remise réduit donc le prix unitaire. Elle est généralement fournie automatiquement à partir d’accords d’achat ou d’accords commerciaux, mais il est possible de la remplacer sur des lignes individuelles si des remises uniques ont été négociées avec le fournisseur. 
    >
    >    - **Pourcentage de remise** : Une fois saisi, il réduit le montant net de la ligne en conséquence. Il est souvent fourni automatiquement à partir d’accords d’achat ou d’accords commerciaux, mais il est possible de le remplacer sur des lignes individuelles si un pourcentage de remise a été négocié avec le fournisseur. 
    >
    >    - **Montant net** : Calculé à partir d’autres champs de la ligne, notamment la quantité, le prix unitaire, la remise et le pourcentage de remise. Il est possible de modifier le montant net, mais les champs Prix unitaire, Remise et Pourcentage de remise sont vides et lorsque vous passez à la ligne, le montant affiché est proportionnel au montant net. Généralement, le champ Montant net n’est utilisé que pour afficher le montant net de la ligne. 

1.  Dans le raccourci **Détails de la ligne**, développez si nécessaire, puis sélectionnez l’onglet **Livraison**. 

    > **Remarque :** Une **date de livraison** unique peut être affectée à chaque ligne de commande. La date est héritée du champ **Date de livraison** dans l’en-tête de la commande fournisseur, mais vous pouvez la modifier. 

1.  Notez le **numéro de la commande fournisseur** et **fermez** la page. 

1.  Dans l’affichage de liste **Toutes les commandes fournisseur**, utilisez le **filtre** pour trouver votre nouvelle commande fournisseur. 

1.  Quand vous avez terminé, **fermez** la page **Toutes les commandes fournisseur** et revenez à la page d’accueil. 

