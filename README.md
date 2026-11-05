# Sentinelle — dashboard de l'équipe Smartshop

Adresse : **https://smartshop-ia.github.io/sentinelle/**

Page publique **sans aucune donnée** : après la connexion Google, elle lit l'état de la Sentinelle dans
Firebase (projet `smartshop-catalogues`, document `sentinelle/etat`), réservé aux comptes de la collection
`authorizedUsers` — la même liste que les Études des commandes et l'Analyse LBI.

Les données sont envoyées à chaque passage de la Sentinelle (dépôt privé `SMARTSHOP-IA/inspecteur-ia`).
Cette page est fabriquée là-bas : `python inspecteur/page_equipe.py index.html`, puis recopiée ici.
