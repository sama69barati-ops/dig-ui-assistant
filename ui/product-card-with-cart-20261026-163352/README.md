# Product Card with Cart

## Description
یک کارت محصول ساده و راست‌چین که تصویر، برچسب "جدید"، عنوان، قیمت با نمایشِ مقدار اصلی و تخفیف، و یک دکمهٔ "افزودن به سبد" با آیکون سبد خرید را نمایش می‌دهد. فایل خروجی یک کامپوننت تک‌فایل React/TSX است که از مؤلفه‌های واقعی Dig استفاده می‌کند.

## Components used (Dig)
- ProductCard, ProductCardMedia, ProductCardBadge, ProductCardBody, ProductCardTitle, ProductCardPrice, ProductCardFooter: برای ساختار استاندارد کارت محصول، تصویر، برچسب و فوتر با قیمت و دکمه. این مجموعه دقیقاً همان کامپوننتی است که دیگ برای کارت محصول ارائه می‌دهد.
- Button: برای دکمهٔ "افزودن به سبد"؛ از variant="flat" و fullWidth برای هم‌تراز بودن با دستورالعمل‌های طراحی استفاده شد.
- Badge: برای برچسب "جدید" داخل ProductCardBadge تا رنگ و اندازهٔ مناسب طبق توکن‌های دیگ استفاده شود.

## Icons used (Digche)
- shopping-cart (Linear): آیکون استاندارد سبد خرید برای دکمهٔ افزودن به سبد. (Linear style برای آیکون‌های عملکردی در رابط کاربری مناسب است.)

## Install
npx digdesign@latest add https://docs.digdesign.ir/r/product-card.json https://docs.digdesign.ir/r/button.json https://docs.digdesign.ir/r/badge.json

## Usage
- کپی کنید و فایل را در پروژهٔ خود (مثلاً src/components/ProductCardWithCart.tsx) قرار دهید.
- مسیر تصویر (/bag.jpg) را به مسیر واقعی محصول تغییر دهید یا یک تصویر از شبکه بارگذاری کنید.
- این کامپوننت را مستقیماً ایمپورت و در صفحات خود استفاده کنید:

import ProductCardWithCart from "@/components/ProductCardWithCart";

<ProductCardWithCart />
