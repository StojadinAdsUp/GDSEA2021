# GDSEA2021

### Products impressions

> Visite sur une page "Catégorie"

```html
<script>
    window.dataLayer = window.dataLayer || [];
    //Googe Ads data
    window.dataLayer.push({
        google_tag_params : {
            ecomm_pagetype : "category",
            ecomm_category : "Pice agricole Travail du sol"
        }
    });
    //Google Analytics data
    window.dataLayer.push({ ecommerce : null}); //Effacer les infos ecommerce précédentes
    window.dataLayer.push({
        event : "view_item_list",
        action_field : {

        },
        ecommerce : {
            currency : "EUR",
            items : [ 
                {
                    item_id : "55978", //{string} | id du produit
                    item_name : "Soc charrue Kuhn - Gauche - Carbure", // {string} | Nom du produit
                    currency : "EUR", // {string} | Code ISO de la devise affichée
                    price : 160.54, // {number} | prix unqiue du produit TTC
                    quantity : 1, // {number} | quantité
                    index : 1, // {number} | position du produit dans la liste
                    item_brand : "Khun", // {string} | marque du produit
                    item_category : "Pièce agricole Travail du sol", // {string} |
                    item_category2 : "Pièce de Charrue", // {string} |
                    item_category3 : "Sac de charrue" // {string} |
                }, {
                    item_id : "55995", 
                    item_name : "Piece agricole Travail du sol", 
                    currency : "EUR", 
                    price : 141.55, 
                    quantity : 1, 
                    index : 2, 
                    item_brand : "Kverneland", 
                    item_category : "Pièce agricole Travail du sol", 
                    item_category2 : "Pièce de Charrue", 
                    item_category3 : "Sac de charrue" 
                }, {
                    // Suite des produits 
                }
            ]
        }
    });
</script>
```

### Products clicks

> Clics sur la miniature d'un produit

```html
<script>
    window.dataLayer = window.dataLayer || [];
    //Google Analytics data
    window.dataLayer.push({ ecommerce : null}); //Effacer les infos ecommerce précédentes
    window.dataLayer.push({
        event : "select_item",
        ecommerce : {
            currency : "EUR",
            items : [ 
                {
                    item_id : "55978", //{string} | id du produit
                    item_name : "Soc charrue Kuhn - Gauche - Carbure", // {string} | Nom du produit
                    currency : "EUR", // {string} | Code ISO de la devise affichée
                    price : 160.54, // {number} | prix unqiue du produit TTC
                    quantity : 1, // {number} | quantité
                    index : 1, // {number} | position du produit dans la liste
                    item_brand : "Khun", // {string} | marque du produit
                    item_category : "Pièce agricole Travail du sol", // {string} |
                    item_category2 : "Pièce de Charrue", // {string} |
                    item_category3 : "Sac de charrue" // {string} |
                }
            ]
        }
    });
</script>
```

### Products details

> Visite sur une page "Produit"

```html
<script>
    window.dataLayer = window.dataLayer || [];
    //Googe Ads data
    window.dataLayer.push({
        google_tag_params : {
            ecomm_pagetype : "product",
            ecomm_prodid : "55978",
            ecomm_totalvalue : 160.54, // {number} | prix unqiue du produit TTC
             ecomm_totalvalue_tax_exc : 128.43, // {number} | prix unqiue du produit HT
            ecomm_category : "Pièce agricole Travail du sol"
        }
    });
    //Google Analytics data
    window.dataLayer.push({ ecommerce : null}); //Effacer les infos ecommerce précédentes
    window.dataLayer.push({
        event : "view_item",
        ecommerce : {
            currency : "EUR",
            items : [ 
                {
                    item_id : "55978", //{string} | id du produit
                    item_name : "Soc charrue Kuhn - Gauche - Carbure", // {string} | Nom du produit
                    currency : "EUR", // {string} | Code ISO de la devise affichée
                    price : 160.54, // {number} | prix unqiue du produit TTC
                    quantity : 1, // {number} | quantité
                    index : 0, // {number} | position du produit dans la liste = zéro par défaut 
                    item_brand : "Khun", // {string} | marque du produit
                    item_category : "Pièce agricole Travail du sol", // {string} |
                    item_category2 : "Pièce de Charrue", // {string} |
                    item_category3 : "Sac de charrue" // {string} |
                }
            ]
        }
    });
</script>
```

### Add to cart

> Clic sur le bouton "Ajout au panier"

