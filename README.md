# 📚 PDF-MERGER

A simple and efficient web application to merge multiple PDF files into one. Built with Node.js, Express, and a stylish Bootstrap frontend.

---

## ✨ Features

- 🚀 Upload and merge multiple PDF files
- 📥 Download the combined PDF instantly
- 💻 Clean, responsive UI (Bootstrap)
- 🔒 Secure and temporary file handling

---

## 🚀 Getting Started

### 1. 🌀 Clone the Repository

```bash
git clone https://github.com/amansatya/PDF-MERGER.git
cd PDF-MERGER
```

### 2. 📦 Install Dependencies

Make sure you have [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed.

```bash
npm install
```

This will install all required modules as listed in `package.json`, such as:
- `express` – For the web server and routing
- `multer` – For handling file uploads
- `pdf-merger-js` – PDF merging engine

### 3. ▶️ Run the Application

```bash
node server.js
```

By default, visit [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🗂️ File Structure

```
PDF-MERGER/
├── public/         # 🌐 Static assets (CSS, JS, images) & stores merged output PDFs
├── uploads/        # 🗃️ Temporary user PDF uploads
├── templates/      # 📝 HTML templates (if used)
├── merge.js        # 🔗 PDF merging logic
├── server.js       # 🚦 Main server file
├── package.json    # 📋 Project metadata & dependencies
└── README.md       # 📖 Documentation
```

---

## 🗃️ Folders Explained

### public/ 🌐

- **Purpose:** Holds static files (CSS, JS, images) served directly to users and **stores the merged PDF output files** so users can download them.
- **Why:** This setup makes sure outputs are easily accessible via direct URLs after merging.

### uploads/ 🗃️

- **Purpose:** Temporarily stores PDF files uploaded by users before merging.
- **Why:** Allows secure, isolated file processing before output.

---

## 🛠️ Why This Module & Version?

We use [`pdf-merger-js`](https://www.npmjs.com/package/pdf-merger-js) (see `package.json` for the exact version, e.g., `^4.2.0`) because:

- ⚡ **Simplicity:** Easy API for merging PDFs.
- 🧩 **Node.js Friendly:** Works seamlessly with file paths and buffers.
- 🛡️ **Reliability:** Actively maintained and widely used in the Node.js ecosystem.

Specifying a version ensures stability and prevents unexpected breaking changes.

---

## 📬 Contact

Questions or feedback?  
Open an issue or pull request on [GitHub](https://github.com/amansatya/PDF-MERGER/issues)!

---


Happy merging! 🎉