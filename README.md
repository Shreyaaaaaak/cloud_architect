# ☁️ Cloud Architect

An interactive **AWS architecture diagram builder** with drag-and-drop functionality, real-time visualization, and AI-powered architecture review.

## 🚀 Features

- 🧩 **Drag & Drop AWS Services**  
  Easily add services like EC2, S3, Lambda, RDS, etc. onto a canvas.

- 🔗 **Connect Services**  
  Create relationships between components with a visual connection system.

- 🧠 **AI Architecture Review**  
  Get expert-level feedback on your architecture using Claude AI.

- 💾 **Save & Load Diagrams**  
  Store your designs locally and reload them anytime.

- 📸 **Export as PNG**  
  Export your architecture diagrams as high-quality images.

- 🔍 **Search AWS Services**  
  Quickly find services using the built-in search.

- 🗺️ **Mini-map Navigation**  
  Visual overview for large architectures.

- ↩ **Undo / Clear Canvas**  
  Efficient editing with undo support.

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript (Vanilla)
- **Canvas Rendering:** HTML5 Canvas API
- **AI Integration:** Claude API (Anthropic)
- **Storage:** LocalStorage (for saved diagrams)
- **Export:** Canvas-based PNG generation

---

## 📂 Project Structure

```
Cloud-Architect/
 ├── cloud_architect.html
 └── README.md
```

---

## ⚙️ Setup & Usage

### 1. Clone the Repository
```
git clone https://github.com/your-username/cloud-architect.git
cd cloud-architect
```

### 2. Open the App
Simply open the HTML file in your browser:
```
open cloud_architect.html
```

---

## 🔑 AI Review Setup

To use the **AI Review feature**:

1. Get an API key from Anthropic  
2. Enter the key in the input field (format: `sk-ant-...`)  
3. Click **✨ AI Review**

---

## 🎮 How to Use

- Drag services from the sidebar to the canvas  
- Click **🔗 Connect** to link components  
- Double-click a node to delete it  
- Press `Delete` or `Backspace` to remove selected nodes  
- Use `Ctrl + Z` for undo  

---

## 📸 Export Diagram

Click **📸 Export PNG** to download your architecture as an image.

---

## 💡 Example Use Cases

- Designing AWS system architectures  
- Learning cloud service relationships  
- Preparing for cloud certifications  
- Portfolio/demo projects  

---

## ⚠️ Limitations

- Works fully in-browser (no backend)
- Diagrams are stored locally (browser storage)
- Requires API key for AI review feature

---

## 🔮 Future Improvements

- Multi-cloud support (Azure, GCP)
- Collaboration / sharing features
- Backend storage for diagrams
- Pre-built architecture templates

---

## 👩‍💻 Author

Shreya Kaushik

---

## 📄 License

This project is open-source and available under the MIT License.
