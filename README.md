# 🩸 Wealop

Wealop is a tool that allows you to jam Discord users and (in the future updates) servers. It can be used to spam message requests or ping requests. It supports Linux, macOS, Windows

**Key Features:**
- 🔵 **Load multiple bot tokens**: Works with java by going and modifying the `tokens.json` script with your own discord BOT(app)
- 🎯 **Send a custom message multiple times to a user**
- 🚀 **Colored terminal UI**: User-friendly UI for discord spamming and server attacks using `pystyle`
- 🖥️ **Async-powered**: using `discord.py`

This tool was created for educational purposes only. I do not take any responsibility for the misuse of this tool.

<img width="1377" height="766" alt="image" src="https://github.com/user-attachments/assets/37f8025c-dac9-4d0b-991c-2fb2d8668d87" />


> ⚠️ This tool is for **educational and testing purposes only**. Abuse of this tool may violate Discord's [Terms of Service](https://discord.com/terms).

---

## ✨ Features

- Load multiple bot tokens from a `tokens.json` file
- Send a custom message multiple times to a user
- Colored terminal UI using `pystyle`
- Async-powered using `discord.py`

---

## 📦 Requirements

Install required packages with:

```bash
pip install -r requirements.txt
````

---

## 📄 requirements.txt

```text
discord.py
pystyle
```

---

## 🚀 Usage

1. Create a `tokens.json` file with this format:

```json
[
    "BOT_TOKEN_1",
    "BOT_TOKEN_2",
    "BOT_TOKEN_3"
]
```

2. Run the script:

```bash
python main.py
```

3. You will be prompted to enter:

   * User ID to send messages to
   * File name of your token list (e.g. `tokens.json`)
   * Message to send
   * Number of times to send it

---

## 👁 Preview

```text
Enter the user ID to message: 123456789012345678
Enter the bot token file name (e.g., tokens.json): tokens.json
Enter the message to send: Hello from all my bots!
Enter how many times to send the message: 3

Bot1 successfully sent messages.
Bot2 successfully sent messages.
...
```

---

## 🙏 Credits

Made with ❤️ by (yours truly)

---

## 📜 License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.
---
