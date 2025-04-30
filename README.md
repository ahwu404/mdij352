<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>صحيفة الأفق الإلكترونية</title>
    <style>
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #e74c3c;
            --light-color: #ecf0f1;
            --dark-color: #2c3e50;
            --text-color: #333;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            color: var(--text-color);
            line-height: 1.6;
        }
        
        header {
            background-color: var(--primary-color);
            color: white;
            padding: 1rem;
            text-align: center;
        }
        
        nav {
            background-color: var(--dark-color);
            padding: 0.5rem;
        }
        
        nav a {
            color: var(--light-color);
            text-decoration: none;
            margin: 0 1rem;
            padding: 0.5rem;
            transition: all 0.3s;
        }
        
        nav a:hover {
            background-color: var(--secondary-color);
            border-radius: 4px;
        }
        
        section {
            padding: 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        h1, h2, h3 {
            color: var(--primary-color);
        }
        
        img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            margin: 1rem 0;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 1rem 0;
        }
        
        table, th, td {
            border: 1px solid #ddd;
        }
        
        th, td {
            padding: 12px;
            text-align: right;
        }
        
        th {
            background-color: var(--primary-color);
            color: white;
        }
        
        tr:nth-child(even) {
            background-color: #f2f2f2;
        }
        
        form {
            background-color: #f9f9f9;
            padding: 2rem;
            border-radius: 8px;
            max-width: 600px;
            margin: 0 auto;
        }
        
        label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: bold;
        }
        
        input, textarea {
            width: 100%;
            padding: 0.5rem;
            margin-bottom: 1rem;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        
        input[type="submit"], input[type="reset"] {
            width: auto;
            padding: 0.5rem 1rem;
            background-color: var(--primary-color);
            color: white;
            border: none;
            cursor: pointer;
            margin-right: 1rem;
        }
        
        input[type="submit"]:hover, input[type="reset"]:hover {
            background-color: var(--secondary-color);
        }
        
        footer {
            background-color: var(--dark-color);
            color: white;
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
        }
        
        .news-item {
            margin-bottom: 2rem;
            border-bottom: 1px solid #eee;
            padding-bottom: 1rem;
        }
        
        @media (max-width: 768px) {
            nav a {
                display: block;
                margin: 0.5rem 0;
            }
            
            section {
                padding: 1rem;
            }
        }
    </style>
</head>
<body>
    <!-- الشعار والقائمة -->
    <header>
        <h1>صحيفة الأفق الإلكترونية</h1>
        <p>نافذتك على آخر الأخبار المحلية والعالمية</p>
    </header>
    
    <nav>
        <a href="#home">الصفحة الرئيسية</a>
        <a href="#sports">أخبار الرياضة</a>
        <a href="#tech">أخبار التقنية</a>
        <a href="#local">الأخبار المحلية</a>
        <a href="#contact">تواصل معنا</a>
    </nav>

    <!-- الصفحة الرئيسية -->
    <section id="home">
        <h2>أهم الأخبار</h2>
        
        <div class="news-item">
            <h3><a href="#sports">فوز فريق الهلال في نهائي الدوري</a></h3>
            <p>حقق نادي الهلال فوزًا مثيرًا في المباراة النهائية بنتيجة 3-2 ضد الاتحاد، في مباراة مثيرة جمعت بين قطبي الكرة السعودية.</p>
            <img src="https://via.placeholder.com/600x400?text=صورة+مباراة+الهلال" alt="صورة مباراة الهلال">
        </div>
        
        <div class="news-item">
            <h3><a href="#tech">إطلاق هاتف جديد بتقنية الذكاء الاصطناعي</a></h3>
            <p>أعلنت شركة "تِك فون" عن إطلاق هاتفها الجديد الذي يستخدم الذكاء الاصطناعي لتحسين الأداء والتصوير، بميزات غير مسبوقة.</p>
            <img src="https://via.placeholder.com/600x400?text=هاتف+ذكي+جديد" alt="هاتف ذكي جديد">
        </div>
        
        <div class="news-item">
            <h3><a href="#local">مشروع تطوير جديد في وسط المدينة</a></h3>
            <p>تم إطلاق مشروع جديد يهدف إلى تحسين البنية التحتية وزيادة المساحات الخضراء في وسط المدينة، بتكلفة إجمالية تصل إلى 50 مليون ريال.</p>
            <img src="https://via.placeholder.com/600x400?text=مشروع+تطوير+المدينة" alt="مشروع تطوير المدينة">
        </div>
    </section>

    <!-- أخبار الرياضة -->
    <section id="sports">
        <h2>أخبار الرياضة</h2>
        <p>حقق نادي الهلال فوزًا مثيرًا في المباراة النهائية بنتيجة 3-2 ضد الاتحاد، في مباراة ستظل عالقة في أذهان الجماهير لفترة طويلة.</p>
        <img src="https://via.placeholder.com/600x400?text=أخبار+الرياضة" alt="صورة مباراة">
        
        <h3>إحصائيات المباراة</h3>
        <table>
            <tr><th>الفريق</th><th>الأهداف</th><th>التسديدات</th><th>حيازة الكرة</th></tr>
            <tr><td>الهلال</td><td>3</td><td>12</td><td>54%</td></tr>
            <tr><td>الاتحاد</td><td>2</td><td>8</td><td>46%</td></tr>
        </table>
        
        <h3>أهداف المباراة</h3>
        <ul>
            <li>الدقيقة 23: هدف للهلال (سالم الدوسري)</li>
            <li>الدقيقة 37: هدف للاتحاد (رومارينهو)</li>
            <li>الدقيقة 55: هدف للهلال (أوديون إيغالو)</li>
            <li>الدقيقة 72: هدف للاتحاد (عبدالرزاق حمدالله)</li>
            <li>الدقيقة 89: هدف للهلال (أندريه كاريلو)</li>
        </ul>
    </section>

    <!-- أخبار التقنية -->
    <section id="tech">
        <h2>أخبار التقنية</h2>
        <p>أعلنت شركة "تِك فون" عن إطلاق هاتفها الجديد الذي يستخدم الذكاء الاصطناعي لتحسين الأداء والتصوير، بميزات غير مسبوقة في السوق المحلي.</p>
        <img src="https://via.placeholder.com/600x400?text=أخبار+التقنية" alt="هاتف ذكي">
        
        <h3>مقارنة بين الهواتف</h3>
        <table>
            <tr><th>الموديل</th><th>السعر</th><th>المعالج</th><th>الكاميرا</th><th>البطارية</th></tr>
            <tr><td>تك فون AI</td><td>3000 ريال</td><td>Octa-core AI</td><td>108MP</td><td>5000mAh</td></tr>
            <tr><td>جالاكسي X</td><td>2800 ريال</td><td>Snapdragon 888</td><td>64MP</td><td>4500mAh</td></tr>
            <tr><td>آيفون 14</td><td>3500 ريال</td><td>A15 Bionic</td><td>48MP</td><td>3200mAh</td></tr>
        </table>
        
        <h3>مميزات الهاتف الجديد</h3>
        <ul>
            <li>معالج مخصص للذكاء الاصطناعي</li>
            <li>نظام تحسين الأداء الذكي</li>
            <li>كاميرا 108 ميجابكسل مع تحسينات الذكاء الاصطناعي</li>
            <li>بطارية 5000 ملي أمبير مع شحن سريع 65 واط</li>
            <li>شاشة AMOLED بدقة 2K بمعدل تحديث 120 هرتز</li>
        </ul>
    </section>

    <!-- الأخبار المحلية -->
    <section id="local">
        <h2>الأخبار المحلية</h2>
        <p>تم إطلاق مشروع جديد يهدف إلى تحسين البنية التحتية وزيادة المساحات الخضراء في وسط المدينة، وذلك ضمن خطة التنمية المستدامة 2030.</p>
        <img src="https://via.placeholder.com/600x400?text=الأخبار+المحلية" alt="مشروع تطوير">
        
        <h3>تفاصيل المشروع</h3>
        <table>
            <tr><th>العنصر</th><th>القيمة</th></tr>
            <tr><td>المساحة</td><td>50000 متر مربع</td></tr>
            <tr><td>عدد الأشجار المزروعة</td><td>1000 شجرة</td></tr>
            <tr><td>مسارات المشاة</td><td>5 كم</td></tr>
            <tr><td>مواقف السيارات</td><td>300 مكان</td></tr>
            <tr><td>تكلفة المشروع</td><td>50 مليون ريال</td></tr>
            <tr><td>مدة التنفيذ</td><td>18 شهرًا</td></tr>
        </table>
        
        <h3>أهداف المشروع</h3>
        <ul>
            <li>تحسين جودة الحياة للمواطنين</li>
            <li>زيادة المساحات الخضراء في المدينة</li>
            <li>تشجيع المشي والرياضة</li>
            <li>تحسين البنية التحتية</li>
            <li>تعزيز السياحة المحلية</li>
        </ul>
    </section>

    <!-- صفحة تواصل معنا -->
    <section id="contact">
        <h2>تواصل معنا</h2>
        <p>يسعدنا تلقي استفساراتكم واقتراحاتكم عبر النموذج التالي:</p>
        
        <form action="#" method="post">
            <label>الاسم الكامل:
                <input type="text" name="name" required>
            </label>
            
            <label>البريد الإلكتروني:
                <input type="email" name="email" required>
            </label>
            
            <label>رقم الهاتف:
                <input type="tel" name="phone">
            </label>
            
            <label>نوع الرسالة:
                <select name="message_type">
                    <option value="inquiry">استفسار</option>
                    <option value="suggestion">اقتراح</option>
                    <option value="complaint">شكوى</option>
                    <option value="other">أخرى</option>
                </select>
            </label>
            
            <label>الرسالة:
                <textarea name="message" rows="6" required></textarea>
            </label>
            
            <input type="submit" value="إرسال الرسالة">
            <input type="reset" value="مسح النموذج">
        </form>
        
        <h3>معلومات الاتصال</h3>
        <p><strong>العنوان:</strong> الرياض، المملكة العربية السعودية</p>
        <p><strong>الهاتف:</strong> +966 11 123 4567</p>
        <p><strong>البريد الإلكتروني:</strong> info@alofoqnews.com</p>
    </section>

    <!-- التذييل -->
    <footer>
        <p>صحيفة الأفق الإلكترونية - نافذتك على العالم</p>
        <p>تابعنا على وسائل التواصل الاجتماعي: 
            <a href="#" style="color: white;">فيسبوك</a> | 
            <a href="#" style="color: white;">تويتر</a> | 
            <a href="#" style="color: white;">إنستغرام</a> | 
            <a href="#" style="color: white;">يوتيوب</a>
        </p>
        <p>جميع الحقوق محفوظة لصحيفة الأفق © 2025</p>
    </footer>
</body>
</html>
