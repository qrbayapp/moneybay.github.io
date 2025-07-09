# MoneyBay

MoneyBay là một website được xây dựng bằng Jekyll, một static site generator phổ biến.

## Yêu cầu hệ thống

- Ruby phiên bản 2.7.0 trở lên
- RubyGems
- GCC và Make

## Cài đặt

1. Clone repository này:
```bash
git clone <your-repository-url>
cd moneybay
```

2. Cài đặt dependencies:
```bash
bundle install
```

## Phát triển local

Để chạy website ở môi trường local:

```bash
bundle exec jekyll serve --livereload
```

Truy cập website tại:
- http://localhost:4000 hoặc
- http://localhost:4001 (nếu port 4000 đã được sử dụng)

Các tính năng:
- Auto-regeneration: Tự động rebuild khi có thay đổi
- LiveReload: Tự động refresh browser khi có thay đổi

## Cấu trúc thư mục

```
moneybay/
├── _config.yml      # Cấu hình Jekyll
├── _posts/         # Thư mục chứa bài viết
├── _site/          # Thư mục chứa website được build
├── Gemfile         # Ruby dependencies
└── index.md        # Trang chủ
```

## Thêm bài viết mới

1. Tạo file mới trong thư mục `_posts/` với định dạng tên: `YYYY-MM-DD-title.md`
2. Thêm YAML front matter vào đầu file:
```yaml
---
layout: post
title: "Tiêu đề bài viết"
date: YYYY-MM-DD HH:MM:SS +0700
categories: category-name
---
```

## Deploy

Để deploy lên GitHub Pages:

1. Cập nhật `_config.yml`:
```yaml
baseurl: "/TestGithubPages"  # Tên repository
url: "https://username.github.io"  # Domain GitHub Pages
```

2. Push code lên GitHub:
```bash
git add .
git commit -m "Update website"
git push origin main
```

## Công nghệ sử dụng

- [Jekyll](https://jekyllrb.com/) - Static site generator
- [Minima](https://github.com/jekyll/minima) - Theme mặc định
- [Jekyll Feed](https://github.com/jekyll/jekyll-feed) - Tạo RSS feed
- [Jekyll SEO Tag](https://github.com/jekyll/jekyll-seo-tag) - Tối ưu SEO 