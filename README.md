# Create Sandbox App (Groq + Deepgram)
This starter is an example of how to create a composable Sandbox interaction that runs in a Next.js app.
The project consists of a Next.js app that uses the Sandbox SDK (`sandbox-client`) and a server `server.js` that handles the interaction with other services such as speech-to-text (STT), large language models (LLMs) and text-to-speech (TTS). 

### Environment variables
Start by signing up and getting your API key from [Sandbox.com](https://www.sandbox.com/). Then, fill in the `.env` file in the root of the project and put in the following environment variables:

```bash
NEXT_PUBLIC_SANDBOX_API_KEY="API key from sandbox.com"
DEEPGRAM_API_KEY="API key from deepgram.com"
GROQ_API_KEY="API key from console.groq.com"
```

If you want to try Sandbox but don't have API access to these third parties, ask in Discord and we can help you out with that ([Discord Link](https://discord.gg/yQx49zNF4d)). 

To run the back-end and front-end together, run the following command:


```bash
npm run start
```

### Characters
You can swap out the character by finding one that you like in the [docs](https://docs.sandbox.com/introduction), or [create your own](https://app.sandbox.com/) 

![alt text](media/image.png) ![alt text](media/image-4.png) ![alt text](media/image-2.png) ![alt text](media/image-3.png) ![alt text](media/image-5.png) ![alt text](media/image-6.png)

### Alternative STT, TTS and LLM providers 
You can of course replace Deepgram with AI services with your own preference, or even build your own.
The only requirement for Sandbox to work is that audio is sent using PCM16 format and 16KHz sample rate or sending it through MediaStream. If you're having trouble getting nice audio, feel free to ask for help in Discord.  

## Links
[\[Sandbox\]](https://sandbox.com)   
[\[Deepgram\]](https://deepgram.com)
[\[Groq\]](https://groq.com)


## Deploy on Vercel

An easy way to deploy your avatar interaction to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme). 
# Sandbox