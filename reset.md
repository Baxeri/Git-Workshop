## Reset
Jos tulee katumapäälle tekemiensä muutosten osalta, voi käyttää `git reset --hard HEAD` -komentoa. Jos taas haluaa 
palauttaa yksittäisen tiedoston, sekin onnistuu; `git checkout HEAD -- tiedosto/polku/tähän`. Myös kommitoidut 
muutokset voidaan peruuttaa komennolla `git reset --soft HEAD~1`.
