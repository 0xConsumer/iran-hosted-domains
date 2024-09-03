# v2rayNG

شما می‌توانید کلاینت v2rayNG را برای اندروید از [اینجا](https://github.com/2dust/v2rayNG) دانلود کنید.

## مسیریابی :id=routing

> اطمینان حاصل کنید که آخرین نسخه v2rayNG را نصب کرده‌اید.

1. منو را باز کرده و به `Geo asset files` بروید.
2. از گوشه بالا سمت راست، بر روی آیکون `+` کلیک کرده و `Add URL` را انتخاب کنید.
3. آدرس زیر را اضافه کرده و از بالا `🗸` را فشار دهید.

<div dir="ltr">

-   **remarks**: `iran.dat`
-   **URL**: `https://github.com/bootmortis/iran-hosted-domains/releases/latest/download/iran.dat`

</div>

4. بر روی آیکون دانلود ابری در گوشه بالا سمت راست کلیک کرده و منتظر بمانید تا دانلود تمام شود.
5. به منو اصلی برگردید و به `settings` بروید.
6. به بخش `Custom rules` در `Settings` بروید.
7. قوانین زیر را در هر تب بنویسید و از گوشه بالا سمت راست `✓` را بزنید تا ذخیره شود:

<div dir="ltr">

-   **Proxy URL OR IP**: `ext:iran.dat:proxy`
-   **DIRECT URL OR IP**: `ext:iran.dat:all,geoip:ir`
-   **BLOCKED URL OR IP**: `ext:iran.dat:ads,geosite:category-ads-all`

</div>

8. به عقب بروید و مجدداً متصل شوید.
