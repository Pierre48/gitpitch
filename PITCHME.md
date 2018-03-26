# Git @ SIP 
<img src="https://git-scm.com/images/logos/2color-lightbg@2x.png" alt="Drawing" style="width: 400px;" />
---
## Git what ?
<span style="text-align: justify;font-size:1em; color:gray">"Git is a version control system for **tracking changes** in computer files and coordinating work on those files among multiple people. As a **distributed revision control system** it is aimed at speed, data integrity, and support for distributed, non-linear workflows.</span>

<span style="text-align: justify;font-size:1em; color:gray">Git was created by Linus Torvalds in 2005 for development of the Linux kernel, with other kernel developers contributing to its initial development."</span>
<br/>[Wikipedia](https://en.wikipedia.org/wiki/Git)
---
## Git vs Svn
<img src="https://i.stack.imgur.com/6SqPf.png" alt="Drawing" style="width: 600px;" />
<br/>[stackexchange](https://softwareengineering.stackexchange.com/questions/136079/are-there-any-statistics-that-show-the-popularity-of-git-versus-svn)
---
## System atoption 
![Image](https://github.com/Pierre48/gitpitch/blob/master/assets/images/openhub-gitstatistics.png?raw=true)<br/>
[OpenHub](https://www.openhub.net/repositories/compare)
---
## Notable users
<span style="font-size:1em; color:gray">Linux kernel, Android, Bugzilla, DragonFly BSD, GNOME, GNU Emacs, GRUB2, KDE, MySQL, Perl 5, PostgreSQL, Qt Development Frameworks, Samba, Ruby, Ruby on Rails, Wine, Compiz Fusion, XCB, ELinks, XMMS2, e2fsprogs, GNU Core Utilities, DokuWiki, Drupal, LibreOffice, **<u>Mono, ASPNET MVC, ADONET Entity Framework, NuGet</u>**, jQuery and many of its plugins, OpenCV, Wireshark, Django, many companies like Ericsson, Microsoft, Huawei, Apple, Amazon, LG ...</span>
---
## Git and ALM solutions 
#### Application  Lifecycle managment :
+ GitHub
+ GitLab
+ Bitbucket
+ But also VSTS / TFS (Since TFS15) !
---
## What about SIP 
+ Git is not usable with ePCToolbar
+ But ... Git is ready to production with our continuous integration !
---
## Why Git ? Why now ?
+ More and more collaboration subjects (Library, LibraryUI,...)
+ Git, the standard tool for source control (Well known by students, developers)
+ Already used by DCSI service (GitLab)
+ Simplest than Tfs SC
---
## What do we want to do
Test Git on method's product : Library 
+ Used by every project
+ Pending bugfix that could be directly done by team members
+ Enhencements could be shared in Library (Extentions, New features ...)
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
## Git and documentation
Documentation in Git is based on markdown language. 
</br>With Git :
+ Writing documetation is easy and fast
+ Documentation are stored with the source code
+ Documentation are versionned with the source code
+ Documentation can be easily moved to another source control

Our proposal is to use Git for development documentation. Other documentation stays in the Wiki (Same strategy than DCSI)
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


   
