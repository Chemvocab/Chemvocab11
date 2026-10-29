ChemVocab 11 – Giao diện danh sách và Speaking Lab

CÀI ĐẶT
1. Mở repository GitHub của dự án.
2. Chọn Add file > Upload files.
3. Tải index.html trong bộ này lên để thay thế bản cũ.
4. Nhấn Commit changes và chờ GitHub Pages cập nhật.

CÁC CẢI TIẾN
- Chế độ xem từ vựng dạng thẻ hoặc danh sách gọn.
- Tìm kiếm, lọc chủ đề, sắp xếp và nút xóa bộ lọc.
- Thanh điều hướng thân thiện hơn trên màn hình điện thoại.
- Speaking Lab: nghe phát âm tiếng Anh bằng SpeechSynthesis, nhận diện giọng nói bằng Web Speech API nếu trình duyệt hỗ trợ, luyện thuật ngữ và câu mẫu.

GIỚI HẠN QUAN TRỌNG
Speaking Lab hiện sử dụng chức năng giọng nói của trình duyệt và phản hồi tự động dựa trên mức độ khớp văn bản. Đây chưa phải mô hình AI hội thoại thực sự, không đánh giá chính xác âm vị/trọng âm như chuyên gia. Nhận diện giọng nói có thể không hoạt động trên mọi trình duyệt/thiết bị và thường cần HTTPS, quyền micro, đôi khi cần kết nối mạng.
Muốn tích hợp mô hình AI hội thoại thực sự, cần thêm backend an toàn gọi API AI; không đặt API key bí mật trực tiếp trong index.html vì mã nguồn website công khai có thể làm lộ khóa.

DỮ LIỆU
Website hiện tiếp tục lưu tiến độ trong localStorage của trình duyệt trên từng thiết bị; chưa đồng bộ giữa thiết bị và chưa có bảng điều khiển giáo viên.
