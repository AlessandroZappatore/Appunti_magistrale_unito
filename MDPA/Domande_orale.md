# Domande orale Modellazione dei Processi Aziendali

## 1. Intro: Concettualizzazione e Sistemi Informativi

### Cos'è la **concettualizzazioene** e come viene percepita/organizzata da un agente?

> #### Definizione di Concettualizzazione
  >
  > La **concettualizzazione** è definita come il modo in cui un agente percepisce e organizza una porzione della realtà. Essa si realizza attraverso un processo di **astrazione** rispetto a una situazione specifica e al linguaggio utilizzato. In sostanza, un concetto emerge come risultato di generalizzazione e astrazione dell'esperienza, permettendo agli esseri umani di strutturare la percezione del dominio. L'agente organizza la realtà attraverso un processo selettivo che coinvolge i seguenti aspetti:
  >
  > 1. **Separazione delle invarianti**: L'agente deve isolare le **invarianti rilevanti** da quelle irrilevanti presenti nella realtà fisica. Questo processo si avvale della percezione, della cognizione, dell'esperienza culturale e del linguaggio. Le invarianti possono essere distinte in due livelli:
  >
  >     * **Livello Sincronico**: L'attribuzione di proprietà unitarie a schemi di input, fancedo emergere insiemi topologici o morfologici (ad esempio, una costellazione).
  >     * **Livello Diacronico**: Riguardano la persistenza nel tempo, permettendo di identificare **oggetti** (relazioni di equivalenza tra percezioni in momenti diversi) ed **eventi** (sequenze di percezioni nel tempo).
  >
  > 2. **Ruolo degli Obiettivi**: La selezione delle invarianti e la coseguente organizzazione della realtà sono guidate dagli **obiettivi** che l'agente deve raggiungere. L'obiettivo ultimo della concettualizzazione è trovare un linguaggio che rappresenti nel modo migliore ciò che l'agente vuole esprimere.
  > 3. **Soggettività**: Poiché la concettualizzazione dipende dagli obiettivi, è possibile che due agenti diversi elaborino **concettualizzazioni differenti per la stessa realtà** se perseguono scopi diversi.
  >
