<div dir="rtl">
    <h1>امضاهای دیجیتال (امضا و راستی‌آزمایی)</h1>
    <p><span style="color: #999999;">
            اثبات این که امضا و کلید عمومی با یک کلید خصوصی یکسان تولید شدن.
        </span></p>
    <h2>فهرست</h2>
    <hr>
    <ul>
        <li>
            <p><a href="#1">امضا کردن</a>
            <ul>
                <li>
                    <p><a href="#1-1">۱- جزء تصادفی</a></p>
                </li>
                <li>
                    <p><a href="#1-2">۲- جزء مربوط به امضا</a></p>
                </li>
            </ul>
            </p>
        </li>
        <li>
            <p><a href="#2">راستی‌آزمایی</a>
            <ul>
                <li>
                    <p><a href="#2-1">نقطه‌ی ۱</a></p>
                </li>
                <li>
                    <p><a href="#2-2">نقطه‌ی ۲</a></p>
                </li>
            </ul>
            </p>
        </li>
    </ul>
    <hr>
    <hr>
    <h2 id="1">امضا کردن</h2>
    <p>یه امضای دیجیتال دو جزء داره: </p>
    <p>۱- جزء تصادفی</p>
    <p>۲- جزء مربوط به امضا (کلید خصوصی+داده‌ی تراکنشی که داریم امضای دیجیتالی رو براش ایجاد می‌کنیم.)</p>
    <br>
    <h3 id="1-1">۱- جزء تصادفی</h3>
    <p>با تولید یه عدد تصادفی شروع می‌کنیم؛ و بعد، این عدد رو با نقطه‌ی تولیدکننده‌ی خم بیضوی (نقطه‌ای که برای تولید<a
            href="Public%20Keys.md"> کلید عمومی</a> هم
        استفاده می‌شه) ضرب می‌کنیم.
    </p>
    <img style="display: block; margin-left: auto; margin-right: auto;"
        src="https://learnmeabitcoin.com/beginners/images/digital_signatures_signing_verifying/png/01-signing-random-point.png">
    <br>
    <br>
    <p>جز تصادفی امضای دیجیتال، نقطه‌ای روی خم بیضویه که نتیجه‌ی نهایی رو می‌ده. اما ما فقط مختصات xش رو در نظر می‌گیرم:
    </p>
    <br>
    <br>
    <img style="display: block; margin-left: auto; margin-right: auto;"
        src="https://learnmeabitcoin.com/beginners/images/digital_signatures_signing_verifying/png/01-signing-random-point-x.png">
    <br>
    <br>
    <p>به اختصار بهش می‌گیم «r». </p>
    <br>
    <br>
    <img style="display: block; margin-left: auto; margin-right: auto;"
        src="https://learnmeabitcoin.com/beginners/images/digital_signatures_signing_verifying/png/01-signing-random-r.png">
    <br>
    <br>
    <p><strong>عملا این کار شبیه تولید یه کلید خصوصی و یه کلید عمومیه. با این تفاوت که این‌جا داریم این کار رو می‌کنیم
            که به امضای
            دیجیتال‌مون یه بخش تصادفی اضافه کرده باشیم.
        </strong></p>
    <p>پس حالا نصف امضای دیجیتال‌مون آماده‌ست؛ اما کلید خصوصی‌مون رو تا اینجا برای هیچ کاری استفاده نکردیم. اینجاست که
        می‌رسیم به نیمه‌ی دوم...</p>
    <br>
    <h3 id="1-2">۲- جزء مربوط به امضا</h3>
    <p>اول، کلید خصوصی‌مون رو برمی‌داریم و در r (مختصات x از نقطه‌ی تصادفیِ روی خم، که تازه پیدا کردیم) ضرب می‌کنیم.
    </p>
    <br>
    <br>
    <img style="display: block; margin-left: auto; margin-right: auto;"
        src="https://learnmeabitcoin.com/beginners/images/digital_signatures_signing_verifying/png/01-signing-signature-r-privkey.png">
    <br>
    <br>
    <p>مرحله‌ی بعد، چیزی رو که قراره امضا کنیم رو هم بهش اضافه می‌کنیم. به این چیز «پیام» گفته می‌شه. در بیت‌کوین،
        پیام، هش کل داده‌ی تراکنشه که خروجی‌ای که می‌خوایم باز کنیم رو در خودش جا می‌ده.
    </p>
    <br>
    <br>
    <img style="display: block; margin-left: auto; margin-right: auto;"
        src="https://learnmeabitcoin.com/beginners/images/digital_signatures_signing_verifying/png/01-signing-signature-r-privkey-thing.png">
    <p style="color: #999999; text-align: center;"> افزودن هش تراکنش، باعث می‌شه که امضا به یه تراکنش وصل بشه (و قابل
        استفاده برای تراکنش دیگه‌ای نباشه.)</p>
    <br>
    <br>
    <p>در نهایت، به عنوان یه حرکت مفید، همه‌ی این‌ها رو به عدد تصادفی اولیه‌مون تقسیم می‌کنیم:</p>
    <br>
    <br>
    <img style="display: block; margin-left: auto; margin-right: auto;"
        src="https://learnmeabitcoin.com/beginners/images/digital_signatures_signing_verifying/png/01-signing-signature-r-privkey-thing-randnum.png">
    <br>
    <br>
    <p>و… هجی مجی لاترجی! جزء حیاتی «امضا» از امضای دیجیتال‌مون آماده‌ست. به اختصار به این بخش می‌گیم «s». </p>
    <br>
    <br>
    <img style="display: block; margin-left: auto; margin-right: auto;"
        src="https://learnmeabitcoin.com/beginners/images/digital_signatures_signing_verifying/png/01-signing-signature-rs.png">
    <p style="color: #999999; text-align: center;">Mr. D Signature.</p>
    <br>
    <hr>
    <p>و حالا بخش جالب ماجرا … </p>
    <p>
        اگه کسی از ما بخواد که اثبات کنیم کلید خصوصی مربوط به یه کلید عمومی رو می‌دونیم، می‌تونیم امضای دیجیتال‌مون
        (r و s)‌ رو ارائه کنیم.
    </p>
    <p>
        اما چطوری یه نفر می‌تونه از این اطلاعات به عنوان اثبات استفاده کنه؟
    </p>
    <br>
    <h2 id="2">راستی‌آزمایی </h2>
    <blockquote>
        <p>در بیت‌کوین، کل این امضا به قسمتی از تراکنش می‌ره که بهش می‌گیم «اسکریپت باز کننده». کلید
            خصوصی‌ای که از اون برای تولید امضا استفاده کردیم همون کلیدیه که به آدرسی که خروجی‌ها بهش قفل شدن
            گره خورده. </p>
        <br>
        <br>
        <img style="display: block; margin-left: auto; margin-right: auto;"
            src="https://learnmeabitcoin.com/beginners/images/digital_signatures_signing_verifying/png/02-verifying-goal.png">
        <br>
    </blockquote>
    <br>
    <p>
        هدف‌مون راستی‌آزمایی این مساله‌ست که آیا امضای دیجیتال از کلید خصوصی درست ایجاد شده یا نه.
        برای راستی‌آزمایی این‌که آیا کلید خصوصی درستی برای تولید امضای دیجیتال استفاده شده یا نه، کسی که این امضای
        دیجیتال رو بررسی
        می‌کنه باید از هر دو جزء استفاده کنه تا دو نقطه‌ی جدید روی خم بیضوی پیدا بشه.
    </p>
    <br>
    <h3 id="2-1">نقطه‌ی ۱</h3>
    <p>پیام رو به s‌ تقسیم می‌کنیم. اولین نقطه، نقطه‌ی تولیدکننده است که در این مقدار ضرب شده: </p>
    <br><br>
    <img style="display: block; margin-left: auto; margin-right: auto;"
        src="https://learnmeabitcoin.com/beginners/images/digital_signatures_signing_verifying/png/02-verifying-point1.png">
    <br><br>
    <h3 id="2-2">نقطه‌ی ۲</h3>
    <p>r رو به s تقسیم می‌کنیم. </p>
    <p>دومین نقطه کلید عمومیه که در این مقدار ضرب شده:</p>
    <br>
    <br>
    <img style="display: block; margin-left: auto; margin-right: auto;"
        src="https://learnmeabitcoin.com/beginners/images/digital_signatures_signing_verifying/png/02-verifying-point2.png">
    <br><br>
    <h3>و در آخر … </h3>
    <p>اگه این دو تا نقطه رو با هم جمع کنیم، یه نقطه‌ی سومی روی خم به دست میاریم: </p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;"
        src="https://learnmeabitcoin.com/beginners/images/digital_signatures_signing_verifying/png/02-verifying-add.png"><br><br>
    <p>و اگه مختصات x از این نقطه‌ی سوم با مختصات x‌ نقطه‌ی تصادفی که باهاش شروع کردیم (یعنی r) یکسان باشه، پس اثبات
        می‌شه
        که امضای دیجیتال با استفاده از کلید خصوصی مربوط به این کلید عمومی تولید شده.
    </p>
    <br><br>
    <img style="display: block; margin-left: auto; margin-right: auto;"
        src="https://learnmeabitcoin.com/beginners/images/digital_signatures_signing_verifying/png/02-verifying-final.png"/>
    <br><br>
    <br>
    <p><a href="https://learnmeabitcoin.com/beginners/digital_signatures_signing_verifying">منبع</a></p>
    <p>شاد زی..</p>
    <p>اینم آخرین قسمت./</p>
</div>
