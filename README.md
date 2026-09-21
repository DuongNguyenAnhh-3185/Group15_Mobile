# Group15_Mobile

Ứng dụng di động được phát triển bằng Flutter và Dart trong khuôn khổ dự án nhóm 15.

## Công nghệ

- Flutter
- Dart
- Android Studio

## Yêu cầu môi trường

- Flutter SDK phiên bản ổn định mới nhất
- Dart SDK đi kèm Flutter
- Android Studio và Android SDK
- Thiết bị Android hoặc Android Emulator

Kiểm tra môi trường bằng:

```bash
flutter doctor
```

## Cài đặt và chạy dự án

1. Clone repository:

   ```bash
   git clone https://github.com/DuongNguyenAnhh-3185/Group15_Mobile.git
   cd Group15_Mobile
   ```

2. Cài đặt dependencies:

   ```bash
   flutter pub get
   ```

3. Kết nối thiết bị hoặc khởi động emulator, sau đó chạy:

   ```bash
   flutter run
   ```

4. Chạy kiểm tra trước khi tạo Pull Request:

   ```bash
   flutter analyze
   flutter test
   ```

## Phân công thành viên

| Thành viên | Vai trò | Trách nhiệm chính |
| --- | --- | --- |
| `DuongNguyenAnhh-3185` | Trưởng nhóm / tích hợp | Phân chia công việc, quản lý issue, review và tích hợp code |
| `nguyenlinh260803` | Thành viên 1 | Phát triển tính năng và viết test theo issue được giao |
| `THÀNH_VIÊN_3` | Thành viên 2 | Thiết kế giao diện và triển khai các màn hình Flutter |
| `THÀNH_VIÊN_4` | Thành viên 3 | Xử lý dữ liệu, kiểm thử và hoàn thiện tài liệu |

Thay `THÀNH_VIÊN_3` và `THÀNH_VIÊN_4` bằng GitHub username thực tế khi thêm thành viên.

## Quy trình Git và Pull Request

- Nhánh chính là `main`; không push trực tiếp vào `main`.
- Mỗi công việc bắt đầu từ một nhánh mới theo quy ước `feature/<mo-ta>`, `fix/<mo-ta>` hoặc `docs/<mo-ta>`.
- Commit nên ngắn gọn và mô tả đúng thay đổi.
- Mở Pull Request vào `main`, điền mẫu PR và yêu cầu ít nhất một thành viên review.
- Chỉ merge khi CI kiểm tra thành công, đã xử lý góp ý và không còn conflict.
- Sau khi merge, xóa branch đã hoàn tất để repository luôn gọn.

## Thành viên cộng tác

Repository hiện cấp quyền `Write` cho `nguyenlinh260803`. Các thành viên còn lại sẽ được bổ sung trong mục **Settings > Collaborators** khi có GitHub username.

## Trạng thái dự án

Repository đang được khởi tạo. Cập nhật phần này khi có phiên bản đầu tiên và các mốc phát hành.