> #### Differenza rispetto all'Ontologia
  >
  > &Egrave; importante distinguere la concettualizzazione dall'**ontologia**. Mentre la concettualizzazione è un atto soggettivo compiuto da un agente in funzione di un obiettivo, l'ontologia è una descrizione formale della realtà (o dell'essere) che ne descrive la struttura, le categorie e le proprietà in modo indipendente, studando "ciò che c'è".

### Caratteristiche della **modellazione concettuale** in relazione agli obiettivi di un agente

> #### Selezione guidata dagli obiettivi
  >
  >La concettualizzazione non è una registrazione passiva della realtà, ma un processo attivo in cui l'agente deve separare le **invarianti rilevanti** da quelle irrilevanti. Questo filtro selettivo è determinato esplicitamente dagli **obiettivi** che l'agente deve raggiungere. L'agente isola gli aspetti della realtà fisica (invarianti spaziali e temporali) che sono tuili al suo scopo, utilizzando percezione, cognizione ed esperienza.
  >
> #### Soggettività e Variabilità del Modello
  >
  >Poiché la creazione del modello dipende dagli obiettivi, la concettualizzazione è intrisecamente soggettiva.
  >
  >* **Variazione del modello**: Al variare degli obiettivi, cambia la concettualizzazione.
  >* **Pluralità di visioni**: &Egrave; possibile (e normale) che due agenti diversi producano concettualizzazioni differenti per la stessa identica porzione di realtà, se i loro obiettivi differiscono.
  >
> #### Funzione Espressiva (Linguaggio)
  >
  >L'obiettivo ultimo della concettualizzazione è trovare un **linguaggio** che riesca a rappresnetare nel modo migliore ciò che l'agente vuole esprimere rispetto al dominio di interesse. Il modello funge quindi da mezzo per preservare e comunicare una certa visione del mondo, permettendo il ragionamento e la risoluzione di problemi.
  >
> #### Differenza rispetto all'Ontologia 2
  >
  > Questa dipendenza dagli obiettivi dell'agente distingue la modellazione concettuale dall'**ontologia**.
  >
  >* **Modellazione Concettuale**: Viene eseguita da un agente che persegue un obiettivo specifico.
  >* **Ontologia**: &Egrave; una descrizione formale della realtà che mira a descriverne la struttura e le proprietà ("ciò che c'è") in modo indipendente dagli scopi specifici di un agente.

### Cos'è un **Sistema Informativo** e quali sono le sue funzioni principali?

> Un **Sistema Informativo (IS)** è un sistema progettato per collezionare, immagazzinare, processare e distribuire informazioni riguardanti lo stato di un dominio specifico, definito "Universo del Discorso" (UoD). Il suo obiettivo principale è facilitare la pianificazione, il controllo, la coordinazione e il processo decisionale all'interno di un'organizzazione.
>
> &Egrave; importante notare che un Sistema Informativo non è costruito semplicemente da un database contente dati, ma comprende anche la semantica e l'organizzazione di tali dati.
>
> Le funzioni principali di un Sistema Informativo sono tre: **memorizzazione**, **informativa** e **attiva**.
>
> 1. **Funzione di Memorizzazione (Memory)**: Questa funzione permette al sistema di mantenere una rappresentazione interna dello stato del dominio. Tale rappresentazione si articola su due livelli:
>
>     * **Livello intensionale**: riguarda i concetti, le regole e i vincoli che che descrivono la struttura del dominio (ad esempio, lo schema del database).
>     * **Livello Estensionale**: riguarda le istanze specifiche dei concetti, ovvero i dati effettivi che popolano il sistema in un dato momento.
>
>     L'aggiornamento di queste informazioni può avvenire in due modalità:
>
>     * **Su richiesta**: l'utente informa esplicitamente il sistema di un cambiamento avvenuto nella realtà.
>     * **In autonomia**: il sistema osserva direttamente il dominio (ad esempio tramite sensori) e aggiorna automaticamente il proprio stato itnerno.
>
> 2. **Funzione informativa (Informative)**: Attraversp questa funzione, il sistema fornisce agli utenti informazioni sullo stato del dominio. Le interrogazioni (query) pososno riguardare dati specifici (query estensionali) o le proprietà delle classi e dei concetti (query intensionali).
>
>     Anche questa funzione opera in due modalità:
>
>     * **Su richiesta**: l'utente pone una domanda (query) e il sistema fornisce una risposta.
>     * **In autonomia**: l'utente definisce a priori una condizione di interesse e il sistema invia una notifica ogni volta che tale condizione si verifica nello stato mantenuto dal sistema.
>
> 3. **Funzione Attiva (Active)**: Un Sistema Informativo può eseguire azioni che modificano lo stato del dominio stesso. Per svolgere questa funzione, il sistema deve conoscere le azioni possibili, le loro precondizioni e i loro effetti.
>
>     L'esecuzione delle azioni segue le due modalità standard:
>
>     * **Su richiesta**: un utente autorizza o delega il sistema a eseguire un'azione specifica (ad esempio, effettuare una trasazione bancaria).
>     * **In autonomia**: il sistema è configurato per innescare (triggerare) automaticamente un'azione quando si verifica una specifica condizione nello stato del dominio (ad esempio, il riordino automatico di merce quando le scorte scendono sotto una certa soglia).

### Qual è la distinzione tra funzioni **su richiesta** e funzioni **in autonomia**?

> Nei Sistemi Informativi (IS), la distinzione tra le modalità **su richiesta** (on request) e **in autonomia** (autonomous) riguarda il soggetto o l'evento che innesca l'operazione del sistema: l'utente nel primo caso, il sistema stesso (tramite osservazione diretta o regole predefinite) nel secondo.
Questa distinzione si applica a tutte e tre le funzioni principali di un Sistema Informativo: memorizzazione, informativa e attiva.
>
> 1. **Funzione di Memorizzazione (Memory)**: Riguarda l'aggiornamento della rappresentazione interna dello stato del dominio (livello estensionale).
>
>     * **Su richiesta**: L'aggiornamento avviene perché un utilizzatore informa esplicitamente il sistema di un cambiamento avvenuto nella realtà.
>       * *Esempio*: Un operatore aggiorna manualmente l'indirizzo di un cliente nel CRM.
>     * **In autonomia**: Il sistema osserva direttamente il dominio (spesso tramite sensori o integrazioni automatiche) e aggiorna il proprio stato interno senza intervento umano diretto.
>         * *Esempio*: Un sistema di controllo misura la temperatura ambientale tramite sensori e aggiorna il dato nel database
>
> 2. **Funzione Informativa (Informative)**: Riguarda la fornitura di informazioni sullo stato del dominio agli utenti.
>
>     * **Su richiesta**: L'interazione parte dall'utente, che pone una domanda (query) al sistema e attende una risposta.
>       * *Esempio*: Un manager interroga il sistema per sapere quali dipendenti guadagnano più di una certa cifra.
>     * **In autonomia**: L'utente non pone una domanda specifica in quel momento, ma ha definito a priori una condizione di interesse. Il sistema monitora lo stato e invia una notifica (alert) all'utente ogni volta che tale condizione si verifica.
>       * *Esempio*: Un operatore riceve un avviso automatico quando la temperatura di una CPU supera una soglia critica.
>
> 3. **Funzione Attiva (Active)**: Riguarda l'esecuzione di azioni che modificano lo stato del dominio reale.
>
>     * **Su richiesta**: Un utente autorizza o delega esplicitamente il sistema a eseguire un'azione specifica.
>       * *Esempio*: Un utente ordina al sistema di effettuare un bonifico bancario.
>     * **In autonomia**: Il sistema è configurato per innescare (triggerare) automaticamente un'azione quando si verifica una specifica condizione nello stato del dominio, senza bisogno di un comando umano al momento dell'esecuzione.
>         * *Esempio*: Il sistema invia automaticamente un ordine di rifornimento al fornitore quando le scorte di magazzino scendono sotto una certa soglia (riordino automatico).
>
> In sintesi, la modalità **su richiesta** è reattiva rispetto ai comandi dell'utente, mentre la modalità **in autonomia** è proattiva, basata sul monitoraggio continuo e su regole preimpostate.

### Cosa sono le **query intensionali ed estensionali**?

>Nel contesto della funzione **informativa** di un Sistema Informativo (IS), che ha lo scopo di fornire agli utenti informazioni sullo stato del dominio, le interrogazioni (query) vengono classificate in due tipologie principali: **estensionali** e **intensionali**.
>
>Questa distinzione riflette la struttura della memoria del sistema, suddivisa in livello estensionale (i dati/istanze) e livello intensionale (lo schema/concetti).
>
> 1. **Query Estensionali**: Le query estensionali richiedono informazioni specifiche riguardanti elementi particolari o lo stato attuale del dominio (l'Information Base).
>     * **Obiettivo**: Recuperare dati fattuali su istanze specifiche.
>     * **Esempi**: "Chi sta frequentando il corso di Modellazione Concettuale?" oppure "Chi ha accumulato acquisti superiori a 100.000 euro?".
>     * **Tipo di risposta**: È interessante notare che a una query estensionale il sistema può rispondere in due modi:
>         * Con informazione *estensionale*: "Laura sta frequentando il corso" (elenco puntuale delle istanze).
>         * Con informazione *intensionale*: "I clienti Gold" (una descrizione o categoria che raggruppa le istanze richieste).
> 2. **Query Intensionali**: Le query intensionali riguardano le proprietà di una classe, le definizioni dei concetti e i vincoli strutturali del sistema. Esse interrogano il sistema sul *tipo* di informazioni che esso conosce e su come sono strutturate, piuttosto che sui dati contenuti in quel momento.
>
>     * **Obiettivo**: Comprendere la struttura, le regole o il significato dei dati (livello dello schema o ontologico).
>     * **Esempio**: "Che cos'è uno studente?".
>
>In sintesi, mentre le query estensionali interrogano i **fatti** (livello dei dati), le query intensionali interrogano le **regole e i concetti** (livello dello schema).

### Quali sono le differenze tra la **modellazione del dominio concettuale** e quella **ontologica**?

> 1. **Ruolo dell'Agente e degli Obiettivi (Soggettività vs Oggettività)**: La differenza fondamentale risiede nel **chi** esegue la modellazione e **perché**.
>
>     * **Modellazione Concettuale (Concettualizzazione)**: È un processo intrinsecamente dipendente da un **agente** che persegue un **obiettivo** specifico.
>       * L'agente filtra la realtà attraverso un processo di astrazione, separando le "invarianti rilevanti" da quelle irrilevanti in funzione dei propri scopi.
>       * L'obiettivo è trovare un linguaggio che rappresenti nel modo migliore ciò che l'agente vuole esprimere o preservare rispetto a una specifica visione del mondo.
>       * Di conseguenza, due agenti diversi con obiettivi diversi possono produrre concettualizzazioni differenti della stessa realtà.
>     * **Modellazione Ontologica**: È definita come una descrizione formale della realtà che mira a descriverne la struttura, le categorie e le proprietà in modo indipendente.
>       * Filosoficamente, l'ontologia studia "la natura e la struttura dell'essere" e "ciò che c'è", a prescindere dalla sua esistenza attuale o dagli scopi di un osservatore specifico.
>
> 2. **Assunzioni sulla Conoscenza (Open vs Closed World)**: Una distinzione tecnica cruciale riguarda il modo in cui i due approcci trattano l'assenza di informazioni (verità vs conoscenza).
>
>     * **Modellazione Concettuale** (es. Database): Adotta tipicamente la **Closed World Assumption (CWA)**.
>       * Si assume che tutto ciò che è vero sia conosciuto dal sistema.
>       * Se un fatto non è presente nel sistema, si assume che sia **falso**.
>     * **Modellazione Ontologica** (es. Web Semantico): Adotta tipicamente la **Open World Assumption (OWA)**.
>       * Ciò che è noto al sistema è solo un sottoinsieme di ciò che è vero.
>       * La mancanza di conoscenza su un fatto non implica che esso sia falso, ma semplicemente che non è noto ("non si sa").
>
> 3. **Interpretazione dei Vincoli**: Conseguenza diretta del punto precedente è l'uso che si fa dei vincoli nel modello:
>
> * **Nel Modello Concettuale**: I vincoli sono interpretati come controlli di integrità (integrity checks). Il sistema verifica che i dati inseriti rispettino le regole; se non le rispettano, l'aggiornamento viene rifiutato.
> * **Nell'Ontologia**: I vincoli sono interpretati come **conoscenza intensionale** utilizzata per fare inferenza. Il sistema usa i vincoli per dedurre o costruire nuove informazioni ("modelli") a partire da ciò che è noto.

### Chi sono gli utenti che interagiscono con il sistema informativo?

>Gli utenti che interagiscono con un Sistema Informativo (IS) possono essere classificati in base al loro ruolo, alle funzioni che svolgono e alla loro posizione rispetto all'organizzazione (interni o esterni).
>
>1. **Classificazione per Ruolo nel Processo (BPM)**: Nel contesto del Business Process Management, gli utenti (stakeholder) sono suddivisi tra ambito Business e ambito IT:
>     * **Process Participant (Partecipante al processo)**: Sono gli utenti operativi che svolgono le attività quotidiane previste dal workflow. Esempi specifici citati nel caso di studio includono il **magazziniere** (che riceve e stocca merci), l'**impiegato** (che analizza scorte e gestisce pagamenti), il **venditore** (che registra ordini e clienti), il **manager** (che analizza i rischi) e lo **spedizioniere**.
>     * **Process Responsible (Responsabile del processo)**:
>         * *Livello Strategico*: Definisce gli obiettivi a lungo termine.
>         * *Livello Operativo*: Il "Process Owner" che ha la responsabilità globale del processo, ne monitora l'efficienza e opera in modo trasversale rispetto alle funzioni aziendali.
>     * **Process Analyst (Analista di processo)**: Si occupa dell'analisi, della modellazione e dell'ottimizzazione dei processi.
>     * **Process Engineer (Ingegnere di processo)**: Cura l'implementazione tecnica e l'ingegnerizzazione del workflow.
>     * **Enterprise Architect**: Definisce l'architettura generale dei sistemi e come i processi si integrano nel panorama IT.
>2. **Utenti Esterni e Contesto**: Il sistema interagisce con entità esterne all'organizzazione, fondamentali per la catena del valore:
>     * **Clienti**: Sono i fruitori finali del valore (prodotto o servizio) generato dal processo. Nel caso di studio, interagiscono per effettuare ordini o richieste (anche tramite portali web o call center).
>     * **Fornitori (Suppliers)**: Interagiscono con il sistema inviando merci, fatture e ricevendo ordini e pagamenti.
>     * **Competitors (Concorrenti)**: Pur non essendo utenti diretti del sistema interno, influenzano il contesto strategico in cui il sistema opera.
>3. **Modalità di Interazione**: Gli utenti interagiscono con il sistema attraverso il livello di presentazione (Presentation Layer), che gestisce l'interfaccia e la sicurezza. A seconda della funzione svolta, l'interazione può essere:
>
>     * **Per l'aggiornamento (Funzione di Memorizzazione)**:
>         * *Esempio*: Un operatore (es. un impiegato del CRM) informa esplicitamente il sistema di un cambiamento avvenuto nella realtà, aggiornando l'informazione estensionale.
>     * **Per la consultazione (Funzione Informativa)**:
>         * *Esempio*: Un manager interroga il sistema (query on request) per sapere, ad esempio, quali dipendenti guadagnano più di una certa cifra o per ottenere report decisionali.
>     * **Per l'esecuzione (Funzione Attiva)**:
>         * *Esempio*: Un utente autorizza o delega il sistema a eseguire un'azione specifica, come una transazione bancaria.
>4. **Il Sistema come "Utente" (Modalità Autonoma)**: È importante notare che, nelle modalità b, il sistema stesso agisce come un agente che osserva il dominio (tramite sensori) o esegue azioni (triggerate da eventi) senza l'intervento diretto di un utente umano in quel momento specifico. Tuttavia, queste regole sono configurate a monte da utenti tecnici o analisti.

### **Modello, Metamodello e Linguaggio**: Qual è la differenza tra questi tre livelli di astrazione?

> La differenza tra Modello, Metamodello e Linguaggio risiede nel livello di astrazione e nell'oggetto che ciascuno di essi descrive. Possiamo visualizzarli come una gerarchia dove ogni livello definisce le regole per quello sottostante.
>
> 1. **Il Modello (Livello del Dominio)**: Il **modello** è un'astrazione della realtà (o di una porzione di essa, detta *Universo del Discorso*) costruita secondo una certa concettualizzazione.
>     * **Funzione**: Serve a preservare e comunicare una specifica visione del mondo, supportando l'analisi e la risoluzione di problemi.
>     * **Cosa descrive**: Descrive entità, processi o dati specifici di un'organizzazione o di un sistema reale (ad esempio: il processo di vendita di un'azienda, gli ordini, i clienti).
>     * **Esempio**: Un diagramma BPMN che illustra come viene gestito un ordine di pizza ("make pin", "request credit").
> 2. **Il Linguaggio di Modellazione (Strumento Espressivo)**: Il **linguaggio di modellazione** (come UML, ORM o BPMN) è lo strumento utilizzato per costruire il modello. Esso fornisce la notazione (grafica o testuale), la sintassi e la semantica necessarie per rappresentare la realtà.
>
>     * **Funzione**: Permette al modellatore di esprimere gli aspetti statici e dinamici del dominio in modo comprensibile e (spesso) formale.
>     * **Relazione**: È il mezzo tramite il quale il modello viene concretizzato. Il metamodello "fissa" il linguaggio da utilizzare.
>
> 3. **Il Metamodello (Livello delle Regole)**: Il **metamodello** (o schema metaconcettuale) è un modello che descrive il linguaggio stesso. È uno schema che specifica le regole di progettazione che devono essere soddisfatte dai modelli concettuali.
>     * **Funzione**: Definisce i tipi di elementi utilizzabili per costruire un modello e le relazioni permesse tra di essi. In pratica, definisce la grammatica e la struttura del linguaggio di modellazione.
>     * **Cosa descrive**: Non descrive la realtà aziendale (es. "Clienti"), ma i costrutti del linguaggio (es. "Che cos'è un'Attività?", "Che cos'è una Relazione?", "Un processo è composto da 1 a N attività").
>     * **Esempio**: La regola che stabilisce che "una relationship type è un tipo di fatto che mette in relazione almeno due entity types" è una regola del metamodello ORM.
>
> #### Sintesi delle differenze (Gerarchia di Astrazione)
>
> 1. **Metamodello**: Astrae dai Modelli. Definisce concetti astratti come Processo e Attività e le loro relazioni logiche.
> 2. **Modello**: Astrae dai Casi Reali (istanze). Utilizza i concetti del metamodello per descrivere scenari specifici come Vendite o Produzione.
> 3. **Casi (Realtà)**: Sono le istanze concrete, come "lo spillo prodotto da Adam Smith nel 1776".
>
> In breve: il **Metamodello** definisce il **Linguaggio**, il quale viene usato per creare il **Modello**, che a sua volta rappresenta la **Realtà**.

### **Sintassi vs Semantica**: Differenza tra sintassi (concreta e astratta) e semantica di un linguaggio di modellazione

> La distinzione tra sintassi (nelle sue forme astratta e concreta) e semantica di un linguaggio di modellazione può essere articolata analizzando i criteri di correttezza e la struttura dei linguaggi (come BPMN o ORM).
>
> 1. **Sintassi (La Forma e le Regole)**: La sintassi definisce le regole per la corretta costruzione di un modello, indipendentemente dal suo significato nel mondo reale. Essa si divide in due livelli:
>
>     * **Sintassi Astratta** (Il Metamodello): Corrisponde al Metamodello (o schema metaconcettuale). Questo livello definisce la struttura logica del linguaggio, i tipi di elementi utilizzabili e le regole di composizione che devono essere soddisfatte affinché un modello sia valido.
>         * *Esempio*: La regola che stabilisce che "una relationship type è un fatto che mette in relazione almeno due entity types" è una regola sintattica astratta definita dal metamodello ORM.
>         * *Correttezza Sintattica*: Un modello è sintatticamente corretto se è conforme al metamodello del linguaggio.
>     * **Sintassi Concreta (La Notazione)**: Riguarda la rappresentazione visiva o testuale degli elementi definiti dalla sintassi astratta. Le fonti si riferiscono a questo aspetto parlando di **notazione grafica** o testuale.
>         * *Esempio*: In BPMN, ogni componente del nucleo (Core) è associato a una specifica notazione grafica (es. rettangoli arrotondati per le attività, rombi per i gateway). La chiarezza del modello dipende da quanto bene questa notazione viene utilizzata.
> 2. **Semantica (Il Significato)**: La semantica riguarda il significato attribuito ai costrutti sintattici e come questi si mappano sulla realtà (l'Universo del Discorso).
>
>     * **Definizione**: È legata al "Triangle of Meaning", che collega il simbolo (parola/segno) al concetto e al referente reale. La semantica definisce come interpretare i simboli del linguaggio per comprendere lo stato e il comportamento del dominio.
>     * **Correttezza Semantica**: Un modello è semanticamente corretto se la conoscenza rappresentata nello schema concettuale è rilevante e vera nel dominio di applicazione.
>     * **Formalizzazione**: Per evitare ambiguità, la semantica deve essere ben definita.
>         * Nel caso del **BPMN**, la semantica formale è rappresentata dal **Token Game**, ispirato alle **Reti di Petri**. Il movimento del token (che rappresenta l'esecuzione di un'istanza) attraverso i simboli grafici (sintassi concreta) definisce il comportamento logico del processo (semantica).
>
> Sintesi delle differenze:

| Livello           | Concetto Chiave               | Funzione                                                               | Esempio                                                                             |
|-------------------|-------------------------------|------------------------------------------------------------------------|-------------------------------------------------------------------------------------|
| Sintassi Astratta | Metamodello.                  | Definisce le regole di composizione e le strutture valide.             | "Un arco deve collegare due nodi".                                                  |
| Sintassi Concreta | Notazione (Grafica/Testuale). | Definisce come il modello appare visivamente.                          | "Le attività sono rettangoli smussati".                                             |
| Semantica         | Significato/Interpretazione.  | Definisce cosa il modello rappresenta nella realtà o come si comporta. | "Questo rettangolo significa che l'utente deve approvare l'ordine" o il Token Game. |

> In conclusione, mentre la **sintassi** assicura che il modello sia "ben formato" secondo le regole del metamodello, la **semantica** assicura che il modello abbia un senso e rappresenti fedelmente la realtà o il comportamento desiderato.

### **Componenti del Sistema Informativo**: Quali sono le 5 componenti essenziali?

> Le "5 componenti essenziali" a cui si fa riferimento nel contesto della modellazione dei sistemi informativi aziendali corrispondono ai **cinque modelli** (o **metamodelli**) **distinti ma coordinati** necessari per descrivere un'azienda o un sistema senza renderne la rappresentazione incomprensibile.
>
> Questi cinque modelli rappresentano cinque punti di vista fondamentali sotto cui è possibile osservare l'azienda:
>
> 1. **Modello Strategico**: Rappresenta gli obiettivi che l'azienda intende raggiungere (business goals). Il processo deve essere conforme a tali obiettivi; se la strategia definisce il "cosa" e il "perché", il modello strategico vincola il processo affinché permetta di raggiungerli.
> 2. **Modello Organizzativo**: Definisce la struttura statica dell'azienda, incluse le unità organizzative (dipartimenti, uffici) e le risorse (persone, ruoli) che vengono assegnate alle varie funzioni.
> 3. **Modello Funzionale**: Descrive il comportamento dell'azienda analizzando lo scambio di oggetti (informazioni o prodotti) tra le sue funzioni. Tiene conto delle risorse impegnate e dei vincoli. Spesso viene rappresentato utilizzando il linguaggio **IDEF0**.
> 4. **Modello dei Processi**: Specifica la dinamica, ovvero come avviene l'esecuzione delle attività nel tempo. Descrive l'insieme delle esecuzioni possibili (istanze), gli stati attraverso cui passa un'attività e le transizioni causate dagli eventi.
> 5. **Modello di Implementazione**: Riguarda la traduzione del modello in specifiche tecniche eseguibili, ad esempio l'input per un motore di workflow che gestisce l'automazione del processo.
>
> Questi modelli lavorano in sinergia per coprire tutti gli aspetti del sistema informativo: dagli obiettivi di alto livello (Strategico) all'esecuzione tecnica (Implementazione), passando per la struttura (Organizzativo), le funzioni (Funzionale) e il flusso di lavoro (Processo).

## 2. ORM (Object-Role Modeling)

### Quali sono le differenze strutturali e filosofiche tra **UML**, **ORM** ed **E-R**?

>Le differenze strutturali e filosofiche tra Entity-Relationship (E-R), Unified Modeling Language (UML) e Object-Role Modeling (ORM) risiedono principalmente nel modo in cui ciascun linguaggio astrae la realtà, gestisce gli attributi e si orienta verso l'implementazione finale.
>
>
>**1. Entity-Relationship (E-R)**
>
>* **Filosofia:** È il linguaggio più diffuso per la modellazione dei dati, focalizzato specificamente sulla struttura statica dei dati stessi. È fortemente orientato verso la progettazione di database relazionali.
>* **Struttura:** Si basa su tre costrutti principali: **entità, relazioni e attributi**. Le entità rappresentano oggetti identificabili, mentre le relazioni sono tuple di entità.
>* **Limiti:** Manca di una modellazione dinamica (comportamentale) ed è spesso molto vicino allo schema logico relazionale, riducendo il livello di astrazione.
>
>**2. Unified Modeling Language (UML)**
>
>* **Filosofia:** È lo standard per l'ingegneria del software e la progettazione **Object-Oriented**. A differenza dell'E-R, non si limita ai dati ma include aspetti comportamentali (operazioni e metodi) e politiche di incapsulamento tipiche del paradigma a oggetti.
>* **Struttura:** Utilizza diagrammi di classe caratterizzati da **classi e attributi**.
>* **Dettaglio:** Le classi in UML fungono da entità, ma integrano anche la logica comportamentale, distinguendosi per una maggiore ricchezza semantica rispetto all'E-R per quanto riguarda il design del software, ma mantenendo l'uso degli attributi.
>
>**3. Object-Role Modeling (ORM)**
>
>* **Filosofia (Fact-Oriented):** ORM adotta un approccio orientato ai fatti per modellare la semantica dell'Universo del Discorso. Mira a una maggiore stabilità semantica e indipendenza dalle scelte implementative.
>* **Struttura (Senza Attributi):** La differenza strutturale più radicale è l'assenza di attributi. In ORM, gli elementi primitivi sono gli **oggetti** e i **ruoli** che questi giocano nelle relazioni.
>* **Differenze Chiave con E-R e UML:**
>   * **Assenza di attributi:** Mentre E-R e UML usano attributi per descrivere le proprietà (es. una persona ha un nome), ORM tratta tutto come relazioni tra oggetti (es. l'oggetto "Persona" ha una relazione con l'oggetto "Nome"). L'uso di attributi è considerato un "impegno prematuro" che riduce la stabilità del modello nel tempo.
>   * **Concetto di Istanza:** In E-R e UML le entità sono istanze degli elementi. In ORM, le istanze si manifestano solo quando giocano un ruolo in una relazione con altri elementi.
>   * **Espressività vs Semplicità:** ORM utilizza costrutti atomici più semplici (fatti elementari), ma ciò porta a diagrammi graficamente più complessi e ricchi di elementi rispetto a quelli di E-R e UML.
>   * **Verbalizzazione:** ORM facilita la validazione con esperti del dominio poiché i fatti e le regole possono essere facilmente tradotti in frasi in linguaggio naturale (verbalizzazione) e popolati con esempi concreti.
>
>In sintesi, mentre **E-R** e **UML** strutturano il mondo in "entità contenitori" dotate di attributi (rispettivamente per DB relazionali e software a oggetti), **ORM** appiattisce questa struttura trattando ogni informazione come una relazione tra oggetti elementari, favorendo la stabilità semantica e l'analisi concettuale pura.

### **Metodologia CSDP**: descrivere i punti e la funzione del primo passo

>Il primo passo della metodologia **CSDP** (Conceptual Schema Design Procedure) è denominato **"Trasformare gli Esempi in Fatti Elementari"**.
>
>La funzione principale di questo passo è ottenere una comprensione approfondita del dominio di riferimento (Universo del Discorso - UoD) per isolare le informazioni rilevanti che dovranno essere rappresentate nel Sistema Informativo. L'obiettivo è arrivare alla definizione di **fatti elementari**, ovvero le più piccole unità informative che, se ulteriormente semplificate, perderebbero di significato semantico.
>
>La procedura operativa di questo primo passo si articola in **cinque punti fondamentali**:
>
>1. **Raccolta degli esempi:** Si raccolgono tutte le fonti di informazione disponibili, come report, scontrini, grafici, moduli e tabelle. È necessario coprire tutti i casi possibili, tenendo presente che la maggior parte del materiale grezzo rappresenta una conoscenza incompleta del dominio.
>2. **Analisi con l'esperto di dominio:** Si discute il materiale raccolto con gli esperti per disambiguare situazioni anomale. In questa fase si identificano i sinonimi, si scelgono i termini preferenziali e si redige un **glossario**.
>3. **Verbalizzazione:** Si trasformano gli esempi raccolti in frasi in linguaggio naturale (verbalizzazione del sistema).
>4. **Processare le verbalizzazioni:** Si analizzano le frasi per individuare i fatti elementari, scomponendo quelli complessi o composti. Questo serve a riscrivere il sistema in termini di fatti atomici e a definire esattamente quale parte del dominio è rilevante.
>5. **Rielaborazione (Arricchimento):** Poiché gli esempi iniziali potrebbero non coprire tutte le casistiche necessarie, si aggiungono nuovi fatti elementari per colmare le lacune e arricchire la conoscenza del dominio.
>
>In sintesi, questo passo trasforma dati non strutturati e conoscenza implicita in asserzioni formali e atomiche (es. "La Persona X lavora per la Compagnia Y"), che costituiscono la base solida per la costruzione del modello concettuale.

### Cos'è un **fatto elementare** e cosa non lo è? Fornire esempi

>Un **fatto elementare** è definibile come la più piccola unità informativa che possiede un significato autonomo all'interno dell'Universo del Discorso (UoD). È un'asserzione atomica che coinvolge uno o più oggetti e i ruoli che essi giocano in una relazione.
>
>La caratteristica fondamentale di un fatto elementare è l'**inseparabilità**: se si tentasse di scomporlo ulteriormente in unità più piccole, si verificherebbe una perdita di informazioni o il frammento risultante perderebbe di senso compiuto.
>
>
>### 1. Cos'è un Fatto Elementare
>
>Un fatto elementare afferma che un particolare oggetto possiede una proprietà (fatto unario) o che più oggetti partecipano insieme a una relazione.
>
>**Esempi di fatti elementari:**
>
>* **Fatti unari (Proprietà):** *"Anna fuma"*. Questo fatto non può essere spezzato; descrive una caratteristica dell'oggetto "Anna".
>* **Fatti binari:** *"Anna impiega Bob"* oppure *"Bob è impiegato da Anna"*. Questa è una relazione diretta tra due entità.
>* **Fatti n-ari (Inseparabili):** *"Il gruppo di studio A si incontra Lunedì alle 15:00 nell'aula CS-718"*. Sebbene coinvolga tre oggetti (Gruppo, Tempo, Aula), questo fatto potrebbe essere considerato elementare se la relazione tra i tre è inscindibile (ovvero, se non si può dedurre che il gruppo è in quell'aula senza specificare l'orario).
>
>### 2. Cosa NON è un Fatto Elementare
>
>Un fatto non è elementare se può essere diviso in due o più fatti più semplici senza perdere informazioni. Inoltre, spesso non sono considerati fatti elementari le negazioni o le proposizioni logiche complesse che usano connettivi come "e" (congiunzioni).
>
>**Esempi di fatti NON elementari:**
>
>* **Fatti composti (Congiunzioni):** *"Anna impiega Bob e John"*.
>   * *Perché non è elementare:* Questo fatto può essere diviso in due fatti elementari distinti: "Anna impiega Bob" e "Anna impiega John", senza alcuna perdita di significato.
>* **Fatti ambigui o composti:** *"Anna e Bob chiedono un prestito"*.
>   * *Perché non è elementare:* A meno che non si tratti di un prestito cointestato inscindibile, solitamente indica due azioni separate di richiesta.
>* **Fatti negativi:** *"Bob non fuma"*.
>   * *Perché non è elementare:* Nei sistemi informativi (specialmente quelli basati sulla *Closed World Assumption*), si memorizzano solo i fatti veri. Se il fatto "Bob fuma" non è presente nel sistema, si assume implicitamente che sia falso. Pertanto, la negazione non è un fatto elementare da memorizzare esplicitamente.
>
>### Come verificare se un fatto è elementare?
>
>Per determinare se un fatto ternario o superiore è elementare, si può utilizzare il test della **proiezione concettuale (Split & Join)**: si prova a separare la tabella dei fatti in tabelle più piccole e poi a ricongiungerle (join). Se il risultato del join restituisce la tabella originale senza generare "falsi" fatti o duplicati errati, allora il fatto originale non era elementare e doveva essere separato; se invece le tabelle non coincidono, il fatto è inscindibile ed è quindi elementare.

### Qual è la differenza tra **object type dipendenti** e **object type indipendenti**?

>La differenza fondamentale tra **object type dipendenti** e **object type indipendenti** nel modello ORM risiede nella condizione necessaria per la loro esistenza all'interno della base di dati (Information Base).
>
>### 1. Object Type Indipendenti
>
>Un object type è definito **indipendente** quando la sua esistenza è considerata rilevante "di per sé", a prescindere dalle relazioni che intrattiene con altri oggetti.
>
>* **Caratteristica principale:** I suoi ruoli nei fatti sono "collettivamente opzionali". Ciò significa che un'istanza di questo oggetto può essere registrata nel sistema anche se non partecipa attivamente a nessuna relazione specifica in quel momento.
>* **Esempio:** Un'aula (*Room*) in una università può esistere ed essere elencata nel database anche se in quel momento non ospita alcuna lezione e non è prenotata da nessuno.
>* **Notazione grafica:** Viene marcato con un punto esclamativo (**!**) accanto al nome dell'oggetto nel diagramma.
>* **Mapping Relazionale:** Poiché ha un proprio ciclo di vita autonomo, un object type indipendente deve essere mappato su una **tabella dedicata** (o tabella di riferimento) che elenchi tutte le sue istanze esistenti, indipendentemente dal fatto che giochino altri ruoli.
>
>### 2. Object Type Dipendenti (Non-Indipendenti)
>
>Sebbene le fonti non usino esplicitamente il termine "dipendente" come definizione formale opposta, descrivono il comportamento standard degli object type in ORM (quando non marcati come indipendenti).
>
>* **Caratteristica principale:** La popolazione di un object type non indipendente è costituita esattamente dall'unione delle popolazioni di tutti i ruoli ad esso collegati.
>* **Esistenza:** Le istanze di questi oggetti si manifestano nel sistema **solo quando giocano un ruolo** in una relazione con altre entità. Se un oggetto di questo tipo smette di partecipare a qualsiasi fatto modellato nello schema, esso cessa di essere registrato nel sistema.
>* **Vincoli:** Esiste un vincolo di obbligatorietà disgiuntiva implicito che copre tutti i ruoli giocati dall'oggetto.
>
>### Sintesi
>
>In breve, se si vuole poter inserire nel database un oggetto (es. "Cliente") senza dover necessariamente specificare un fatto che lo riguardi (es. "ha fatto un ordine"), quell'oggetto deve essere modellato come **indipendente** (`!`). Se invece l'oggetto esiste nel sistema solo in virtù delle sue azioni o relazioni (es. un "Ordine" esiste solo se collegato a un cliente e a un prodotto), esso è trattato come un object type standard (dipendente dai fatti).

### Cosa sono i **vincoli ad anello**? (Definizione, esempi e schemi d'uso)

>I **vincoli ad anello** (o *Ring Constraints*) sono vincoli specifici del modello ORM applicabili a coppie di ruoli collegate allo stesso *object type* (fact type omogenei o ricorsivi). Vengono utilizzati per definire le proprietà logiche delle relazioni che un oggetto intrattiene con altri oggetti dello stesso tipo, prevenendo situazioni logicamente impossibili o indesiderate.
>
>### 1. Definizione e Tipologie
>
>I vincoli ad anello applicano le proprietà delle relazioni matematiche in senso "negativo" (cioè come vincoli da rispettare per escludere certe configurazioni). Le principali tipologie definite sono:
>
>* **Irreflessibilità (Irreflexive):** Un oggetto non può essere in relazione con se stesso.
>   * *Formula:* $\forall x, \neg xRx$.
>   * *Esempio:* Una persona non può essere supervisore di se stessa.
>* **Asimmetria (Asymmetric):** Se un oggetto A è in relazione con B, allora B non può essere in relazione con A (questo implica automaticamente l'irreflessibilità).
>   * *Formula:* $\forall x, y, xRy \rightarrow \neg yRx$.
>   * *Esempio:* La relazione "è genitore di". Se A è genitore di B, B non può essere genitore di A.
>* **Antisimmetria (Antisymmetric):** Simile all'asimmetria, ma permette l'uguaglianza (riflessività). Se A è in relazione con B e A è diverso da B, allora B non può essere in relazione con A.
>   * *Formula:* $\forall x, y, x \neq y \wedge xRy \rightarrow \neg yRx$.
>* **Intransitività (Intransitive):** Se A è in relazione con B e B è in relazione con C, allora A non può essere in relazione diretta con C.
>   * *Formula:* $\forall x, y, z, xRy \wedge yRz \rightarrow \neg xRz$.
>   * *Esempio:* La relazione "è padre di". Se A è padre di B e B è padre di C, A è nonno (non padre) di C.
>* **Simmetria (Symmetric):** Se A è in relazione con B, allora B deve essere in relazione con A.
>   * *Formula:* $xRy \rightarrow yRx$.
>   * *Esempio:* La relazione "è sorella di" (assumendo il contesto femminile) o "è collega di".
>
>### 2. Schemi d'uso e Casi Complessi
>
>I vincoli ad anello vengono rappresentati graficamente collegando i due ruoli della relazione ricorsiva con icone stilizzate che richiamano la proprietà matematica imposta.
>
>**Aciclicità (Acyclic)**
>È una generalizzazione dell'asimmetria. Si usa quando si vuole evitare che si formino cicli indiretti attraverso l'applicazione ripetuta della relazione.
>
>* *Uso:* È fondamentale nelle strutture gerarchiche (es. organigrammi, distinte base) per evitare loop infiniti (es. A supervisiona B, B supervisiona C, C supervisiona A).
>* *Vincolo:* Un oggetto non può essere indirettamente collegato a se stesso ($A \to B \to C \to A$ è illegale).
>* *Criticità:* È un vincolo costoso da verificare nei database (richiede la chiusura transitiva), quindi spesso viene controllato in modalità batch o demandato alle procedure di inserimento dati piuttosto che imposto strutturalmente in tempo reale.
>
>**Relazioni tra vincoli**
Esistono implicazioni logiche tra i diversi vincoli ad anello che evitano ridondanze nello schema:
>
>* Un vincolo di **Esclusione** tra i ruoli implica l'asimmetria e, di conseguenza, l'irreflessibilità.
>* L'**Asimmetria** implica l'irreflessibilità.
>
>### 3. Esempi Grafici e Concettuali
>
>Le fonti riportano diversi esempi di modellazione:
>
>* **Person -- is sister of -- Person:** Può essere modellato con vincoli di simmetria (se A è sorella di B, B è sorella di A) e irreflessibilità (A non è sorella di se stessa).
>* **Person -- is supervisor of -- Person:** Richiede un vincolo di aciclicità (per evitare che un subordinato sia indirettamente il capo del proprio capo) e asimmetria.
>* **Person -- is parent of -- Person:** Richiede asimmetria e aciclicità (nessuno può essere antenato di se stesso).
>* **City -- has direct connection to -- City:** Se la connessione è bidirezionale ma non si può essere connessi a se stessi, si usa l'irreflessibilità e la simmetria. Se il grafo deve essere un triangolo che non si chiude, si potrebbe usare l'intransitività.

### Chi è il proprietario dei dati/database nel contesto di un progetto ORM?

>Nel contesto di un progetto **ORM** (Object-Role Modeling) e della relativa metodologia di progettazione (CSDP), la figura che detiene la conoscenza, l'autorità semantica e, di fatto, la "proprietà" concettuale dei dati è l'**esperto di dominio** (o esperto del dominio).
>
>1. **Ruolo nella Metodologia CSDP:** Durante il primo passo della procedura di progettazione (CSDP - *Conceptual Schema Design Procedure*), il modellatore raccoglie esempi di informazioni (report, moduli, ecc.) ma deve analizzarli e discuterli con l'**esperto di dominio**. È compito dell'esperto disambiguare situazioni anomale, chiarire i sinonimi e validare che l'interpretazione dei dati corrisponda alla realtà dell'azienda.
>2. **Validazione tramite Verbalizzazione:** Una delle caratteristiche distintive di ORM è la capacità di tradurre i diagrammi e i vincoli in frasi in linguaggio naturale (verbalizzazione). Questo processo è pensato specificamente per permettere all'esperto di dominio (che potrebbe non avere competenze tecniche informatiche) di validare i fatti e le regole del sistema. Poiché è l'esperto a confermare se un fatto è vero o falso nell'Universo del Discorso (UoD), egli agisce come autorità ultima sulla correttezza dei dati.
>3. **Rappresentazione dell'Universo del Discorso:** Il modello concettuale serve a rappresentare l'**Universo del Discorso (UoD)**, ovvero il dominio di interesse dell'organizzazione. I dati inseriti nella base di informazioni (*Information Base*) devono riflettere lo stato di questo dominio. L'esperto di dominio è colui che conosce questo stato e le regole di business che lo governano.
>
>In sintesi, mentre il modellatore fornisce la struttura formale (lo schema concettuale), è l'**esperto di dominio** a fornire il contenuto semantico e a possedere la "verità" sui dati rappresentati.

### **Vincoli di Set-Comparison**: Definizione e utilizzo dei vincoli di **Subset**, **Equality** e **Exlusion** tra ruoli

>I **vincoli di Set-Comparison** (o vincoli insiemistici) in ORM servono a confrontare le popolazioni di due o più ruoli (o sequenze di ruoli) giocati dallo stesso *object type* (o da un suo supertipo). Questi vincoli definiscono le relazioni logiche tra le istanze che partecipano ai diversi fatti.
>
>Definizione e utilizzo dei tre vincoli principali:
>
>### 1. Vincolo di Subset (Sottoinsieme)
>
>* **Simbolo:** $\subseteq$
>* **Definizione:** Indica che la popolazione di un ruolo (o sequenza di ruoli) $r1$ deve essere inclusa nella popolazione di un altro ruolo $r2$. Formalmente: $pop(r1) \subseteq pop(r2)$.
>* **Utilizzo:** Si usa quando la partecipazione a un fatto implica necessariamente la partecipazione a un altro, ma non viceversa. Se un oggetto gioca il ruolo $r1$, allora deve giocare anche il ruolo $r2$.
>* **Esempio:** Una *Company* può fornire servizi di E-Commerce ($r1$) e può essere registrata a una banca elettronica sicura ($r2$). Il vincolo di subset stabilisce che "Se una compagnia fornisce servizi di E-Commerce, deve essere registrata a una banca elettronica". Non tutte le compagnie registrate alla banca devono però offrire E-Commerce.
>
>### 2. Vincolo di Equality (Uguaglianza)
>
>* **Simbolo:** $=$
>* **Definizione:** Indica che la popolazione di due ruoli è identica. Formalmente: $pop(r1) = pop(r2)$.
>* **Utilizzo:** Stabilisce una relazione "se e solo se". Un oggetto gioca il ruolo $r1$ se e solo se gioca anche il ruolo $r2$. In pratica, l'oggetto deve partecipare a entrambi i fatti oppure a nessuno dei due.
>* **Esempio:** Una *Person* può avere un *Username* ed essere autenticata da una *Password*. Il vincolo di uguaglianza impone che una persona o possiede entrambe le credenziali (Username e Password) o non ne possiede nessuna.
>
>### 3. Vincolo di Exclusion (Esclusione)
>
>* **Simbolo:** $\otimes$ o $X$
>* **Definizione:** Indica che le popolazioni dei due ruoli sono mutuamente esclusive, ovvero la loro intersezione è vuota. Formalmente: $pop(r1) \cap pop(r2) = \emptyset$.
>* **Utilizzo:** Serve a impedire che un oggetto partecipi contemporaneamente a due fatti incompatibili. Affinché il vincolo abbia senso logico, i ruoli coinvolti devono essere **opzionali**; se fossero obbligatori, il vincolo renderebbe impossibile la popolazione del database.
>* **Esempio:** Un *Loan* (prestito) può essere in stato "pending" ($r1$) oppure "open" ($r2$) per un cliente. Il vincolo di esclusione assicura che un prestito non possa essere contemporaneamente in attesa e aperto.
>
>### Combinazioni e Note Aggiuntive
>
>* **Exclusive-Or (XOR):** È la combinazione di un vincolo di **Esclusione** e un vincolo di **Obbligatorietà Disgiuntiva** (Inclusive Or). Impone che ogni oggetto debba giocare *esattamente uno* dei ruoli specificati (né zero, né più di uno).
>* **Vincoli di Coppia (Pair constraints):** I vincoli di set-comparison non si applicano solo a singoli ruoli, ma possono essere estesi a **tuple di ruoli**. Ad esempio, un vincolo *Pair-subset* può stabilire che se una persona gestisce (*manages*) una compagnia, allora deve anche lavorarci (*works in*): la coppia (Persona, Compagnia) nella relazione "gestisce" deve esistere anche nella relazione "lavora in".

### **Objectification (Nested Object Types)**: Cos'è l'oggettivazione di un fatto e quando è necessaria?

>L'**oggettivazione** (nota anche come *Objectification*, *Nesting* o *Reificazione*) è un costrutto fondamentale in ORM che consiste nel trattare una relazione tra oggetti come se fosse essa stessa un oggetto.
>
>Dal punto di vista linguistico, corrisponde alla **nominalizzazione**, ovvero l'atto di trasformare un predicato verbale in un sostantivo (ad esempio, il fatto che una persona "lavora" in un'azienda diventa l'oggetto "Impiego"). Graficamente, si rappresenta circondando la relazione coinvolta con un rettangolo smussato.
>
>Ecco in dettaglio quando è necessaria e come differisce dalle relazioni n-arie (approccio *flattened*):
>
>### 1. Quando è necessaria l'oggettivazione?
>
>L'oggettivazione è necessaria quando vogliamo affermare qualcosa *riguardo* a un'istanza di una relazione esistente. In pratica, si usa quando una relazione deve giocare un ruolo all'interno di un altro fatto.
>
>I casi d'uso principali includono:
>
>* **Attribuire proprietà a una relazione:** Se esiste il fatto "Persona lavora in Azienda" e si vuole specificare il *Salario* o la *Data di Inizio* di quel rapporto lavorativo, è necessario reificare la relazione "lavora in" nell'oggetto "Impiego" (Employment). A questo punto, l'oggetto "Impiego" può essere collegato all'oggetto "Salario" tramite una nuova relazione.
>
>* **Gestire relazioni complesse (es. Recensioni):** Se un "Impiegato" scrive una recensione per un "Prodotto" e assegna un "Punteggio", la relazione "scrive recensione per" viene oggettivata in "Recensione" (*Review*). Questo nuovo oggetto "Recensione" diventa l'entità che si lega all'oggetto "Punteggio" (*Score*).
>
>### 2. Differenza tra versione Nested e Flattened
>
>Spesso ci si trova a scegliere tra una versione **Flattened** (relazione ternaria o n-aria, es. Persona-Azienda-Salario collegati insieme) e una versione **Nested** (oggettivazione della relazione binaria Persona-Azienda, collegata poi a Salario).
>
>È fondamentale notare che le due versioni **non sono sempre equivalenti**:
>
>* **Equivalenza:** Lo sono solo se il ruolo giocato dalla relazione oggettivata verso il terzo oggetto è **obbligatorio** (Mandatory Role). Ad esempio, se per ogni "Impiego" deve *necessariamente* esistere un "Salario", allora la versione oggettivata e quella ternaria sono semanticamente simili.
>* **Preferenza per il Nesting:** L'oggettivazione è preferibile o necessaria quando il ruolo aggiuntivo è **opzionale** o quando l'associazione oggettivata deve partecipare a molteplici altri fatti.
>
>### 3. Oggettivazione e Indipendenza
>
>Le associazioni oggettivate sono spesso modellate come **entity type indipendenti** (marcate con **!**). Questo approccio permette di registrare l'esistenza della relazione (es. "Impiego" o "Meeting") prima ancora di conoscere tutti i dettagli accessori o indipendentemente dal fatto che partecipi ad altre relazioni in quel momento.
>
>### 4. Traduzione nel Database (Relational Mapping)
>
>In fase di mapping relazionale, un'oggettivazione viene trattata inizialmente come una "black box": la sua chiave primaria è composta dalla combinazione delle chiavi degli oggetti che formano la relazione base. Successivamente, questa chiave composta viene usata per mappare i legami con gli altri oggetti (es. il Salario).

### **Entity Type vs Value Type**: Qual è la differenza concettuale tra un oggetto dotato di identità e un valore puro?

>La distinzione concettuale tra **Entity Type** (Tipo Entità/Oggetto) e **Value Type** (Tipo Valore) è fondamentale per la modellazione dell'Universo del Discorso (UoD), che viene partizionato proprio in queste due categorie esclusive ed esaustive.
>
>Differenze principali:
>
>**1. Identità e Autoriferimento**
>
>* **Value Type:** Un valore possiede un riferimento "auto-identificante" (self-identifying reference). Questo significa che il valore è definito da se stesso (es. il numero 30, la stringa "Lee", un codice fiscale) e non ha bisogno di altro per essere identificato. I valori sono essenzialmente costanti, come stringhe di testo o numeri.
>* **Entity Type:** Un'entità è un concetto le cui istanze sono oggetti individuali e identificabili che esistono nel dominio. Un'entità non è auto-identificante; per fare riferimento a essa è necessario utilizzare una "descrizione definita" che combina un valore, il tipo di entità e un *reference mode* (il modo in cui il valore si riferisce all'entità).
>
>**2. Rigidità vs Mutabilità**
>
>* **Value Type:** I valori sono considerati **rigidi**. Un numero o una stringa non cambiano la loro natura.
>* **Entity Type:** Le entità tipicamente **evolvono nel tempo**. Un oggetto (es. una persona, un ordine, un computer) può cambiare stato o proprietà pur mantenendo la sua identità, mentre un valore rimane immutabile.
>
>**3. La distinzione Uso/Menzione**
La differenza si chiarisce con la distinzione linguistica tra l'uso di un termine e la sua menzione:
>
>* Un'entità viene **referenziata da** un valore rigido.
>* Utilizzare solo un valore non è sufficiente per definire un'entità a causa dell'ambiguità referenziale (ad esempio, la stringa "Lee" è un valore, ma non sappiamo se si riferisce a una persona, a un cognome, o a un luogo senza un contesto).
>
>**Esempio Pratico:**
>
>* **Valore:** La stringa `'Lee'` o il codice `'E301'` sono valori puri (Value Types).
>* **Entità:** *"La Persona con cognome Lee"* è un'entità. Qui l'oggetto "Persona" è identificato tramite il valore `'Lee'` usando il *reference mode* "surname". Analogamente, *"La Stanza con codice E301"* è un'entità distinta dal semplice valore `'E301'`.

### **Vincoli di Mandatory Role**: Come si definisce un ruolo obbligatorio e come differisce dal vincolo di unicità?

>Basandosi sulle fonti fornite, ecco la definizione di vincolo di ruolo obbligatorio e la sua differenza rispetto al vincolo di unicità.
>
>### 1. Definizione di Ruolo Obbligatorio (Mandatory Role)
>
>Un vincolo di ruolo è definito **obbligatorio** per un *object type* se e solo se ogni singola istanza di quell'oggetto presente nel database deve necessariamente giocare quel ruolo.
>
>* **Significato formale:** Per ogni stato della base di dati, la popolazione del ruolo ($r$) coincide con l'intera popolazione dell'object type ($A$) a cui è collegato. In formule: $pop(r) = pop(A)$.
>* **Implicazione semantica:** Indica una cardinalità di **"almeno uno"** ($\ge 1$). Ogni oggetto deve partecipare alla relazione specificata per poter esistere nel sistema.
>* **Rappresentazione:** Graficamente viene indicato con un pallino pieno (role dot) sulla linea che collega l'object type al ruolo.
>* **Impatto sugli aggiornamenti:** Questo vincolo influenza le operazioni di inserimento. Ad esempio, non è possibile inserire un nuovo *TuteGroup* nel sistema se non si specifica contestualmente il *Program* a cui appartiene, se tale ruolo è obbligatorio.
>
>Esistono anche **vincoli obbligatori disgiuntivi** (Disjunctive Mandatory Constraint), i quali stabiliscono che un oggetto deve giocare *almeno uno* tra un insieme di ruoli specificati (unione delle popolazioni dei ruoli), rappresentati graficamente da un cerchio collegato ai ruoli coinvolti.
>
>### 2. Differenza con il Vincolo di Unicità (Uniqueness Constraint)
>
>La differenza sostanziale risiede nella quantità di volte in cui un oggetto può o deve partecipare a una relazione:
>
>* **Vincolo di Unicità (UC):** Stabilisce che un oggetto può giocare un determinato ruolo **al più una volta** ($\le 1$). Serve a garantire che non ci siano fatti duplicati o che una relazione sia funzionale (es. "una persona ha *un solo* codice fiscale").
>* **Vincolo Obbligatorio:** Stabilisce che un oggetto deve giocare il ruolo **almeno una volta** ($\ge 1$). Serve a garantire l'esistenza della relazione per ogni istanza (es. "ogni impiegato *deve* avere un contratto").
>
>### 3. Combinazione: "Exactly One"
>
>I due vincoli lavorano spesso insieme. Quando su un ruolo insistono sia un vincolo di unicità che un vincolo di obbligatorietà, si ottiene la condizione di **"Esattamente uno"** (Exactly One).
>
>* Il vincolo di unicità impone "al più uno".
>* Il vincolo obbligatorio impone "almeno uno".
>* **Risultato:** Ogni oggetto partecipa alla relazione esattamente una volta ($= 1$).
>
>Un esempio riportato è quello di un *TuteGroup* e un *Program*: se il vincolo di unicità dice che un gruppo ha al più un programma, e il vincolo obbligatorio dice che deve averne uno, allora ogni gruppo appartiene esattamente a un programma.

## 3. RMAP

### **Algoritmo RMAP**: come vengono gestite le **associazioni 1 a 1**? (Analisi dei quattro casi)

>Nell'ambito dell'algoritmo **RMAP** (Relational Mapping), la traduzione delle associazioni uno a uno (1:1) mira a bilanciare l'efficienza (riducendo il numero di tabelle e join) con la minimizzazione dei valori nulli e delle ridondanze.
>
>La procedura per determinare in quale tabella raggruppare la relazione (o se crearne una nuova) si basa sull'analisi di **quattro casi** specifici, determinati dalla presenza di altri ruoli funzionali giocati dagli *object type* coinvolti e dai vincoli di obbligatorietà (*mandatory roles*).
>
>### 1. Un solo lato gioca altri ruoli funzionali
>
>In questo scenario, uno dei due *object type* coinvolti nella relazione 1:1 partecipa ad altre relazioni (e quindi diventerà una tabella), mentre l'altro no (spesso è un semplice *value type* o un nodo "foglia").
>
>* **Soluzione:** Si raggruppa la relazione nella tabella dell'*object type* che gioca altri ruoli funzionali (l'entità principale).
>* **Vincoli:** L'informazione della relazione 1:1 viene inserita come colonna e impostata come chiave (o con un vincolo di unicità `U1`) per evidenziare che i valori non possono ripetersi.
>
>### 2. Entrambi i lati giocano altri ruoli, ma solo uno è obbligatorio
>
>Entrambi gli *object type* diventano tabelle (perché coinvolti in altri ruoli funzionali), ma la relazione 1:1 ha un vincolo di obbligatorietà (*mandatory*) solo su un lato.
>
>* **Soluzione:** Si raggruppa la relazione nella tabella dell'*object type* che possiede il **vincolo di obbligatorietà**.
>* **Motivazione:** Questa scelta elimina i valori nulli (NULL) nella chiave esterna, poiché per ogni istanza di quella tabella deve esistere per forza l'associazione.
>* **Vincoli:** Si impone un vincolo di chiave esterna verso l'altra tabella.
>
>### 3. Entrambi i lati giocano altri ruoli e sono entrambi obbligatori
>
>Entrambi gli *object type* sono tabelle e la relazione è obbligatoria per ambedue le parti (relazione simmetrica obbligatoria).
>
>* **Soluzione:** La scelta del lato su cui raggruppare è arbitraria (scelta del modellatore), oppure si possono unire le tabelle se concettualmente appropriato.
>* **Vincoli:** Poiché le stesse informazioni sono presenti da entrambe le parti, si impone un vincolo di chiave esterna doppio o un controllo specifico per mantenere la coerenza 1:1.
>
>### 4. Entrambi i lati giocano altri ruoli e nessuno è obbligatorio
>
>Entrambi gli *object type* sono tabelle, ma la relazione è opzionale per entrambe le parti (0..1 a 0..1). Questo implica la presenza inevitabile di valori nulli.
>
>* **Soluzione:** Si raggruppa dal lato che **minimizza i valori nulli**. Si sceglie cioè la tabella corrispondente all'entità che ha più probabilità di partecipare alla relazione (es. è più probabile che una *Company* abbia un *CEO* piuttosto che una *Persona* sia un *CEO*).
>* **Alternativa:** Se le probabilità sono simili o si vuole evitare del tutto l'uso di NULL, si può creare una **terza tabella separata** dedicata esclusivamente alla relazione 1:1, collegando le due entità tramite chiavi esterne.
>
>### Sintesi della Strategia
>
>La strategia generale riassuntiva per le associazioni 1:1 segue questo ordine di priorità:
>
>1. Se solo un *object type* ha altri ruoli funzionali, raggruppa su quello.
>2. Se entrambi hanno ruoli funzionali ma solo uno è obbligatorio nella relazione, raggruppa sul lato obbligatorio.
>3. Se nessuno ha altri ruoli funzionali, mappa la 1:1 in una tabella separata.
>4. In tutti gli altri casi (es. entrambi opzionali o entrambi obbligatori), la scelta è delegata al modellatore per ottimizzare i NULL o la semantica.

### **Pool vs Lane**: Qual è la differenza semantica tra una Pool e una Lane?

>La differenza semantica tra una **Pool** e una **Lane** risiede nel livello di indipendenza del partecipante rappresentato e nel modo in cui il processo è strutturato e connesso al suo interno.
>
>### 1. Definizione e Ruolo Organizzativo
>
>* **Pool (Partecipante Indipendente):** Rappresenta un partecipante indipendente (ad esempio un'azienda, un cliente, un fornitore) o una classe di risorse specifica che possiede la propria specifica di processo aziendale. Ogni Pool agisce come contenitore per un singolo processo distinto. Un Pool può essere rappresentato come "white-box" (mostrando il processo interno) o "black-box" (nascondendo i dettagli interni, usato spesso per attori esterni).
>* **Lane (Suddivisione Interna):** Rappresenta una classe di risorse all'interno di uno spazio organizzativo (Pool) che condivide lo stesso processo con altre classi di risorse interne. Le Lane sono suddivisioni di un Pool utilizzate per indicare quale specifica risorsa (es. un ufficio, un dipartimento, un ruolo specifico come "Manager") svolge una determinata attività.
>
>### 2. Relazione con il Processo (Orchestrazione)
>
>* **Pool:** Corrisponde a un'unica orchestrazione di processo. Se un'organizzazione ha un processo diviso tra più ruoli interni, questi devono essere gestiti all'interno di un singolo Pool (diviso in Lane), non attraverso Pool separati, poiché Pool separati implicano processi indipendenti.
>* **Lane:** È solo un meccanismo di partizionamento *interno* per categorizzare le attività (ad esempio per ruolo o dipartimento). Non implica un processo separato; le attività in Lane diverse dello stesso Pool fanno parte dello stesso flusso logico sequenziale.
>
>### 3. Flussi di Comunicazione e Vincoli
>
>La distinzione semantica più evidente si manifesta nelle regole di connessione:
>
>* **Tra Pool diversi (Collaborazione):** È vietato utilizzare un *Sequence Flow* (flusso di sequenza) attraverso i confini di un Pool. La comunicazione tra due Pool distinti può avvenire esclusivamente tramite **Message Flow** (flusso di messaggi), rappresentando una collaborazione tra entità distinte.
>* **Tra Lane dello stesso Pool:** Le attività in Lane diverse sono collegate tramite **Sequence Flow**. Poiché fanno parte dello stesso processo, il token di esecuzione passa da una Lane all'altra senza scambi di messaggi, seguendo la logica di orchestrazione interna.
>
>### Sintesi 2
>
>In sintesi, una **Pool** definisce i confini di un processo completo e di un'entità organizzativa autonoma, mentre una **Lane** definisce la responsabilità di esecuzione (chi fa cosa) all'interno di quel singolo processo.

### **Topologie di Task**: Differenza tra **User Task**, **Service Task**, **Manual Task**, **Script Task**

>La distinzione tra le diverse topologie di Task in BPMN (Business Process Model and Notation) si fonda principalmente sul soggetto che esegue l'attività (uomo o sistema) e sul livello di interazione con il Sistema Informativo (IS).
>
>Ecco le differenze specifiche riportate nei documenti:
>
>### 1. User Task (Attività Utente)
>
>* **Definizione:** È un compito svolto sotto la responsabilità di un essere umano che interagisce con il sistema informativo.
>* **Caratteristiche:** Corrisponde a una *User Interaction Activity*. Si verifica quando una persona deve utilizzare il sistema software per completare un'unità di lavoro.
>
>### 2. Service Task (Attività di Servizio)
>
>* **Definizione:** È un compito automatizzato, gestito in autonomia dal sistema senza alcun intervento umano.
>* **Caratteristiche:** Rientra nella categoria delle *System Activity*. In questo caso, il sistema informativo esegue l'operazione in background (es. invocare un servizio web o un'applicazione esterna).
>
>### 3. Manual Task (Attività Manuale)
>
>* **Definizione:** È un'attività che non è supportata dal sistema informativo.
>* **Caratteristiche:** Viene svolta fisicamente da una persona senza l'ausilio diretto del sistema (es. caricare un camion, installare un pezzo fisico). Queste attività non sono tracciate direttamente dal sistema, a meno che non siano collegate a una notifica sotto forma di attività di interazione umana per confermarne l'esecuzione.
>
>### 4. Script Task
>
>* **Contesto:** Sebbene il termine "Script Task" sia citato nell'elenco delle domande d'esame, i dettagli specifici sulla sua definizione grafica o funzionale distinta non sono esplicitati nella sezione "Basic Task Types" delle slide fornite, che si limitano a definire *Abstract*, *User* e *Service* Task.
>* **Classificazione:** Tuttavia, basandosi sul metamodello fornito, un Script Task ricade nella definizione generale di **System Activity**, essendo un'attività eseguita dal sistema informativo in autonomia, similmente al Service Task, ma tipicamente per operazioni interne (script eseguiti dal motore di processo) piuttosto che servizi esterni.
>
### Tabella Riassuntiva

| Tipo di Task | Esecutore | Supporto Sistema Informativo (IS) |
| :--- | :--- | :--- |
| **User Task** | Umano | Sì (Interazione attiva) |
| **Service Task** | Sistema | Sì (Esecuzione autonoma) |
| **Manual Task** | Umano | No (Attività fisica/esterna) |
| **Script Task** | Sistema | Sì (Esecuzione autonoma interna) |

### **Modellazione dei Dati**: Cosa sono i **Data Objects** e i **Data Stores** e come si collegano alle attività?

>In ambito BPMN (Business Process Model and Notation), la gestione dei dati è fondamentale per descrivere come le informazioni vengono manipolate durante l'esecuzione di un processo. Sebbene il BPMN sia "agnostico" rispetto al dominio (non fornisce un modello dati formale come l'ER o l'ORM), offre costrutti specifici per rappresentare l'input, l'output e la persistenza delle informazioni.
>
>Ecco la distinzione tra **Data Objects** e **Data Stores** e le modalità di collegamento alle attività:
>
>### 1. Data Objects (Oggetti Dati)
>
>I Data Objects rappresentano le informazioni manipolate all'interno del processo. Hanno le seguenti caratteristiche:
>
>* **Variabili Locali e Temporanee:** Sono considerati come variabili locali all'interno di un livello del processo. Puntano a un'unità di informazione temporanea che esiste e vive fintanto che il processo (o la sua istanza) è attivo.
>* **Rappresentazione Grafica:** Sono simboleggiati dall'icona di un foglio di carta (con l'angolo piegato).
>* **Stato dell'Oggetto:** È possibile specificare lo stato in cui si trova l'oggetto in quel momento (es. `Order [paid]` o `Order [finalized]`) tramite un'etichetta tra parentesi quadre sotto il nome dell'oggetto.
>* **Collezioni:** Esiste una variante grafica (tre fogli sovrapposti o simbolo specifico) per rappresentare una *Data Object Collection*, ovvero una variabile che rappresenta un insieme di oggetti.
>
>### 2. Data Stores (Archivi Dati)
>
>I Data Stores rappresentano meccanismi di persistenza delle informazioni.
>
>* **Persistenza e Esternalità:** Si riferiscono a unità di informazione persistenti (es. un database o un archivio fisico). A differenza dei Data Objects, i dati in un Data Store persistono oltre la durata dell'istanza del processo e sono tecnicamente esterni al processo stesso.
>* **Accesso Condiviso:** Essendo persistenti, possono essere manipolati non solo dal processo corrente ma anche da entità esterne o altri processi.
>* **Rappresentazione Grafica:** Sono rappresentati dall'icona di un cilindro (simbolo classico dei database).
>
>### 3. Collegamento alle Attività (Associazioni e Flusso Dati)
>
>I dati si collegano alle attività (Task) o agli eventi tramite **associazioni direzionali** (frecce tratteggiate). La direzione della freccia determina la semantica dell'operazione (lettura o scrittura).
>
>* **Input (Lettura/Query):**
>   * Quando la freccia tratteggiata parte dal *Data Object* (o *Data Store*) e punta verso l'attività.
>   * Questo indica che l'attività legge il dato come input. Nel caso dei Data Store, questa associazione denota una **query** per recuperare informazioni.
>   * La fonte semplifica il concetto grafico dicendo: "se [la freccia] esce [dal documento] indica che leggo".
>
>* **Output (Scrittura/Aggiornamento):**
>   * Quando la freccia tratteggiata parte dall'attività e punta verso il *Data Object* (o *Data Store*).
>   * Questo indica che l'attività produce o modifica quel dato (output). Nel caso dei Data Store, questa associazione denota un **aggiornamento** (update) delle informazioni persistenti.
>   * La fonte descrive graficamente: "una freccia che entra nel documento indica che ci scrivo".
>
>**Il Concetto di Data Flow:**
La combinazione di un'associazione di output da un'attività verso un oggetto, seguita da un'associazione di input da quell'oggetto verso un'attività successiva, crea un **Data Flow** (flusso di dati). Questo mostra come l'informazione viene passata e trasformata attraverso la sequenza delle attività del processo.

### **Messaggi vs Flussi di Sequenza**: Quando si usa un Message Flow invece di un Sequence Flow?

>La scelta tra l'uso di un **Sequence Flow** (flusso di sequenza) e un **Message Flow** (flusso di messaggio) dipende strettamente dai confini organizzativi e dal tipo di interazione che si sta modellando. La regola d'oro distingue tra **orchestrazione** interna e **collaborazione** esterna.
>
>### 1. Quando usare un Sequence Flow (Freccia continua)
>
>Si utilizza il **Sequence Flow** per definire l'**orchestrazione** del processo, ovvero il flusso di controllo logico ed esecutivo.
>
>* **Ambito Interno:** Si usa esclusivamente **all'interno di un singolo Pool** (o all'interno di un singolo processo) per collegare attività, gateway ed eventi che vengono eseguiti sotto la stessa unità di orchestrazione.
>* **Ordine di Esecuzione:** Rappresenta l'ordine in cui le attività vengono eseguite. Tutte le attività, i gateway e gli eventi di un processo devono trovarsi su una catena continua di flussi di sequenza.
>* **Vincoli Rigidi:**
>   * Un Sequence Flow **non deve mai attraversare i limiti di un Pool**.
>   * Un Sequence Flow **non deve mai attraversare i limiti di un Sottoprocesso**; può solo puntare al confine del sottoprocesso o connettere elementi al suo interno, rimanendo confinato nel suo livello specifico.
>
>### 2. Quando usare un Message Flow (Freccia tratteggiata)

Si utilizza il **Message Flow** per modellare la **comunicazione** e l'interazione tra entità distinte (Collaborazione).
>
>* **Tra Partecipanti Diversi:** Si usa quando due processi separati (rappresentati da due **Pool** distinti) devono scambiarsi informazioni o segnali. Rappresenta una richiesta o una notifica inviata da un partecipante a un altro (es. un Cliente e un Fornitore).
>* **Collaborazione:** È l'unico mezzo consentito per collegare due Pool separati. Definisce i messaggi scambiati tra processi che procedono in parallelo.
>* **Vincoli Rigidi:**
>   * Un Message Flow **non deve mai collegare due nodi all'interno dello stesso Pool**. Due elementi appartenenti allo stesso processo (orchestrati congiuntamente) non possono essere interconnessi tramite un flusso di messaggi.
>   * Un Message Flow non può collegarsi direttamente a un **Gateway** o a un **Data Store**.
>   * Può collegare solo attività, eventi di messaggio/multipli o Pool "black-box" (scatola nera).
>
### Sintesi delle Regole di Connessione

| Tipo di Flusso | Rappresentazione Grafica | Ambito di Utilizzo | Regola "MAI" (Divieti) |
| :--- | :--- | :--- | :--- |
| **Sequence Flow** | Freccia con linea continua | Dentro lo stesso Pool (Orchestrazione) | Mai attraversare i confini di un Pool o di un Sottoprocesso. |
| **Message Flow** | Freccia con linea tratteggiata | Tra due Pool diversi (Interazione/Coreografia) | Mai collegare oggetti dentro lo stesso Pool. |

>In sintesi, se l'attività successiva è svolta dalla stessa entità organizzativa (stesso processo), si usa il **Sequence Flow**; se l'attività richiede di inviare o ricevere dati da un'entità esterna (un altro processo/Pool), si usa il **Message Flow**.

## 4. BPM (Business Process Management)

### Cosa si intende per **approccio sistemico** nello studio di un'azienda? Quali sono i suoi vantaggi e svantaggi?

>### Definizione di Approccio Sistemico
>
>L'approccio sistemico è un metodo di valutazione utilizzato prevalentemente fino agli anni '80, in cui l'azienda viene considerata come un **sistema complesso** assimilabile a una "scatola chiusa" (black box).
In questo modello:
>
>* Il sistema è caratterizzato da un ingresso (input) e un'uscita (output).
>* Il funzionamento interno è approssimato mediante la **teoria delle code**: si ipotizza la presenza di una coda di attesa e di serventi che elaborano le richieste.
>* Non vengono modellate esplicitamente le attività interne; l'attenzione è rivolta ai flussi in entrata e in uscita.
>
>### Metodologia (Leggi di Little)
>
>L'analisi si basa su leggi matematiche, in particolare le **Leggi di Little**, valide in condizioni stazionarie (dove il tasso di arrivo $\lambda$ è circa uguale al tasso di uscita $\lambda'$). Queste leggi mettono in relazione:
>
>* $N$: Numero di oggetti nel sistema.
>* $L$: Numero di oggetti in coda.
>* $\Lambda$: Tempo di ciclo (tempo totale nel sistema).
>* $\mu$: Tasso di servizio.
>
>La relazione fondamentale è $N = \lambda * \Lambda$. Questo permette di calcolare parametri di efficienza, come il tempo di ciclo o il numero di pratiche in lavorazione, conoscendo gli altri valori.
>
>### Vantaggi e Svantaggi
>
>**Vantaggi:**
>
>* **Valutazione dell'efficienza quantitativa:** Permette di calcolare indicatori precisi riguardanti i tempi di attesa, i tempi di ciclo e i carichi di lavoro (es. quante pratiche gestisce un'agenzia in un dato tempo), fornendo dati oggettivi sulle prestazioni del sistema in condizioni stazionarie.
>* **Focus sui parametri macroscopici:** Consente al gestore di focalizzarsi su pochi parametri chiave (es. tasso di arrivo e numero di oggetti) per derivare gli altri indicatori necessari al dimensionamento del sistema (es. stabilità delle code).
>
>**Svantaggi e Criticità:**
>
>* **Visione a "Scatola Chiusa":** Il limite principale è che questo approccio non fornisce alcuna indicazione su *come* l'azienda gestisce le attività interne, né su come essa crei valore per il cliente.
>* **Mancanza di dettaglio sui processi:** È impensabile estendere questo tipo di analisi per modellare le singole attività interne del processo aziendale; il modello rimane troppo astratto rispetto alla realtà operativa.
>* **Eccessiva complessità e scarsa applicabilità:** L'analisi matematica richiesta è spesso troppo complessa e rigida per essere utilizzata come strumento generale per la modellazione e lo studio dei moderni processi aziendali, che richiedono flessibilità e comprensione dei flussi di lavoro.
>
>In sintesi, l'approccio sistemico è stato storicamente superato (o integrato) da visioni più moderne come il *Business Process Management* (BPM), poiché non è in grado di spiegare le dinamiche interne di creazione del valore e risulta inadatto come strumento generale di modellazione.

