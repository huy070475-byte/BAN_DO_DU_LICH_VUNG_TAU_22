# WEBSITE BẢN ĐỒ SỐ CƠ SỞ LƯU TRÚ VŨNG TÀU - NCKH 2026

## 1. Giới thiệu
Mẫu website bản đồ số khảo sát 22 cơ sở lưu trú (CSLT) tại Vũng Tàu, bao gồm các nhóm khách sạn 5 sao, 4 sao, 3 sao và homestay/resort do nhóm học sinh/sinh viên thực hiện.
Website sử dụng thư viện Leaflet (mã nguồn mở), nền bản đồ OpenStreetMap và có thể đăng miễn phí lên GitHub Pages[cite: 1, 4].

## 2. Danh sách tệp
- `index.html`: Giao diện, bộ lọc theo loại hình, bản đồ tương tác và chức năng chỉ đường.
- `du_lieu.js`: Chứa 22 điểm cơ sở lưu trú gồm mã điểm, tên, loại hình, tọa độ (lat/lng), mô tả chi tiết và đường dẫn ảnh (nếu có).
- `anh/`: Thư mục chứa ảnh thực địa của các cơ sở lưu trú (nếu có).

## 3. Chạy thử trên máy tính
Giải nén thư mục dự án, mở tệp `index.html` bằng trình duyệt Google Chrome hoặc Microsoft Edge. Cần có kết nối Internet để tải Leaflet và lớp nền bản đồ[cite: 1, 4].

## 4. Đăng website MIỄN PHÍ bằng GitHub Pages[cite: 1, 4]
1. Truy cập vào https://github.com và đăng nhập tài khoản của bạn[cite: 1, 4].
2. Chọn **New repository**, đặt tên (ví dụ: `ban-do-luu-tru-vung-tau`), chọn chế độ **Public**, nhấn **Create repository**[cite: 1, 4].
3. Trong kho mã vừa tạo, chọn **Add file > Upload files**. Kéo thả các tệp `index.html`, `du_lieu.js`, `README.md` và thư mục `anh/` (nếu có) vào thư mục gốc, sau đó nhấn **Commit changes**[cite: 1, 4].
4. Chuyển sang thẻ **Settings > Pages**. Tại phần *Build and deployment*: chọn **Deploy from a branch**, chọn nhánh `main` và thư mục `/(root)`, rồi nhấn **Save**[cite: 1, 4].
5. Sau vài phút, GitHub Pages sẽ xuất bản website với đường dẫn dạng: `https://TEN-GITHUB.github.io/ban-do-luu-tru-vung-tau/`[cite: 1, 4].

## 5. Thêm ảnh và chỉnh sửa dữ liệu
- **Ảnh thực địa:** Lưu ảnh vào thư mục `anh/` (ví dụ: `anh/5S01.jpg`). Trong `du_lieu.js`, cập nhật thuộc tính `image` tương ứng từ `""` thành `"anh/5S01.jpg"`[cite: 1, 4].
- **Sửa thông tin:** Chỉnh sửa trực tiếp tên, địa chỉ hoặc mô tả trong `du_lieu.js`[cite: 1, 4].
- **Chỉ đường:** Nút chỉ đường tích hợp sẵn sẽ liên kết trực tiếp tới Google Maps khi người dùng thao tác[cite: 1, 4].

## 6. Lưu ý quan trọng
- Tọa độ và nội dung mô tả được lấy từ dữ liệu khảo sát thực tế của nhóm, cần đối chiếu kỹ trước khi báo cáo chính thức[cite: 1, 4].
- Tuân thủ các chính sách sử dụng mã nguồn mở và tile bản đồ của OpenStreetMap[cite: 1, 4].