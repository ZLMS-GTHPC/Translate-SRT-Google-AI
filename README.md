# **Translate-SRT Google-Gemini-AI**

## Giới thiệu

**Translate SRT** là một phần mềm hỗ trợ dịch file phụ đề định dạng `.srt` nhanh chóng và chính xác bằng AI. Công cụ được thiết kế để giúp người dùng dễ dàng chuyển đổi phụ đề sang nhiều ngôn ngữ khác nhau mà vẫn giữ nguyên cấu trúc thời gian và định dạng gốc.

## Tính năng chính

* Dịch file phụ đề `.srt` tự động
* Hỗ trợ nhiều ngôn ngữ khác nhau
* Tích hợp AI (Google Gemini / AI API)
* Tốc độ xử lý nhanh, tối ưu cho file với phụ đề nhiều
* Giữ nguyên timestamp và cấu trúc phụ đề
* Xuất file `.srt` đã dịch dễ dàng

## Công nghệ sử dụng

* Python
* CustomTkinter (giao diện UI)
* Google Generative AI (Gemini)
* Regex xử lý SRT
* Threading tối ưu hiệu suất


## Cách sử dụng

1. Mở phần mềm
2. Chọn file `.srt` cần dịch
3. Chọn model **Gemini** để dịch, khuyên nên chọn `gemini-3-flash-previw` dành cho dân free
4. Chọn phong cách dịch
5. Chọn ngôn ngữ đích
6. Số khối dịch, nên chọn (80 - 100 chunks)
7. Nhấn nút **Translate**
8. Chờ quá trình xử lý hoàn tất và chọn thư mục lưu

## Lưu ý

* Cần có `API key` để sử dụng AI dịch, nếu cành nhiều API key dịch càng nhanh, tốt nhận lấy một `API key` trong một tài khoản Google nếu dịch phụ đề dài và hạn chế lỗi **429 & 503**
* Đối với lấy `API key` có thể truy cập **Google AI Studio** hoặc https://aistudio.google.com/api-keys để lấy key
* File SRT phải đúng định dạng chuẩn
* Đối với các model: `gemini-pro-latest, gemini-3.1-pro-preview, gemini-2.5-pro` cần phải trả phí cho Google AI không phải cho phần mềm
