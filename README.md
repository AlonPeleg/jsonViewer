# JSON/XML Viewer & Compare

A fast, lightweight, and modern web application designed for viewing, editing, formatting, and comparing JSON and XML data side by side. Built with a clean Visual Studio Code-inspired UI, it provides flexible view modes, deep search, path breadcrumbs, and seamless file handling.

🌐 **Live Demo:** [https://alonpeleg.github.io/jsonViewer/](https://alonpeleg.github.io/jsonViewer/)

---

## ✨ Features

### 👁️ JSON & XML Viewer
* **Dual View Modes:** Toggle between single-column **Line View** and multi-column **Grid View** layout.
* **Interactive Tree View:** Expand, collapse, or focus individual nodes or entire documents with one click.
* **Breadcrumb Navigation:** Hover over any node to view its exact dot-notation path (e.g., `root.users[0].address.city`).
* **Format Conversion:** Instantly convert JSON to XML and XML to JSON.
* **Search & Highlight:** Real-time search with match navigation (`Enter`) across nodes and attributes.
* **Context Menu:** Right-click any node to quickly copy its JSON path or perform editor operations.
* **Focus Overlay:** Pop out any entry into a full-screen blurred backdrop for distraction-free analysis.
* **Persistent History:** Save entries locally in your browser session so you never lose your work on refresh.

### ⚖️ Side-by-Side Edit & Compare
* **Dual Panel Layout:** Edit or paste two separate documents into Panel A and Panel B.
* **Synchronized Scrolling:** Scroll both panels simultaneously for fast manual visual checks.
* **Diff Highlighting:** Run automated comparisons to spot added (`+`), removed (`-`), or modified (`Δ`) keys and values.
* **Flexible Diff Views:** View differences in a consolidated list or a side-by-side grid.
* **Interactive Diff Jump:** Click any highlighted line in the comparison output to auto-scroll directly to that path and selection in the editor panel.
* **Quick Chips:** Effortlessly load entries posted in the Viewer tab directly into Panel A or Panel B using drag-and-drop or direct selection.

---

## 🛠️ Usage & Keyboard Shortcuts

| Action | How to trigger |
| :--- | :--- |
| **Add Data** | Paste JSON/XML into the input box or drag and drop `.json` / `.xml` files. |
| **Search Nodes** | Type in the `Find...` input inside any entry card; press `Enter` to step through matches. |
| **Copy Path** | Right-click any node line and select **Copy Path**. |
| **Focus View** | Click the frame/expand icon on any card; press `Esc` to close focus mode. |
| **Compare** | Switch to the **Edit & Compare** tab, load Panel A and Panel B, then click **Compare Panels**. |

---

## 🚀 Getting Started

No build process or installation required. Simply open `index.html` in any web browser, or host it statically via GitHub Pages.

```bash
# Clone the repository
git clone [https://github.com/AlonPeleg/jsonViewer.git](https://github.com/AlonPeleg/jsonViewer.git)

# Open in browser
cd jsonViewer
open index.html
