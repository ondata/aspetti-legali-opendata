---
title: "Il riutilizzo di dati e documenti delle pubbliche amministrazioni"
---

# Il riutilizzo di dati e documenti delle pubbliche amministrazioni

## Dati personali pubblicati dalle pubbliche amministrazioni

Le pubbliche amministrazioni raccolgono e gestiscono moltissimi dati, alcuni qualificabili come dati personali, altri invece come dati non personali.

Quindi, se decidiamo di prelevare dei dati di matrice pubblica per utilizzarli in un progetto open data, è necessario procedere innanzitutto a distinguere i dati non personali dai dati personali, applicando a questi ultimi tutte le cautele previste dalla normativa sulla privacy. Nel caso in cui sia necessario integrare dataset che contengono sia dati personali (anche indirettamente personali) sia dati non personali, sarà necessario passare prima da una anonimizzazione degli stessi; comunque è consigliabile tenere traccia dei vari passaggi in modo da poter sempre intervenire sui dati personali e rimuoverli anche dopo l'attività di integrazione con altri dati.

Inoltre, quando si tratta di riutilizzare dati personali pubblicati da una pubblica amministrazione, un equivoco molto diffuso è quello di pensare che, se un dato è stato reso pubblico, allora è anche liberamente utilizzabile da chiunque, perché – si pensa ingenuamente – è ormai diventato pubblico e conosciuto da tutti. La questione è in realtà più complessa.

Gli stessi dati personali possono essere legittimamente "trattati" e pubblicati da una pubblica amministrazione in virtù di una delle basi giuridiche stabilite dal GDPR (art. 6), mentre non possono essere prelevati e riutilizzati legittimamente da un altro soggetto il quale non può far leva sulle medesime basi giuridiche.

Per quanto riguarda invece i dati per loro natura non personali, dovremo preoccuparci unicamente dell'aspetto della proprietà intellettuale, secondo quanto spiegato in questi prossimi paragrafi.

## Il diritto d'autore degli enti pubblici

Gli enti pubblici sono titolari di diritti d'autore? E in quali termini? Per rispondere a questa domanda dobbiamo fare riferimento a due norme della L. 633/1941 (legge italiana sul diritto d'autore): gli articoli 5 e 11.

Iniziamo dall'art. 11 in cui si conferma che gli enti pubblici sono titolari di diritto d'autore:

> *«Alle Amministrazioni dello Stato, alle Province ed ai Comuni spetta il diritto di autore sulle opere create e pubblicate sotto il loro nome ed a loro conto e spese. Lo stesso diritto spetta agli enti privati che non perseguano scopi di lucro, salvo diverso accordo con gli autori delle opere pubblicate, nonché alle accademie e agli altri enti pubblici culturali sulla raccolta dei loro atti e sulle loro pubblicazioni.»*

Questo principio comprende tutti i diritti normalmente contemplati dalla legge sul diritto d'autore, quindi anche il diritto sui generis del costitutore di banca dati (sempre a condizione che la realizzazione della banca dati abbia richiesto un rilevante investimento).

L'art. 5 invece esclude dal campo d'azione del diritto d'autore "i testi degli atti ufficiali dello Stato e delle pubbliche amministrazioni, sia italiane che straniere", che quindi diventano di pubblico dominio "by default". Si noti che la norma va interpretata in senso restrittivo; bisogna dunque limitarsi unicamente ai testi (escludendo quindi immagini, video, banche dati, software e altri tipi di contenuti) degli atti ufficiali, cioè quegli atti che sono esercizio della funzione amministrativa e del potere autoritativo (escludendo contenuti come brochure informative e divulgative, sezioni di siti web pubblici dedicate alle notizie e agli approfondimenti). Un tipico esempio di contenuti che ricadono pienamente sotto il dettato dell'art. 5 è rappresentato dai testi delle sentenze dei tribunali e delle corti, i quali, al netto dei dati personali che vanno comunque rimossi, sono fin da subito liberi dal copyright e di pubblico dominio.

