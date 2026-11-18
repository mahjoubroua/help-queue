Q1: .env : contient des informations sensibles et personnelles, Il ne faut donc pas le partager publiquement pour protéger la sécurité du projet.
vendor/:contient les bibliothèques et dépendances installées par Composer et Il est volumineux
=> et il sont deja excite dans .gitignore

Q2:car la route /helo n'est pas définie dans le fichier routes/web.php

Q3 :La deuxième adresse /hello/a/b ne fonctionne pas parce que la route /hello/{name} accepte un seul paramètre (name).

Q4:  Hello <marquee>Bob.!
This page was built by a Blade view.
Hello roua!
This page was built by a Blade view.
Pour la deuxième adresse /hello/<marquee>Bob, le texte « Bob » ne défile pas comme une balise HTML <marquee>. Il est affiché comme du texte normal.

Q5:  main.tickets ..................................................................  
  Columns ..................................................................... 3  

  Column ................................................................... Type  
  id integer, autoincrement ............................................. integer  
  created_at datetime, nullable ........................................ datetime  
  updated_at datetime, nullable ........................................ datetime 