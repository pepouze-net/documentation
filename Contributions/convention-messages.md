# Conventions des messages d'atomes de code

Un atome de code (ou "commit" pour l'outre-manche) s'accompagne généralement d'un petit message
déclaratif sur son contenu. Ainsi le journal d'historique se lit avec beaucoup de clareté !

Au Pepouez Net on aime bien les conventions (pas toutes non plus..), c'est pourquoi on s'applique
à utiliser le célèbre [Commits Conventionels](https://www.conventionalcommits.org/fr/v1.0.0/).

```
<raison>[périmètre]: <description>

[corp optionnel]
```

Mais comme ici on fait les choses bien, il s'agirait d'être un peu chauvin et de dialoguer correctement !
C'est pourquoi nous avons un peu nationalisé le corpus des `raisons` pour le rendre un peu plus chalereux :

```
doc (documentation) : c'est qui le doc de la doc, doc ?
oups (zut) : corrige un p'tit soucis de rien du tout
hop (!) : v'la une nouvelle fonctionnalité
pff (corvée) : soupir, mais de satisfaction
biduc (bitoduc) : le machine qui se lance quand tu pousse sur le dépôt
reu (reusinage) : on structure un peu le code
vroum (vroum) : pour des performances de zinzin
```

Par exmple :

```
oups(app.py): correction de typo dans l'import de requests
vroum(Dockerfile): ajout du drapeau apt --no-install-recommends
hop!: chiffrement de bout-en-bout sur le clavardage
biduc: lancement de Ruff à chaque nouvelle fusiodemande
```

.. et voilà !