# Product Card with Cart Icon

## Description
یک کارت محصول ساده و آمادهٔ استفاده در چیدمان RTL که تصویر، برچسبِ وضعیت، عنوان و قیمت را نمایش می‌دهد و یک دکمهٔ افزودن به سبد همراه آیکونِ سبد خرید دارد. این کامپوننت برای فهرست محصولات یا ویترین استفاده می‌شود و از مؤلفه‌های واقعی Dig بهره می‌برد.

## Components used (Dig)
- ProductCard، ProductCardMedia، ProductCardBadge، ProductCardBody، ProductCardTitle، ProductCardPrice، ProductCardFooter: کارتِ محصول استاندارد Dig برای نمایش تصویر، برچسب و قیمت؛ انتخاب اصلی برای سازگاری با گریدها و اندازه‌های دیگ.
- Button: برای دکمهٔ عملِ افزودن به سبد؛ از واریانتِ outline و fullWidth برای حالتِ فروشگاهی استفاده شد.
- Badge: برای نشان دادن وضعیتِ "جدید" روی تصویر؛ کامل با ProductCardBadge.

## Icons used (Digche)
- shopping-cart (Linear): آیکون سبد خرید (Shopping-cart) از مجموعهٔ Digche در سبک Linear — مناسبِ رابط‌های فروشگاهی و هماهنگ با وزن و مقیاس آیکون‌های Dig.

## Install
از دستورات نصب رسمی Dig برای افزودن این کامپوننت‌ها به پروژه استفاده کنید:

npx digdesign@latest add https://docs.digdesign.ir/r/product-card.json https://docs.digdesign.ir/r/badge.json https://docs.digdesign.ir/r/button.json

(اگر به Rating یا NumberField نیاز داشتید، بسته‌های مربوطه را نیز اضافه کنید.)

## Usage
- فایلِ تولیدی را در پروژهٔ خود (مثلاً components/ProductCardWithCart.tsx) قرار دهید و سپس از آن در صفحات یا لیست‌ها فراخوانی کنید:

import ProductCardWithCart from "@/components/ProductCardWithCart";

function Products() {
  return (
    <div>
      <ProductCardWithCart />
    </div>
  );
}

- تصویر نمونه در کد به `/bag.jpg` اشاره می‌کند؛ مسیر یا منبع تصویر را با داده‌های واقعی خود جایگزین کنید.

