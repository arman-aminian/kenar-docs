# لیست ارائه‌دهندگان خدمات

از صفحه مدیریت آگهی یا احتمالا صفحات دیگری از دیوار میتوان به لیستی از ارائه دهندگان خدمات دست یافت. لینک مربوط به درخواست خدمت از اپلیکیشن شما را خود شما از طریق تماس با رابط پلتفرم دیوار در اختیار ما قرار داده اید.

> این لینک میتواند شامل کوئری پارامز مثلا utm باشد.

برای سهولت کار شما، ما اطلاعات قابل انتشار آگهی را به شکل کوئری پارامز در کنار پارامترهایی که خودتان قرار داده‌اید قرار داده‌ایم. در اینجا چند نمونه از این اطلاعات را براش شما تشریح میکنیم.

```text
https://example.com/service_path/?
    app_slug=example_app&
    body_chassis_status.back_chassis_status=healthy&
    body_chassis_status.body_status=some-scratches&
    body_chassis_status.front_chassis_status=healthy&
    body_status=some-scratches&
    brand_model=Pride+131+SE&
    category=light&
    chassis_status=both-healthy&
    color=%D8%B3%D9%81%DB%8C%D8%AF&
    fuel_type=benzine&
    gearbox=manual&
    motor_status=healthy&
    new_price=203000000.000000&
    post_token=QZk4AH_B&
    prefilled_title=%D9%BE%D8%B1%D8%A7%DB%8C%D8%AF+131+SE%D8%8C+%D9%85%D8%AF%D9%84+%DB%B1%DB%B3%DB%B9%DB%B2&
    price.mode=%D9%85%D9%82%D8%B7%D9%88%D8%B9&
    price.value=203000000.000000&
    third_party_insurance_deadline=11&
    usage=256000.000000&
    utm_campaign=inspection_26aug&
    utm_medium=admanagement&
    utm_source=divar&
    year=%DB%B1%DB%B3%DB%B9%DB%B2
```

در اینجا مقدار پارامتر زیر را پلتفرم باز دیوار تنظیم میکند:
- app_slug
- post_token

برخی مقادیر توسط خود اپلیکیشن در این لینک قرار داده شده:
- utm_campaign
- utm_medium
- utm_source

باقی پرامترها از روی اطلاعات آگهی برای شما تنظیم شده اند:
- price.value
- usage
- ...

> از این پارامترها میتوانید برای prefill کردن فرمهای خود استفاده کنید. از کار را برای جلوگیری از نیاز شما به دریافت آگهی انجام داده‌ایم.

> فرم شما باید نسبت به کوئری پارامز اضافه‌تر یا کمتر مقاوم باشد. همچنین ممکن از تایپ ولیو یک پارامتر تغییر کند. برای مثال برنامه داریم مقادیر فلوت نمونه بالا را اینتیجر کنیم.

> این مثال ارائه شده برای یک نمونه آگهی در دسته‌بندی خودرو است. هر دسته‌بندی دارای مقادیر مختص خود است که میتوانید با آزمون و خطا به آنها دست پیدا کنید

برخی از این پارامتر‌ها دارای فضای حالت بزرگی هستند یا نیازمند برگردان فارسی برای تجربه کاربری بهتر هستند. برای اطلاع از این مقادیر، به
 [قسمت است](../assets/ReadMe.md)
 .در این سند مراجعه نمائید