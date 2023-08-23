<div dir="rtl">
    <h1>امضای دیجیتال</h1>
    <p><span style="color: #999999;">عددی که از کلید خصوصی شما تولید شده تا اثبات کنه مالک کلید عمومی‌تون‌اید. 
    </span></p>
    <h2>فهرست</h2>
    <hr>
    <ul>
        <li>
            <p><a href="#1">امضای دیجیتال چیه؟</a></p>
        </li>
        <li>
            <p><a href="#2">چرا از امضاهای دیجیتال در بیت‌کوین استفاده می‌کنیم؟</a></p>
        </li>
        <li>
            <p><a href="#3">امضای دیجیتال وارد می‌شود</a></p>
        </li>
        <li>
           <p><a href="#4">چی باعث می‌شه که با استفاده از یه امضای دیجیتال، کسی نتونه بیت‌کوین‌های موجود دیگه‌ی همون آدرس من رو باز کنه؟ </a></p>
        </li>
        <li>
            <p><a href="#5">امضاهای دیجیتال چطور کار می‌کنن؟</a></p>
        </li>
    </ul>
    <hr>
    <hr>
    <h2 id="1">امضای دیجیتال چیه؟</h2>
    <p>امضای دیجیتال یه چیزیه که باهاش می‌تونین بدون نشون دادن<a href="./Private%20Keys.md"> کلید خصوصی</a> واقعی، ثابت کنین کلید خصوصی مرتبط به یه 
    <a href="./Public%20Keys.md">کلید عمومی</a> رو می‌دونید.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/digital_signatures/png/01-digital-signature-usage.png"><br>
    <p>پس، هر وقت کسی ازتون پرسید که آیا کلید خصوصی مربوط به یه کلید عمومی به‌خصوص (یا آدرس) رو دارید، می‌تونین امضای 
    دیجیتال‌تون رو به عنوان اثبات نشون بدین. 
    </p>
    <blockquote>
        فقط نیازه که یه کم محاسبه‌ی ریاضی کنیم تا رابطه‌ی امضای دیجیتال با کلید عمومی دربیاد و اثبات بشه که به هم مرتبطند. 
    </blockquote>
    <br>
    <h2 id="2">چرا از امضاهای دیجیتال در بیت‌کوین استفاده می‌کنیم؟</h2>
    <p>چون وقتی که یه تراکنش ایجاد می‌کنی، باید <a href="./Outputs.md">بیت‌کوینی که تو کیف پوله</a> رو باز کنی. این کار با نشون دادن «مالکیت» بیت‌کوین‌ها 
    انجام‌پذیره. و این کار رو با نشون دادن کلید خصوصی آدرسی که بیت‌کوین‌ها توش قفل شده، اثبات می‌کنی: 
    </p>
    <br>
    <br>
    <img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/digital_signatures/png/02-transaction-data.png"><br><br>
    <p>اما اگه کلید خصوصی‌ت رو تو داده‌ی تراکنش قرار بدی، هر کسی تو شبکه می تونه کلید خصوصی‌ت رو ببینه: </p>
    <br>
    <br>
    <img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/digital_signatures/png/02-transaction-data-privkey.png">
    <br><br>
    <p>و اگه کسی به کلید خصوصی‌ت دست پیدا کنه، می‌تونه بیت‌کوین‌های دیگه‌ای که داخل همون آدرس هست رو باز کنه. 
    </p>
    <p>
    پس چطور قفل رو باز کنیم بدون این‌که کلید خصوصی‌مون لو بره؟</p>
    <br>
    <h2 id="3">امضای دیجیتال وارد می‌شود</h2>
    <blockquote>
        <p>امضای دیجیتال می‌تونه استفاده بشه تا مقدار بیت‌کوینی که می‌شه خرج کرد رو باز کنه؛ چون نشون‌دهنده‌ی
        اینه که کلید خصوصی یه آدرس رو می‌دونیم. </p>
    </blockquote>
    <p>اما به‌ترین قسمتش اینه که استفاده از امضای دیجیتال به معنی ارائه نکردن کلید خصوصی به شبکه‌ست. </p>
    <br><br>
    <img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/digital_signatures/png/02-transaction-data-digsig.png">
    <br><br>
    <p>برای همینه که از امضای دیجیتال به جای قرار دادن مستقیم کلیدهای خصوصی‌مون توی داده‌ی تراکنش استفاده می‌کنیم. </p>
    <h2 id="4">چی باعث می‌شه که با استفاده از یه امضای دیجیتال، کسی نتونه بیت‌کوین‌های موجود دیگه‌ی همون آدرس من رو باز کنه؟ </h2>
    <p>سوال خوبیه. بالاخره اگه کلید خصوصی‌ای که استفاده می‌کنم، بیت‌کوین‌های آدرس من رو باز می‌کنه، چرا کسی نتونه امضای 
    دیجیتال رو برداره و ازش استفاده‌ی مشابهی بکنه؟</p>
    <blockquote>
        <p>جواب: چون هر امضای دیجیتال مختص فقط همون تراکنشه. </p>
    </blockquote>
    <p>یعنی این‌که تو فقط از کلید خصوصی‌ت برای تولید امضای دیجیتال استفاده نمی‌کنی … از کلید خصوصی‌ت به اضافه‌ی داده‌ی اصلی 
    تراکنش استفاده می‌کنی: </p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/digital_signatures/png/03-digital-signature-components.png">
    <br><br>
    <p>بنابراین، هر امضای دیجیتال به تراکنشی وصله که در اون استفاده می‌شه. </p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/digital_signatures/png/03-digital-signature-environment.png"><br><br>
    <p>پس، اگه کسی بخواد از این امضای دیجیتال تو یه تراکنش دیگه استفاده کنه، این امضا با داده‌ی تراکنش در حافظه‌ی امضای دیجیتال 
    هم‌خوانی نخواهد داشت و گره‌های شبکه‌ی بیت‌کوین قبولش نمی‌کنن.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="https://learnmeabitcoin.com/beginners/images/digital_signatures/png/03-digital-signature-environment-different.png"><br><br>
    <blockquote>در نتیجه، امضای دیجیتال هر تراکنش‌، از دستکاری شدن همون تراکنش هم محافظت می‌کنه. </blockquote>
    <br>
    <h2 id="5">امضاهای دیجیتال چطور کار می‌کنن؟</h2>
    <p>ریاضیه، عزیزم. </p>
    <ol>
    <li>
    <p> کلید خصوصی رو با داده‌ی تراکنش تلفیق می‌کنی و با کمک یه کم ریاضی ازش یه امضای دیجیتال تولید می‌کنی.</p>
    </li><li>
    <p> بعدش، می‌تونی امضای دیجتال+داده‌ی تراکنش+کلید عمومی رو برداری و یه کم ریاضی بیش‌تری روش پیاده کنی و نتیجه‌ش 
    چیزی می‌شه که می‌تونه صحت کلید خصوصی استفاده‌شده برای تولید امضای دیجیتالی رو تصدیق کنه. </p>
    </li>
    </ol>
    <p>چون یادت باشه، هدف امضای دیجیتال، نشون دادن مالکیت کلید عمومیه. </p>
    <hr>
    <blockquote>
        <p>می‌دونم که این پروسه در نگاه اول شبیه جادوگری می‌مونه؛ اما راستش رو بخوای تهش فقط محاسبات ریاضیه.</p>
        <p>و اگه دوست داری ببینی چطوری …. </p>
        <p><a href="./Digital%20Signatures%20(Signing%20%26%20Verifying).md">امضاهای دیجیتال (امضا و تایید) </a></p>
    </blockquote>
    <hr>
    <br>
    <p><a href="https://learnmeabitcoin.com/beginners/digital_signatures">منبع</a></p>
    <p>شاد زی..</p>
    <p>علم داشتن نوعی قدرته، این یادمون باشه !</p>
</div>