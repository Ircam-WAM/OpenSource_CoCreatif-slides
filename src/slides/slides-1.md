class: ircam, center, middle

# Stratégies et cas pratiques pour la gestion collaborative des œuvres audio-visuelles versionnées

<hr>

## Projets Sidney / Antony (+ Telemeta)

### Guillaume Pellerin - POW @ IRCAM, Paris

Méridien - IRCAM - 10/12/2018



---
class: ircam
# Introduction
<hr>

## Pérennité des supports physiques ?

.pull-left[
<img src="img/Edisongoldmoulded.jpg" width="80%">

Wax cylinder

]

--
.pull-right[
<img src="img/EdisonPhonograph.jpg" width="75%">

Phonograph

]

---
class: ircam
# Introduction
<hr>

## Pérennité des supports physiques ?

.pull-left[
<img src="img/Gillett3_a2cbe.gif" width="90%">

Phonograph plan

]

--
.pull-right[
<img src="img/archeoph2.jpg" width="80%">

The Archeophone

]

---
class: ircam
# Introduction
<hr>

## Dans tous les domaines, le numérique est fragile

.pull-left[
.right[![image](img/HDMAXTOR.jpg)]
]

.pull-right[
.right[![image](img/harddiskdrive.jpg)]
]

---
class: ircam
# Introduction
<hr>

## Age numérique

- de l'**analogique** *continu* au **numérique** *discret*
- des **armoires** aux **plateformes**
- du **papier** au **Web**
- de l'archivage pérenne **statique** au stockage **dynamique**
- de la **centralisation** à la **décentralisation**

---
class: ircam

# Maintenabilité dans l'espace numérique

<hr>

## Règles d'or

- s'appuyer sur les **standards**
- logiciels, formats et frameworks **open source**
- **workflow** pour la réplication de données
- éditer, publier et **partager** !

---
class: ircam

# Patrimoine audio-visuel numérique
<hr>

## Challenges

- accès aux **données** musicales (binaires) et méta-données
- moteurs de **recherche**
- outils pour l'**analyse** computationnelle
- numérisation >> **valorisation** des données culturelles et scientifiques
- grandir et **passer l'échelle** des données tout en respectant les règles de pérennité
- trouver des outils **modulaires** adaptés

---
class: ircam
# Multimedia digital Content Management System?
<hr>

- Data vs metadata
- Binary data vs text data
- Multimedia vs monomedia
- Formats & standards
- Frameworks & librairies
- Operating systems and infrastructure
- UI and UX
- Workflow
- Architecture
- Data model

---
class: ircam, tight

# Web application architecture
<hr>

![image](img/Web-Application-Architecture.png)

---
class: ircam, center, middle

# Cas pratiques : Telemeta - Sidney / Antony

---
class: ircam
#Telemeta
<hr>

.pull-left[
<img src="img/telemeta_logo_wh.png" height="100px" />

##Collaborative content management system for musicology

http://telemeta.org

https://github.com/Parisson/Telemeta

###MIR + Musicology + Archiving = MIRchiving !

###>>> active learning

]

.pull-right[
.right[![image](img/telemeta_screenshot_en_2.png)]

https://archives.crem-cnrs.fr/
]

---
class: ircam
#Telemeta - architecure
<hr>

.center-60[
![image-wh-bg](img/TM_arch.svg)
]


---
class: ircam

# Sidney
<hr>
## Plateforme de documentation et de partage d'oeuvres musicales contemporaines

http://brahms.ircam.fr/sidney/

<iframe id="frame" src="http://brahms.ircam.fr/sidney/" scrolling="auto" frameborder="0" allowfullscreen="" width="100%" height="480px"></iframe>


---
class: ircam, tight

# Sidney
<hr>

## Modèle de données

http://brahms.ircam.fr/admin/works/version/add/

.pull-left[
## +++

- gestion des oeuvres et de leurs versions
- modèle de méta-données modulaire (Django)
- partage des ressources

]

.pull-right[
### ---

- fichiers zippés et stockés très volumineux
- tracabilité faible des données
- versionnement fin impossible
- download / upload lourds
]

---
class: ircam, tight

# Sidney
<hr>

## Evolution du modèle de données

<img src="img/Sidney2Antony.png" width="100%">

---
class: ircam

# Antony
<hr>

## Hypothèses

- une oeuvre numérique est un programme informatique à part entière
- une oeuvre doit pouvoir être partagée dans son intégralité (selon les droits d'auteurs)
- une oeuvre peut être co-créée

## Solutions

- respecter la continuité entre les versions de l'oeuvre
- déléguer la gestion des fichiers à un sous-systèmes dédié
- associer des licence à chacune des parties de l'oeuvre

---
class: ircam

# Antony - Versionnement
<hr>

.pull-left[
## Git

- https://git-scm.com/
- https://github.com/
- https://about.gitlab.com/
]

.pull-right[
<img src="https://blog.lesieur.name/media/images/upload/GitFlowworkflow_thumb2.png" width="80%">
]

(source: blog.lesieur.name)

---
class: ircam

# Antony - Versionnement
<hr>

<img src="http://appendto.com/wp-content/uploads/2015/06/Screen-Shot-2015-06-24-at-8.37.13-PM-1024x663.png" width="70%"> (source: appento.com)


---
class: ircam

# Antony - Déploiement
<hr>

.pull-left[
- SI + Huma-Num
- Linux, Docker, Django
- Git, GitLab, Git-LFS
]

.pull-right[
<img src="https://git-lfs.github.com/images/graphic.gif" width="80%">
]
---
class: ircam, tight

# Conclusion
<hr>

## Git

- peut résoudre le problème de discontinuité entre versions d'oeuvres
- ouvre de nouvelles perspectives de modes de création partagées distantes et locales
- facilite la diffusion, la traçabilité et le partage des ressources

## Antony

- Ouverture du système d'archivage aux communautés (open sourcing)
- Connexe avec les méthodologies de la nouvelle plateforme Forum
- Plateforme ou instances autonomes ?
- Interfaces natives à choisir et/ou définir
- Workflow
- Documentation (!)
- Licences (!!)

---
class: ircam, center, middle

# Merci !
<hr>

##Guillaume Pellerin + POW + Groupe de travail AFIM

###guillaume.pellerin@ircam.fr / @yomguy
