---
layout: post
title: Product Story V2
---

## Une solution full-commerce intelligente
Axé autour de la prédiction, du machine learning et de l'aide à la décision, la  plateforme vous aide à contrôler toute votre activité commerciale quel que soit le canal utilisé (Boutique, marketplace, E-Commerce) dans un but performant.

Autour de KPI que vous pourrez indiquer ou que la plateforme vous conseillera, vous serez en mesure de suivre facilement l'état de santé de votre business grace à un système de notification intelligent et pourrez aussitôt réagir sur les alertes remontées par la plateforme.

Résolument orientée Business, une brique financière vous permettra de projeter votre BP selon des hypothèses données. Vous pourrez ainsi avoir une vision fine sur votre rentabilité, vos finances et vos couts variables.

Une gestion fine de votre logistique vous permettra d'adresser le bon stock au bon endroit, au bon moment.

Grâce à l'aggregation des données provenant de plusieurs marques vous pourrez vous positionner par rapport au marché, considérer des actions prises par vos concurrents.

Transverse et omniprésente, la machine vous conseillera des actions sur la gestion de vos différents leviers, de la logistique au service clients en passant par l'affichage de votre site ou vos vitrine, la maitrise de vos implantations, votre rythme de réassort.

Suivez de façon précise votre business grâce aux reportings automatisés de la plateforme ainsi que ses analyses et conseils de réactivités.

Proposez à vos clients une nouvelle expérience en boutique en leur proposant des modes de paiements dématérialisés, une livraison à domicile.

### Fonctionnels

#### Finance

1. Analyse de rentabilité : sur réel et prévisions
    - Marge sur coûts variables, transport, logistique
2. Analyse Financière sur réel et prévisions
    - Fond de Roulement
    - Besoin en fond de roulement : Stock, client et fournisseur avec focus sur cout de stock
3. Pilotage / optimisation du stock
    - Indicateur de dépreciation de stock -> Impact sur la marge brut
        + Ex : Sous stock -> Combien on aurait pu vendre et gagner / combien de temps pour m'approvisionner sur mes bests et avoir ce minimum en stock
        + Ex : Sur Stock -> Détection auto de l'obsolescence de stock
    - Modèle de réassort en fonction d'un taux de couverture -> avoir le bon niveau de stock
    - Générateur d'appel d'offre pour le destockage :
        + Exemple : J'ai du stock, je me connecte à l'api de ventes privées, showroom, je reçois la meilleure offre de destockage.
4. Analyse concurrentielle
    - voir le prix produits sur les sites concurrents / Scrapping
    - Présence internationale de la concurrence
5. Devises
    - Conversion
    - Risque (coface)
        + Risque de changement
        + Risque crédit
        + Risque Pays
6. Prédictif
    - Deduction de la prev de n+1 en fonction de résultats n et des hypothèses de saisie manuelle.
    - Simulation de BP + résultat selon complétude des infos initiales.

#### Business

* Suivis automatique des KPIs business (KPIs pré-selectionnés ou proposés) par rapport aux provisions de ventes définies.
    - Levées d'alertes sur les baisses de CA par canal de vente
    - Mise en avant des best sellers / least sellers
    - Répartition ventes par canal / familles produit / géographie
    - Suivis des indicateurs trafic
    - Déduction des causes de succès
    - remontées des produits les plus vus
* Générer des reportings automatiquement
    - Analyse du CA par canal
    - Mise en avant des critères de succès

#### Logistique

* Pilotage de l'image de stock et son coût
* Mise en avant du taux de cotation de la valeur de stock / à la valeur
* Destockage automatique des produits avec taux de rotation faible depuis 30 jours
* Selection de transporteurs selon le poids du produit et son adresse de livraison
* Réappro automatique

#### CRM

* Import
    * Connecteurs CRM marques
    * Connecteur ERP (outils caisse)
    * Connecteur outils Service Client
    * DMP
    * Interface de saisie vendeur
* Suivis
    - Redressement automatique
    - Conseil de segment / cible
* Monitorer
    - Matrice de passage d'un segment à un autre
    - CA par segment
    - Tx de Churn
