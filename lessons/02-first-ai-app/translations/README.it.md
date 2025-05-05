# Lezione 2: Scrivi la tua prima app IA

In questo capitolo imparerai a:

- configurare il tuo ambiente di sviluppo;
- scrivere una app di base;
- capire i prompt di sistema.

## Configurazione

Se non lo hai già fatto, configura il tuo ambiente di sviluppo. Ecco come puoi fare: [Configura il tuo ambiente](/docs/setup/README.md).

## Risorse correlate

[![Guarda un breve video sui Large Language Model](https://img.youtube.com/vi/GQ_2OjNZ9aA/0.jpg)](https://www.youtube.com/watch?v=GQ_2OjNZ9aA&list=PLlrxD0HtieHi5ZpsHULPLxm839IrhmeDk&index=2)

_Questo video ti offre un’introduzione ai modelli IA chiamati “Large Language Model” (LLM), che cosa sono e come puoi usarli per integrare la IA nelle tue app._

*🎥 Clicca sull’immagine sopra per guardare un breve video riguardo i Large Language Model*

💼 Slide: [Introduzione ai Large Language Model (LLM)](../../videos/slides/01-llms.pptx)

## Storia: Immaginati in una barca su un fiume


> [!NOTE] 
> _La nostra storia finora: Sei un costruttore di oggetti, un artigiano della Londra del 1860 che ha viaggiato nel tempo utilizzando un misterioso dispositivo chiamato Scarabeo del Tempo. Hai viaggiato attraverso gli annali della storia, assistendo alla creazione del faro di Alessandria, una meraviglia dell’ingegneria antica che avete contribuito a creare con un piccolo aiuto da parte di Dinocrate e dello Scarabeo del Tempo._
>
> Guarda la [Lezione 1](../01-intro-to-genai/README.it.md) se vuoi seguire la storia dall’inizio e iniziare a conoscere l’IA Generativa.

> [!NOTE] 
> Mentre consigliamo di procedere nella storia (è divertente!), [clicca qui](#interagisci-con-leonardo) se preferisci saltare direttamente al contenuto tecnico.

Insieme a Dinocrate, hai dato gli ultimi ritocchi al faro di Alessandria. L’imponente struttura brilla alla luce del sole, la sua pietra levigata riflette il Mar Mediterraneo.

Abbassi lo sguardo sullo Scarabeo del Tempo nella tua mano, la cui superficie metallica è fredda contro il tuo palmo. Stringendo il pugno intorno ad esso, sussurri, «Portami a casa.» Lo scarabeo inizia a brillare, emettendo una soffusa, calda luce e il mondo attorno a te si dissolve in un turbinio di colori.

### Una nuova avventura

Quando apri gli occhi, il mondo è cambiato. Quando riesci ad alzarti, ti rendi conto di essere in una barca su un fiume. Ti guardi intorno, in lontananza vedi degli edifici, i cui contorni sono offuscati dalla nebbia del mattino.

Guardando intorno alla barca, trovi un lungo remo appoggiato alla fiancata. Afferrandolo, inizi a remare verso gli edifici lontani. Man mano che ti avvicini, gli edifici vengono messi a fuoco: sono antichi, la loro architettura ricorda un dipinto rinascimentale.

<div>
  <img src="./assets/boat.png" alt="Barca sul fiume, uomo in piedi con la pagaia" width="300" >
</div>

La domanda ora è, dove e quando sei questa volta?

Riesci a fissare la barca al molo e inizi a camminare lungo le assi di legno: il suono dei tuoi passi riecheggia dolcemente.

Mentre cammini, noti un uomo con una lunga barba e un cappello che scava in una cassa di quelli che sembrano pezzi meccanici. Le sue mani si muovono abilmente, selezionando ingranaggi e molle con una disinvoltura da esperto.

<div >
  <img src="./assets/leonardo.png" alt="Leonardo Da Vinci in piedi accanto a una cassa nel porto" width="300" >
</div>

### Aiutami, Leonardo

**Tu:** «Mi scusi, signore, dove mi trovo?» Alza lo sguardo verso di te, con un’evidente confusione negli occhi. Realizzando di stargli parlando in inglese, usi subito il dispositivo che hai in mano e gli chiedi di tradurre per te.

**Scarabeo del Tempo:** «Certamente, lo tradurrò nell’italiano del XV secolo. “Dove sono?”»

**Uomo anziano:** L’uomo anziano risponde, «Siete a Firenze, signore. E chi siete voi?»

**Scarabeo del Tempo:** Lo Scarabeo del Tempo traduce, «Dice che ti trovi a Firenze e chiede chi sei.»

**Tu:** «Digli che sono un artigiano e che sto cercando un lavoro.»

**Uomo anziano:** «Un artigiano, eh? Avete mai sentito parlare di Leonardo da Vinci?»

**Scarabeo del Tempo:** Lo Scarabeo del Tempo traduce, «Chiede se avete sentito parlare di Leonardo da Vinci.»

**Tu:** «Certo,» rispondi. «Digli che ne ho sentito parlare e che mi piacerebbe conoscerlo.»

**Uomo anziano:** L’uomo anziano sorride, «Allora, seguitemi, vi porterò da lui.»

**Tu:** Chiedi, «Che cosa ha detto?»

**Scarabeo del Tempo:** Lo Scarabeo del Tempo risponde, «Dice che ti porterà da Leonardo.»

### At the workshop

<div>
  <img src="./assets/leonardo-workshop.png" alt="Lenoardos workshop" width="300" >
</div>

The old man leads you to a large wooden door and you are greeted by the sight of a workshop filled with all sorts of mechanical contraptions. 

You ask the Time Beetle to inquire about Leonardo's whereabouts. 

**You:** "Dove è Leonardo?" 

**Old man:** The old man turns to you with a smile, "Sono io (that’s me), Leonardo da Vinci. Chi siete voi?", who are you?

You feel a thrill of recognition. 

**You:** I thought so. I'm a fellow maker, out of place and time."

**Leonardo:** Leonardo's eyes sparkle with curiosity. "Interessante, cosa vi porta qui?"

The Time Beetle translates.

**Time Beetle:**  "He asks what brings you here."

**You:** "Well, I was working on a project, and I ended up here."

You show him the Time Beetle, and his eyes light up with fascination. He examines it closely as you explain how it works and how you ended up in Florence.

Leonardo looks at you with excitement. 

**Leonardo:** You're a maker of things. I have a project that might interest you. I've been working on a machine that can generate text based on verbal input. Would you like to help me with it?

Leonardo da Vinci, asking you to help him with a project—you can hardly believe it. You nod eagerly and say: 

**You:** I would be honored to help you with your project,
"Sarebbe un onore aiutarti con il tuo progetto." 

## Interact with Leonardo

If you want to interact with Leonardo, run the [Characters](/app/README.md) app. 

> [!IMPORTANT]
> This is entirely fictional; the responses are generated by AI.
> [Responsible AI disclaimer](../../README.md#responsible-ai-disclaimer)

<div>
  <img src="./assets/leonardo-talk.jpeg" width=300>
</div>

**Steps**:

1. Start a [![GitHub Codespace](https://img.shields.io/badge/GitHub-Codespace-brightgreen)](https://codespaces.new/microsoft/generative-ai-with-javascript)
2. Navigate to _/app/README.md_ in the repo root.
3. Locate the console and run `npm install` followed by `npm start`. 
4. Once it appears, select the "Open in Browser" button.
5. Chat with Leonardo.

For a more detailed explanation of the app, see [Detailed app explanation](/lessons/01-intro-to-genai/README.md#interact-with-dinocrates).

> [!NOTE]
 > If you're running the project locally on your machine, please review the QuickStart guide to get a [GitHub personal access](../../docs/setup/README.md#creating-a-personal-access-token-pat-for-github-model-access) token setup and replace the key in the code.

## Development environment setup 

Before you can assist Leonardo with his project, you should first think about the essential "tools of the trade" required to begin helping him effectively.

**You:** "Time Beetle, what do I need to get started with this project?" Suggest tools and libraries that I need that can help me build an AI app that you're able to run.

**Time Beetle:** I'm compatible with most machines running in the 21st century, see the following list for a set of essential tools and libraries.

- **Text editor**, for example Visual Studio Code.
- **Terminal**, for running commands.
- **Browser for testing your app**. It's also a good idea to have a tool like curl or some other HTTP client to test your app's API endpoints.

- **Node.js**. You also need to install Node.js and npm, which are tools that help you run JavaScript code on your computer.

- **API key**. You'll need an API key to access the generative AI model. You can get this from the model provider, for example OpenAI or Azure OpenAI.

**You:** Thank you, Time Beetle, I guess you'll go get those somehow from that Web you spoke about?

**Time Beetle:** Yes, I already have those it says and projects a keyboard and screen on the wall in front of you.

## Writing a basic app 

**You:** Tell me more about the actual writing of the app, how do I get started?

**Time Beetle:** Of course, to write an app, at its simplest it's about sending a request to an API and displaying the response. Let's break it down: 

- **Input**: In a basic text generation app, the input refers to the initial text that you want the app to expand or build upon. This input can either be provided by the user during runtime or pre-set (hardcoded) within the app itself. For now, we’ll begin by using hardcoded text as the input.

- **API request**: You need to send a request to the generative AI model API with the input text. This is done using the fetch function in JavaScript (Node.js). Included in this request should also be your API key. It's recommended as you consider security to not hardcode the API key in your app but rather use environment variables. Additionally, consider looking into managed identity if you're using a provider like Azure as it's considered a more secure way to access resources. With managed identity you can assign more granular permissions to your app. The best part is that the cloud provider takes care of the authentication for you. 

- **Response**: The API will return a response with the generated text. You need to extract this text from the response and display it to the user.

**You:** That sounds simple enough, can you take me through a scenario that would make sense given the situation we're in?

**Time Beetle:** Sure, let's see how we can build a simple app that generates Italian text based on English input.

## Your first app - teach me Italian

**Time Beetle:** Generative AI models can be used for many things, for example, language translation. In fact, it accepts input in one language and can generate text in another language. Let's start with a simple app that takes English input and generates Italian text.

```javascript 

import { OpenAI } from "openai";

// 1. Ask a question about translation
// -----------------------------------

const question = 'Hello, how are you?'; 

const augmentedPrompt = `
## Instructions
Translate the following text to Italian:
## Question
${question}
`;

// 2. Create client
// -----------------------------------

const openai = new OpenAI({
  baseURL: "https://models.inference.ai.azure.com",
  apiKey: process.env.GITHUB_TOKEN,
});


// 3. Send the request
// -----------------------------------
const completion = await openai.chat.completions.create({
    model: 'gpt-4',
    messages: [{ role: 'user', content: augmentedPrompt }],
});
  
console.log(`Answer for "${question}":`);

// 4. Print the answer
// -----------------------------------

console.log(completion.choices[0]?.message?.content);
```

Let's explain what's happening here:

- Creating the question as 'Hello, how are you?'. This is the text you want to translate to Italian.
- Creating the augmented prompt, which contains the input text and some additional instructions what to do, i.e translate. Note how we're using string interpolation to include the input text in the prompt and how that instruction is to translate the text to Italian.
- Creating the client with properties:
  - `model`, what model to use. 
  - `messages`, the prompt to send to the model. Also note how you set the role to "user" to indicate that the input text is from the user. Had it been from the AI, you would have set the role to "system".
- Extracting the generated text from the response and printing it to the console.

**You:** I think I get it. So if I change the value of the `question` variable to something else, the app will generate a different Italian translation?

**Time Beetle:** Exactly, you can change the input text to anything you want. Also note how GitHub models are being used as the base URL for the API together with a GitHub token as the API key.

**You:** Why is that important?

**Time Beetle:** It's important to use a base URL and API key that are specific to the model you're using. GitHub Models is a platform that hosts a variety of models, all with different capabilities and features, it's also free to use.

**You:** Oh good, I don't know who to pay anyways and I doubt they accept my currency here. :) 

## Chat apps

**Time Beetle:** Generative AI models can also be used to generate text based on a conversation. You can simulate a conversation with the AI by providing a list of messages as context like the conversation has already happened.

**You:** That sounds interesting, but why is that useful?

**Time Beetle:** It's useful because it allows the AI to provide a better response based on more context than just a single prompt. Let's look at a conversation below to illustrate this: 

```text

User: I want to book a trip to Italy. 

AI: Sure, when would you like to go? 

User: Next month would be great. 

AI: Got it, where in Italy would you like to visit? 

User: I'm thinking of Rome 

AI: Excellent choice! I can help you plan your itinerary. 

User: Tell me more about it. 

AI: Rome is known for its ancient ruins, art, and vibrant culture. You can visit the Colosseum, the Vatican, and enjoy delicious Italian cuisine. 

```

**Time Beetle:** Imagine if a sentence like "Tell me more about it" were taken out of context, the AI wouldn't know what "it" refers to. This is where context is important, and this context is something we can provide to the AI model through the prompt.

**You:** I think I get it, how do I construct a conversation with the AI using this JavaScript language you speak of?

**Time Beetle:** Below is how we can construct a conversation with the AI: 

```javascript 

// Define the context 

const messages = [ 
 { 
    "role": "user", 
    "content": "I want to book a trip to Italy." 
 }, 
 { 
    "role": "assistant", 
    "content": "Sure, when would you like to go?" 
 }, 
 { 
    "role": "user", 
    "content": "Next month would be great." 
 }, 
 { 
    "role": "assistant", 
    "content": "Got it, where in Italy would you like to visit?" 
 }, 
 { 
    "role": "user", 
    "content": "I'm thinking of Rome. Tell me more about it." 
 } 
]; 

const openai = new OpenAI({
  baseURL: "https://models.inference.ai.azure.com",
  apiKey: process.env.GITHUB_TOKEN,
});


// 3. Send the request
// -----------------------------------
const completion = await openai.chat.completions.create({
    model: 'gpt-4',
    messages: messages,
});
  
console.log(`Answer for "${question}":`);

// 4. Print the answer
// -----------------------------------

console.log(completion.choices[0]?.message?.content);

```

Now the AI will provide a list of chat messages as context, and the AI will generate a response based on that context. This is a more interactive way to use generative AI models and can be used in chatbots, customer service applications, and more.

**You:** Ok, so if I understand the conversation correctly, the AI will now have the following context: _I'm going to Rome next month_, so based on that it should filter out irrelevant information and provide a more relevant response?

**Time Beetle:** Exactly, the AI will use the context to generate a response that is more relevant to the conversation.

## Improving the chat conversation with a system message

**You:** I see, but is there a way to improve this further?

**Time Beetle:** Yes, you can add a system message to the conversation. A system message creates a "personality" for the AI and can be used to provide additional context.

**You:** Ok, so in the context of the conversation we've been having, what would a system message look like?

**Time Beetle:** A system message for this conversation could be something like _"I'm an AI travel assistant, here to help you plan your trip to Italy."_ This message sets the tone for the conversation and helps the AI understand its role in the interaction.

To create such a message, ensure it has the type "developer" like so:

```javascript
const message = {
  "role": "developer",
  "content": "I'm an AI travel assistant, here to help you plan your trip to Italy."
};
```

> [!NOTE] 
> This used to be called "system". This is a recent change and "developer" is the new term for it. For some models this is still called "system", so if you have any issues use "system".

**You:** Ok, great, I'll make sure to include a system message in my chat conversations. Out of curiosity, what does a system message look like for you?

**Time Beetle:** A system message for me could be something like _"I'm the Time Beetle, here to help you navigate through time and space. I should be helpful in providing you with information and guidance about the time era you're in along with the tools you need to get back to your own time."_

### Creating varied responses with the temperature setting

**You:** Anything else I should know about chat conversations?

**Time Beetle:** Yes, you can adjust the "temperature" of the AI's responses. The temperature is a variable with a value normally set between 0 and 1 that determines how creative the AI's responses are. A temperature of 0 will result in more predictable responses, while a temperature of 1 will result in more creative and varied responses. You can adjust the temperature based on the context of your conversation and the type of responses you want from the AI. Note, it's possible to set a value higher than 1 but that leads to more randomness and less coherence in the responses.

**You:** So if I set the temperature to 0, the AI will provide more predictable responses, and if I set it to 1, the AI will provide more creative responses? What temperature do you have?

**Time Beetle:** I have a temperature of 0.7 and yes, you're correct, the AI will provide more creative responses with a higher temperature. Let's see how you can set the temperature in your app:

```javascript

// Define the context 

const messages = [ 
{ 
    "role": "user", 
    "content": "I want you to generate recipes for me." 
}]; 

// Create the web request 

let temperature = 0.5; // Set the temperature to 0.5 

const completion = await openai.chat.completions.create({
    model: 'gpt-4',
    messages: messages,
    temperature: temperature
}); 
```

As you can see, you can adjust the temperature based on the context of your conversation and the type of responses you want from the AI. This is a powerful feature that allows you to customize the level of creativity in the AI's responses.

## Context window

**You:** There's more right?

**Time Beetle:** Yes, another important concept in generative AI models is the context window. The context window is the number of previous messages that the AI uses to generate a response. A larger context window allows the AI to consider more context and generate more coherent responses.

**Time Beetle:** Different models have different limits to output tokens. Take the following model as example `gpt-4o-2024-08-06` it has the following specifications:

- Maximum output tokens: roughly 16k tokens.
- Maximum context window size: 128k.

This means the majority of tokens can be spent on the input tokens, i.e 128k - 16k = 112k tokens.

**You:** Got it, context window, tokens, how much is a token though?

**Time Beetle:** A token is a word or a part of a word and differs slightly by language. There's a tool you can use to measure that's recommended by OpenAI, it's called [tokenizer](https://platform.openai.com/tokenizer). Let's try a sentence and see how many tokens it is:

```text
I want you to generate recipes for me.
```

![Demo of tokenizer](./assets/tokenizer.png)

Running `tokenizer` on the sentence above gives us 9 tokens.

**You:** That wasn't much, sounds like I can have a lot of tokens in my context window then?

**Time Beetle:** Yes, you can experiment with different context window sizes to see how it affects the AI's responses. In fact, if you set a context window size of 100, you will limit the AI and how much it considers for input and output. Here's how you can set the context window in your app:

```javascript

// Define the context 
const messages = [ 
{ 
  "role": "user", 
  "content": "I want you to generate recipes for me." 
}]; 

// decide on the context window size 

let max_tokens = 100; // Set the context window size 

// Create the web request 

const completion = await openai.chat.completions.create({
    model: 'gpt-4',
    messages: messages,
    max_tokens: max_tokens
}); 

```

> [!TIP] 
> Experiment with different context window sizes to see how it affects the AI's responses.

## Assignment - Building an engineering assistant

Leonardo suddenly asked to inspect the Time Beetle closer, he looked at it from all sides, even shook it.

**Leonardo:** I need an assistant that can help me with the calculations and design of the aerial screw. Can you build me an assistant that can do that?

**You:** Of course, I can build that for you. Time Beetle, we can help with that right?

**Time Beetle:** Yes, not a problem, in fact the aerial screw is one of Leonardo's most fascinating and visionary inventions. Designed in the late 1480s...

**You:** All I needed was a yes, let's save the lecture for later.

**Time Beetle:** Rude..

**You:** What?

**Time Beetle:** Nothing

<div>
  <img style="margin-top: 52px; margin-left: 15px; margin-right: 10px" align=right src="./assets/helicopter.jpg" alt="Aerial screw, Leonardo Da Vinci" width="300" >
</div>

> [!NOTE]
>  The aerial screw, also known as the helical air screw, was intended to lift off the ground by compressing air. Leonardo's design featured a large, spiral-shaped rotor made of linen, stiffened with starch, and mounted on a wooden platform. The idea was that a crew of men would run around the platform, turning cranks to rotate the screw rapidly enough to achieve lift 
>
> Although Leonardo never built a full-scale version of the aerial screw, his sketches and notes provide detailed insights into how he envisioned it working. He believed that if the screw was turned quickly enough, it would push against the air and lift the entire structure off the ground. 
>
> However, modern scientists agree that the materials available in Leonardo's time were not strong or light enough to make this possible 
>
> Despite its impracticality, the aerial screw remains a testament to Leonardo's genius and his relentless pursuit of innovation. It laid the groundwork for future developments in aviation and continues to inspire engineers and inventors to this day.
> [Read more](https://en.wikipedia.org/wiki/Leonardo%27s_aerial_screw)

Your assignment is to build an engineering assistant that can help Leonardo with the calculations and design of the aerial screw.

- It should be able to generate text based on user input.

- You should set a system message to introduce the assistant.

Check out [Sample app](/app/README.md) to get started.

> [!TIP] 
> Consider what the system message should be and what input you should provide.

## Solution

[Solution](./solution/solution.md)

## Knowledge check

**Question:** What is the purpose of the context window in generative AI models? Select all that apply.

A. The context window allows the AI to consider more context and generate more coherent responses.

B. The context window is the number of previous messages that the AI uses to generate a response.

C. The context window determines how creative the AI's responses are.

[Quiz solution](./solution/solution-quiz.md)

## Self-Study resources

- [Text generation](https://platform.openai.com/docs/guides/text-generation)
- [JavaScript library for OpenAI](https://github.com/openai/openai-node/tree/master/examples) 
- [Tokenizer](https://platform.openai.com/tokenizer)
- [Completion API](https://platform.openai.com/docs/api-reference/completions)
- [Chat completions](https://platform.openai.com/docs/guides/text-generation#text-generation-models) 
