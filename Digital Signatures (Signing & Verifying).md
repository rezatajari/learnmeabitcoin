<div dir="rtl">
    <br>
    <h2>لیست محتویات</h2>
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
            <p><a href="#2">تایید کردن</a>
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
    <h2>امضاهای دیجیتال (امضا و تایید)</h2>
    <p>اثبات می‌کنه که امضا و کلید عمومی با یک کلید خصوصی یکسان تولید شدن</p>
    <br>
    <h2 id="1">امضا کردن</h2>
    <p>یه امضای دیجیتال دو جزء داره: </p>
    <p>۱- جزء تصادفی</p>
    <p>۲- جزء مربوط به امضا (کلید خصوصی+داده‌ی تراکنشی که داریم امضای دیجیتالی رو براش ایجاد می‌کنیم.)</p>
    <br>
    <h2 id="1-1">۱- جزء تصادفی</h2>
    <p>با تولید یه عدد تصادفی شروع می‌کنیم؛ و بعد، این عدد رو با نقطه‌ی تولیدکننده‌ی خم بیضوی (نقطه‌ای که برای تولید<a href="https://github.com/rezatajari/learnmeabitcoin/blob/master/08.%20Public%20Keys.md"> کلید عمومی</a> هم </p>
    <p>استفاده می‌شه) ضرب می‌کنیم. </p>
    <img src="https://learnmeabitcoin.com/beginners/images/digital_signatures_signing_verifying/png/01-signing-random-point.png">
    <br>
    <br>
    <p>جز تصادفی امضای دیجیتال، نقطه‌ای روی خم منحنیه که نتیجه‌ی نهایی رو می‌ده. اما ما فقط مختصات xش رو در نظر می‌گیرم: </p>
    <br>
    <br>
    <img src="https://learnmeabitcoin.com/beginners/images/digital_signatures_signing_verifying/png/01-signing-random-point-x.png">
    <br>
    <br>
    <p>به اختصار بهش می‌گیم «r». </p>
    <br>
    <br>
    <img src="https://learnmeabitcoin.com/beginners/images/digital_signatures_signing_verifying/png/01-signing-random-r.png">
    <br>
    <br>
    <h4>عملا این کار شبیه تولید یه کلید خصوصی و یه کلید عمومیه. با این تفاوت که این‌جا داریم یه بخش تصادفی هم به امضای </h4>
    <h4>دیجیتال‌مون اضافه می‌کنیم. </h4>
    <p>پس حالا نصف امضای دیجیتال‌مون آماده‌ست؛ اما کلید خصوصی‌مون رو تا اینجا برای هیچ کاری استفاده نکردیم.</p>
    <br>
    <h2 id="1-2">۲- جزء مربوط به امضا</h2>
    <p>اول، کلید خصوصی‌مون رو برمی‌داریم و در r (مختصات x از نقطه‌ی تصادفی منحنی‌ای که پیدا کردیم) ضرب می‌کنیم. </p>
    <br>
    <br>
    <img src="https://learnmeabitcoin.com/beginners/images/digital_signatures_signing_verifying/png/01-signing-signature-r-privkey.png">
    <br>
    <br>
    <p>مرحله‌ی بعد، چیزی رو که قراره امضا کنیم رو هم بهش اضافه می‌کنیم. به این چیز «پیام» گفته می‌شه. در بیت‌کوین، </p>
    <p>پیام، هش کل داده‌ی تراکنشه که بیت‌کوینی که می‌خوایم باز کنیم رو در خودش جا می‌ده. </p>
    <br>
    <br>
    <img src="https://learnmeabitcoin.com/beginners/images/digital_signatures_signing_verifying/png/01-signing-signature-r-privkey-thing.png">
    <p>مشمول کردن هش تراکنش، باعث می‌شه که امضا به یه تراکنش وصل بشه (و قابل استفاده تو تراکنش دیگه‌ای نباشه.)</p>
    <br>
    <br>
    <p>در نهایت، به یه اندازه‌ی مناسب، همه‌ی این‌ها رو به عدد تصادفی اولیه‌مون تقسیم می‌کنیم:</p>
    <br>
    <br>
    <img src="https://learnmeabitcoin.com/beginners/images/digital_signatures_signing_verifying/png/01-signing-signature-r-privkey-thing-randnum.png">
    <br>
    <br>
    <p>و … هجی مجی لاترجی! جزء حیاتی «امضا» از امضای دیجیتال‌مون آماده‌ست. به اختصار به این بخش می‌گیم «s». </p>
    <br>
    <br>
    <img src="https://learnmeabitcoin.com/beginners/images/digital_signatures_signing_verifying/png/01-signing-signature-rs.png">
    <p>Mr. D Signature.</p>
    <br>
    <br>
    <p>و حالا بخش جالب ماجرا … </p>
    <p>اگه کسی از ما بخواد که اثبات کنیم کلید خصوصی مربوط به یه کلید عمومی رو می‌دونیم، می‌تونیم امضای دیجیتال‌مون </p>
    <p>(r و s)‌ رو ارائه کنیم. </p>
    <p>اما چطوری یه نفر می‌تونه از این اطلاعات به عنوان اثبات استفاده کنه؟</p>
    <br>
    <h2 id="2">تایید کردن </h2>
    <blockquote>
        <p>در بیتکوین، کل این امضا به قسمتی از تراکنش می‌ره که بهش می‌گیم «اسکریپت بازگشایی». کلید </p>
        <p>خصوصی‌ای که از اون برای تولید امضا استفاده کردیم همون کلیدیه که به آدرس بیت‌کوین‌های قفل‌شده </p>
        <p>وصل می‌شه. </p>
    </blockquote>
    <br>
    <br>
    <img src="https://learnmeabitcoin.com/beginners/images/digital_signatures_signing_verifying/png/02-verifying-goal.png">
    <br>
    <br>
    <p>هدف‌مون تایید این مساله‌ست که آیا کلید عمومی و امضای دیجیتال از یه کلید خصوصی ایجاد شدن یا نه. </p>
    <p>برای تایید این‌که آیا کلید خصوصی درستی برای تولید امضای دیجیتال استفاده شده یا نه، کسی که این امضای دیجیتال رو بررسی </p>
    <p>می‌کنه باید از هر دو جزء استفاده کنه تا دو نقطه‌ی جدید روی منحنی بیضوی پیدا بشه. </p>
    <br>
    <h2 id="2-1">نقطه‌ی ۱</h2>
    <p>پیام رو به s‌ تقسیم می‌کنیم. اولین نقطه فقط نقش نقطه‌ی تولیدکننده رو داره که با این مقدار ضرب شده: </p>
    <br><br>
    <img src="https://learnmeabitcoin.com/beginners/images/digital_signatures_signing_verifying/png/02-verifying-point1.png">
    <br><br>
    <h2 id="2-2">نقطه‌ی ۲</h2>
    <p>r رو به s تقسیم می‌کنیم. </p>
    <p>دومین نقطه فقط نقش کلید عمومی رو داره که با این مقدار ضرب شده:</p>
    <br>
    <br>
    <img src="https://learnmeabitcoin.com/beginners/images/digital_signatures_signing_verifying/png/02-verifying-point2.png">
    <br><br>
    <p>و در آخر … </p>
    <p>اگه این دو تا نقطه رو با هم جمع کنیم، یه نقطه‌ی سومی روی منحنی به دست میاریم: </p>
    <br><br><img src="https://learnmeabitcoin.com/beginners/images/digital_signatures_signing_verifying/png/02-verifying-add.png"><br><br>
    <p>و اگه مختصات x از این نقطه‌ی سوم با مختصات x‌ نقطه‌ی تصادفی که باهاش شروع کردیم (یعنی r) یکسان باشه، پس اثبات می‌شه </p>
    <p>که امضای دیجیتال با استفاده از کلید خصوصی مربوط به این کلید عمومی تولید شده. </p>
    <br><br><img src="https://learnmeabitcoin.com/beginners/images/digital_signatures_signing_verifying/png/02-verifying-final.png"><br><br>
    <br>
    <p><a href="https://learnmeabitcoin.com/beginners/digital_signatures_signing_verifying">منبع</a></p>
    <p>شاد زی..</p>
    <p>اینم آخرین قسمت./</p>
</div>