```html
<script>
    window.dataLayer = window.dataLayer || [];
    //Google Analytics data
    window.dataLayer.push({ ecommerce : null}); //Effacer les infos ecommerce précédentes
    window.dataLayer.push({
        event : "add_to_cart",
        ecommerce : {
            currency : "EUR",
            items : [ 
                {
                    item_id : "55978", //{string} | id du produit
                    item_name : "Soc charrue Kuhn - Gauche - Carbure", // {string} | Nom du produit
                    currency : "EUR", // {string} | Code ISO de la devise affichée
                    price : 160.54, // {number} | prix unqiue du produit TTC
                    quantity : 1, // {number} | quantité du produit ajouté au panier
                    index : 0, // {number} | position du produit dans la liste  = zéro par défaut 
                    item_brand : "Khun", // {string} | marque du produit
                    item_category : "Pièce agricole Travail du sol", // {string} |
                    item_category2 : "Pièce de Charrue", // {string} |
                    item_category3 : "Sac de charrue" // {string} |
                }
            ]
        }
    });
</script>
```

### Remove from cart

> Clics sur le bouton "Supprimer ce produit"

```html
<script>
    window.dataLayer = window.dataLayer || [];
    //Google Analytics data
    window.dataLayer.push({ ecommerce : null}); //Effacer les infos ecommerce précédentes
    window.dataLayer.push({
        event : "remove_from_cart",
        ecommerce : {
            currency : "EUR",
            items : [ 
                {
                    item_id : "55978", //{string} | id du produit
                    item_name : "Soc charrue Kuhn - Gauche - Carbure", // {string} | Nom du produit
                    currency : "EUR", // {string} | Code ISO de la devise affichée
                    price : 160.54, // {number} | prix unqiue du produit TTC
                    quantity : 1, // {number} | quantité du produit enlevé du panier
                    index : 0, // {number} | position du produit dans la liste = zéro par défaut 
                    item_brand : "Khun", // {string} | marque du produit
                    item_category : "Pièce agricole Travail du sol", // {string} |
                    item_category2 : "Pièce de Charrue", // {string} |
                    item_category3 : "Sac de charrue" // {string} |
                }
            ]
        }
    });
</script>
```

### View cart

> Visite sur la page "Panier"

```html
<script>
    window.dataLayer = window.dataLayer || [];
    //Googe Ads data
    window.dataLayer.push({
        google_tag_params : {
            ecomm_pagetype : "cart",
            ecomm_prodid : [
                "55978",
                "55995"
            ],
            ecomm_totalvalue : 443.64, // {number} | Montant total (produits x quantité) du panier TTC
            ecomm_totalvalue_tax_exc : 354.91 // {number} | Montant total (produits x quantité) du panier HT
        }
    });
    //Google Analytics data
    window.dataLayer.push({ ecommerce : null}); //Effacer les infos ecommerce précédentes
    window.dataLayer.push({
        event : "view_cart",
        action_field : {

        },
        ecommerce : {
            currency : "EUR",
            value : 443.64, // {number} | Montant total (produits x quantité) du panier TTC
            items : [ 
                {
                    item_id : "55978", //{string} | id du produit
                    item_name : "Soc charrue Kuhn - Gauche - Carbure", // {string} | Nom du produit
                    currency : "EUR", // {string} | Code ISO de la devise affichée
                    price : 160.54, // {number} | prix unqiue du produit
                    quantity : 1, // {number} | quantité
                    index : 1, // {number} | position du produit dans la liste
                    item_brand : "Khun", // {string} | marque du produit
                    item_category : "Pièce agricole Travail du sol", // {string} |
                    item_category2 : "Pièce de Charrue", // {string} |
                    item_category3 : "Sac de charrue" // {string} |
                }, {
                    item_id : "55995", 
                    item_name : "Piece agricole Travail du sol", 
                    currency : "EUR", 
                    price : 141.55, 
                    quantity : 2, 
                    index : 2, 
                    item_brand : "Kverneland", 
                    item_category : "Pièce agricole Travail du sol", 
                    item_category2 : "Pièce de Charrue", 
                    item_category3 : "Sac de charrue" 
                }, {
                    // Suite des produits 
                }
            ]
        }
    });
</script>
```

### Begin checkout

> Visite sur la page "Panier"

