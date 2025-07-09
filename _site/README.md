# MoneyBay Landing Page

Landing page cho ứng dụng MoneyBay - Quản lý chi tiêu cá nhân thông minh.

## Cấu trúc thư mục

```
moneybay.github.io/
├── _config.yml           # Cấu hình Jekyll
├── index.html            # Trang chủ
├── assets/              
│   ├── css/             # CSS files
│   │   └── style.scss   # File CSS chính
│   └── images/          # Hình ảnh
├── _site/               # Build output
└── Gemfile             # Ruby dependencies
```

## Yêu cầu

- Ruby >= 2.7.0
- Bundler
- Jekyll

## Cài đặt

1. Clone repository:
```bash
git clone https://github.com/qrbayapp/moneybay.github.io.git
cd moneybay.github.io
```

2. Cài đặt dependencies:
```bash
bundle install
```

3. Chạy server development:
```bash
bundle exec jekyll serve
```

4. Truy cập website tại http://localhost:4000/moneybay.github.io/

## Hình ảnh cần thiết

Thêm các hình ảnh sau vào thư mục `assets/images/`:

- apple-logo.png
- google-play.png
- banner_moneybay_1200x750.png
- banner_moneybay_800x600_01.png
- banner_moneybay_800x600_02.png
- banner_moneybay_800x600_03.png

## Tính năng

- [x] Responsive design
- [x] Dark mode
- [x] Đa ngôn ngữ (VI/EN)
- [x] Animation và hiệu ứng
- [x] Tối ưu SEO

## Deployment

Website được host trên GitHub Pages. Mọi thay đổi trên nhánh `main` sẽ tự động được deploy.

## Liên hệ

- Email: support@moneybay.app
- Website: https://qrbayapp.github.io/moneybay.github.io/ 