# 🚀 CV Generator

**[gb English](#-english) | [🇻🇳 Tiếng Việt](#-tiếng-việt)**

---

<a name="-english"></a>
## EN English

A simple, fast, and secure web tool to create professional resumes (CVs) directly in your browser. No registration, no software installation, and completely **free**.

👉 **Try it live:** [https://bluesky2112.github.io/cv-generator/](https://bluesky2112.github.io/cv-generator/)

### ✨ Features
- **Live Preview:** Type on the left, and watch your CV update instantly on the right.
- **Avatar Support:** Automatically embeds your photo (Base64) directly into the exported HTML file.
- **ATS-Friendly:** Single-column layout using basic HTML tables and elements. No complex CSS that breaks parsing by Applicant Tracking Systems.
- **100% Client-Side:** All data is processed locally in your browser. No data is sent to any server.
- **1-Click HTML Export:** Download a single, self-contained HTML file (with embedded images) ready for PDF printing.

### 🛠️ How to Use
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

### 💻 Tech Stack
- **HTML5 / CSS3**
- **Tailwind CSS** (via CDN) - For building the user interface.
- **Vanilla JavaScript** - For HTML generation, Base64 image handling, and file export.

### 🚀 Self-Hosting
Since this is a static web app powered entirely by client-side JavaScript, you can easily host it for free.
1. **Fork** or **Clone** this repository.
2. To run locally, simply open `index.html` in your browser.
3. **Deploy to GitHub Pages:**
   - Go to your repo's **Settings** -> **Pages**.
   - Under *Build and deployment* -> *Source*, choose **Deploy from a branch**.
   - Select the `main` branch and `/ (root)` folder, then click **Save**.

### 📄 License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). You are free to use, modify, and share it.

---

<a name="-tiếng-việt"></a>
## 🇻🇳 Tiếng Việt

Một công cụ web đơn giản, nhanh chóng và bảo mật giúp bạn tạo CV (Resume) chuyên nghiệp trực tiếp trên trình duyệt. Không cần đăng ký, không cần cài đặt phần mềm, và đặc biệt là **hoàn toàn miễn phí**.

👉 **Trải nghiệm ngay tại đây:** [https://[username].github.io/cv-generator/](https://[username].github.io/cv-generator/) *(Hãy thay `[username]` bằng tên tài khoản GitHub của bạn)*

### ✨ Tính năng nổi bật
- **Xem trước thời gian thực (Live Preview):** Gõ thông tin bên trái, CV sẽ tự động cập nhật bên phải.
- **Hỗ trợ Ảnh đại diện:** Tự động nhúng ảnh (Base64) trực tiếp vào file HTML xuất ra.
- **Chuẩn ATS (Applicant Tracking System):** Bố cục 1 cột, sử dụng Table và các thẻ HTML cơ bản, không dùng các thuộc tính CSS phức tạp gây lỗi khi đọc bằng máy.
- **Bảo mật 100% (Client-side):** Mọi dữ liệu bạn nhập chỉ xử lý trên trình duyệt của bạn. Không có dữ liệu nào được gửi lên server.
- **Xuất file HTML 1-Click:** Tải về file HTML duy nhất (chứa cả ảnh và chữ), sẵn sàng để in ra PDF.

### 🛠️ Hướng dẫn sử dụng
1. Truy cập vào trang web của tool.
2. Điền đầy đủ thông tin vào biểu mẫu bên trái (Họ tên, Liên hệ, Kỹ năng, Kinh nghiệm, v.v.).
3. Tải lên ảnh đại diện (Avatar) nếu muốn.
4. Bấm nút **Xem Trước** để kiểm tra lại (hoặc tool sẽ tự động cập nhật).
5. Bấm **Tải File HTML** để lưu CV về máy.

### 🖨️ Cách in ra PDF chuẩn đẹp nhất
Sau khi tải file `My_CV.html` về máy:
1. Mở file bằng trình duyệt **Google Chrome** hoặc **Microsoft Edge**.
2. Nhấn `Ctrl + P` (hoặc `Cmd + P` trên Mac) để mở hộp thoại in.
3. Chọn **Save as PDF** (Lưu dưới dạng PDF).
4. Cài đặt quan trọng:
   - **Paper size:** A4
   - **Margins:** Default (hoặc None)
   - **Tích chọn "Background graphics":** Để giữ lại các đường kẻ ngang và màu chữ.
   - **Bỏ tích "Headers and footers":** Để xóa số trang và ngày tháng ở đầu/cuối trang.

### 💻 Công nghệ sử dụng
- **HTML5 / CSS3**
- **Tailwind CSS** (thông qua CDN) - Dùng để thiết kế giao diện form nhập liệu.
- **Vanilla JavaScript** - Xử lý logic tạo HTML, nhúng ảnh Base64 và xuất file.

### 🚀 Tự triển khai (Self-host)
Vì đây là một trang web tĩnh (Static Web App) chạy hoàn toàn bằng JavaScript, bạn có thể dễ dàng tự host nó miễn phí.
1. **Fork** hoặc **Clone** repository này về máy.
2. Nếu chạy local, bạn chỉ cần mở file `index.html` bằng trình duyệt.
3. **Deploy lên GitHub Pages:**
   - Vào phần **Settings** của repo -> **Pages**.
   - Ở mục *Build and deployment* -> *Source*, chọn **Deploy from a branch**.
   - Chọn nhánh `main` và thư mục `/ (root)`, sau đó bấm **Save**.

### 📄 Giấy phép (License)
Dự án này được phân phối dưới giấy phép [MIT License](https://opensource.org/licenses/MIT). Bạn được tự do sử dụng, chỉnh sửa và chia sẻ. 
