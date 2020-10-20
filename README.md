# Recycle together

Realizzato da Miraxh Tereziu, Grigore Andronic e Riccardo Tibaldo


## Indice

- Executive summary _________________________________________________________________________________
- Analisi prodotti già esistenti e ideas generation ________________________________________________________
- PACT Analisys ______________________________________________________________________________________
- Risultato interviste e questionari _____________________________________________________________________
- User requirements __________________________________________________________________________________
- 1° iterazione ________________________________________________________________________________________
- Personas ___________________________________________________________________________________________
- Scenari _____________________________________________________________________________________________
- Motivazione delle principali scelte di design ___________________________________________________________
- Valutazione low fidelity _____________________________________________________________________________
- 2° iterazione _______________________________________________________________________________________
- Modifiche realizzate a seconda dei risultati della valutazione __________________________________________
- Prototipo mid fidelity ______________________________________________________________________________
- Valutazione mid fidelity ____________________________________________________________________________


**Executive summary**

Lo scopo di questo progetto è realizzare un prototipo mid-fidelity di un’applicazione avente
lo scopo di aiutare i cittadini del Comune di Trento a risolvere i problemi quotidiani di effettuare
la raccolta differenziata in modo veloce e funzionale.

Il progetto si focalizza sulla città di Trento, dove sono state effettuate tutte le interviste, i
questionari e tutti lavori riguardanti esso.

La scelta di lavorare su un’applicazione focalizzata su Trento è data dalla possibilità di ottenere
dei feedback più mirati che ci permettessero di capire al meglio le esigenze degli utenti finali.

Inizialmente noi membri del team abbiamo effettuato una fase di "brainstorming" e di
sviluppo di idee. Le idee sono state discusse e sono stati creati schizzi e si sono svolte
discussioni sull’idea in generale e sulla funzionalità proposte dai componenti.

Una volta stabilita l’idea abbiamo analizzato le soluzioni esistenti sul mercato per trarne
ispirazione sulle funzionalità e capire quali fossero i loro punti di forza e le loro debolezze.

Successivamente abbiamo realizzato un questionario semi-strutturato in base alle risposte
che si ricevono, da proporre agli abitanti del comune per aumentare le nostre conoscenze su come
avvenisse la raccolta differenziata nel comune, sulle abitudini delle persone e su eventuali
problemi legati ad essa e se o come vengono risolti, abbiamo effettuato anche delle interviste orali
per poter approfondire meglio i nostri dubbi.

Grazie ai questionari e alle interviste siamo riusciti a stilare gli user requirements e a dare specifici
pesi per ogni requisito, dall’analisi dei dati raccolti abbiamo individuato i principali
comportamenti degli utenti e siamo riusciti a identificare e creare quattro personas.

Sulla base dei dati raccolti abbiamo realizzato un prototipo low-fidelity sia cartaceo che
digitale per aiutarci con la valutazione da parte degli utenti.

Dalla valutazione del prototipo low fidelity sono emerse delle problematiche relative
all’applicazione ed a come fosse strutturata che ci hanno spinto a modificare dei pesi attribuiti a
determinati requisiti e ad aggiungere dei nuovi requisiti, è stato poi modificato il prototipo per
migliorare l'efficienza e la funzionalità complessiva. Buona parte dei componenti sono stati
modificati per implementare le esigenze emerse.

A seguito di tutte le modifiche apportate al low fidelity siamo riusciti a prototipare un mid
fidelity che prende ispirazione dal Material design, ma dove i classici colori pieni e tendenti al
pastello del Material design sono stati sostituiti da dei gradient per rendere il design
dell’applicazione più fresco e moderno e ogni colore gioca un ruolo importante nella percezione
dell’utente.

Il prototipo mid fidelity come quello low è stato testato da 5 persone, in generale i test
condotti in termini di funzionalità e velocità d’utilizzo hanno avuto esito positivo anche se sono

state comunque riscontrate delle problematiche nell’utilizzo del prototipo.

**Analisi prodotti già esistenti e ideas generation**

