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

Q5:  7 columns

Q6 Illuminate\Database\Eloquent\MassAssignmentException  Add [name] to fillable property to allow mass assignment on [App\Models\Ticket].

Q7: numero 4 car La méthode orderBy('created_at')->get() trie les tickets par date de création, du plus ancien au plus récent. Mon ticket apparaît donc en quatrième position dans la liste.