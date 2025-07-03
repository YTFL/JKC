# JKC Utilities — Comic & PDF Tools

A powerful, lightweight collection of Python scripts for managing `.cbz` files, organizing manga/comics, converting images to PDFs, and performing batch file operations. Whether you're building your personal manga library or automating archive tasks, these tools are designed for speed, flexibility, and clarity.

---

## Features

- Convert `.cbz` comic archives to `.pdf`
- Convert image folders into clean PDFs
- Bulk rename and organize chapter/volume folders
- Create `.cbz` files from image directories
- Unzip single or multiple `.cbz` files
- Perform batch PDF operations
- Download images and structure them for use

---

## Script Overview

| Script | Functionality |
|--------|---------------|
| `cbz_to_pdf.py` | Convert a single `.cbz` file to `.pdf` using extracted images. |
| `cbz_to_pdf_direct.py` | Quick variant of CBZ to PDF conversion, minimal user input. |
| `chapters_to_volumes.py` | Combine chapter folders into volume folders for better structuring. |
| `create_cbz.py` | Create `.cbz` files from folders of images. |
| `download_images.py` | Script for downloading images from a source (edit required). |
| `img_to_pdf.py` | Convert a set of images directly into a `.pdf` file. |
| `pdf_bulk.py` | Perform batch operations on multiple `.pdf` files (like merging). |
| `rename_plus_cbz_to_pdf.py` | Combine renaming and CBZ→PDF conversion in a single step. |
| `renamer.py` | Flexible batch file renaming based on patterns or indexes. |
| `unzip_cbz.py` | Extract contents of a single `.cbz` file to a folder. |
| `unzip_cbz_bulk.py` | Bulk unzip multiple `.cbz` files in a directory. |

> 📝 Most scripts are designed for command-line usage and may require editing paths or filenames as per your folder structure.

---

## Getting Started

1. **Clone the repo**

```bash
git clone https://github.com/yourusername/jkc-utils.git
cd jkc-utils
```

2. **(Optional) Set up a virtual environment**

```bash
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
```

3. **Install dependencies**

```bash
pip install Pillow img2pdf
```

> If using scripts like `download_images.py`, you may also need:
> ```bash
> pip install requests
> ```

---

## 🧪 Example Usage

Convert a `.cbz` file to `.pdf`:

```bash
python cbz_to_pdf.py
```

Unzip multiple `.cbz` files in a folder:

```bash
python unzip_cbz_bulk.py
```

Convert images to PDF:

```bash
python img_to_pdf.py
```

Rename a set of files:

```bash
python renamer.py
```

---

## Contributions Welcome!

Have an idea to improve a script? Found a bug? Want to optimize or extend functionality?

### Fork • Improve • Pull Request

Contributions are highly encouraged!

You can:
- Fix bugs or broken logic
- Improve performance or structure
- Add argument parsing / CLI flags
- Introduce new scripts (e.g., EPUB conversion, metadata embedding)
- Improve UX (GUI wrappers, batch automation)

Just fork the repository, make your changes, and submit a **pull request**.
Please keep your code clean and documented where necessary.

---

## License

This project is licensed under the **MIT License**.
You’re free to use, modify, and distribute it.

---

## Questions or Suggestions?

Feel free to open an issue or reach out if you have feedback, bugs, or requests!
