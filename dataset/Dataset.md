# DATASETS

## نمای کلی

این پروژه، **Telecom Fraud Text Detection (CHIFRAUD)**، از چند دیتاست **چندزبانهٔ متنی** برای تشخیص اسپم و کلاهبرداری مخابراتی استفاده می‌کند و سه زبان **English، Arabic و Chinese** را پوشش می‌دهد. هدف اصلی، ایجاد شفافیت در منابع داده و فراهم‌کردن امکان **بازتولیدپذیری** آزمایش‌ها در چارچوب مدل‌های Transformer برای تشخیص کلاهبرداری است.

نکتهٔ مهم: تمامی دیتاست‌ها متعلق به منابع و ارائه‌دهندگان اصلی هستند. این مخزن **دیتاست خام را بازنشر نمی‌کند** و صرفاً لینک‌ها، ارجاع‌ها و راهنمای کلی دسترسی/پیش‌پردازش را برای استفادهٔ پژوهشی ارائه می‌دهد.

---

## دیتاست‌های استفاده‌شده

### A) English — SMS Spam Collection (Kaggle mirror)

**Name:** SMS Spam Collection
**Access link:**

[SMS Spam Collection (Kaggle)](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset?resource=download)

**Description:**
یک دیتاست استاندارد و پرکاربرد برای تشخیص اسپم پیامکی شامل **5,574 پیام SMS انگلیسی** با برچسب‌گذاری دودسته‌ای:

* `ham` (پیام‌های سالم/عادی)
* `spam` (پیام‌های اسپم/نامطلوب)

ساختار داده به‌صورت رایج شامل دو ستون اصلی است:

* `v1`: برچسب (`ham` / `spam`)
* `v2`: متن پیام

#### Original source & citation

* Original dataset page:

   [SMS Spam Collection (Original)](http://www.dt.fee.unicamp.br/~tiago/smsspamcollection/)

* Reference paper:
  Almeida, T. A., Gómez Hidalgo, J. M., & Yamakami, A. (2011). *Contributions to the Study of SMS Spam Filtering: New Collection and Results.* Proceedings of DOCENG 2011.

---

### B) Arabic — Arabic Spam Tweets Dataset (Mendeley)

**Name:** Arabic spam tweets dataset
**Access link:**

[Arabic spam tweets dataset (Mendeley)](https://data.mendeley.com/datasets/86x733xkb8/1)

**Description:**
این دیتاست با استفاده از **Twitter API** در بازهٔ زمانی **January 27, 2021 تا March 10, 2021** جمع‌آوری شده و شامل **13,241 توییت عربی** برای تشخیص اسپم است:

* **1,924 Spam**
* **11,299 Ham**

فرمت انتشار اولیه **XLSX** بوده است. در این پروژه، داده با استفاده از Python به **CSV** تبدیل شده تا برای پیش‌پردازش و مدل‌سازی در زنجیرهٔ NLP قابل استفاده باشد.

#### Citation

Kaddoura, S., Alex, S. A., Itani, M., Henno, S., AlNashash, A., & Hemanth, D. J. (2023). *Arabic spam tweets classification using deep learning.* Neural Computing and Applications.

---

### C) Chinese — CHIFRAUD Dataset

**Name:** CHIFRAUD dataset
**Dataset link:**

[CHIFRAUD Dataset (GitHub)](https://github.com/xuemingxxx/ChiFraud)

**Article link:**

[CHIFRAUD Article (ACL Anthology)](https://aclanthology.org/2025.coling-main.398/)

**Description:**
CHIFRAUD یک **long-term benchmark dataset** برای تشخیص کلاهبرداری مخابراتی/وب در زبان Chinese است که با هدف بازتاب سناریوهای واقع‌گرایانه و متنوع کلاهبرداری طراحی شده است و در این پروژه به‌عنوان بنچمارک اصلی زبان چینی استفاده می‌شود.

#### Citation

Tang, M., Zou, L., Liang, S.-N., Jin, Z., Wang, W., & Cui, S. (2025). *CHIFRAUD: A Long-term Web Text Dataset for Chinese Fraud Detection*. In *Proceedings of the 31st International Conference on Computational Linguistics (COLING 2025)*. ACL Anthology. [https://aclanthology.org/2025.coling-main.398/](https://aclanthology.org/2025.coling-main.398/)


---

## لایسنس و شرایط استفاده

هر دیتاست تابع شرایط استفاده و لایسنس منبع اصلی خود است. مسئولیت رعایت شرایط لایسنس، ارجاع‌دهی صحیح و استفادهٔ مطابق با مقررات، بر عهدهٔ کاربر است. این مخزن صرفاً راهنمای دسترسی و مستندسازی منابع را ارائه می‌دهد.

---

## How to cite

* Almeida, T. A., Gómez Hidalgo, J. M., & Yamakami, A. (2011). *Contributions to the Study of SMS Spam Filtering: New Collection and Results.* Proceedings of DOCENG 2011.
  Original dataset page: [http://www.dt.fee.unicamp.br/~tiago/smsspamcollection/](http://www.dt.fee.unicamp.br/~tiago/smsspamcollection/)

* Kaddoura, S., Alex, S. A., Itani, M., Henno, S., AlNashash, A., & Hemanth, D. J. (2023). *Arabic spam tweets classification using deep learning.* Neural Computing and Applications.
  Dataset page: [https://data.mendeley.com/datasets/86x733xkb8/1](https://data.mendeley.com/datasets/86x733xkb8/1)

* Tang, M., Zou, L., Liang, S.-N., Jin, Z., Wang, W., & Cui, S. (2025). *CHIFRAUD: A Long-term Web Text Dataset for Chinese Fraud Detection*. In *Proceedings of the 31st International Conference on Computational Linguistics (COLING 2025)*. ACL Anthology. [https://aclanthology.org/2025.coling-main.398/](https://aclanthology.org/2025.coling-main.398/)
