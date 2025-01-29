 Multi-File Language Translator Using Python & Tkinter 📝
Excited to share my latest project—a Tkinter-based application that translates multiple .docx files from different languages (Tamil, Hindi, Malayalam, etc.) into English in just one click! 

📌 Project Overview:
Many times, we receive documents in different languages and need them translated into English. This GUI-based tool allows users to:
✅ Select multiple Word (.docx) files from a folder
✅ Automatically translate their content into English
✅ Save the translated files in the same folder with a new name

🔧 Libraries Used:
1️⃣ googletrans – A Python library for translating text using Google Translate API
2️⃣ python-docx – To read and write .docx files programmatically
3️⃣ customtkinter – A modern, theme-based GUI library built on top of Tkinter
4️⃣ tkinter (filedialog & messagebox) – To create a file selection dialog and show alerts

💡 How It Works:
The googletrans library detects the input language and translates it into English.
The python-docx library helps in reading text from .docx files and writing translated content into a new file.
The Tkinter GUI provides a simple interface to select files and process them in one click.
