# DSA-project
Decision Tree


Mô tả. Cây quyết định là mô hình học máy dạng cây: mỗi nút trong kiểm tra một thuộc tính, mỗi nhánh ứng với một giá trị (hoặc một khoảng giá trị) của thuộc tính, mỗi nút lá là một nhãn phân loại. Cây được xây dựng tự động từ dữ liệu huấn luyện bằng các giải thuật ID3, C4.5, CART và được dùng rộng rãi trong chấm điểm tín dụng, chẩn đoán y khoa, dự báo khách hàng rời bỏ dịch vụ.
Nội dung tìm hiểu. Cấu trúc nút của cây quyết định; giải thuật ID3 (đệ quy chọn thuộc tính có
độ lợi thông tin lớn nhất); entropy H(S) = −∑pi log2 pi, độ lợi thông tin, chỉ số Gini; xử lý thuộc tính liên tục bằng ngưỡng chia (sắp xếp giá trị rồi thử các điểm cắt); hiện tượng quá khớp và cắt tỉa (giới hạn độ sâu, số mẫu tối thiểu ở nút); độ phức tạp xây dựng và phân loại. Tài liệu gợi ý: J. R. Quinlan, Induction of Decision Trees, Machine Learning, 1986.
Chương trình minh họa.
• Đọc tập dữ liệu dạng CSV; chạy tay và chạy máy trên bộ dữ liệu kinh điển “Chơi tennis” (14
mẫu), in độ lợi thông tin của từng thuộc tính tại mỗi bước.
• Xây dựng cây bằng ID3 (thuộc tính rời rạc) và mở rộng cho thuộc tính liên tục; in cây dạng
thụt lề, đếm số nút, chiều cao.
• Phân loại mẫu mới nhập từ bàn phím, in đường đi từ gốc đến lá (giải thích quyết định).
• Ứng dụng: dự đoán sinh viên đạt/không đạt học phần từ các thuộc tính (tỉ lệ đi học, điểm
quá trình, số giờ tự học, ...); chia dữ liệu 70% huấn luyện – 30% kiểm tra, tính độ chính xác
và ma trận nhầm lẫn.
Nâng cao. Cắt tỉa cây và so sánh độ chính xác trước/sau cắt tỉa; cài đặt rừng ngẫu nhiên
(Random Forest) gồm nhiều cây quyết định bỏ phiếu.