La raccolta differenziata è strettamente dipendente dagli impianti di raccolta presenti sul
territorio. Questi impianti sono in genere gestiti da privati e trattano rifiuti in base ai codici CER,
di conseguenza il comune adegua la sua raccolta differenziata all’impianto di destinazione. E’ per
questo che la differenziata cambia da comune a comune.


Anche se i nostri competitor sono principalmente quelli sul territorio della provincia di
Trento per avere più ispirazione siamo andati a cercare le varie soluzioni nei comuni italiani, qui
di seguito elenchiamo le più interessanti.

L’applicazione **“100% Riciclo”** che risulta essere l’unica presente sul territorio della
provincia di Trento e quindi nostro reale competitor, offre come punti di forza la possibilità di
trovare di cercare il prodotto da riciclare tramite barra di ricerca o tramite macro categorie,
tuttavia la ricerca testuale alcune volte presenta difficoltà di ricerca data dai vari modi comuni chi
chiamare determinati prodotti e l’uso delle categorie risulta essere lento, non esiste possibilità di
attivare notifiche che avvisare l’utente dei vari giorni di raccolta , pone le funzionalità al primo
posto a discapito della velocità di utilizzo.

**“Il rifiutologo”** è una soluzione che offre oltre la funzionalità di individuare il prodotto
tramite barcode quella di poter prenotare tramite app il ritiro a casa di oggetti ingombranti, e una
sezione mini-games per insegnare ai bambini a riciclare.

**“PULIamo”** permette agli utenti di avere un calendario con le notifiche per i vari giorni di
raccolta differenziata, consente di cercare un prodotto tramite ricerca testuale o tramite categorie
e permette di segnalare tramite foto eventuali problemi di rifiuti in città.

Un’altra soluzione interessante è presentata da **“Riciclario”,** che permette di scambiare
oggetti nella sua “bacheca del riuso” tra gli utenti , fornisce inoltre anche la funzionalità di ricerca
testuale e scansione dei barcode ma che in buona parte dei casi non riconosce il prodotto
scansionato.

Tra le soluzioni esistenti spicca **“Junker”** che si presenta come il nostro principale competitor
in termini di funzionalità. Un’applicazione che cerca di non basarsi su un solo comune, cerca di
individuare i materiali di cui e composto un prodotto grazie alla scansione del barcode , soluzione
che risulta molto più immediata rispetto ad una ricerca testuale.

Un’altra funzionalità importante è data dalla possibilità di ricerca dei simboli di riciclaggio
molto utili in casi in cui non sia possibile il riconoscimento dei barcode o del tipo di materiale del
prodotto.

Abbiamo raccolto il materiale in un'unica libreria su cui abbiamo poi lavorato analizzando
quelle che per noi erano le soluzioni principali e quelle più innovative abbiamo cercato di
estrapolare quelle che secondo noi fossero le funzioni più adatte al nostro problema chiedendoci
cosa realmente serva ad un nostro utente ideale, abbiamo poi raccolto le funzionalità più adatte
in un design space su cui abbiamo lavorato per capire le vere funzionalità che volevamo
implementare.

Partendo dall’idea di sviluppare un’applicazione che aiutasse la gente quotidianamente nella
raccolta differenziata e dopo aver analizzato il materiale raccolto sulle soluzioni esistenti siamo
arrivati alla conclusione che i due campi principali su cui confrontarci con i nostri principali
competitor fossero **“velocità di utilizzo”** e **“funzionalità”** , abbiamo quindi cercato di porre la
nostra idea verso la velocità di utilizzo (ricerca tramite barcode, testuale) e le
funzionalità(calendario raccolta, tipologia di raccolta, prodotti per categorie).

Di seguito riportiamo la nostra idea rapportata alle altre soluzioni attraverso degli assi
ortogonali:


**PACT Analisys**

