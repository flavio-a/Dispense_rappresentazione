# Dispense per il corso "Introduzione alla Teoria della Rappresentazione" del secondo anno in Normale tenuto dai professori Angelo Vistoli e Jacopo Gandini


Queste dispense servono come supporto per lo studio del corso di Introduzione alla Teoria della rappresentazione tenuto in SNS nell'anno 2017/2018.

Queste dispense sono completamente basata su quelle scritte per l'anno 2016/2017, agli autori delle quali vanno i crediti per la maggior parte dei contenuti. Sono comunque state aggiornate e riorganizzate per rispecchiare le differenze tra i due corsi.

Consiglio di usare i pc del collegio per evitare problemi. Per scaricare il repository in generale dovete scegliere una cartella dove posizionarlo e poi digitare in console

`$ git clone INDIRIZZO`

In questo caso l'indirizzo sarà

`$ git clone https://github.com/flavio-a/Dispense_rappresentazione.git`

Non toccate le cose nella cartella .git

Cercate di scrivere agli altri via SMS/Whatsapp/Telegram/piccione viaggiatore/altro quando state scrivendo in modo da evitare che due lavorino contemporaneamente e incasinino il tutto, se dovesse succedere quando usate i comandi `git pull` o `git push` si lamenterà (probabilmente parlando di merge), nel caso chiedete aiuto a qualcuno più esperto di git

Fate le vostre modifiche al file .tex come meglio preferite

Quando avete finito ricordatevi di digitare la corretta sequenza di comandi in console

`$ git add --all`

Che dice al terminale di aggiungere alla lista tutti i file modificati

`$ git commit -m "Scrivi un messaggio in cui spieghi cosa hai fatto"`

Che conferma quello che avete fatto

`$ git push origin master`

Che vi permette di caricare online il risultato. Dovrete inserire user e password del vostro account

Quando avete finito potete cancellare la cartella locale e la volta dopo dovrete di nuovo agire con

`$ git clone https://github.com/OrsoBruno96/Dispense_rappresentazione.git`

oppure tenere la cartella e per aggiornarla prima di continuare

`$ git pull origin`

Ricordatevi di aggiornare prima di partire per evitare di perdere lavoro

Per vedere che cosa è cambiato rispetto all'ultima volta che avete lavorato sul file dovete fare un paio di cose semplici. Intanto digitate

`$ git log`

In cui compariranno tutti i commit delle modifiche precedenti. Cercate di capire qual è quello a cui siete rimasti e annotatevi le prime 4-5 cifre del brutto codice alfanumerico infinito che leggete, per esempio ab12.
Poi guardate il codice dell'ultima versione e annotate pure quel codice, per esempio cd34. Digitate quindi

`$ git diff ab12 cd34`

é importante l'ordine prima vecchio e poi nuovo. A terminale vi verranno stampate le differenze fra le due versioni.

Per l'utilizzo del pacchetto *diagrams* può essere utile il seguente manuale: http://www.paultaylor.eu/diagrams/manual.pdf
