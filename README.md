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
                <img src="https://www.freepik.com/free-vector/books-stack-realistic_1537673.htm#fromView=keyword&page=1&position=0&uuid=69dc745a-485e-4375-a5cc-d9525b9f1f93&query=Book+jpg" alt="Course Image 1">
            </div>
            <div class="gallery-item" data-aos="zoom-in">
                <video controls>
                    <source src="https://www.youtube.com/shorts/lJVjm2ewhrs" type="video/mp4">
                </video>
            </div>
            <div class="gallery-item" data-aos="zoom-in">
                <img src="https://www.freepik.com/free-photo/red-hardcover-book-front-cover_1056320.htm#fromView=keyword&page=1&position=2&uuid=69dc745a-485e-4375-a5cc-d9525b9f1f93&query=Book+jpg" alt="Course Image 2">
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
                <h3>MER1</h3>
                <p>خبير تسويق العلامات التجارية</p>
            </div>
            <div class="team-card" data-aos="flip-left">
                <img src="images/team1.jpg" alt="Team Member">
                <h3>rihab</h3>
                <p>مصممة محتوى وميديا</p>
            </div>
            <div class="team-card" data-aos="flip-left">
                <img src="data:image/jpeg;base64,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 " alt="Team Member">
                <h3>MER</h3>
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
            <input type="text" placeholder=  https://www.facebook.com/XxmerxX1/required>
            
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
