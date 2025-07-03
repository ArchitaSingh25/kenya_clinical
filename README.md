# Kenya Clinical QA (Work in Progress)

This repository focuses on building a **Clinical Question Answering System** for Kenyan medical data using **RAG (Retrieval-Augmented Generation)** techniques.

> ⚠️ **Note:** This is a work in progress. The project is currently being developed and improved iteratively. Stay tuned for updates!

---

## 📁 Current Files & Usage

- **`Train.csv`**  
  Used for **validation** of the generated responses.

- **`Test.csv`**  
  Used to **generate** `submission.csv` by retrieving answers using RAG.

- **`Medical.pdf`**  
  Core knowledge base used to build the **RAG pipeline** via chunking and vector embeddings.

---

## ⚙️ Implementation Notes

- Due to limited resources, the entire pipeline is implemented on **Google Colab**.
- Vector embedding is currently handled using **ChromaDB**, though issues with data persistence have been noted.

---

## 🚧 Future Work

- ✅ Hosting the application as an API or web app.
- ✅ Adding a **user interface** for more accessible interaction.
- ✅ Using a dedicated **index file** to resolve ChromaDB vector storage issues.

---

## 📌 To Do

- [ ] Improve document chunking and retrieval quality  
- [ ] Integrate authentication if deployed  
- [ ] Explore other embedding models for better accuracy  
- [ ] Optimize latency and memory usage on deployment  

---

Feel free to fork or star ⭐ this repository if you find the project interesting or useful.  
Pull requests and suggestions are always welcome!