### **Leggi di Little**: definire la relazione in codizioni stazionarie e il significato dei parametri ($N, L, \lambda, \mu, \Lambda$)

>Le **Leggi di Little** costituiscono il fondamento matematico dell'approccio sistemico per la valutazione delle prestazioni di un processo aziendale. Esse descrivono la relazione tra i flussi in ingresso, i tempi di permanenza e la quantità di lavoro all'interno del sistema.
>
>### Condizioni Stazionarie
>
>Le leggi sono valide in **condizioni stazionarie**, ovvero quando il sistema è stabile. Ciò si verifica quando il flusso in ingresso è bilanciato da quello in uscita, ossia quando il tasso di arrivo ($\lambda$) è all'incirca uguale al tasso di uscita ($\lambda'$):
>$$ \lambda \approx \lambda' $$
>In questo scenario, il numero medio di oggetti nel sistema rimane costante nel tempo.
>
>### Relazioni Fondamentali
>
>Le relazioni principali definite dalle leggi di Little sono,:
>
>1. **Legge sul numero di oggetti nel sistema:**
>    $$ N = \lambda \cdot \Lambda $$
>    Questa formula lega il numero di oggetti presenti nel sistema al tasso di arrivo e al tempo totale che un oggetto trascorre nel sistema.
>
>2. **Legge sul numero di oggetti in coda:**
>    $$ L = \lambda \cdot \Lambda_c $$
>    Questa formula calcola specificamente quanti oggetti sono in attesa, basandosi sul tempo di attesa medio.
>
>### Significato dei Parametri
>
>Ecco la definizione puntuale dei parametri coinvolti, come descritto nelle fonti:
>
>* **$N$ (Numero di oggetti nel sistema):** Rappresenta il *Work In Progress* (WIP), ovvero il totale delle pratiche o degli oggetti presenti nel sistema in un dato momento. È composto dalla somma degli oggetti in coda ($L$) e degli oggetti che stanno venendo serviti ($S$):
>    $$ N = L + S $$
>* **$L$ (Numero di oggetti in coda):** Indica il numero medio di oggetti che si trovano nella coda di attesa, pronti per essere elaborati ma non ancora sotto la responsabilità di un servente.
>* **$\lambda$ (Tasso di arrivo):** È la frequenza con cui i nuovi oggetti (o clienti/pratiche) entrano nel sistema (es. 240 pratiche a settimana). In condizioni stazionarie, corrisponde anche al *throughput* (tasso di uscita).
>* **$\mu$ (Tasso di servizio):** Rappresenta la capacità produttiva dei serventi, ovvero quanti oggetti un servente riesce a elaborare nell'unità di tempo. Il tempo effettivo di servizio per un singolo oggetto è dato da $1/\mu$.
>* **$\Lambda$ (Tempo di ciclo):** È il tempo totale che un oggetto trascorre all'interno del sistema, dall'ingresso all'uscita. È costituito dalla somma del tempo di attesa in coda ($\Lambda_c$) e del tempo di servizio ($1/\mu$):
>    $$ \Lambda = \Lambda_c + \frac{1}{\mu} $$
>
>Queste leggi permettono ai gestori di calcolare un terzo parametro incognito (es. il tempo di ciclo) conoscendo gli altri due (es. tasso di arrivo e numero di oggetti presenti), facilitando il dimensionamento del sistema e la gestione delle code.

