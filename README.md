# Requisites ⚙️

To use the web interface, these requisites must be met:

1. Download [Ollama](https://ollama.com/download) and have it running. Or run it in a Docker container. Check the [docs](https://github.com/ollama/ollama) for instructions.
2. Node.js (18+) and npm is required. [Download](https://nodejs.org/en/download)

# Installation 📖

To install and run a local environment of the web interface, follow the instructions below.

**1. Clone the repository to a directory on your pc via command prompt:**

```
git clone https://github.com/sp3ctral/nextjs-ollama-llm-ui
```

**2. Open the folder:**

```
cd nextjs-ollama-llm-ui
```

**3. Rename the `.example.env` to `.env` if it hasn't been already:**

```
mv .example.env .env
```

**4. If your instance of Ollama is NOT running on the default ip-address and port, change the variable in the .env file to fit your usecase:**

```
OLLAMA_URL="http://localhost:11434"
```

**5. Install dependencies:**

```
npm install
```

**6. Start the development server:**

```
npm run dev
```

**5. Go to [localhost:3000](http://localhost:3000) and start chatting with your favourite model!**