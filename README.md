# Toys-Models-Dashboard
Tableau de bord Power BI pour piloter les ventes, les finances, la logistique et les ressources humaines d’une entreprise de modèles et maquettes.


# Tableau de bord décisionnel — Models and Toys Shop

## Introduction

Dans le cadre de ce projet, une entreprise spécialisée dans la vente de modèles et de maquettes souhaite mieux piloter son activité à l’aide de ses données.

Elle dispose d’une base de données regroupant notamment les employés, les produits, les commandes et les clients. L’objectif est d’explorer ces données, d’en comprendre la structure et de concevoir un tableau de bord interactif avec Power BI.

Le directeur souhaite pouvoir actualiser le rapport chaque matin afin de disposer d’informations récentes pour suivre l’activité et prendre ses décisions.

## Objectifs et enjeux

Le tableau de bord s’articule autour de quatre domaines :

- **Ventes** : chiffre d’affaires, marges, clients et performance commerciale.
- **Finances** : encaissements, soldes à payer et risques clients.
- **Logistique** : niveaux de stock, produits critiques, rotation et délais de livraison.
- **Ressources humaines** : suivi des employés et des indicateurs liés aux équipes.

Les indicateurs clés de performance (KPI) sont classés selon les priorités définies par le client :

- 🔴 **Rouge — Obligatoire**
- 🟢 **Vert — Complémentaire**
- ⚫ **Noir — Optionnel**

Lorsque certaines demandes ne peuvent pas être traitées à partir des données disponibles, des indicateurs alternatifs ou complémentaires peuvent être proposés. Cette démarche permet de répondre au besoin métier tout en tenant compte des limites de la base de données.

## Démarche

Le projet consiste à :

1. Explorer la base de données et examiner ses relations.
2. Vérifier la qualité et la cohérence des données utiles à l’analyse.
3. Définir les KPI et leurs règles de calcul.
4. Concevoir des pages Power BI adaptées aux quatre domaines métier.
5. Présenter les résultats de façon claire pour faciliter le suivi et la prise de décision.

## Indicateurs

Le client souhaite les indicateurs ci-dessous par domaines :

📌 Ressources humaines
- 🔴 Performance des représentants commerciaux : Calculer le chiffre d’affaires généré par chaque employé chargé des ventes.
- 🟢 Ratio commandes/paiements par représentant commercial : Identifier les écarts entre les commandes passées et les paiements reçus pour chaque représentant.
- 🟢 Performance des bureaux : Mesurer le chiffre d’affaires généré par chaque bureau.

📌 Ventes
- 🔴 Chiffre d’affaires par mois et par région + taux d’évolution mensuel : Suivre les revenus générés par région et par mois pour identifier les tendances géographiques.
- 🔴 Produits les plus/moins vendus par catégorie : Identifier les produits les plus performants dans chaque catégorie.
- 🟢 La marge brute par produit et par catégorie : Mesurer la marge brute et en déduire les produits/catégories les plus/moins rentables.
- ⚫ Taux d’évolution mensuel des ventes par catégorie : Mesurer la performance de chaque catégorie de produit dans le temps.
- ⚫ Panier moyen : Mesurer le panier moyen des commandes.
- ⚫ Taux de retour des clients (repeat customers) : Mesurer la fidélité des clients en identifiant ceux qui passent plusieurs commandes.

📌 Finances
- 🔴 Clients générant le plus/moins de revenus : Identifier les clients générant le plus de revenus pour mieux les fidéliser.
- 🟢 Taux de recouvrement des créances par client : Identifier les clients ayant un montant élevé de commandes non payées.
- ⚫ Croissance des ventes par trimestre : Identifier les tendances saisonnières ou les opportunités de croissance.
- ⚫ Montant moyen des paiements + clients en dessous de la moyenne : Évaluer la capacité de paiement des clients.
- ⚫ Taux de paiement par délai : Identifier combien de temps les clients mettent pour payer après une commande.

📌 Logistique
- 🔴 Stock des produits sous seuil critique : Identifier les produits dont le stock est faible pour éviter les ruptures.
- 🟢 Durée moyenne de traitement des commandes + commandes au-dessus de la moyenne de livraison : Mesurer l’efficacité opérationnelle en analysant le temps entre la date de commande et la date d’expédition.
- ⚫ Taux d’écoulement des stocks : Mesurer la rapidité avec laquelle les stocks sont vendus pour chaque produit.
- ⚫ Taux de commandes livrées en retard : Identifier les problèmes logistiques et améliorer les délais de livraison.
