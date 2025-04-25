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
|---|---|
| Il linguaggio di programmazione in sé | Comprese la sua sintassi e le sue funzionalità. |
| Librerie e framework | Librerie disponibili per interagire con i modelli di IA Generativa. |
| Comunità che sostiene il linguaggio | La comunità è importante, soprattutto quando si cerca di imparare qualcosa di nuovo. La comunità intorno alle librerie e ai framework aiuta a decidere quali librerie usare. Inoltre, influisce sulla facilità di trovare aiuto quando si è bloccati. |

**Tu:** «Interessante, ho sentito parlare di programmazione, non è forse qualcosa che hanno sperimentato Ada Lovelace e Charles Babbage?»

**Scarabeo del Tempo:** «Sì, Ada Lovelace è stata la prima programmatrice di computer e Charles Babbage è stato l’inventore del motore differenziale, un computer meccanico. Sono stati pionieri nel campo dell’informatica, gettando le basi per l’era digitale.»

**Tu:** «Sono stati? Cosa vuol dire “sono stati”? Ho appena ricevuto una lettera da Charles Babbage.»

**Scarabeo del Tempo:** «Diciamo che sei in una posizione unica per interagire con i personaggi storici in un modo che pochi altri possono fare.»

### Ecosistema JavaScript

**You:** So ecosystems you said, I'm just taking notes here, what about JavaScript and how is it different from other ecosystems?

**Time Beetle:** JavaScript is one of the most popular programming languages in the world in the 21st century. Here are a few reasons why it's so popular:

| What | Description |
|-|-|
| Potential for full-stack development | JavaScript is one of the few languages that can be used for both front-end and back-end development. |
| Rich library ecosystem | JavaScript has a vast library ecosystem, with frameworks like React, Angular, Vue, and more. There's NPM, the package manager, which is one of the largest package repositories in the world. |
| Strong community support | JavaScript has a large and active community, with many resources available for learning and development. It also just works in the browser, which is a huge advantage. |
| IDEs and tools | JavaScript has a variety of IDEs available, such as Visual Studio Code, WebStorm, and Atom. These IDEs have extensions built by companies and the community helping you with various aspects of development. |
| AI and JavaScript | JavaScript supports AI development with libraries like TensorFlow.js, Brain.js, OpenAI’s APIs, and more enabling developers to integrate machine learning and Generative AI into web and server-side applications. |

**You:** That's a lot of reasons, sounds like I should bet on JavaScript for my future projects.

**Time Beetle:** Indeed, JavaScript is a versatile language, also Python is a popular language for AI development.

**You:** Python, what do snakes have to do with programming?

**Time Beetle:** Let's save that for another time, shall we?

**Time Beetle:** I've given reasons above why JavaScript and its ecosystem is a good fit in general but why specifically for Generative AI? The answer is that it's a supported language by many cloud vendors and AI frameworks and tools. We also believe that even though Python might be top of mind for AI scenarios, many developers are using JavaScript and Typescript.

> **Did you know?**  
> [62.5% of developers say they're using JavaScript](https://www.statista.com/statistics/793628/worldwide-developer-survey-most-used-languages/) with many preferring [TypeScript](https://www.typescriptlang.org) for new projects.

## Assignment – Helping Dinocrates 

To use a Large Language Model (LLM) to help Dinocrates with the lighthouse that we mentioned earlier in our story, we’ll use something called prompts, a sentence to describe what you want. You can specify both the information you need and how you want it presented.

**Time Beetle:** Let's get started, let's use an LLM to research how you can build a lighthouse to help Dinocrates.

**Time Beetle:**: You’ll need to provide context to the LLM (i.e "me") how to build, with what tools and resources should be available in the times of Alexandria.

**You:** Ok, tell me more about LLMs.

**Time Beetle:** LLMs are a type of AI model that can generate human-like text based on a given prompt. They are trained on vast amounts of data and can generate text that is coherent, creative, and contextually relevant.

**Time Beetle:** You probably want to ask me in a better way, so I can give you a better answer, about you know *cough* *cough* Light houses, Alexandria, 300 BC, Dinocrates, Lighthouse of Alexandria, etc.

**You:** Got it, add more context to the prompt and then ask you.

**Time Beetle:** Yes, I'm waiting...

Visit [Microsoft Copilot](https://copilot.microsoft.com), [ChatGPT](https://chatgpt.com/), or another online chatbot tool to generate a plan for building the lighthouse in Alexandria.
 
> [!TIP] 
> Try to have the LLM generate a plan that includes step-by-step instructions for building the lighthouse. Need help? Check out the solution for guidance.

## Solution

[Solution](./solution/solution.md)

### Knowledge check

**Question:** Which of the following statements about Generative AI and JavaScript are true?

A. JavaScript powered Generative AI apps can only generate text.
B. JavaScript can be used to build AI-powered applications, including chatbots, text generation tools, and more.
C. Python is the only language used for AI development.

[Quiz solution](./solution/solution-quiz.md)

## Self-Study resources

- [Generative AI JavaScript video series](https://aka.ms/genai-js)
