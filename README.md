# Sentinelle — dashboard de l'équipe Smartshop

Adresse : **https://sentinelle.smartshop.fr/**

Page publique **sans aucune donnée** : après la connexion Google, elle lit l'état de la Sentinelle dans
Firebase (projet `smartshop-catalogues`, document `sentinelle/etat`), réservé aux comptes Google
**@smartshop.fr** (règle Firestore du document `sentinelle/etat`).

Les données sont envoyées à chaque passage de la Sentinelle (dépôt privé `SMARTSHOP-IA/inspecteur-ia`).
Cette page est fabriquée là-bas : `python inspecteur/page_equipe.py index.html`, puis recopiée ici.
