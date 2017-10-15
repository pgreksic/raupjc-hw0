# raupjc-hw0

#Pitanje 1:

Uz .exe datoteku u Debug diretkoriju imamo i .dll datoteku.
Ako pokrenemo .exe datoteku, a izbrisali smo .dll datoteku program će se skršiti s iznimkom FileNotFounException jer
program ne može referencirati metodu koja se je nalazila unutar .dll izbrisane datoteke.
Kako bi HelloWorld program ispravno radio trebalo bi poslati .exe i .dll datoteku(moraju se nalaziti unutar istog direktorija).   

#Pitanje 2:

Konzolna aplikacija je ispisala promjenu teksta, jer se prilikom prevođenja konzolne 
aplikacije preveo i class library kojeg koristimo u konzolnoj aplikaciji.

#Pitanje 3:

Build proces se je izvršio, a NodaTime paket koji je nedostajao se dohvatio na početku build procesa
