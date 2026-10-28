# Phiên dịch trực tiếp

App web cài được (PWA), giao diện tối giản theo màn hình phiên dịch Samsung. Dịch tiếng Hàn sang tiếng Việt bằng micro, clip trên máy hoặc âm thanh tab video live. Bản gốc và bản dịch hiện cạnh nhau; app thử dịch cả lời đang nhận dạng để phụ đề theo sát lời nói hơn. A−/A+ chỉnh cỡ chữ; app không đọc lại bản dịch thành tiếng.

## Chạy trên máy tính

1. Nhấp đúp run-local.bat.
2. Dùng Chrome hoặc Edge mới tại localhost và cho phép Micro khi được hỏi.
3. Nhấn nút bắt đầu để dịch hội thoại Hàn sang Việt; nhấn Video để chọn clip hoặc chia sẻ tab live.

## Dịch video

- Clip: chọn tệp, nhấn Dịch clip rồi phát. Bản dịch hiện trong bản ghi, trên khung video và ở bảng phụ đề ngay dưới video.
- Live: nhấn Chia sẻ tab live, chọn tab đang phát và bật chia sẻ âm thanh tab. Bản dịch hiện trong bản ghi, trên khung xem trước và ở bảng phụ đề trong cửa sổ Video.
- Trên điện thoại, chia sẻ âm thanh tab có thể bị giới hạn; có thể phát video trên thiết bị khác rồi dùng chế độ mic.
- Nhận dạng âm thanh tab/clip phụ thuộc hỗ trợ của trình duyệt. Nếu không nhận được tiếng, app hiện lý do ngay trong cửa sổ Video. Chrome/Edge mới trên máy tính là mục tiêu chính.
- Dịch câu cần Internet. Tùy trình duyệt, âm thanh có thể được gửi tới dịch vụ nhận dạng trực tuyến.

## Cài như ứng dụng

Manifest, service worker và biểu tượng 192/512 px đã được thêm. Trên máy tính, mở bằng Edge/Chrome rồi chọn Cài ứng dụng. Trên Samsung, app cần được host bằng HTTPS rồi cài từ Chrome/Samsung Internet. run-local.bat chỉ phục vụ localhost trên máy tính.

## Thuật ngữ chuyên ngành

glossary-ko-vi.json được đóng gói cục bộ, gồm dữ liệu lớn, phần mềm, hạ tầng CNTT, điện tử và bán dẫn. Từ khớp được bảo vệ khi dịch rồi thay bằng nghĩa chuyên ngành. Nguồn tham khảo: https://terms.tta.or.kr/main.do và https://semiconductor.samsung.com/kr/support/tools-resources/dictionary/just-the-essentials-semiconductor-terminologyzip/.
