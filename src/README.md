# Ramas con Squash

## Explico los pasos:

- 1- En la rama main hacemos dos commits
        
        git init
        git commit -m "A"
        git commit -m "B"
- 2- Creamos otra rama **'Colaborador'**

        git branch Colaborador
- 2.1- Creamos la nueva clase Colaborador
- 3- Cambiamos de la rama master a la rama colaborador y comprobamos que se realizó el cambio

        git checkout Colaborador
        git branch
- 4- Creamos 3 commit en al rama colaborador

    
        git commit -m 'aC'
        git commit -m 'bC'
        git commit -m 'cC'

- 5- Volvemos a la rama main y lo comprobamos

        git checkout main
        git branch
- 6- Creamos una nueva rama llamada lider, nos cambiamos a ella y comprobamos que nos hemos cambiado correctamente de rama

        git branch lider
        git checkout lider
        git branch
- 6.1- Creamos una nueva clase llamada lider
- 7- En la rama lider creamos 3 commits

        git commit -m 'aL'
        git commit -m 'bL'
        git commit -m 'cL'
- 8- Volvemos a la rama master y comprobamos que hayamos cambiado correctamente

        git checkout master
        git branch
- 9- Hacemos los merge desde la IDE y los commits

        una vez hecho el merge de la rama colaborador hacemos el commit
                git commit -m "squash colaborador"
        hacemos el merge de la rama lider y el commit
                git commit -m "squash lider"
  
        
    




