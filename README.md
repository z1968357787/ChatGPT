<h2 align="center"><img src="https://raw.githubusercontent.com/gencay/vscode-chatgpt/main/images/iconWhite.png" height="64"><br>Ask ChatGPT</h2>
<p align="center"><strong>ChatGPT conversations in Visual Studio Code</strong></p>

[![Badge for version for Visual Studio Code extension gencay.vscode-chatgpt](https://vsmarketplacebadges.dev/version/gencay.vscode-chatgpt.png)](https://marketplace.visualstudio.com/items?itemName=gencay.vscode-chatgpt)

# Level up your coding experience

- 🍻 Optimized for dialogue! Have a conversation with ChatGPT with follow-ups.
- 💯 Get help from ChatGPT within vs-code for implementing test cases, explaining it or finding bugs.
- 📝 Create projects/files with one click using built-in actions in the conversation view.
- ⚡ Built-in syntax highlighting for ChatGPT suggested code.
- 🖼️ Icon is generated by dall-e-2.

<img src="https://raw.githubusercontent.com/gencay/vscode-chatgpt/main/images/chatgpt-gif.gif">

# Features

The extension comes with context menu commands, copy/move suggested code into editor with one-click, conversation window and customization options for OpenAI's ChatGPT prompts.

## ChatGPT conversation window in vs-code

### 🍻 Optimized for dialogue

<img src="https://raw.githubusercontent.com/gencay/vscode-chatgpt/main/images/conversation-mode.png">

---

### Edit and resend a previous prompt

<img src="https://raw.githubusercontent.com/gencay/vscode-chatgpt/main/images/edit-resend.png">

---

### Copy or insert the code ChatGPT is suggesting right into your editor.

<img src="https://raw.githubusercontent.com/gencay/vscode-chatgpt/main/images/code-actions.png">

---

### Ask free-form text questions that will be listed in the conversation window. The conversation is kept in cache until vs-code instance is closed.

<img src="https://raw.githubusercontent.com/gencay/vscode-chatgpt/main/images/rust.png">

---

## Add tests for your code

Right click on a selected block of code, run `ChatGPT: Add Tests` command for ChatGPT to write tests for you.

<img src="https://raw.githubusercontent.com/gencay/vscode-chatgpt/main/images/rust-test.png">

---

## Find bugs in your code

Right click on a selected block of code, run `ChatGPT: Find bugs` command for ChatGPT to analyze and find bugs in your code.

<img src="https://raw.githubusercontent.com/gencay/vscode-chatgpt/main/images/rust-problem.png">

---

## Improve & optimize your code

Right click on a selected block of code, run `ChatGPT: Optimize` command for ChatGPT to add suggestions to your code to improve.

<img src="https://raw.githubusercontent.com/gencay/vscode-chatgpt/main/images/python-optimize.png">

---

## Explain your code

Right click on a selected block of code, run `ChatGPT: Explain` command for ChatGPT to explain the selected code.

<img src="https://raw.githubusercontent.com/gencay/vscode-chatgpt/main/images/python-explain.png">

# Customization settings

- You can configure the commands to use any prompts for the selected code!
- Opt-in to receive notification when ChatGPT sends you a message!

<img src="https://raw.githubusercontent.com/gencay/vscode-chatgpt/main/images/settings.png">

# Setup

Follow the instructions here to get your access token: https://github.com/transitive-bullshit/chatgpt-api#session-tokens

During your first interaction with the extension, you will be asked to enter your access token.

<img src="https://raw.githubusercontent.com/gencay/vscode-chatgpt/main/images/setup.png">

# Troubleshooting

If the bot isn't responding, try clearing your cache by running the `ChatGPT: Clear session` command.

It's possible that openai systems may experience issues responding to your queries due to high-traffic from time to time.

# Credits

- 💻 Open AI ChatGPT: https://chat.openai.com/
- 🖼️ Open AI Dall-E-2: https://openai.com/dall-e-2/
- 🧪 This extension uses unofficial OpenAI APIs. https://github.com/transitive-bullshit/chatgpt-api
