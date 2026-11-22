# n4n-tools — Offline Web Tools

<p align="center">
  <img src="assets/icon-192.png" alt="آیکون n4n-tools" width="96" height="96" />
</p>

<p align="center">
  <strong>تبدیل WebP · کراپ تصویر · تولید پسورد</strong><br />
  کاملاً آفلاین در مرورگر — بدون سرور، بدون آپلود، بدون وابستگی خارجی
</p>

<p align="center">
  <img src="https://img.shields.io/badge/offline-100%25-3d9a78" alt="offline" />
  <img src="https://img.shields.io/badge/license-MIT-blue" alt="license" />
  <img src="https://img.shields.io/badge/HTML%2FCSS%2FJS-vanilla-8b9aab" alt="stack" />
</p>

---

## درباره پروژه

یک صفحهٔ HTML خالص برای کارهای روزمره روی تصویر و پسورد. همهٔ پردازش‌ها داخل مرورگر انجام می‌شود و فایل‌ها از دستگاه خارج نمی‌شوند.

| ابزار | قابلیت‌ها |
| --- | --- |
| **تبدیل به WebP** | تک‌فایل با پیش‌نمایش، چندفایل بدون پیش‌نمایش، کیفیت قابل تنظیم، تغییر ابعاد، دانلود تکی/گروهی |
| **کراپ تصویر** | انتخاب ابعاد خروجی، قفل نسبت، جابجایی کادر، ذخیره |
| **تولید پسورد** | طول و تعداد دلخواه، حروف/عدد/نماد، حذف مبهم‌ها، سنجش قدرت |

## اسکرین‌شات‌ها

### تبدیل WebP — تک‌فایل
![تبدیل WebP تک‌فایل](docs/screenshot-webp.png)

### تبدیل WebP — چندفایل
![تبدیل WebP چندفایل](docs/screenshot-batch.png)

### کراپ تصویر
![کراپ تصویر](docs/screenshot-crop.png)

### تولید پسورد
![تولید پسورد](docs/screenshot-password.png)

## اجرا

نیازی به نصب پکیج نیست. یکی از این‌ها کافی است:

```bash
# باز کردن مستقیم
open index.html

# یا سرو محلی
python3 -m http.server 8080
# سپس http://127.0.0.1:8080
```

## ساختار

```text
.
├── index.html              # نقطه ورود (GitHub Pages)
├── manifest.webmanifest    # PWA سبک
├── LICENSE
├── README.md
├── assets/
│   ├── favicon.svg
│   ├── favicon-32.png
│   ├── apple-touch-icon.png
│   ├── icon-192.png
│   ├── icon-512.png
│   └── og-cover.png
└── docs/
    ├── screenshot-webp.png
    ├── screenshot-batch.png
    ├── screenshot-crop.png
    └── screenshot-password.png
```

## حریم خصوصی

- هیچ درخواستی به سرور ارسال نمی‌شود
- تصویر و پسورد فقط در حافظهٔ مرورگر پردازش می‌شوند
- مناسب برای استفادهٔ محلی و آفلاین

## مجوز

[MIT](LICENSE)
