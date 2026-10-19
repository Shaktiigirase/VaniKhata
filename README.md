# VaniKhata

Voice-based Hindi/Marathi expense and sales ledger for small shopkeepers. A single-file web app: no install, no server, no sign-up. Entries are saved only on the device.

## Host it on GitHub Pages

1. On github.com, create a new **public** repository named `vanikhata`.
2. Click **Add file > Upload files**, upload `index.html` and `README.md`, then **Commit changes**.
3. Go to **Settings > Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main**, folder **/(root)**, then **Save**.
4. Wait 1 to 2 minutes. Your link is `https://<your-username>.github.io/vanikhata/`.

## Use it on iPhone

1. Open the link in **Safari** and allow the microphone when asked.
2. Turn on dictation if voice fails: **Settings > General > Keyboard > Enable Dictation**.
3. Optional: tap **Share > Add to Home Screen** to open it like an app.

## How to speak

Say one sentence with the item, amount and (optionally) the type.

- "chai pachaas rupaye" saves a sale of Rs 50
- "dudh kharcha dedh sau" saves an expense of Rs 150
- "पेट्रोल खर्च ढाई सौ" saves an expense of Rs 250

Always check the confirm card before saving. Words like kharcha/खर्च mark an expense; bikri/बिक्री/becha mark a sale. With no keyword it assumes a sale.

## Notes

- Voice needs internet, because the browser sends audio to its speech service.
- Marathi recognition may not work on some iPhones. Use Hindi, or tap the mic on the iPhone keyboard inside the "Or type here" box.
- Data lives in the browser. Clearing Safari website data deletes it, so export a CSV regularly.
- Number words handled: ek to nabbe, sau, hazaar, dedh, dhai, sawa (Roman and Devanagari). Edit the lists near the top of the script to add more.