**Persone**
Tramite l’utilizzo delle interviste e soprattutto dei questionari, che ci hanno permesso grazie
al loro maggior numero di risposte di ottenere dei dati più precisi, abbiamo creato le personas.
Queste sono i nostri utenti primari che useranno l’applicazione quotidianamente o comunque in
modo più frequente rispetto agli altri utenti.
Queste sono state create dividendo la popolazione per i maggiori tipo di comportamento
riscontrato negli intervistati nel caso di dubbi nel momento del riciclo. Quindi sono state create 4
personas una per ogni comportamento (ricerca online, richiesta ad altre persone, gettare
nell’indifferenziata, ricerca su materiale fornito dall’azienda appaltata) e poi si è cercato di trovare
le caratteristiche più comuni per ogni categoria riconosciuta.
Abbiamo poi riconosciuto come utenti secondari le aziende di gestione dei rifiuti che
dovrebbero impegnarsi a fornire un catalogo completo e chiaro di come gestire la raccolta
differenziata che poi verrà inserito nell’app.

**Attività**
Come abbiamo visto nelle sezioni delle persone attualmente il processo di differenziazione
viene eseguito dalle persone mnemonicamente e nel caso insorgano dubbi o incertezze le persone
ricadono in quattro principali comportamenti.
Questo risultano inefficaci in vari modi come ad esempio consumare troppo tempo o
addirittura produrre risultati sbagliati. Prendiamo per esempio la ricerca online, il risultato che
una persona può trovare online può essere vero per un’azienda dei rifiuti ma essere sbagliato per
un’altra e quindi portare l’utente a gettare il rifiuto nel contenitore sbagliato. Determinando la
posizione dell’utente, ad esempio tramite il GPS, possiamo capire dove si trovi l’utente e
determinare quale sia l’azienda appaltata e risalire alle sue politiche evitando l’errore.

**Contesto**
Le attività vengono svolte in un contesto principalmente casalingo ma non viene escluso
l’utilizzo in aree pubbliche o commerciali con un utilizzo previsto principalmente individuale.

**Tecnologie**
Il prodotto è pensato come applicativo per dispositivi mobile Android e iOS con accesso a
internet per poter mantenere aggiornate le informazioni e accesso alla localizzazione (facoltativo)


per poter determinare di quale azienda applicare le politiche sul riciclaggio. Inoltre, puntiamo ad
implementare, tramite l’accesso alla fotocamera del dispositivo, la possibilità di cercare i prodotti
tramite il codice a barre per ottimizzare i tempi di ricerca per gli utenti.

**Risultato interviste e questionari**

Inizialmente abbiamo proceduto tramite la diffusione all’interno dell’università di un
questionario che ci ha permesso di risolvere dei dubbi e ricavare delle informazioni che ci
mancavano, successivamente vedendo che il tasso demografico dei questionari comprendeva
persone dai 18 ai 25 anni perciò per ricevere dei valori più affidabili e raggiungere persone al di
fuori del tasso demografico che già avevamo abbiamo deciso di cercare di raggiungere un pubblico
più adulto.

Per fare ciò ci siamo rivolta a contesti più famigliari dove sapevamo di poter raggiungere il
pubblico che stavamo cercando e di appendere dei volantini nelle prossimità di bidoni con su
stampato un qr-code che rimandava direttamente al nostro questionario. Dopo aver raggiunto un
buon numero di questionari compilati (163) abbiamo deciso di iniziare a valutare i dati che
avevamo raccolto.

**_Link questionario_**
_https://docs.google.com/forms/d/1XfFrvaDHBIaDouSVNnm9IldMvE24fIngWZwiYxIZacM/edit?us
p=sharing_

Le informazioni più importanti che siamo riusciti ad estrapolare dai questionari sono:

- Abbiamo una suddivisione a circa il 50% tra persone che fanno la raccolta tramite
    cassonetti oppure tramite porta a porta
- In caso di un prodotto sconosciuto che non si sa dove buttare sono l’8% utilizza una app,
    anche tra un pubblico giovane
- Un 30% percento delle persone con raccolta porta a porta afferma di dimenticarsi di
    appuntamenti di raccolta
- Il 67% degli intervistati afferma che sarebbe interessata ad un’applicazione per l’aiuto a
    riciclo

Dalle interviste invece abbiamo confermato quello che abbiamo appreso in precedenza dai
questionari, andando a riproporre domande simili, però cercando di esplorare più nel dettaglio
qualora ce ne fosse l’opportunità. Permettendoci così di andare più nello specifico riguardo certe
problematiche, operazione che risulta difficile se si lavora soltanto tramite questionari senza


