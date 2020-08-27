# MSI Nattcup Web
Detta är ett experiment med att testa ut att använda Python för att skapa en 
webapplikation.

Målet är att få till en administrativ sida hostad i målnet i AWS eller Google

## Funktioner som man skulle vilja ha
Välkomst sida med information

### Användare information
inloggning av löpare / användare  
Sida för att hantera en löpares information
* Namn
* Ålder
* Bild?  

Sparande av information om använare i databasen  
Användarsida för att visa och administrera 

### Skapa en tävling
Behöver kunna skapa ett arrangemang
* Datum för arrangemanget
* Vem är arrangör
* Vilka löpare är med
  * Väljs från användare
* Ban information / Användare
  * Längd - behövs för km tider
  * Antal kontroller - skulle vara intressant för uppföljning.
  * Tid - När personen går i mål detta kommer under tävling.
  
### Anmälnings funktion med kommentarer
här kan man väll fundera på om det är något att satsa på lite häftigt är det bara det 
inte blir fel. Kanske att man behöver få till att man skickar ut mail med sammanställning
och på minnelse.
* Inbjudnings text behöver läggas med till Tävling.
* Anmälnings status behöver vara med.

### Placeringspoäng sammanställning  
Skapa information kring vilken poäng som det ska vara för varje tävling
hur ska man lägga upp detta på ett bra sätt.
* Total summa behöver man få ut
* Tabell med poängsammanställning
* Graf med poängsammanställning 

## Tekniker och hostning som behövs
detta avsnitt hanterar inläsninga och tester av de olika saker som man skulle bheöva på på '
plats för att detta ska fungear fullt ut.

### Ladda upp projektet på GitHub [Klart]
Detta är nu fixat och denna fil skapas fom information.

### Skapa en miljö på AWS eller Google för test [  ]
kolla var man ska skapa detta och vad som behövs för att man ska kunna få det att snurra.
Här kräver det nol lite jobb
* Fixa inladdning av uppsättning från GitHub
* Hur gör man med Databaser och så vidare. 

