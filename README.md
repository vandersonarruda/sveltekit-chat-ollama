# SvelteKit Chat with Ollama

This is a quick test application demonstrating a chatbot powered by AI that runs locally. Currently, only the chat functionality is working.

## Project Overview

This project demonstrates how to build a simple chatbot using SvelteKit, integrated with AI models provided by Ollama and the Vercel AI SDK.

## Technologies and Tools

- **[Vercel AI SDK](https://sdk.vercel.ai/):** A toolkit from Vercel for integrating AI into web projects.
- **[Ollama](https://ollama.com/):** A platform that allows using various Large Language Models (LLMs) locally, such as Gemma 2 from Google.
- **[SvelteKit](https://kit.svelte.dev/):** A framework for building web applications using Svelte.
- **[Tailwind CSS](https://tailwindcss.com/):** A utility-first CSS framework for creating responsive user interfaces.

## Requirements

- **Ollama:** This application requires Ollama to be installed on your machine. You can download it from [Ollama's website](https://ollama.com/download) or install it on macOS using Homebrew:
  ```sh
  brew install ollama
  ollama pull gemma2
  ```

## Setting Up the Project

**Clone the Repository:**

```sh
git clone https://github.com/maykbrito/sveltekit-chat-ollama-vercel
cd sveltekit-chat-ollama-vercel
pnpm i
pnpm run dev -- --open
```

## Features

- Chat Functionality: Users can interact with the chatbot, which uses AI models from Ollama to generate responses.
- SvelteKit: The project is built with SvelteKit, offering a robust framework for developing web applications.
- Tailwind CSS: Tailwind is used for styling, providing a utility-first approach to CSS.
