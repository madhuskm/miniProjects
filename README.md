
# Wikipedia HTML File Analyzer

This repository contains a Python-based project that analyzes local HTML files stored in a directory (e.g., Wikipedia articles saved offline). The script demonstrates foundational skills in file I/O, directory navigation, and preparing data for further parsing or analysis.

## 📝 Project Description

The core functionality of this project includes:
- Listing all files in a given directory (`wiki/`)
- Reading a specific HTML file (`Bay_of_ConcepciC3B3n.html`)
- Printing lines from the file for inspection

The project is implemented in a Jupyter Notebook named `Basics.ipynb`.

## 📂 Directory Structure

```
.
├── Basics.ipynb          # Jupyter notebook containing the code
├── wiki/                 # Folder containing saved Wikipedia HTML files
└── README.md             # Project documentation
```

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/html-file-analyzer.git
cd html-file-analyzer
```

### 2. Launch Jupyter Notebook

Make sure you have Jupyter installed, then run:

```bash
jupyter notebook Basics.ipynb
```

This will open the notebook in your browser for interactive exploration.

## 🧰 Requirements

This project uses Python's standard library only—no external dependencies are needed.

## 🔍 Sample Output

```
Dragnet_(franchise).html
Mick_Crotty.html
Jazz_in_Turkey.html
```

These are some of the HTML filenames listed by the script from the `wiki/` directory.

## 📌 Notes

- This is a beginner-friendly project meant to demonstrate working with local file systems and text content.
- You can build upon this to parse HTML content using `BeautifulSoup` or similar libraries.

## 📄 License

This project is licensed under the MIT License. Feel free to reuse and modify with attribution.
