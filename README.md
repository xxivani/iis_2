## Running it

No install and no key are needed to inspect it.

1. Download or clone the repo and open `index.html` in a browser.
2. **Demo mode** (default): scripted and simulated, with no AI. Every screen and state works: the rule check, the Why panel, the feedback popup, the re-explain and the clarify step.
3. **Live mode** (optional): the AI is Groq (default model `openai/gpt-oss-20b`).
   - Create your own key at https://console.groq.com/keys (it starts with `gsk_`).
   - Paste it into the sidebar, click "Load models from my key" and pick a chat model.
4. The key is used only in your browser tab. It is never saved or written to any file, and no key is included in this repository.
5. If your browser blocks the request, run `python3 proxy.py` and tick "Use local proxy". This is a small helper that runs only on your machine and forwards to api.groq.com only.