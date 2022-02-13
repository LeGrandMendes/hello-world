#Remarques sur les questions

##Exo 1

###Q5
On constate que les variables **toto** et **lolo** ne sont pas égaux. Ce sont deux objets de type `Etudiant`
avec les mêmes valeurs, mais ce sont quand même deux objets différents.
###Q10
On constate que **lolo** a été désinscrit. **toto** est une référence à **lolo** donc désinscrire **toto**revient à désinscrire
la première occurence de lolo ou toto.
##Exo2

###Q7
`calculerMoyenne()` et `getMoyennePromo()`sont quasiment identiques avec `calculerMoyenne()`
qui a des coefficients en plus dans son algorithme. On pourrait créer une fonction `moyenne()` avec la même structure 

##Exo3

###Q2
On ne peut pas ajouter un constructeur pour indiquer le nom, le prénom et l'adresse car c'est un constructeur avec comme
arguments 3 strings et il y'a déjà un constructeur avec comme arguments 3 strings. La machine ne pourra pas différencier entre
ces 2 constructeurs s'ils existaient tout les deux.
###Q4
