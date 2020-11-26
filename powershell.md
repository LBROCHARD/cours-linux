# powershell

	
Powershell -> permet de faire des scripts genre qui te permettent de faire des boucles
et des trucs auto histoires d'aller un peu plus vite de 600 lignes de code

Get-ChildItem -> ls
Get-Alias [commandes] -> te donne equivalent commande genre tu peut faire alias ls pour faire un ls
Set-Location [chemin] -> cd
Get-Process -> processus en cours comme sur gestionnaire des tâches
Get-Service -> services en cours comme sur gestionnaire des tâches
Get-command -> te donne les commandes 


### grosso modo c'est quoi ? 

bon déjà c'est un logiciel developpé par microsoft c'est un outil de gestion d'automatisations et de management, c'est un peu comme un une version serveur de linux ou d'autre chose, c'est un invité de commande, et je crois bien que c'est un délire genre il est un peu à la base de windows (genre c'est ça le core) mais chui pas bien sûr de ça

petits facs :
-on peut utiliser les touches tab et maj pour completer les lignes de code (ça s'apelle la complétion)
-f7 = historique
-bon bah ça on connais mais bon il faut le rapeler : entrée = executer commande, flèche du haut = commande d'avant
-il y a le copié collé ***amen***


## la structure de commande 

### les applets

de ce que je peut comprendre ici, les commandes sont formées comme des genre de phrases, genre : ```get-service``` où get = verbe service = nom
et ensuite on peut rajouter des commutateurs un peut comme des options spécifique : ```get-service -name "*net*"``` où -name est une option et "*net*" une valeur

et ensuite y'a un truc qui s'apelle da collection d'instance, en gros les commandes sembles revoyer à ce truc qui est un genre de collection d'éléments qui doivent être sois des actions, sois des programmes, je verrais


### les variables

les variables quand même je pense (j'éspère) que tout le monde connais donc je ne m'attarde pas là dessus, mais déjà ce que je peut dire c'est que visiblement, toutes les variables doivent être précédé d'un symbole $, qu'elle sont typées lors de l'affectation, et que le moyen le plus simple de les déclarés est sûrement direct de les affecter (comme d'hab quoi) ex : ```$Process = Get-Process```

### le pipeline

alors celui là j'en avait déjà entendut parlé et même un peu utilisé 
le pipeline déjà, c'est ce charactère : ```|```
il est décris comme capable de "chainer" plusieurs commandes,
moi je le considairerais personellement comme un "et" ou un "puis" étant donné qu'il permet de faire quelquechose d'autre à la suite

### les commandes decouverte 

[Info](#){.btn .btn-info} test

quelques commandes "basiques"

|*cmdlet*|*description*|*alias*|

|--------|--------|--------|

|Get-Command|Informations de base sur les commandes|gcm|

|Get-Help|Aide de base (utiliser -full ou -example)|help, man|

































