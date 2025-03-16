# CEO_MEMO

## 1. Giới thiệu  
CEO_MEMO là một dự án React giúp quản lý dữ liệu một cách hiệu quả. Hướng dẫn này sẽ giúp bạn cài đặt và chạy dự án ngay cả khi bạn chưa từng làm việc với React trước đây.  

---

## 2. Yêu cầu hệ thống  
Trước khi bắt đầu, hãy đảm bảo máy tính của bạn đã cài đặt:

- **[Node.js](https://nodejs.org/)** (Phiên bản khuyến nghị: **LTS**)  
- **Git** (để quản lý mã nguồn)  

---

## 3. Hướng dẫn cài đặt  

### 3.1. Kiểm tra Node.js
Mở **Terminal** (Command Prompt / PowerShell / Git Bash) và chạy lệnh sau:  
```sh
node -v
```
Nếu hiển thị phiên bản Node (ví dụ: `v18.17.0`), nghĩa là bạn đã cài Node.js. Nếu chưa, hãy tải về và cài đặt từ [Node.js Official](https://nodejs.org/).

### 3.2. Kiểm tra npm
Gõ lệnh sau trong terminal:
```sh
npm -v
```
Nếu thấy số phiên bản (ví dụ: `9.6.7`), thì bạn đã cài npm thành công.

### 3.3. Clone repository về máy
Chạy lệnh sau để tải mã nguồn về:
```sh
git clone https://github.com/levphuocthinh/CEO_MEMO.git
```
Sau đó, di chuyển vào thư mục dự án:
```sh
cd CEO_MEMO
```

### 3.4. Cài đặt thư viện cần thiết
Trong thư mục dự án, chạy lệnh sau:
```sh
npm install
```
Lệnh này sẽ tải xuống tất cả các thư viện mà dự án cần để chạy.

---

## 4. Chạy dự án  
Sau khi cài đặt thành công, bạn có thể chạy ứng dụng bằng lệnh:
```sh
npm start
```
Hoặc:
```sh
npm run dev
```
Sau khi chạy, bạn sẽ thấy ứng dụng khởi động thành công và có thể truy cập tại:
```
http://localhost:3000
```

---

## 5. Các lệnh hữu ích khác  

### 🔹 Build ứng dụng
(Dùng khi bạn muốn đóng gói ứng dụng để triển khai lên server)
```sh
npm run build
```

### 🔹 Chạy test
```sh
npm run test
```

### 🔹 Eject dự án (không khuyến khích)
```sh
npm run eject
```

---

## 6. Lỗi thường gặp và cách khắc phục  

❌ **Lỗi `command not found: npm`**  
- **Nguyên nhân**: Bạn chưa cài Node.js hoặc chưa thêm vào PATH.  
- **Giải pháp**: Cài đặt lại [Node.js](https://nodejs.org/).

❌ **Lỗi `react-scripts: command not found`**  
- **Nguyên nhân**: Bạn chưa chạy `npm install`.  
- **Giải pháp**: Chạy lại lệnh:
```sh
npm install
```

❌ **Lỗi `port 3000 is already in use`**  
- **Nguyên nhân**: Cổng `3000` đã bị một ứng dụng khác chiếm dụng.  
- **Giải pháp**: Chạy lệnh:
```sh
npx kill-port 3000
```
Sau đó thử chạy lại `npm start`.

---

## 7. Thông tin liên hệ  
Nếu bạn có bất kỳ câu hỏi nào, hãy liên hệ với **levphuocthinh** qua GitHub hoặc email.

🚀 **Chúc bạn cài đặt thành công và code vui vẻ!** 🚀  

---

## ✅ Tại sao README này hữu ích?  
✔ Hướng dẫn từng bước rõ ràng  
✔ Phù hợp cả với người mới chưa biết React  
✔ Cung cấp lệnh kiểm tra và xử lý lỗi thường gặp  
✔ Bao gồm tài nguyên giúp người dùng tự khắc phục vấn đề  

