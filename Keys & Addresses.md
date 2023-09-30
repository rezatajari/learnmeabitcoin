<div dir="rtl">
    <h1>کلیدها و آدرس‌ها</h1>
    <p><span style="color: #999999;">عددهای یکتای استفاده شده برای ارسال و دریافت دسته‌های بیت‌کوین.</span></p>
    <h2>فهرست</h2>
        <hr>
    <ul>
        <li>
            <p><a href="#1">کلید خصوصی، کلید عمومی و آدرس چیست؟</a></p>
        </li>
        <li>
            <p><a href="#2">آدرس‌ها و کلیدها از کجا میان؟</a>
                <ul>
                    <li>
                        <p><a href="#2-1">کلید خصوصی</a></p>
                    </li>
                    <li>
                        <p><a href="#2-2">کلید عمومی</a></p>
                    </li>
                    <li>
                        <p><a href="#2-3">آدرس</a></p>
                    </li>
                </ul>
            </p>
        </li>
        <li>
            <p><a href="#3">آیا باید هر سه کلید رو بیاد داشته باشیم؟</a></p>
        </li>
        <li>
            <p><a href="#4">اگه کلید خصوصی رو گم کنم چی می‌شه؟</a></p>
        </li>
    </ul>
    <hr>
    <hr>
    <h2 id="1">کلید خصوصی، کلید عمومی و آدرس چیست؟</h2>
    <p>برای فرستادن و دریافت کردن پول به شکل بیت‌کوین نیاز به یه «شماره حساب» و «رمز عبور» داری.</p>
    <p>در بیت‌کوین به این دو «کلید عمومی» و «کلید خصوصی» می‌گیم.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/keys_addresses/png/01-private-public.png">
    <p style="color: #999999; text-align: center;">این اطلاعات حساب توست. به بیت‌کوین خوش اومدی.</p><br><br>
    <p>با این حال باید در نظر داشت که این شماره حساب، عدد زیادی بزرگیه، پس برای راحتی بیشتر نسخه‌ی فشرده‌ای از اون رو استفاده می‌کنیم، و بهش می‌گیم آدرس.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/keys_addresses/png/01-private-public-address.png">
    <p style="color: #999999; text-align: center;">کمی جلوتر می‌بینی کلید عمومی چقدر بی‌ریخته.</p><br><br>
    <p>این شد نقش کلید خصوصی، کلید عمومی و آدرس.</p>
    <blockquote>
    <p>خب تا اینجا یه جمع بندی کنیم به طور خلاصه داریم:</p>
    <ul>
        <li>کلید عمومی، شماره حسابته.</li><br>
        <li>آدرس، هم همون شماره حسابته، اما نسخه‌ی کوتاه شده‌ایه که مردم بتونن موقع ارسال بیت‌کوین بهت ازش استفاده کنند.</li><br>
        <li> کلید خصوصی، رمز عبورته که مانع از این می‌شه که شخص دیگه‌ای بتونه از حسابت بیت‌کوین ارسال کنه.</li>
    </ul>
    </blockquote>
    <br>
    <h2 id="2">آدرس‌ها و‌ کلیدها از کجا میان؟</h2>
    <h3 id="2-1">کلید خصوصی</h3>
    <p>همه چیز از کلید خصوصی، که فقط یه عدد بطور تصادفی ایجاد شدست، شروع می‌شه:</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/keys_addresses/png/02-random-private.png"><br><br>
    <p>اما چون این عدد بسیار بزرگه، کامپیوترها (و همینطور بیت‌کوین) علاقه به این دارن که از شکل کوتاه‌تر شانزده‌شانزدهی استفاده کنند:</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/keys_addresses/png/02-random-private-hex.png">
    <p style="color: #999999; text-align: center;">اعداد شانزده‌شانزدهی طول کمتری از اعداد ده‌دهی دارن چون شامل حرف‌های a,b,c,d,e و f هم میشن.</p>
    <br><br>
    <p>و این شد کلید خصوصیمون... فقط یه عدد تصادفی بزرگ (منتها به شکل شانزده‌شانزدهی).
    </p>
    <br>
    <table dir="ltr">
        <tr>
            <td>کلید خصوصی</td>
            <td>ef235aacf90d9f4aadd8c92e4b2562e1d9eb97f0df9ba3b508258739cb013db2</td>
        </tr>
    </table>
    <br>
    <ul>
        <li>یه کلید خصوصی می‌تونه هر عددی بین 1 و
        115792089237316195423570985008687907852837564279074904382605163141518161494336
        باشه</li>
    </ul>
    <br>
    <h2 id="2-2">کلید عمومی</h2>
    <p>با استفاده از کلید خصوصیت می‌تونی کلید عمومی رو بدست بیاری!</p>
    <p>پیش از هرچیز، این رو بدونیم که منظور از عموم در «کلید عمومی» همه‌ی مردمه. پس زمانی که از کلید خصوصی‌مون برای ایجاد کلید عمومی استفاده می‌کنیم، نمی‌خواهیم امکان این وجود داشته باشه که کسی بفهمه کلید خصوصی‌مون چیه.
  </p>
  <p>چون کلید خصوصی از بیت‌کوین‌هامون محافظت می‌کنه.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/keys_addresses/png/03-public-private-one-way.png">
    <p>با وجود اینکه کلید عمومی از کلید خصوصی ساخته میشه، نمی‌خواهیم کسی بتونه در جهت برعکس از کلید عمومی کلید خصوصی رو در بیاره.</p><br><br>
    <p>خوشبختانه می‌تونیم از یه نوع تابع خاص ریاضی برای رسیدن به این هدف دست پیدا کنیم.</p>
    <p>ما فقط کلید خصوصی (که نهایت، یه عدده) رو میدیم به اون تابع ریاضی، و در آخر تابع به ما یه کلید عمومی (که اونم یه عدد دیگه‌ست) میده.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/keys_addresses/png/03-public-private-one-way-function.png"><br><br>
    <p>باید بدونیم که این تابع خاص ریاضی برای ما دو مزیت داره:</p>
    <ol>
        <li>این تابع ریاضی به ما یه کلید عمومی برمی‌گردونه بطور ریاضی به کلید خصوصی گره خورده. این برای زمانی که می‌خواهیم بیت‌کوین رو در تراکنش برای کسی بفرستیم بدرد خواهد خورد.
        </li>
        <br><br>
        <img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/keys_addresses/png/03-public-private-mathematical-fit.png">
        <p style="color: #999999; text-align: center;">مثل اینه که قفل رو از روی کلید بسازی.</p>
        <br><br>
        <li>با وجود اینکه کلید عمومی از نظر ریاضی به کلید خصوصی خورده، ممکن نیست که از روی کلید عمومی به کلید خصوصی دست پیدا کرد، به همین دلیله که از این تابع خاص ریاضی استفاده می‌کنیم... چون یک طرفه است.</li>
    </ol>
    <p>به لطف شماره‌های تصادفی ایجاد شده و این تابع خاصمون حالا یه جفت کلید داریم و می‌تونیم ازش برای فرستادن و دریافت بیت‌کوین‌ استفاده کنیم.</p>
    <table dir="ltr">
        <tr>
            <td>کلید خصوصی</td>
            <td>ef235aacf90d9f4aadd8c92e4b2562e1d9eb97f0df9ba3b508258739cb013db2</td>
        </tr>
        <tr>
            <td>کلید عمومی</td>
            <td>02b4632d08485ff1df2db55b9dafd23347d1c47a457072a1e87be26896549a8737</td>
        </tr>
    </table>
    <br>
    <h2 id="2-3">آدرس</h2>
    <p>دیدید چقدر کلید عمومی بدریخته؟ هیچکس با تایپ کردنش حال نمی‌کنه، بیایید عملی‌ترش کنیم و اسمشو بذاریم آدرس.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/keys_addresses/png/04-public-address-pretty.png">
    <p style="color: #999999; text-align: center;">آخیش!</p><br><br>
    <p>فقط کلید عمومی رو فشرده کردیم و به شکلی در آوردیم که از کاراکترهای از نظر نوشتاری مشابه (مثل “O”, “0”, “I” یا “l” ) استفاده نشده.</p>
    <p>هنوز تو دهن نمی‌چرخه ولی بهبود خوبیه.</p>
    <p>
     این آدرس بود... یه نسخه کوتاه‌تر/ساده‌تر کلید عمومی.</p>
    <table dir="ltr">
        <tr>
            <td>کلید خصوصی</td>
            <td>ef235aacf90d9f4aadd8c92e4b2562e1d9eb97f0df9ba3b508258739cb013db2</td>
        </tr>
        <tr>
            <td>کلید عمومی</td>
            <td>02b4632d08485ff1df2db55b9dafd23347d1c47a457072a1e87be26896549a8737</td>
        </tr>
        <tr>
            <td>آدرس</td>
            <td>1EUXSxuUVy2PC5enGXR1a3yxbEjNWMHuem</td>
        </tr>
    </table>
    <p>خب یه نکته رو هم در اینجا بگم که با توجه به روش فشرده‌سازی کلید عمومی، در اینجا هم نمی‌تونیم از روی آدرس به کلید عمومی دست پیدا کنیم.</p>
    <br>
    <h2 id="3">آیا باید هر سه کلید رو بیاد داشته باشیم؟</h2>
    <p>از اونجایی که کلید عمومی و همینطور آدرس بر گرفته از کلید خصوصیته، فقط کافیه کلید خصوصی رو ذخیره کنی.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/keys_addresses/png/05-private-source.png">
    <p style="color: #999999; text-align: center;">یادت باشه, کلید عمومیت (و آدرس) از کلید خصوصیت در میان.</p>
    <br><br>
    <p>بنابراین اگه اتفاقی هم افتاد، اگه بخوای آدرس برای کسی بفرستی فقط کافیه آدرس رو از کلید خصوصی در بیاری.</p>
    <p> در حالت عادی بهتره که کلید خصوصی و آدرس رو در یه جایی نگهداری کنی، آدرس زمانی که می‌خواهی کسی برات بیت‌کوین ارسال کنه بکار میاد.</p>
    <br>
    <h2 id="4">اگه کلید خصوصی رو گم کنم چی می‌شه؟</h2>
    <p>خب این می‌تونه بدترین اتفاق ممکن برات باشه !</p>
    <p>غیرممکنه که از روی کلید عمومی و یا آدرس خودت به کلید خصوصیت دست پیدا کنی، در نتیجه اگه کلید خصوصیت رو گم کنی، دیگه از دست رفته!</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/keys_addresses/png/05-private-lost.png"><br><br>
    <p>و اگه کلید خصوصی مربوط به آدرس رو از دست بدی، بیت‌کوین‌هایی که در اون آدرس داشتی تا ابد قفل میشه!</p>
    <blockquote>
    <p>شاید بگید که این که خیلی سازوکار بی‌رحمیه، آره همینطوره.</p>
    <p>اما از طرف دیگه، خیالت راحته که برای دسترسی به پولت در پشتی‌ای درکار نیست. فقط یه کلید برای بیت‌کوین‌هات هست و اونم در دست توست.</p>
    </blockquote>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/keys_addresses/png/lol-customer-support.png">
    <br><br>
    <p><a href="https://learnmeabitcoin.com/beginners/keys_addresses">منبع</a></p>
    <h2 dir="ltr">Fortunately, "You can take your <br> country out of Bitcoin, but you <br> can't take #Bitcoin out of your <br> country!" - @aantonop</h2>
    <p>شاد زی..</p>
</div>
