# 🛡️ OnDevice — Your Privacy Is our priority

OnDevice is a premium, privacy-first web utility engineered to convert images and standard documents entirely inside your browser sandbox. Traditional web converters secretly stream your private documents to third-party cloud containers. OnDevice flips the script: **Zero uploads. Zero tracking. 100% Client-Side.**

Developed by **Pranav Aitha**

---

## ✨ Key Features

- 🔒 **Zero Server Ingestion:** Files are parsed exclusively inside local memory via HTML5 APIs. Absolutely zero file bytes leave your device.
- ⏳ **Instant RAM Erasure:** The moment you close the tab, all transient memory buffers vanish forever.
- 🛜 **Offline Capable:** Once the web application loads, it can function entirely without an internet connection.
- 🎨 **Premium UI/UX:** Built featuring an ultra-dynamic glassmorphic design that is as functional as it is beautiful.

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

*Note: WebP & AVIF output compatibility depends directly on your browser's underlying canvas engine.*

---

## 🚀 How to Run Locally

### Prerequisites
You only need a modern web browser supporting modern HTML5 APIs (Chrome, Firefox, Edge, or Safari).

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com
   ```
2. Navigate into the project folder:
   ```bash
   cd ondevice
   ```
3. Open `index.html` directly in your browser, or serve it using a lightweight local server:
   ```bash
   # If you use Python
   python -m http.server 8080
   ```

---

## 🔒 Verification
Want to verify our privacy promise? 
1. Open your browser **DevTools** (F12).
2. Move to the **Network** tab.
3. Drop a file and click **Convert File in Browser**. 
4. You will see **exactly zero network payloads** transmitted. 

---

## ⚖️ License
Distributed under the Unilicense License. See `LICENSE` for more information.
