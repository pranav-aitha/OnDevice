# 🛡️ OnDevice — Privacy-First File Converter

OnDevice is a premium, privacy-first web utility engineered to convert images and standard documents entirely inside your browser sandbox. Traditional web converters secretly stream your private documents to third-party cloud containers. OnDevice flips the script: **Zero uploads. Zero tracking. 100% Client-Side.**

> ### 🔒 "Your Privacy is Our Absolute Priority"

Developed by **Pranav Aitha**

---

## ✨ Key Features

- 🔒 **Zero Server Ingestion:** Files are parsed exclusively inside local memory via HTML5 APIs. Absolutely zero file bytes leave your device.
- ⏳ **Instant RAM Erasure:** The moment you close the tab, all transient memory buffers vanish forever.
- 🛜 **Offline Capable:** Once the web application loads, it functions entirely without an internet connection.
- ⚙️ **Pure Sandbox Execution:** Runs strictly within your local browser ecosystem, meaning no stealth background APIs, no analytics pings, and complete data isolation.

---

## 🛠️ Advanced Conversion Control

Take complete control over your file rendering pipeline directly in your browser:
*   **Quality Compression:** Fine-tune output quality and compression ratios (Default: `0.92`).
*   **Dynamic Dimension Scaling:** Resize outputs instantly ranging from original dimensions down to crisp `256px` App Icons.
*   **Alpha Background Fill:** Custom hex-color background rendering for converting transparent alpha channels to `JPEG`, `BMP`, or `PDF`.

---

## 📊 Performance & Honest Limits

Because OnDevice respects your privacy by processing everything locally on your machine's hardware, strict physical limits apply:

| Parameter | Capability / Limit |
| :--- | :--- |
| **Optimized Formats** | Images (including WebP & AVIF output) and standard text files. |
| **PDF Conversion** | Supports instant local layout export to PDF. |
| **File Size Limit** | Files exceeding **80MB** may exhaust browser tab RAM. |
| **Exclusions** | Heavy video containers and proprietary binary Office docs (`DOCX`, `XLSX`, `PPTX`) are not parsed. |

> ⚠️ **Note:** WebP & AVIF output compatibility depends directly on your browser's underlying canvas engine.

---

## 🚀 How to Use It Happily

No installations, no terminal commands, and no developer setup needed! To access this file and use it completely offline:

1. **Download the source files locally** to your machine.
2. Double-click the **`index.html`** file to launch it instantly in any modern web browser (Chrome, Firefox, Edge, or Safari).
3. Bookmark the page to use it happily whenever you need secure, instant conversions!

---

## 🔒 Verification
Want to verify our privacy promise? 
1. Open your browser **DevTools** (F12).
2. Move to the **Network** tab.
3. Drop a file and click **Convert File in Browser**. 
4. You will see **exactly zero network payloads** transmitted. 

---

## ⚖️ License
This project is dedicated to **Unilicense**. You are free to copy, modify, publish, use, compile, sell, or distribute this software in source code form or as a compiled binary, for any purpose, commercial or non-commercial, and by any means.
