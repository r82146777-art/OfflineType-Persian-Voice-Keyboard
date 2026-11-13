# آفلاین تایپ (Offline Type)

کیبورد و موتور تشخیص گفتار فارسی کاملاً آفلاین برای اندروید.

مناسب برای نابینایان، کم‌بینایان و افراد بینا.

## ویژگی‌ها
- تشخیص گفتار فارسی و انگلیسی آفلاین با مدل‌های ONNX / Sherpa
- کیبورد فارسی با پیشنهاد کلمه
- پشتیبانی از Voice Interaction و RecognitionService
- نسخه عمومی امضا‌شده برای تست

## دانلود نسخه عمومی
- [APK نسخه ۴.۴ عمومی](https://drive.google.com/file/d/1hcPCaErOEBanQBTVzdbL07JLqBDFJ0Zf/view?usp=drivesdk)
- [سورس دیکامپایل‌شده (jadx + apktool)](https://drive.google.com/file/d/1miE1DPg0wc3OZBZ3axpAO0cFVAucTWlO/view?usp=drivesdk)
- [کلید امضای عمومی + رمز](https://drive.google.com/file/d/1WJohuZ-_hyUzSJPnPL0PyZ2s1W9L22Kc/view?usp=drivesdk)

## امضا
- keystore: OfflineType-v4.4-public.keystore
- alias: offlinetype
- store/key password: offlinetype2026

**توجه:** این امضا جدید است و با نسخه‌های قبلی سازگار نیست (نصب به‌روزرسانی مستقیم ممکن نیست). برای ادامه توسعه با امضای قبلی، کلید قبلی را نگه دارید.

## ساختار سورس
- `sources/`: کد جاوای دیکامپایل‌شده (برای خواندن منطق)
- `smali/`: کد Smali قابل بازسازی با apktool
- `resources/`: منابع، assets مدل‌های ASR، صداها

کد اصلی پروژه احتمالاً Kotlin بوده و دیکامپایل به جاوا شده. برای ویرایش عملی از smali یا بازسازی پروژه Gradle استفاده کنید.

## دسترسی‌پذیری
برنامه برای استفاده با TalkBack طراحی شده. در نسخه‌های بعدی بهبودهای بیشتری در contentDescription و فوکوس اعمال خواهد شد.

## مجوز
برای استفاده شخصی و تست. مدل‌های ASR ممکن است مجوزهای خاص خود را داشته باشند.
