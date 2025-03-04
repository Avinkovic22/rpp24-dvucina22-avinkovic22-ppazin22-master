# Carchive

## Opis domene
Aplikacija Carchive je namijenjena vođenju evidencije kod prodaje te iznajmljivanje automobila pojedine auto-kuće. Primarni cilj ove aplikacije je pružanje cjelovitog sustava za praćenje i upravljanje većim brojem vozila, optimizacija resursa te smanjenju operativnih troškova. Sustav će omogućiti potporu auto-kućama u poboljšanju njihove učinkovitosti i održavanju vozila.

## Specifikacija projekta
Aplikacija će se temeljiti na client-server arhitekturi. Aplikacija će sadržavati sučelje za interakciju s korisnikom, dok će backend(server) pružati pozadinske servise kao što su autentifikacija, upravljanje podatcima i korisnicima.

Oznaka | Naziv | Kratki opis
------ | ----- | -----------
F01 | Prijava i registracija | Sustav će omogućiti prijavu korisnika pomoću korisničkog imena i lozinke uz uvjet da podatci verificiraju i omoguće pristup aplikaciji. Registracija se koristi kao forma za slanje upita koji se mora odobriti od admina. |
F02 | Upravljanje katalogom vozila | Sustav će omogućiti korisniku unos, izmjenu, pregled i brisanje podataka o vozilima. |
F03 | Upravljanje katalogom kontakata | Sustav će omogućiti unos, izmjenu, pregled i brisanje podataka o kontaktima klijenata i partnera. |
F04 | Objavljivanje na oglasnik |Sustav će omogućiti objavu vozila na vanjske oglasnike s pripadajućim podacima o vozilu. |
F05 | Statistika | Sustav će omogućiti generiranje statističkih izvještaja o poslovanju, uključujući analize prodaje, najma i korištenja vozila. | 
F06 | Prodaja vozila | Sustav će omogućiti unos i obradu podataka potrebnih za provođenje procesa prodaje automobila. | 
F07 | Iznajmljivanje vozila | Sustav će omogućiti unos i obradu podataka potrebnih za iznajmljivanje vozila. | 
F08 | Pregled mape lokacija | Sustav će omogućiti prikaz trenutnih lokacija vozila i kontakata na interaktivnoj karti. | 
F09 | Upravljanje ponudama | Sustav će omogućiti kreiranje, prilagodbu i slanje ponuda za vozila klijentima. | 


## Tehnologije i oprema
Za implementaciju aplikacije Carchive koristit ćemo .NET kao razvojni okvir te WPF (Windows Presentation Foundation) za izradu aplikacije. Upravljački alat za projekt bit će GitHub Projects, a za verzioniranje koda koristit ćemo Git. Sav izvorni kod bit će pohranjen na GitHubu. Tehnička i projektna dokumentacija vodit će se putem GitHub Wiki. Za dizajn korisničkog sučelja koristit ćemo Figma. Sve tehnologije su javno dostupne i imaju odgovarajuće licence, a u dokumentaciji ćemo opisati postupak preuzimanja i instaliranja potrebnih alata. Za razvoj aplikacije koristiti ćemo vlastita računala.
