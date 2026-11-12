# فلش‌کارت — یادگیری هوشمند (PWA)

نسخهٔ نصب‌شوندهٔ برنامه با آیکون انتخابی شمارهٔ ۱ (کارت‌های روی‌هم).

## انتشار روی GitHub Pages

Workflow انتشار آماده است. فقط فعال‌سازی اولیهٔ Pages برای مخزن لازم است:

1. وارد [Settings → Pages](https://github.com/mhtabmjawry-web/FLASHCARD-MASTER-PREMIUM/settings/pages) شو.
2. در **Build and deployment → Source** گزینهٔ **GitHub Actions** را انتخاب و ذخیره کن.
3. سپس وارد [Actions → Deploy Flashcard PWA](https://github.com/mhtabmjawry-web/FLASHCARD-MASTER-PREMIUM/actions/workflows/deploy-pages.yml) شو؛ روی **Run workflow**، شاخهٔ `main` را انتخاب و اجرا کن.

پس از سبزشدن اجرای Deployment، آدرس اپ این خواهد بود:
`https://mhtabmjawry-web.github.io/FLASHCARD-MASTER-PREMIUM/`

از دفعات بعد، هر push به شاخهٔ `main` به‌صورت خودکار منتشر می‌شود.

## امکانات و نکات
- نصب مستقل روی Android و دسکتاپ، با Service Worker و پوستهٔ آفلاین
- ذخیرهٔ محلی دک‌ها و کارت‌ها با IndexedDB؛ همگام‌سازی خودکار بین دستگاه‌ها وجود ندارد
- مرور فاصله‌دار، جلسه‌های مطالعه، ایمپورت و خروجی پشتیبان JSON
- تم روشن و تاریک و آیکون برداری معمولی و maskable
- Manifest شامل آیکون‌های SVG با اندازه‌های اعلام‌شدهٔ ۱۹۲ و ۵۱۲ پیکسل
- برای نصب باید سایت با HTTPS باز شود؛ اجرای مستقیم با `file://` کافی نیست
- پیش از پاک‌کردن داده‌های مرورگر یا انتقال دستگاه، پشتیبان JSON بگیر
