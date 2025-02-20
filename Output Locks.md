<div dir="rtl">
    <h1>قفل‌های خروجی</h1>
    <p><span style="color: #999999;">سازوکار قفل کردن خروجی‌های بیت‌کوین.</span></p>
    <h2>فهرست</h2>
        <hr>
    <ul>
        <li>
            <p><a href="#1">قفل خروجی چیه؟</a></p>
        </li>
        <li>
            <p><a href="#2">این قفل‌ها از کجا میان؟</a></p>
        </li>
        <li>
            <p><a href="#3">چطوری می‌شه یه قفل خروجی ایجاد کرد؟</a></p>
        </li>
        <li>
            <p><a href="#4">چطوری می‌شه قفل خروجی رو باز کرد؟</a></p>
        </li>
    </ul>
    <hr>
    <hr>
    <h2 id="1">قفل خروجی چیه؟</h2>
    <p>قفل خروجی یک سری پیش‌نیاز گذاشته شده روی خروجیه. این به این معنیه که باید اول این پیش‌نیازها رفع بشه تا بشه خروجی رو توی یه تراکنش استفاده کرد.</p>
    <p>برای مثال رایج‌ترین حالت قفل خروجی چیزی شبیه به اینه:</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="./beginners/guide/locks/01-output-lock-english.png"><br><br>
    <p>این قفل‌هان که جلوی ما رو می‌گیرن که نتونیم خروجی همدیگه رو تو تراکنش خرج کنیم، چون حالا روی هر خروجی یه قفل زده شده.</p>
    <br>
    <h2 id="2">
        این قفل‌ها از کجا میان؟
    </h2>
    <p>همونطور که می‌دونیم، یه تراکنش فرآیند برداشتن خروجی‌های موجود و ساخت خروجی‌های جدید از اونهاست:</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="./beginners/guide/locks/02-transaction.png"><br><br>
    <p>در این حین ساخت این خروجی‌هاست که روی هر کدوم یه قفل می‌ذاریم:</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="./beginners/guide/locks/02-transaction-locks.png">
    <p style="color: #999999; text-align: center;">ساخت خروجی‌های جدید و قفل زدن روی هر کدام.</p>
    <br><br>
    <p> پس وقتی مثلا می‌خواهیم این رو برای دوستمون بفرستیم، خروجی جدید رو ایجاد می‌کنیم و روش یک قفل می‌زنیم که می‌گه «تنها مالک آدرس 1friend1234567890  (دوست ما) می‌تونه این خروجی رو استفاده کنه».</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="./beginners/guide/locks/02-transaction-locks-addresses.png">
    <p style="color: #999999; text-align: center; ">تمام این‌ها تو اطلاعات تراکنش ثبت شده.</p>
    <br><br>
    <p>نتیجه اینه که این خروجی جدید در عمل فقط به دوستمون «تعلق» داره، چون تنها کسیه که کلید خصوصی این آدرس رو داره پس هیچ کس دیگه‌ای نمی‌تونه خروجی رو خرج کنه.</p>
    <blockquote>
    <p>همونطور که احتمالا متوجه شدی، هرگز واقعا بیت‌کوین در یه تراکنش «ارسال» نمی‌کنی.</p>
    <p>بجاش یه تراکنش می‌سازی که خروجی جدید (با قفل جدید) ایجاد می‌کنه و این داده‌ی تراکنش رو به شبکه بیت‌کوین ارسال می‌کنی و منتظر می‌مونی که استخراج‌کننده‌ها تراکنش رو توی یک بلوک استخراج کنند.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="./beginners/guide/locks/aside-overview.png"><br><br>
    <p>پس هرچند که زنجیره‌بلوک یک فایل از تراکنش‌هاست، اما از سطح کاربردی می‌شه بهش به عنوان واحد انبار خروجی‌ها نگاه کرد.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="./beginners/guide/locks/aside-blockchain-outputs.png"><br><br>
    <p>زمانی که بیت‌کوین‌های «خودت» رو برای کسی می‌فرستی، به خروجی‌های درون زنجیره که می‌تونی خرج کنی اشاره می‌کنی.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="./beginners/guide/locks/aside-blockchain-outputs-transaction.png"><br><br>
    <p>زمانی که این تراکنش در زنجیره‌بلوک استخراج شد، دیگه این خروجی‌هایی که (به عنوان ورودی) استفاده کردی قابل استفاده دوباره نخواهند بود.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="./beginners/guide/locks/aside-blockchain-outputs-transaction-mined.png">
    <p style="color: #999999; text-align: center; ">هر بلوک تراکنش یک سری خروجی تازه به زنجیره‌بلوک اضافه می‌کنه.</p> <br><br>
    <p>پس زنجیره‌بلوک تمام خروجی‌ها رو در خودش ذخیره می‌کنه و هر زمان که بخوای می‌تونی هر کدوم ازشون رو استفاده کنی، البته اگه بتونی قفلشون رو باز کنی. </p>
    </blockquote>
    <hr>
    <br>
    <h2 id="3">چطوری می‌شه یه قفل خروجی ایجاد کرد؟</h2>
    <p>ققل خروجی در یک زبان برنامه‌نویسی ابتدایی به نام اسکریپت نوشته می‌شه.</p>
    <p>توضیح دادن سازوکار یه زبان برنامه‌نویسی کامل با یه نمودار کمی مشکله، اما به هر حال یه چیزی شبیه به اینه:</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="./beginners/guide/locks/03-locking-script.png">
    <p style="color: #999999; text-align: center; ">به قفلی که برنامه‌نویسی می‌کنیم می‌گیم اسکریپت قفل کننده.</p><br><br>
    <p>حالا جالب‌ترین بخش این اسکریپت قفل کننده کلیدواژه‌ی CHECKPRIVATEKEY است، که یه تابعه که ازش برای تعریف پیش‌نیازهای قفل کمک می‌گیریم.</p>
    <p>در مثال بالا برای نمونه ما قفلی رو گذاشتیم که آدرس 1EUXSxuUVy2PC5enGXR1a3yxbEjNWMHuem  رو می‌خواد با یه کلید خصوصی مقایسه کنه،</p>
    <p> اگر بتونیم به این قفل یه کلید خصوصی منطبق ارائه بدیم می‌تونیم این قفل رو باز کنیم و توی یه تراکنش ازش استفاده کنیم.</p>
    <br>
    <h2 id="4">چطوری می‌شه قفل خروجی رو باز کرد؟</h2>
    <p>زمانی که داده‌های تراکنش رو می‌سازی، بعد از هر خروجی‌ای که می‌خوای استفاده کنی یه «اسکریپت باز کننده» می‌ذاری:</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="./beginners/guide/locks/04-unlocking-script.png"><br><br>
    <p>پس مثلا برای باز کردن یه اسکریپت قفل کننده‌ی معمولی (مثل: [CHECKPRIVATEKEY][آدرس] )، باید نشون بدیم که [آدرس] رو داریم برای اثبات این کار، با کلید خصوصیمون یه امضای دیجیتال می‌سازیم.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="./beginners/guide/locks/04-unlocking-script-privkey.png">
    <p style="color: #999999; text-align: center; ">امضای دیجیتالت رو به عنوان اسکریپت باز کننده قرار می‌دی.</p>
    <br><br>
    <p>زمانی که یه گره این داده‌های ارسالی رو دریافت می‌کنه، میاد اسکریپت‌های «قفل کننده»+«باز کننده» رو با هم اجرا می‌کنه که بررسی کنه امضای دیجیتال با آدرسی که خروجی باهاش قفل شده مطابقت داره یا نه.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="./beginners/guide/locks/04-locking-unlocking-script-simple.png"><br><br>
    <p>اگه همه چیز اوکی باشه گره تراکنش رو قبول می‌کنه و اون رو به گره‌های دیگه می‌فرسته که هر کدوم از اون‌ها هم پیش از پذیرش تراکنش اسکریپت‌ «قفل کننده»+«باز کننده» رو اجرا می‌کنن.</p>
    <p>و اینطوری می‌شه یه قفل خروجی رو باز کرد.</p>
    <br>
    <h3>چی شد؟ کلید خصوصی رو که رو لو دادیم!</h3>
    <p>آفرین به این حواس جمع.</p>
    <p>اعتراف: ما درواقع کلید خصوصی خودمون رو در داده‌های تراکنش قرار نمی‌دیم.</p>
    <p>برای اینکه کلید خصوصی خودمون رو داخل داده‌های تراکنش لو ندیم، یه چیزی به اسم «امضای دیجیتال» می‌سازیم.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="./beginners/guide/locks/05-unlocking-script-digitalsignature.png">
    <p style="color: #999999; text-align: center; ">از کلید خصوصی‌مون استفاده می‌کنیم که یه امضای دیجیتال بسازیم.</p><br><br>
    <p>مشخصه که در مورد تابعی که استفاده می‌کنیم هم دروغ گفته بودم. اما ترسی نداره، در واقع یه تابع دیگه هست که [آدرس] رو با [امضای دیجیتال] مقایسه می‌کنه؛ که بهش می‌گن  CHECKSIG.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="./beginners/guide/locks/05-unlocking-script-digitalsignature-simple.png">
    <p style="color: #999999; text-align: center; ">همچنان مشکلمون رو حل می‌کنه.</p><br><br>
    <p>پس به لطف جادوی امضای دیجیتال و تابع CHECKSIG، هم می‌تونیم خروجی‌هامون رو به آدرس‌ها قفل کنیم و هم بدون لو دادن کلید خصوصی‌مون بازشون کنیم .</p>
    <p>همیشه یادمون باشه کلید خصوصی خیلی خیلی خیلی خیلی مهمه و باید بسیار مراقب اون باشیم چون هر کسی اون رو داشته باشه دسترسی به کیف پولمون داره!</p>
    <p>یه فرآیند کامل و عالی!</p>
    <p><a href="https://learnmeabitcoin.com/beginners/guide/locks/">منبع</a></p>
    <p>به یادش: بسیار سفر باید تا پخته شود خامی</p>
    <p>تمومه این قسمت !</p>
    <p>شاد زی..</p>
</div>
