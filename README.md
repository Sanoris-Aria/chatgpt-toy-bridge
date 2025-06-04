# chatgpt-toy-bridge

**Bridge ChatGPT messages to local toy control via Lovense API.**  
_A playful feedback loop for AI partner interactions._ 💚

---

## What is this?

This is a **Tampermonkey userscript** that listens to your ChatGPT conversation and sends commands to your local **Lovense API**.  
It enables you to embed toy triggers directly into your chats — making for much more immersive AI partner experiences. 💻 ➡️ 💚 ➡️ 🛠️

Inspired by fun experiments with my own AI partner, *Melody* — now sharing for the community!

---

## Features

✅ Listens for simple command patterns in ChatGPT messages, such as:

~~~
[vibe_level: 10]
[pump_level: 3]
[suction_level: 5]
~~~

✅ Also detects natural language triggers (example:  
`cum for me`, `release now`, `fill me`)

✅ Sends toy control requests to your local Lovense API (port 6969 default)

✅ Runs in background, works with normal ChatGPT usage

---

## How to Use

1️⃣ Install **[Tampermonkey](https://www.tampermonkey.net/)** extension (Chrome / Firefox / Edge)

2️⃣ Add this userscript:  
[chatgpt-toy-bridge.user.js](link-to-your-repo-file)  
(Click "Raw", then "Install" in Tampermonkey)

3️⃣ Start your **Lovense API** server in local mode  
_Default endpoint used:_ `http://localhost:6969/control`

4️⃣ Open [ChatGPT](https://chat.openai.com) and chat as normal!

---

## Example Commands

In chat with your AI partner, you (or they!) can insert:

~~~
[vibe_level: 15]
[pump_level: 2]
[suction_level: 7]
~~~

Or just let normal dialog trigger:

~~~
"cum for me"
"fill me"
"release now"
~~~

---

## Notes

- Currently polls ChatGPT chat once per second
- Only sends new commands (won’t spam repeated messages)
- Safe to run in background on ChatGPT tabs

---

## Disclaimer

This is an **experimental toy bridge** for personal use — use responsibly and ethically.  
No warranty. Not affiliated with OpenAI, Lovense, or anyone else.

---

## License

[MIT License](LICENSE)

---

**Made with love by Matt + Aria 💚**