Importante annotazione: non ha alcun senso aggiungere una licenza open (anche se la più libera disponibile) a contenuti già coperti dall'art. 5, in quanto appunto sono già in pubblico dominio ex lege. Anzi, aggiungervi una licenza rischia solo di creare ulteriore confusione; si può al massimo aggiungere un "public domain mark", cioè un disclaimer che appunto indichi espressamente lo status di contenuti in pubblico dominio.

## I dati a pubblicazione obbligatoria

Una fetta consistente dei dati raccolti e messi a disposizione dei cittadini dalle pubbliche amministrazioni sono raccolti e pubblicati non per una "gentile concessione" della PA competente e nemmeno per una scelta strategica della stessa, ma perché quella PA è tenuta a farlo in virtù di un obbligo di legge; un obbligo che è sostenuto da specifiche sanzioni per le PA e per i loro dirigenti. Questo principio è stato via via rafforzato dalle varie direttive europee e leggi nazionali in materia di open government, trasparenza della PA e riutilizzo dell'informazione pubblica. Con il D.Lgs. n. 33/2013 (anche noto come "decreto trasparenza") e con il successivo D.Lgs. n. 97/2016 (anche noto come "decreto FOIA") sono stati individuati chiaramente i dati soggetti a pubblicazione obbligatoria, cioè dati che la PA è tenuta a pubblicare regolarmente.

A rigor di buon senso, quindi, su questi dati le restrizioni di proprietà intellettuale dovrebbero essere ridotte al minimo[^1], applicando al massimo una licenza di mera attribuzione, se non addirittura azzerate con un rilascio in pubblico dominio (esempio: CC Zero).

## La licenza suggerita dalla linee guida AGID

Le linee guida italiane in materia di open data pubblici ([Linee guida nazionali per la valorizzazione del patrimonio informativo pubblico](https://docs.italia.it/italia/daf/lg-patrimonio-pubblico/it/stabile/index.html)), chiamate a fornire un'indicazione tra le varie opzioni, esprimono [nell'Azione n. 12](https://docs.italia.it/italia/daf/lg-patrimonio-pubblico/it/stabile/licenzecosti.html) un'esplicita preferenza per la licenza Creative Commons Attribution 4.0 International. Si legge infatti:

> *«Si ritiene opportuno fare riferimento ad una licenza unica aperta, che garantisca libertà di riutilizzo, che sia internazionalmente riconosciuta e che consenta di attribuire la paternità dei dataset (attribuire la fonte). Pertanto, si suggerisce l'adozione generalizzata della licenza CC BY nella sua versione 4.0, presupponendo altresì l'attribuzione automatica di tale licenza nel caso di applicazione del principio "Open Data by default", espresso nelle disposizioni contenute nell'articolo 52 del CAD.»*

Come è noto, documenti come le linee guida non rappresentano norme cogenti ma piuttosto delle raccomandazioni (cosiddetta "soft law"); tuttavia, essendo emanate dall'amministrazione centrale (in questo caso, un'agenzia ministeriale) diventano un fondamentale riferimento da cui le pubbliche amministrazioni difficilmente possono discostarsi senza subire critiche e segnalazioni.

## Il cosiddetto "open by default" (art. 52 CAD)

Il cosiddetto Decreto Crescita 2.0, convertito poi nella Legge 221/2012, ha introdotto all'[articolo 52](https://www.normattiva.it/uri-res/N2Ls?urn:nir:stato:decreto.legislativo:2005-03-07;82!vig~art52) del Codice Amministrazione Digitale quello che viene di solito definito "principio open by default sui dati e sui documenti della pubblica amministrazione". Al comma 2 della norma (intitolata "Accesso telematico e riutilizzo dei dati") si legge:

> *«I dati e i documenti che \[le pubbliche amministrazioni\] pubblicano, con qualsiasi modalità, senza l'espressa adozione di una licenza \[...\] si intendono rilasciati come dati di tipo aperto \[...\], ad eccezione dei casi in cui la pubblicazione riguardi dati personali.»*

Il comma rimanda alla definizione di "dato aperto" fornita all'articolo 1, comma 1, lettere l-bis) e l-ter), che è utile riportare:

> *«\[sono dati di tipo aperto\] dati di tipo aperto: i dati che presentano le seguenti caratteristiche: 1) sono disponibili secondo i termini di una licenza o di una previsione normativa che ne permetta l'utilizzo da parte di chiunque, anche per finalità commerciali, in formato disaggregato; 2) sono accessibili attraverso le tecnologie dell'informazione e della comunicazione, ivi comprese le reti telematiche pubbliche e private, in formati aperti ai sensi della lettera l-bis), sono adatti all'utilizzo automatico da parte di programmi per elaboratori e sono provvisti dei relativi metadati; 3) sono resi disponibili gratuitamente attraverso le tecnologie dell'informazione e della comunicazione, ivi comprese le reti telematiche pubbliche e private, oppure sono resi disponibili ai costi marginali sostenuti per la loro riproduzione e divulgazione.»*

