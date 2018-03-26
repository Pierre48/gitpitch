# Git @ SIP 
<img src="https://git-scm.com/images/logos/2color-lightbg@2x.png" alt="Drawing" style="width: 400px;" />
---
## Git what ?
> "Git is a version control system for **tracking changes** in computer files and coordinating work on those files among multiple people. As a **distributed revision control system** it is aimed at speed, data integrity, and support for distributed, non-linear workflows.
<br/>[Wikipedia](https://en.wikipedia.org/wiki/Git)

> Git was created by Linus Torvalds in 2005 for development of the Linux kernel, with other kernel developers contributing to its initial development."
<br/>[Wikipedia](https://en.wikipedia.org/wiki/Git)
---
## Git vs Svn
<img src="https://i.stack.imgur.com/6SqPf.png" alt="Drawing" style="width: 600px;" />
<br/>[stackexchange](https://softwareengineering.stackexchange.com/questions/136079/are-there-any-statistics-that-show-the-popularity-of-git-versus-svn)
---
## System atoption 
![Image](https://github.com/Pierre48/gitpitch/blob/master/images/openhub-gitstatistics.png?raw=true)<br/>
[OpenHub](https://www.openhub.net/repositories/compare)

---
## Notable users
> Linux kernel, Android, Bugzilla, DragonFly BSD, GNOME, GNU Emacs, GRUB2, KDE, MySQL, Perl 5,[82] PostgreSQL, XOrg, Cairo, Qt Development Frameworks, Samba, OpenEmbedded, Ruby, Ruby on Rails, Wine, Fluxbox, Openbox, Compiz Fusion, XCB, ELinks, XMMS2, e2fsprogs, GNU Core Utilities, DokuWiki, Drupal, LibreOffice, MediaWiki, **<u>Mono, ASPNET MVC, ADONET Entity Framework, NuGet</u>**, jQuery and many of its plugins, OpenCV, Wireshark, Django, many companies like Ericsson, Microsoft, Huawei, Apple, Amazon, LG ...
---
## Git and ALM solutions 
#### Application  Lifecycle managment :
+ GitHub
+ GitLab
+ Bitbucket
+ But also VSTS / TFS (Since TFS15) !
---
## What about SIP ??? :
+ Git not usable with ePCToolbar
+ But ... Git is ready to production with our continuous integration
---
## Why Git ? Why now ?
+ More and more collaboration subjects (Library, LibraryUI,...)
+ Git, a standard tool,

Besoin de colobarotion
 composant commun
 Outillage Merge request etc

Standard du marche
 Outil connu et maitrise par les nouveaux
 Ouverture sur d qutre plateforme (GitLab de DCSI)
---
## Cible  et Strategie
Tester sur un produit methode
Library
 - Outil utilise par tout le monde
  - besoin de modification par les equipes (Partager des Extensions, BugFix, ....)
---
## Fork et Merge request
Definition
Strategie (valider par le resp du produit)
Pas de setup sur les forks = obligation de merge pour aller en prod
---
## Gestion des branches 
Faire le parallele avec nos branches
---
## Conduite du changement
Beta Tester
  => Ludo !

Formation
https://try.github.io/levels/
http://rogerdudler.github.io/git-guide/
+ Formation VS &  TFS

---
## Tomorow
##### Check-up in 2 months
+ Success
+ Difficulties 

##### To decide if 
+ Git is not the solution --> Rollback to TFS SC
+ Git everywhere --> Git for Frelon, Neon, for other teams
---
## Markdown
Strategie  DCSI
Doc technique dans Git
Lien du wiki aui pointe sur Git
Les autres docs (dep, support...) reste dans le wiki

Avantages
Ecrire la doc plus vite
La doc et au meme endroit que le code
La doc est versonnee avec le code
Standard du marche
Portabilite de la doc
## Todo 
+ Migration TFS to Git
+ Migration Git To TFS
--- 
# LibraryUI
--- 
## Concept
- Git 
- Markdowm
- GitFlow
- Nuget pour les composants graphique
--- 
## Qui
iMat et mesure
Thanks to us

--- 
## And now
On garde pas gitflow
Methodologie
CA devient un produit methode
   - Validation des merges requests pour la partie  (A Voir demain si plus)
   
Michelin Design System ?
--- 

## Problemes
Build ?
Documentation ?
Sample ?
UT ?

--- 

## Quand
Maintenant


   