### Cos'è l'**organizzazione funzionale** e quali criticità presenta?

>### Cos'è l'Organizzazione Funzionale
>
>L'organizzazione funzionale rappresenta la struttura tradizionale con cui un'azienda si organizza per raggiungere i propri obiettivi. Il suo principio cardine è il **raggruppamento di tutte le attività simili** all'interno dell'azienda.
>
>In questo modello, le **funzioni** sono definite come aggregazioni di uomini e mezzi necessari per gestire lo stesso tipo di risorse e tecnologie. Queste risorse vengono raggruppate in un'unità organizzativa posta sotto un'unica responsabilità (ad esempio: produzione, marketing, contabilità, risorse umane).
>
>### Criticità e Svantaggi
>
>Sebbene sia il modello tradizionale, l'organizzazione funzionale presenta diversi inconvenienti che limitano l'efficienza complessiva e la capacità di adattamento dell'azienda:
>
>1. **Struttura Rigida e Gerarchica:** Favorisce una struttura statica caratterizzata da linee di comando e di controllo rigide, che possono rallentare i processi decisionali.
>2. **Visione a "Compartimenti Stagni" (Silos):** Ogni funzione ha una visione ristretta, focalizzata esclusivamente al proprio interno. Questo porta spesso a comunicazioni insoddisfacenti con le altre funzioni e a una carenza nel coordinamento necessario tra le diverse attività aziendali.
>3. **Ottimizzazione Locale vs Globale:** Il miglioramento dei processi è limitato al livello delle attività gestite dalla singola funzione. Questo approccio parziale può avere effetti negativi a livello globale, poiché l'ottimizzazione di una singola parte non garantisce l'efficienza dell'intero sistema.
>4. **Mancanza di Responsabilità verso il Cliente:** Questo tipo di organizzazione non permette di individuare chiaramente la responsabilità verso il cliente finale, poiché l'attenzione è rivolta all'esecuzione del compito funzionale piuttosto che alla creazione di valore per il cliente.
>
>A causa di questi limiti, si ritiene necessaria una visione dell'azienda più ampia, che superi l'architettura puramente funzionale per abbracciare una gestione basata sui processi.

### **Catena del valore di Porter**: classificazione tra attività primarie e di supporto, e tra attività che aggiungono valore (VA) e non (NVA)

>La **Catena del Valore di Porter** è un modello che descrive l'azienda come un sistema di attività generatrici di valore, finalizzate alla creazione di un prodotto o servizio che soddisfi i desideri del cliente.
>
>### 1. Classificazione basata sul Valore (VA vs NVA)
>
>Il concetto cardine è il **valore** trasferito al cliente finale. Le attività aziendali vengono classificate in base alla loro capacità di contribuire a questo obiettivo:
>
>* **Attività a Valore Aggiunto (VA - Value Adding):** Sono le attività che contribuiscono direttamente alla creazione di valore per il cliente (ad esempio, la realizzazione fisica del prodotto o il servizio clienti).
>* **Attività che Non Aggiungono Valore (NVA - Non-Value Adding):** Sono attività che non incrementano il valore del prodotto per il cliente e che, idealmente, dovrebbero essere eliminate o ridotte al minimo.
>* **Attività a Valore Aggiunto per l'Azienda (VAA):** Le slide introducono anche questa terza categoria (Business Value Adding), riferendosi ad attività che, pur non aggiungendo valore diretto per il cliente, sono necessarie per il funzionamento dell'azienda (es. adempimenti legali o amministrativi).
>
>### 2. Classificazione tra Attività Primarie e di Supporto
>
>Le attività che generano valore (VA) vengono ulteriormente suddivise in due categorie principali, rappresentate graficamente nel diagramma della catena del valore:
>
>#### **Attività Primarie**
>
>Sono quelle direttamente coinvolte nella creazione fisica del prodotto, nella sua vendita e trasferimento al compratore, e nell'assistenza post-vendita. Si dividono in attività relative al **prodotto** e relative al **mercato**. Esse includono:
>
>1. **Logistica in ingresso:** Ricevimento, magazzinaggio e distribuzione degli input.
>2. **Operazioni:** Trasformazione degli input nel prodotto finale.
>3. **Logistica in uscita:** Raccolta, magazzinaggio e distribuzione fisica dei prodotti ai compratori.
>4. **Marketing & Vendite:** Attività per indurre i compratori ad acquistare il prodotto.
>5. **Servizi:** Attività per mantenere o accrescere il valore del prodotto (assistenza post-vendita).
>
>#### **Attività di Supporto**
>
>Sono attività che non contribuiscono direttamente alla creazione fisica del prodotto, ma sono necessarie affinché le attività primarie possano essere svolte nel miglior modo possibile. Esse "attraversano" trasversalmente le attività primarie e includono:
>
>1. **Infrastrutture dell'impresa:** Gestione generale, pianificazione, finanza, affari legali.
>2. **Gestione delle Risorse Umane:** Ricerca, assunzione, addestramento e sviluppo del personale.
>3. **Gestione delle Tecnologie (Sviluppo della tecnologia):** Know-how, procedure, tecnologie di processo.
>4. **Acquisti (Procurement):** Approvvigionamento degli input usati nella catena del valore.
>
>In sintesi, queste attività generatrici di valore producono i **ricavi** per l'azienda, ma consumano risorse determinando i **costi**; il margine (profitto) deriva dalla differenza tra il valore totale generato e il costo complessivo delle attività svolte.

### Qual è la **relazione tra processi** e **organizzazione funzionale**?

