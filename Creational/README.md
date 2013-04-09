<div dir="rtl">
# Creational Patterns

- [Abstract Factory](AbstractFactory): بدون مشخص کردن کلاس‌های کانکرت، واسطی برای ساخت خانواده‌ای از اشیاء وابسته یا مرتبط با یکدیگر فراهم می‌کند.

- [Builder](Builder): روند ساخت یک شیء پیچیده را از نمایش آن جدا می‌کند به طوری که یک روند ساخت مشترک می‌تواند برای ساخت انوع بازنمایی‌ها به کار گرفته شود.

- [Factory Method](FactoryMethod): واسطی برای ساخت اشیاء ایجاد می‌کند، اما به زیرکلاس‌ها اجازه می‌دهد که تصمیم بگیرند که چه کلاسی را نمونه‌سازی کنند. این الگو اجازه می‌دهد تا نمونه‌برداری کلاس، به زیرکلاس‌ها معوق شود.

- [Prototype](Prototype): انواع اشیائی که باید ساخته شوند را با استفاده از یک نمونهٔ اولیه، مشخص می‌کند و اشیاء جدید را با کپی کردن این نمونهٔ اولیه تولید می‌کند.

- [Singleton](Singleton): تضمین می‌کند که کلاس تنها یک نمونه داشته باشد و دسترسی سراسری برای آن فراهم می‌کند.


# فرق بین Abstract Factory و Factory Method چیست؟
الگوی Abstract Factory
- اجازهٔ تعریف خانواده‌ای از اشیاء را می‌دهد و پیاده‌سازی ساخت این اشیاء را از کارخواه مخفی می‌کند.
- متدهای Abstract Factory همانند متد فکتوری پیاده‌سازی می‌شود.

الگوی Factory Method
- اجازهٔ تعریف چگونگی ساخت یک نوع شیء را می‌دهد و پیاده‌سازی ساخت این شیء را از کارخواه مخفی می‌کند.
- الگوی طراحی Factory Method نسخهٔ ساده‌شده‌ای از Abstract Factoryی‌ست.