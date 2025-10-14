# 🏥 Health Checker - Trợ lý Chăm sóc sức khỏe được hỗ trợ bằng AI

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20App-blue?style=for-the-badge)](https://healthcheckersgu-996c684714f1.herokuapp.com/)
[![Python](https://img.shields.io/badge/Python-3.9+-blue?style=for-the-badge&logo=python)](https://python.org)
[![Flask](https://img.shields.io/badge/Flask-2.0+-green?style=for-the-badge&logo=flask)](https://flask.palletsprojects.com/)
[![AI Powered](https://img.shields.io/badge/AI-Google%20Gemini-orange?style=for-the-badge&logo=google)](https://ai.google.dev/)

> **Một nền tảng quản lý chăm sóc sức khỏe được hỗ trợ bởi AI toàn diện, cách mạng hóa việc theo dõi sức khỏe cá nhân và tư vấn y tế nhờ trí tuệ nhân tạo tiên tiến.**

## 🌟 Tổng quan

Health Checker là một ứng dụng web sáng tạo kết nối công nghệ AI tiên tiến với các công cụ quản lý chăm sóc sức khỏe thiết thực. Được xây dựng với Flask và được hỗ trợ bởi Google Gemini AI, nền tảng này cung cấp phân tích sức khỏe thông minh, tư vấn y tế cá nhân hóa và nhắc nhở sức khỏe tự động để giúp người dùng duy trì sức khỏe tối ưu.

**🔗 Ứng dụng trực tiếp:** [https://healthcheckersgu-996c684714f1.herokuapp.com/](https://healthcheckersgu-996c684714f1.herokuapp.com/)

## ✨ Các tính năng nổi bật

### 🤖 Phân tích Y tế được hỗ trợ bởi AI
- **Phân tích Tài liệu Y tế**: Tải lên và phân tích hồ sơ y tế, đơn thuốc và báo cáo xét nghiệm bằng OCR tiên tiến và diễn giải bằng AI
- **Đánh giá Sức khỏe Thể chất**: Phân tích thành phần cơ thể bằng AI thông qua nhận diện hình ảnh
- **Những Gợi ý Sức khỏe Thông minh**: Khuyến nghị sức khỏe toàn diện dựa trên dữ liệu đã phân tích

### 🩺 Bác sĩ AI ảo
- **Tư vấn bằng Giọng nói**: Tương tác bằng giọng nói theo thời gian thực với trợ lý y tế AI
- **Tích hợp Chuyển văn bản sang giọng nói**: Chuyển văn bản thành giọng nói tự nhiên bằng công nghệ TTS của ElevenLabs
- **Hỗ trợ Đa ngôn ngữ**: Hỗ trợ Đa ngôn ngữ: Chủ yếu tiếng Việt với khả năng tiếng Anh
- **Cơ sở Kiến thức Y tế**: Cơ sở kiến thức y tế được AI đào tạo sâu rộng để cung cấp hướng dẫn sức khỏe chính xác

### 📅 Quản lý Sức khỏe Thông minh
- **Nhắc nhở Thông minh**: Thông báo tự động về thuốc, tập luyện và lịch khám
- **Lịch trình Linh hoạt**: Tần suất nhắc nhở hàng ngày, hàng tuần và hàng tháng
- **Thông báo qua Email**: Cảnh báo email cho các hoạt động sức khỏe quan trọng
- **Nhận diện múi giờ**: Tối ưu múi giờ Việt Nam để lập lịch chính xác

### 📊 Lịch sử Sức khỏe Toàn diện
- **Theo dõi Phân tích**: Lịch sử đầy đủ của mọi phân tích tài liệu y tế
- **Theo dõi Tiến triển Sức khỏe**: Theo dõi các đánh giá sức khỏe thể chất theo thời gian
- **Lưu trữ Tư vấn**: Lịch sử đối thoại với bác sĩ AI có thể tra cứu
- **Xuất Dữ liệu**: Truy cập dễ dàng vào dữ liệu sức khỏe lịch sử

### 🔐 Quản trị Người dùng An toàn
- **Xác thực Email**: Tạo tài khoản an toàn với xác thực email
- **Bảo mật Mật khẩu**: Lưu trữ mật khẩu được mã hóa với chuẩn băm ngành
- **Quản lý Phiên**: Phiên người dùng an toàn với xác thực JWT
- **Quyền riêng tư Dữ liệu**: Xử lý và lưu trữ dữ liệu tuân thủ GDPR

## 🛠️ Bộ công nghệ

### Kiến trúc Backend
- **Framework**: Flask (Python) - Framework web nhẹ và có thể mở rộng
- **Cơ sở dữ liệu**: MySQL với ORM SQLAlchemy cho quản lý dữ liệu mạnh mẽ
- **Tích hợp AI**: Google Gemini 2.0 Flash cho xử lý ngôn ngữ tiên tiến
- **Xử lý Giọng nói**: ElevenLabs API cho chuyển đổi văn bản thành giọng nói tự nhiên
- **Lên lịch Công việc**: APScheduler cho hệ nhắc nhở tự động

### Hạ tầng Đám mây
- ** Hosting**: Heroku với khả năng tự động mở rộng
- ** Lưu trữ Tệp**: Cloudinary cho lưu trữ hình ảnh và âm thanh tối ưu
- ** Dịch vụ Email**: Gmail SMTP tích hợp cho thông báo đáng tin cậy
- ** Cơ sở Dữ liệu**: AWS RDS MySQL cho lưu trữ dữ liệu có sẵn cao

### Công nghệ Frontend
- **UI Framework**: Bootstrap 5 cho thiết kế đáp ứng
- **JavaScript**: ES6+ hiện đại cho các tính năng tương tác
- **CSS3**: Thiết kế tùy chỉnh theo hướng ưu tiên di động
- **Icon**: Font Awesome cho biểu tượng chuyên nghiệp

## 🚀 Cài đặt & Thiết lập

### Yêu cầu trước
- Python 3.9 trở lên
- Cơ sở dữ liệu MySQL
- Khoá API Google Gemini
- Khoá API ElevenLabs
- Tài khoản Cloudinary

### Phát triển tại máy

1. **Clone Kho lưu trữ**
   ```bash
   git clone https://github.com/zaikaman/health-checker.git
   cd health-checker
   ```

2. **Cài đặt phụ thuộc**
   ```bash
   pip install -r requirements.txt
   ```

3. **Cấu hình Môi trường**
   ```bash
   # Thiết lập biến môi trường của bạn
   export GEMINI_API_KEY="your_gemini_api_key"
   export ELEVENLABS_API_KEY="your_elevenlabs_api_key"
   export DATABASE_URL="your_mysql_connection_string"
   ```

4. **Cài đặt Cơ sở Dữ liệu**
   ```bash
   # Ứng dụng sẽ tự động tạo bảng khi chạy lần đầu
   python app.py
   ```

5. **Chạy Ứng dụng**
   ```bash
   python app.py
   # hoặc cho sản phẩm
   gunicorn app:app --preload
   ```

## 📱 Hướng dẫn Sử dụng

### Bắt đầu
1. **Đăng ký**: Tạo tài khoản với xác thực email
2. **Đăng nhập**: Truy cập bảng điều khiển cá nhân
3. **Tải lên Tài liệu**: Phân tích hồ sơ y tế và đơn thuốc
4. **Đánh giá Sức khỏe**: Tải lên ảnh cho phân tích thể chất bằng AI
5. **Tư vấn với AI Bác sĩ**: Tư vấn bằng giọng nói hoặc văn bản với AI y tế
6. **Thiết lập Nhắc nhở**: Tạo thông báo sức khỏe tự động

### Điểm cuối API
- `GET /` - Bảng điều khiển chính
- `POST /file_analysis` - Phân tích tài liệu y tế
- `POST /health_analysis` - Đánh giá sức khỏe thể chất
- `POST /analyze_audio` - Tư vấn giọng nói của bác sĩ AI
- `GET /history` - Lịch sử phân tích
- `POST /reminders` - Quản lý nhắc nhở sức khỏe

## 🏗️ Cấu trúc Dự án

```
health-checker/
├── app.py                 # Main Flask application
├── requirements.txt       # Python dependencies
├── Procfile              # Heroku deployment configuration
├── runtime.txt           # Python version specification
├── utils/                # Utility modules
│   ├── gemini_integration.py   # AI analysis logic
│   ├── audio_utils.py          # Audio processing
│   ├── email_utils.py          # Email functionality
│   ├── reminder_utils.py       # Scheduling system
│   └── validation_utils.py     # Input validation
├── templates/            # HTML templates
│   ├── index.html        # Main dashboard
│   ├── ai_doctor.html    # AI consultation interface
│   ├── file_analysis.html # Document analysis page
│   ├── health_analysis.html # Physical assessment page
│   └── reminders.html    # Reminder management
├── static/               # Static assets
│   ├── css/             # Stylesheets
│   ├── js/              # JavaScript files
│   └── images/          # Application assets
└── uploads/             # Temporary file storage
```

## 🔧 Mô hình Cơ sở dữ liệu

### Mô hình Cốt lõi
- **User**: Xác thực và quản lý hồ sơ
- **FileAnalysis**: Ghi lại phân tích tài liệu y tế
- **HealthAnalysis**: Dữ liệu đánh giá sức khỏe thể chất
- **AiDoctor**: Lịch sử hội thoại tư vấn AI
- **HealthReminder**: Hệ thống nhắc nhở bằng thông báo tự động

## 🌐 Triển khai

Ứng dụng đã sẵn sàng cho triển khai và được triển khai trên Heroku với:
- Chứng chỉ SSL tự động
- Khả năng mở rộng theo chiều ngang
- Triển khai liên tục từ Git
- Quản lý biến môi trường
- Kết nối cơ sở dữ liệu được tối ưu

## 🔮 Các cải tiến tương lai

- **Ứng dụng di động**: Ứng dụng native iOS và Android
- **Tích hợp thiết bị đeo**: Kết nối Apple Watch và Fitbit
- **Phân tích nâng cao**: Phân tích xu hướng sức khỏe bằng học máy
- **Telemedicine**: Tư vấn từ xa bằng video
- **Hỗ trợ đa ngôn ngữ**: Mở rộng các ngôn ngữ
- **Tài liệu API**: Tích hợp OpenAPI/Swagger

## 👨‍💻 Nhà phát triển

**Đinh Phúc Thịnh**
- 💼 **LinkedIn**: [https://www.linkedin.com/in/đinh-phúc-thịnh-2561b5274](https://www.linkedin.com/in/%C4%91inh-ph%C3%BAc-th%E1%BB%8Bnh-2561b5274)
- 🐙 **GitHub**: [https://github.com/zaikaman](https://github.com/zaikaman)
- 📧 **Email**: [zaikaman123@gmail.com](mailto:zaikaman123@gmail.com)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 🙏 Acknowledgments

- Google Gemini AI cho xử lý ngôn ngữ tiên tiến
- ElevenLabs cho tổng hợp giọng nói tự nhiên
- Cloudinary cho lưu trữ phương tiện đáng tin cậy
- Cộng đồng mở nguồn cho các công cụ và thư viện tuyệt vời

---

<div align="center">

**Xây dựng với ❤️ để cải thiện khả năng tiếp cận chăm sóc sức khỏe**

*Làm cho chăm sóc sức khỏe được hỗ trợ bởi AI đến với mọi người, ở mọi nơi.*

</div>