>La relazione tra processi aziendali (Business Process) e organizzazione funzionale può essere descritta come un rapporto di **complementarietà** e, allo stesso tempo, di **attraversamento trasversale**.
>
>### 1. Natura Trasversale (Orizzontalità vs Verticalità)
>
>La differenza sostanziale risiede nella direzione del flusso di lavoro rispetto alla struttura gerarchica:
>
>* **Organizzazione Funzionale (Verticale):** Raggruppa le attività e le risorse simili (uomini e mezzi) in unità organizzative specializzate (es. Vendite, Produzione, Magazzino) sotto un'unica responsabilità gerarchica. Questa struttura crea dei "silos" verticali.
>* **Processi (Orizzontale):** I processi sono insiemi di attività interrelate finalizzate a creare valore per il cliente. Essi operano in maniera **trasversale** rispetto alle funzioni: un singolo processo (es. l'evasione di un ordine) parte da un evento esterno (il cliente), "attraversa" diverse funzioni aziendali (passando ad esempio dalle Vendite, alla Produzione, alla Distribuzione) e ritorna al cliente finale con il risultato.
>
>### 2. Complementarietà
>
>Nonostante le differenze, le due visioni non si escludono a vicenda ma sono **complementari**:
>
>* Le **Funzioni** gestiscono le competenze, le risorse e le tecnologie necessarie per svolgere le attività.
>* I **Processi** utilizzano queste attività, orchestrandole in una sequenza logica per raggiungere un obiettivo di business e generare valore.
È utile analizzare il valore delle attività gestite dalle singole funzioni per capire come queste contribuiscano alla catena del valore complessiva del processo.
>
>### 3. Gestione e Responsabilità (Process Owner)
>
>L'introduzione della gestione per processi (BPM) serve a superare i limiti della visione puramente funzionale, che tende a ottimizzare solo localmente (all'interno del proprio reparto) perdendo di vista l'obiettivo finale del cliente.
Per gestire questa complessità, il processo ha un responsabile, il **Process Owner**, che opera in maniera trasversale rispetto alle funzioni gerarchiche, garantendo che le attività svolte nei vari dipartimenti siano coordinate efficacemente per il raggiungimento dell'obiettivo globale.
>
>### Sintesi Visiva
>
>Le fonti descrivono graficamente questa relazione immaginando l'organigramma funzionale come una serie di rettangoli (i dipartimenti) e il processo come una freccia che li attraversa orizzontalmente, collegando le attività svolte in ciascun rettangolo per trasformare l'input del cliente in un output di valore.

### Definizione di **processo aziendale** e delle sue proprietà

