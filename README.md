# 🍜 Huong Vi Viet | Modern F&B Architectural Web Interface

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/yourusername/repo-name/graphs/commit-activity)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Static Analysis](https://img.shields.io/badge/Performance-90%2B-brightgreen.svg)](#)

**Huong Vi Viet** là một giải pháp Frontend chuyên dụng cho ngành F&B, kết hợp giữa ngôn ngữ thiết kế tinh tế (Modern Aesthetics) và tư duy lập trình tối ưu (Performance-First). Dự án mô phỏng một hệ sinh thái đặt món hoàn chỉnh từ khâu duyệt danh mục đến quy trình thanh toán QR động.

---

## 💎 Core Value Propositions

### 1. UX/UI Sophistication
* **Typography System:** Sử dụng cặp font đối bản `Playfair Display` (Serif) cho Branding và `Outfit` (Sans-serif) cho Content, tối ưu hóa khả năng đọc (Readability) và tính sang trọng.
* **Interaction Design:** Hệ thống **Toast Notifications** và **Micro-interactions** được xử lý bất đồng bộ, giúp tăng tỷ lệ chuyển đổi người dùng (Conversion Rate).
* **Responsive Engine:** Kiến trúc Fluid Grid giúp giao diện thích ứng hoàn hảo trên mọi kích thước màn hình từ 320px đến 4K.

### 2. Technical Implementation
* **State Management:** Quản lý giỏ hàng thông minh bằng JavaScript thuần, tối ưu hóa việc lưu trữ và cập nhật dữ liệu (Cart Logic) mà không cần nạp lại trang.
* **Security & Validation:** * Hệ thống **Captcha Engine** tự chọn mẫu ngẫu nhiên ngăn chặn spam bot.
    * Validation đa lớp cho form đăng ký (Tuổi, định dạng Email, Số điện thoại).
* **Dynamic Rendering:** Render sản phẩm dựa trên cấu trúc dữ liệu JSON-like, dễ dàng chuyển đổi sang kết nối API thực tế (RESTful/GraphQL).

---

## 🛠 Tech Stack & Architecture

| Layer | Technology | Role |
| :--- | :--- | :--- |
| **Frontend** | HTML5 / CSS3 (ES6+) | Cơ trúc và phong cách hóa hệ thống |
| **Logic** | Vanilla JavaScript | Xử lý nghiệp vụ giỏ hàng & Auth |
| **Icons** | Font Awesome 6 | Hệ thống chỉ thị trực quan |
| **Fonts** | Google Fonts API | Định hình nhận diện thương hiệu |

---

## 🧬 Key Modules

### 🛒 Smart Cart System
Thuật toán xử lý giỏ hàng cho phép tính toán tổng tiền thực tế, cập nhật số lượng (Inventory simulation) và đồng bộ trạng thái UI ngay lập tức.

### 🔐 Secure Auth Gate
Quy trình xác thực người dùng được thiết kế chuyên nghiệp với:
- Chế độ chuyển đổi Tab (Login/Register) mượt mà.
- Tích hợp đăng nhập bên thứ ba (Oauth2 Simulation).
- Captcha Verification tự động làm mới.

### 💳 QR Payment Gateway
Tích hợp Modal thanh toán thông minh, giả lập hệ thống quét mã QR ngân hàng giúp rút ngắn quy trình Checkout truyền thống.

---

## 🚀 Getting Started

1. **Clone & Explore:**
   ```bash
   git clone [https://github.com/yourusername/repo-name.git](https://github.com/yourusername/repo-name.git)
