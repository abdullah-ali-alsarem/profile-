[index.html](https://github.com/user-attachments/files/32656105/index.html)
<!DOCTYPE html>
<!-- يحدد أن الملف يستخدم معيار HTML5 -->

<html lang="ar" dir="rtl">
<!-- بداية صفحة HTML، واللغة عربية واتجاه الكتابة من اليمين لليسار -->

<head>
<!-- بداية معلومات الصفحة -->

    <meta charset="UTF-8">
    <!-- يجعل الصفحة تدعم اللغة العربية وجميع الأحرف -->

    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- يجعل الموقع متجاوباً مع شاشات الجوال والكمبيوتر -->

    <meta name="description" content="الموقع الشخصي لعبدالله علي عبده علي الصارم، محاسب قانوني ومهندس تقنية معلومات وتاجر.">
    <!-- وصف الموقع لمحركات البحث -->

    <meta name="keywords" content="عبدالله الصارم, محاسب قانوني, مهندس تقنية معلومات, برمجة, تجارة, إب, اليمن">
    <!-- الكلمات المفتاحية للموقع -->

    <meta name="author" content="عبدالله علي عبده علي الصارم">
    <!-- اسم صاحب الموقع -->

    <meta name="theme-color" content="#00a9d6">
    <!-- لون واجهة المتصفح على بعض أجهزة الجوال -->

    <title>عبدالله الصارم | محاسب قانوني ومهندس تقنية معلومات</title>
    <!-- عنوان الموقع الذي يظهر في تبويب المتصفح -->

    <link rel="stylesheet" href="style.css">
    <!-- ربط ملف CSS المسؤول عن تصميم الموقع -->

</head>
<!-- نهاية معلومات الصفحة -->


<body>
<!-- بداية محتوى الموقع -->


<header class="header" id="header">
<!-- رأس الموقع والقائمة الرئيسية -->

    <div class="container header-container">
    <!-- حاوية تجمع عناصر رأس الموقع -->

        <a href="#home" class="logo">
        <!-- شعار الموقع ويرجع إلى الصفحة الرئيسية -->

            <span>عبدالله</span>
            <!-- الجزء الأول من اسم الشعار -->

            <strong>الصارم</strong>
            <!-- الجزء الثاني من اسم الشعار -->

        </a>
        <!-- نهاية الشعار -->


        <button class="menu-toggle" id="menuToggle" aria-label="فتح القائمة" aria-expanded="false">
        <!-- زر القائمة في الجوال -->

            <span></span>
            <!-- الخط الأول من أيقونة القائمة -->

            <span></span>
            <!-- الخط الثاني من أيقونة القائمة -->

            <span></span>
            <!-- الخط الثالث من أيقونة القائمة -->

        </button>
        <!-- نهاية زر القائمة -->


        <nav class="nav" id="nav">
        <!-- القائمة الرئيسية -->

            <a href="#home" class="nav-link active">الرئيسية</a>
            <!-- رابط القسم الرئيسي -->

            <a href="#about" class="nav-link">نبذة عني</a>
            <!-- رابط قسم نبذة عني -->

            <a href="#skills" class="nav-link">المهارات</a>
            <!-- رابط قسم المهارات -->

            <a href="#experience" class="nav-link">الخبرات</a>
            <!-- رابط قسم الخبرات -->

            <a href="#certificates" class="nav-link">الشهادات</a>
            <!-- رابط قسم الشهادات -->

            <a href="#cv" class="nav-link">السيرة الذاتية</a>
            <!-- رابط قسم السيرة الذاتية -->

            <a href="#contact" class="nav-link">تواصل معي</a>
            <!-- رابط قسم التواصل -->

        </nav>
        <!-- نهاية القائمة -->

    </div>
    <!-- نهاية حاوية الرأس -->

</header>
<!-- نهاية رأس الموقع -->



<main>
<!-- بداية المحتوى الرئيسي -->


<section class="hero" id="home">
<!-- القسم الرئيسي للموقع -->

    <div class="hero-background"></div>
    <!-- خلفية زخرفية للقسم -->

    <div class="container hero-container">
    <!-- حاوية محتوى القسم الرئيسي -->

        <div class="hero-content">
        <!-- محتوى النص الرئيسي -->

            <p class="hero-small-title">
                مرحباً بك في موقعي الشخصي
            </p>
            <!-- رسالة الترحيب -->

            <h1>
                عبدالله علي عبده علي الصارم
            </h1>
            <!-- الاسم الكامل -->

            <h2>
                محاسب قانوني <span>+</span> مهندس تقنية معلومات
            </h2>
            <!-- التخصص والمهنة -->

            <p class="hero-description">
                أجمع بين الخبرة التجارية والمحاسبية والاهتمام بتقنية المعلومات
                والبرمجة لبناء حلول عملية ومشاريع رقمية حديثة.
            </p>
            <!-- الوصف المختصر -->

            <div class="hero-buttons">
            <!-- مجموعة أزرار القسم الرئيسي -->

                <a href="#cv" class="btn btn-primary">
                    عرض السيرة الذاتية
                </a>
                <!-- زر الانتقال إلى السيرة الذاتية -->

                <a href="#contact" class="btn btn-outline">
                    تواصل معي
                </a>
                <!-- زر الانتقال إلى التواصل -->

            </div>
            <!-- نهاية مجموعة الأزرار -->

        </div>
        <!-- نهاية المحتوى النصي -->


        <div class="hero-image-wrapper">
        <!-- حاوية الصورة الشخصية -->

            <div class="image-glow"></div>
            <!-- تأثير ضوئي خلف الصورة -->

            <div class="hero-image">
            <!-- إطار الصورة -->

                <img src="10.jpg"  alt="صورة عبدالله علي عبده علي الصارم">
                <!-- الصورة الشخصية، ضع صورتك باسم my-photo.jpg -->

            </div>
            <!-- نهاية إطار الصورة -->

        </div>
        <!-- نهاية حاوية الصورة -->

    </div>
    <!-- نهاية الحاوية -->

</section>
<!-- نهاية القسم الرئيسي -->



<section class="about section" id="about">
<!-- قسم نبذة عني -->

    <div class="container">
    <!-- حاوية القسم -->

        <div class="section-heading">
        <!-- عنوان القسم -->

            <span>01</span>
            <!-- رقم القسم -->

            <h2>نبذة عني</h2>
            <!-- عنوان القسم -->

            <p>
                تعرف على خلفيتي وخبراتي ومجالات اهتمامي.
            </p>
            <!-- وصف القسم -->

        </div>
        <!-- نهاية عنوان القسم -->


        <div class="about-grid">
        <!-- شبكة معلومات القسم -->

            <div class="about-text glass-card">
            <!-- بطاقة المعلومات الشخصية -->

                <h3>من أنا؟</h3>
                <!-- عنوان البطاقة -->

                <p>
                    أنا عبدالله علي عبده علي الصارم، يمني من محافظة إب،
                    لدي خبرة في مجال التجارة والمحاسبة، واهتمام كبير
                    بتقنية المعلومات والبرمجة وتطوير المشاريع الرقمية.
                </p>
                <!-- نبذة شخصية -->

                <p>
                    أعمل على تطوير مهاراتي بشكل مستمر في البرمجة،
                    تصميم المواقع، الأنظمة المحاسبية وتقنيات الحاسب.
                </p>
                <!-- فقرة إضافية -->

            </div>
            <!-- نهاية بطاقة المعلومات -->


            <div class="info-grid">
            <!-- شبكة البيانات الشخصية -->

                <div class="info-card">
                    <span>الاسم</span>
                    <strong>عبدالله الصارم</strong>
                </div>
                <!-- بطاقة الاسم -->

                <div class="info-card">
                    <span>الجنسية</span>
                    <strong>يمني</strong>
                </div>
                <!-- بطاقة الجنسية -->

                <div class="info-card">
                    <span>المحافظة</span>
                    <strong>إب</strong>
                </div>
                <!-- بطاقة المحافظة -->

                <div class="info-card">
                    <span>المهنة</span>
                    <strong>عامل</strong>
                </div>
                <!-- بطاقة المهنة -->

                <div class="info-card">
                    <span>التخصص</span>
                    <strong>محاسبة وتقنية معلومات</strong>
                </div>
                <!-- بطاقة التخصص -->

                <div class="info-card">
                    <span>الخبرة</span>
                    <strong>8 سنوات في التجارة</strong>
                </div>
                <!-- بطاقة الخبرة -->

            </div>
            <!-- نهاية شبكة المعلومات -->

        </div>
        <!-- نهاية شبكة نبذة عني -->

    </div>
    <!-- نهاية الحاوية -->

</section>
<!-- نهاية قسم نبذة عني -->



<section class="skills section" id="skills">
<!-- قسم المهارات -->

    <div class="container">
    <!-- حاوية القسم -->

        <div class="section-heading">
            <span>02</span>
            <h2>المهارات</h2>
            <p>مجموعة من المهارات والخبرات التي أعمل على تطويرها باستمرار.</p>
        </div>
        <!-- عنوان القسم -->


        <div class="cards-grid">
        <!-- شبكة بطاقات المهارات -->

            <article class="skill-card glass-card">
                <div class="skill-icon">01</div>
                <h3>المحاسبة</h3>
                <p>خبرة في أساسيات المحاسبة والتعامل مع الأنظمة والعمليات المالية.</p>
            </article>
            <!-- بطاقة المحاسبة -->

            <article class="skill-card glass-card">
                <div class="skill-icon">02</div>
                <h3>التجارة</h3>
                <p>خبرة عملية في التجارة وإدارة الأعمال والبيع والشراء.</p>
            </article>
            <!-- بطاقة التجارة -->

            <article class="skill-card glass-card">
                <div class="skill-icon">03</div>
                <h3>HTML / CSS / JS</h3>
                <p>تصميم وتطوير صفحات ومواقع ويب باستخدام تقنيات الويب الأساسية.</p>
            </article>
            <!-- بطاقة تطوير الويب -->

            <article class="skill-card glass-card">
                <div class="skill-icon">04</div>
                <h3>تقنية المعلومات</h3>
                <p>اهتمام بالشبكات والبرمجة وأنظمة الحاسب وتقنيات المعلومات.</p>
            </article>
            <!-- بطاقة تقنية المعلومات -->

        </div>
        <!-- نهاية شبكة المهارات -->

    </div>
    <!-- نهاية الحاوية -->

</section>
<!-- نهاية قسم المهارات -->



<section class="experience section" id="experience">
<!-- قسم الخبرات المهنية -->

    <div class="container">
    <!-- حاوية القسم -->

        <div class="section-heading">
            <span>03</span>
            <h2>الخبرات المهنية</h2>
            <p>أبرز الخبرات العملية والمجالات التي عملت فيها.</p>
        </div>
        <!-- عنوان القسم -->


        <div class="timeline">
        <!-- بداية الخط الزمني -->

            <div class="timeline-item">
            <!-- عنصر الخبرة الأول -->

                <div class="timeline-dot"></div>
                <!-- نقطة الخط الزمني -->

                <div class="timeline-content glass-card">
                <!-- محتوى الخبرة -->

                    <span class="timeline-date">8 سنوات</span>
                    <!-- مدة الخبرة -->

                    <h3>التجارة</h3>
                    <!-- عنوان الخبرة -->

                    <p>
                        خبرة عملية في مجال التجارة وإدارة عمليات البيع والشراء
                        والتعامل مع العملاء وإدارة النشاط التجاري.
                    </p>
                    <!-- وصف الخبرة -->

                </div>
                <!-- نهاية محتوى الخبرة -->

            </div>
            <!-- نهاية عنصر الخبرة -->


            <div class="timeline-item">
                <div class="timeline-dot"></div>

                <div class="timeline-content glass-card">

                    <span class="timeline-date">خبرة عملية</span>

                    <h3>تجارة المواد الغذائية</h3>

                    <p>
                        العمل في مجال تجارة المواد الغذائية والتعامل مع المنتجات
                        والعملاء وإدارة العمليات التجارية اليومية.
                    </p>

                </div>

            </div>
            <!-- نهاية الخبرة الثانية -->

        </div>
        <!-- نهاية الخط الزمني -->

    </div>
    <!-- نهاية الحاوية -->

</section>
<!-- نهاية الخبرات -->



<section class="certificates section" id="certificates">
<!-- قسم الشهادات والدورات -->

    <div class="container">
    <!-- حاوية القسم -->

        <div class="section-heading">
            <span>04</span>
            <h2>الشهادات والدورات</h2>
            <p>أهم الشهادات والدورات التي تم الحصول عليها.</p>
        </div>
        <!-- عنوان القسم -->


        <div class="cards-grid certificates-grid">
        <!-- شبكة الشهادات -->

            <article class="certificate-card glass-card">
                <span>01</span>
                <h3>HTML + CSS + JS</h3>
                <p>شهادة في أساسيات تطوير الويب.</p>
            </article>
            <!-- الشهادة الأولى -->

            <article class="certificate-card glass-card">
                <span>02</span>
                <h3>الرخصة الدولية للموظف المحترف</h3>
                <p>تدريب وشهادة في المهارات المهنية.</p>
            </article>
            <!-- الشهادة الثانية -->

            <article class="certificate-card glass-card">
                <span>03</span>
                <h3>دبلوم إنجليزي مبتدئ</h3>
                <p>دراسة أساسيات اللغة الإنجليزية.</p>
            </article>
            <!-- الشهادة الثالثة -->

            <article class="certificate-card glass-card">
                <span>04</span>
                <h3>التنمية البشرية والتسويق</h3>
                <p>دورات في التنمية البشرية والتسويق.</p>
            </article>
            <!-- الشهادة الرابعة -->

            <article class="certificate-card glass-card">
                <span>05</span>
                <h3>دورات في المحاسبة</h3>
                <p>دورات قصيرة في أساسيات المحاسبة.</p>
            </article>
            <!-- الشهادة الخامسة -->

            <article class="certificate-card glass-card">
                <span>06</span>
                <h3>الرخصة الدولية لقيادة الحاسوب</h3>
                <p>تدريب في مهارات استخدام الحاسب.</p>
            </article>
            <!-- الشهادة السادسة -->

            <article class="certificate-card glass-card">
                <span>07</span>
                <h3>برمجة الجوال</h3>
                <p>دورات وتعلم أساسيات برمجة تطبيقات الجوال.</p>
            </article>
            <!-- الشهادة السابعة -->

        </div>
        <!-- نهاية شبكة الشهادات -->

    </div>
    <!-- نهاية الحاوية -->

</section>
<!-- نهاية الشهادات -->



<section class="cv section" id="cv">
<!-- قسم السيرة الذاتية -->

    <div class="container">
    <!-- حاوية القسم -->

        <div class="section-heading">
            <span>05</span>
            <h2>السيرة الذاتية</h2>
            <p>ملخص احترافي للمعلومات والخبرات.</p>
        </div>
        <!-- عنوان القسم -->


        <div class="cv-box glass-card">
        <!-- صندوق السيرة الذاتية -->

            <div class="cv-header">
            <!-- رأس السيرة الذاتية -->

                <div>
                    <span class="cv-label">السيرة الذاتية</span>
                    <h3>عبدالله علي عبده علي الصارم</h3>
                    <p>محاسب قانوني | مهندس تقنية معلومات | تاجر</p>
                </div>
                <!-- بيانات رأس السيرة -->

                <div class="cv-badge">
                    CV
                </div>
                <!-- علامة CV -->

            </div>
            <!-- نهاية رأس السيرة -->


            <div class="cv-details">
            <!-- تفاصيل السيرة -->

                <div>
                    <span>الخبرة</span>
                    <strong>8سنوات في العمل</strong>
                </div>

                <div>
                    <span>التخصص</span>
                    <strong>محاسبة وتقنية معلومات</strong>
                </div>

                <div>
                    <span>المحافظة</span>
                    <strong>إب - اليمن</strong>
                </div>

            </div>
            <!-- نهاية تفاصيل السيرة -->


            <button class="btn btn-primary print-cv" id="printCv">
                طباعة / حفظ السيرة الذاتية
            </button>
            <!-- زر طباعة السيرة الذاتية -->

        </div>
        <!-- نهاية صندوق السيرة -->

    </div>
    <!-- نهاية الحاوية -->

</section>
<!-- نهاية السيرة الذاتية -->



<section class="contact section" id="contact">
<!-- قسم التواصل -->

    <div class="container">
    <!-- حاوية القسم -->

        <div class="section-heading">
            <span>06</span>
            <h2>تواصل معي</h2>
            <p>يمكنك التواصل معي للاستفسار أو التعاون في المشاريع.</p>
        </div>
        <!-- عنوان التواصل -->


        <div class="contact-grid">
        <!-- شبكة التواصل -->

            <div class="contact-info glass-card">
            <!-- معلومات الاتصال -->

                <h3>معلومات التواصل</h3>

                <div class="contact-item">
                    <span>📍</span>
                    <div>
                        <small>الموقع</small>
                        <strong>إب - خط الثلاثين</strong>
                    </div>
                </div>
                <!-- الموقع -->

                <div class="contact-item">
                    <span>📱</span>
                    <div>
                        <small>الهاتف</small>
                        <strong>771729181</strong>
                    </div>
                </div>
                <!-- الهاتف -->

            </div>
            <!-- نهاية معلومات التواصل -->


            <div class="contact-actions glass-card">
            <!-- أزرار التواصل -->

                <h3>تواصل مباشرة</h3>

                <a
                    href="https://wa.me/967771729181"
                    class="whatsapp-button"
                    target="_blank"
                    rel="noopener noreferrer"
                >
                    التواصل عبر واتساب
                </a>
                <!-- زر واتساب -->

                <a href="tel:+967771729181" class="call-button">
                    الاتصال مباشرة
                </a>
                <!-- زر الاتصال -->

            </div>
            <!-- نهاية أزرار التواصل -->

        </div>
        <!-- نهاية شبكة التواصل -->

    </div>
    <!-- نهاية الحاوية -->

</section>
<!-- نهاية قسم التواصل -->



</main>
<!-- نهاية المحتوى الرئيسي -->



<footer class="footer">
<!-- بداية تذييل الموقع -->

    <div class="container footer-container">
    <!-- حاوية التذييل -->

        <p>
            © <span id="year"></span> عبدالله علي عبده علي الصارم
        </p>
        <!-- حقوق الموقع -->

        <p>
            جميع الحقوق محفوظة
        </p>
        <!-- عبارة الحقوق -->

    </div>
    <!-- نهاية حاوية التذييل -->

</footer>
<!-- نهاية التذييل -->



<button class="back-to-top" id="backToTop" aria-label="العودة إلى الأعلى">
    ↑
</button>
<!-- زر العودة إلى أعلى الصفحة -->


<script src="app.js"></script>
<!-- ربط ملف JavaScript -->

</body>
<!-- نهاية محتوى الصفحة -->

</html>
<!-- نهاية ملف HTML -->
