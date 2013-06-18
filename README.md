SImRuby: Jour 1
===============

Ce repository contient les specs de la premiere journee de la semaine
immersive Ruby.

Programme de la journee
-----------------------

Les exercices/specs d'ajourd'hui vous feront travailler sur le langage
Ruby lui-meme, des bases a quelques elements de meta-programmation. De
facon a etre pret pour attaquer Rails des demain a la premiere heure.

Ordre des exercices
-------------------

* basic_spec.rb
* so_class_spec.rb
* modules_spec.rb
* metaprog_spec.rb

Comment executer les specs ?
----------------------------

    host $ cd /path/to/day1
    host $ ln -s /path/to/my/exercices exos # ! Une seule fois !
    host $ rspec # or `rspec -fd` or `rspec --help`

Vous pouvez aussi executer seulement un seul fichier de spec

    host $ rspec spec/basic_spec.rb

Ou encore seulement un seul example, en specifiant le fichier puis la
ligne de l'exemple

    host $ rspec spec/basic_spec.rb:77

