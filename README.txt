Zebra QLn (2-inch) Web Label Printer
=====================================

This simple, single‑file web app lets you print ZPL or CPCL labels to a Zebra QLn‑series 2‑inch printer (e.g., QLn220/QLn230) directly from your browser using Zebra **Browser Print**.

Files
-----
- index.html — open in Chrome/Edge. No server required.
- (this) README.txt — setup notes.

Setup
-----
1) Install **Zebra Browser Print** (Link‑OS) for your OS and start the tray app.
2) Connect your zebra printer (USB, Bluetooth, or Network). Install the standard Zebra driver if on Windows.
3) On the printer, set the language to match what you plan to send:
   - ZPL (recommended) or CPCL
4) Open `index.html`. The top status pills should show:
   - Browser Print: loaded
   - Printer: connected (after selecting if needed)

Printing
--------
- Fill the fields and click **Preview Commands** to see the ZPL/CPCL to be sent.
- Click **Print Label** to send via Browser Print, or **Test Print** to send a small demo.
- If Browser Print isn’t available, click **Save .txt** and send the file via Zebra Setup Utilities → Tools → *Send file*.

Dimensions / DPI
----------------
- QLn 2-inch printers are 203 dpi devices. Exact 2.0″ width is **406 dots**.
- Many media types also work fine with **384 dots** width; if right edge clips, increase to 406.
- You can switch PW (print width) from the dropdown in the app.

Notes
-----
- If you send ZPL to a CPCL‑configured printer (or vice‑versa), nothing will print. Change the printer language or the app’s language.
- For bulk quantities, the app repeats the job to maximize compatibility. If you prefer ZPL’s ^PQ, you can edit the template in code.
- The CPCL template in this app uses TEXT font 4; adjust as needed.

Enjoy!
— Generated 2025-10-05T21:05:38
