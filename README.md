PHẦN 1: PHÂN TÍCH VÀ ĐỀ XUẤT GIẢI PHÁP
1. Tại sao máy tính bị giật lag và hiện tượng "Swap/Page File" là gì?
•	Tại sao máy lag (RAM 98%): Trình duyệt Chrome ngốn rất nhiều bộ nhớ. Mở 30 tab làm RAM bị tràn không còn chỗ trống để máy xử lý dữ liệu.
•	Swap / Page File là gì: Khi RAM đầy, Windows tự động lấy một phần ổ cứng ra để dùng tạm làm RAM 
•	Tác động đến máy: Tốc độ của ổ cứng chậm hơn RAM rất nhiều. Ổ cứng làm nhiệm vụ của RAM khiến máy bị chậm, chuột di chuyển giật lag.
2. So sánh giữa ổ HDD và SSD NVMe trong tình huống này
Tiêu chí	Dùng ổ HDD	Dùng ổ SSD NVMe
Tốc độ đọc/ghi	Rất chậm	Rất nhanh 
Khi tràn RAM (98%)	Máy đơ cứng/treo: Chuột đứng hình do HDD quay không kịp để xử lý dữ liệu ảo.	Chỉ bị mượt nhẹ: Máy vẫn chạy ổn định vì SSD xử lý dữ liệu ảo rất nhanh.
3. Sơ đồ IPO đơn giản của 1 tab Chrome
  INPUT => PROCESS =>  OUTPUT 
Mở tab / Nhập URL   CPU xử lý dữ liệu   Màn hình hiển thị
4. 3 hành động giải phóng RAM ngay lập tức
1.	Đóng bớt các tab Chrome không dùng 
2.	Tắt tab tốn RAM bằng Task Manager của Chrome .
3.	Tắt ứng dụng chạy ngầm bằng Windows
PHẦN 2: BÁO CÁO CHẨN ĐOÁN 
•	Thời điểm kiểm tra: 22:00
•	Kết quả đo thực tế từ Task Manager:
o	CPU: 30% (Hoạt động bình thường)
o	RAM: 98% (Cảnh báo: Đã quá tải)
o	Disk: 90% (Ổ cứng đang gánh tải cho RAM)
•	Đánh giá & Khuyên dùng: Máy bị chậm do thiếu RAM. Cách khắc phục lâu dài là tắt bớt ứng dụng ngầm hoặc nâng cấp thêm RAM/SSD cho máy.

