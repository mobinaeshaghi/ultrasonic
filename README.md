# ultrasonic
گزارش کار آزمایش سنسور آلتراسونیک با نمایش در سریال مانیتور

نام و نام خانوادگی:مبینا اسحاقی

نام استاد: اقای دکتر عباسی

آزمایش:آزمایش سنسور آلتراسونیک


هدف آزمایش:
هدف از این آزمایش، آشنایی با نحوه استفاده از سنسور آلتراسونیک برای اندازه‌گیری فاصله و نمایش مقدار اندازه‌گیری شده در سریال مانیتور محیط توسعه آردوینو (Arduino IDE) است.

وسایل مورد نیاز آزمایش:
برد آردوینو Uno (یا هر برد سازگار دیگر) - 1 عدد
سنسور آلتراسونیک HC-SR04 - 1 عدد
برد بورد (Breadboard) - 1 عدد
سیم‌های جامپر نر به نر (Jumper Wires) - به تعداد لازم برای اتصال قطعات
کابل USB برای اتصال آردوینو به کامپیوتر



شرح آزمایش :
در این آزمایش، سنسور آلتراسونیک به برد آردوینو متصل می‌شود. پایه VCC سنسور به ولتاژ 5 ولت آردوینو، پایه GND به زمین آردوینو، پایه Trig به یکی از پین‌های دیجیتال آردوینو (برای ارسال پالس فعال‌سازی) و پایه Echo به پین دیجیتال دیگری (برای دریافت پالس بازگشتی) متصل می‌گردند. با نوشتن و آپلود کد در آردوینو، یک پالس کوتاه به پین Trig ارسال شده و سپس زمان لازم برای بازگشت موج صوتی که به مانع برخورد کرده و توسط سنسور دریافت شده است، اندازه‌گیری می‌شود. با استفاده از این زمان و سرعت صوت، فاصله تا مانع محاسبه شده و از طریق ارتباط سریال بر روی سریال مانیتور در محیط آردوینو IDE نمایش داده می‌شود.
