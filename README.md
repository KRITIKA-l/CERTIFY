
# 🎓 Certificate Generator
A lightweight, browser-based **Certificate Generator** that allows you to create personalized certificates for one or multiple recipients. Names are rendered onto a certificate template using HTML Canvas, converted into PDFs, and downloaded together inside a ZIP file — all without any backend.



---

## 🚀 Features

- 🎨 Canvas-based certificate rendering  
- 📝 Supports multiple names (comma-separated input)  
- 📄 Auto PDF generation for each certificate  
- 📦 ZIP download containing all generated PDFs  
- 🖼️ Live preview of each generated certificate  
- ⏭️ "Next" button to view each certificate one by one  
- ✔️ Fully client-side, no server required  

---

## 🛠️ Technologies Used

- **HTML5 Canvas**  
- **JavaScript (Vanilla JS)**  
- **Bootstrap 5**  
- **jsPDF** for PDF generation  
- **JSZip** for ZIP creation  

---

## 🧑‍💻 How It Works

1. The certificate template (`sample.jpg`) loads onto the canvas.  
2. You enter one or multiple names separated by commas.  
3. Press **Generate** → the first certificate is drawn on the canvas.  
4. Press **Next** to preview certificates for the remaining names.  
5. Press **Download** to export all certificates as PDFs inside a ZIP file.

---

## 📥 Output Format

Each generated certificate is saved as an individual PDF:

```
John_Doe.pdf
Jane_Smith.pdf
Aarav_Sharma.pdf
```

The final download will be:

```
certificates.zip
```

---

## 🖼️ Template

- The certificate background file must be named **sample.jpg**.
- It should be placed in the same directory as the HTML file.
- Make sure your template has enough free space to place the name clearly.

---

## 📌 Notes

- Name text is rendered at coordinates `(650, 650)` using:
  - Font: **100px Arial**
  - Color: **black**
- You may adjust the coordinates, font, or style as needed for your template.

---

## 📄 License

This project is free to use for personal, educational, and institutional purposes.



