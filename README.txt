# موقع كرسي الألكسو + لوحة إدارة Decap CMS (نسخة محسّنة)

## خطوات النشر السريع (Netlify + GitHub)
1) ارفع هذا المجلد إلى مستودع GitHub جديد.
2) على Netlify: انشئ موقعًا من Git (New site from Git).
3) فعّل Identity + Git Gateway من إعدادات Netlify.
4) افتح `/admin/` على موقعك وسجّل الدخول وابدأ التحرير.

## ما الجديد هنا؟
- تمييز تلقائي للرابط النشط في شريط التنقل العلوي والشريط الجانبي.
- تمرير سلس (smooth scrolling).
- نموذج تواصل مفعّل لـ Netlify Forms (الرسائل ستظهر في تبويب Forms).
- إجراء GitHub Action يولّد تلقائيًا `content/news/index.json` عند كل دفع (push).

## التحرير من لوحة الإدارة
- الصفحة الرئيسية: الواجهة الرئيسية → `content/home.json`.
- عن الكرسي: عن الكرسي → `content/about.md`.
- الرؤية/البرامج: حقول نصية في JSON.
- الأخبار: أنشئ خبرًا جديدًا؛ الـAction سيحدّث الفهرس تلقائيًا.
- الموارد: بطاقات من `content/resources/index.json`.
- المكتبة: تحميلات من `content/library.json`.

> ضع شعارك في `assets/uploads/logo.png` ليظهر في الهيدر.
