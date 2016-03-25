---
layout: post
title: Consolidation Finance
---

Merci pour cet atelier, c’était très intéressant et complet. 
Voilà ce que nous avons dit : 

3 axes principaux ont été sélectionné : 

## Complétude de l’info Catalogue (DEB = Préforma)
    - Code Douanier
        - Vérification de la présence du code douanier
        - Validité du code
        - Verify legal (présence dans les références internationales)
    - Poids du produit
        - Présence du poids en Kg
        - Obligatoire pour l’export (facture proforma)
        - Ctrl de poids
    - Pays de Fabrication
        -  Vérification de sa présence

## TVA
    - Prix TTC (prix affiché)
        - Recalcul du HT
    - Zones
        - Zone « Export » (paradis fiscaux + TOM) -> 0% de TVA mais 12 % de DDP service basé sur valeur produit) 
        - Zone «  IntraCom » (chaque pays = config TVA) 
        - Zone FR (Tx TVA France, DOM -> Tx à vérifier)

## Documents
    - Export
        - Facture proforma (nbre necessaire par pays) -> Envoyé à ADS
        - Facture Magento (clients)
    - IntraCom
        - Facture magento par Pays -> Clients
            - Immatriculé => N° + tx TVA du Pays de Livraison
            - Non immatriculé => N° + tx TVA FR
    - Rq Générale
        - Facture à harmoniser entre intra et mage 