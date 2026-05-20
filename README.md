<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>مُزّمل للعلوم | Muzzamil lil-Uloom - Online Madrasah & Academy</title>
  <meta name="description" content="مُزّمل للعلوم: تعليم شرعي، تحفيظ قرآن، ودروس مدرسية من 9 إلى UPSC عبر الإنترنت">
  <style>
    :root {
      --primary: #0F4C3A;
      --accent: #C9A961;
      --light: #F8F5F0;
      --dark: #1A1A1A;
      --blue: #1E3A8A;
    }
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { 
      font-family: 'Tahoma', 'Segoe UI', sans-serif; 
      background: var(--light); 
      color: var(--dark);
      line-height: 1.8;
    }
    .container { max-width: 1200px; margin: 0 auto; padding: 0 20px; }
    header { 
      background: linear-gradient(135deg, var(--primary), #0a3025); 
      color: white; 
      padding: 70px 0; 
      text-align: center;
    }
    header h1 { font-size: 3rem; margin-bottom: 10px; }
    header p { font-size: 1.2rem; opacity: 0.9; }
    .btn {
      display: inline-block;
      background: var(--accent);
      color: var(--dark);
      padding: 12px 28px;
      margin: 10px 5px 0;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }
    .btn-outline {
      background: transparent;
      border: 2px solid white;
      color: white;
    }
    .btn:hover { transform: translateY(-2px); }
    section { padding: 60px 0; }
    h2 { 
      color: var(--primary); 
      font-size: 2.2rem; 
      margin-bottom: 20px;
      text-align: center;
    }
    .section-intro {
      text-align: center;
      max-width: 700px;
      margin: 0 auto 40px;
      color: #444;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.05);
      border-right: 4px solid var(--accent);
    }
    .card h3 { 
      color: var(--primary); 
      margin-bottom: 15px;
      font-size: 1.3rem;
    }
    .card ul { 
      list-style: none; 
      padding-right: 5px;
    }
    .card li {
      padding: 6px 0;
      border-bottom: 1px dashed #eee;
    }
    .card li:last-child { border: none; }
    .badge {
      background: var(--blue);
      color: white;
      font-size: 0.8rem;
      padding: 3px 8px;
      border-radius: 4px;
      margin-right: 6px;
    }
    .two-col {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 40px;
    }
    @media(max-width: 768px) {
      .two-col { grid-template-columns: 1fr; }
      header h1 { font-size: 2.2rem; }
    }
    footer {
      background: var(--dark);
      color: white;
      text-align: center;
      padding: 40px 0;
      margin-top: 40px;
    }
    .contact-box {
      background: white;
      padding: 40px;
      border-radius: 12px;
      text-align: center;
      box-shadow: 0 4px 20px rgba(0,0,0,0.08);
    }
    .contact-box a { color: var(--primary); font-weight: bold; text-decoration: none; }
  </style>
</head>
<body>

  <header>
    <div class="container">
      <h1>مُزّمل للعلوم</h1>
      <p>Muzzamil lil-Uloom | Online Madrasah & Academy</p>
      <p>من النظرة إلى UPSC: العلوم الشرعية والتعليم الأكاديمي في مكان واحد</p>
      <a href="#islamic" class="btn">العلوم الشرعية</a>
      <a href="#academic" class="btn btn-outline">الدراسة الأكاديمية</a>
    </div>
  </header>

  <section id="islamic">
    <div class="container">
      <h2>قسم العلوم الشرعية</h2>
      <p class="section-intro">برامج تأصيلية من المبتدئين إلى درجة الفضيلة، بإشراف علمي وإجازات معتمدة</p>
      <div class="grid">
        <div class="card">
          <h3>القرآن الكريم</h3>
          <ul>
            <li>ناظرة قرآن - Nazra Quran</li>
            <li>حفظ القرآن - Hifz e Quran</li>
            <li>تجويد وقراءات - Tajweed & Qirat</li>
            <li>تفسير وترجمة القرآن - Tafseer & Tarjuma</li>
          </ul>
        </div>
        <div class="card">
          <h3>اللغات الإسلامية</h3>
          <ul>
            <li>دورة اللغة العربية - Arabic Language Course</li>
            <li>دورة القراءة والكتابة الأردية - Urdu Reading & Writing</li>
          </ul>
        </div>
        <div class="card">
          <h3>العلوم الأساسية</h3>
          <ul>
            <li>دينيات - Deeniyat Basic Islamic Studies</li>
            <li>فقه وحديث دورة مختصرة - Fiqh & Hadith Short Course</li>
          </ul>
        </div>
        <div class="card">
          <h3>الدراسات العليا الشرعية</h3>
          <ul>
            <li>عالم / عالمة - Alim / Alimah Course</li>
            <li>فضيلة - Fazilat Advance Alim Course</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <section id="academic" style="background: white;">
    <div class="container">
      <h2>قسم التعليم الأكاديمي</h2>
      <p class="section-intro">دروس تقوية ومناهج مدرسية وجامعية + تجهيز للاختبارات التنافسية الكبرى</p>
      <div class="two-col">
        <div class="card">
          <h3>دروس التقوية <span class="badge">Tuition</span></h3>
          <ul>
            <li>الصف التاسع - 9th State / CBSE</li>
            <li>الصف العاشر - 10th State / CBSE</li>
            <li>الصف الحادي عشر - 11th State / CBSE</li>
            <li>الصف الثاني عشر - 12th State / CBSE</li>
            <li>11th + JEE / NEET</li>
            <li>12th + JEE / NEET</li>
          </ul>
        </div>
        <div class="card">
          <h3>التعليم المدرسي <span class="badge">Schooling</span></h3>
          <ul>
            <li>SSLC - 10th Equivalent</li>
            <li>2nd PUC - 12th Equivalent</li>
            <li>درجة جامعية - Degree Any Stream</li>
          </ul>
        </div>
        <div class="card">
          <h3>الاختبارات التنافسية</h3>
          <ul>
            <li>JEE / NEET / NDA / CUET</li>
            <li>Graduation BSc / BCA + CUET + IIT-JAM</li>
            <li>Post Graduation MSc / MCA + NET / JRF</li>
            <li>Engineering BE / B.Tech + GATE</li>
            <li>UPSC-CSE IAS / IPS</li>
          </ul>
        </div>
        <div class="card">
          <h3>مميزات القسم الأكاديمي</h3>
          <ul>
            <li>مدرسون متخصصون لكل مادة</li>
            <li>حصص مباشرة + تسجيلات</li>
            <li>اختبارات دورية وتحليل أداء</li>
            <li>متابعة مع ولي الأمر شهرياً</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <section id="why">
    <div class="container">
      <h2>لماذا مُزّمل للعلوم؟</h2>
      <div class="grid">
        <div class="card"><h3>منهج متكامل</h3><p>نجمع بين حفظ القرآن والتميز في JEE/UPSC بدون تعارض.</p></div>
        <div class="card"><h3>هيئة تدريس مزدوجة</h3><p>علماء مجازون + أساتذة IIT/NEET/UPSC خبرة.</p></div>
        <div class="card"><h3>مرونة كاملة</h3><p>اختر حصص صباحية/مسائية. مناسب للطلاب في الهند والخليج.</p></div>
        <div class="card"><h3>رسوم ميسرة</h3><p>باقات شهرية وسنوية مع خصم للإخوة وطلاب العلم.</p></div>
      </div>
    </div>
  </section>

  <section id="contact" style="background: white;">
    <div class="container">
      <div class="contact-box">
        <h2>ابدأ رحلتك اليوم</h2>
        <p>للتسجيل والاستشارة المجانية:</p>
        <p style="font-size: 1.3rem; margin: 15px 0;">واتساب: <a href="https://wa.me/91XXXXXXXXXX">+91 XXX XXX XXXX</a></p>
        <p>البريد: <a href="mailto:admissions@muzzamilliluloom.com">admissions@muzzamilliluloom.com</a></p>
        <a href="https://wa.me/91XXXXXXXXXX" class="btn">احجز مقعدك الآن</a>
      </div>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>© 2026 مُزّمل للعلوم - Muzzamil lil-Uloom</p>
      <p>Online Madrasah & Academy | من النظرة إلى UPSC</p>
    </div>
  </footer>

</body>
</html>
