# smart-document-analyzer

---

📋 Table of Contents

- [Overview](#-overview)  
- [Demo Video](#-demo-video)  
- [Tech Stack](#-tech-stack)  
- [Features](#-features)  
- [Screenshots](#%EF%B8%8F-screenshots)  
- [Installation](#-installation)  
- [Developer Notes](#-developer-notes)  
- [Contributing](#-contributing)  
- [License](#-license)  
- [Copyright](#%EF%B8%8F-copyright)

---

## 🎯 Overview

✨ **Smart Document Analyzer** is a polished Windows desktop application built with Java Swing and Maven to analyze documents and extract deep text intelligence in one click. It supports five document formats - txt, pdf, docx, xlsx & pptx and delivers 12 instant metrics covering vocabulary, structure, and readability. The modern FlatLaf-powered interface features a fixed two-panel layout with a drag-and-drop drop zone that previews PDF page thumbnails after upload, a live color-coded status bar, and a Document Intelligence card displaying all metrics side-by-side. Packaged as a one-click installer for effortless deployment, Smart Document Analyzer brings professional-grade document analysis straight to your desktop.

---

## 🎥 Demo Video

> ⏳ Demo video is currently **In progress...** — it will be linked here once available.

---

## 🛠 Tech Stack

- **Language:** Java 21
- **UI Framework:** Java Swing with FlatLaf 3.7
- **Build Tool:** Apache Maven
- **PDF Processing:** Apache PDFBox 3.0.7
- **Office Processing:** Apache POI 5.5.1
- **IDE:** Visual Studio Code

---

## ✨ Features

- 📁 **Multi-Format Document Support**
Supports TXT, PDF, DOCX, XLSX, and PPTX files using appropriate parsers for each format.

- 📊 **Comprehensive Text Analysis & Statistics**
Calculates Character Count, Word Count, Sentence Count, Paragraph Count, Unique Words, Smallest Word, Longest Word, Most Repeated Word, Average Word Length, Average Sentence Length, Average Paragraph Length, and Total Pages.

- 🖱️ **Drag & Drop Upload**
Allows easy document upload via drag-and-drop along with manual file browsing.

- 🖼️ **Thumbnail Preview**
Displays a preview thumbnail of the selected document within the application.

- 🔄 **Live Color-Coded Status Bar**
Colored dot-prefixed messages for every user action - upload, analyze, clear, and exit.

- 🖥️ **Modern UI Design**
Built using Java Swing with FlatLaf look and feel, featuring clean layout, color-coded metric cards, and an intuitive interface.

---

## 🖼️ Screenshots

Below are complete interface screenshots from the Smart Document Analyzer application, covering all key views — including the default launch state, PDF thumbnail preview after upload, and full analysis results with all 12 metrics populated.

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/ef3acf88-11f9-47a6-94d1-28e10c3031c6" width="800"/></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/78579b6b-697d-443f-8f8e-afa3b7f42dd1" width="800"/></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/f46a8606-f1d7-4067-b515-f73d565b15d8" width="800"/></td>
  </tr>
</table>

> 🖼️ This gallery covers all major interface states for full visual context.

---

## 🚀 Installation

1. **Download the Installer**  
   Grab `SmartDocumentAnalyzer_Setup.exe` from the [Releases](https://github.com/prashanth-kumar-g/smart-document-analyzer/releases/tag/v1.0.0/SmartDocumentAnalyzer_Setup.exe) page.

2. **Run the Installer**  
   Double-click `SmartDocumentAnalyzer_Setup.exe` and follow the prompts. It installs the application, creates Desktop/Start Menu shortcuts, and requires no further setup.

3. **Launch the Application**  
   Open from your Desktop or Start Menu shortcut and start analyzing documents instantly.

> 💡 No additional frameworks or manual configuration required.

---

## 🧑‍💻 Developer Notes

Contributors and curious developers can find more details here:

- **Build Tool:** Apache Maven — run `mvn package` to compile and produce both JARs
- **Key Source File:** `src/main/java/Main.java` — entire application in a single file
- **Output JARs:**
  - `target/smart-document-analyzer-1.0.0.jar` — application-only JAR
  - `target/smart-document-analyzer-1.0.0-all.jar` — uber-JAR with all dependencies (runnable)
- **Run Directly:** `java -jar target/smart-document-analyzer-1.0.0-all.jar`

> ⚠️ End users do not need this section. This information is intended for developers who wish to explore the source code or rebuild the application manually.

---

## 🤝 Contributing

Contributions are welcome!

If you'd like to improve this Smart Document Analyzer, fix bugs, or add new features:

- Fork the repository
- Create a new branch for your changes
- Submit a pull request with a clear explanation

You can also open issues for suggestions or questions.  
Thank you for supporting this project!

---

## 📜 License

This project is licensed under the [CC BY-NC 4.0 License](LICENSE).  
You may use and modify this code for personal or educational purposes—see `LICENSE` for full details.

---

## ©️ Copyright

© 2025 Prashanth Kumar G. All rights reserved.  
Unauthorized commercial use or redistribution is prohibited without prior written consent.

---
