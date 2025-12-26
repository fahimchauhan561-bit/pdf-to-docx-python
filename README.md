# pdf-to-docx-python
Recreating a PDF document into MS Word using Python
# 📄 PDF to MS Word Conversion using Python

## 📌 Project Overview

This project demonstrates how to recreate a given PDF document into a Microsoft Word (`.docx`) file using Python. The goal was to closely match the original PDF's layout, structure, spacing, alignment, and readability by manually analyzing the PDF and generating the Word document programmatically.

---

## 🎯 Objective

- Read and analyze the provided PDF document
- Recreate the document layout in MS Word from scratch
- Maintain headings, tables, spacing, alignment, and formatting
- Generate a fully editable and readable `.docx` file using Python

---

## 🛠️ Tools & Technologies Used

- **Python 3**
- **python-docx** (for Word document generation)
- **Visual Studio Code**
- **Microsoft Word**

---

## 🧠 Approach

1. The PDF file was manually reviewed to understand:
   - Headings and subheadings
   - Table structure and borders
   - Text alignment and spacing

2. A new Word document was created using the `python-docx` library.

3. Center-aligned headings were added to match the PDF.

4. Tables were created and populated to replicate the form structure.

5. Line breaks, bold formatting, and section spacing were applied to ensure readability.

6. The final output closely matches the original PDF layout.

---

## 📂 Project Structure

```
.
├── script.py
├── Mediation_Application_Form.docx
└── README.md
```

---

## ▶️ How to Run the Project

### 1️⃣ Install Required Library

```bash
pip install python-docx
```

### 2️⃣ Run the Script

```bash
python script.py
```

### 3️⃣ Output

After execution, a file named `Mediation_Application_Form.docx` will be generated in the same directory.

Open the file using Microsoft Word.

---

## 📄 Output Description

The generated Word document:

- ✅ Matches the PDF structure and layout
- ✅ Contains all headings and form fields
- ✅ Uses tables and borders for clarity
- ✅ Is fully editable in MS Word

---

## ✅ Status

| Status | Description |
|--------|-------------|
| ✔️ Completed | Project is fully functional |
| ✔️ Assignment-ready | Ready for submission |
| ✔️ Successfully tested | Tested and verified |

---

## 📌 Notes

- The `.docx` file is a binary document and should be opened in Microsoft Word, not in a code editor.
- The project focuses on layout recreation, not automated PDF conversion.

---

## 👤 Author

**Fahim Chauhan**

---

## 📝 License

This project is open source and available for educational purposes.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

---

## ⭐ Show your support

Give a ⭐ if this project helped you!
