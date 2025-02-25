
# 📂 File Organizer CLI (Dart + Termux)

A **simple and efficient command-line tool** to automatically **organize files** into categorized folders based on their type.  
This project is written in **Dart** and designed to run on **Termux** or any command-line environment.

## ✨ Features
- ✅ **Scans a directory** and detects all files.
- ✅ **Categorizes files** based on their extensions (Images, Videos, Documents, Music, Archives, etc.).
- ✅ **Moves files** into organized folders.
- ✅ **Creates missing folders** if they don’t exist.
- ✅ **Provides a summary report** after execution.
- ✅ **Handles errors gracefully** (invalid directories, empty folders, etc.).

---

## 🛠️ Installation

### **Prerequisites**
1. Install **Dart** on Termux:
   ```sh
   pkg install dart

2. Clone this repository:

git clone https://github.com/yourusername/file-organizer-cli.git
cd file-organizer-cli


3. Run the program:

dart organizer.dart




---

🚀 Usage

1. Run the script in Termux or a command-line terminal:

dart organizer.dart


2. Enter the directory path where your files are stored:

Enter the directory path to organize: /data/data/com.termux/files/home/Downloads


3. The script will:

Scan the directory.

Categorize files based on type.

Move files into appropriate folders.

Show a summary report.





---

📂 Example Output

----------------------------------------
📂 File Organizer - Dart CLI
----------------------------------------
Enter the directory path to organize: /storage/emulated/0/Downloads

🔍 Scanning directory...
Found 8 files.

✅ Categorized: photo.jpg → Images
✅ Categorized: video.mp4 → Videos
✅ Categorized: document.pdf → Documents
✅ Categorized: song.mp3 → Music
✅ Categorized: archive.zip → Archives

📁 Creating folder: Images/
📁 Creating folder: Videos/
📁 Creating folder: Documents/
📁 Creating folder: Music/
📁 Creating folder: Archives/

🚀 Moving files...
✅ Moved: photo.jpg → Images/
✅ Moved: video.mp4 → Videos/
✅ Moved: document.pdf → Documents/
✅ Moved: song.mp3 → Music/
✅ Moved: archive.zip → Archives/

----------------------------------------
✅ File Organization Completed!
----------------------------------------
📂 Organized Files:
   - 1 Image file
   - 1 Video file
   - 1 Document file
   - 1 Music file
   - 1 Archive file

🎉 Total Files Moved: 5
📁 Files stored in respective folders.


---

📁 Folder Structure

After execution, the directory structure will look like this:

📂 Downloads/
│── 📂 Images/
│   ├── photo.jpg
│── 📂 Videos/
│   ├── video.mp4
│── 📂 Documents/
│   ├── document.pdf
│── 📂 Music/
│   ├── song.mp3
│── 📂 Archives/
│   ├── archive.zip


---

🔧 Configuration (Optional)

You can customize the file categories in data/categories.json:

{
  "Images": ["jpg", "png", "gif"],
  "Videos": ["mp4", "mkv", "mov"],
  "Documents": ["pdf", "docx", "txt"],
  "Music": ["mp3", "wav"],
  "Archives": ["zip", "rar"]
}


---

🚨 Error Handling

❌ Invalid Directory

If the user enters a non-existent directory:

❌ Error: The directory does not exist. Please enter a valid path.

⚠ No Files Found

If the directory is empty:

🔍 Scanning directory...
⚠ No files found to organize.

⚠ Unrecognized File Type

If a file doesn’t match any category:

⚠ Skipped: unknown.xyz (No category found)


---

🎯 Future Enhancements

🔹 Undo function - Restore files to their original location.
🔹 Custom categories - Let users define their own categories via config.
🔹 Scheduler - Run automatically at set intervals.
🔹 GUI version - Convert this CLI into a mobile/desktop app with Flutter.


---

🤝 Contributing

Contributions are welcome! Feel free to submit a pull request.


---

📜 License

This project is licensed under the MIT License.


---

💬 Support & Contact

For questions, open an issue on GitHub or contact your.email@example.com.

---

### **How to Use This?**
1. Replace `yourusername` with your **GitHub username**.  
2. Replace `your.email@example.com` with your **email/contact info**.  
3. Modify the **future features** based on your **roadmap**.  
4. Add any **custom branding** or credits as needed.  

Would you like a **GitHub repository structure** guide along with `README` best practices?

