# raupjc-hw0

#Pitanje 1:

Uz .exe datoteku u Debug diretkoriju imamo i .dll datoteku.
Ako pokrenemo .exe datoteku, a maknuli smo .dll datoteku, program će se srušiti s iznimkom FileNotFoundException jer 
ne može referencirati metodu koja se je nalazila unutar .dll datoteke.
Kako bi HelloWorld program ispravno radio treba poslati .exe i .dll datoteku(moraju se nalaziti unutar istog direktorija).   

#Pitanje 2:

Konzolna aplikacija je ispisala promjenu teksta, jer se prilikom prevođenja konzolne 
aplikacije preveo i class library kojeg koristimo u konzolnoj aplikaciji.

#Pitanje 3:

Build proces se je izvršio bez greške, a NodaTime paket koji je nedostajao je ponovno dohvaćen na početku build procesa.
