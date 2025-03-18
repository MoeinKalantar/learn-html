# learn-html

### basic tag

| Syntax      | Description |
| ----------- | ----------- |
| `<!DOCTYPE>`      | نوع سند رو مشخص می کند       |
| `<html></html>`  | <span lang="fa" dir="rtl">سند html را می سازد</span>       |
| `<head></head>`      |   اطلاعات درباره سندداخل این تگ قرار میگیرد      |
| `<meta/>`   | اطلاعات درباره ی سند        |
| `<title></title>`      | عنوان سند در صفحه وب       |
| `<body></body>`   | تمام ان چیزی که در صفحه وب میبینم داخل این تگ قرار میگیرد        |

### text tag

| Syntax      | Description |
| ----------- | ----------- |
| `<h1></h1>`      | عنوان رو مشخص می کند       |
| `<p></p>`  | یک پاراگراف ایجاد می کند        |
| `<pre></pre>`      | یک پاراگراف فرمت شده ایجاد میکند       |
| `<b></b>`   | متن رو بلد میکند        |
| `<strong></strong>`      | <span lang="fa" dir="rtl">یک متن یا کلمه مهم را بلد می کند که در seo کاربرد دارد</span>       |
| `<i></i>`   | یک کلمه یا متن رو ایتالیک می کند        |
| `<em></em>`      | به یک کلمه یا متن تأکید میکند وان را ایتالیک میکند      |
| `<del></del>`   | یک خط افقی رو یک کلمه یا متن می اندازد        |
| `<br/>`      | یک خط جدید ایجاد میکند       |
| `<hr/>`   | یک خط افقی به اندازه صفحه عرض صفحه ایجاد میکند        |

### links

| Syntax      | Description |
| ----------- | ----------- |
| `<a href="URL">clickable text</a>`      | ایجاد یک لینک       |
| `<a href="URL" download>clickable text</a>`   | ایجاد یک لینک با قابلیت دانلود        |
| `<a href="mailto:EMAIL_ADDRESS">clickable text</a>`      | ایجاد لینک برای منتقل شدن یه ایمیل       |
| `<a href="tel:Phone_Number">clickable text</a>`   | ایجاد یک لینک برای تماس        |

### images elements

| Syntax      | Description |
| ----------- | ----------- |
| `<img src="URL" alt="Text instead of photo">`      | ایجاد یک عکس       |
| `<picture><source></source></picture>`   | ایجاد عکس برای مباحث مربوط به ریسپانسیو        |

### favicon

| Syntax      | Description |
| ----------- | ----------- |
| `<link rel="icon" type="image/png or ..." href="">`      | یک ایکون کنار عنوان صفحه وب اضافه می      |

### tables

| Syntax      | Description |
| ----------- | ----------- |
| `<table> </table>`      | ایجاد جدول       |
| `<thead></thead>`   | قسمت مربوط به عنوان های جدول        |
| `<tbody></tbody>`      | قسمت مربوط به مقادیر جدول       |
| `<tr></tr>`   | ایجاد ردیف در جدول        |
| `<th></th>`      | ایجاد مقادیر عنوان        |
| `<td></td>`   | ایجاد مقادیر جدول        |

###  lists

| Syntax      | Description |
| ----------- | ----------- |
| `<ul> </ul>`      | ایجاد لیست نامرتب       |
| `<ol start="" type=""> </ol>`   | ایجاد لیست مرتب        |
| `<li> </li>`   | ایجاد مقدار برای لیست        |

### div & span & semantic tags

