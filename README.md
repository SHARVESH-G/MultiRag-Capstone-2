# MultiRag-Capstone-2

🚀 **MultiRag-Capstone-2** is a full-stack project designed to perform advanced multimodal search and retrieval, integrating state-of-the-art machine learning models with an interactive web interface. The project leverages technologies like FastAPI, CLIP, and OCR to search, cluster, and display visual and textual data.

---

## 📝 Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## 📖 Introduction

**MultiRag-Capstone-2** is a capstone project focused on multimodal retrieval and search. The system is capable of processing and searching images and text, with a web interface for uploading, searching, and managing data. It combines deep learning models for feature extraction and similarity search, with a modern frontend for ease of use.

---

## ✨ Features

- ⚡ **Multimodal Search:** Search and retrieve images using both text and image queries.
- 📦 **FastAPI Backend:** High-performance backend for API endpoints and static file serving.
- 🖼️ **CLIP Model Integration:** Leverages OpenAI’s CLIP for powerful image and text embedding.
- 🔤 **OCR Support:** Extracts and uses text from images via EasyOCR.
- 🗂️ **Clustering Notebooks:** Includes Jupyter notebooks for clustering and search experiments.
- 🎨 **Modern UI:** Clean, Apple-style admin and user interfaces.
- 🔒 **Admin Panel:** For uploading and managing image data.

---

## 🛠️ Installation

### Prerequisites

- Python 3.8+
- [pip](https://pip.pypa.io/en/stable/)
- (Optional) [Poetry](https://python-poetry.org/) or [virtualenv](https://virtualenv.pypa.io/)

### Clone the Repository

```bash
git clone https://github.com/your-username/MultiRag-Capstone-2.git
cd MultiRag-Capstone-2
```

### Backend Setup

1. **Install Dependencies**

    ```bash
    cd backend
    pip install -r requirements.txt
    ```

    _Typical packages required (add these to your `requirements.txt`):_
    ```
    fastapi
    uvicorn
    torch
    numpy
    pillow
    scikit-learn
    easyocr
    git+https://github.com/openai/CLIP.git
    ```

2. **Run the Backend Server**

    ```bash
    uvicorn main:app --reload
    ```

3. **(Optional) Run Full Stack App**

    ```bash
    cd ../fullStackApp/backend
    uvicorn main:app --reload
    ```

---

## 🚀 Usage

### 1. Launch the Backend

Start the FastAPI backend as shown above.

### 2. Access the Web Interface

- User interface: `http://127.0.0.1:8000/`
- Admin panel: `http://127.0.0.1:8000/static/admin.html`

### 3. Use the Features

- **Upload Images:** Use the admin panel to upload images for searching.
- **Search:** Enter a text query or upload an image to perform similarity search.
- **Results:** View ranked results with image and text details.

### 4. Experiment with Notebooks

- `SEARCH2_O.ipynb` and `cluster_2_o.ipynb` provide code for experiments in search and clustering using the project’s models.
- Open these notebooks with Jupyter or Google Colab.

---

## 🤝 Contributing

Contributions are welcome! To get started:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

Please read the [CONTRIBUTING.md](CONTRIBUTING.md) for more details.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 📁 Project Structure

```
MultiRag-Capstone-2/
│
├── backend/
│   ├── main.py
│   └── static/
│       ├── admin.html
│       ├── admin.css
│       ├── admin.js
│       ├── index.html
│       ├── style.css
│       └── app.js
├── fullStackApp/
│  

## License
This project is licensed under the **MIT** License.

---
🔗 GitHub Repo: https://github.com/SHARVESH-G/MultiRag-Capstone-2