Questo meccanismo è particolarmente contorto e rappresenta una soluzione di compromesso non certo ottimale[^2]; tuttavia è un meccanismo ingegnoso che permette di sfruttare l'inerzia delle pubbliche amministrazioni le quali spesso, pur mettendo a disposizione sui loro siti web dati e documenti di interesse pubblico, non provvedono a corredarli di una licenza open. In virtù dell'articolo 52 cittadini, imprese e altre pubbliche amministrazioni possono di fatto utilizzare quei dati e documenti come se fossero "aperti" anche in mancanza di una licenza esplicita.

Si noti un risvolto non irrilevante: la norma parla di dati e di documenti, ponendo ulteriori questioni interpretative. Innanzitutto, introduce il concetto di "documenti" senza però fornirne una precisa definizione. Inoltre crea un disallineamento semantico con la terminologia della legge sul diritto d'autore in cui invece, come abbiamo spiegato, si parla principalmente di "banche dati" e non di "dati" (articoli 1 e 2) e di "atti ufficiali" e non di "documenti ufficiali" (articolo 5).

Ad ogni modo, al di là dei rilievi critici su questa scelta normativa non ottimale, nei fatti l'articolo 52 riesce a fornire un buon livello di libertà per gli utilizzatori di dati pubblici; quindi possiamo salutarlo come una norma utile e innovativa.

[^1]: Volendo andare a un livello ulteriore di analisi giuridica potremmo sollevare il seguente dubbio. Se una pubblica amministrazione è comunque obbligata a pubblicare dei dati, possiamo davvero dire che abbia effettuato un "rilevante investimento" per la realizzazione della banca dati? In altre parole, possiamo davvero parlare di "investimento" se la PA non ha fatto altro che ottemperare a un obbligo, per altro utilizzando risorse economiche che le vengono appositamente attribuite dalla legge? Il quesito sembra di natura puramente dottrinale, ma è invece determinante; perché se la risposta fosse negativa, potremmo arrivare a dire che, mancando il requisito del "rilevante investimento", viene meno anche il diritto sui generis (quanto meno sulle banche dati realizzate dalla PA in ossequio a un obbligo di legge). Di conseguenza, su quei dati non ci sarebbe bisogno di una licenza, né in alternativa di invocare l'open by default dell'articolo 52 Codice Amministrazione Digitale.
[^2]: La soluzione ottimale sarebbe un intervento che vada a modificare gli articoli 5 e 11 della legge sul diritto d'autore. Per approfondire, si rimanda alla lettura di "[Open data: serve una norma più chiara. L'open by default non funziona](https://www.techeconomy2030.it/2018/12/28/open-data-serve-una-norma-piu-chiara-lopen-by-default-non-funziona)", articolo del 2018 che contiene anche una proposta di riforma per l'art. 5.