andare a rompere vincoli importati di essi. Domande riguardo questioni che magari ci fossero
sfuggite tipo eventuali problematiche dei vari metodi di raccolta, ad esempio da un’intervista è
emerso che se si sbaglia giorno di raccolta ripetutamente si rischia di ricevere una sanzione,
motivandoci così a sviluppare la sezione di controllo dei vari giorni di raccolta in maniera più
attenta.

Le interviste sono state 5 per membro del gruppo per un totale di 15 e ci hanno permesso di
rafforzare le nostre conoscenze acquisite tramite l’utilizzo dei questionari.

**_Link interviste_**
_https://drive.google.com/drive/folders/1QODCMlaNXw5FTu2APbfJb9MiS6MqJah2?usp=sharing_

**User requirements**

Successivamente alle interviste e i questionari abbiamo analizzato tutti i dati a nostra
disposizione ed abbiamo definito alcuni requisiti fondamentali, dei quali abbiamo riportato di
seguito quelli più importanti suddivisi in funzionali e non funzionali.

**_Link user requirements_**

_https://docs.google.com/spreadsheets/d/14dsMhyDnTUq0LqyI7mrE-
K9MetdfNvWV8__wDg2BNj4/edit?usp=sharing_

**Requisiti funzionali:**

- L'applicazione deve permettere di individuare un "prodotto" tramite fotocamera del dispositivo
- L'applicazione deve mostrare un calendario con i giorni in cui avviene la raccolta differenziata
- L'applicazione deve permettere di cercare un "prodotto" per nome
- L'applicazione deve notificare i giorni di raccolta (tipi raccolti)

**Requisiti non funzionali:**

- l'interfaccia dell'applicazione deve essere facile da usare per utenti di qualsiasi età
- l'applicazione deve essere il più veloce possibile
- l'interfaccia dell'applicazione deve essere chiara e coerente

**1° iterazione**

**Personas**

Per quanto riguarda Personas ne abbiamo identificate 4 principali, tutte con caratteristiche
in comune ma con principalmente una voglia generale di migliorare il proprio metodo di riciclo.
Di seguito ne abbiamo riportata una mentre le altre tre possono essere trovate nella cartella drive

**_Link personas_**

_https://drive.google.com/drive/folders/1Zmr4QfEsRpNbfTmmCa6W2tBvFp45GXgo?usp=sharing_


**Scenari**

Fondamentalmente nella nostra applicazione abbiamo due scenari primari

**Primo scenario ricerca prodotto**


Lo scenario consiste nell'utilizzo dell'applicazione in caso di necessita. In caso di mancata
conoscenza dei un appropriato riciclo di un determinato prodotto, l'utente andrà ad aprire
l'applicazione e in base a vari metodi di identificazione del prodotto, che possono essere:

-^ Ricerca tramite codice a barre
-^ Ricerca tramite ricerca testuale
-^ Ricerca tramite categorie
Nello scenario viene descritta una ricerca tramite codice a barre. Successivamente dopo che il
prodotto viene identificato, verrà comunicato all'utente dove va buttato il prodotto

**Secondo scenario avviso ritiro**

In questo scenario viene descritta la funzionalità che permette agli utenti che effettuano la
raccolta porta a porta, la possibilità di poter assegnare una notifica in base ai propri orari di
raccolta, orari che ovviamente verranno presi in automatico. L'utente nel determinato giorno di
raccolta riceverà per tempo una notifica che gli comunicherà che in giornata è previsto un ritiro.
Di conseguenza l'utente provvederà portare nelle apposite zone di raccolta il materiale che verrà
raccolto nel preciso giorno. Inoltre, nell'applicazione sarà possibile visualizzare orari futuri di
raccolta per una adeguata preparazione dei rifiuti.

**Motivazione delle principali scelte di design**

Il principale scopo dell’applicazione è permettere all’utente di identificare come riciclare un
particolare prodotto di cui sta avendo difficolta nella identificazione dell’apposito bidone di
raccolta.

Innanzitutto, all’utente verrà chiesti la propria posizione, tramite cap oppure gps, e la tipologia di
raccolta, cassonetti oppure porta a porta.

