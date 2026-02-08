<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>تواصلوا معنا - NovaCoode</title>
  <meta name="description" content="تواصلوا مع فريق NovaCoode لحلول برمجية وتطبيقات مخصصة"/>
  
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #0f0f1a;
      color: #e2e8f0;
      line-height: 1.6;
    }
    
    .container {
      max-width: 1100px;
      margin: 0 auto;
      padding: 0 20px;
    }
    
    header {
      background: linear-gradient(135deg, #1e1b4b, #6d28d9, #c026d3);
      color: white;
      text-align: center;
      padding: 100px 20px 80px;
      position: relative;
      overflow: hidden;
    }
    
    header::before {
      content: '';
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background: radial-gradient(circle at 30% 70%, rgba(139, 92, 246, 0.2), transparent 60%);
      pointer-events: none;
    }
    
    header h1 {
      font-size: 3.2rem;
      margin-bottom: 16px;
      text-shadow: 0 0 20px rgba(167, 139, 250, 0.7);
    }
    
    header p {
      font-size: 1.3rem;
      opacity: 0.92;
      max-width: 640px;
      margin: 0 auto;
    }
    
    .contact-section {
      padding: 100px 0 80px;
    }
    
    .contact-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 50px;
      align-items: start;
    }
    
    .info-box, .form-box {
      background: #1e1e38;
      padding: 40px;
      border-radius: 20px;
      box-shadow: 0 10px 40px rgba(0,0,0,0.4),
                  0 0 20px rgba(139, 92, 246, 0.15);
      border: 1px solid rgba(139, 92, 246, 0.2);
    }
    
    .info-box h2, .form-box h2 {
      color: #a78bfa;
      margin-bottom: 28px;
      font-size: 2rem;
    }
    
    .info-item {
      margin-bottom: 24px;
      font-size: 1.1rem;
    }
    
    .info-item strong {
      display: inline-block;
      min-width: 120px;
      color: #c4b5fd;
    }
    
    a {
      color: #c084fc;
      text-decoration: none;
      transition: color 0.2s;
    }
    
    a:hover {
      color: #e9d5ff;
      text-decoration: underline;
    }
    
    .form-group {
      margin-bottom: 28px;
    }
    
    label {
      display: block;
      margin-bottom: 10px;
      font-weight: 600;
      color: #c4b5fd;
    }
    
    input, textarea {
      width: 100%;
      padding: 14px 16px;
      border: 1px solid #4c1d95;
      border-radius: 10px;
      font-size: 1rem;
      background: #111827;
      color: #f3f4f6;
      transition: all 0.25s;
    }
    
    input:focus, textarea:focus {
      outline: none;
      border-color: #a78bfa;
      box-shadow: 0 0 0 4px rgba(167, 139, 250, 0.25);
      background: #1e1e38;
    }
    
    button {
      background: linear-gradient(90deg, #7c3aed, #c026d3);
      color: white;
      border: none;
      padding: 16px 40px;
      font-size: 1.15rem;
      border-radius: 10px;
      cursor: pointer;
      transition: all 0.3s;
      font-weight: bold;
      box-shadow: 0 4px 15px rgba(192, 38, 211, 0.4);
    }
    
    button:hover {
      transform: translateY(-3px);
      box-shadow: 0 10px 25px rgba(192, 38, 211, 0.6);
    }
    
    .success-msg {
      color: #34d399;
      font-weight: bold;
      margin-top: 24px;
      display: none;
      background: rgba(52, 211, 153, 0.15);
      padding: 12px;
      border-radius: 10px;
      text-align: center;
    }
    
    footer {
      text-align: center;
      padding: 50px 0;
      color: #94a3b8;
      border-top: 1px solid #2d3748;
    }
    
    @media (max-width: 768px) {
      .contact-grid {
        grid-template-columns: 1fr;
        gap: 40px;
      }
      
      header h1 {
        font-size: 2.6rem;
      }
      
      header {
        padding: 80px 20px 60px;
      }
    }
  </style>
</head>
<body>

  <header>
    <div class="container">
      <h1>تواصلوا مع NovaCoode</h1>
      <p>نساعدك في تحويل فكرتك إلى منتج رقمي مميز. تواصل معنا الآن ونبدأ معًا!</p>
    </div>
  </header>

  <section class="contact-section">
    <div class="container">
      <div class="contact-grid">

        <!-- معلومات التواصل -->
        <div class="info-box">
          <h2>معلومات التواصل</h2>
          
          <div class="info-item">
            <strong>البريد الإلكتروني:</strong>
            <a href="mailto:novacoode@gmail.com">novacoode@gmail.com</a>
          </div>
          
          <div class="info-item">
            <strong>واتساب / الهاتف:</strong>
            <a href="https://wa.me/201156868326" target="_blank">0115 686 8326</a>
          </div>
          
          <div class="info-item">
            <strong>ساعات العمل:</strong>
            9:00 ص – 10:00 م (طوال الأسبوع)
          </div>
          
          <div class="info-item">
            <strong>الرد المتوقع:</strong>
            خلال ساعات قليلة في أغلب الأحيان
          </div>
        </div>

        <!-- نموذج التواصل -->
        <div class="form-box">
          <h2>أرسل لنا رسالتك</h2>
          
          <form id="contact-form" action="https://formspree.io/f/mvzbolrl" method="POST">
            <div class="form-group">
              <label for="name">الاسم</label>
              <input type="text" id="name" name="name" required placeholder="اكتب اسمك هنا"/>
            </div>
            
            <div class="form-group">
              <label for="email">البريد الإلكتروني</label>
              <input type="email" id="email" name="email" required placeholder="example@domain.com"/>
            </div>
            
            <div class="form-group">
              <label for="phone">رقم الجوال (اختياري)</label>
              <input type="tel" id="phone" name="phone" placeholder="011xxxxxxxx"/>
            </div>
            
            <div class="form-group">
              <label for="message">رسالتك / استفسارك</label>
              <textarea id="message" name="message" rows="6" required placeholder="صف مشروعك أو اطرح استفسارك..."></textarea>
            </div>

            <!-- اختياري: تحسين عنوان الرسالة في الإيميل -->
            <input type="hidden" name="_subject" value="استفسار جديد من موقع NovaCoode" />

            <!-- اختياري: حماية بسيطة من البوتات -->
            <input type="text" name="_gotcha" style="display:none" />
            
            <button type="submit">إرسال الرسالة</button>
            
            <div class="success-msg" id="success">تم إرسال رسالتك بنجاح! سنرد عليك قريبًا.</div>
          </form>
        </div>

      </div>
    </div>
  </section>

  <footer>
    <p>© 2025 NovaCoode - جميع الحقوق محفوظة</p>
  </footer>

  <script>
    document.getElementById('contact-form').addEventListener('submit', function(e) {
      // يمكنك الاحتفاظ بالكود ده لعرض رسالة فورية قبل ما Formspree يعيد التوجيه
      document.getElementById('success').style.display = 'block';
      setTimeout(() => {
        document.getElementById('success').style.display = 'none';
      }, 6000);
      
      // Formspree هيتعامل مع الإرسال تلقائيًا
      // لا حاجة لـ e.preventDefault() هنا إلا لو عايز تتحكم أكتر
    });
  </script>

</body>
</html>
