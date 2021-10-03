## Alias
Git alias mahdollistaa nimeämään komennoille aliaksia, käytännössä lyhentäen käytettyjä komentoja. 
Nimen saa tietysti itse päättää. Aliasta voi käyttää suoraan komentoriviltä esimerkiksi näin: 
`git config --global alias.br branch`, tässä 'branch' lyhennetään 'br'. 
Toki muokkaukset voi tehdä myös suoraan ~/.gitconfig tiedostoon [alias] kohdan alle. 
`[alias]
	br = branch
	co = checkout
	cm = commit`
Kätevä ominaisuus, joka säästää aikaa.
