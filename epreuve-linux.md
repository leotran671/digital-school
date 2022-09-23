# DIGITAL SCHOOL - EXAMEN LINUX
## DUREE 
12H30 - 15H30 (3H)
### Consignes
Vous devez envoyer vos réponses par mail à ulrichmonji@eazytraining.fr avant  la fin du temps imparti. Tout travail en retard ne sera pas pris en compte, et la note adéquate sera simplement zéro (O). Bonne chance à tous !


### Exercice 1 : QCM 
Choisir la bonne réponse, 1 seul choix est bon. 

    1) Quels sont les composants d'un Système d'exploitation Linux ?
        A: Kernel, FOS, CLI et GUI
        B: Kernel, File System, API et GUI
        C: Kernel, File System, CLI et GUI
        D: Gnome, Kde, Unity, File System, CLI et GUI

    2) Que signifie le sigle CLI ?
        A: Command Line Interface
        B: COmmand Line Input
        C: Create Long Interface
        D: Create Long Input

    3) Que signifie le sigle GUI ?
        A: Gnome User Interface, c'est le moteur Gnome
        B: Graphical User Interface, c'est une interface graphique
        C: Google User Inherit, un Framework google sur Linux
        D: Graphical User Input

    4) Sur quel composant retrouve-t-on le BIOS ?
        A: Le système d'exploitation
        B: La RAM
        C: Le disque dur
        D: La carte mère

    5) Au démarrage d'un ordinateur, quel programme permet de choisir l'OS de démarrage ?
        A: Le Boot Loader
        B: Le programme initd 
        C: Le driver loader
        D: Le programme systemd

    6) Qu'est-ce qu'une distribution Linux ?
        A: Un Linux dérivé de windows
        B: Une version packagée de Linux parmi plusieurs
        C: Un windows dérivé de Linux
        D: C'est une version récente de MacOS

    7) Linux provient d'un OS payant, dont il en est la copie, lequel ?
        A: CentOs
        B: MacOS
        C: Linus
        D: Unix

    8) Les OS suivants sont des distributions Linux :
        A: Redhat, CentOs, AIX, Debian
        B: MacOS, CentOS, Redhat, Ubuntu
        C: Redhat, CentOs, Fedora, Amazone Linux, Debian, Ubuntu
        D: Alpine, Kali, Kaizen, Windows


    9) C'est quoi un hyperviseur ?
        A: Logiciel de conteneurisation
        B: Logiciel de virtualisation des ressources informatiques
        C: Logiciel de Packaging d'application
        D: C'est un service Windows pour installer des applications

    10) Qu'est-ce qu'un hyperviseur de Type 1 ?
        A: Un driver connecté au BIOS permettant de faire de la virtualisation
        B: Un logiciel installé sous Linux permettant de faire de la virtualisation
        C: Une image docker permettant de faire de la virtualisation
        D: Un système d'exploitation permettant de faire de la virtualisation

    11) Quels sont les hyperviseurs de type 1 dans la liste ?
        A: Proxmox VE, VMware ESXi
        B: Proxmox VE, VMware Workstation
        C: VMware Workstation, Virtualbox
        D: Kvm, Hyperv, VMware Workstation

    12) En virtualisation, qu'appelle-t-on machine invitée ?
        A: Le serveur qui supporte l'hyperviseur
        B: La machine virtuelle hébergée par un hyperviseur
        C: Le serveur physique qui heberge les conteneurs
        D: La machine virtuelle qui contient docker installé

    13) En virtualisation, qu'appelle-t-on machine hôte ?
        A: Le serveur physique qui heberge les conteneurs
        B: La machine virtuelle hébergée par un hyperviseur
        C: La machine virtuelle qui contient docker installé
        D: La serveur où est installé l'hyperviseur

    14) Comment accéder à la console à distance ?
        A: CMD + Alt + F1
        B: Ctrl + Alt + F1
        C: Il faut configurer un client ssh
        D: Signe windows + C

    15) Dans la liste, lesquels sont des clients ssh ?
        A: Putty, MobaXterm, remote-ssh de vscode
        B: Vscode, Putty, Powershell
        C: Powershell, gitbash, Putty
        D: Putty, git, Mobaxterm

    16) Comment configurer Linux afin qu'il démarre par défaut en CLI ?
        A: systemctl set-default cli.target
        B: systemctl set-default multi-user.target
        C: systemctl set-default graphical.target
        D: systemctl set-default gui.target

    17) L'accès ssh donne un 'permission denied'. Quel est votre premier reflexe ?
        A: Envoyer sa clé publique ssh sur le serveur ssh distant
        B: Générer une paire de clé ssh => ssh-keygen
        C: Vérifier la validité de vos informarions d'identifications
        D: Vérifier l'activité du démon ssh sur le serveur ssh distant

    18) Qu'est-ce qu'un shell dans Linux ?
        A: C'est le programme qui interprète les commandes en CLI
        B: C'est une autre appellation du Powershell
        C: C'est la fenêtre noire qu'on voit dans les séries policières
        D: C'est le programme qui permet de démarrer Linux

    19) Quelle touche du clavier permet de bénéficier de l'auto-completion ?
        A: Le Ctrl
        B: Le Shift
        C: La tabulation
        D: L'espace

    20) Comment afficher l'aide des commandes ?
        A: La commande aide
        B: La commande man, exemple : 'man date' pour l'aide sur 'date'
        C: La commande help
        D: L'option --h ou -help à toute commande
                    
    21) Dans Linux, quelle lettre représente les fichiers sockets ?
        A: p
        B: l
        C: d
        D: s

    22) Comment sont représentés les fichiers ordinaires sur Linux ?
        A: un tiret : '-' 
        B: la lettre 'o' 
        C: la lettre 'f' 
        D: la lettre 'b' 

    23) Comment Linux organise-t-il les fichiers dans son système de fichier?
        A: Plusieurs arborescences avec des racines nommées en lettres
        B: Une arborescence ayant une racine unique qui est '/'
        C: Une arborescence par partition de disque numérotées par des lettres
        D: Une arborescence par type de fichiers

    24) Que représente le dossier /home dans l'arborescence Linux ?
        A: C'est l'équivalent de 'Mes Documents' sous windows
        B: C'est le répertoire personnel de l'utilisateur connecté
        C: C'est le répertoire personnel de l'utilisateur root
        D: Il contient les répertoires personnels des utilisateurs

    25) Que représente le dossier /root dans l'arborescence Linux ?
        A: Le répertoire personnel du l'utilisateur 'root'
        B: La racine du système de fichier
        C: C'est l'équivalent de 'Ce PC' dans windows
        D: Le répertoire de tous les points de montage

    26) On accède à un fichier via deux types de chemin, lesquels ?
        A: Chemin primaire et Chemin étendu
        B: Chemin absolu et Chemin Relatif
        C: Chemin primaire et Chemin absolu
        D: Chemin étendu et Chemin absolu

    27) Dans un chemin, que représente le caractère ~ ?
        A: Le répertoire courant
        B: Le répertoire personnel parent
        C: Le répertoire personnel du root
        D: Le répertoire personnel de l'utilisateur connecté

    28) Que se passe-t-il si je tape la commande suivante : 'cd'?
        A: Une erreur de syntaxe est levée par le système
        B: Rien, il faut donner un argument à la commande cd
        C: Je me déplace dans mon répertoire personnel
        D: Je me déplace dans le premier répertoire d'acceuil

    29) Que se passe-t-il si je tape la commande suivante : 'cd -' ?
        A: Une erreur de syntaxe est levée par le système
        B: Je me déplace dans le répertoire précédent
        C: Je me déplace dans mon répertoire personnel
        D: Je me déplace dans le premier répertoire d'acceuil

    30) Que se passe-t-il si je tape la commande suivante : 'cd ..'?
        A: Je me déplace dans le répertoire parent
        B: Je me déplace dans le répertoire précédent
        C: Je me déplace dans mon répertoire personnel
        D: Je me déplace dans le premier répertoire fils

    31) Que se passe-t-il si je tape la commande suivante : 'cd ~jenkins'?
        A: Je me déplace dans le répertoire personnel de l'utilisateur jenkins
        B: Je me déplace dans le répertoire précédent
        C: Je me déplace dans mon répertoire personnel
        D: Je me déplace dans le premier répertoire fils

    32) Sous Linux, l'extension ne fait pas partir du nom du fichier !
        A: Vrai, c'est comme sous  windows
        B: Faux, uniquement pour les fichiers binaires
        C: Faux, l'extension fait partir du nom et est conventionnel
        D: Faux, uniquement pour les fichiers texte
                        


    33) Comment créer un fichier ordinaire vide nommé toto.txt ?
        A: touch toto
        B: touch toto.txt
        C: mkdir toto.txt
        D: mkdir toto

    34) Quelle commande permet de créer un lien de ./toto vers ~/toto.txt ?
        A: cp -s ~/toto.txt ./toto
        B: cp ./toto ~/toto.txt
        C: ln -s ./toto ~/toto.txt
        D: ln -s  ~/toto.txt ./toto

    35) Quelle commande permet de renommer un fichier sur Linux ?
        A: ln
        B: touch
        C: mv
        D: cp

    36) Comment afficher les 20 premières lignes du fichier /var/log/messages ?
        A: head -n 20  /var/log/messages
        B: tail -n 20  /var/log/messages
        C: cat -n 20 /var/log/messages
        D: echo /var/log/messages | head -n 20

    37) Comment supprimer le répertoire ./test_folder ?
        A: rm ./test_folder
        B: rm -r ./test_folder
        C: rm -f ./test_folder
        D: rmdir ../test_folder

    38) Comment trouver le chemin absolu de la commande echo ?
        A: who echo
        B: file echo
        C: find echo
        D: which echo

    39) Quel paquet permet d'installer la commande locate ?
        A: mlocate ou plocate
        B: locate-rpm
        C: locate.pack
        D: locate.paquet

    40) La commande locate est très rapide car elle recherche sur le disque dur directement !
        A: Faux, elle recherche dans le Kernel
        B: Faux, elle recherche dans sa base de donnée interne
        C: Faux, elle recherche  en RAM
        D: Vrai, et il faut mettre à jour avec updatedb

    41) Par défaut, linux fournit une commande permettant de faire de la recherche, laquelle ?
        A: which
        B: grep
        C: locate
        D: find

    44) Que recherche la commande suivante : 'find . -type d' ?
        A: Tous les processus démons dans le répertoire courant
        B: Tous les fichiers démons dans le répertoire courant
        C: Tous les répertoire dans le répertoire courant
        D: Tous les fichiers ordinaires dans le répertoire courant


    45) Un utilisateur particulier est le propriétaire du système, lequel ?
        A: route
        B: root
        C: proote
        D: root_user

    46) Quel est le nom du groupe du super utilisateur ?
        A: super-user-root
        B: super-user-group
        C: root-group
        D: root

    47) Sous linux, on distinque 2 types de groupes, lesquels ?
        A: Les super groupes et les groupes systèmes
        B: Les groupes user et les groupes utilisateurs
        C: Les groupes systèmes et les groupes utilisateurs
        D: Les utilisateurs systèmes et ceux utilisateurs

    48) En notation octale, comment donner uniquement les droits d'éxécution au owner ?
        A: chmod u=rwx,g=0,o=0 <fichier concerné>
        B: chmod u=x,g=-,o=- <fichier concerné>
        C: chmod 100 <fichier concerné>
        D: chmod chmod u=1,g=-,o=-<fichier concerné>

    49) Que fait la commande suivante ? chmod 157 toto.txt
        A: Droit d'exécution au owner
        B: Droits de lecture et d'exécution au groupe
        C: Tous les droits à tous les autres
        D: Toutes les réponses sont valables

    50) 'chown apache: /var/www/html'. Que fait cette commande ?
        A: /var/www/html appartiendra à apache et au groupe apache
        B: /var/www/html appartiendra au groupe apache
        C: Le contenu de /var/www/html appartiendra à apache
        D: Le contenu de /var/www appartiendra à html

    51) Quel fichier est modifié quand je créé un nouvel utilisateur ?
        A: /etc/user
        B: /etc/passwd
        C: /home/passwd
        D: /home/user

    52) Quelle commande permet de changer le mot de passe ?
        A: usermod
        B: chmod
        C: sudo
        D: passwd

    53) Que contient le fichier /etc/group ?
        A: La liste des utilisateurs du système
        B: La liste des mots de passe des groupes
        C: La liste des groupes existants sur le système
        D: Les mots de passe chiffrés

    54) Que contient le fichier /etc/shadow ?
        A: La liste des utilisateurs du système
        B: La liste mots de passe des groupes
        C: La liste des ombres existants sur le système
        D: Les mots de passe chiffrés
        
    55) Lesquels des outils suivants sont des éditeurs de texte ?
        A: vi, word, eclipse
        B: vi, vim, nano, gedit, notepad
        C: vi, vim, nano, powerpoint
        D: writer, vi, gedit,

    56) Que signifie le sigle vim ?
        A: Very Improved Machine
        B: vin maison
        C: rien, c'est simlplement le nom complet de vi
        D: vim = vi iMproved

    57) C'est quoi vimtutor ?
        A: C'est le nom complet de vim
        B: C'est un wrapper de vim
        C: Un tutoriel pour apprendre vi/vim
        D: C'est le projet opensource de vi

    59) Dans vi, 3 modes à connaitre au minimum, lesquels ?
        A: interactif, insertion et commande
        B: interactif, normal et commande
        C: normal, insertion et commande
        D: interactif, insertion et normal

    60) A l'ouverture de vi, quel mode de travail s'ouvre directement ?
        A: insertion
        B: interactif
        C: normal
        D: commande

    61) En une seule commande, comment enregistrer son travail et sortir directement de vi ?
        A: :w!
        B: :q!
        C: :w
        D: :x ou :wq

    62) Depuis le mode interactif, je passe en mode insertion avec la touche __  et je reviens avec __ 
        A: i, Echap
        B: Echap, i
        C: i, Entrée
        D: Entrée, i

    63) Je veux remplacer le mot 'ancien' par 'nouveau' dans tout mon fichier, que faire ?
        A: En mode interractif, :%s/ancien/nouveau/ puis valider
        B: En mode commande, %s/ancien/nouveau/g puis valider
        C: En mode interractif, :s/ancien/nouveau/g puis valider
        D: En mode commande, :%s/ancien/nouveau/ puis valider

    64) Quelle commande permet d'afficher les numéros de ligne dans vi ?
        A: :set mouse=a
        B: :syntax off
        C: :syntax on
        D: :set number, abrégé :se nu

    65) Comment activer le support de la souris dans vi/vim ?
        A: :vsp
        B: :syntax on
        C: :set mouse=a
        D: :se nu

    66) C'est quoi un paquet dans Linux ?
        A: Archive contenant uniquement des binaires
        B: Archive contenant le produit à installer et des règles d'installation
        C: Archive contenant des exécutable windows
        D: C'est une image de système d'exploitation

    67) Quel est le format des paquets sous CentOs, respectivement Ubuntu?
        A: .jar et .zip
        B: .rpm et .apk
        C: .dpkg et .rpm
        D: .rpm et .deb

    68) C'est quoi un dépôt dans Linux ?
        A: C'est un serveur 
        B: Un serveur de code source
        C: Un serveur où on peut télécharger des paquets
        D: Un registre d'images

    69) Dans Redhat et debian, où se trouvent respectivement la configuration des dépôts ?
        A: /etc/yum.repos.d/* & /etc/apt/source.list
        B: /etc/apt/source.list & /etc/yum.repos.d/* 
        C: /etc/yum.repo & /etc/dpkg.repo
        D: /etc/rpm.repo & /etc/deb.repo

    70) Dans Redhat et debian, quels sont respectivement les gestionnaires de paquet bas niveau ?
        A: rpm & deb
        B: rpm & dpkg
        C: dpkg & rpm
        D: deb & rpm

    71) Dans Redhat et debian, quels sont respectivement les gestionnaires de paquet évolués ?
        A: apt, apt-get, aptitude & yum, dnf
        B: yum, dnf & rpm, dpkg
        C: rpm, dpkg & apt, apt-get, aptitude
        D: yum, dnf  &  apt, apt-get, aptitude

    72) Quel avantage majeur propose les gestionnaires de paquet évolués ?
        A: La gestion des dépendances de paquet
        B: La vitesse de téléchargement des paquets
        C: L'appli installée prend moins d'espace
        D: L'auto-configuration des dépôts de paquets

    73) Comment installer le paquet git dans CentOs, respectivement Debian ?
        A: yum install git  et  apt install git
        B: apt install git  et   yum install git
        C: aptitude install git et yum upgrade git
        D: yum remove git   et yum install git

    74) Laquelle des commandes suivantes permet de lister tous les paquets installés ?
        A: yum update
        B: yum search 
        C: rpm -ql
        D: rpm -qa --last

    75) Laquelle des commandes suivantes affiche le paquet qui a installé le fichier /etc/nginx/nginx.conf ?
        A: which /etc/nginx/nginx.conf
        B: rpm -ql /etc/nginx/nginx.conf
        C: rpm -qf /etc/nginx/nginx.conf
        D: rpm -qa --file /etc/nginx/nginx.conf

    76) Laquelle des commandes suivantes affiche tous les fichiers du paquet httpd ?
        A: which /etc/nginx/nginx.conf
        B: rpm -ql httpd
        C: rpm -qf /etc/nginx/nginx.conf
        D: rpm -qa --file httpd.rpm
        
    77) Lesquels des exemples suivants sont des flux de données dans Linux ?
        A: grep, cut, awk, sed, 
        B: Input/output de commande, contenu de fichier, traffic réseau
        C: tcpdump, netcat, netstat
        D: Pipeline, Pipe, tube nommé

    78) Quel outil est approprié pour repérer un motif dans un flux donnée ? 
        A: locate
        B: find
        C: cut
        D: grep et dérivés

    79) Qu'extrait la commande suivante ? :  'cut -c 2-5 syslog' ?
        A: Les lignes en position 2 à 5 du fichier syslog
        B: Les mots en position 2 à 5 du fichier syslog
        C: Les caractères en position 2 à 5 du fichier syslog
        D: Les caractères en position 2 et 5 du fichier syslog

    80) Comment afficher le nombre de lignes uniques contenant exactement 'error' dans le fichier toto?
        A: grep 'error' toto | sort | wc -l
        B: grep -iE 'error' toto | sort | wc -l
        C: grep 'toto' error | sort | wc -l
        D: grep -E 'Error' toto | sort | wc -l

    81) Quels chiffres représentent respectivement la sortie standard et celle erreur ?
        A: 1 et 0
        B: 0 et 1
        C: 2 et 1
        D: 1 et  2

    82) Comment rediriger la sortie d'une commande sur l'entrée d'une autre commande ?
        A: chainage avec le Pipe  :'|'
        B: utilisationn de l'opérateur logique  '||' 
        C: utilisationn de l'opérateur logique  '&' 
        D: utilisationn de l'opérateur logique  '&&' 

    83) Que fait cette commande ? : echo 'Hello from Eazytraining' >> index
        A: Elle ajoute 'Hello from Eazytraining' en milieu de fichier
        B: Elle ajoute 'Hello from Eazytraining' en fin de fichier
        C: Elle ajoute 'Hello from Eazytraining' en debut de fichier
        D: Seul 'Hello from Eazytraining' sera dans le fichier index

    84) Que fait la redirection suivante : 2>>&1 ? 
        A: Redirige la sortie standard au meme endroit que les erreurs
        B: Redirige les erreurs au même endroit que la sortie standard
        C: C'est pareil que  2>&1
        D: Elle n'existe pas sous Linux

    85) Que fait la commande 'tail -f syslog.log' ?
        A: Affiche les 10 dernières lignes de syslog.log
        B: Affiche le début du fichier syslog.log
        C: Affiche progressivement les nouvelles lignes de syslog.log
        D: Affiche la fin du fichier syslog.log

    86) Qu'est ce qu'un processus ?
        A: C'est une application web
        B: C'est un programme en cours d'exécution
        C: C'est une socket Unix
        D: C'est un script linux

    87) L'une des particularité des processus utilisateurs est  : 
        A: Ils tournent en premier plan (foreground)
        B: Ils tournent en tâche de fond
        C: Ils nz sont pas rattachés au terminal de l'utilisateur
        D: Ils sont rattachés au terminal de l'utilisateur

    88) C'est quoi un PID, respectivement PPID ?
        A: ID du processus parent et ID du processus
        B: ID du processus et ID du processus fils
        C: ID du processus et ID du processus parent
        D: ID du processus file & ID du processus parent

    89) Par quel moyen communiquent les processus ?
        A: L'échange de signaux
        B: La socket TCP
        C: Le protocole IP
        D: Les bus de données

    90) Que font les commandes 'ps -ef' ou 'ps -aux' ?
        A: Elles suppriment tous les processus
        B: Elles affiche tous les processus
        C: Elles stoppent tous les processus
        D: Elles mettent en background tous les processus

    91) Comment lancer une commande en arrière plan ?
        A: La commande ps avec l'id du processus en paramètre
        B: La commande fg
        C: La commande jobs
        D: Utilisation du '&' ou 'nohup'

    92) Quel outil permet de lancer régulièrement une commande ?
        A: crontab
        B: acron
        C: at
        D: sleep

    93) Quelle fonctionnalité de systemd permet de remplacer la crontab système?
    A: Les cibles systemd
    B: Les timers systemd
    C: Les runlevels
    D: Les unités

    94) Quel outil permet de déclencher une action à une heure précise en one shot ?
        A: timer systemd
        B: crontab
        C: anacron
        D: at

    95) Dans la crontab, quelle est la fréquence minimale d'éxécution d'une commande ?
        A: 1 sec,
        B: 1 h
        C: 1 min
        D: 1 jour

    96) Que signifie archiver des fichiers ?
        A: compresser plusieurs fichiers en un seul fichier
        B: Regrouper plusieurs fichiers en un unique fichier
        C: Convertir un fichier en un fichier zip
        D: convertie un fichier en fichier binaire

    97) Une archive est forcément compressée !
        A: FAUX, on archive uniquement des fichiers compressés
        B: VRAI uniquement dans Windows
        C: VRAI, dans Linux c'est toujours le cas
        D: FAUX, on a le choix de la compresser ou pas du tout

    98) Que fait cette commande : 'tar cvf rapport rapport_origin/' ?
        A: Elle désarchive l'archive 'rapport_origin' en 'rapport'
        B: Elle créé l'archive 'rapport_origin' du répertoire 'rapport'
        C: Elle créé l'archive 'rapport' du répertoire 'rapport_origin'
        D: Elle désarchive l'archive 'rapport' en 'rapport_origin'

    99) Que fait la commande suivant : 'tar -tf rapport.tar' ?
        A: Listing du contenu de l'archive 'rapport.tar'
        B: Rajout de contenu dans l'archive 'rapport.tar'
        C: Suppression du dernier fichier dans l'archive rapport.tar
        D: Suppression du premier fichier dans l'archive rapport.tar

    100) Que fait cette commande : 'tar xvf rapport.tar' ?
        A: Elle compresse l'archive 'rapport.tar' en .zip
        B: Elle désarchive l'archive 'rapport.tar'
        C: Elle décompresse l'archive compressée 'rapport.tar'
        D: Elle archive le répertoire courant en 'rapport.tar'

    101) L'extension .tar des archives est obligatoire !
        A: VRAI, c'est comme avec winrar et 7zip
        B: VARI, sinon  l'outil tar ne marche pas
        C: FAUX, c'est .gz qu'il faut mettre
        D: FAUX, c'est  simplement une convention

    102) Les outils suivant sont des outils de compression !
        A: gzip, bzip2
        B: tar, pdf creator
        C: gzip,  
        D: vlc, gunzip, bunzip

    103) Quelle option des commandes gzip/bzip2 permet de ne pas toucher au fichier original ?
        A: --save
        B: -k
        C: -s
        D: --kip

    104) Que fait cette commande : 'tar -jxvf rapport.tar.bz2 rapport_origin/' ?
        A: Archivage et compression avec gzip
        B: Archivage et compression avec bzip2
        C: Désarchivage et décompression avec gzip
        D: Désarchivage et décompression avec bzip2

    105) Que fait cette commande : 'tar -zcvf rapport.tar.gz rapport_origin/' ?
        A: Désarchivage et décompression avec bzip2
        B: Désarchivage et décompression avec gzip
        C: Archivage et compression avec gzip
        D: Archivage et compression avec bzip2

    106) Comment visualiser le shell utilisé
        A: Dans le fichier ~/.shells de l'utilisateur
        B: Dans le fichier /etc/shell
        C: Dans le fichier /etc/group
        D: Dans la variable d'environnement SHELL

    107) Dans un script shell, comment se nomme la premiere ligne commençant par '#!' ?
        A: Le shebang
        B: Le hashtag
        C: Le tag
        D: Le Label

    108) Comment transformer un script shell en une commande linux ?
        A: Copier le script dans le répertoire /etc/bin
        B: Ajouter une option de manuel -h au script
        C: Rendre le script exécutable
        D: Rajouter le dossier du script dans la variable PATH
  
  
    109) Quelle commande permet de visualiser les variables d'environnement ?
        A: echo $ENV
        B: who
        C: date
        D: env
    
    110) Qu'est ce qu'un alias en shell ?
        A: Un raccourci sur une variable d'environnement
        B: Un script shell développé avec le shell 'alias'
        C: Un binaire exécutable
        D: Un raccourci sur une commande

    111) Quelle est l'utilité des fichiers d'environnement ?
        A: Stocker les crédentials du user
        B: Stocker les variables d'env uniquement
        C: Stocker les chemin vers les scripts shell
        D: Stocker permanemment le paramétrage de l'env du user


    112) Parlant de caractères de protection, que signifie les back quotes : AltGr + touche 7 (``) ?
        A: Aucune variable ne se trouve dans les back quotes
        B: Interprète les caractère spéciaux
        C: N'interprète pas les caractères spéciaux
        D: Exécute se qui se trouve à l'intérieur des back quotes

    113) Que représente les variables suivantes  ? : $1, $2, $4 ...$9, $*, $#, $?, $$
        A: Variables prédéfinies automatiquement au run d'un script
        B: Variables prédéfinies de l'utilisateur courant
        C: Variables permettant de séquencer les job d'un script
        D: Variable interne du Kernel, servant à l'ordonnancement

    114) Que fait la déclaration suivante : Continents=('Afrique' 'Asie' 'Europe' 'Amérique' 'Oceanie')
        A: Creation d'un variable d'environnement nommée Continents
        B: Creation de 5 variable simples nommées Afrique, Asie etc...
        C: Creation d'un hash d'un élément, dont la clé est Continents
        D: Creation d'un tableau de 5 éléments

    115) Que signifie l'opérateur booléeen '&&' ?
        A: La négation, test si le contraire est OK
        B: Intersection, OK si les tests de part et d'autre sont OK
        C: L'union, Ok si l'une des expressions est OK 
        D: La OU exclusif

    116) Que signifie le caractère & en shell ?
        A: Il permets d'afficher le contenu d'une variable
        B: Il affiche le code retour de la derniere commande
        C: Il permet de mettre une commande en premier plan
        D: Il permet de lancer une commande en arrière plan

    117) Quelle différence entre les opérateurs de test '=' et '==' pour les chaînes de caractère
        A: L'un pour tester les voyelles, l'autre les consonnes
        B: L'un pour tester les majuscule, l'autre les minuscules
        C: Aucune, ils sont pareils
        D: L'un permet de tester les mots clés du shell uniquement

    118) Quand est ce qu'une boucle while s'arrête ?
        A: Lorsque le test s'incrémente
        B: Lorsqu'il n'existe aucune condition de sortie
        C: Lorsque la condition de test devient vrai
        D: Lorsque la condition de test devient fausse

    119) Quand est ce qu'une boucle until s'arrête ?
        A: Lorsque le test s'incrémente
        B: Lorsqu'il n'existe aucune condition de sortie
        C: Lorsque la condition de test devient vrai
        D: Lorsque la condition de test devient fausse


    120) Dans un script, où déclarer des fonctions ?
        A: Toujours apres le shebang, c'est obligatoire
        B: En début de script, ou avant leur utilisation
        C: Peu importe l'endroit
        D: Peu importe, pourvu qu'on utilise avant de déclarer

    121) Que signifie regexp ?
        A: Reference Google Expression
        B: Regular Expression, c'est une abbréviation anglaise
        C: Reference Google Experience
        D: Return Google Experience

    122) Que fait la commande suivante ? sed 3,5d fichier
        A: Supprimer les lignes 3 à 5 dans 'fichier' 
        B: Supprimer les lignes 3 et 5 dans 'fichier' 
        C: Ajouter des lignes en position 3 et 5 dans 'fichier' 
        D: Supprimer les lignes contenant 3 ou 5 dans 'fichier' 

    123) Quel est le résultat de la commande suivante ? echo un deux trois | awk 'print $0}'
        A: un,deux,trois
        B: un deux trois
        C: un
        D: un:deux:trois

    124) Quel est le résultat de la commande suivante ? echo un deux trois | awk 'print $1,$2,$3}'
        A: un,deux,trois
        B: un deux trois
        C: un
        D: un:deux:trois

### Exercice 2 : Les droits sur les fichiers.
Pour cet exercice, renseignez juste les commandes adéquates pour chaque question.

1) Dans le répertoire ```/tmp``` créer les fichiers et les répertoires suivants:
    - ```priv-dir/priv-file```
    - ```pub-dir/pub-file```

2) En utilisant la commande ```ls -l``` afficher les permissions des fichiers créés

    a) Quelles sont les permissions du propriétaire sur ces fichiers ?
    b) Qelles sont celles du groupe propriétaire ?
    c) Que peuvent faire les autres utilisateurs sur ces fichiers ?

3) En utilisant la notation octale de chmod, interdire tout accès des autres utilisateurs au répertoire ```priv-dir```

4) En utilisant la notation décimale de ```chmod```, rendre le répertoire ```pub-dir``` totalement accessible à tout le monde

5) Supprimer toute permission que possède le groupe et les autres utilisateurs sur le fichier ```priv-file```

6) Rendre le fichier ```pub-file``` accessible en lecture et en écriture pour tous les utilisateurs

7) Dans le répertoire ```~```, créer un fichier ```test.sh``` contenant la ligne suivante : ```echo "Silence, nous sommes en examen LINUX"``` 

8) Exécuter le fichier ```test.sh``` avec ```./test.sh```, pourquoi l’exécution a échouée ?

9) Rendre le fichier ```test.sh``` exécutable pour l'utilisateur propriétaire et essayer de l’exécuter de nouveau

10) En utilisant la notation octale changer les permissions du fichier ```test.sh``` pour permettre à tout le monde d’exécuter le fichier ```test.sh```