```html
<script>
    window.dataLayer = window.dataLayer || [];
    //Googe Ads data
    window.dataLayer.push({
        google_tag_params : {
            ecomm_pagetype : "checkout",
            ecomm_prodid : [
                "55978",
                "55995"
            ],
            ecomm_totalvalue : 443.64, // {number} | Montant total (produits x quantité) du panier TTC
            ecomm_totalvalue_tax_exc : 354.91 // {number} | Montant total (produits x quantité) du panier HT
        }
    });
    //Google Analytics data
    window.dataLayer.push({ ecommerce : null}); //Effacer les infos ecommerce précédentes
    window.dataLayer.push({
        event : "begin_checkout",
        action_field : {

        },
        ecommerce : {
            currency : "EUR",
            value : 443.64, // {number} | Montant total (produits x quantité) du panier TTC
            items : [ 
                {
                    item_id : "55978", //{string} | id du produit
                    item_name : "Soc charrue Kuhn - Gauche - Carbure", // {string} | Nom du produit
                    currency : "EUR", // {string} | Code ISO de la devise affichée
                    price : 160.54, // {number} | prix unqiue du produit TTC
                    quantity : 1, // {number} | quantité
                    index : 1, // {number} | position du produit dans la liste
                    item_brand : "Khun", // {string} | marque du produit
                    item_category : "Pièce agricole Travail du sol", // {string} |
                    item_category2 : "Pièce de Charrue", // {string} |
                    item_category3 : "Sac de charrue" // {string} |
                }, {
                    item_id : "55995", 
                    item_name : "Piece agricole Travail du sol", 
                    currency : "EUR", 
                    price : 141.55, 
                    quantity : 2, 
                    index : 2, 
                    item_brand : "Kverneland", 
                    item_category : "Pièce agricole Travail du sol", 
                    item_category2 : "Pièce de Charrue", 
                    item_category3 : "Sac de charrue" 
                }, {
                    // Suite des produits 
                }
            ]
        }
    });
</script>
```

### Add Shipping Method

> Visite sur la page "Mode de livraison"

```html
<script>
    window.dataLayer = window.dataLayer || [];
    //Googe Ads data
    window.dataLayer.push({
        google_tag_params : {
            ecomm_pagetype : "checkout",
            ecomm_prodid : [
                "55978",
                "55995"
            ],
            ecomm_totalvalue : 443.64, // {number} | Montant total (produits x quantité) du panier TTC
            ecomm_totalvalue_tax_exc : 354.91 // {number} | Montant total (produits x quantité) du panier HT
        }
    });
    //Google Analytics data
    window.dataLayer.push({ ecommerce : null}); //Effacer les infos ecommerce précédentes
    window.dataLayer.push({
        event : "add_shipping_method",
        action_field : {

        },
        ecommerce : {
            currency : "EUR",
            value : 443.64, // {number} | Montant total (produits x quantité) du panier TTC
            items : [ 
                {
                    item_id : "55978", //{string} | id du produit
                    item_name : "Soc charrue Kuhn - Gauche - Carbure", // {string} | Nom du produit
                    currency : "EUR", // {string} | Code ISO de la devise affichée
                    price : 160.54, // {number} | prix unqiue du produit TTC
                    quantity : 1, // {number} | quantité
                    index : 1, // {number} | position du produit dans la liste
                    item_brand : "Khun", // {string} | marque du produit
                    item_category : "Pièce agricole Travail du sol", // {string} |
                    item_category2 : "Pièce de Charrue", // {string} |
                    item_category3 : "Sac de charrue" // {string} |
                }, {
                    item_id : "55995", 
                    item_name : "Piece agricole Travail du sol", 
                    currency : "EUR", 
                    price : 141.55, 
                    quantity : 2, 
                    index : 2, 
                    item_brand : "Kverneland", 
                    item_category : "Pièce agricole Travail du sol", 
                    item_category2 : "Pièce de Charrue", 
                    item_category3 : "Sac de charrue" 
                }, {
                    // Suite des produits 
                }
            ]
        }
    });
</script>
```

### Add Shipping Address

> Visite sur la page "Adresse de livraison"

```html
<script>
    window.dataLayer = window.dataLayer || [];
    //Googe Ads data
    window.dataLayer.push({
        google_tag_params : {
            ecomm_pagetype : "checkout",
            ecomm_prodid : [
                "55978",
                "55995"
            ],
            ecomm_totalvalue : 443.64, // {number} | Montant total (produits x quantité) du panier TTC
            ecomm_totalvalue_tax_exc : 354.91 // {number} | Montant total (produits x quantité) du panier HT
        }
    });
    //Google Analytics data
    window.dataLayer.push({ ecommerce : null}); //Effacer les infos ecommerce précédentes
    window.dataLayer.push({
        event : "add_shipping_address",
        action_field : {

        },
        ecommerce : {
            currency : "EUR",
            value : 443.64, // {number} | Montant total (produits x quantité) du panier TTC
            items : [ 
                {
                    item_id : "55978", //{string} | id du produit
                    item_name : "Soc charrue Kuhn - Gauche - Carbure", // {string} | Nom du produit
                    currency : "EUR", // {string} | Code ISO de la devise affichée
                    price : 160.54, // {number} | prix unqiue du produit TTC
                    quantity : 1, // {number} | quantité
                    index : 1, // {number} | position du produit dans la liste
                    item_brand : "Khun", // {string} | marque du produit
                    item_category : "Pièce agricole Travail du sol", // {string} |
                    item_category2 : "Pièce de Charrue", // {string} |
                    item_category3 : "Sac de charrue" // {string} |
                }, {
                    item_id : "55995", 
                    item_name : "Piece agricole Travail du sol", 
                    currency : "EUR", 
                    price : 141.55, 
                    quantity : 2, 
                    index : 2, 
                    item_brand : "Kverneland", 
                    item_category : "Pièce agricole Travail du sol", 
                    item_category2 : "Pièce de Charrue", 
                    item_category3 : "Sac de charrue" 
                }, {
                    // Suite des produits 
                }
            ]
        }
    });
</script>
```

