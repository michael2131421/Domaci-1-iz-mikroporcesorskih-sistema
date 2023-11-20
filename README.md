Milan Nedić 608/2021
-	Pre svega, pošto imam vise suglasnika nego samoglasnika u imenu, izabrao sam port B, a pošto je moduo deljenje broja slova mog imena 4, izabrao sam 4. pin. Dakle, radim na PB4.
-	Sledeci korak je odrediti dužinu impulsa i pauze kao i taktova. Pošto mi ime ima 5 slova, dužina impulsa je 5 milisekundi i pošto mi prezime takođe ima 5 slova dužina pauze je 5 milisekundi. Ovaj prvi takt se ponavalj 5 puta. Zbog karakteristika mog imena, drugi takt ima apsolutno ista trajanja podtaktova i isti broj ponavljanja kao i prvi takt. 
-	Za realizaciju proteus dela domaćeg sam korisito STM32F103C6 komponentu i zelenu diodu. 
-	Za STM deo sam korisitio dve for petlje kako bih realizovao taktove. Komentari prisutni u kodu su tu jer sam proverao da li projekat radi ako zamenim for petlje odgovarajućim while petljama. Radi.
