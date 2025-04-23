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

> [!NOTA] 
> Iniziamo con una panoramica della storia: una storia che collega il passato e il futuro! Procedendo in questo curriculum, ti imbarcherai in un’avventura emozionante, viaggiando indietro nel tempo per collaborare con alcune delle più grandi menti della storia. Insieme, affronterete sfide ed esplorerete come l’IA Generativa può rivoluzionare le tue applicazioni JavaScript._

> [!NOTA]  
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

_"Caro amico,_

_ti invio questa lettera per aiutarti nei tuoi sforzi con l’automa. È fondamentale che continui questo lavoro. In allegato c’è la chiave della biblioteca. Incontriamoci lì oggi alle 15:00._

_Tuo,_

_Charles Babbage."_

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

**Dinocrate:** «Benvenuto, viaggiatore,» he says warmly. «Sono Dinocrate, l’architetto di questa grande città. Il tuo arrivo è stato predetto.»

**Tu:** «Davvero? Voglio dire, di certo lo è stato. Sono qui per aiutare, credo.»

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
> In 300 BC, Alexandria was a thriving city founded by Alexander the Great in 331 BC. It quickly became one of the greatest cities of the Hellenistic world. Designed by Alexander's chief architect, Dinocrates, it became a major port and cultural hub.
>
> Alexandria was known for its impressive structures, including the Pharos (lighthouse), one of the Seven Wonders of the Ancient World, and the legendary Library of Alexandria. The city’s strategic location made it a key center for trade and knowledge exchange.
>
> Under the Ptolemaic Kingdom, which followed Alexander’s death, Alexandria grew into one of the most prosperous and influential cities of its time.

## Interact with Dinocrates

If you want to interact with Dinocrates, run the [Characters](/app/README.md) app. 

> [!IMPORTANT]
> This is entirely fictional; the responses are generated by AI.
> [Responsible AI disclaimer](../../README.md#responsible-ai-disclaimer)

<div>
   <img src="./assets/dinocrates.png" alt="Dinocrates wearing a toga" width="300">
</div>

**Steps**:

1. Start a [![GitHub Codespace](https://img.shields.io/badge/GitHub-Codespace-brightgreen)](https://codespaces.new/microsoft/generative-ai-with-javascript)
2. Navigate to _/app_ in the repo root.
3. Locate the console and run `npm install` followed by `npm start`. 
4. Once it appears, select the "Open in Browser" button.
5. Chat with Dinocrates.

> [!NOTE]
 > If you're running the project locally on your machine, please review the QuickStart guide to get a [GitHub personal access](../../docs/setup/README.md#creating-a-personal-access-token-pat-for-github-model-access) token setup and replace the key in the code.

### Code sneak peek

While there is still a lot more to cover in this Generative AI curriculum, let's take a quick peek at the AI code to begin learning about using JavaScript with AI.

Inside of `/app/app.js` you'll find an `app.post`function that handles the Generative AI functionality. It's shown next:

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

Here's a step-by-step summary of what the function does:

1. **Extract Message from Request**: The function extracts the message from the request body (req.body).
2. **Create Prompt Array**: It constructs an array of messages, including a system message and the user's prompt message.
3. **Initialize OpenAI Client**: An OpenAI client is initialized with the base URL and API key from environment variables. A _gpt-4o-mini_ model from [GitHub Models](https://github.com/marketplace/models) is used to process the prompt and return a response.
4. **Send Prompt to OpenAI**: The function logs the prompt and sends it to the OpenAI API to generate a completion.
5. **Handle Response**: If successful, the function responds with the prompt and the completion's answer.
6. **Error Handling**: If an error occurs, it responds with a 500 status and the error message.

> **Note**: [GitHub Copilot](https://github.com/features/copilot) was used to generate this code summary. Generative AI in action!

### What can Generative AI do for me and my Apps?

> [!NOTE]
> You've probably figured out by now that the time beetle works like an AI assistant that you can interact with using natural language, written or spoken.

As your adventure in Alexandria unfolds, you begin to see the possibilities of combining creativity, ingenuity, and cutting-edge tools to solve challenges and transform the world around you.

**You:** Tell me more about lighthouses, you say to your device.

**Time Beetle:** A lighthouse is a tower equipped with a bright light at the top, located near the shore to guide ships at sea. The light serves as a navigational aid, helping sailors avoid dangerous rocks and reefs and safely reach the harbor.

Dinocrates overhears your conversation and adds:

**Dinocrates:** We need a lighthouse to guide our ships safely into the harbor. The seas can be treacherous, and many ships have been lost to the rocks. We need a beacon of light to guide them home.

#### Generative AI application areas

**You:** Lighthouses sound like an interesting area for sure, what else can Generative AI do for me and my apps? 

**Time Beetle:**. In the 21st century, generative AI has revolutionized many industries, from healthcare to finance to entertainment, here are some examples:

- **Chatbot**: A chatbot that can generate human-like responses to user queries. Instead of a static FAQ page, users can interact with a chatbot that provides dynamic responses. This makes for a more engaging and less frustrating user experience.

- **Assistants and Agents** Assistants and agents can carry out more advanced instructions like leveraging tools to call APIs, run code, generate images and more. Advanced agents can carry out goals and carry out tasks autonomously.

- **A content creation tool**:. A tool to generate blog posts and social media posts. Imagine creating campaigns in minutes instead of hours when an e-commerce site has a black Friday sale.

- **Code completion**: A code completion tool that can generate code snippets based on user input. This can be a huge time saver for developers, especially when working on repetitive tasks.

- **Translation** – Translate text between languages with high accuracy.

As you can see, these improvements can both help the front office and the back office of your app and company.

Here's an example of a "chatbot application" in action:

![Image of chat app](https://camo.githubusercontent.com/76f2ad7cd754a2de2b9957d2070448e130e5ba228084b9b4b128e3af9c9f5239/68747470733a2f2f6c6561726e2e6d6963726f736f66742e636f6d2f656e2d75732f73656d616e7469632d6b65726e656c2f6d656469612f636861742d636f70696c6f742d696e2d616374696f6e2e676966) 

**You:** Fascinating, I'll make a note of going to the 21st century to see how these tools are used.

### Generative AI and the JavaScript ecosystem

**Time Beetle:** A popular way to build apps in the 21st century is by using JavaScript. With every programming language, there's an ecosystem around it. This ecosystem includes the programming language itself, libraries and frameworks, community support, and IDEs and tools. In a programming language ecosystem, we're usually talking about the following:

| What | Description | 
|---|---| 
| The programming language itself | Including its syntax and features. |
| Libraries and frameworks    | Available libraries to interact with the generative AI models.                                                         | 
| Community supporting the language| Community matters, especially when trying to learn something new. The community around libraries and frameworks helps decide what libraries to use. It also affects how easy it is to find help when you're stuck. | 

**You:** Interesting, I've heard of programming I think, didn't Ada Lovelace experiment with that and Charles Babbage?

**Time Beetle:** Yes, Ada Lovelace was the first computer programmer, and Charles Babbage was the inventor of the difference engine, a mechanical computer. They were pioneers in the field of computing, laying the foundation for the digital age.

**You:** Were? What do you mean were? I just got a letter from Charles Babbage.

**Time Beetle:** Let's just say that you're in a unique position to interact with historical figures in a way that few others can.

### JavaScript ecosystem

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
