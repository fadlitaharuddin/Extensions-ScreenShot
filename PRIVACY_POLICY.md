# Privacy Policy for SpreadSheet Screenshot

**Effective Date:** November 23, 2026  
**Developer:** Fadli Tahar  
**Extension:** SpreadSheet Screenshot  

---

### 1. Overview
SpreadSheet Screenshot is committed to protecting your privacy. This extension is designed with a **privacy-first architecture**: all capturing, rendering, and clipboard processing operations are executed **entirely locally on your device**.

### 2. Information We Do NOT Collect
* **No Personal Data:** We do not collect, store, or transmit your name, email, credentials, IP address, or account information.
* **No Spreadsheet Data:** The content of your spreadsheets, cell values, formulas, sheets, and generated screenshot images never leave your browser. They are not uploaded to any remote server or third-party service.
* **No Tracking or Analytics:** This extension contains no analytics trackers, tracking cookies, advertising SDKs, or background telemetries.

### 3. Permissions Usage
The extension requires only the minimum necessary permissions to function:
* `clipboardWrite`: Used exclusively to copy the generated image of your selected spreadsheet cells directly to your system clipboard so you can paste it into other applications.
* `storage`: Used solely to save your local user preferences (such as image quality setting, margin/padding choices, output format, and floating button visibility).
* `activeTab`: Used to detect the active spreadsheet tab when you trigger keyboard shortcuts (`Alt+S` / `Alt+G`).
* `host_permissions` (`docs.google.com/spreadsheets/*` and `*.googleusercontent.com/*`): Used strictly to retrieve the temporary PDF rendering for the selected range from Google Sheets directly within your active browser session.

### 4. Third-Party Libraries
The extension includes a locally bundled, open-source library ([PDF.js by Mozilla](https://github.com/mozilla/pdfjs-dist)) to parse and render cell selections onto an HTML5 Canvas locally in your browser. No external code is loaded dynamically from third-party CDNs.

### 5. Changes to This Privacy Policy
If any changes are made to this policy, the updated version will be posted here with an updated "Effective Date".

### 6. Contact
If you have any questions or feedback regarding this Privacy Policy, please contact:
* **Developer:** Fadli Tahar
* **Contact / Support:** [fadli.taharuddin@gmail.com](mailto:fadli.taharuddin@gmail.com)
