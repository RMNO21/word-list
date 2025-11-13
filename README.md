# 🔑 Wordlist-Tool

A simple yet powerful Python tool for generating and managing custom wordlists.  
Perfect for automation, security research, or any workflow that needs flexible list generation.

---

## 📦 Installation

You can install directly from PyPI:

```bash
pip install wordlist-tool
```

Or, if you’re working from source:

```bash
git clone https://github.com/RMNO21/wordlist-tool.git
cd wordlist-tool
pip install .
```

---

## 🚀 Usage

After installation, the tool is available as a CLI command:

```bash
wordlist-tool --help
```

### Example: Generate a wordlist from a file
```bash
wordlist-tool generate --input words.txt --output mylist.txt
```

### Example: Combine multiple lists
```bash
wordlist-tool merge list1.txt list2.txt --output merged.txt
```

### Example: Apply filters
```bash
wordlist-tool filter --input biglist.txt --min-length 6 --max-length 12
```

---

## ⚙️ Features
- Generate wordlists from text files or stdin  
- Merge multiple lists into one  
- Apply filters (length, charset, etc.)  
- Save results to file or print to stdout  
- Lightweight, fast, and scriptable  

---

## 🛠 Development

Clone the repo and install in editable mode:

```bash
git clone https://github.com/RMNO21/wordlist-tool.git
cd wordlist-tool
pip install -e .
```

Run tests:

```bash
pytest
```

---

## 🤝 Contributing

Pull requests are welcome!  
For major changes, please open an issue first to discuss what you’d like to change.

---

## 📜 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---
