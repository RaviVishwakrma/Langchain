# Langchain Project

A Python project demonstrating Langchain implementations with chat models and embedding models.

## 📁 Project Structure

```
Langchain/
├── requirements.txt          # Python dependencies
├── text.py                   # Main text processing file
├── 2.ChatModels/
│   └── 1_chatmodel_hg_local.py  # HuggingFace local chat model
└── 3.Embedding_Models/
    └── Embedding_hf_local.py    # HuggingFace local embedding model
```

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- Git

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/RaviVishwakrma/Langchain.git
   cd Langchain
   ```

2. **Create virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## 🎯 Usage

### Chat Models
Run the HuggingFace local chat model:
```bash
python 2.ChatModels/1_chatmodel_hg_local.py
```

### Embedding Models
Run the HuggingFace local embedding model:
```bash
python 3.Embedding_Models/Embedding_hf_local.py
```

### Main Text Processing
Run the main text processing script:
```bash
python text.py
```

## 📋 Requirements

All required packages are listed in `requirements.txt`:
- langchain
- transformers
- torch
- Other dependencies...

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

Ravi Vishwakrma - [GitHub Profile](https://github.com/RaviVishwakrma)

---

**⭐ Star this repo if you find it helpful!**