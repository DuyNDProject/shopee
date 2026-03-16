- **Phân loại lỗi (Categorization):** Tách biệt rõ ràng giữa lỗi nghiệp vụ (sai dữ liệu đầu vào, hết hạn phiên) và lỗi hệ thống (sập DB, lỗi logic code).

- **Ghi chú ngữ cảnh (Contextual Logging):** Đảm bảo mỗi lỗi văng ra đều mang theo "dấu vết" của function hoặc module nơi nó phát sinh, giúp việc debug tại Production nhanh hơn gấp nhiều lần.

- **Bảo vệ dữ liệu (Data Sanitization):** Chặn đứng nguy cơ rò rỉ thông tin nhạy cảm của hệ thống ra ngoài thông qua các thông báo lỗi thô từ Database hoặc Server.
