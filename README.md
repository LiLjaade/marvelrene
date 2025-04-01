*MULTIVERSE OF GITNESS*

1. Creamos el directorio marvel e iniciamos un repositorio en él.
	mkdir marvel
	cd marvel
	git init


2. Renombramos la rama master/main a marvel
	git branch -m master marvel
	git branch --show current


3. Creamos un fichero llamado filmografia.txt
	touch filmografia.txt


4. Lo añadimos al repositorio como “Índice de películas”
	git add ./
	git commit -m “Índice de películas”
	git show


5. Creamos una rama llamada capitan_america
		git branch capitan_america
		git checkout capitan_america

	a. Editamos el fichero y escribimos: “1. Captain America: The First Avenger (1942)"
		nano filmografia.txt

	b. Confirmamos los cambios “Película 1” y mezclamos con marvel
		git commit -am "Película 1"
		git checkout marvel
		git merge capitan_america


6. Creamos una rama llamada capitana_marvel
		git checkout -b capitana_marvel

	a. Editamos el fichero y escribimos: “2. Captain Marvel (1995)"
		nano filmografia.txt

	b. Confirmamos los cambios “Película 2” y mezclamos con marvel
		git commit -am "Película 2"
		git checkout marvel
		git merge capitana_marvel


7. Creamos una rama llamada ironman
		git checkout -b ironman

	a. Editamos el fichero y escribimos: “3. Iron Man (2008)"
		nano filmografia.txt

	b. Confirmamos los cambios “Película 3”
		git commit -am "Película 3"

	c. Editamos el fichero y escribimos: “4. Iron Man 2 (2011)"
		nano filmografia.txt

	d. Confirmamos los cambios “Película 4” y mezclamos con marvel
		git commit -am "Película 4"
		git checkout marvel
		git merge ironman


8. Creamos una rama llamada hulk
		git checkout -b hulk

	a. Editamos el fichero y escribimos: “5. The Incredible Hulk (2011)"
		nano filmografia.txt

	b. Confirmamos los cambios “Película 5” y mezclamos con marvel
		git commit -am "Película 5"
		git checkout marvel
		git merge hulk


9. Creamos una rama llamada thor
		git checkout -b thor

	a. Editamos el fichero y escribimos: "6. Thor (2011)"
		nano filmografia.txt

	b. Confirmamos los cambios “Película 6” y mezclamos con marvel
		git commit -am "Película 6"
		git checkout marvel
		git merge thor


10. Creamos una rama llamada vengadores
		git checkout -b vengadores

	a. Editamos el fichero y escribimos: “7. The Avengers (2012)"
		nano filmografia.txt

	b. Confirmamos los cambios “Película 7” y mezclamos con marvel
		git commit -am "Película 7"
		git checkout marvel
		git merge vengadores


11. Cambiamos a la rama ironman
		git checkout ironman

	a. Comprobamos el registro de commits y actualizamos la rama
		git show
		git merge marvel

	b. Editamos el fichero y escribimos: “8. Iron Man 3 (2012)"
		nano filmografia.txt

	c. Confirmamos los cambios “Película 8” y mezclamos con marvel
		git commit -am "Película 8"
		git checkout marvel
		git rebase ironman


12. Cambiamos la rama thor
		git checkout thor
		git rebase marvel

	a. Editamos el fichero y escribimos: “9. Thor: The Dark World (2013)"
		nano filmografia.txt

	b. Confirmamos los cambios “Película 9” y mezclamos con marvel
		git commit -am "Película 9"
		git checkout marvel
		git rebase thor


13. Cambiamos la rama capitan_america
		git checkout capitan_america
		git rebase marvel

	a. Editamos el fichero y escribimos: “10. Captain America: The Winter Soldier (2014)"
		nano filmografia.txt

	b. Confirmamos los cambios “Película 10” y mezclamos con marvel
		git commit -am "Película 10"
		git checkout marvel
		git rebase capitan_america


14. Creamos una rama llamada guardianes_galaxia
		git checkout -b guardianes_galaxia

	a. Editamos el fichero y escribimos: “11. Guardians of the Galaxy (2014)"
		nano filmografia.txt

	b. Confirmamos los cambios “Película 11”
		git commit -am "Película 11"

	c. Editamos el fichero y escribimos: “12. Guardians of the Galaxy 2 (2014)"
		nano filmografia.txt

	d. Confirmamos los cambios “Película 12” y mezclamos con marvel
		git commit -am "Película 12"
		git checkout marvel
		git rebase guardianes_galaxia


15. Cambiamos la rama vengadores
		git checkout vengadores
		git rebase marvel

	a. Editamos el fichero y escribimos: “13. Avengers: Age of Ultron (2015)"
		nano filmografia.txt

	b. Confirmamos los cambios “Película 13” y mezclamos con marvel
		git commit -am "Película 13"
		git checkout marvel
		git rebase vengadores


16. Creamos una rama llamada antman
		git checkout -b antman

	a. Editamos el fichero y escribimos: “14. Ant-Man (2015)"
		nano filmografia.txt

	b. Confirmamos los cambios “Película 14” y mezclamos con marvel
		git commit -am "Película 14"
		git checkout marvel
		git rebase antman


17. Cambiamos la rama capitan_america
		git checkout capitan_america
		git rebase marvel

	a. Editamos el fichero y escribimos: “15. Captain America: Civil War (2016)"
		nano filmografia.txt

	b. Confirmamos los cambios “Película 15” y mezclamos con marvel
		git commit -am "Película 15"
		git checkout marvel
		git rebase capitan_america


