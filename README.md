# Website Học Tiếng Anh với Cô Trần Minh Thúy

## Cấu trúc thư mục
```
learn-english/
│
├── index.html              # Trang chủ
├── about.html             # Trang giới thiệu
├── basic-grammar.html     # Trang ngữ pháp cơ bản
├── vocabulary.html        # Trang từ vựng
├── pronunciation.html     # Trang phát âm
│
├── css/
│   └── style.css         # File CSS chính
│
├── images/
│   └── teacher.svg       # Avatar giáo viên
│
└── README.md             # File hướng dẫn này
```

## Cách chạy trang web trên local

### Phương pháp 1: Sử dụng Visual Studio Code
1. Cài đặt [Visual Studio Code](https://code.visualstudio.com/)
2. Cài đặt extension "Live Server":
   - Mở VS Code
   - Nhấn vào biểu tượng Extensions (Ctrl+Shift+X)
   - Tìm kiếm "Live Server"
   - Cài đặt extension của Ritwick Dey
3. Mở thư mục dự án trong VS Code
4. Click chuột phải vào file `index.html`
5. Chọn "Open with Live Server"
6. Trang web sẽ tự động mở trong trình duyệt mặc định của bạn

### Phương pháp 2: Sử dụng Python
1. Mở terminal/command prompt
2. Di chuyển đến thư mục dự án:
   ```bash
   cd đường-dẫn-đến-thư-mục/learn-english
   ```
3. Nếu bạn dùng Python 3:
   ```bash
   python -m http.server 8000
   ```
   Nếu bạn dùng Python 2:
   ```bash
   python -m SimpleHTTPServer 8000
   ```
4. Mở trình duyệt và truy cập: `http://localhost:8000`

### Phương pháp 3: Sử dụng Node.js
1. Cài đặt [Node.js](https://nodejs.org/)
2. Mở terminal/command prompt
3. Cài đặt `http-server` globally:
   ```bash
   npm install -g http-server
   ```
4. Di chuyển đến thư mục dự án:
   ```bash
   cd đường-dẫn-đến-thư-mục/learn-english
   ```
5. Chạy server:
   ```bash
   http-server
   ```
6. Mở trình duyệt và truy cập: `http://localhost:8080`

## Lưu ý
- Đảm bảo tất cả các file đều nằm đúng vị trí trong cấu trúc thư mục
- Nếu bạn thấy lỗi 404 (file not found), hãy kiểm tra lại đường dẫn các file
- Trang web yêu cầu kết nối internet để tải các font chữ và icon từ CDN

## Yêu cầu hệ thống
- Trình duyệt web hiện đại (Chrome, Firefox, Edge, Safari)
- Kết nối internet (để tải font và icon)
- Một trong các công cụ sau:
  - Visual Studio Code + Live Server
  - Python 2.7+ hoặc Python 3+
  - Node.js 