### Add Payment Method

> Visite sur la page "Paiement et facturation"

```html
<script>
    window.dataLayer = window.dataLayer || [];
    //Googe Ads data
    window.dataLayer.push({
        google_tag_params : {
            ecomm_pagetype : "checkout",
            ecomm_prodid : [
                "55978",
                "55995"
            ],
            ecomm_totalvalue : 443.64, // {number} | Montant total (produits x quantité) du panier TTC
            ecomm_totalvalue_tax_exc : 354.91 // {number} | Montant total (produits x quantité) du panier HT
        }
    });
    //Google Analytics data
    window.dataLayer.push({ ecommerce : null}); //Effacer les infos ecommerce précédentes
    window.dataLayer.push({
        event : "add_payment_info",
        action_field : {

        },
        ecommerce : {
            currency : "EUR",
            value : 443.64, // {number} | Montant total (produits x quantité) du panier TTC
            items : [ 
                {
                    item_id : "55978", //{string} | id du produit
                    item_name : "Soc charrue Kuhn - Gauche - Carbure", // {string} | Nom du produit
                    currency : "EUR", // {string} | Code ISO de la devise affichée
                    price : 160.54, // {number} | prix unqiue du produit TTC
                    quantity : 1, // {number} | quantité
                    index : 1, // {number} | position du produit dans la liste
                    item_brand : "Khun", // {string} | marque du produit
                    item_category : "Pièce agricole Travail du sol", // {string} |
                    item_category2 : "Pièce de Charrue", // {string} |
                    item_category3 : "Sac de charrue" // {string} |
                }, {
                    item_id : "55995", 
                    item_name : "Piece agricole Travail du sol", 
                    currency : "EUR", 
                    price : 141.55, 
                    quantity : 2, 
                    index : 2, 
                    item_brand : "Kverneland", 
                    item_category : "Pièce agricole Travail du sol", 
                    item_category2 : "Pièce de Charrue", 
                    item_category3 : "Sac de charrue" 
                }, {
                    // Suite des produits 
                }
            ]
        }
    });
</script>
```

### Purchase

> Visite de la page de confirmation de commande

```html
<script>
    window.dataLayer = window.dataLayer || [];
    //Googe Ads data
    window.dataLayer.push({
        google_tag_params : {
            ecomm_pagetype : "purchase",
            ecomm_prodid : [
                "55978",
                "55995"
            ],
            ecomm_totalvalue : 443.64, // {number} | Montant total (produits x quantité) du panier TTC
            ecomm_totalvalue_tax_exc : 354.91 // {number} | Montant total (produits x quantité) du panier HT
        }
    });
    //Google Analytics data
    window.dataLayer.push({ ecommerce : null}); //Effacer les infos ecommerce précédentes
    window.dataLayer.push({
        event : "purchase",
        action_field : {

        },
        ecommerce : {
            currency : "EUR",
            value : 443.64, // {number} | Montant total (produits x quantité) du panier TTC
            transaction_id : "T1234", // {string} | ID de la transaction sur la BDD
            first_purchase : true, // {boolean} | première transaction
            payment_method : "Credit Card", //{string} | Méthode de paiement choisie par l'utilisateur
            items : [ 
                {
                    item_id : "55978", //{string} | id du produit
                    item_name : "Soc charrue Kuhn - Gauche - Carbure", // {string} | Nom du produit
                    currency : "EUR", // {string} | Code ISO de la devise affichée
                    price : 160.54, // {number} | prix unqiue du produit TTC
                    quantity : 1, // {number} | quantité
                    index : 1, // {number} | position du produit dans la liste
                    item_brand : "Khun", // {string} | marque du produit
                    item_category : "Pièce agricole Travail du sol", // {string} |
                    item_category2 : "Pièce de Charrue", // {string} |
                    item_category3 : "Sac de charrue" // {string} |
                }, {
                    item_id : "55995", 
                    item_name : "Piece agricole Travail du sol", 
                    currency : "EUR", 
                    price : 141.55, 
                    quantity : 2, 
                    index : 2, 
                    item_brand : "Kverneland", 
                    item_category : "Pièce agricole Travail du sol", 
                    item_category2 : "Pièce de Charrue", 
                    item_category3 : "Sac de charrue" 
                }, {
                    // Suite des produits 
                }
            ]
        }
    });
</script>
```
