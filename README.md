# Tu Hán Ngữ

App Android học tiếng Trung theo phong cách tu tiên: phát âm, thanh điệu, flashcard có âm Hán Việt, luyện nghe và luyện nói.

## Build
Mỗi lần đẩy code lên nhánh `main`, GitHub Actions tự build APK. File `TuHanNgu.apk` nằm ở mục **Releases** của repo.

## Sửa nội dung
Toàn bộ app nằm trong `www/index.html`. Từ vựng là các dòng dạng `chữ|pinyin|Hán Việt|nghĩa` trong biến `HSK1`, `CONGSO`, `TANGKINH`.
