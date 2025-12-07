# Copy Randomizer – Chrome Extension

Copy Randomizer is a lightweight Chrome extension that watches copy actions and, when configured trigger words or phrases are copied, replaces the clipboard contents with a randomly chosen sentence from a list. It’s great for demos, testing, obfuscation, or just adding a bit of unpredictable fun to your clipboard.

---

## 🔹 Features

- Monitors all copy actions in the browser
- Detects configured trigger words and phrases
- Replaces clipboard content with a random sentence
- Fast, lightweight, and easy to use
- Works instantly with standard copy shortcuts

---

## 🔹 How It Works

1. You select and copy text as usual.
2. The extension checks whether the copied text contains any trigger word or phrase.
3. If a match is found, the clipboard text is replaced with a randomly selected replacement sentence.
4. When you paste, you’ll see the randomized result instead of the original text.

---

## 🔹 Installation (Developer Mode)

1. Clone or download this repository:
   - `git clone https://github.com/dachi-khelashvili/copy-randomizer.git`
   - Or download and extract the ZIP file

2. Open Google Chrome and go to:
   - `chrome://extensions`

3. Enable **Developer mode** (top right corner).

4. Click **Load unpacked**.

5. Select the project folder (the one containing `manifest.json`).

6. The Copy Randomizer extension is now installed and ready to use.

---

## 🔹 Usage

1. Make sure the extension is enabled.
2. Copy any text on a webpage.
3. If the copied content contains a trigger word or phrase, it will be replaced automatically.
4. Paste the text anywhere to view the randomized result.

---

## 🔹 Configuration

Trigger words and their randomized replacement sentences are defined inside the extension’s JavaScript files.

To update them:
1. Open the main script file (for example `content.js`).
2. Update the trigger word list and replacement sentence arrays.
3. Save the file.
4. Reload the extension from `chrome://extensions`.

Your changes will apply immediately.

---

## 🔹 Project Structure

Typical structure:

- `manifest.json` – Chrome extension configuration
- `content.js` – Copy listener and clipboard replacement logic
- `background.js` (optional) – Background processes
- `icons/` – Extension icons
- `README.md` – Project documentation

---

## 🔹 Common Use Cases

- UI and product demos
- Testing clipboard-based workflows
- Obfuscating sensitive copied content
- Fun and experimental clipboard behavior

---

## 🔹 Troubleshooting

**Nothing changes when copying text**
- Confirm the extension is enabled.
- Reload both the extension and the webpage.
- Verify that trigger words are correctly defined.

**Randomization is inconsistent**
- Some websites override copy events.
- Test on a simple page like a blog article.

---

## 🔹 License

MIT License (or add your preferred license).

---

## 🔹 Author

Developed by **Dachi Khelashvili**  
GitHub: https://github.com/dachi-khelashvili