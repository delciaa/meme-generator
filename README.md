# AI Meme-generator
An AI-powered meme creation website that generates funny, creative captions for any image you upload.  
Built with Next.js, TypeScript, and OpenAI’s GPT-4o-mini, it brings together humor and technology in a sleek, easy-to-use interface.


# Features

-  Upload any image and generate a meme caption instantly  
-  Choose from multiple humor styles — sarcastic, wholesome, punny, dark humor, relatable, and more  
-  Powered by **OpenAI GPT-4o-mini** for creative caption generation  
-  “Create Another Meme” option to quickly start over  
-  Clean and responsive UI

# How It Works

1. Upload your image (any format).  
2. Select the humor style — e.g., *sarcastic*, *wholesome*, *punny*, *dark humor*, *relatable*.  
3. The app sends a request to OpenAI’s API.  
4. The AI responds with a short, witty caption.  
5. The caption is displayed below your image in meme style.

##  Local Setup

1 - Clone the repository
```bash
git clone https://github.com/delciaa/meme-generator-ai.git
cd meme-generator-ai

2 - Install dependencies
npm install

3 - Add your OpenAI API key
*Create a file named .env.local in the project root and enter the following:
OPENAI_API_KEY=your_openai_api_key_here

4 - Run it
npm run dev
Open http://localhost:3000 in your browser
