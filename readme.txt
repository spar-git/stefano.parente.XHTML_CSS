Nella speranza di aver fatto cosa gradita, ho pensato di personalizzare il contenuto della pagina web con un argomento di 
mio interesse, attenendomi comunque alle conoscenze apprese a lezione e durante le esercitazioni di laboratorio.

La pagina web "Pagina iniziale.html" si compone di alcuni files: 
- un documento per le regole di stile;
- alcune immagini. 
In sostanza ho deciso di implementare le regole di stile in un file CSS esterno (external stylesheet), chiamato 
mieistili.css, al quale il documento HTML farà riferimento attraverso l'elemento <link>.

Al titolo principale della pagina web (h1) ho applicato un selettore di classe "toptitle" associando delle regole di stile 
tra cui la bordatura con angoli arrotondati (border-radius) e un colore del testo differente dal resto del body.

La barra di navigazione orizzontale funge da menù ed ha un colore di background nero; al passaggio del mouse (li a:hover), 
l'area dei collegamenti ipertestuali assume un colore più chiaro evidenziando la scelta dell'utente. Essa è 
fondamentalmente una lista di link, quindi ho trovato sensato utilizzare gli elementi <ul> e <li> per implementre questa
funzionalità. 

La prima parte testuale è prettamente descrittiva ed è contenuta nell'elemento block-level <div> a cui avrei potuto 
associare delle regole di stile ma, per una questione di gusto, ho preferito mantenere una formattazione coerente al resto 
della pagina. E' anche presente un elemento link come supporto all'utente per la comprensione del contenuto.

L'elemento <table> implementa una tabella alla quale ho scelto di personalizzare l'intestazione con il selettore di classe 
"toptable". 
Tutto il contenuto della tabella è stato formattato in modo da lasciare dello spazio dai bordi  delle 
singole celle (padding).
L'ultima colonna della tabella contiene le miniature delle immagini, corrispondenti ai rispettivi itinerari, le quali 
sono contornate da una bordatura arrotondata agli angoli. Le dimensioni e le bordature delle miniature sono state anch'esse 
definite nel file CSS con il selettore "img". Le miniature possono essere visualizzate in dimensioni originali facendo 
click su di esse. Infatti nel file HTML i tag <img> sono annidati nei tag <a> che permettono di puntare ai file JPG 
presenti nella cartella "file".

L'ultima area prevede un'ulteriore parte descrittiva e contiene un link come supporto all'utente per una maggiore 
comprensione del contenuto.