# HỆ THỐNG LỌC CỔ PHIẾU TỰ ĐỘNG TẠI THỊ TRƯỜNG SAUDI ARABIA

**Dự án nhóm | Phân tích dữ liệu tài chính | Dashboard | Stock Screening**

## 1. Giới thiệu dự án

Dự án xây dựng hệ thống lọc cổ phiếu tự động dựa trên các tiêu chí phân tích cơ bản, nhằm hỗ trợ người dùng sàng lọc và đánh giá doanh nghiệp niêm yết trên thị trường chứng khoán Saudi Arabia.

Hệ thống tích hợp quy trình xử lý dữ liệu tài chính, thiết lập bộ tiêu chí lọc và trực quan hóa kết quả thông qua dashboard tương tác.

**Mục tiêu dự án:**
- Xây dựng hệ thống lọc cổ phiếu dựa trên các chỉ tiêu tài chính.
- Chuẩn hóa và xử lý dữ liệu từ báo cáo tài chính doanh nghiệp.
- Thiết kế bộ lọc theo nhiều chiến lược đầu tư.
- Phát triển dashboard trực quan hóa dữ liệu.
- Hỗ trợ người dùng tra cứu và so sánh thông tin tài chính doanh nghiệp.

## 2. Công nghệ và công cụ sử dụng

| Công nghệ | Mục đích |
|---|---|
| HTML | Xây dựng cấu trúc giao diện website |
| CSS | Thiết kế giao diện |
| JavaScript | Xử lý dữ liệu và xây dựng logic lọc |
| Excel / CSV | Định dạng dữ liệu đầu vào |
| JSON | Tổ chức dữ liệu sau khi đọc từ Excel |

## 3. Dữ liệu nghiên cứu

Hệ thống sử dụng dữ liệu tài chính của các doanh nghiệp niêm yết tại Saudi Arabia trong giai đoạn 2015–2024.

**Quy mô dữ liệu:**
- 390 doanh nghiệp có dữ liệu báo cáo năm.
- 273 doanh nghiệp có dữ liệu báo cáo quý.

Các nhóm chỉ tiêu tài chính được sử dụng bao gồm:

- **Định giá:** P/E, P/B.
- **Khả năng sinh lời:** ROE, ROA.
- **Hiệu quả kinh doanh:** Doanh thu, lợi nhuận gộp, EBIT.
- **Dòng tiền:** CFO.
- **Cấu trúc tài chính:** D/E, Current Ratio.

## 4. Quy trình thực hiện

### Bước 1: Thu thập và xử lý dữ liệu

- Tổng hợp dữ liệu tài chính từ các doanh nghiệp niêm yết.
- Đọc và chuyển đổi dữ liệu Excel sang cấu trúc JSON.
- Chuẩn hóa tên cột và định dạng dữ liệu số.
- Xử lý các giá trị không hợp lệ.
- Tính toán bổ sung các chỉ số tài chính cần thiết.
- Tổ chức dữ liệu theo năm, quý và mã cổ phiếu.

### Bước 2: Xây dựng bộ tiêu chí lọc

Hệ thống hỗ trợ các nhóm chiến lược:

**Nhóm phòng thủ:**
- Đầu tư giá trị.
- Doanh nghiệp chất lượng cao.
- Đầu tư cổ tức.
- Tránh rủi ro kiệt quệ tài chính.

**Nhóm tấn công:**
- CANSLIM.
- Đầu tư tăng trưởng.
- Đầu tư theo đà.
- Đầu tư chu kỳ.

Ngoài ra, người dùng có thể thiết lập bộ lọc tùy chỉnh bằng các ngưỡng P/E, P/B, ROE và ROA.

### Bước 3: Xây dựng logic lọc tự động

- Thiết lập điều kiện lọc theo từng chiến lược.
- Cho phép kết hợp nhiều chiến lược đồng thời.
- Áp dụng logic AND để xác định doanh nghiệp đáp ứng các tiêu chí.
- Trả về danh sách cổ phiếu phù hợp với điều kiện được lựa chọn.

### Bước 4: Thiết kế dashboard

Dashboard hỗ trợ:

- Tải dữ liệu từ file Excel hoặc CSV.
- Lựa chọn dữ liệu theo năm hoặc quý.
- Lọc cổ phiếu theo chiến lược đầu tư.
- Tra cứu thông tin theo mã cổ phiếu.
- Hiển thị kết quả lọc dưới dạng bảng.
- Trực quan hóa doanh thu, lợi nhuận, ROE, ROA và dòng tiền.
- So sánh các doanh nghiệp theo những chỉ tiêu tài chính.

## 5. Kết quả dự án

Dự án đã xây dựng hệ thống lọc cổ phiếu với các chức năng chính:

- Tự động xử lý và chuẩn hóa dữ liệu đầu vào.
- Sàng lọc doanh nghiệp dựa trên các chỉ tiêu tài chính.
- Hỗ trợ nhiều chiến lược phân tích cơ bản.
- Hiển thị kết quả qua dashboard tương tác.
- Cho phép người dùng tùy chỉnh điều kiện lọc và trực quan hóa dữ liệu.

Hệ thống được thiết kế để giảm các thao tác sàng lọc thủ công và hỗ trợ quá trình phân tích dữ liệu tài chính.

## 6. Kỹ năng thể hiện qua dự án

- Thu thập và xử lý dữ liệu tài chính.
- Làm sạch và chuẩn hóa dữ liệu.
- Xây dựng logic lọc dữ liệu.
- Phân tích các chỉ tiêu tài chính doanh nghiệp.
- Thiết kế dashboard tương tác.
- Trực quan hóa và trình bày kết quả phân tích.
- Phối hợp thực hiện dự án nhóm.

## 7. Mã nguồn và hướng dẫn sử dụng

Mã nguồn giao diện và bộ lọc được cung cấp trong file `index.html`.

**Hướng dẫn sử dụng:**

1. Tải file HTML về máy tính.
2. Mở file bằng trình duyệt web.
3. Tải dữ liệu Excel hoặc CSV có cấu trúc tương thích vào hệ thống.
4. Lựa chọn dữ liệu theo năm hoặc quý.
5. Chọn các chiến lược hoặc thiết lập điều kiện lọc.
6. Xem kết quả sàng lọc và các biểu đồ phân tích.

**Lưu ý:** Dữ liệu nghiên cứu gốc không được công khai trong repository. Người dùng cần chuẩn bị dữ liệu đầu vào tương ứng để sử dụng đầy đủ chức năng.

## 8. Thông tin dự án

- **Hình thức:** Dự án nhóm.
- **Học phần:** Phân tích chứng khoán.
- **Đơn vị:** Trường Đại học Kinh tế – Luật, ĐHQG TP.HCM.
- **Thời gian:** 03/2026.
- **Thị trường nghiên cứu:** Saudi Arabia.

---

*Dự án phục vụ mục đích học tập và nghiên cứu, không phải khuyến nghị đầu tư.*