18. Creamos una rama llamada black_widow
		git checkout -b black_widow

	a. Editamos el fichero y escribimos: “16. Black Widow (2016)"
		nano filmografia.txt

	b. Confirmamos los cambios “Película 16” y mezclamos con marvel
		git commit -am "Película 16"
		git checkout marvel
		git rebase black_widow


19. Creamos una rama llamada spiderman
		git checkout -b spiderman

	a. Editamos el fichero y escribimos: “17. Spider-Man: Homecoming (2016)"
		nano filmografia.txt

	b. Confirmamos los cambios “Película 17” y mezclamos con marvel
		git commit -am "Película 17"
		git checkout marvel
		git rebase spiderman


20. Creamos una rama llamada strange
		git checkout -b strange

	a. Editamos el fichero y escribimos: “18. Doctor Strange (2016-2017)"
		nano filmografia.txt

	b. Confirmamos los cambios “Película 18” y mezclamos con marvel
		git commit -am "Película 18"
		git checkout marvel
		git rebase strange


21. Creamos una rama llamada black_panther
		git checkout -b black_panther

	a. Editamos el fichero y escribimos: “19. Black Panther (2017)"
		nano filmografia.txt

	b. Confirmamos los cambios “Película 19” y mezclamos con marvel
		git commit -am "Película 19"
		git checkout marvel
		git rebase black_panther


22. Cambiamos a la rama thor
		git checkout thor
		git rebase marvel

	a. Editamos el fichero y escribimos: “20. Thor: Ragnarok (2017)"
		nano filmografia.txt

	b. Confirmamos los cambios “Película 20” y mezclamos con marvel
		git commit -am "Película 20"
		git checkout marvel
		git rebase thor


23. Cambiamos a la rama vengadores
		git checkout vengadores
		git rebase marvel

	a. Editamos el fichero y escribimos: “21. Avengers: Infinity War (2017)"
		nano filmografia.txt

	b. Confirmamos los cambios “Película 21” y mezclamos con marvel
		git commit -am "Película 21"
		git checkout marvel
		git rebase vengadores


24. Cambiamos a la rama antman
		git checkout antman
		git rebase marvel

	a. Editamos el fichero y escribimos: “22. Ant-Man and the Wasp (2017)"
		nano filmografia.txt

	b. Confirmamos los cambios “Película 22” y mezclamos con marvel
		git commit -am "Película 22"
		git checkout marvel
		git rebase antman


25. Cambiamos a la rama vengadores
		git checkout vengadores
		git rebase marvel

	a. Editamos el fichero y escribimos: “23. Avengers: Endgame (2017-2022)"
		nano filmografia.txt

	b. Confirmamos los cambios “Película 23” y mezclamos con marvel
		git commit -am "Película 23"
		git checkout marvel
		git rebase vengadores


26. Creamos una rama llamada shangchi
		git checkout -b shangchi

	a. Editamos el fichero y escribimos: “24. Shang-Chi and the Legend of the Ten Rings (2023)"
		nano filmografia.txt

	b. Confirmamos los cambios “Película 24” y mezclamos con marvel
		git commit -am "Película 24"
		git checkout marvel
		git rebase shangchi


27. Cambiamos a la rama spiderman
		git checkout spiderman
		git rebase marvel

	a. Editamos el fichero y escribimos: “25. Spider-Man: Far From Home (2023)"
		nano filmografia.txt

	b. Confirmamos los cambios “Película 25” y mezclamos con marvel
		git commit -am "Película 25"
		git checkout marvel
		git rebase spiderman


28. Creamos una rama llamada eternals
		git checkout -b eternals

	a. Editamos el fichero y escribimos: “26. Eternals (2023)"
		nano filmografia.txt

	b. Confirmamos los cambios “Película 26” y mezclamos con marvel
		git commit -am "Película 26"
		git checkout marvel
		git rebase eternals


29. Cambiamos a la rama spiderman
		git checkout spiderman
		git rebase marvel

	a. Editamos el fichero y escribimos: “27. Spider-Man: No Way Home (2024)"
		nano filmografia.txt

	b. Confirmamos los cambios “Película 27” y mezclamos con marvel
		git commit -am "Película 27"
		git checkout marvel
		git rebase spiderman


30. Cambiamos a la rama strange
		git checkout strange
		git rebase marvel

	a. Editamos el fichero y escribimos: “28. Dr. Strange in the Multiverse of Madness (2025)"
		nano filmografia.txt

	b. Confirmamos los cambios “Película 28” y mezclamos con marvel
		git commit -am "Película 28"
		git checkout marvel
		git rebase strange


31. Cambiamos a la rama thor
		git checkout thor
		git rebase marvel

	a. Editamos el fichero y escribimos: “29. Thor: Love and Thunder (2025)"
		nano filmografia.txt

	b. Confirmamos los cambios “Película 29” y mezclamos con marvel
		git commit -am "Película 29"
		git checkout marvel
		git rebase thor


32. Cambiamos a la rama black_panther
		git checkout black_panther
		git rebase marvel

	a. Editamos el fichero y escribimos: “30. Black Panther: Wakanda Forever (2025)"
		nano filmografia.txt

	b. Confirmamos los cambios “Película 30” y mezclamos con marvel
		git commit -am "Película 30"
		git checkout marvel
		git rebase black_panther

