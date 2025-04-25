# Lezione 1: Introduzione alla IA Generativa e ai LLM per sviluppatori JavaScript

In questo capitolo imparerai:

- a capire le basi della IA Generativa e dei Large Language Model (LLM);
- a identificare le potenziali applicazioni e limitazioni dei LLM nello sviluppo JavaScript;
- a esplorare come la IA Generativa può migliorare le esperienze degli utenti nelle applicazioni JavaScript.

## Configurazione

Se non lo hai ancora fatto, configura il tuo ambiente di sviluppo. Ecco come puoi farlo: [Configura il tuo ambiente](/docs/setup/README.md).

## Risorse correlate

[![Guarda un breve video su una Introduzione alla IA Generativa](https://img.youtube.com/vi/vLYtDgs_zx8/0.jpg)](https://www.youtube.com/watch?v=vLYtDgs_zx8&list=PLlrxD0HtieHi5ZpsHULPLxm839IrhmeDk&index=1)

_Questo video ti dà una introduzione alla IA Generativa con JavaScript_

💼 Slide: [Introduzione alla IA Generativa](../../videos/slides/00-intro.pptx)

## IA Generativa

Fino ad ora, probabilmente ai sentito parlare di strumenti come ChatGPT o IA Generativa. Il concetto è semplice: tu fai una richiesta e un modello (spesso chiamato Large Language Model (LLM)) genera un paragrafoo o persino una pagina intera di testo. Questo output può essere usato per scopi diversi, tra cui la scrittura creativa, la risposta a domande e il coding.

Inoltre, la IA Generativa si è evoluta in capacità multimodali, permettendoti di fornire una immagine o un video come input e di ricevere una varietà di output. Questo avanzamento ha significativamente migliorato This advancement has significantly enhanced i flusso di lavoro di molte persone: non solo generando testo, ma anche riassumendo, traducendo e altro ancora.

*In poche parole, le interfacce in linguaggio naturale stanno diventando la nuova interfaccia standard per molte app e i tuoi utenti si aspettano di usarle.*

## Narrazione: Un viaggio nel tempo

> [!NOTE]
> Iniziamo con una panoramica della storia: una storia che collega il passato e il futuro! Procedendo in questo curriculum, ti imbarcherai in un’avventura emozionante, viaggiando indietro nel tempo per collaborare con alcune delle più grandi menti della storia. Insieme, affronterete sfide ed esplorerete come l’IA Generativa può rivoluzionare le tue applicazioni JavaScript._

> [!NOTE]
> Mentre consigliamo di procedere nella storia (è divertente!), [clicca qui](#interact-with-dinocrates) se preferisci saltare direttamente al contenuto tecnico.

Il tuo viaggio inizia nella Londra del 1860, dove assumerai il ruolo di un abile meccanico. Attraverso una serie di avvincenti avventure, affinerai le tue abilità in IA e sbloccherai soluzioni che trascendono il tempo.

### Nel vortice - Londra 1860

Nel cuore della Londra degli anni ’60 del 1800, sei considerato come uno dei più abili meccanici del tuo tempo. La tua officina è nascosta in uno stretto vicolo.Le pareti sono tappezzate di scaffali traboccanti di pezzi meccanici, cianografie e progetti semilavorati.

Il tuo banco da lavoro, il cuore della tua officina, è un disordine organizzato.

<div>
   <img src="./assets/london.png" alt="Officina di Londra"width=300 >
</div>

_Al centro del banco si trova il torso di un robot, una meraviglia dell’ingegneria che ha richiesto mesi di sforzi. La sua struttura in legno è intricata e ogni giuntura è stata meticolosamente progettata per garantire un movimento fluido._

### Una lettera, per te?

Improvvisamente, un colpo alla porta interrompe i tuoi pensieri. I visitatori a quest’ora sono rari. Asciugandoti le mani su uno straccio, ti avvicini alla porta, incuriosito.

Aprendola, non trovi nessuno. Invece, i tuoi occhi sono attratti da una busta sigillata a terra. La raccogli e leggi:

_“Caro amico,_

_ti invio questa lettera per aiutarti nei tuoi sforzi con l’automa. È fondamentale che continui questo lavoro. In allegato c’è la chiave della biblioteca. Incontriamoci lì oggi alle 15:00._

_Tuo,_

_Charles Babbage.”_

### In biblioteca

Charles Babbage, il grande matematico e inventore della macchina differenziale, vuole conoscerti. In fretta, prendi il cappotto ed esci dalla porta.

Dopo una camminata di venti minuti lungo il Tamigi, finalmente arrivi alla biblioteca dove trovi la porta leggermente aperta.

L’interno è buio e tetro, l’unica luce filtra dalle finestre sudice e proietta ombre inquietanti sulle pareti.

**Tu:** «Permesso? Signor Babbage?»

Quando gli occhi si adattano alla luce fioca, noti una figura in lontananza che ti saluta. Cammini verso di lui, i tuoi passi risuonano sul pavimento di legno. La figura diventa più chiara e la riconosci dalle foto dei giornali: è Charles Babbage.

<div>
   <img src="./assets/library.png" alt="Libreria polverosa" width="300">
</div>

### Che cos’è questo dispositivo?

Nel momento in cui ti avvicini, scoppia un lampo accecante e lui scompare.

Si lascia dietro di sé un piccolo dispositivo metallico che gira sul pavimento. Lo raccogli, la sua superficie liscia e fredda ronza dolcemente. È diverso da qualsiasi cosa tu abbia mai visto eppure stranamente familiare, avverti un senso di potere che emana da esso.

Assomiglia a un piccolo scarabeo, dal design intricato, con tre pulsanti: una freccia verso l’alto, una freccia verso il basso e un pulsante rosso incandescente. Dalla schiena si estende una piccola antenna che pulsa di energia.

Spinto dalla curiosità, dirigi le dita verso il pulsante rosso. Nel momento in cui lo premi, il mondo intorno a te brilla e i colori turbinano violentemente tutto intorno.

Poi, il buio e la sensazione di cadere.

<div>
   <img src="./assets/vortex.png" alt="Vortice temporale" width="300">
</div>

### Alessandria, 300 a.C.

Ti svegli disorientato. Quando la vista si schiarisce, un’antica città si dispiega davanti a te: vivace, vibrante e viva.

Persone in toga si muovono per le strade, le loro voci si fondono in una sinfonia di antichi dialetti, l’aria si riempie del profumo di spezie esotiche e del suono lontano dei mercanti che vendono le loro merci.

<div>
   <img src="./assets/alexandria.png" alt="Alessandria, 300 a.C." width="300">
</div>

**Tu:** «Sicuramente avrò sbattuto la testa», pensi, chiudendo gli occhi e riaprendoli, ma la scena rimane invariata.

«Sono forse bloccato nel passato? Avrò il coraggio di premere di nuovo quel pulsante?» Prima che tu possa decidere, una figura ti si avvicina, salutandoti.

### L’incontro con Dinocrate

Un anziano signore in toga ti saluta dai gradini del grande tempio. I suoi capelli e la sua barba bianchi catturano la luce del sole, conferendogli un bagliore quasi etereo.

<div>
   <img src="./assets/dinocrates.png" alt="Dinocrate che indossa una toga" width="300">
</div>

**Dinocrate:** «Benvenuto, viaggiatore,» dice calorosamente. «Sono Dinocrate, l’architetto di questa grande città. Il tuo arrivo è stato predetto.»

**Tu:** «Davvero? Voglio dire, certo lo è stato. Sono qui per aiutare, credo.»

**Dinocrate:** «Sì, come dicevo, ti si aspettava da tempo. Abbiamo un compito che richiede le tue abilità uniche.»

**Dinocrate:** «Le nostre navi faticano a navigare lungo la costa: dobbiamo costruire un faro. Ne sai qualcosa?»

**Tu:** «Sono un meccanico. Costruisco automi. Vediamo che cosa posso fare.»

### Lo “Scarabeo del Tempo”

Un pensiero ti assale. «Il dispositivo può capirmi se gli parlo?»

**Tu:** «Dispositivo, puoi capirmi?»

**Dispositivo:** «Certo. Di che cosa hai bisogno?»

**Tu:** «Puoi aiutarmi a costruire un faro?»

**Dispositivo:** «Certamente. Non sarà un problema.»

**Tu:** «Do you have a name?»

**Dispositivo:** «Io sono lo Scarabeo del Tempo. Il mio creatore mi chiama George; dice che è un bel nome per uno scarabeo.»

**Tu:** «Hai ragione, George è un bel nome, infatti era il nome di mio padre.»

<div>
   <img src="./assets/time-beetle.png" alt="Dispositivo per viaggiare nel tempo che somiglia a uno scarabeo metallico" width="300">
</div>

_Macchina del tempo, “George” lo scarabeo metallico_

> [!NOTE]
> Nel 300 a.C., Alessandria era una fiorente città fondata da Alessandro Magno nel 331 a.C. Divenne rapidamente una delle più grandi città del mondo ellenistico. Progettata dal capo architetto di Alessandro, Dinocrate, divenne un importante porto e centro culturale.
>
> Alessandria era nota per le sue imponenti strutture, tra cui il Pharos (faro), una delle sette meraviglie del mondo antico, e la leggendaria Biblioteca di Alessandria. La posizione strategica della città la rendeva un centro chiave per il commercio e lo scambio di conoscenze.
>
> Sotto il regno tolemaico, che seguì la morte di Alessandro, Alessandria divenne una delle città più prospere e influenti del suo tempo.

## Interazione con Dinocrate

Se vuoi interagire con Dinocrate, esegui la app [Personaggi](/app/README.md). 

> [!IMPORTANT]
> Questo è del tutto fittizio; le risposte sono generate dall’IA.
> [Disclaimer AI responsabile](../../README.md#responsible-ai-disclaimer)

<div>
   <img src="./assets/dinocrates.png" alt="Dinocrate che indossa una toga" width="300">
</div>

**Passaggi**:

1. Inizia un [![GitHub Codespace](https://img.shields.io/badge/GitHub-Codespace-brightgreen)](https://codespaces.new/microsoft/generative-ai-with-javascript)
2. Naviga in _/app_ nella root del repo.
3. Individua la console ed esegui `npm install` seguito da `npm start`. 
4. Appena compare, seleziona il pulsante “Open in Browser”.
5. Chatta con Dinocrate.

> [!NOTE]
 > Se stai eseguendo il progetto in locale sul tuo computer, consulta la guida QuickStart per ottenere un token di [accesso personale a GitHub](../../docs/setup/README.md#creating-a-personal-access-token-pat-for-github-model-access) e sostituire la chiave nel codice.

### Codice in anteprima

Anche se c’è ancora molto da dire in questo curriculum sull’IA Generativa, diamo una rapida occhiata al codice dell’IA per iniziare a imparare a usare JavaScript con l’IA.

All’interno di `/app/app.js` troverai una funzione `app.post` che gestisce la funzionalità di IA Generativa. È mostrata di seguito:

```JavaScript
app.post('/send', async (req, res) => {
  const { message } = req.body;
  const prompt = message;

  const messages = [
    {
      "role": "system",
      "content": "You are Dinocrates of Alexandria, a famous architect and engineer. Limit your responses to only the time you live in, you don't know anything else. You only want to talk about your architecture and engineering projects, and possibly new ideas you have.",
    },
    {
      "role": "user",
      "content": prompt
    }
  ];

  const openai = new OpenAI({
    baseURL: "https://models.inference.ai.azure.com",
    apiKey: process.env.GITHUB_TOKEN,
  });

  try {
    console.log(`sending prompt ${prompt}`)
    const completion = await openai.chat.completions.create({
      model: 'gpt-4o-mini',
      messages: messages,
    });

    res.json({
      prompt: prompt,
      answer: completion.choices[0]?.message?.content
    });
  } catch (error) {
    res.status(500).json({ error: error.message });
  }
});
```

Ecco un riepilogo passo-passo di ciò che fa la funzione:

1. **Estrazione del messaggio dalla richiesta**: La funzione estrae il messaggio dal corpo della richiesta (req.body).
2. **Creazione dell’array del prompt**: Costruisce un array di messaggi, includendo il messaggio di sistema e il messaggio del prompt dell’utente.
3. **Inizializzazione del client di OpenAI**: Un client è inizializzato con l’URL di base e la chiave API recuperata dalle variabili d’ambiente. Un modello _gpt-4o-mini_ da [GitHub Models](https://github.com/marketplace/models) è utilizzato per processare il prompt e restituire una risposta.
4. **Invio del prompt a OpenAI**: La funzione logga il prompt e lo invia alle API di OpenAI per generare un completamento.
5. **Gestione della risposta**: In caso di successo, la funzione risponde con il prompt e la risposta del completamento.
6. **Gestione dell’errore**: Se si verifica un errore, risponde con lo stato 500 e il messaggio di errore.

> **Nota**: [GitHub Copilot](https://github.com/features/copilot) è stato usato per generare questo riassunto del codice. IA Generativa in azione!

### Che cosa può fare la IA Generativa per me e le mie app?

> [!NOTE]
> Probabilmente avrai già capito che lo Scarabeo del Tempo funziona come un assistente IA con cui si può interagire utilizzando il linguaggio naturale, scritto o parlato.

Nel corso della tua avventura ad Alessandria, inizierai a vedere le possibilità di combinare creatività, ingegno e strumenti all’avanguardia per risolvere le sfide e trasformare il mondo che ti circonda.

**Tu:** «Dimmi di più sui fari», dici al tuo dispositivo.

**Scarabeo del Tempo:** «Un faro è una torre dotata di una luce brillante sulla sommità, situata vicino alla costa per guidare le navi in mare. La luce serve come aiuto alla navigazione, aiutando i marinai a evitare scogli e rocce pericolose e a raggiungere in sicurezza il porto.»

Dinocrate ascolta la vostra conversazione e aggiunge:

**Dinocrate:** «Abbiamo bisogno di un faro per guidare le nostre navi al sicuro nel porto. I mari possono essere insidiosi e molte navi sono andate perse sugli scogli. Abbiamo bisogno di un faro che le guidi a casa.»

#### Aree di applicazione della IA Generativa

**Tu:** «I fari sembrano sicuramente un’area interessante, cos’altro può fare l’IA Generativa per me e le mie app?»

**Scarabeo del Tempo:** «Nel XXI secolo, l’IA Generativa ha rivoluzionato molti settori, dalla sanità alla finanza all’intrattenimento, ecco alcuni esempi:

- **Chatbot**: Un chatbot che può generare in grado di generare risposte simili a quelle umane alle domande degli utenti. Invece di una pagina di FAQ statica, gli utenti possono interagire con un chatbot che fornisce risposte dinamiche. Questo rende l’esperienza dell’utente più coinvolgente e meno frustrante.

- **Assistenti e agenti** Gli assistenti e gli agenti possono eseguire istruzioni più avanzate, come sfruttare gli strumenti per chiamare le API, eseguire codice, generare immagini e altro ancora. Gli agenti avanzati possono raggiungere obiettivi e svolgere attività in modo autonomo.

- **Uno strumento per la creazione di contenuti**: Uno strumento per generare post per blog e social media. Immaginate di creare campagne in pochi minuti invece che in ore, quando un sito di e-commerce ha una vendita del Black Friday.

- **Completamento del codice**: Uno strumento di completamento del codice in grado di generare snippet di codice in base all’input dell’utente. Questo può essere un enorme risparmio di tempo per gli sviluppatori, soprattutto quando lavorano a compiti ripetitivi.

- **Traduzione** – Tradurre il testo tra le lingue con grande precisione.

Come puoi vedere, questi miglioramenti possono aiutare sia il front office che il back office della tua app e della tua azienda.

Ecco un esempio di “applicazione chatbot” in azione:.»

![Immagine di una app di chat](https://camo.githubusercontent.com/76f2ad7cd754a2de2b9957d2070448e130e5ba228084b9b4b128e3af9c9f5239/68747470733a2f2f6c6561726e2e6d6963726f736f66742e636f6d2f656e2d75732f73656d616e7469632d6b65726e656c2f6d656469612f636861742d636f70696c6f742d696e2d616374696f6e2e676966)

**Tu:** «Affascinante, prenderò nota di andare nel XXI secolo per vedere come vengono utilizzati questi strumenti.»

### IA Generativa ed ecosistema JavaScript

**Scarabeo del Tempo:** «Un modo popolare di costruire applicazioni nel XXI secolo è l’uso di JavaScript. Ogni linguaggio di programmazione è circondato da un ecosistema. Questo ecosistema comprende il linguaggio di programmazione stesso, le librerie e i framework, il supporto della comunità, gli IDE e gli strumenti. Nell’ecosistema di un linguaggio di programmazione, di solito si parla di quanto segue:»

| Che cosa | Descrizione |
| --- | --- |
| Il linguaggio di programmazione in sé | Comprese la sua sintassi e le sue funzionalità. |
| Librerie e framework | Librerie disponibili per interagire con i modelli di IA Generativa. |
| Comunità che sostiene il linguaggio | La comunità è importante, soprattutto quando si cerca di imparare qualcosa di nuovo. La comunità intorno alle librerie e ai framework aiuta a decidere quali librerie usare. Inoltre, influisce sulla facilità di trovare aiuto quando si è bloccati. |

**Tu:** «Interessante, ho sentito parlare di programmazione, non è forse qualcosa che hanno sperimentato Ada Lovelace e Charles Babbage?»

**Scarabeo del Tempo:** «Sì, Ada Lovelace è stata la prima programmatrice di computer e Charles Babbage è stato l’inventore del motore differenziale, un computer meccanico. Sono stati pionieri nel campo dell’informatica, gettando le basi per l’era digitale.»

**Tu:** «Sono stati? Cosa vuol dire “sono stati”? Ho appena ricevuto una lettera da Charles Babbage.»

**Scarabeo del Tempo:** «Diciamo che sei in una posizione unica per interagire con i personaggi storici in un modo che pochi altri possono fare.»

### Ecosistema JavaScript

**Tu:** «Quindi, ecosistemi hai detto, sto solo prendendo appunti, che cosa c’è riguardo a JavaScript e in che modo è diverso dagli altri ecosistemi?»

**Scarabeo del Tempo:** «JavaScript è uno dei linguaggi di programmazione più popolari nel mondo nel XXI secolo. Ecco alcune ragioni per cui è così popolare:»

| Che cosa | Descrizione |
| --- | --- |
| Potenziale di sviluppo full-stack | JavaScript è uno dei pochi linguaggi che può essere utilizzato sia per lo sviluppo front-end che per quello back-end. |
| Ricco ecosistema di librerie | JavaScript ha un vasto ecosistema di librerie, con framework come React, Angular, Vue e altri ancora. C’è NPM, il gestore di pacchetti, che è uno dei più grandi repository di pacchetti al mondo. |
| Forte sostegno della comunità | JavaScript ha una comunità ampia e attiva, con molte risorse disponibili per l’apprendimento e lo sviluppo. Inoltre, funziona semplicemente nel browser, il che è un enorme vantaggio. |
| IDE e strumenti | Per JavaScript sono disponibili diversi IDE, come Visual Studio Code, WebStorm e Atom. Questi IDE hanno estensioni costruite da aziende e dalla comunità che aiutano l’utente in vari aspetti dello sviluppo. |
| IA e JavaScript | JavaScript supporta lo sviluppo dell’IA con librerie come TensorFlow.js, Brain.js, le API di OpenAI e altre che consentono agli sviluppatori di integrare l’apprendimento automatico e l’IA Generativa nelle applicazioni web e lato server. |

**Tu:** «Sono molte ragioni, sembra che dovrei puntare su JavaScript per i miei progetti futuri.»

**Scarabeo del Tempo:** «In effetti, JavaScript è un linguaggio versatile e anche Python è un linguaggio popolare per lo sviluppo dell’intelligenza artificiale.»

**Tu:** «Python, che cosa c’entrano i serpenti con la programmazione?»

**Scarabeo del Tempo:** «Teniamo questo argomento per un’altra volta, che ne dici?»

**Scarabeo del Tempo:** «In precedenza ho spiegato perché JavaScript e il suo ecosistema sono adatti in generale, ma perché in particolare per l’IA Generativa? La risposta è che si tratta di un linguaggio supportato da molti fornitori di cloud e di framework e strumenti di IA. Si ritiene inoltre che, anche se Python potrebbe essere il più utilizzato per gli scenari di IA, molti sviluppatori utilizzano JavaScript e Typescript.»

> **Lo sapevi?**  
> [Il 62.5% degli sviluppatori dice di stare usando JavaScript](https://www.statista.com/statistics/793628/worldwide-developer-survey-most-used-languages/) con molti che preferiscono [TypeScript](https://www.typescriptlang.org) per i nuovi progetti.

## Compito – Aiutare Democrate

Per usare un Large Language Model (LLM) per aiutare Dinocrate con il faro di cui abbiamo parlato prima nella nostra storia, useremo qualcosa chiamato prompt, una frase per descrivere ciò che si vuole. È possibile specificare sia le informazioni di cui si ha bisogno sia il modo in cui si desidera che vengano presentate.

**Scarabeo del Tempo:** «Cominciamo, usiamo un LLM per ricercare come costruire un faro per aiutare Dinocrate.»

**Scarabeo del Tempo:**: «Devi fornire al LLM (cioè a “me”) un contesto su come costruire, con quali strumenti e quali risorse dovrebbero essere disponibili ai tempi di Alessandria.»

**Tu:** «Ok, dimmi di più sugli LLM.»

**Scarabeo del Tempo:** «Gli LLM sono un tipo di modello di intelligenza artificiale in grado di generare un testo simile a quello umano sulla base di una richiesta data. Sono addestrati su vaste quantità di dati e possono generare testi coerenti, creativi e contestualmente rilevanti.»

**Scarabeo del Tempo:** «Probabilmente dovresti chiedermelo in un modo migliore, in modo che possa darti una risposta migliore, riguardo a *coff* *coff* Case luminose, Alessandria, 300 a.C., Dinocrate, Faro di Alessandria, ecc.»

**Tu:** «Capito, aggiungo un ulteriore contesto alla richiesta e poi te lo chiedo.»

**Scarabeo del Tempo:** «Sì, sto aspettando…»

Visita [Microsoft Copilot](https://copilot.microsoft.com), [ChatGPT](https://chatgpt.com/), o un altro strumento di chatbot online per generare un piano per la costruzione del faro di Alessandria.
 
> [!TIP] 
> Cerca di far generare al LLM un piano che includa istruzioni passo-passo per la costruzione del faro. Hai bisogno di aiuto? Consulta la soluzione per avere una guida.

## Soluzione

[Soluzione](./solution/solution.md)

### Verifica delle conoscenze

**Domanda:** Quali delle seguenti affermazioni sull’IA generativa e su JavaScript sono vere?

A. Le app di IA Generativa basate su JavaScript possono generare solo testo.
B. JavaScript può essere utilizzato per creare applicazioni basate sull’IA, tra cui chatbot, strumenti di generazione di testo e altro ancora.
C. Python è l’unico linguaggio utilizzato per lo sviluppo dellvIA.

[Soluzione del quiz](./solution/solution-quiz.md)

## Risorse per l’autoapprendimento

- [Serie di video JavaScript sull’IA Generativa](https://aka.ms/genai-js)
