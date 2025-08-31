[baladiyat_hairambar.html](https://github.com/user-attachments/files/22066767/baladiyat_hairambar.html)
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>بلدية هايرامبار</title>
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    body {
      font-family: 'Cairo', sans-serif;
      margin: 0;
      background-color: #f2f2f2;
      color: #333;
    }
    header {
      background-color: #004080;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    header img {
      height: 70px;
      margin-bottom: 10px;
      display: block;
      margin-right: auto;
      margin-left: auto;
    }
    nav {
      background-color: #0066cc;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.2s;
      display: flex;
      align-items: center;
      gap: 5px;
    }
    nav a:hover {
      color: #ffcc00;
    }
    .hero {
      background-image: url('https://via.placeholder.com/1200x300');
      background-size: cover;
      background-position: center;
      height: 300px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 2em;
      font-weight: bold;
    }
    .section {
      padding: 30px;
      background-color: white;
      margin: 20px auto;
      max-width: 1000px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    footer {
      background-color: #004080;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }
    @media (max-width: 600px) {
      nav {
        flex-direction: column;
        gap: 10px;
      }
      .section {
        padding: 10px;
        margin: 10px;
      }
      .hero {
        font-size: 1.2em;
        height: 150px;
      }
    }
  </style>
</head>
<body>
  <header>
    <img src="شعار البل.jpg" alt="شعار بلدية هايرامبار">
    <h1>بلدية هايرامبار</h1>
    <p>في خدمتكم من أجل تنمية شاملة ومستدامة</p>
  </header>

  <nav>
    <a href="#about"><i class="fas fa-users"></i> من نحن</a>
    <a href="#services"><i class="fas fa-concierge-bell"></i> الخدمات</a>
    <a href="#news"><i class="fas fa-newspaper"></i> الأخبار</a>
    <a href="#contact"><i class="fas fa-envelope"></i> اتصل بنا</a>
    <a href="#complaints"><i class="fas fa-comments"></i> الشكاوى والمقترحات</a>
  </nav>

  <div class="hero">
    مرحبًا بكم في بلدية هايرامبار
  </div>

  <div class="section" id="about">
    <h2>من نحن</h2>
    <p>بلدية هايرامبار هي مؤسسة خدمية تهدف إلى تقديم خدمات إدارية وتنموية للمواطنين، وتعزيز المشاركة المجتمعية من أجل تطوير مستدام وشامل للمنطقة.</p>
  </div>

  <div class="section" id="services">
    <h2>الخدمات البلدية</h2>
    <ul>
      <li>استخراج الوثائق الإدارية</li>
      <li>تنظيم الشكاوى والمقترحات</li>
      <li>رخص البناء والتعمير والأنشطة الاجتماعية والثقافية</li>
      <li>متابعة مشاريع التنمية المحلية</li>
    </ul>
  </div>

  <!-- الأخبار الديناميكية -->
  <div class="section" id="news">
    <h2><i class="fas fa-newspaper"></i> آخر الأخبار</h2>
    <ul id="newsList">
      <li>سيتم قريبًا إطلاق منصة رقمية لتسهيل الحصول على الخدمات عن بُعد.</li>
    </ul>
    <form id="addNewsForm" style="margin-top:15px;">
      <input type="text" id="newsInput" placeholder="أضف خبرًا جديدًا..." required style="width:70%;padding:8px;">
      <button type="submit" style="background:#0066cc;color:#fff;padding:8px 20px;border:none;border-radius:5px;cursor:pointer;">إضافة</button>
    </form>
  </div>

  <div class="section" id="contact">
    <h2>اتصل بنا</h2>
    <p>
      العنوان: وسط مدينة هايرامبار<br>
      الهاتف العمدة:  22246527702<br>
      الهاتف أمين العام:  22248845677<br>
      البريد الإلكتروني: contact@hairambar.gov.mr
    </p>
    <form id="contactForm" style="margin-top:20px;">
      <label for="name">الاسم:</label><br>
      <input type="text" id="name" name="name" required style="width:100%;padding:8px;margin-bottom:10px;"><br>
      <label for="email">البريد الإلكتروني:</label><br>
      <input type="email" id="email" name="email" required style="width:100%;padding:8px;margin-bottom:10px;"><br>
      <label for="message">الرسالة:</label><br>
      <textarea id="message" name="message" required style="width:100%;padding:8px;height:80px;margin-bottom:10px;"></textarea><br>
      <button type="submit" style="background:#004080;color:#fff;padding:10px 30px;border:none;border-radius:5px;cursor:pointer;">إرسال</button>
    </form>
  </div>

  <div class="section" id="complaints">
    <h2><i class="fas fa-comments"></i> الشكاوى والمقترحات</h2>
    <p>يمكنكم إرسال شكواكم أو اقتراحاتكم عبر النموذج التالي:</p>
    <form id="complaintForm" style="margin-top:20px;">
      <label for="complaintName">الاسم:</label><br>
      <input type="text" id="complaintName" name="complaintName" required style="width:100%;padding:8px;margin-bottom:10px;"><br>
      <label for="complaintEmail">البريد الإلكتروني:</label><br>
      <input type="email" id="complaintEmail" name="complaintEmail" required style="width:100%;padding:8px;margin-bottom:10px;"><br>
      <label for="complaintMessage">الشكوى أو الاقتراح:</label><br>
      <textarea id="complaintMessage" name="complaintMessage" required style="width:100%;padding:8px;height:80px;margin-bottom:10px;"></textarea><br>
      <button type="submit" style="background:#0066cc;color:#fff;padding:10px 30px;border:none;border-radius:5px;cursor:pointer;">إرسال</button>
    </form>
  </div>

  <div class="section" id="privacy">
    <h2><i class="fas fa-user-shield"></i> سياسة الخصوصية</h2>
    <p>
      تلتزم بلدية هايرامبار بالحفاظ على سرية بيانات زوار الموقع. لا يتم جمع أي بيانات شخصية إلا بموافقة المستخدم، وتستخدم فقط لتحسين جودة الخدمات أو التواصل معكم عند الحاجة. لن يتم مشاركة بياناتكم مع أي جهة خارجية إلا بموجب القانون الموريتاني أو بطلب رسمي من السلطات المختصة.<br>
      يمكنكم التواصل معنا في أي وقت لطلب حذف أو تعديل بياناتكم الشخصية.
    </p>
  </div>

  <!-- معرض الصور -->
  <div class="section" id="gallery">
    <h2><i class="fas fa-images"></i> معرض الصور</h2>
    <div style="display:flex;flex-wrap:wrap;gap:15px;justify-content:center;">
      <img src="https://via.placeholder.com/200x130?text=صورة+1" alt="صورة 1" style="width:200px;height:130px;border-radius:8px;object-fit:cover;">
      <img src="https://via.placeholder.com/200x130?text=صورة+2" alt="صورة 2" style="width:200px;height:130px;border-radius:8px;object-fit:cover;">
      <img src="https://via.placeholder.com/200x130?text=صورة+3" alt="صورة 3" style="width:200px;height:130px;border-radius:8px;object-fit:cover;">
      <img src="https://via.placeholder.com/200x130?text=صورة+4" alt="صورة 4" style="width:200px;height:130px;border-radius:8px;object-fit:cover;">
    </div>
  </div>

  <div style="margin-top:20px;">
    <iframe
      src="https://www.google.com/maps?q=Hairembar,+Mauritania&hl=ar&z=14&output=embed"
      width="100%" height="300" style="border:0;border-radius:10px;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade">
    </iframe>
  </div>

  <footer>
    &copy; 2025 بلدية هايرامبار - جميع الحقوق محفوظة |
    <a href="#privacy" style="color:#ffcc00;text-decoration:underline;">سياسة الخصوصية</a>
  </footer>
  <script>
    document.getElementById('contactForm').onsubmit = function(e) {
      e.preventDefault();
      alert('تم إرسال رسالتك بنجاح! سنرد عليك قريبًا.');
      this.reset();
    }
    document.getElementById('complaintForm').onsubmit = function(e) {
      e.preventDefault();
      alert('تم إرسال الشكوى أو الاقتراح بنجاح! شكراً لتواصلكم.');
      this.reset();
    }
    document.getElementById('addNewsForm').onsubmit = function(e) {
      e.preventDefault();
      var newsText = document.getElementById('newsInput').value.trim();
      if(newsText) {
        var li = document.createElement('li');
        li.textContent = newsText;
        document.getElementById('newsList').prepend(li);
        this.reset();
      }
    }
  </script>
</body>
</html>