| Syntax      | Description |
| ----------- | ----------- |
| `<div></div>`      | <span lang="fa" dir="rtl">یک تگ block برای قالب بندی و استایل دهی سایت</span>       |
| `<span></span>`   | <span lang="fa" dir="rtl">یک تگ inline برای استایل دهی یک کلمه یا یک قسمت </span>        |
| `<header></header>`      | تگ معنادار مربوط به قسمت هدر سایت       |
| `<nav></nav>`   | تگ معنا دار مربوط به نوبار سایت        |
| `<main></main>`      | تگ معناداری که یک بار ازش استفاده میشه برای قسمت بدنه سایت       |
| `<section></section>`   | تگ معنادار برای بخش بندی        |
| `<aside></aside>`      | تگ معنادار برای قسمت های مربوط به سایدبار       |
| `<article></article>`   | تگ معنادار برای قسمت های مربوط به مقالات        |
| `<footer></footer>`      | تگ معنا دار برای قسمت پاورقی سایت       |

### form elements

| Syntax      | Description |
| ----------- | ----------- |
| `<form></form>`      | ایجاد فرم       |
| `<fieldeset></fieldeset>`   | ایجاد یک فیلد برای فرم        |
| `<legend></legend>`      | نام فیلد       |
| `<lable></lable>`   | ایجاد نام برای اینپوت ها        |
| `<input type="text"></input>`      | یک ورودی از نوع متن ایجاد میکند       |
| `<input type="radio"></input>`   | <span lang="fa" dir="rtl">ایجاد radio button</span>        |
| `<input type="checkbox"></input>`      | <span lang="fa" dir="rtl">ایجاد checkbox با قابلیت انتخاب چند گزینه</span>       |
| `<input type="submit">`   | ایجاد دکمه ارسال برای فرم        |
| `<select></select>`      | ایجاد یک منو کشویی       |
| `<option>`   | <span lang="fa" dir="rtl">ایجاد ایتم برای select و datalist</span>        |
| `<textarea></textarea>`      | <span lang="fa" dir="rtl">ایجاد text box</span>       |
| `<datalist></datalist>`   | ایجاد یک دیتا لیست برای متصل کردن ان به یک ورودی با قابلیت سرچ        |

### input types

| Syntax      | Description |
| ----------- | ----------- |
| `<input type="email">`      | ایجاد ورودی از نوع ایمیل       |
| `<input type="number">`   | ایجاد ورودی از نوع عددی        |
| `<input type="password">`      | ایجاد وروردی از نوع رمز       |
| `<input type="range">`   | Text        |
| `<input type="date/month/week/time">`      | ایجاد ورودی ار نوع تاریخ و...      |
| `<input type="color">`   | ایجاد ورودی با انتخاب رنگ       |

### form attributies

| Syntax      | Description |
| ----------- | ----------- |
| `action="#"`      | مسیر ارسال فرم       |
| `method="get/post"`   | روش ارسال فرم        |
| `target="_blank"`      | ارسال فرم در تب جدید      |
| `autocomplete="on/off"`   |  تکمیل خودکار فرم       |

### input attributies

| Syntax      | Description |
| ----------- | ----------- |
| `type=""`      | نوع ورودی را مشخص میکند       |
| `name=""`   | نام متغییری که مقدار را دریافت میکند        |
| `id=""`      |  id      |
| `value=""`   | مقدار        |
| `required`      | پر بودن ورودی موردنیاز است       |
| `readonly`   | فقط قابلیت خواندن دارد و نمی شود تغییری ایجاد کرد        |
| `placeholder`      | یک متن کم رنگ شده داخل ورودی برای راهنمایی کاربر       |
| `disabled`   | غیرفعال شدن یک ورودی        |
| `maxlength=""`      | حداکثر طول یک ورودی       |
| `minlength=""`   | حداقل طول یک ورودی        |
| `multiple`      | انتخاب چند مورد       |
| `autofocus`   | <span lang="fa" dir="rtl">هنگام لود صفحه ورودی که autofocus دارد انتخاب می شود</span>        |
| `min="" max=""`      | یک محدوده رو میتوان مشخص کرد       |

### iframe - video & audio

| Syntax      | Description |
| ----------- | ----------- |
| `<iframe src=""></iframe>`      | اضافه کردن یک وبسایت        |
| `<video src="" controls></video>`   | video        |
| `<audio src="" controls></audio>`      | audio       |