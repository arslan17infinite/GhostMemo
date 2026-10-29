# GhostMemo 👻

GhostMemo is a small memory journal with a ghost-story feature. Save a title and story, then ask a local AI model to turn that memory into a mysterious fictional retelling.

## Features

- Save memories in your browser.
- Keep saved memories after refreshing the page.
- Delete memories from the archive.
- Generate a ghost-story retelling with Gemma 3 1B running locally through Ollama.

## What you need

- A web browser
- [Ollama](https://ollama.com/)
- The `gemma3:1b` model downloaded in Ollama
- Visual Studio Code with the Live Server extension

## Run GhostMemo

1. Open Ollama and make sure the `gemma3:1b` model is available.
2. Open `index.html` in Visual Studio Code.
3. In VS Code, click **Go Live** to open GhostMemo in your browser.
4. Save a memory, then click its ghost-story button.

## Privacy and limitations

Memories are saved in this browser using local storage. They are not uploaded to a GhostMemo server.

The storyteller sends the memory text to Ollama running on your own computer. Generated stories are fictional retellings and may add details that were not in the original memory.

GhostMemo is a learning project. Keep Ollama available only on your own computer; do not expose its connection to the internet.

## AI model

GhostMemo uses Gemma 3 1B through Ollama. Gemma 3 1B is an open-weight model that runs locally.
