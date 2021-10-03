## .gitignore
Joskus on tarpeen jättää joitakin tiedostoja pois gitistä. Silloin .gitignore astuu kuvioihin. Tiedoston voi luoda 
ihan normaalisti `touch ~/.gitignore` ja sitten ajetaan `git config --global core.excludesFile ~/.gitignore`
Saman voi tehdä myös suoraan `~/.gitconfig` -tiedostoon:

`[core]
	excludeFile = ~/.gitignore
`

Pois jätettävistä tiedostoista voi tehdä listan `~/.gitignore` -tiedostoon. Jokainen uusi rivi määrittää kaavan, jota
Git noudattaa. Esimerkiksi:
`*.txt` Kaikki .txt -tiedostot sivuutettaisiin.
`!ohje.txt` Kysymysmerkki alussa tarkoittaa sitä, että kyseinen tiedosto pidetään laskuissa mukana, tässä 
tapauksessa ohje.txt -tiedosto pysyy seurattuna (tracked).