>La definizione di processo aziendale e l'analisi delle sue proprietà fondamentali.
>
>### Definizione di Processo Aziendale
>
>Un **Processo Aziendale** (o *Business Process* - BP) è costituito da un insieme di attività (azioni e controlli) tra loro interrelate e svolte in coordinazione all'interno di un ambiente organizzativo e tecnico.
L'obiettivo di queste attività è realizzare un risultato definito e misurabile (un prodotto o un servizio) che trasferisca **valore** al fruitore finale, ovvero il cliente.
>
>Diverse prospettive autorevoli convergono su questa definizione:
>
>* **Weske:** Sottolinea che le attività realizzano congiuntamente un obiettivo di business.
>* **Hammer & Champy:** Evidenziano che il processo prende uno o più input per creare un output di valore per il cliente.
>* **Davenport:** Definisce il processo come un insieme di compiti strutturati per ottenere un risultato definito per un particolare mercato o cliente.
>
>### Proprietà Fondamentali
>
>Un processo aziendale è caratterizzato da proprietà specifiche e ben definite che lo distinguono da una semplice aggregazione di compiti. Le principali proprietà sono,,:
>
>1. **Risposta a un evento (Trigger):** Il processo non avviene a caso, ma risponde a un evento esterno. Un evento è definito come l'accadere, in un preciso istante di tempo, di un fatto rilevante per l'azienda (es. l'arrivo di un ordine).
>2. **Risultato misurabile:** Deve fornire un output (prodotto o servizio) che sia identificabile e misurabile.
>3. **Creazione di Valore:** Deve soddisfare i requisiti dei clienti, trasferendo loro valore.
>4. **Obiettivi:** Il processo è finalizzato al raggiungimento di specifici obiettivi aziendali.
>5. **Consumo di Risorse:** Per la sua esecuzione, il processo consuma risorse aziendali (uomini, mezzi, materiali).
>6. **Vincoli e Regole:** L'esecuzione è vincolata da regole interne ed esterne (leggi, regolamenti, policy aziendali); il processo deve essere progettato per rispettarle e prevedere la gestione delle violazioni.
>7. **Responsabilità (Process Owner):** Il processo ha un responsabile, detto *Process Owner*, che possiede la responsabilità globale del processo stesso e opera in maniera trasversale rispetto alle funzioni gerarchiche dell'azienda.
>
>### Livelli di Astrazione: Intensionale ed Estensionale
>
>Per comprendere appieno la definizione di processo nel contesto dei Sistemi Informativi, è utile distinguere due livelli,:
>
>* **Livello Intensionale (Process Model):** È il modello o lo schema del processo ("blueprint"). Descrive la struttura, le attività e le regole generali.
>* **Livello Estensionale (Process Instance/Case):** Rappresenta l'esecuzione specifica del processo (un "caso"). Ogni caso è un'entità concreta (es. la gestione di *quello* specifico reclamo) che ha un inizio, una fine e una traccia di esecuzione costituita dagli eventi accaduti.
  
### Quali sono gli **obiettivi del BPM** e cos'è l'analisi "**What-if**"?

>### Obiettivi del BPM
>
>Il **Business Process Management (BPM)** è un approccio che utilizza metodi, tecniche e strumenti per la modellazione, l'analisi e l'ottimizzazione dei processi aziendali al fine di raggiungere gli obiettivi strategici dell'azienda.
>
>Gli obiettivi principali del BPM includono:
>
>1. **Comprensione e Allineamento:**
>
>     * Comprendere come organizzare il lavoro e come sono correlate le attività chiave dell'azienda.
>     * Facilitare l'allineamento dei processi gestionali e produttivi agli obiettivi strategici dell'impresa.
>     * Comprendere come le attività si inseriscono nel contesto organizzativo e tecnico.
>
>2. **Ottimizzazione ed Efficienza:**
>
>     * Ottimizzare i processi interni migliorando la qualità e l'efficienza.
>     * Facilitare il flusso del processo tra i partecipanti, cercando di eliminare le attese.
>
>     * Migliorare l'ambiente di lavoro eliminando i passi ripetitivi attraverso un uso intelligente delle tecnologie.
>
>3. **Automazione e Controllo:**
>
>      * Automatizzare il flusso di controllo e la gestione dei documenti all'interno del processo.
>      * Analizzare, modellare e misurare il processo definendo indicatori di efficienza (KPI).
>
>4. **Flessibilità:**
>
>     * Migliorare la flessibilità dell'organizzazione per rispondere rapidamente ai cambiamenti di scenario (mercato, clienti, normative).
>
>### Analisi "What-if"
>
>L'analisi **"What-if"** è una tecnica previsionale che sfrutta il modello del processo per anticipare comportamenti futuri in scenari ipotetici.
>
>* **Definizione:** È l'utilizzo del modello di processo per fare delle previsioni su come il sistema reagirebbe a determinate modifiche o condizioni diverse da quelle attuali.
>* **Contesto di utilizzo:** Si colloca tipicamente nella fase di **Validazione e Simulazione** del ciclo di vita del processo. In questa fase, dopo aver modellato il processo, lo si sottopone a simulazioni di scenari differenti per verificarne la robustezza e le prestazioni prima dell'implementazione effettiva.
>* **Scopo:** Permette all'azienda di valutare l'impatto di cambiamenti (es. aumento del carico di lavoro, riduzione delle risorse, modifica delle regole) in un ambiente simulato, minimizzando i rischi associati a modifiche dirette sui processi reali.

### **Ciclo di vita di un processo**: fasi e motivi della sua introduzione

>### Motivi dell'introduzione del Ciclo di Vita
>
>L'introduzione del ciclo di vita del Business Process (BP) nasce dalla consapevolezza che un processo aziendale non è una struttura statica, ma un'entità che evolve nel tempo.
I motivi principali includono:
>
>* **Adattamento al cambiamento:** Le aziende devono adeguarsi continuamente ai cambiamenti del contesto esterno (clienti, concorrenti, mercato) e interno per restare competitive.
>* **Miglioramento continuo:** A differenza dei vecchi approcci di reingegnerizzazione radicale, il ciclo di vita mira a una valutazione e un monitoraggio costanti per fornire miglioramenti incrementali.
>* **Gestione della complessità:** Serve a gestire il processo dalla sua ideazione fino alla sua esecuzione e dismissione, garantendo allineamento tra strategia e operazioni.
>
>### Fasi del Ciclo di Vita
>
>Il ciclo di vita è un processo iterativo ("closed loop") che permette di affinare continuamente le prestazioni. Le fasi principali sono,,:
>
>1. **Modellazione e Ottimizzazione**
>    * **Attività:** Si inizia costruendo il modello del processo (spesso usando il linguaggio BPMN) e definendo gli indicatori di efficienza (KPI). Il modello viene ottimizzato attraverso analisi previsionali, come l'analisi "what-if".
>    * **Attori:** Analista.
>
>2. **Validazione e Simulazione**
>    * **Attività:** Il modello viene verificato attraverso l'animazione e la simulazione per controllarne la robustezza e l'aderenza alla realtà aziendale prima della messa in opera. Si confrontano i risultati simulati con gli indicatori attuali.
>    * **Attori:** Analista.
>
>3. **Implementazione**
>    * **Attività:** Il modello validato viene "tradotto" nelle specifiche di input comprensibili dal motore di workflow (il sistema software), automatizzando il flusso di controllo.
>    * **Attori:** Sviluppatore.
>
>4. **Esecuzione**
>    * **Attività:** Il motore di workflow gestisce attivamente il processo reale, coordinando le attività e interagendo con i vari partecipanti (attori umani o sistemi).
>    * **Attori:** Gestore.
>
>5. **Monitoraggio**
>    * **Attività:** Poiché il motore traccia tutte le operazioni, questa fase utilizza i dati raccolti per controllare gli indicatori e verificare se le prestazioni rientrano nei livelli previsti. Se si identificano inefficienze o nuove esigenze, si decide di ristrutturare il processo, facendo ripartire il ciclo dalla fase di modellazione.
>    * **Attori:** Analista e Gestore.
  
### Differenza tra **orchestrazione** (privata/pubblica) e **coreografia** (collaborazioni/conversazioni)

>La distinzione tra orchestrazione e coreografia riguarda la prospettiva (interna vs esterna) e il modo in cui vengono gestite le interazioni tra i partecipanti.
>
>### 1. Orchestrazione (Processo)
>
>L'orchestrazione riguarda la **prospettiva intra-organizzativa**. Essa definisce il flusso di controllo logico all'interno di un singolo processo, gestito tipicamente da un motore centrale. Si suddivide in tre tipologie:
>
>* **Processo Privato (Private):** È un processo strettamente interno all'organizzazione.
>   * *Non eseguibile (Abstract):* Usato principalmente a scopo di documentazione.
>   * *Eseguibile:* Contiene tutte le specifiche necessarie (linguaggi concreti per condizioni, loop, scelte) per essere eseguito da un motore di workflow.
>* **Processo Pubblico (Public):** Rappresenta l'interazione tra un processo privato e un'entità esterna. In questo modello, vengono mostrate **solo** le attività interne che sono coinvolte nell'interazione, nascondendo i dettagli privati non rilevanti per l'esterno.
>
>### 2. Coreografia e Collaborazione
>
>Questi concetti riguardano l'interazione tra **due o più entità di business** distinte.
>
>* **Collaborazione (Collaboration):** È l'interazione concreta tra entità diverse. È costituita da multipli processi privati (rappresentati da Pool diversi) che comunicano tra loro attraverso lo scambio di messaggi.
>* **Coreografia (Choreography):** Rappresenta il **contratto** o il comportamento atteso tra i partecipanti che interagiscono.
>   * *Assenza di un gestore centrale:* A differenza dell'orchestrazione, nella coreografia non c'è un orchestratore centrale.
>   * *Struttura:* Simile a un processo, ma ogni "attività" all'interno di una coreografia rappresenta in realtà uno **scambio di messaggi** tra i partecipanti.
>* **Conversazione (Conversation):** Rappresenta la relazione logica implicata dallo scambio di messaggi. Si focalizza sugli artefatti di business (i dati o documenti oggetto dello scambio) e sull'identificazione dei partecipanti che li manipolano attraverso la comunicazione.
>
>**Sintesi della differenza:**
Mentre l'**orchestrazione** definisce "chi fa cosa" all'interno di un'unica organizzazione (controllo centralizzato), la **coreografia** definisce le regole di ingaggio e lo scambio di messaggi tra organizzazioni diverse (senza controllo centralizzato).

### Differenza tra **modello strategico** (BMM), **organizzativo**, **funzioanle** e di **processo**

>La gestione aziendale moderna scompone la complessità dell'impresa in diversi **metamodelli** distinti ma coordinati. Ognuno di essi osserva l'azienda da una prospettiva specifica.
>
>Ecco le differenze sostanziali tra Modello Strategico, Organizzativo, Funzionale e di Processo:
>
>### 1. Modello Strategico (BMM - Business Motivation Model)
>
>Questo modello rappresenta il "perché" e il "dove" l'azienda vuole andare. Definisce le proprietà che i processi devono soddisfare per essere conformi agli obiettivi aziendali.
>
>* **Obiettivo:** Rappresentare la strategia e le motivazioni del business. Costituisce il punto di partenza per ogni iniziativa di miglioramento.
>* **Struttura (BMM):** Si basa sullo standard BMM dell'OMG e distingue tra:
>   * **Fini (Ends):** Cosa l'azienda vuole essere (Visione, Risultati attesi, Goal, Obiettivi).
>   * **Mezzi (Means):** Come l'azienda intende raggiungere i fini (Missione, Strategie, Tattiche, Direttive).
>   * **Valutazioni e Fattori:** Elementi interni o esterni che influenzano il raggiungimento dei fini.
>
>### 2. Modello Organizzativo
>
>Questo modello descrive la struttura "statica" dell'azienda, rispondendo alla domanda "chi fa cosa" e "con quali risorse".
>
>* **Obiettivo:** Definire le funzioni delle varie unità organizzative e le attività associate ad esse, nonché le risorse utilizzate.
>* **Elementi:** Include l'organigramma, le unità organizzative, i ruoli, le persone e le risorse (umane e tecnologiche). Specifica le relazioni gerarchiche e di appartenenza (es. un Ruolo è rivestito da una Persona; una Funzione è svolta da un'Unità Organizzativa).
>* **Relazione con i processi:** Le attività definite in questo modello sono gli elementi di base (i "mattoni") utilizzati poi nella modellazione del processo.
>
>### 3. Modello Funzionale
>
>Descrive il comportamento dell'azienda in termini di scambio di oggetti tra le funzioni, senza però dettagliare la sequenza temporale esecutiva.
>
>* **Obiettivo:** Analizzare lo scambio di input e output (informazioni, documenti, prodotti) tra le funzioni, tenendo conto delle risorse impegnate e dei vincoli (regole aziendali).
>* **Linguaggio:** È tipicamente rappresentato tramite il linguaggio **IDEF0**.
>* **Struttura:** Utilizza una rete funzionale gerarchica. Ogni funzione è vista come un blocco che trasforma Input in Output, controllata da Vincoli (frecce dall'alto) e supportata da Risorse/Meccanismi (frecce dal basso).
>
>### 4. Modello di Processo
>
>A differenza dei precedenti (che sono essenzialmente statici), questo modello descrive la **dinamica** operativa, ovvero "come" avviene l'esecuzione nel tempo.
>
>* **Obiettivo:** Specificare l'insieme delle esecuzioni possibili (istanze) e l'evoluzione temporale delle attività.
>* **Dinamicità:** Descrive il passaggio attraverso vari stati (es. attiva, in attesa, sospesa) tramite un diagramma stati/transizioni. Le transizioni sono innescate da **eventi** (il verificarsi di fatti in precisi istanti di tempo).
>* **Contenuto:** Mentre il modello funzionale dice *cosa* viene scambiato, il modello di processo orchestra *quando* e in che ordine le attività vengono eseguite per raggiungere il risultato finale.

### Sintesi delle Differenze

| Modello | Domanda Chiave | Focus | Natura |
| :--- | :--- | :--- | :--- |
| **Strategico** | *Perché?* | Obiettivi, Missione, Strategia (BMM) | Astratta/Motivazionale, |
| **Organizzativo** | *Chi?* | Struttura, Unità, Ruoli, Risorse | Statica/Strutturale, |
| **Funzionale** | *Cosa si scambia?* | Scambio di input/output tra funzioni (IDEF0) | Statica/Comportamentale, |
| **Di Processo** | *Come e Quando?* | Esecuzione, Flusso temporale, Eventi, Stati | Dinamica/Esecutiva, |

### Quali sono i **pilastri del BPM**?

>I **pilastri del BPM** (Business Process Management) sono tre elementi fondamentali che, partendo dalle unità atomiche di lavoro (attività o task), gestiscono i diversi tipi di informazioni necessarie al processo.
>
>I tre pilastri sono,,:
>
>1. **Flusso di controllo (Control-flow):**
    Cattura gli ordinamenti consentiti e i vincoli dinamici sugli eventi che tracciano l'esecuzione delle istanze di attività. In termini pratici, definisce come le varie attività vengono coordinate tra loro, stabilendo l'orchestrazione del processo.
>2. **Dati (Data):**
    Riguarda le informazioni che vengono prodotte, trasferite e manipolate dalle istanze di attività, in conformità con i vincoli di uno schema concettuale che modella il dominio. Questo pilastro definisce come deve navigare il flusso dei dati in relazione alle attività stesse.
>3. **Risorse (Resources):**
    Comprende la struttura organizzativa e le risorse che consentono l'esecuzione fisica dei processi di business (BP). Questo aspetto segue specifiche strategie e politiche di allocazione che definiscono le responsabilità e i doveri degli stakeholder (partecipanti) coinvolti.

## 5. BPMN (Business Process Management and Notation)

### Quali sono gli **obiettivi del linguaggio BPMN**?

>L'obiettivo primario del **BPMN** (Business Process Model and Notation) è fornire una notazione che sia comprensibile da tutti gli utenti di business, colmando il divario comunicativo che spesso esiste tra la progettazione dei processi aziendali e la loro implementazione tecnica.
>
>Nello specifico, gli obiettivi del linguaggio possono essere articolati nei seguenti punti fondamentali:
>
>### 1. Standardizzazione e Comunicazione Unificata
>
>Il BPMN mira a fornire alle aziende la capacità di comprendere le proprie procedure interne attraverso una notazione grafica standard. Questo permette di:
>
>* Creare un linguaggio comune comprensibile dagli **analisti di business** (che creano le bozze dei processi), dagli **sviluppatori tecnici** (che implementano la tecnologia per eseguirli) e dai **manager** (che monitorano e gestiscono i processi).
>* Facilitare la comprensione delle collaborazioni e delle transazioni di business tra diverse organizzazioni (B2B).
>
>### 2. Ponte tra Business e IT
>
>Uno degli scopi centrali è colmare il gap tra il design del processo e la sua implementazione. Sebbene il BPMN appaia esternamente familiare alle persone di business (simile ai tradizionali flowcharts), esso è una specifica formale dotata di un metamodello e regole di utilizzo precise, che permettono la validazione e l'automazione dei modelli.
>
>### 3. Interoperabilità e Interscambio (BPMN 2.0)
>
>Con l'evoluzione alla versione 2.0, gli obiettivi si sono estesi per includere aspetti tecnici cruciali per la portabilità:
>
>* **Formato di interscambio:** Abilitare lo scambio di Business Process (BP) e dei layout dei diagrammi tra diversi strumenti di modellazione, preservando l'integrità semantica.
>* **Specifica Unica:** Fornire un'unica specifica che comprenda la notazione, il metamodello e il formato di interscambio.
>
>### 4. Rappresentazione della Logica di Processo
>
>Il BPMN ha l'obiettivo di rappresentare esplicitamente la **logica del processo**, ovvero definire tutte le possibili sequenze di attività (orchestrazione). In questo modo, quando il sistema conosce quali eventi sono accaduti e quali dati sono stati prodotti, sa esattamente cosa deve essere fatto successivamente.
A differenza dei diagrammi di flusso classici, il BPMN è progettato specificamente per catturare:
>
>* Comportamenti innescati da **eventi** (event-triggered behavior).
>* Le **collaborazioni** di business (come processi diversi comunicano tra loro).
>
>### 5. Supporto all'Esecuzione
>
>Infine, un obiettivo tecnico è fornire una semantica di esecuzione, spesso realizzata attraverso la traduzione dei modelli in processi eseguibili (come WS-BPEL), permettendo alle organizzazioni di adattarsi rapidamente a nuove circostanze interne o di mercato.

### Quali sono i possibili modi per **far partire un processo**?

>Un processo BPMN inizia attraverso uno **Start Event** (rappresentato da un cerchio con bordo sottile). È in questo punto che viene creato il **token** che attraverserà il flusso del processo.
>
>Esistono diversi modi e configurazioni per far partire un processo, distinti in base al "trigger" (l'evento scatenante) o alla struttura del modello.
>
>### 1. Tipologie di Trigger (Cosa fa partire il processo)
>
>I principali tipi di eventi di start includono:
>
>* **None Start Event (Start Generico):** Non ha un trigger specificato. Indica che il processo viene avviato manualmente da un utente o che il trigger non è rilevante per la modellazione specifica. È l'unico tipo di start event utilizzabile all'interno di un *sottoprocesso standard*, poiché quest'ultimo viene avviato dal flusso del processo padre.
>* **Message Start Event (Start a Messaggio):** Il processo parte alla ricezione di un messaggio proveniente da un partecipante esterno (un altro pool). È essenziale per modellare reazioni a richieste esterne.
>* **Timer Start Event (Start a Tempo):** Il processo si avvia in uno specifico momento (data/ora) o segue una ricorrenza ciclica (es. "ogni venerdì alle 17:00").
>* **Multiple Start Event:** Raggruppa più trigger all'interno dello stesso evento. Si divide in due casi:
>   * **Multiplo (icona pentagono):** Il processo parte se accade *uno qualsiasi* dei trigger definiti.
>   * **Multiplo Parallelo (icona "+"):** Il processo parte solo quando *tutti* i trigger definiti accadono.
>
>### 2. Configurazioni Strutturali (Come sono disegnati gli start)
>
>Oltre al singolo evento, il processo può essere configurato per gestire avvii complessi:
>
>* **Alternative Start Events (Start Alternativi):** È possibile disegnare più start event distinti per lo stesso processo. Questo si usa quando l'inizio può avvenire tramite canali diversi (es. "Ricezione ordine via Web" vs "Ricezione ordine via Telefono") che poi convergono verso un flusso comune. Basta che si attivi uno solo di questi eventi per creare una nuova istanza del processo.
>* **Event Subprocess Start:** Un sottoprocesso ad eventi (Event Subprocess) risiede all'interno di un processo o sottoprocesso ma non è connesso al flusso sequenziale principale. Esso parte (viene triggerato) solo se si verifica l'evento di start specificato al suo interno (es. un errore o un messaggio urgente). Può essere di tipo **interrompente** (blocca il processo padre) o **non interrompente** (viene eseguito in parallelo).
>
>In sintesi, la scelta del modo in cui far partire un processo dipende dalla natura dell'evento scatenante (manuale, temporale, messaggio) e dalla necessità di modellare canali di ingresso alternativi o paralleli.

### Come si fa partire un **sottoprocesso**?

>L'avvio di un **sottoprocesso** avviene secondo meccanismi precisi che dipendono dal tipo di sottoprocesso (standard o ad eventi) e seguono regole specifiche di gestione del flusso (Token Game).
>
>Ecco come si fa partire un sottoprocesso:
>
>### 1. Avvio tramite Flusso del Processo Padre (Sottoprocesso Standard)
>
>Nel caso di un sottoprocesso standard (embedded o reusable), l'avvio è determinato direttamente dal flusso di controllo del processo genitore.
>
>* **Meccanismo del Token:** Un sottoprocesso si attiva quando il **token** (l'indicatore di esecuzione) del processo principale raggiunge il confine dell'attività che rappresenta il sottoprocesso.
>* **Creazione Istanza:** Il token del processo padre viene messo in attesa sul bordo esterno del sottoprocesso, mentre ne viene creato e attivato immediatamente un altro all'interno per iniziare l'esecuzione.
>* **Tipo di Start Event:** All'interno di un sottoprocesso standard, si deve utilizzare esclusivamente un **None Start Event** (evento di inizio generico, rappresentato da un cerchio sottile vuoto).
>   * Questo indica che il sottoprocesso non attende un trigger esterno (come un messaggio), ma inizia non appena il processo padre lo abilita.
>   * Per evitare ambiguità, un sottoprocesso dovrebbe avere un **singolo** None Start Event. Se ce ne fossero multipli, non sarebbe chiaro se indicano punti di partenza alternativi o rami paralleli.
>
>### 2. Avvio tramite Trigger (Event Subprocess)
>
>Esiste una tipologia specifica chiamata **Event Subprocess** (sottoprocesso ad eventi) che si comporta diversamente.
>
>* **Trigger:** Questo sottoprocesso non è collegato al flusso sequenziale normale tramite archi in ingresso, ma si avvia quando occorre uno specifico evento (trigger) durante l'esecuzione del processo che lo contiene.
>* **Tipo di Start Event:** Utilizza uno start event con un **trigger** specifico (es. Messaggio, Timer o Errore).
>* **Modalità:** Può essere di due tipi:
>   * *Interrupting:* Interrompe il processo padre al verificarsi dell'evento.
>   * *Non-interrupting:* Si avvia in parallelo senza interrompere il processo padre.
>
>In sintesi, mentre i sottoprocessi standard partono "per flusso" usando un *None Start Event*,, i sottoprocessi ad eventi partono "per evento" usando trigger specifici (come timer o messaggi).

### Definizione di **terminazione di un processo** e tipi di **End Event**

>La definizione di terminazione di un processo e la descrizione dei vari tipi di End Event nel linguaggio BPMN.
>
>### Definizione di Terminazione di un Processo
>
>Un processo (o sottoprocesso) non termina necessariamente quando il flusso raggiunge un evento di fine. Secondo la logica del "Token Game", la terminazione di un'istanza di processo avviene quando si verificano le seguenti condizioni:
>
>1. Un flusso di esecuzione (thread) raggiunge un **End Event** e il relativo token viene consumato.
>2. Non ci sono altri token attivi o flussi di esecuzione ancora in corso all'interno dello stesso processo o sottoprocesso.
>
>Se rimangono token non consumati in altri rami paralleli, il processo rimane "attivo" finché tutti i percorsi non hanno raggiunto la loro conclusione. Questa regola generale viene però sovrascritta dallo specifico comportamento del *Terminate End Event*.
>
>### Tipi di End Event
>
>Gli **End Event** sono rappresentati graficamente da un cerchio con un bordo spesso. Indicano la fine di un percorso di esecuzione e possono definire un risultato specifico (il "risultato" è l'equivalente del "trigger" per gli eventi di start).
>
>Ecco le principali tipologie descritte nelle fonti:
>
>* **None End Event (Terminazione Generica):**
>   * **Icona:** Cerchio spesso vuoto.
>   * **Funzione:** Indica la fine del flusso senza produrre alcun risultato specifico o interazione esterna. È buona norma collassare più flussi paralleli che terminano in un "None End" in un unico evento finale per chiarezza.
>
>* **Message End Event (Terminazione con Messaggio):**
>   * **Icona:** Cerchio spesso con una busta nera all'interno.
>   * **Funzione:** Indica che, al raggiungimento della fine del percorso, viene inviato un messaggio a un partecipante esterno. Deve essere sempre collegato tramite un *Message Flow* a un pool o partecipante diverso. Non si devono collegare direttamente più flussi paralleli allo stesso Message End Event.
>
>* **Terminate End Event (Terminazione Forzata):**
>   * **Icona:** Cerchio spesso con un "bulls-eye" (cerchio pieno nero) all'interno.
>   * **Funzione:** Provoca la terminazione **immediata** dell'intero processo (o sottoprocesso).
>   * **Effetto:** A differenza degli altri eventi di fine, questo evento rimuove e distrugge tutti i token attivi in qualsiasi altro ramo parallelo del processo, fermando ogni attività in corso. È tipicamente usato per gestire eccezioni gravi o situazioni in cui il completamento di un ramo rende inutili gli altri (es. un errore critico).
>
>* **Multiple End Event:**
>   * **Icona:** Cerchio spesso con un pentagono all'interno.
>   * **Funzione:** Indica un singolo punto di fine in cui vengono scatenati **tutti** i risultati definiti (ad esempio, l'invio di più messaggi contemporanei o l'attivazione di più segnali).
>
>* **Error End Event:**
>   * **Icona:** Cerchio spesso con una saetta (N) all'interno.
>   * **Funzione:** Lancia un errore specificato (con un codice errore) che deve essere catturato da un livello superiore (pattern *throw-catch*). Quando raggiunto, termina tutti i thread paralleli nel livello corrente e propaga l'errore al processo padre.
>
>Le fonti citano inoltre, tramite tabelle riassuntive, altri tipi di End Event come **Escalation**, **Cancel**, **Compensation** e **Signal**,, che servono rispettivamente per gestire escalation di responsabilità, annullamento di transazioni, compensazioni di attività già svolte o invio di segnali in broadcast.

### Qual è la differenza tra **evento intermedio** e **boundary event**?

>La distinzione tra un evento intermedio "standard" (o nel flusso di sequenza) e un *boundary event* (evento sul confine) risiede principalmente nella loro **posizione** all'interno del diagramma e nel modo in cui influenzano il **flusso di esecuzione** (il *token game*).
>
>### 1. Evento Intermedio (nel flusso di sequenza)
>
>Gli eventi intermedi sono rappresentati da un doppio cerchio e indicano che qualcosa accade durante l'esecuzione del processo (tra l'inizio e la fine).
Quando un evento intermedio è posizionato direttamente sul flusso di sequenza principale:
>
>* **Comportamento (Catching):** Se è un evento di *catch* (ricezione), il processo si **arresta** quando il token raggiunge l'evento. Il token rimane bloccato in quel punto finché non si verifica il trigger specifico (es. ricezione di un messaggio, scadenza di un timer). Solo allora il processo riprende.
>* **Comportamento (Throwing):** Se è un evento di *throw* (lancio), il token attiva l'evento (es. invia un messaggio), completa l'azione immediatamente e prosegue nel flusso senza fermarsi.
>
>### 2. Boundary Event (Evento sul Confine)
>
>Un *boundary event* è tecnicamente un evento intermedio di tipo *catch* che viene però disegnato **sul bordo** (il confine) di un'attività o di un sottoprocesso, anziché nel flusso sequenziale.
>
>* **Comportamento (Ascolto):** Il processo non si ferma per attendere l'evento. Mentre l'attività a cui l'evento è attaccato viene eseguita, l'evento rimane "in ascolto" (attivo in background).
>* **Attivazione:** L'evento è sensibile al trigger solo per la durata dell'attività. Se l'attività termina senza che l'evento accada, l'evento viene disattivato e il processo segue il flusso normale (normal flow).
>* **Flusso di Eccezione:** Se l'evento si verifica mentre l'attività è ancora in corso, viene attivato un percorso alternativo chiamato "flusso di eccezione" (exception flow).

### Tabella di sintesi delle differenze

| Caratteristica | Evento Intermedio (in flusso) | Boundary Event (sul confine) |
| :--- | :--- | :--- |
| **Posizione** | Sul flusso di sequenza (tra due attività). | Attaccato al bordo di un'attività o sottoprocesso. |
| **Azione del Token** | Il token arriva e **aspetta** (se catch). | Il token è dentro l'attività; l'evento **monitora** dall'esterno. |
| **Scopo principale** | Rappresentare un passo sequenziale o un'attesa obbligatoria. | Gestire eccezioni, eventi esterni o timeout durante l'esecuzione di un lavoro. |
| **Continuazione** | Prosegue lungo lo stesso flusso. | Devia verso un flusso di eccezione alternativo. |

>### Tipologie di Boundary Event
>
>È importante notare che i *boundary event* possono avere due comportamenti distinti in base alla loro configurazione grafica:
>
>1. **Interrupting (Linea continua):** Se l'evento accade, l'attività a cui è attaccato viene **immediatamente interrotta** e il flusso prosegue solo lungo il percorso dell'evento.
>2. **Non-Interrupting (Linea tratteggiata):** Se l'evento accade, l'attività principale **continua** normalmente, ma viene generato un nuovo token parallelo che percorre il flusso dell'evento (utilizzato ad esempio per inviare notifiche di ritardo senza bloccare il lavoro).

### Boundary event: differenza tra modalità **interrompente** e **non interrompente**

>La differenza fondamentale tra un *boundary event* (evento sul confine) in modalità **interrompente** e uno in modalità **non interrompente** risiede nel modo in cui viene gestita l'attività a cui l'evento è allegato e nel comportamento del flusso dei token (il *Token Game*).
>
>Ecco i dettagli distintivi:
>
>### 1. Modalità Interrompente (Interrupting)
>
>In questa configurazione, il verificarsi dell'evento ha la priorità assoluta sull'esecuzione dell'attività.
>
>* **Comportamento:** Se l'evento scatta (trigger) mentre l'attività è ancora in corso, l'attività viene **immediatamente terminata**. Tutto il lavoro associato a essa si ferma.
>* **Token Game:** Il token che si trovava all'interno dell'attività viene consumato (rimosso). Un nuovo token viene generato e si sposta lungo il **flusso di eccezione** (la freccia in uscita dall'evento sul confine). Di conseguenza, il flusso prosegue *solo* lungo la via indicata dall'evento, abbandonando il percorso normale.
>* **Rappresentazione Grafica:** È rappresentato da un doppio cerchio con linea **continua** (solid line).
>* **Utilizzo tipico:** Gestione di errori critici o timeout che rendono inutile il proseguimento dell'attività (es. "Tempo scaduto", "Errore grave").
>
>### 2. Modalità Non Interrompente (Non-Interrupting)
>
>In questa configurazione, l'evento gestisce una situazione collaterale senza fermare il lavoro principale.
>
>* **Comportamento:** Se l'evento scatta mentre l'attività è in corso, l'attività principale **continua normalmente** la sua esecuzione fino al completamento.
>* **Token Game:** Il token originale rimane nell'attività. Contemporaneamente, viene duplicato o generato un **nuovo token** che attiva il flusso di eccezione in parallelo. Il processo avrà quindi due percorsi attivi simultaneamente: il flusso normale dell'attività e il nuovo thread generato dall'evento.
>* **Rappresentazione Grafica:** È rappresentato da un doppio cerchio con linea **tratteggiata** (dashed line).
>* **Utilizzo tipico:** Invio di notifiche o avvisi che non richiedono lo stop del lavoro (es. "Inviare sollecito dopo 3 giorni" mentre si attende una risposta).

### Tabella Riassuntiva 2

| Caratteristica | Interrompente (Solid) | Non Interrompente (Dashed) |
| :--- | :--- | :--- |
| **Attività Principale** | Viene interrotta immediatamente. | Continua l'esecuzione. |
| **Flusso** | Prosegue solo sul flusso di eccezione. | Prosegue su entrambi i flussi (parallelo). |
| **Token** | Il token dell'attività è distrutto. | Nasce un nuovo token parallelo. |
| **Grafica** | Doppio cerchio continuo. | Doppio cerchio tratteggiato. |

>In entrambi i casi, se l'attività termina *prima* che l'evento si verifichi, l'evento sul confine viene disattivato e il processo prosegue esclusivamente lungo il flusso normale.

### Cosa sono i **SESE block** e perché sono rilevanti per i gateway OR?

>I **SESE block** (Single Entry Single Exit) sono frammenti di processo strutturati caratterizzati da un singolo punto di entrata e un singolo punto di uscita, che permettono una composizione ricorsiva dei modelli di processo. Possono rappresentare task singoli, sequenze, scelte o strutture parallele che vengono astratte come sottoprocessi.
>
>La loro rilevanza per i **gateway OR** (Inclusive Gateway) deriva dalla complessità semantica intrinseca di questi connettori, in particolare nella fase di *join*:
>
>* **Problema dell'OR-Join:** A differenza di altri gateway, l'OR-join deve sincronizzare i flussi in arrivo, ma deve attendere solo i token dai percorsi che sono stati effettivamente attivati. Poiché la condizione di scelta non è locale, il gateway deve sapere quali thread sono attivi per non bloccarsi in attesa di token che non arriveranno mai.
>* **Soluzione tramite SESE:** Utilizzando una struttura a blocchi SESE, si garantisce che ogni OR-split abbia un corrispondente OR-join nello stesso blocco. In questo modo, quando l'esecuzione passa attraverso lo split, vengono determinati i rami attivi; grazie alla corrispondenza 1:1 all'interno del blocco, il join "sa" esattamente quanti e quali thread deve sincronizzare.
>* **Semplificazione Semantica:** All'interno di un blocco SESE, la logica dell'OR-join viene semplificata e può essere implementata come una variante di un AND-join che attende solo i rami attivati.
>
>Senza l'utilizzo dei blocchi SESE, la gestione degli OR-join richiede una semantica molto più complessa ("non-local semantics") che implica la verifica dei percorsi a monte per determinare se è possibile che un token arrivi in futuro, esponendo il modello al rischio di paradossi logici (come i "vicious circles").

### Funzionamento del gateway **Inclusive-OR** in modalità split e join (perché è difficile da implementare?)

>Il gateway **Inclusive-OR** (rappresentato da un rombo con un cerchio al suo interno) gestisce situazioni in cui si deve effettuare una scelta che può portare all'attivazione di uno o più percorsi simultaneamente. La sua implementazione è particolarmente complessa a causa della logica necessaria per la sincronizzazione (fase di *join*).
>
>Ecco il funzionamento dettagliato e le problematiche connesse:
>
>### 1. Modalità Split (Divergenza)
>
>Il funzionamento in modalità split è relativamente semplice e intuitivo.
>
>* **Logica:** Quando il flusso arriva al gateway, vengono valutate tutte le condizioni sui flussi in uscita. A differenza dello XOR (che ne sceglie una sola), l'OR-split attiva **tutti** i percorsi per cui la condizione risulta vera.
>* **Vincoli:** È necessario che almeno una condizione sia vera; spesso si definisce un flusso di *default* per gestire il caso in cui tutte le altre condizioni siano false.
>* **Token Game:** Il gateway genera un numero di token pari al numero di condizioni verificate, avviando di fatto dei thread paralleli condizionali.
>
>### 2. Modalità Join (Convergenza)
>
>Il funzionamento in modalità join è dove risiede la complessità formale e implementativa.
>
>* **Logica:** L'OR-join deve sincronizzare i flussi in arrivo, ma, a differenza dell'AND-join (che aspetta tutti i flussi entranti) o dello XOR-join (che passa il primo che arriva), l'OR-join deve attendere **tutti e soli i flussi che sono stati effettivamente attivati**.
>* **Sincronizzazione:** Il gateway attende che arrivino tutti i token "attesi". Una volta arrivati tutti i token dai percorsi attivi, li fonde in un unico token in uscita e prosegue l'esecuzione.
>
>### Perché è difficile da implementare?
>
>La difficoltà nasce dal fatto che il gateway, localmente, non può sapere quali e quanti percorsi sono stati attivati a monte. Questo problema è noto come **semantica non locale** ("non-local semantics").
>
>* **Necessità di "guardare a monte":** Per decidere se procedere o attendere, l'OR-join non può limitarsi a guardare i propri ingressi. Deve analizzare lo stato dell'intero processo (o del diagramma a monte) per verificare se esiste un token in viaggio che potrebbe raggiungere il gateway in futuro.
>* **Definizione formale complessa:** Secondo lo standard BPMN, il gateway si attiva se ha almeno un token in ingresso e *non* esistono altri percorsi attivi che potrebbero portare un altro token al gateway senza passare attraverso il gateway stesso.
>* **Il "Circolo Vizioso":** In configurazioni non strutturate (con cicli o intrecci complessi), questa logica può portare a paradossi logici (vicious circles), situazioni in cui lo stato del gateway dipende da una condizione che il gateway stesso deve risolvere, portando a potenziali deadlock o stati indefiniti.
>
>### Soluzione: SESE Block
>
>Per mitigare questa complessità, si raccomanda l'uso di **SESE Block** (Single Entry Single Exit), ovvero strutturare il processo in modo che a ogni OR-split corrisponda un OR-join dedicato in una struttura a blocchi.
In questo scenario, la semantica diventa semplice: il gateway di join sa esattamente quali "porte" sono state aperte dallo split corrispondente e deve semplicemente attendere quei specifici thread, comportandosi come una variante di un AND-join.

### Cos'è l'**Event-Based Exclusive Gateway**?

>L'**Event-Based Exclusive Gateway** (spesso chiamato semplicemente *Event Gateway*) è un elemento del BPMN utilizzato per gestire punti di decisione in cui il percorso da intraprendere dipende non da dati interni già posseduti dal processo, ma dal verificarsi di un **evento esterno** o temporale.
>
>Ecco le sue caratteristiche fondamentali e il funzionamento:
>
>* **Logica basata sull'attesa:** A differenza del gateway esclusivo classico (XOR) che valuta immediatamente una condizione sui dati, l'Event Gateway ferma il flusso (il token) e si mette in ascolto.
>* **Race Condition (Gara tra eventi):** Il gateway è collegato a due o più rami, ciascuno iniziante con un evento intermedio di tipo *catch* (ad esempio la ricezione di un messaggio o un timer). Si crea una situazione di competizione ("race condition") tra questi eventi: il percorso viene determinato da **quale evento si verifica per primo**.
>* **Esclusività:** Appena il primo evento scatta, il token attraversa quel ramo specifico. Simultaneamente, tutte le altre opzioni in attesa vengono disabilitate e i restanti percorsi ignorati.
>
>**Esempi di utilizzo tipico:**
>Questo gateway è necessario quando la scelta non può essere presa internamente dall'orchestratore del processo ma dipende da fattori esterni. Casi comuni includono:
>
>* **Gestione dei Timeout:** Il processo attende una risposta (messaggio), ma se questa non arriva entro un certo lasso di tempo, scatta un evento *Timer* che devia il flusso su un percorso alternativo (es. invio di un sollecito).
>* **Messaggi Alternativi:** Il processo deve reagire diversamente a seconda del tipo di messaggio ricevuto da un partecipante esterno (es. "Ricevuta risposta ordine" vs "Ricevuto messaggio di errore").

### Differenza e utilizzo di **Escalation**, **Signal** ed **Error event**

>### 1. Error Event (Evento di Errore)
>
>Rappresentato da un cerchio con un fulmine all'interno.
>
>* **Utilizzo:** Gestisce eccezioni critiche o fallimenti che impediscono il normale completamento di un'attività.
>* **Comportamento (Throw):** Quando viene lanciato (solitamente come stato finale di un sottoprocesso o task), termina immediatamente tutti i thread paralleli attivi allo stesso livello del processo.
>* **Propagazione:** Segue una logica strettamente gerarchica (throw-catch). Il segnale di errore viene propagato al livello superiore (genitore). Se il livello genitore possiede un evento di *catch* sul confine con lo stesso codice di errore, il flusso viene deviato verso il percorso di eccezione; altrimenti, l'errore continua a salire ricorsivamente verso i livelli superiori.
>* **Interruzione:** È tipicamente **interrompente**. Un evento di errore sul confine (boundary event) interrompe l'attività a cui è associato, spostando il token sul flusso di eccezione.
>
>### 2. Escalation Event (Evento di Escalation)
>
>Rappresentato da una punta di freccia rivolta verso l'alto.
>
>* **Utilizzo:** Gestisce eccezioni "lievi" o situazioni di business che richiedono attenzione (es. un ritardo, una notifica al manager) ma che non costituiscono un fallimento fatale del processo.
>* **Comportamento:** A differenza dell'errore, l'escalation può essere lanciata nel mezzo di un processo (non solo alla fine) e permette al flusso originale di continuare.
>* **Interruzione:** Viene utilizzata prevalentemente come evento sul confine **non interrompente** (rappresentato con un doppio cerchio tratteggiato). Ciò significa che l'attività principale continua a essere eseguita mentre, in parallelo, viene attivato il flusso di gestione dell'escalation. Tuttavia, se necessario, può essere configurata anche come interrompente.
>* **Propagazione:** Simile all'errore, comunica con i livelli superiori del processo (dal figlio al genitore).
>
>### 3. Signal Event (Evento Segnale)
>
>Rappresentato da un triangolo all'interno del cerchio.
>
>* **Utilizzo:** Serve per la comunicazione in *broadcast* (trasmissione a tutti). Codifica un paradigma di tipo "publish/subscribe".
>* **Portata (Scope):** A differenza di Error ed Escalation che sono limitati alla gerarchia padre-figlio, il Signal è molto più flessibile:
>   * **Inter-processo:** Può inviare segnali tra processi diversi (pool differenti).
>   * **Intra-processo:** Può raggiungere thread paralleli all'interno dello stesso processo.
>* **Disaccoppiamento:** Chi lancia il segnale (thrower) non deve conoscere chi lo riceverà (catcher). Il segnale viene inviato a tutti i partecipanti attivi che sono in ascolto per quel specifico segnale.
>* **Flessibilità:** Può essere usato per terminare selettivamente alcune attività o per avviare nuovi processi tramite uno *Start Signal Event*.

### Sintesi delle differenze

| Caratteristica | Error Event | Escalation Event | Signal Event |
| :--- | :--- | :--- | :--- |
| **Icona** | Fulmine | Freccia in alto | Triangolo |
| **Scopo** | Fallimento critico | Avviso/Eccezione lieve | Comunicazione broadcast |
| **Direzione** | Verticale (dal figlio al padre) | Verticale (dal figlio al padre) | Orizzontale/Globale (tra pool o thread) |
| **Interruzione** | Sì, interrompe l'attività (Interrupting) | Tipicamente No (Non-interrupting) | Dipende dalla configurazione |
| **Destinatari** | Processo genitore (livello superiore) | Processo genitore (livello superiore) | Chiunque sia in ascolto (anche processi esterni) |

### Definizione di **sottoprocessi ad hoc** e **sottoprocessi paralleli**

>### Sottoprocessi Paralleli (Parallel Box)
>
>I sottoprocessi paralleli contengono un insieme di attività che non seguono un ordine di esecuzione sequenziale predefinito, ma sono concepite per essere eseguite in concorrenza (concurrently).
Le loro caratteristiche principali sono:
>
>* **Attivazione:** Quando il sottoprocesso viene avviato, tutte le attività al suo interno vengono abilitate simultaneamente.
>* **Completamento:** Il flusso del processo padre può proseguire solo quando **tutte** le attività contenute nel sottoprocesso parallelo sono state completate.
>
>### Sottoprocessi Ad Hoc (Ad-hoc Box)
>
>I sottoprocessi ad hoc, contrassegnati graficamente dal simbolo della tilde (`~`), rappresentano un'unità di lavoro flessibile in cui il flusso di controllo non è completamente specificato (underspecified). Vengono utilizzati quando l'ordine delle attività varia in base alla situazione specifica e BPMN non riesce a esprimere facilmente logiche che dipendono strettamente dal singolo caso.
>
>Le loro caratteristiche principali sono:
>
>* **Ordine di esecuzione:** Le attività al loro interno non hanno un ordine specificato a priori; la decisione su quali attività eseguire (e in che ordine) viene presa caso per caso ("ad hoc") durante l'esecuzione stessa.
>* **Vincoli:** Secondo la definizione fornita nel testo MDPA, le attività all'interno di questo box hanno un ordine non specificato ma non possono essere eseguite in parallelo. Tuttavia, è possibile inserire flussi di sequenza per modellare specifici vincoli di precedenza.
>* **Terminazione:** A differenza dei sottoprocessi paralleli che richiedono il completamento di tutte le attività, un sottoprocesso ad hoc può essere terminato in qualsiasi momento, purché non vi siano attività al suo interno ancora in esecuzione.

### Descrivere i passi della metodologia **Top-Down Decomposition**

>La metodologia **Top-Down Decomposition** (decomposizione dall'alto verso il basso) è un approccio fondamentale nella modellazione BPMN per gestire la complessità dei processi, garantendo che i modelli rimangano leggibili e comprensibili. L'obiettivo è realizzare modelli gerarchici in cui il diagramma di livello superiore stia in una singola pagina, nascondendo i dettagli nei livelli sottostanti.
>
>La metodologia si articola in **cinque passi principali**:
>
>**1. Definizione dei confini del processo (Start/End)**
Prima di analizzare i dettagli, è necessario avere un'idea chiara di dove il processo inizia e dove finisce.
>
>* Bisogna chiedersi: come inizia il processo? Cosa ne determina la fine? Esistono diversi modi per determinarne la fine?.
>
>**2. Individuazione della mappa ad alto livello (High-Level Map)**
Si identificano le attività principali che compongono il processo.
>
>* Si stila una lista di un numero limitato di attività principali (solitamente una decina, per mantenere la leggibilità).
>* Queste attività fungono da "contenitori stabili" che verranno dettagliati successivamente.
>* Per ogni attività si definiscono: nome, responsabilità, requisiti e condizioni di terminazione.
>
>**3. Creazione del diagramma di livello superiore (Top-Level Process Diagram)**
>Si organizza la mappa definita al passo precedente in un diagramma BPMN coerente.
>
>* Si determina l'evento di inizio (Start Event).
>* Ciascuna delle attività principali individuate viene modellata come un **sottoprocesso collassato** (compresso).
>* Si collegano queste attività utilizzando flussi di sequenza e gateway di base per definire l'orchestrazione generale. In questa fase ci si concentra spesso sui percorsi "felici" (happy paths) prima di gestire le eccezioni.
>
>**4. Espansione dei sottoprocessi (Child-Level Expansion)**
>Si definiscono i dettagli interni di ciascun sottoprocesso in modo ricorsivo.
>
>* Si crea un diagramma separato per ciascun sottoprocesso collassato presente nel livello superiore.
>* Si dettaglia il flusso di lavoro interno fino a quando tutte le attività sono atomiche (task).
>* È cruciale mantenere la **coerenza ("allineamento semantico")** tra i livelli: ad esempio, se un sottoprocesso nel livello padre è seguito da un gateway che testa diverse condizioni di uscita (es. "approvato" vs "rifiutato"), il diagramma del sottoprocesso figlio deve terminare con distinti *End Event* che corrispondono a tali risultati.
>
>**5. Aggiunta del contesto e dei flussi di messaggi**
Si arricchisce il modello chiarendo le interazioni con entità esterne.
>
>* Si aggiungono i *Message Flow* (flussi di messaggio) per mostrare le comunicazioni con altri attori o pool (rappresentati spesso come *black box*).
>* Questo chiarisce il contesto aziendale in cui il processo opera.
>
>Questa metodologia evita l'approccio *bottom-up* (dal basso verso l'alto), che tende a produrre diagrammi "piatti", enormi e difficili da leggere, favorendo invece una struttura gerarchica navigabile.

### Perché suddividere compiti atomici in attività separate in un AND split?

>La suddivisione di compiti in attività separate gestite tramite un **AND split** (Parallel Gateway) risponde a precise necessità logiche e semantiche relative al flusso di controllo del processo.
>
>Ecco i motivi principali per cui si adotta questa struttura:
>
>**1. Rappresentazione dell'indipendenza logica (Interleaving)**
L'utilizzo di un AND split permette di definire che due o più attività sono logicamente indipendenti l'una dall'altra riguardo all'ordine di esecuzione.
>
>* A differenza di un flusso sequenziale (che impone un ordine rigido, es. prima A poi B), l'AND split crea dei thread paralleli.
>* Dal punto di vista della semantica formale (derivata dalle Reti di Petri), questo corrisponde alla **semantica di interleaving**: il parallelismo tra due attività B e C significa che l'esecuzione valida può essere la sequenza "B poi C" oppure "C poi B". Non si impone un ordine, lasciando al sistema o agli esecutori la libertà di agire.
>
>**2. Creazione di thread paralleli (Fork)**
Suddividere i compiti permette di avviare flussi di esecuzione concorrenti.
>
>* Quando il token raggiunge un AND split, il gateway genera un numero di token pari al numero di flussi in uscita, duplicando di fatto il flusso di controllo.
>* Questo consente l'esecuzione simultanea (anche se non obbligatoria) delle attività, diversamente da quanto accadrebbe se fossero raggruppate in un'unica attività atomica o poste in sequenza.
>
>**3. Sincronizzazione obbligatoria (Join)**
La separazione in rami paralleli è funzionale anche alla successiva fase di sincronizzazione.
>
>* Utilizzando un **AND join** corrispondente, il processo si assicura che **tutte** le attività separate siano state completate prima di proseguire.
>* Questo meccanismo è simile al concetto di "Parallel Box" nei sottoprocessi, dove tutte le attività contenute devono essere terminate per concludere il sottoprocesso.
>
>In sintesi, si suddividono i compiti in un AND split per modellare esplicitamente che tali attività devono essere tutte eseguite, ma che non esiste un vincolo di precedenza temporale tra di loro, permettendo esecuzioni sia simultanee che sequenziali in ordine variabile.

## 6. Reti di Petri

### **Definizione formale** di una Rete di Petri

>La **definizione formale** di una Rete di Petri è espressa tramite una quadrupla $(P, T, F, W)$.
>
>Gli elementi che compongono questa quadrupla sono definiti come segue:
>
>* **$P$**: è un insieme finito di **Places** (posti).
>* **$T$**: è un insieme finito di **Transitions** (transizioni), tale per cui l'intersezione tra l'insieme dei posti e l'insieme delle transizioni è vuota ($P \cap T = \emptyset$).
>* **$F$**: rappresenta il **Flow** (flusso), ovvero un insieme di archi che costituisce un sottoinsieme del prodotto cartesiano tra posti e transizioni e viceversa ($F \subseteq (P \times T) \cup (T \times P)$).
>* **$W$**: è la funzione di peso (**Weight**), che associa a ogni arco appartenente al flusso ($F$) un numero naturale positivo ($W : F \rightarrow \mathbb{N} \setminus \{0\}$).
>
>**Caratteristiche e Rappresentazione**
Dal punto di vista grafico e semantico, questi elementi formali corrispondono a un grafo orientato bipartito:
>
>* I **Place** sono rappresentati da cerchi e indicano uno stato raggiunto dal sistema.
>* Le **Transition** sono rappresentate da rettangoli (o quadrati) e indicano un'attività o un evento che causa un passaggio di stato.
>* Gli **Archi** collegano sempre un elemento di un tipo a un elemento dell'altro tipo (da Place a Transition o viceversa) e hanno un peso associato maggiore di 0.
>
>La definizione formale è completata dal concetto di **Marking** (marcatura), che rappresenta lo stato della rete in un dato momento. Un marking $M$ è un **multiset** (multi-insieme) su $P$, che indica quanti *token* (gettoni) sono presenti in ciascun posto della rete.

### Cosa rappresentano i **Place**, le **Transition** e la **funzione di flusso (F)**?

>Ecco cosa rappresentano i tre elementi fondamentali di una Rete di Petri secondo le fonti:
>
>* **Place (Posti):** Sono rappresentati graficamente da **cerchi** e indicano uno **stato** raggiunto dal sistema. Formalmente costituiscono un insieme finito indicati con la lettera $P$. Nel contesto della mappatura dei processi di business, corrispondono agli stati del sistema.
>
>* **Transition (Transizioni):** Sono rappresentate graficamente da **quadrati** (o rettangoli) e indicano un'**attività** che viene svolta, ovvero il momento in cui avviene il passaggio da uno stato all'altro. Formalmente costituiscono un insieme finito indicato con $T$. Rappresentano attività atomiche o eventi nel ciclo di vita di un'attività.
>
>* **Funzione di flusso ($F$):** Rappresenta le relazioni tra i nodi attraverso un insieme di **archi orientati**. Formalmente, $F$ è un sottoinsieme che unisce gli archi che vanno dai posti alle transizioni con quelli che vanno dalle transizioni ai posti ($F \subseteq (P \times T) \cup (T \times P)$). Poiché una rete di Petri è un grafo bipartito, questi archi collegano sempre un elemento di un tipo a un elemento dell'altro tipo (da Place a Transition o viceversa), mai due elementi dello stesso tipo.

### Definizione della **funzione di peso (W)**: dominio e range

>La funzione di peso $W$ (Weight function), che costituisce il quarto elemento della definizione formale di una Rete di Petri $(P, T, F, W)$, è definita come segue,:
>
>$$W : F \rightarrow \mathbb{N} \setminus \{0\}$$
>
>Nello specifico:
>
>* **Dominio:** È l'insieme **$F$** (Flow relation), ovvero l'insieme degli archi orientati che collegano i posti ($P$) alle transizioni ($T$) e viceversa.
>* **Range (Codominio):** È l'insieme dei numeri naturali escluso lo zero ($\mathbb{N} \setminus \{0\}$).
>
>Questa definizione implica che a ogni arco appartenente al flusso ($F$) deve essere associato un peso numerico intero strettamente positivo.

### Definizione di **Present** e **Postset** (Multiset e notazione vettoriale)

>### 1. Multiset (Multi-insieme)
>
>Prima di definire Preset e Postset, è necessario definire il concetto di **Multiset**, poiché essi sono espressi tramite questa struttura matematica.
Un multiset è un insieme su un dato alfabeto in cui ogni elemento può comparire più volte (ha una sua **molteplicità**).
>
>* Può essere visto come una funzione $X: S \rightarrow \mathbb{N}$ che associa a ogni elemento dell'insieme $S$ un numero naturale indicante quante volte quell'elemento è presente.
>* Si rappresentano con parentesi quadre. Per compattezza, si usa la notazione esponenziale (power notation) dove l'esponente indica la quantità. Ad esempio: $[a, a, a, b, c, b]$ viene scritto come $[a^3, b^2, c^1]$.
>
>### 2. Definizione di Preset ($\bullet a$)
>
>Data una Rete di Petri definita dalla quadrupla $(P, T, F, W)$ e un nodo generico $a$ (che appartiene all'unione di Posti $P$ e Transizioni $T$), il **Preset** (o pre-insieme) è definito come il multiset degli elementi $x$ che hanno un arco diretto verso $a$, pesati dalla funzione $W$.
>
>**Formula:**
>$$ \bullet a = [ x^{W(x,a)} \mid W(x, a) \text{ è definito e } (x, a) \in F ] $$
>
>In termini intuitivi, il preset di un nodo elenca tutti i nodi da cui partono archi entranti nel nodo stesso, con una molteplicità pari al peso dell'arco.
>
>### 3. Definizione di Postset ($a \bullet$)
>
>Analogamente, il **Postset** (o post-insieme) di un nodo $a$ è definito come il multiset degli elementi $y$ verso cui è diretto un arco partente da $a$, pesati dalla funzione $W$.
>
>**Formula:**
>$$ a \bullet = [ y^{W(a,y)} \mid W(a, y) \text{ è definito e } (a, y) \in F ] $$
>
>In termini intuitivi, il postset elenca tutti i nodi verso cui il nodo $a$ ha archi uscenti.
>
>### 4. Notazione Vettoriale
>
>La notazione vettoriale è utilizzata spesso per rappresentare il **Marking** (marcatura) della rete in modo compatto, ma si applica concettualmente a qualsiasi multiset definito su un insieme ordinato di posti.
Se si stabilisce un ordine fisso per i posti della rete (es. $p_1, p_2, ..., p_n$), un multiset può essere scritto come un vettore dove l'elemento $i$-esimo corrisponde alla molteplicità (o numero di token) del posto $p_i$.
>
>**Esempio:**
>Se il marking è $M_0 = [p_1^1, p_2^3]$ (ovvero un token in $p_1$ e tre token in $p_2$), la notazione vettoriale corrispondente è:
>$$ M_0 = (1, 3) $$
>
>Questa notazione è fondamentale per calcolare algebricamente la regola di *firing* delle transizioni, confrontando il vettore del Marking corrente con il vettore del Preset della transizione.

### Cos'è il **Marking** e cosa rappresenta intuitivamente?

>Il **Marking** (o marcatura) è un concetto fondamentale nelle Reti di Petri che definisce la configurazione dei **token** (gettoni) all'interno della rete in un dato momento.
>
>**Definizione e Rappresentazione**
Formalmente, un Marking $M$ è un **multiset** (multi-insieme) definito sull'insieme dei posti $P$ della rete. Esso associa a ogni posto un numero naturale che indica quanti token sono contenuti al suo interno.
Esistono due modi principali per rappresentarlo:
>
>* **Elenco con apici:** Una lista dei posti con un apice che indica il numero di token (es. $M_0 = [p_1^1, p_2^3]$ indica un token in $p_1$ e tre in $p_2$).
>* **Notazione vettoriale:** Un vettore dove ogni posizione corrisponde a un posto specifico e il valore numerico indica la quantità di token (es. $M_0 = (1, 3)$).
>
>**Significato Intuitivo**
Intuitivamente, il Marking rappresenta lo **stato del sistema** o lo stato di computazione in un preciso istante.
>
>* È paragonabile a uno **snapshot** (istantanea) che fotografa la situazione di un'istanza di processo.
>* Poiché i token rappresentano i casi che vengono elaborati (il progresso dell'esecuzione), il Marking ci dice esattamente dove si trovano questi casi all'interno del flusso di lavoro e in quali quantità.
>
>**Dinamica del Marking**
Il Marking non è statico ma evolve nel tempo. Partendo da un **Marking iniziale** ($M_0$), la rete esegue delle "transizioni" (firing) che spostano i token da un posto all'altro, generando nuovi marking ($M_1, M_2, ...$).
Nelle *Workflow Net* (reti usate per modellare processi di business), si definiscono due marking speciali che delimitano il ciclo di vita del processo:
>
>1. **Input state ($i$):** Un token nel posto iniziale e zero altrove.
>2. **Output state ($o$):** Un token nel posto finale e zero altrove.

### Cos'è la **Regola di Firing** e quando una transizione è **abilitata**?

>La **Regola di Firing** (regola di scatto) è il meccanismo fondamentale che determina la dinamica e l'evoluzione di una Rete di Petri, stabilendo quali transizioni possono essere eseguite (fare un passo di computazione) e quale sarà il nuovo stato (Marking) della rete dopo l'esecuzione.
>
>**Quando una transizione è abilitata?**
Una transizione $t$ è definita **abilitata** (enabled) se e solo se il Marking corrente $M$ contiene un numero di token sufficiente in tutti i posti di input della transizione (il suo *preset*, indicato con $\bullet t$).
Formalmente, la condizione è:
>$$M \ge \bullet t$$
>Questo significa che, posizione per posizione (cioè per ogni posto), il numero di token presenti nel marking attuale deve essere **maggiore o uguale** al peso dell'arco che collega quel posto alla transizione. Intuitivamente, ci devono essere abbastanza token nei posti in ingresso per soddisfare i pesi degli archi entranti.
>
>**Esecuzione del Firing (Scatto)**
Se una transizione è abilitata, essa *può* scattare (fire). Se più transizioni sono abilitate contemporaneamente, la scelta di quale far scattare è **non deterministica** (token game).
Lo scatto di una transizione $t$ comporta due azioni simultanee:
>
>1. **Consumo:** Rimuove i token dai posti di input in quantità pari ai pesi degli archi entranti.
>2. **Produzione:** Genera nuovi token nei posti di output (il *postset*, indicato con $t \bullet$) in quantità pari ai pesi degli archi uscenti.
>
>**Calcolo del Nuovo Marking**
Il passaggio da un marking $M$ a un nuovo marking $M'$ tramite lo scatto della transizione $t$ (denotato come $(N, M)[t\rangle(N, M')$) si calcola con la seguente formula algebrica,:
>
>$$M' = (M - \bullet t) + t \bullet$$
>
>Dove:
>
>* $M$ è il marking attuale.
>* $\bullet t$ è il preset (token da rimuovere).
>* $t \bullet$ è il postset (token da aggiungere).

### Come cambia la regola di firing in presenza di **omega** ($\omega$)?

>La presenza del simbolo **omega ($\omega$)**, introdotto per gestire le reti di Petri non limitate (*unbounded*) e costruire i grafi di copertura, modifica l'applicazione della regola di firing attraverso l'estensione degli operatori matematici e di confronto sui multiset.
>
>**1. Condizione di Abilitazione (Confronto)**
Per verificare se una transizione è abilitata ($M \ge \bullet t$), le regole di confronto vengono estese come segue:
>
>* $\omega$ è strettamente **maggiore** di qualsiasi numero naturale $n$ ($\omega > n$ per ogni $n \in \mathbb{N}$).
>* $\omega$ è **maggiore o uguale** a se stesso ($\omega \ge \omega$).
>
>Questo implica che se un posto contiene $\omega$ (infiniti token), esso soddisferà sempre il requisito di peso dell'arco in ingresso necessario per abilitare la transizione.
>
>**2. Calcolo del Nuovo Marking (Aritmetica)**
Nel calcolo del nuovo stato dopo lo scatto ($M' = (M - \bullet t) + t \bullet$), si applicano regole aritmetiche specifiche per indicare che un posto illimitato rimane tale per sempre ("An unbounded place will be unbounded forever"):
>
>* **Sottrazione:** $\omega - n = \omega$. Il consumo di token (input della transizione) non riduce l'infinito.
>* **Addizione:** $\omega + n = \omega$. La produzione di nuovi token (output della transizione) non altera l'infinito.
>
>In sintesi, la regola di firing con $\omega$ assicura che il comportamento della rete sia monotono: se una transizione è abilitata in un marking $M$, lo sarà anche in qualsiasi marking che "include" $M$ (e $\omega$ rappresenta l'inclusione di qualsiasi numero intero).

### Come si costruisce un **grafo di raggiungibilità**?

>Come si costruisce un **Grafo di Raggiungibilità** (Reachability Graph) per una Rete di Petri.
>
>Il grafo di raggiungibilità è un sistema di transizioni che rappresenta l'insieme di tutti i possibili marking raggiungibili (stati) e le transizioni che li collegano, a partire da uno stato iniziale.
>
>### Algoritmo di Costruzione
>
>L'algoritmo procede in modo iterativo esplorando i nuovi stati generati dallo scatto delle transizioni abilitate. Dati una rete di Petri $N$ e un marking iniziale $M_0$, i passi sono i seguenti:
>
>1. **Inizializzazione:**
>
>     * Si crea il nodo radice etichettandolo con il marking iniziale $M_0$.
>     * Si inizializza un insieme chiamato `New` inserendo al suo interno solo $M_0$ (`New` = {$M_0$}).
>
>2. **Ciclo di Esplorazione:**
>
>     * Finché l'insieme `New` non è vuoto (cioè finché ci sono stati nuovi da esplorare):
>        1. **Selezione:** Si seleziona un marking $M$ dall'insieme `New`.
>        2. **Verifica Transizioni:** Si controlla quali transizioni $t$ sono abilitate nel marking $M$ (secondo la regola di firing).
>        3. **Esecuzione (per ogni transizione abilitata $t$):**
>            * Si calcola il nuovo marking $M'$ risultante dallo scatto della transizione $t$ su $M$ ($M \xrightarrow{t} M'$).
>            * **Controllo Novità:** Se il marking $M'$ *non* compare già nel grafo:
>                * Lo si aggiunge come nuovo nodo del grafo.
>                * Lo si inserisce nell'insieme `New` (per essere esplorato nei cicli successivi).
>            * **Creazione Arco:** Si disegna un arco orientato dal nodo $M$ al nodo $M'$ etichettandolo con il nome della transizione $t$.
>        4. **Rimozione:** Una volta esplorate tutte le transizioni possibili per $M$, si rimuove $M$ dall'insieme `New`.
>
>### Risultato e Limiti
>
>Il risultato finale è un grafo dove i nodi sono gli stati possibili del sistema e gli archi rappresentano l'evoluzione del processo.
>
>Tuttavia, esiste un problema fondamentale legato alla **limitatezza (boundedness)**:
>
>* Se la rete è **limitata** (bounded), l'algoritmo termina e produce un grafo finito.
>* Se la rete è **illimitata** (unbounded), ovvero i token possono accumularsi all'infinito in alcuni posti, il grafo di raggiungibilità sarebbe infinito e l'algoritmo non terminerebbe mai.
>
>In caso di reti non limitate, per ottenere una rappresentazione finita, si ricorre al **Grafo di Copertura** (Coverability Graph), che utilizza il simbolo $\omega$ per rappresentare l'accumulo infinito di token.

### Qual è la differenza tra **grafo di raggiungibilità** e **grafo di copertura**?

>La principale differenza tra il **grafo di raggiungibilità** e il **grafo di copertura** risiede nella capacità di gestire reti di Petri non limitate (*unbounded*) e nella precisione delle informazioni rappresentate.
>
>**1. Finitudine e Gestione dell'Infinito**
>
>* **Grafo di Raggiungibilità:** Rappresenta l'insieme esatto di tutti i possibili marking (stati) raggiungibili dalla rete. Se la rete è **illimitata** (ovvero i token possono accumularsi all'infinito in alcuni posti), il grafo di raggiungibilità diventa infinito e l'algoritmo per costruirlo non termina mai.
>* **Grafo di Copertura:** È un'**astrazione finita** del grafo di raggiungibilità, introdotta per risolvere il problema dell'illimitatezza. Utilizza il simbolo **$\omega$** (omega) per rappresentare i posti in cui il numero di token cresce indefinitamente. Grazie a questa astrazione, l'algoritmo di costruzione del grafo di copertura termina sempre, anche per reti infinite.
>
>**2. Precisione e Perdita di Informazione**
>
>* **Grafo di Raggiungibilità:** Contiene informazioni precise su ogni stato. Ogni nodo corrisponde a una configurazione esatta di token.
>* **Grafo di Copertura:** A causa dell'uso di $\omega$ (che significa "n token, dove n può essere arbitrariamente grande"), si perde precisione.
>   * Non è possibile usare il grafo di copertura per rispondere a domande sulla **raggiungibilità** esatta di uno stato (es. "Posso arrivare esattamente a 5 token?"), ma solo a domande di "copertura" (es. "Posso arrivare ad avere *almeno* 5 token?").
>   * Reti di Petri diverse potrebbero generare lo stesso grafo di copertura a causa dell'astrazione.
>   * Non si può decidere correttamente la **liveness** (vivacità) di una transizione basandosi solo sul grafo di copertura, poiché un'esecuzione valida sul grafo potrebbe non corrispondere a un'esecuzione reale della rete.
>
>**3. Coincidenza**
I due grafi **coincidono** se e solo se la rete di Petri è **limitata** (*bounded*). In questo caso, non ci sono posti che accumulano token all'infinito, il simbolo $\omega$ non compare, e il grafo di copertura diventa un'esatta rappresentazione del grafo di raggiungibilità.

### Relazione tra Reti di Petri e **linguaggio BPMN** (limiti della traduzione)

>La relazione tra **Reti di Petri** e **BPMN** è fondamentale: le Reti di Petri costituiscono il **fondamento formale** (la semantica) che sta alla base del linguaggio grafico BPMN.
>
>Tuttavia, esistono differenze sostanziali di espressività che generano limiti nella traduzione tra i due formalismi.
>
>### 1. Relazione e Mapping
>
>Il funzionamento del BPMN viene spesso spiegato tramite il "Token Game", un concetto derivato direttamente dalle Reti di Petri, dove i token rappresentano le istanze di processo che attraversano il flusso.
>
>La corrispondenza strutturale tra i due linguaggi è definita come segue:

| Concetto BPMN | Elemento Rete di Petri |
| :--- | :--- |
| **Stato** (inizio/fine/intermedio) | **Place** ($P$, cerchi) |
| **Attività** (Task atomico) | **Transition** ($T$, rettangoli) |
| **Flusso** (Sequence Flow) | **Arco** ($F$, flow) |
| **Caso** (Istanza di processo) | **Token** |
| **Esecuzione** | **Firing** (scatto di una transizione) |

>Inoltre, i costrutti di controllo di base del BPMN (Sequence, AND-split/join, XOR-split/join, Loop) hanno una traduzione diretta in frammenti di Reti di Petri.
>
>### 2. Limiti della Traduzione
>
>Nonostante la forte relazione, la traduzione non è sempre isomorfa o priva di perdite. I principali limiti risiedono nella diversa espressività e nella gestione di dati e logiche complesse.
>
>**A. Il problema del Gateway OR (Inclusive OR)**
Il limite più significativo riguarda il **Gateway OR (Inclusive)**.
>
>* In BPMN, un *OR-Join* deve sincronizzare tutti i token attivi che arrivano dai percorsi scelti a monte. Per funzionare correttamente, il gateway deve "sapere" se aspettare altri token o procedere.
>* Nelle Reti di Petri standard, la regola di firing è **locale**: una transizione scatta se i token sono presenti *ora* nel preset. La transizione non può guardare "a monte" per sapere se un token *sta arrivando*.
>* Di conseguenza, la semantica dell'OR-Join è difficile da implementare direttamente in una Rete di Petri classica senza estensioni complesse o esplosione degli stati.
>
>**B. Perdita di Dati e Risorse**
>
>* **BPMN** include elementi come *Data Objects*, *Data Stores* e *Pool/Lane* (risorse).
>* Le **Reti di Petri** classiche ($P, T, F, W$) modellano puramente il **flusso di controllo** (control-flow). Quando si traduce un diagramma BPMN in una rete di Petri classica, la connessione con i dati e le risorse viene persa o è molto debole. Per mantenere queste informazioni, sarebbe necessario utilizzare varianti più complesse come le *Colored Petri Nets*.
>
>**C. Strutture non mappabili (Mismatch Strutturale)**
Non esiste una corrispondenza biunivoca perfetta tra tutte le Reti di Petri e i diagrammi BPMN validi.
>
>* Esistono Reti di Petri valide che **non possono essere rappresentate** da un processo BPMN strutturato.
>* BPMN supporta concetti come la cancellazione di attività, le eccezioni e i segnali broadcast che richiedono pattern di reti di Petri molto complessi (es. archi inibitori o reset arcs) per essere formalizzati accuratamente.
>
>**D. Logica dei Task**
BPMN descrive la logica del processo (l'orchestrazione) ma non specifica la logica interna dei task atomici. La traduzione in Reti di Petri eredita questo limite: la rete modella *quando* accade qualcosa, non *come* viene eseguita l'attività atomica al suo interno.

### Proprietà delle Reti di Petri

* Quando una rete è **terminante**?
* Definizione di rete **deadlock-free**.
* Definizione di Place **k-bounded** e rete **sicura**.
* Quando una transizione o una rete è **live**?

>Le definizioni formali delle proprietà fondamentali di una Rete di Petri $(N, M)$ con un marking iniziale $M$:
>
>**1. Rete Terminante (Terminating)**
Una rete è definita **terminante** se e solo se esiste un numero naturale $k \in \mathbb{N}$ tale per cui ogni possibile sequenza di *firing* (scatti) a partire dal marking iniziale $M$ ha una lunghezza inferiore o uguale a $k$.
In termini intuitivi, questo significa che l'esecuzione della rete non può procedere all'infinito e si concluderà sempre dopo un numero finito di passi.
>
>**2. Rete Deadlock-free**
Una rete è **deadlock-free** (libera da blocchi) se e solo se, per ogni marking $M'$ raggiungibile dal marking iniziale $M$, esiste almeno una transizione abilitata in $M'$.
Questo implica che il sistema non raggiunge mai uno stato in cui tutto è fermo e nessuna operazione può essere eseguita.
*Nota:* Nel contesto specifico delle **Workflow Net**, la condizione di correttezza richiede che la rete sia deadlock-free nel senso che l'unica situazione in cui non è possibile effettuare una transizione è il raggiungimento dello stato finale desiderato ($o$).
>
>**3. Place k-bounded e Rete Sicura**
Queste proprietà riguardano il numero di token che possono accumularsi nei posti:
>
>* **Place k-bounded:** Un posto $p$ è definito *$k$-bounded* se e solo se, per ogni marking $M'$ raggiungibile da $M$, il numero di token in $p$ è al massimo $k$ (ovvero $M'$ assegna a $p$ al più $k$ token).
>* **Rete k-bounded:** L'intera rete è definita *$k$-bounded* se e solo se ogni suo posto è $k$-bounded.
>* **Rete Sicura (Safe):** Una rete è definita **sicura** (safe) se e solo se è **1-bounded**. In una rete sicura, nessun posto conterrà mai più di un token contemporaneamente.
>
>**4. Transizione e Rete Live**
La proprietà di *liveness* (vivacità) garantisce che le attività possano sempre essere eseguite in futuro:
>
>* **Transizione Live:** Una transizione $t$ è **live** se e solo se, per ogni marking $M'$ raggiungibile da $M$, esiste un marking $M''$ raggiungibile da $M'$ in cui la transizione $t$ è abilitata. Ciò significa che, indipendentemente dallo stato raggiunto, c'è sempre un modo per attivare nuovamente quella transizione in futuro.
>* **Rete Live:** L'intera rete è definita **live** se e solo se tutte le sue transizioni sono live.

### **Workflow Net**: definizione, requisiti di correttezza

>### Definizione di Workflow Net (WFN)
>
>Una **Workflow Net** è una specifica classe di Reti di Petri progettata per la modellazione dei processi di business. Una Rete di Petri $N = (P, T, F, W)$ è definita come una Workflow Net se soddisfa tre condizioni strutturali specifiche,,,:
>
>1. **Input Place ($p_i$):** Esiste un unico posto iniziale, denominato *input place* ($i$ o $p_i$), che non ha archi entranti ($\bullet p_i = \emptyset$). Questo posto rappresenta l'inizio del processo.
>2. **Output Place ($p_o$):** Esiste un unico posto finale, denominato *output place* ($o$ o $p_o$), che non ha archi uscenti ($p_o \bullet = \emptyset$). Questo posto rappresenta la fine del processo.
>3. **Connessione Forte (Strongly Connected):** Se si aggiunge alla rete una transizione fittizia $t^*$ che collega il posto finale $p_o$ al posto iniziale $p_i$, la rete risultante ($\bar{N}$) diventa **fortemente connessa**. Ciò significa che ogni nodo (posto o transizione) della rete si trova su un percorso diretto che va dall'inizio alla fine; non ci sono quindi "parti scollegate" o nodi che non contribuiscono al processo.
>
>### Requisiti di Correttezza: La Soundness
>
>Il criterio standard per verificare la correttezza di una Workflow Net è chiamato **Soundness** (robustezza/correttezza). Una Workflow Net è definita *sound* se soddisfa tre proprietà comportamentali fondamentali,,:
>
>1. **Terminazione Garantita (Option to complete):** Partendo dallo stato iniziale ($i$, con un token in $p_i$), deve essere sempre possibile raggiungere lo stato finale ($o$, con un token in $p_o$). In altre parole, per ogni marking raggiungibile dall'inizio, esiste una sequenza di scatti (firing sequence) che porta al termine del processo.
>2. **Terminazione Pulita (Proper Termination):** Quando il processo termina (ovvero quando appare un token nel posto finale $p_o$), non devono esserci altri token residui in nessun altro posto della rete. Lo stato finale deve corrispondere esattamente al marking $o$ (un solo token in $p_o$ e zero altrove).
>3. **Assenza di Attività Morte (No Dead Tasks):** Per ogni transizione della rete, deve esistere almeno una possibile esecuzione del processo che la attivi. Non devono esserci attività che non possono mai essere eseguite.
>
>### Teorema di Van der Aalst
>
>Esiste una relazione formale tra la proprietà di *Soundness* e le proprietà standard delle Reti di Petri (vivacità e limitatezza).
Il Teorema di Van der Aalst stabilisce che una Workflow Net $N$ è **sound** se e solo se la rete estesa $\bar{N}$ (quella con la transizione fittizia $t^*$ che chiude il ciclo) è **live** (viva) e **bounded** (limitata).
>
>* **Bounded:** La rete non accumula token all'infinito (non ci sono stati infiniti).
>* **Live:** Ogni transizione è potenzialmente attivabile da qualsiasi stato raggiungibile (nella rete estesa, il processo può ripartire all'infinito senza bloccarsi).

### **Teorema di Van der Aalst**: condizioni di correttezza per una rete workflow

>Il **Teorema di Van der Aalst** (1997) stabilisce un criterio fondamentale per verificare la correttezza (denominata **Soundness**) di una Workflow Net, collegando le proprietà specifiche dei processi di business alle proprietà classiche delle Reti di Petri.
>
>Il teorema afferma che una Workflow Net $N$ è **sound** (corretta) se e solo se la rete estesa $\bar{N}$ è **live** (viva) e **bounded** (limitata).
>
>Di seguito i dettagli delle condizioni e delle implicazioni del teorema:
>
>### 1. La Rete Estesa ($\bar{N}$)
>
>Il teorema non si applica alla rete originale $N$, che ha un inizio e una fine, ma alla sua versione estesa $\bar{N}$. Questa si ottiene aggiungendo alla rete originale una **transizione fittizia $t^*$** che collega il posto finale ($p_o$) al posto iniziale ($p_i$).
>
>* Questa operazione rende la rete **fortemente connessa**, creando un ciclo continuo dove il processo può ripartire ogni volta che termina.
>
>### 2. Le Condizioni del Teorema
>
>Affinché la Workflow Net sia dichiarata corretta, la rete estesa $\bar{N}$ deve soddisfare due proprietà standard delle reti di Petri:
>
>* **Boundedness (Limitatezza):** Il numero di token in qualsiasi posto della rete non deve mai crescere all'infinito. Una rete *workflow* corretta non deve accumulare lavoro arretrato o risorse in modo incontrollato.
>* **Liveness (Vivacità):** Ogni transizione della rete deve poter essere attivata. In una rete estesa fortemente connessa, questo significa che dal marking iniziale è possibile raggiungere uno stato che abilita qualsiasi attività del processo, garantendo l'assenza di parti "morte" del processo.
>
>### 3. Equivalenza con la Soundness
>
>Il teorema dimostra che se $\bar{N}$ è *live* e *bounded*, allora la Workflow Net originale soddisfa automaticamente i tre requisiti comportamentali della **Soundness**:
>
>1. **Deadlock-free (nell'esecuzione):** Partendo dallo stato iniziale $i$, l'unica situazione in cui il sistema si ferma (nessuna transizione abilitata) è il raggiungimento dello stato finale $o$.
>2. **Opzione di completamento:** Per qualsiasi stato $M$ raggiungibile dall'inizio, esiste sempre un percorso che porta allo stato finale $o$. Non esistono vicoli ciechi che impediscano la terminazione del processo.
>3. **Terminazione pulita:** Quando viene marcato il posto finale $p_o$ (con un token), non devono esserci altri token residui in giro per la rete. Lo stato finale corrisponde esattamente al marking $o$.
>
>### Nota sulle Free-Choice Nets
>
>Un corollario importante del lavoro di Van der Aalst specifica che, se la Workflow Net appartiene alla classe delle **Free-Choice Nets** (dove le scelte non dipendono dallo stato globale ma solo locale), la proprietà di *soundness* può essere verificata in **tempo polinomiale**, rendendo l'analisi molto efficiente.

### Cos'è una **Free-Choice Net** e perché è rilevante nei processi di business?

>La definizione di **Free-Choice Net** e la spiegazione della sua rilevanza nel contesto dei processi aziendali.
>
>### Cos'è una Free-Choice Net?
>
>Una **Free-Choice Net** (rete a scelta libera) è una sottoclasse delle Reti di Petri che soddisfa una specifica condizione strutturale riguardante gli archi che collegano i posti alle transizioni.
>
>**Definizione Formale**
Una Rete di Petri $N = (P, T, F, W)$ è definita *Free-Choice* se, per ogni arco $(p, t)$ esistente tra un posto $p$ e una transizione $t$, è vera almeno una delle seguenti due condizioni,,:
>
>1. Il posto $p$ ha quell'unico arco in uscita ($|p^{\bullet}| = 1$). In questo caso, non c'è una scelta (conflitto) associata a quel posto.
>2. La transizione $t$ ha quell'unico arco in entrata ($|^{\bullet}t| = 1$). In questo caso, la transizione non dipende da altri posti per essere abilitata.
>
>**Significato Intuitivo**
In una rete Free-Choice, **le decisioni non devono mai essere condizionate** da stati esterni alla scelta stessa.
Se un posto è input di più transizioni (c'è un conflitto o una scelta), allora l'abilitazione di queste transizioni deve dipendere *esclusivamente* dalla presenza del token in quel posto. Non è permesso che una delle transizioni della scelta richieda un token aggiuntivo da un *altro* posto (sincronizzazione) per attivarsi, perché questo renderebbe la scelta non più "libera" ma dipendente dalla disponibilità dell'altra risorsa.
>
>### Perché è rilevante nei Processi di Business (BPM)?
>
>Le Free-Choice Nets sono particolarmente rilevanti nella modellazione dei processi aziendali (BPM) per due motivi principali legati alla natura delle decisioni nei flussi di lavoro:
>
>**1. Corrispondenza con la logica decisionale dei processi**
Nei processi di business reali, le scelte (modellatete tipicamente con i gateway **XOR** in BPMN) sono quasi sempre "libere" nel senso strutturale delle Reti di Petri. Una decisione in un workflow dipende tipicamente da:
>
>* **Dati locali:** Il valore di una variabile associata al caso (es. "Importo > 500€").
>* **Decisioni esterne (Deferred Choice):** Una scelta esplicita fatta da un attore umano o da un evento esterno.
>
>Non accade quasi mai che una scelta di business (es. approvare o rifiutare una pratica) sia strutturalmente vincolata dalla presenza contemporanea di un token in un ramo parallelo non correlato. Le Free-Choice Nets catturano esattamente questo comportamento, evitando le complessità di sincronizzazioni "nascoste" che non corrispondono alla realtà operativa dei processi.
>
>**2. Facilità di Analisi**
Sebbene le fonti non entrino nei dettagli algoritmici, viene evidenziato che l'uso di strutture Free-Choice semplifica l'analisi del comportamento della rete. Nelle reti che *non* sono Free-Choice (dove una scelta è condizionata da un altro posto, come nel caso di un posto $p_{cond}$ esterno), l'analisi diventa più complessa perché si introducono dipendenze che non sono visibili localmente nel punto di scelta.