Successivamente per l’identificazione del particolare prodotto sono state fornite alcune
possibilità:

1. **Scansione codice a barre per identificazione del prodotto:**

```
o Tramite l’utilizzo della camera è possibile scannerizzare il codice a barre di un
prodotto e tramite l’interrogazione di un apposito database identificare come riciclare
il specifico prodotto
```
2. **Tramite ricerca testuale:**

```
o Nel caso il prodotto non abbia un codice a barre è possibile cercarlo tramite un classico
metodo di ricerca testuale
```
3. **Tramite categoria:**

```
o Se non si sa il nome del prodotto ed esso non ha nemmeno un codice a barre è possibile
consultare una lista di categorie per cercare di capire in quale di esse il nostro prodotto
risiede e ricevere informazioni riguardo al suo riciclo
```

4. **Visualizzazione di prodotto ricercati recentemente:**

```
o Possibilità di avere una lista dei prodotti ricercati recentemente da noi, oppure dalla
community locale
```
Essendo queste modalità di ricerca le funzionalità principali della nostra applicazione
abbiamo ritenuto che fosse necessaria la possibilità di accedere ad essere in qualsiasi momento
tramite solo un click.

Inoltre, per utenti con metodologia di raccolta tramite porta a porta è possibile accedere ad
un calendario o agenda con tutti gli appuntamenti futuri di raccolta, per prevenire una
dimenticanza di un ritiro è possibile abilitare un sistema di notifiche. Oppure nel caso di utenti
con tipologia di raccolta tramite cassonetti è possibile visualizzare una mappa con i vari punti di
raccolta. Anche queste funzionalità essendo molto importanti saranno sempre raggiungili tramite
un solo click.

Infine, l’ultimo elemento consiste nelle impostazioni che permettono di gestire il tipo di
raccolta o la posizione di residenza. Queste impostazioni sono invece annidate e necessitano di
due click per raggiungerle per evitare click accidentale essendo che il cambio di residenza oppure
tipologia di raccolta non sia un’operazione molto frequente.

Del prototipo low fedelity è stata realizzata una versione disegnata a mano (si può trovare
all’interno della cartella drive) ed una versione digitale riportata di seguito

**Link low fidelity disegnato + versione digitale**

_https://drive.google.com/drive/folders/1XLLEXEgEMlMxI6W4aElLd9Ix-MhVikyr?usp=sharing_

**Valutazione low fidelity**

Il prototipo è stato testato da 5 persone tramite l’utilizzo della funzionalità di Axure che
permette di interagire con un prototipo tramite un link. Ai tester è stato chiesto di testare alcune
funzionalità del tipo:

- Scansione prodotto tramite lettura codice a barre
- Visualizzazione info prodotto recente
- Visualizzare prossimo ritiro
- Cambiare tipologia raccolta


- Visualizzare mappa

Da questi test è emerso:

- La UI è molto semplice e facile da navigare
- Mancanza di una pagina iniziale di intro per spiegare l’idea generale dell’applicazione
- I prodotti recenti non sono facilmente localizzati
- Le informazioni dei prodotti recenti non sono chiare e forniscono pochi dettagli
- Cambiare la tipologia di raccolta risulta ostico
- Alcuni utenti preferiscono avere il calendario al posto dell’agenda come metodo default

**_Link video valutazioni low fidelity_**

_https://drive.google.com/drive/folders/1wbSTJf3-qfodAXEGf_S5_7nOfEZCfIwI?usp=sharing_

**2° iterazione**

**Modifiche realizzate a seconda dei risultati della valutazione**

Successivamente alla valutazione del prototipo low fidelity sono emerse delle problematiche
relative all’applicazione ed a come fosse strutturata quindi abbiamo pensato di implementare le
seguenti modifiche per andare a risolvere le problematiche riscontrate. Le modifiche apportate
sono:

- Aggiunta di una pagina inziale di intro
- Aggiungere una didascalia ai prodotti recenti
- Cambiare la tipologia di card relativa ai prodotti recenti e renderla verticale e non
    orizzontale e non verticale così da permettere la possibilità di aggiungere più informazioni
    in maniera più chiara e visibile
