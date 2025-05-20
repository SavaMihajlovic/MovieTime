# MovieTime

MovieTime je web aplikacija rađena u c# .netu i reactjsu kao bazu koristi neo4j iz dockera.
Aplikacija nudi:

- Prijava i odjava.
- Pregled filmova i serija.
- Ocenjivanje filmova i serija kao i dodavanje omiljenih istih.
- Filtriranje filmova i serija po različitim kriterijumima (klikom na ikonicu pored "MovieTime").
- Srž aplikacije se nalazi u sistemu za predlaganje filmova u zavisnosti od korisnikove liste omiljenih.

# Uputstvo za pokretanje

- Potrebno je pokretanje docker kontejnera koji sadrži neo4j bazu.
- U neo4j na lokaciji http://localhost:7474/browser/ dodati plain podatke koje se nalaze u CREATE folderu ( u fajlu CTRL+A, CTRL+C i na browseru CTRL+V za kopiranje), jedino je bitno da izvršite Create_nodes komande pre Create_edges.
- Backend se pokreće tako sto otvorite terminal u backend folder u ukucate sledeću komandu : dotnet run (ili dotnet watch run ako želite pristup swaggeru)
- Frontend se pokreće tako što otvorite terminal u frontend folder u ukucate sledeće komande ovim redosledom :npm install , npm audit fix (ove dve komande samo prvog puta) i na kraju npm run dev , za pokretanje samog frontenda

# Podaci

- Kada unesete podatke (2. korak uputstva za pokretanje imaćete pristup sledećim nalozima):

admin neo4j:

gmail: m.sava017@gmail.com
password: sava12345!

user neo4j:

gmail: peraperic@gmail.com
password: pera12345!

- Naravno moćićete pored ovih naloga da napravite više naloga kroz samu aplikaciju.
