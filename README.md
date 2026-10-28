# ماهک | دستیار چرخه تو

نسخه ۱.۰۱ — رابط فارسی و راست‌چین، تقویم شمسی، حالت تاریک و نصب‌پذیری PWA.

## انتشار روی GitHub Pages
1. یک repository جدید در GitHub بساز (مثلاً `maahak-pwa`).
2. تمام محتویات این پوشه را در ریشه repository قرار بده: `index.html`، `manifest.webmanifest`، `service-worker.js` و پوشه `icons`.
3. از **Settings → Pages**، گزینه **Deploy from a branch** را انتخاب کن؛ Branch را روی `main` و Folder را روی `/(root)` بگذار و Save کن.
4. بعد از انتشار، GitHub Pages یک آدرس HTTPS می‌دهد. اگر repository به نام `username.github.io` باشد، سایت روی ریشه دامنه منتشر می‌شود؛ در غیر این صورت معمولاً آدرس به شکل `https://username.github.io/maahak-pwa/` است.
5. برای به‌روزرسانی، فایل‌ها را در GitHub جایگزین و commit کن.

## نصب برای دیگران
- **Android (Chrome):** لینک HTTPS را باز کنند، منوی مرورگر را بزنند و `Install app` یا `Add to Home screen` را انتخاب کنند.
- **iPhone/iPad (Safari):** لینک HTTPS را در Safari باز کنند، دکمه Share را بزنند و `Add to Home Screen` را انتخاب کنند.
- اپ از طریق وب منتشر می‌شود؛ برای این نسخه نیازی به انتشار در Google Play یا App Store نیست.

## دامنه شخصی
وقتی دامنه `www.sajaddarvishi.ir` را به هاست/GitHub Pages متصل کردی، آدرس نهایی را در تنظیمات دامنه و در صورت نیاز فایل `CNAME` قرار بده. اتصال DNS باید در پنل دامنه انجام شود.

## نکته مهم درباره تاریخ‌ها
نمایش تقویم و انتخاب تاریخ در رابط کاربری شمسی است؛ تاریخ‌ها برای ذخیره‌سازی داخلی به قالب استاندارد میلادی تبدیل می‌شوند تا محاسبه چرخه دقیق و پایدار بماند.
