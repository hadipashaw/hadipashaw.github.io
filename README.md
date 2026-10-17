<div dir="rtl">

# هادی پاشایی | Hadi Pashaei — پورتفولیو شخصی

سایت شخصی من: [hadipashaw.github.io](https://hadipashaw.github.io)

یه صفحه‌ی تک‌فایلی (single-page) برای معرفی خودم، مهارت‌ها، پروژه‌ها و مسیری که تا الان طی کردم — دانشجوی مهندسی برق، علاقه‌مند به رباتیک، اتوماسیون صنعتی (PLC) و امنیت سایبری.

---

## ساختار پروژه

```
hadipashaw.github.io/
├── index.html          # کل سایت (HTML + CSS + JS در یک فایل)
└── images/              # عکس‌های پروژه‌ها
    ├── emo-robot.jpg
    ├── plc-industrial.jpg
    ├── cybersecurity.jpg
    ├── oled-emotion.jpg
    ├── python-tools.jpg
    └── embedded-systems.jpg
```

هیچ فریم‌ورک یا بیلدی لازم نیست — کل سایت یک فایل `index.html` خالصه (vanilla HTML/CSS/JS) و مستقیم روی GitHub Pages سرو می‌شه.

---

## بخش‌های سایت

- **خانه** — معرفی کوتاه + تگ‌های حوزه کاری
- **درباره** — کارت هویت و متن معرفی
- **مهارت‌ها** — مهارت‌های فنی با برچسب سطح (نه درصد ساختگی) + زبان‌ها و ابزارها
- **پروژه‌ها** — کارت هر پروژه با تصویر، تگ‌های فناوری و توضیح
- **مسیر** — تایم‌لاین مراحل یادگیری تا امروز
- **تماس** — لینک مستقیم به تلگرام

### ویجت‌های تعاملی
- **چشم‌های EMO** (کنار لوگو در نوار بالا) — با موس/لمس دنبالت می‌کنن؛ اشاره‌ای به پروژه‌ی ربات EMO خودم
- **اسیلوسکوپ زنده** (در صفحه‌ی خانه) — موج sine/square که با حرکت موس فرکانس و دامنه‌ش عوض می‌شه

---

## تکنولوژی

- HTML5 / CSS3 (بدون فریم‌ورک)
- JavaScript خالص (Vanilla JS) — بدون کتابخانه خارجی
- فونت [Vazirmatn](https://github.com/rastikerdar/vazirmatn) برای فارسی
- Canvas API برای پس‌زمینه‌ی مداری و اسیلوسکوپ
- `prefers-reduced-motion` و `focus-visible` برای دسترس‌پذیری

---

## راه‌اندازی محلی

نیازی به نصب یا بیلد نیست. کافیه فایل `index.html` رو مستقیم تو مرورگر باز کنی، یا با یه سرور ساده:

```bash
python3 -m http.server 8000
```

بعد برو به `http://localhost:8000`

---

## افزودن عکس پروژه‌ها

عکس هر پروژه رو با همین اسم‌ها داخل پوشه‌ی `images/` بذار (نسبت تصویر ۱۶:۹، حداقل ۸۰۰×۴۵۰، حجم زیر ۳۰۰ کیلوبایت):

| پروژه | فایل |
|---|---|
| ربات EMO | `images/emo-robot.jpg` |
| پروژه‌های PLC صنعتی | `images/plc-industrial.jpg` |
| پروژه‌های امنیت سایبری | `images/cybersecurity.jpg` |
| OLED Emotion System | `images/oled-emotion.jpg` یا `.gif` |
| ابزارهای Python | `images/python-tools.jpg` |
| Embedded Control Systems | `images/embedded-systems.jpg` |

---

## کارهای باقی‌مانده (To-Do)

- [ ] جایگزینی عکس واقعی پروژه‌ها در `images/`
- [ ] تکمیل جزئیات فنی هر پروژه (مشکل، راه‌حل، چالش، نتیجه)
- [ ] افزودن `og:image` و `favicon`

---

## دسترسی

- GitHub: [@hadipashaw](https://github.com/hadipashaw)
- Telegram: [@Hadipashaw](https://t.me/Hadipashaw)
- Instagram: [@hadipashaw](https://www.instagram.com/hadipashaw)

</div>

---

<div dir="ltr">

## English

A single-page personal portfolio for Hadi Pashaei — electrical engineering student, hardware/robotics hobbyist, with hands-on experience in PLC programming (Ladder, FBD, STL), Arduino, Python, and cybersecurity/Linux.

**Stack:** plain HTML/CSS/JS, no build step, no frameworks — deployed directly via GitHub Pages.

**Run locally:**
```bash
python3 -m http.server 8000
```

See the Persian section above for the full file structure, image-folder naming convention, and remaining to-dos.

</div>