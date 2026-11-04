# cv-generator
# 🚀 CV Generator

A simple, fast, and secure web tool to create professional resumes (CVs) directly in your browser. No registration, no software installation, and completely **free**.

👉 **Try it live:** [https://[username].github.io/cv-generator/](https://[username].github.io/cv-generator/) *(Replace `[username]` with your GitHub username)*

## ✨ Features

- **Live Preview:** Type on the left, and watch your CV update instantly on the right.
- **Avatar Support:** Automatically embeds your photo (Base64) directly into the exported HTML file.
- **ATS-Friendly:** Single-column layout using basic HTML tables and elements. No complex CSS that breaks parsing by Applicant Tracking Systems.
- **100% Client-Side:** All data is processed locally in your browser. No data is sent to any server.
- **1-Click HTML Export:** Download a single, self-contained HTML file (with embedded images) ready for PDF printing.

## 🛠️ How to Use

1. Visit the live website.
2. Fill in the form on the left (Name, Contact, Skills, Experience, etc.).
3. Upload your avatar photo (optional).
4. Click **Preview** to check the layout (or let it auto-update).
5. Click **Download HTML** to save your CV to your computer.

### 🖨️ Exporting to PDF (Perfect Layout)
After downloading the `My_CV.html` file:
1. Open the file in **Google Chrome** or **Microsoft Edge**.
2. Press `Ctrl + P` (or `Cmd + P` on Mac) to open the print dialog.
3. Select **Save as PDF**.
4. **Crucial Settings:**
   - **Paper size:** A4
   - **Margins:** Default (or None)
   - **Check "Background graphics":** To keep the horizontal lines and text colors.
   - **Uncheck "Headers and footers":** To remove page numbers and dates.

## 💻 Tech Stack

- **HTML5 / CSS3**
- **Tailwind CSS** (via CDN) - For building the user interface.
- **Vanilla JavaScript** - For HTML generation, Base64 image handling, and file export.

## 🚀 Self-Hosting

Since this is a static web app powered entirely by client-side JavaScript, you can easily host it for free.

1. **Fork** or **Clone** this repository.
2. To run locally, simply open `index.html` in your browser.
3. **Deploy to GitHub Pages:**
   - Go to your repo's **Settings**.
   - Select **Pages** from the sidebar.
   - Under *Build and deployment* -> *Source*, choose **Deploy from a branch**.
   - Select the `main` branch and `/ (root)` folder, then click **Save**.

## 📄 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). You are free to use, modify, and share it.
