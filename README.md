# 🏆 Silk FPGA Challenge - Đợt 1: Logic Hunter

Chào mừng các bạn đến với đợt 1 của cuộc thi **Silk FPGA Challenge** mang tên **Logic Hunter**!

Trong thử thách này, nhiệm vụ của bạn là phân tích mã nguồn, tìm ra và sửa các lỗi logic để hệ thống có thể hoạt động và hiển thị chính xác lên màn hình thông qua board ảo Remote Lab.

## 📝 Đề bài chi tiết

- **File làm việc chính:** `de_bai.sv`
- **Mô tả:** File này sẽ được dùng làm khối **top-module**, thay thế cho khối `vga.v` hiện hành trên repository GitHub của Silk FPGA tại đường dẫn: [https://github.com/HUYATIEO/silk-fpga](https://github.com/HUYATIEO/silk-fpga).
- **Thử thách:** Trong file đề bài sẽ cố ý đặt **03 lỗi logic**. Các lỗi này nằm rải rác trên 03 dòng code khác nhau (mỗi lỗi chỉ nằm ở 1 chỗ duy nhất). Nhiệm vụ của bạn là đọc hiểu đoạn mã, khoanh vùng và sửa lại cho đúng logic phần cứng.
- **Lưu ý quy ước đặt tên:** Tên file .js nộp bài phải trùng khớp với tên thí sinh đã đăng ký. Ví dụ: Nếu bạn nhập tên là huyatieo thì file nộp bài bắt buộc phải có tên là huyatieo.js.

- **⚠️ Yêu cầu giám sát (BẮT BUỘC):** Trong suốt quá trình làm bài thi, thí sinh phải có camera quay lại toàn bộ màn hình. Lưu ý thật kỹ quy định này, nếu không tuân thủ, bài thi của bạn sẽ bị vô hiệu hóa ngay lập tức.

## 🚀 Hướng dẫn tham gia thi

Để hoàn thành phần thi một cách tốt nhất, các bạn thực hiện theo các trình tự sau:

1. **Bắt đầu tính giờ & Sửa code:**
   - Khi bạn chính thức bắt đầu bài thi, hệ thống sẽ kích hoạt **Timer (đồng hồ bấm giờ)**.
   - Bắt tay vào debug và sửa các lỗi trong file `de_bai.sv`.

2. **Biên dịch và tạo file nạp (.js):**
   - Sau khi thực hiện sửa code, để kiểm tra lại kết quả, bạn thực hiện các bước như hướng dẫn sử dụng của repository GitHub Silk FPGA tại đường dẫn: [https://github.com/HUYATIEO/silk-fpga](https://github.com/HUYATIEO/silk-fpga).
   - **Lưu ý quan trọng:** Bạn cần thay thế file `vga.v` gốc thành file `de_bai.sv` của bạn trong quá trình build để tạo ra file `.js`.

3. **Kiểm tra trên Board ảo & Nộp bài:**
   - Đem file `.js` vừa tạo nạp lên board ảo tại đường dẫn: [https://silkfpga.ctw-sevina.com/](https://silkfpga.ctw-sevina.com/).
   - Bạn có thể liên tục sửa lỗi và nạp thử cho đến khi màn hình VGA của board ảo đã hiển thị đúng.
   - Khi kết quả trên VGA đã chuẩn xác, tiến hành **nộp lại file `.js` đó trực tiếp tại website của Remote Lab luôn**.
   - **Nộp bài thành công -> Bay lên Bảng Xếp Hạng!** Thời gian hoàn thành càng ngắn, thứ hạng của bạn càng cao.

---
*Chúc các Thợ săn logic "săn bug" thành công và đạt thứ hạng cao nhất!* 🐛🔨
