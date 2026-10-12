Tạo file ../cv.html (một file HTML tĩnh, CSS inline trong <style>, không JavaScript) trình bày CV từ phần nội dung trong 02_cv_content.md (CHỈ phần phía trên đường "---"; không đưa ghi chú vào CV, giữ nguyên văn nội dung, giữ nguyên các placeholder trong ngoặc vuông).

Bố cục phải mô phỏng sát ảnh mẫu ../IMG_0855.jpeg (hãy xem ảnh):
- Khổ A4 (210mm x 297mm), đúng 1 trang khi in; @page { size: A4; margin: 0 } và in được màu nền (print-color-adjust: exact).
- Dải nền gradient hồng nhạt ở phần đầu trang phía trên; cột trái (~35%) là khung bo góc viền tối chứa: ảnh chân dung bo góc (dùng <img src="photo.jpg">; nếu chưa có ảnh thì khung nền hồng nhạt với chữ "Ảnh 3x4" — dùng CSS để khung luôn hiển thị đẹp, ví dụ đặt ảnh lên trên một div placeholder), các dòng liên hệ có icon tròn nền hồng (dùng SVG inline đơn giản: lịch, điện thoại, thư, vị trí), mục "Trình độ học vấn", "Kỹ năng", "Ngoại ngữ & Công nghệ".
- Cột phải: Họ tên rất lớn, đậm, màu xám xanh đậm (#3d4a63 hoặc tương tự); chức danh "Tư vấn viên" bên dưới; các tiêu đề mục ("Mục tiêu nghề nghiệp", "Kinh nghiệm làm việc") nằm trên dải gradient hồng nhạt dần sang phải; tên công ty in đậm kèm thời gian, chức danh dòng thường, gạch đầu dòng chấm tròn, căn đều.
- Font: Google Fonts "Be Vietnam Pro" (hỗ trợ tiếng Việt đầy đủ).
- Họ tên hiển thị "Mông Hoài Vũ"; chức danh "Tư vấn viên".
- Kiểm tra kỹ dấu tiếng Việt, không lỗi chính tả.
