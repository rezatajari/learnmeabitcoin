<div dir="rtl">
    <h1>قفل‌های خروجی</h1>
    <p><span style="color: #999999;">سازوکار قفل کردن خروجی‌های بیت‌کوین.</span></p>
    <h2>فهرست</h2>
        <hr>
    <ul>
        <li>
            <p><a href="#1">یک قفل خروجی چیست ؟</a></p>
        </li>
        <li>
            <p><a href="#2">از چه جایی و متعلق به کجاست این قفل ها ؟</a></p>
        </li>
        <li>
            <p><a href="#3">چگونه می توان یک قفل خروجی ایجاد کرد ؟</a></p>
        </li>
        <li>
            <p><a href="#4">چگونه شما می تونید قفل خروجی رو باز کنید ؟</a></p>
        </li>
        <li>
            <p><a href="#5">چه چیزی می تونه ترسناک باشه ؟ پرایویت کی ای که همینجوری از دست بره !
            </a></p>
        </li>
    </ul>
    <hr>
    <hr>
    <h2 id="1">یک قفل خروجی چیست ؟</h2>
    <p>قفل در خروجی ها به معنیه اینه که باید اول یه سری کارهای لازم انجام بشه تا بعد این قفل باز بشه تا قابلیت استفاده از خروجی رو به ما بده.</p>
    <p>برای مثال عمومی ترین حالتی که می توان گفت در این مورد یه چیزی شبیه اینه:</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/output_locks/png/01-output-lock-english.png"><br><br>
    <p>این قفل ها باعث جلوگیری از استفاده آن ها می شه، ینی اینکه روی هر خروجی یه قفل زده شده، که تا زمانی که ما نخواهیم اون رو نمی شه خرج کرد و این قفل ها باعث می شن که تراکنش ها سرخود خرج نشن !</p>
    <br>
    <h2 id="2">
        از چه جایی و متعلق به کجاست این قفل ها ؟
    </h2>
    <p>خب همونطور که می دونیم یه تراکنش فرآیندی هست بین خروجی های موجود و ایجاد نوع جدیدی از اونها:</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/output_locks/png/02-transaction.png"><br><br>
    <p>در این حین که این خروجی ها ایجاد می شوند، به آنها همزمان قفل هم زده می شه:</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/output_locks/png/02-transaction-locks.png">
    <p>Creating new outputs and giving each one a lock.</p>
    <br><br>
    <p>بنابراین بعد از اینکار ما یه خروجی جدید ایجاد کردیم که مثلا می خواهیم این رو برای دوستمون بفرستیم، وقتی اینکارو می خوایم کنیم بگونه ای انجام می گیره که تنها مالک (دوست ما) می تونه قفل این خروجی رو باز کنه و از اون استفاده کنه.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/output_locks/png/02-transaction-locks-addresses.png">
    <p>All of this is stored in the transaction data.</p>
    <br><br>
    <p>نتیجه چی میشه !؟ نتیجه اینه که وقتی ما این خروجی رو میفرستیم برای دوستمون و طوری قفل می زنیم که فقط اون استفاده کنه، بنابراین هیچ کس دیگه ای جز اون (دوست ما) که خروجی متعلق به خودشه نمی تونه قفل خروجی رو باز کنه چون تنها کلید دست دوست ماست که قابلیت
        باز کردن این خروجی رو داره.</p>
    <hr>
    <hr>
    <p>همانطور که متوجه هستید هرگز بیت‌کوین ها رو در یه تراکنش ارسال نمی کنید.</p>
    <p>بجاش شما یه خروج جدید ایجاد می کنید (با قفل جدید) و این اطلاعات تراکنش رو به شبکه بیت‌کوین ارسال می کنید و منتظر این می مونید که استخراج گرها (استخراج‌کننده ها) تراکنش شما رو به زنجیره‌بلوک منتقل کنند.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/output_locks/png/a-overview.png"><br><br>
    <p>خب هرچند که زنجیره‌بلوک یه سری فایل هستش، اما شما به هر حال به عنوان یه خروجی که به صورت عملی می توانید از آن استفاده کنید، می توانید از این تراکنش بهره ببرید.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/output_locks/png/a-blockchain-outputs.png"><br><br>
    <p>و اگه زمانی شما نیاز داشته باشید که بیت‌کوین های خودتون رو برای کسی بفرستید به قفل بیت‌کوین هایی که در خروجی شما قرار دارند دسترسی دارید و قابلیت خرج آن را دارید.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/output_locks/png/a-blockchain-outputs-transaction.png"><br><br>
    <p>و زمانی که شما این تراکنش رو خرج کردید و استخراج‌کننده‌ها اون رو به زنجیره‌بلوک اضافه کردند دیگه این خروجی ها رو (نوعی ورودی) نمی توانید دوباره خرج کنید.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/output_locks/png/a-blockchain-outputs-transaction-mined.png">
    <p>Each new block of transactions adds a fresh bunch of outputs in to the blockchain.</p> <br><br>
    <p>بنابراین زنجیره‌بلوک یا همون زنجیره بلوک تمام خروجی ها رو در خودش ذخیره می کنه و هر زمان که شما بخواهید می تونید از اونها استفاده کنید، و البته اینم میدونید که تا زمانی که شما دسترسی به قابلیت باز کردن خروجی ها داشته باشید یا کلید خروجی ها
        رو در دست داشته باشید. </p>
    <hr>
    <hr>
    <br>
    <h2 id="3">چگونه می توان یک قفل خروجی ایجاد کرد ؟</h2>
    <p>ققل خروجی در زبان برنامه نویسی که در قالب اسکریپت نوشته شده است.</p>
    <p>این موضوع کمی مشکله توضیح دادنش به صورت یه دیاگرام که به چه شکل عمل می کند، اما به هر حال یه چیزی شبیه به این شکل هست:</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/output_locks/png/03-locking-script.png">
    <p>This lock we program is called a locking script.</p><br><br>
    <p>درواقع جالب ترین بخش این خروجی ها همان بررسی کردن پرایویت کی هستش، که در قالب یه تابع قرار داده شده که برای تنظیم نحوه قفل خروجی از آن استفاده می شود.</p>
    <p>در مثال بالا برای نمونه ما خروجی را بطوری تنظیم کرده ایم که آدرس زیر را</p>
    <p>1EUXSxuUVy2PC5enGXR1a3yxbEjNWMHuem </p>
    <p>با پرایویت کی مورد نظر این آدرس مقایسه کرده، و پرایویت کی رو با این آدرس تطبیق بدیم، بعد از موفقیت این مرحله، می توان قفل رو باز کنیم و از تراکنش استفاده کنیم.</p>
    <br>
    <h2 id="4">چگونه شما می تونید قفل خروجی رو باز کنید ؟</h2>
    <p>زمانی که شما جزئیات یه تراکنش رو ساختید، کنار آن اسکریپتی برای باز کردن قفل دارید " unlocking script " که برای استفاده از هر خروجی این اسکریپت رو به کار میگیرید.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/output_locks/png/04-unlocking-script.png"><br><br>
    <p>بنابراین برای باز کردن یه نمونه قفل اسکریپت (به عنوان مثال [address][CHECKPRIVATEKEY] )، ما باید ثابت کنیم که آدرس که در پرانتز هم بود، رو داریم برای انجام این کار، ما توسط کلید خصوصی که داریم می تونیم برای امضاء دیجیتالی از ان استفاده کنیم که جزئی
        از عملیات کار می باشد.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/output_locks/png/04-unlocking-script-privkey.png">
    <p>You put your digital signature as the “unlocking script”.</p>
    <br><br>
    <p>خب بعد از این زمانی که این داده های ارسالی رو یه گره در شبکه دریافت می کنه، میاد بررسی می کنه که " با هم دیگه اجرا بشن و بررسی می کنند با آدرسی که داشتید اسکریپت های "unlocking" + "locking"  مطابقت داشته باشه، درواقع نگاه می کنند که قفل مرتبط باشه
        با آدرس و امضای دیجیتالی که ارسال شده است از طرف شما.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/output_locks/png/04-locking-unlocking-script-simple.png"><br><br>
    <p>اگه همه چیز اوکی باشه گره (نود) تراکنش رو قبول می کنه و اون رو ارسال می کنه به گره‌های دیگه که هر کدام به عنوان گره در شبکه میان "locking" و "unlocking" رو بررسی می کنن و بعد اون تراکنش رو قبول می کنند.</p>
    <p>و اینجوریه که در واقع روند باز کردن یه قفل خروجی انجام میگیره.</p>
    <br>
    <h2 id="5">چه چیزی می تونه ترسناک باشه ؟ پرایویت کی ای که همینجوری از دست بره !</h2>
    <p>دقت کنید به این موضوع عزیزان !</p>
    <p>اعتراف: ما درواقع کلید خصوصی خودمون رو در اطلاعات دیتا تراکنش قرار نمی دهیم، این نکته رو اشتباه متوجه نشیم !</p>
    <p>برای اینکه ما از پرایویت کی خود محافظت کنیم و اون رو در معرض خطر قرار ندهیم، و همینطور داخل دیتایی ارسال نکنیم، تنها یه امضای دیجیتالی انجام میدیم، نه اینکه پرایویت کی رو برای کسی بفرستیم.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/output_locks/png/05-unlocking-script-digitalsignature.png">
    <p>We use our private key to make a digital signature.</p><br><br>
    <p>درواقع چیزی که از تابع هایی که ما استفاده می کنیم دروغی بود که به شما گفتم  اما این موضوع ترسناک نیست، چون در واقعیت این موضوع مقایسه کردن وجود داره و باید حتما یه پرایویت کی مخصوص آن آدرس باشه که با هم دیگه مقایسه بشه، که می شه مقایسه امضای دیجیتالی
        شما با مقایسه آدرس.. که این رو به اصطلاح CHECKSIG نام گذاری می کنند.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/output_locks/png/05-unlocking-script-digitalsignature-simple.png">
    <p>Still does the trick.</p><br><br>
    <p>بنابراین یه دستت درد نکنه اساسی به امضای دیجیتال باید گفت که به لطف اون و البته تابع CHECKSIG ، ما می تونیم خروجی هامون رو قفل بزنیم و اون ها رو خرج کنیم و همه این کارها بدون اینکه پرایویت کی خودمون رو در دست کسی دیگه قرار داده باشیم.</p>
    <p>همیشه یادمون باشه پرایویت کی خیلی خیلی خیلی خیلی مهم هستش و باید بسیار مراقب اون باشیم زیرا هرکسی اون رو داشته باشه دسترسی به کیف پول شما داره !</p>
    <p>یک فرآیند کامل و عالی !</p>
    <p><a href="https://learnmeabitcoin.com/beginners/output_locks">منبع</a></p>
    <p>به یادش: بسیار سفر باید تا پخته شود خامی</p>
    <p>تمومه این قسمت !</p>
    <p>شاد زی..</p>
</div>
