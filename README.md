# django_challenge
با سلام

این پروژه یک چالش برای سنجیدن سطح تسلط شما در جنگو است.

# **توضیح دامنه‌ی پروژه**

در این پروژه هر کاربر می‌تواند تعدادی پست بنویسد، که هر کدام از این پست‌ها می‌تواند شامل چندین فرم باشند. این فرم‌ها به صورت داینامیک تولید می‌شوند. به صورتی در هنگام ساخت فرم، سوالات آن و فرمت جواب از کاربر پرسیده می‌شود.

همچنین هر کاربر می‌تواند پست‌ها را مشاهده کند و به هر فرمی که می‌خواهد، پاسخ بدهد.

ناشر پست، در هنگام ساخت فرم باید مشخص کند که هر چند ساعت یکبار می‌خواهد گزارشی از پاسخ‌های آن دریافت نماید. اما از آنجایی که هر کاربر می‌تواند چندین پست داشته باشد و هر پست می‌تواند چندین فرم داشته باشد، ممکن است تعداد پیامک‌های دریافتی برای هر کاربر  زیاد شود و باعث آزارش شود. به همین دلیل کاربر انتظار دارد پیامک‌ها به صورت جمع‌بندی‌شده (aggregated) برایش ارسال شود. به طور مثال یکی از متن‌های پیامک می‌تواند به صورت زیر باشد:

       سلام مهدیه‌ گرامی
       در سه ساعت گذشته، ۵ پاسخ برای فرم سایت یا اینستا؟، ۲ پاسخ برای فرم درخواست نمایندگی و یک پاسخ برای فرم سفارش کوله ثبت شده است.
       
       برای مشاهده‌ی پاسخ‌ها می‌توانید به آدرس زیر مراجعه کنید.
       test.ir/forms/