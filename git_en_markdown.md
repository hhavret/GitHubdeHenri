## *GitHub*

## 1 Présentation
### 1.1 GitHub

*Plateforme colleborative* Pour dev, plus gradn espace de stockage 
de travaux collaborative dans le monde! GitHub en lui-meme n'est
 plus q'un reseau social come FB.
 Vous construiser un profil, vous y deposez des projets a paratager 
 et vous vous connectez avec d'autre utilisateurs en suivant leurs comptes. Meme
 si la plupart des utilisateeur y deposent des projets de programmes ou de code,
  rien ne vous empeche  d'y placer des textes ou tout type fe fichier à présenter dans 
  vos repertoires de projets.

  ### 1.2 Git
  Git est un *logiciel de controle de version*, 
  ce qui signuifie qu'il gere les modification 
  d'un projet sans écraser n'importe quelle partie du projet.


## 2 Git et GitHub
### 2.1 Vocabulaire
**ligne de commande**: En gros : le programme de l'ordinateur que nous
 utilisons pour entrer des commandes Git. Dans le monde UNIX, on dit qu'on travaille
  en "ligne de commande"
  pour désigner le fait
 d'interagir avec un système informatique en entrant des lignes d'instructions textuelles dans un terminal,
 et non à l'aide d'une interface graphihque
 journal  du Net <https://www.journaldunet.fr/web-tech/dictionnaire-du-webmastering/1445276-commande-informatique-definition-precise-et-exemples>

 **Depot**: un repertoire ou l'epsace de stockage ou vos projets peuvent vivre; les utilisatuer de GitHub racourcissent 
 en "repo" pour "repositoey". Il peut etre un espace de stockage surGitHub ou un uatre hebergeuer en  ligne. 
 A l'interieur d'un depot, vous pouvez conserver des fichiers de codes, des fichiers et des images.

 **Control de version**: Fondamentalement, l'objectif pour lequel Git a été concu.quand vous avaez un 
 fichier, vous l' écraserez à chaque dois que vous sauvegarder plusieurs versions . Avec Git, 
 vous n'est plus obligé de faire ça.git conserve des "instantanes" de chaque point dans 
 l'historique d'un projet, de sorte que vous ne pouvez jamais le perdre ou l'ecraser.


 **commit**: C'est la commande qui done à git toute puissance. Quand vous commmitez, vous prenez un instantané
 une photo de votre depot a ce stade vous donnant point de controle que vous  pouvez ensuite réévaluer ou tout simplement
 restaureer votre projet à cette version.
  Il est necessaires de rappeler ou tout simplement restaureer votre projet à cette version. Il est nécessaire de 
  rappker que le nom de vos commits doivent etre parlant afin de sabvoir a quel stade du projet celui-ci est fait .

  **Branche** : Comment plusieur persones travailleant sur un projet en meme temps qanq que Git ne s'embrouille? Habituellement, elle se debranchent du projet principal avec leur propre versaions complètes, des modifications qu'elles on chacune produites de leur cote.
  Apres avoir termine, il est temps de fusionner cette  bra,che pour la ramener vers la branche master, le repertoire principal
  du projet.



  ### 2.2 Commandes specifique Git
  **git init**: Initialise un nouveau depot git jsuqu'a ce sue vous executiez les commandes Git qui suivent.


  **git config** Raccourcide configuration, ceci est tout particulierement utiles quand vous parametrez Git pour 
  la premiere fois identifiant et mail d'ultilisateur.

  **git help**: oublie une commande? pour afficher les 21 commandes de git ;

  **git status**: verifier le statue de votre repo. Voir les fichiers et et quelle sont les 
  modifications a commiter et sur quelle branche ou repo vous ete entrain de travailler.

  **git add**: Ceci n'ajoute pas de s fichiers dans votre repo, Au lieu de cela , cela porte de ouveaux fichiers à l'attestation de git. 
  Apres avoir ajoute des des fichiers, ils dont inclsus dans les oinstantanes du depot Git


**git commit**: La commande la plus importante de git. Apres avoir effectue toute sorte de modifiaction vous entrez ca afin de prendre
un instantanes du depot.le mettre en memoire.On ecrit ca sous la forme de git commit -m 'votre message'. Le -m indique que la section 
suivante de la commande devrai etre lu comme un message

**git branche**: Vous travaillez avec plusieurs collaborateur et vous voulez produire des modifications de voter 
cote? cette commande vous permet de construire une nouvelle branche, ou une chronologie de commits, des 
modfifications et des ajjouts de fichiers qui sont completement les votres. Votre titre va apres la commande. Si vouls vouliez creer une nouvellesbranche appellee 'yacine'
vous saisiriez git branche yacine
.

**git checkout**: Ceci est une commande de navigation qui vous permet fde vous deplacer vers le repertoires que vous voulez verifier. vous pouver utiliser
cette commande sous la formed e git checkout master pour regarder la branche master, ou git checkout yacine pour regarder une autre branche.

**git merge**: lorsque vous avez finis de travailler sur un branche vous pouvez fusionneer vos modifications vers la branche master , qui est visible pour tous les collaborateur. git merge yadaf prendrait toutes les modification que vous avez apporteer à la branche yadaf  et les ajoutera à la branche master.


**git push** : si vous travaille sur votre ordinateur en local et vous voulez que vos commits soient visibles aussi en ligne sur GitHub, vous pusher les modifications vers gitHub
aevc cette command.



**git pull**: Si vous travaillez en local et  que vous voulez la version la plus a jour de votre repo pour travialler dessus
vous pullez le smodificatrions provenzntt de git hub avec  commande

**gigt clone** : Permet de dudyupliquer , cloner un existant sur github pour l'avoir en local .
La commande github doit etre suivit de url de repo correspondant qui copie depuis github direct.