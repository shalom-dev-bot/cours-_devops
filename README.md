# INTRODUCTION AU DEVOPS
 ici lorsqu'on devellope une application alors on lui met en productions dans des serveurs
 et parlant de cela on a les serveur *** PAAS *** 
 
 ## 1 PASS 
 ici generalement ls majorite des serveur sont deja configurer juste des simple configuration qui ne demande pas trop de connaissance en la matiere 
 EXEMPLE nous avons *** heruku, render***
    ### REMARQUE 
    en genie logiciel il existe une notion nomme SDLC(software development life circle)
    ici on passe par une processus d'etape a savoir 

    - RQ(requirement datery): ici on collete tout les informations pour le developpement du logicie;
    - ANALYSE 
    - DESIGN
    - IMPLEMENTATION
    - DEPLOYEMENTS
    - MAINTENANCE

don pour applique le principe de SDLC il existe plusieur methode a svoir

    - PROTOTYPE  ici cela est pour juste un projet de tetst qui comporte 2 a 3 fonctionaliter pouvant faire recour a la methode waterfall ou agile
    - WATERFALL MODEL  ici apres la resolution d'une tache on ne peux pas revenir en arriere meme si il ya erreur 
    - METHODE AGILE  elle est la pour resoudre e probleme du waterfall donc il ya de return back 

    alors compte tenue  de tout cela , le RQ est generalement concu entre le chef de l'entreprise et le clients et apres collete des information cela est enoer a l'equipe de devellopement qui ferront l'analyse la conception et l'implementation puis apres cela est transmis a l'equipe de deployement qui vas mettre en production et faire la maintenance   ce qui est parfois tres long et pas recommander .
    alors voila pourquoi le devops est la afin que apres chaque fonctionalite cela soit teste en ligne directement ainsi pour permettre une bonne communication entre les developpeur

# 2  LE DEVOPS
cela est contitue du mot DEV  qui veut dire devellopeur  OPS qui veux dire *** OPERATIONS ***
et et tout cele forme ce qu'on appele *** DEVOPS***
olors de quoi est constitue le  *** OPS ***

  - COLLABORATION
  - MONITORING
  - CI/CD
  - IAC (infrastructure as code)
  - AUTOMATISATION

## A LA COLLABORATIONS
   ici le devops doit faciter la collarorations entre les differents membre de l'equipe sur la gestion du project

## B AUTOMATISATIONS
  ici le devops automatise tout le project de sorte que chaque fonctionater etant nouvelle puis etre deployer automatiquement a travers les les ligne de code permettant un test pour cela alors lorsque on creer le project dans github chaque developpeur ajoute sa fonctionaliter et cela passe par un test puis apres le project ce *** build*** apres cela qui est une serie de test cela est deployer alors on retient au 
  l'automatisations permet de faire en sorte que le project soit automatique du debut jusqu'a la livraison 

## C LE IAC

  lorsque les utilisation envoie des donnees dans la bas de donnees et que l'espace est inssufissant   generalement la solution est de payer de l'espace pour augmenter cela ce qui peux etre resolu d'une autre   maniere   voila pourquoi le  IAC est la permettant d'ecrire un code qui augmenter de l'espace automatiuements orsque cela est insuffisant on parle de la ram de la memoire de stockage

## D LE CI/CD (continue intergrations/continue delivery ou deployments)
  
  ### CI 
     ici lorsque on ajoute une fonctionaliter le CI permet que cela ne puis pas ecraser les fonctionaliter deja existant 
  ### CD 
      ***continue deploy***  ici lorsque on ajoute une fonctionaliter cela es directement texte et mise dans l'applications en ligne donc pour un utilisateur dans l'application cela v directement apparaitre

      *** CONTINUE DELIVERY*** 
        ici on veut texte la nouvelle fonctionaliter sans que cela ne soit deployer pour etre vue par l'utilisateur  cela est juste la pour un teste pour les developper 
      en gros cela est le plus grand ravaille du devops

##   E LE MONITORING
     elle permet de traquer tout les erreur du systeme permettant au coduer de le resoudre car le client ne vas pas te dire l'erreur ce a toi de voir   donc il permet de controler tout les actions du client dans l'appliction et cela rend plus de profetionalisme
     ---

# LECON 2 LINUX
 
  le systeme linux a un coeur et il est appeller le KERNEL et es lui qui vas communiquer avec les partir materiel du system comme la souris le clavier et d\autre on les retrouve dans les dossier suivant DEV ,PROC ET SYS
  dans linux il existe des tache qui sexecute en arriere plan et generalement il finissent pas la lettre (d)
  et est appeler *** LES DEMOND ***
  nous avons les fichier cacher et est materialiser par un point au debut du mot

  LISTE DES DOSSIER SYSTEME

    pour les gestion du system
      bin  sbin  lib  boot  etc

    pour la gestion des utilisateru 
      home   root

    Pour le stocjage des donnees
      var  tmp   srv

    pour le materiel et peripherique
      dev  proc  sys

    pour les logiciel et extension
      opt  usr

    pour les montage de memoire
      mnt  media 
      
  ### LES COMMMANDE LES PLUS IMPORTANTE POUR LE DEVOPS

    ici nous allons commencer par la commande 
    *** sudo su*** cette commande te permet de te connecter en tant que super utilisateur et generalement on le fait souvent pour faire des installoations dans notre systeme

  ###LES GESTIONNAIRE DE PACKAGE

    - yum
    - apt

      si on veut installer un service sur notre machine on utilise soit le yum ou le apt selon votre distribution cela peux etre ubuntu pop os debian centos ou d'autres
      lprsque cela ne veux pas montre la version apres installation alors cela voudrait dit que ces un service system et pour cela on doit faire appele au service systeme a traverrs la commange suivant
        systemctl(systemctl action(
          start ,restart, stop, status,reload,enable ,desable,
        ))puis le nom du service 
        CAT(cat et le nom du fichier) permet d'afiche le contenue du fichier
        nous avon *** VIM *** qui est la commande permettant d'ouvrir un editeur dans le terminal

      par EXEMPLE nous 
      pour installer on fait *** apt install/unistall puis le nom de service
      apt install nginx(est un serveur web )il joue le role de RIVER PROXY ,LOAD BALANCER


