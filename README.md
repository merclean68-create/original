[style.css](https://github.com/user-attachments/files/24224018/style.css)[script.js](https://github.com/user-attachments/files/24224014/script.js)[nouveau 1.txt](https://github.com/user-attachments/files/24224011/nouveau.1.txt)
brand-school/
│
├─ index.html
├─ style.css
├─ script.js
├─ images/
│   ├─ course1.jpg
│   ├─ course2.jpg
│   └─ team1.jpg
├─ videos/
│   └─ course-intro.mp4
[index.html](https://github.com/user-attachments/files/24224013/index.html)
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مدرسة العلامات التجارية</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.css" rel="stylesheet">
</head>
<body>

<!-- رأس الموقع -->
<header>
    <div class="container">
        <h1>مدرسة العلامات التجارية</h1>
        <nav>
            <ul>
                <li><a href="#about">من نحن</a></li>
                <li><a href="#courses">الدورات</a></li>
                <li><a href="#gallery">معرض الدورة</a></li>
                <li><a href="#team">فريقنا</a></li>
                <li><a href="#contact">تواصل معنا</a></li>
            </ul>
        </nav>
    </div>
</header>

<!-- القسم الترحيبي -->
<section class="hero">
    <div class="container" data-aos="fade-up">
        <h2>تعلم فن تسليط الضوء على العلامات التجارية</h2>
        <p>نحن نعلمك استراتيجيات تسويق العلامات التجارية بطريقة عملية ومبتكرة.</p>
        <a href="#courses" class="btn">ابدأ التعلم الآن</a>
    </div>
</section>

<!-- من نحن -->
<section id="about" class="about" data-aos="fade-right">
    <div class="container">
        <h2>من نحن</h2>
        <p>مدرستنا متخصصة في تعليم طرق إبراز العلامات التجارية، إنشاء محتوى جذاب، وفهم سلوك العملاء للوصول للنجاح.</p>
    </div>
</section>

<!-- الدورات -->
<section id="courses" class="courses" data-aos="fade-left">
    <div class="container">
        <h2>الدورات التدريبية</h2>
        <div class="course-cards">
            <div class="course-card" data-aos="zoom-in">
                <h3>تسويق العلامات التجارية</h3>
                <p>تعلم استراتيجيات بناء وترويج العلامات التجارية بشكل احترافي.</p>
            </div>
            <div class="course-card" data-aos="zoom-in">
                <h3>تصميم المحتوى</h3>
                <p>إبداع محتوى جذاب ومؤثر على منصات التواصل الاجتماعي.</p>
            </div>
            <div class="course-card" data-aos="zoom-in">
                <h3>تحليل السوق</h3>
                <p>فهم العملاء والسوق لتحسين نتائج العلامات التجارية.</p>
            </div>
        </div>
        <div class="enroll" data-aos="fade-up">
            <h3>احجز دورتك الآن</h3>
            <div id="paypal-button-container"></div>
        </div>
    </div>
</section>

<!-- معرض الدورة -->
<section id="gallery" class="gallery" data-aos="fade-up">
    <div class="container">
        <h2>معرض الدورة</h2>
        <div class="gallery-items">
            <div class="gallery-item" data-aos="zoom-in">
                <img src="images/course1.jpg" alt="Course Image 1">
            </div>
            <div class="gallery-item" data-aos="zoom-in">
                <video controls>
                    <source src="videos/course-intro.mp4" type="video/mp4">
                </video>
            </div>
            <div class="gallery-item" data-aos="zoom-in">
                <img src="images/course2.jpg" alt="Course Image 2">
            </div>
        </div>
    </div>
</section>

<!-- فريقنا -->
<section id="team" class="team" data-aos="fade-left">
    <div class="container">
        <h2>فريقنا</h2>
        <div class="team-cards">
            <div class="team-card" data-aos="flip-left">
                <img src="images/team1.jpg" alt="Team Member">
                <h3>أحمد</h3>
                <p>خبير تسويق العلامات التجارية</p>
            </div>
            <div class="team-card" data-aos="flip-left">
                <img src="images/team1.jpg" alt="Team Member">
                <h3>ليلى</h3>
                <p>مصممة محتوى وميديا</p>
            </div>
            <div class="team-card" data-aos="flip-left">
                <img src="images/team1.jpg" alt="Team Member">
                <h3>سامي</h3>
                <p>محلل سوق واستراتيجيات</p>
            </div>
        </div>
    </div>
</section>

<!-- تواصل معنا -->
<section id="contact" class="contact" data-aos="fade-up">
    <div class="container">
        <h2>تواصل معنا</h2>
        <form>
            <input type="text" placeholder="الاسم" required>
            <input type="email" placeholder="البريد الإلكتروني" required>
            <textarea placeholder="رسالتك" required></textarea>
            <button type="submit">إرسال</button>
        </form>
    </div>
</section>

<!-- تذييل الموقع -->
<footer>
    <div class="container">
        <p>&copy; 2025 مدرسة العلامات التجارية. كل الحقوق محفوظة.</p>
    </div>
</footer>

<script src="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.js"></script>
<script src="script.js"></script>
<script src="https://www.paypal.com/sdk/js?client-id=YOUR_CLIENT_ID&currency=USD"></script>
<script>
  AOS.init({ duration: 1000, once: true });

  paypal.Buttons({
      createOrder: function(data, actions) {
          return actions.order.create({
              purchase_units: [{ amount: { value: '50.00' } }]
          });
      },
      onApprove: function(data, actions) {
          return actions.order.capture().then(function(details) {
              alert('تم الدفع بنجاح! شكراً لك ' + details.payer.name.given_name);
          });
      }
  }).render('#paypal-button-container');
</script>
[Upload// تغيير الألوان ديناميكياً
function changeTheme(primary, secondary) {
    document.documentElement.style.setProperty('--primary-color', primary);
    document.documentElement.style.setProperty('--secondary-color', secondary);
}
ing script.js…]()

[Uploading style.cs:root {
    --primary-color: #0d6efd;
    --secondary-color: #ffc107;
}

body {
    font-family: 'Cairo', sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    direction: rtl;
    color: #333;
}

/* رأس الموقع */
header {
    background: var(--primary-color);
    color: #fff;
    padding: 20px 0;
}
header h1 { text-align: center; margin: 0; }
header nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
    padding: 0;
}
header nav ul li { margin: 0 15px; }
header nav ul li a {
    color: #fff; text-decoration: none; font-weight: bold;
}

/* القسم الترحيبي */
.hero {
    background: url('images/course1.jpg') no-repeat center center/cover;
    color: #fff;
    text-align: center;
    padding: 150px 0;
}
.hero .btn {
    display: inline-block;
    padding: 10px 25px;
    background: var(--secondary-color);
    color: #333;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
    margin-top: 20px;
}

/* الأقسام */
section { padding: 80px 0; text-align: center; }
.course-cards, .team-cards, .gallery-items { display: flex; flex-wrap: wrap; gap: 20px; justify-content: center; }
.course-card, .team-card, .gallery-item {
    background: #f7f7f7;
    padding: 20px;
    border-radius: 10px;
    width: 250px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}
.team-card img { width: 100%; border-radius: 10px; }
.gallery-item img, .gallery-item video { width: 100%; border-radius: 10px; }

/* النموذج */
.contact form { display: flex; flex-direction: column; max-width: 500px; margin: auto; }
.contact input, .contact textarea { margin-bottom: 15px; padding: 10px; border-radius: 5px; border: 1px solid #ccc; }
.contact button { padding: 10px; border: none; background: var(--primary-color); color: #fff; font-weight: bold; cursor: pointer; border-radius: 5px; }

/* التذييل */
footer { background: #333; color: #fff; padding: 20px 0; }

/* Theme Switcher */
.theme-switcher { text-align: center; margin: 30px 0; }
.theme-switcher button {
    padding: 10px 15px;
    margin: 0 5px;
    border: none;
    cursor: pointer;
    border-radius: 5px;
    font-weight: bold;
    color: #fff;
}
s…]()

![Uploading ChatGPT Image 18 déc. 2025, 00_32_34.png…]()

</body>
</html>
