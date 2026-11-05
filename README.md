# Ôn tập Kinh tế học vi mô V3.4 — Mobile UX

Trang web tĩnh cho GitHub Pages. Ngân hàng câu hỏi, đáp án, giải thích và cơ chế lưu tiến độ giữ nguyên từ V3.4; chỉ tối ưu giao diện làm bài trên điện thoại.

## Triển khai GitHub Pages

1. Tạo repo `on-tap-kinh-te-vi-mo` (Public).
2. Chọn **Add file → Upload files** và tải **`index.html`** lên thư mục gốc của repo (thay file cũ nếu có).
3. **Commit changes**.
4. Vào **Settings → Pages → Build and deployment**: Source = **Deploy from a branch**, Branch = **main**, Folder = **/(root)**, rồi Save.
5. Mở `https://TEN-TAI-KHOAN.github.io/on-tap-kinh-te-vi-mo/`.

## Trên điện thoại

- Vùng làm bài đầu tiên cao khoảng một màn hình (câu hỏi, đáp án, kiểm tra, làm lại, câu trước/tiếp).
- Với câu có nội dung quá dài, **chỉ khung câu hỏi/đáp án cuộn bên trong**; các nút luôn hiện ở dưới khung, không phải cuộn toàn bộ trang để tìm nút.
- Lời giải/giải thích và danh sách câu nằm bên dưới vùng làm bài; chỉ cuộn trang khi muốn xem.
- Nội dung ôn và lưu tiến độ trên thiết bị qua `localStorage` hoạt động không cần backend.

Không cần Node, npm, database hay hosting riêng. Không yêu cầu thư viện CDN.
