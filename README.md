# NasHubs website

Trang giới thiệu tại **https://nashubs.duconmang.io.vn**, cùng phong cách với [duconmang.io.vn](https://duconmang.io.vn) và [officelab.duconmang.io.vn](https://officelab.duconmang.io.vn).

- Trang tĩnh trong `site/` (HTML/CSS thuần, không cần build). GitHub Actions (`.github/workflows/deploy.yml`) đăng lên GitHub Pages mỗi lần push `main`.
- `site/privacy/` và `site/security/` là đường dẫn đã khai báo với App Store; giữ nguyên địa chỉ.
- Bản cài Android nằm ở mục [Releases](https://github.com/duconmang-io/NasHubs/releases). Khi phát hành bản mới, sửa đường dẫn tải và SHA-256 trong `site/index.html`.

Xem thử trên máy: `cd site && python -m http.server 8000`.
