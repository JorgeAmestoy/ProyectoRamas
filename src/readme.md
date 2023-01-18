1 Creo repositorio en GitHub

2En Intellij creo nuevo proyecto llamado “RamasProject”.

3 En la barra de herramientas, en VCS, marco en crear nuevo repositorio

4 En la Main edito el código y guardo el cambio en commit A.

5 Vuelvo a hacer otro cambio que quede reflejado en un nuevo commit (B)

6 Con el comando ”Git Branch nombreNuevaRama (exp)” creo una nueva rama

7 Tras hacerlo, en dicha rama creo una nueva clase en la que editaré el código y haré otro commit ( C )

8 Con “Git Checkout Main”, me vuelvo a la rama Main, en la cual realizaré un nuevo commit (E)

9 Tras esto, vuelvo a usar el Git Checkout, pero en este caso a la rama exp, y edito otra vez, reflejándolo en el commit E

10 Vuelvo a la clase Main usando dicho comando y en la barra de herramientas, concretamente en Git, voy a merge seleccionando la rama con la que quiero hacer el merge (exp). Finalmente, se crea un nuevo commit de manera automática que sería el F, usando la opción -m.
Agrego el readme con la explicación de la tarea y realizo el último commit(readme)

11 Por último, en git push voy a la opción “define remote” en la que escribo la ruta del repositorio, y después git push.