- Alla selezione della tipologia di raccolta fornisce una breve descrizione riguardo la
    possibilità di modificare la tipologia di raccolta in futuro all’interno delle impostazioni
- Impostare il calendario come forma di organizzazione dei ritiri principale per una migliore
    visione dei prossimi ritiri

**Prototipo mid fidelity**

Per la realizzazione del prototipo mid fidelity è stato seguito uno stile che prende ispirazione
dal Material design, ma dove i classici colori pieni e tendenti al pastello del Material design sono
stati sostituiti da dei gradiant per rendere il design dell’applicazione più fresco e moderno.
Prendendo spunto dal sistema fisico di riciclo ogni tipologia di prodotto ha un suo colore
assegnato, ad esempio la carta è rappresentata dal giallo, la plastica dal blue è così via.

Riprendendo questo concetto all’interno dell’applicazione ogni categoria di riciclo ha un suo
colore che è utilizzato all’interno di tutta l’applicazione per mantenere una continuità e per
permettere all’utente di identificare la categoria di riciclo di un prodotto senza nemmeno leggerla
ma semplicemente guardando il colore. Il resto dell’applicazione riporta colori molto chiari come
il bianco così da esaltare gli elementi colorati.

**_Mid fidelity Axure_**

_https://drive.google.com/drive/folders/1LAH4s7U7ssySUJ1qjYwP2rHotqHB4IhC?usp=sharing_


**_Mid fidelity images_**

_https://drive.google.com/drive/folders/16-KA3QY4jK18LVmEvIR_qaToNhqT-0G9?usp=sharing_

**_Mid fidelity video_**

_https://drive.google.com/drive/folders/1jZBjeRnRbHqRiLg8OX6s4mwYt9C4o5Iw?usp=sharing_

**Valutazione mid fidelity**

Il prototipo mid fidelity come quello low è stato testato da 5 persone, a cui è stato chiesto di
provare le seguenti funzionalità:

- Visualizzazione informazioni di un prodotto scannerizzato recentemente
- Controllare il prossimo ritiro del prodotto selezionato


- Scannerizzare un nuovo prodotto tramite fotocamera
- Ricercare un nuovo prodotto tramite ricerca testuale
- Accesso sezione categorie e visualizzazione informazione di una particolare categoria
- Cambio tipologia raccolta
- Visualizzazione di un altro prodotto recente
- Verifica distanza del cassonetto più vicino e visualizzazione nella mappa

Tramite il test di queste funzionalità sono emerse le seguenti problematiche:

- Alcuni utenti hanno trovato poco intuitivo il fatto che per ricevere più informazioni di un
    prodotto bisognasse cliccare sul bottone “scopri di più” e che non si potesse cliccare
    sull’immagine del prodotto
- La leggenda del calendario non è molto chiara
- Poco intuitivo come cambiare la tipologia di raccolta oppure la posizione
- Non si capisce se l’agenda è scrollabile
- In certi menù la grandezza delle scritte risulta poco leggibile
- Alcuni utenti hanno espresso che avrebbero voluto un maggior focus sull'utilizzo della
    fotocamera considerando che è la funzionalità principale
- Mancanza di un feedback istantaneo quando un pulsante viene premuto

**_Link video valutazioni mid fidelity_**
https://drive.google.com/drive/folders/1W7rzob0N91XZGYxqU_8aBJ_BJyvX6fyl?usp=sharing

**Conclusioni**

Il prototipo presenta ancora molte mancanze di usabilità come emerso dalla valutazione del
mid fidelity, dovute anche alla nostra poco esperienza in ambito di Human computer interaction,
il mid- fidelity andrebbe rivalutato e migliorato in base ai risultati emersi dalla valutazione degli
utenti finali prima di poter procedere con un high fidelity. Nonostante le problematiche emerse il
mid fidelity sviluppato ha riscontrato molti esiti positivi e per come è stata pensata l’applicazione
se portata a realizzazione potrebbe sostituire l’attuale competitor nel comune di Trento e riuscire
a scontrarsi anche in un mercato più ampio.


