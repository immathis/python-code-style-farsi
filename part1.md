<h1>
code style
</h1>
<p>
<div dir="rtl"> اگر شما از برنامه نویسان پایتون بپرسید که بیشتر چه چیزی را در پایتون دوست دارند اغلب آنها خواهند گفت آسانی خوانده شدن کد ها ؛ در حقیقت  این قابلیت در پی شناسایی این نکته که اغلب  کد بسیار بیشتر از نوشتن؛ خوانده می شود , در قلب طراحی پایتون قرار دارد.
یکی از دلایل خوانایی بالای کدهای پایتون مجموعه کاملی از دستورالعمل Style Code و اصطلاحات Pythonic است.

هنگامی که یک توسعه دهنده کهنه کار پایتون (Pythonista) بخشی از کد را «Pythonic» نمی نامد، معمولا این بدان معنی است که این خطوط کد از دستورالعمل های معمول پیروی نمی کنند و نتوانستند قصد خود را در انچه مطرح شده به بهترین شکل بیان کنند.

در برخی از موارد ، بهترین راه در مورد چگونگی بیان قصد در کد پایتون توافق نشده است، اما این موارد نادر هستند.

مفاهیم عمومی :

کد های واضح(explicit)
در حالی که هر نوع جادوی سیاهی با Python امکان پذیر است، روش صریح تر و سر راست تر ترجیح داده می شود.
</div>
</p>

Bad:
<pre>
<code>
def make_complex(*args):
    x,y = args
    return dict(**locals())

</code>
</pre>

Good:
<pre>
<code>
def make_complex(x, y):
    return {'x': x, 'y': y}


</code>
</pre>

<p>
<div dir="rtl">

</div>
</p>
