# MADNI-REAL-ESTATE-AGENCY-
ہمارے ہاں جائیداد کی خرید وفروخت کی جاتی ہے 
‎<!DOCTYPE html>
‎<html lang="ur" dir="rtl">
‎<head>
‎    <meta charset="UTF-8">
‎    <meta name="viewport" content="width=device-width, initial-scale=1.0">
‎    <title>Madani Real Estate Agency | مدنی ریئل اسٹیٹ ایجنسی</title>
‎    <link href="https://fonts.googleapis.com/css2?family=Noto+Nastaliq+Urdu:wght@400;600;700&family=Amiri:wght@400;700&display=swap" rel="stylesheet">
‎    <style>
‎        * {
‎            margin: 0;
‎            padding: 0;
‎            box-sizing: border-box;
‎        }
‎
‎        :root {
‎            --primary: #1e3a5f;
‎            --secondary: #c9a227;
‎            --accent: #2c5282;
‎            --text: #333;
‎            --light: #f8fafc;
‎        }
‎
‎        body {
‎            font-family: 'Amiri', 'Noto Nastaliq Urdu', serif;
‎            background-color: var(--light);
‎            color: var(--text);
‎            line-height: 1.8;
‎        }
‎
‎        header {
‎            background: linear-gradient(135deg, var(--primary) 0%, var(--accent) 100%);
‎            color: white;
‎            padding: 1rem 2rem;
‎            position: fixed;
‎            width: 100%;
‎            top: 0;
‎            z-index: 1000;
‎            box-shadow: 0 2px 20px rgba(0,0,0,0.1);
‎        }
‎
‎        .header-content {
‎            max-width: 1200px;
‎            margin: 0 auto;
‎            display: flex;
‎            justify-content: space-between;
‎            align-items: center;
‎        }
‎
‎        .logo-section {
‎            display: flex;
‎            align-items: center;
‎            gap: 1rem;
‎        }
‎
‎        .logo-img {
‎            width: 70px;
‎            height: 70px;
‎            border-radius: 50%;
‎            border: 3px solid white;
‎            background: white;
‎            object-fit: contain;
‎            padding: 5px;
‎        }
‎
‎        .logo-text h1 {
‎            font-size: 1.4rem;
‎            color: white;
‎            margin-bottom: 0.2rem;
‎        }
‎
‎        .logo-text p {
‎            font-size: 0.8rem;
‎            opacity: 0.9;
‎        }
‎
‎        nav ul {
‎            list-style: none;
‎            display: flex;
‎            gap: 1.5rem;
‎        }
‎
‎        nav a {
‎            color: white;
‎            text-decoration: none;
‎            padding: 0.5rem 1rem;
‎            border-radius: 20px;
‎            transition: all 0.3s;
‎            font-size: 0.95rem;
‎        }
‎
‎        nav a:hover {
‎            background: var(--secondary);
‎            color: var(--primary);
‎        }
‎
‎        .hero {
‎            margin-top: 90px;
‎            position: relative;
‎            height: 500px;
‎            overflow: hidden;
‎        }
‎
‎        .hero img {
‎            width: 100%;
‎            height: 100%;
‎            object-fit: cover;
‎        }
‎
‎        .hero-overlay {
‎            position: absolute;
‎            top: 0;
‎            left: 0;
‎            width: 100%;
‎            height: 100%;
‎            background: linear-gradient(to bottom, rgba(0,0,0,0.4), rgba(0,0,0,0.7));
‎            display: flex;
‎            align-items: center;
‎            justify-content: center;
‎            text-align: center;
‎            color: white;
‎        }
‎
‎        .hero-content h2 {
‎            font-size: 2.5rem;
‎            margin-bottom: 1rem;
‎        }
‎
‎        .hero-content p {
‎            font-size: 1.2rem;
‎            max-width: 600px;
‎            margin: 0 auto 2rem;
‎        }
‎
‎        .cta-button {
‎            display: inline-block;
‎            padding: 1rem 2rem;
‎            background: var(--secondary);
‎            color: var(--primary);
‎            text-decoration: none;
‎            border-radius: 30px;
‎            font-weight: bold;
‎            transition: all 0.3s;
‎        }
‎
‎        .cta-button:hover {
‎            transform: translateY(-3px);
‎            box-shadow: 0 10px 20px rgba(0,0,0,0.2);
‎        }
‎
‎        .container {
‎            max-width: 1200px;
‎            margin: 0 auto;
‎            padding: 3rem 1rem;
‎        }
‎
‎        .section-title {
‎            text-align: center;
‎            font-size: 2rem;
‎            color: var(--primary);
‎            margin-bottom: 2rem;
‎            position: relative;
‎            padding-bottom: 0.5rem;
‎        }
‎
‎        .section-title::after {
‎            content: '';
‎            position: absolute;
‎            bottom: 0;
‎            left: 50%;
‎            transform: translateX(-50%);
‎            width: 80px;
‎            height: 3px;
‎            background: var(--secondary);
‎        }
‎
‎        .about-section {
‎            background: white;
‎            padding: 3rem 0;
‎            margin-bottom: 2rem;
‎        }
‎
‎        .about-content {
‎            display: grid;
‎            grid-template-columns: 1fr 1fr;
‎            gap: 2rem;
‎            align-items: center;
‎        }
‎
‎        .about-text p {
‎            font-size: 1rem;
‎            margin-bottom: 1rem;
‎            text-align: justify;
‎        }
‎
‎        .about-image img {
‎            width: 100%;
‎            border-radius: 10px;
‎            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
‎        }
‎
‎        .properties-grid {
‎            display: grid;
‎            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
‎            gap: 2rem;
‎            margin-top: 2rem;
‎        }
‎
‎        .property-card {
‎            background: white;
‎            border-radius: 10px;
‎            overflow: hidden;
‎            box-shadow: 0 5px 15px rgba(0,0,0,0.08);
‎            transition: all 0.3s;
‎        }
‎
‎        .property-card:hover {
‎            transform: translateY(-5px);
‎            box-shadow: 0 10px 30px rgba(0,0,0,0.15);
‎        }
‎
‎        .property-image {
‎            width: 100%;
‎            height: 220px;
‎            object-fit: cover;
‎        }
‎
‎        .property-content {
‎            padding: 1.5rem;
‎        }
‎
‎        .property-title {
‎            font-size: 1.3rem;
‎            color: var(--primary);
‎            margin-bottom: 0.8rem;
‎            border-bottom: 2px solid var(--secondary);
‎            padding-bottom: 0.5rem;
‎        }
‎
‎        .property-description {
‎            color: #555;
‎            font-size: 0.95rem;
‎            line-height: 1.7;
‎        }
‎
‎        .contact-btn {
‎            display: inline-block;
‎            margin-top: 1rem;
‎            padding: 0.5rem 1.2rem;
‎            background: var(--primary);
‎            color: white;
‎            text-decoration: none;
‎            border-radius: 20px;
‎            font-size: 0.9rem;
‎        }
‎
‎        .founder-section {
‎            background: linear-gradient(135deg, var(--primary) 0%, var(--accent) 100%);
‎            color: white;
‎            padding: 3rem 0;
‎            margin: 2rem 0;
‎        }
‎
‎        .founder-content {
‎            display: grid;
‎            grid-template-columns: 1fr 1fr;
‎            gap: 3rem;
‎            align-items: center;
‎            max-width: 1200px;
‎            margin: 0 auto;
‎            padding: 0 1rem;
‎        }
‎
‎        .founder-image {
‎            text-align: center;
‎        }
‎
‎        .founder-image img {
‎            width: 300px;
‎            height: 300px;
‎            object-fit: cover;
‎            border-radius: 50%;
‎            border: 5px solid var(--secondary);
‎        }
‎
‎        .founder-info h3 {
‎            font-size: 2rem;
‎            color: var(--secondary);
‎            margin-bottom: 0.5rem;
‎        }
‎
‎        .founder-info .title {
‎            font-size: 1.1rem;
‎            opacity: 0.9;
‎            margin-bottom: 1rem;
‎        }
‎
‎        .phone-number {
‎            display: inline-block;
‎            font-size: 1.8rem;
‎            color: var(--secondary);
‎            text-decoration: none;
‎            font-weight: bold;
‎            margin-top: 1rem;
‎            background: rgba(255,255,255,0.1);
‎            padding: 0.8rem 1.5rem;
‎            border-radius: 10px;
‎            border: 2px solid var(--secondary);
‎        }
‎
‎        .office-section {
‎            background: white;
‎            padding: 3rem 0;
‎        }
‎
‎        .office-content {
‎            display: grid;
‎            grid-template-columns: 1fr 1fr;
‎            gap: 2rem;
‎            align-items: center;
‎        }
‎
‎        .office-image img {
‎            width: 100%;
‎            border-radius: 10px;
‎            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
‎        }
‎
‎        footer {
‎            background: var(--primary);
‎            color: white;
‎            text-align: center;
‎            padding: 2rem 1rem;
‎        }
‎
‎        .footer-content h3 {
‎            color: var(--secondary);
‎            font-size: 1.5rem;
‎            margin-bottom: 1rem;
‎        }
‎
‎        .contact-info {
‎            margin: 1rem 0;
‎        }
‎
‎        .contact-info p {
‎            margin: 0.3rem 0;
‎        }
‎
‎        @media (max-width: 768px) {
‎            .header-content {
‎                flex-direction: column;
‎                gap: 1rem;
‎            }
‎
‎            .hero {
‎                height: 400px;
‎                margin-top: 140px;
‎            }
‎
‎            .about-content,
‎            .founder-content,
‎            .office-content {
‎                grid-template-columns: 1fr;
‎            }
‎
‎            .founder-image img {
‎                width: 200px;
‎                height: 200px;
‎            }
‎
‎            .phone-number {
‎                font-size: 1.4rem;
‎            }
‎        }
‎    </style>
‎</head>
‎<body>
‎
‎    <header>
‎        <div class="header-content">
‎            <div class="logo-section">
‎                <img src="/mnt/kimi/upload/1000001601.jpg" alt="Madani Real Estate Logo" class="logo-img">
‎                <div class="logo-text">
‎                    <h1>مدنی ریئل اسٹیٹ ایجنسی</h1>
‎                    <p>Madani Real Estate Agency</p>
‎                </div>
‎            </div>
‎            <nav>
‎                <ul>
‎                    <li><a href="#home">Home</a></li>
‎                    <li><a href="#about">About</a></li>
‎                    <li><a href="#properties">Properties</a></li>
‎                    <li><a href="#founder">Founder</a></li>
‎                    <li><a href="#contact">Contact</a></li>
‎                </ul>
‎            </nav>
‎        </div>
‎    </header>
‎
‎    <section id="home" class="hero">
‎        <img src="/mnt/kimi/upload/1000005499.jpg" alt="Madani Real Estate">
‎        <div class="hero-overlay">
‎            <div class="hero-content">
‎                <h2>مدنی ریئل اسٹیٹ ایجنسی</h2>
‎                <p>یہاں پر آپ کو مختلف  مقدار پر مختلف پلیسز میں مناسب قیمت پر زمینیں مل سکتی ہیں</p>
‎                <a href="#properties" class="cta-button">View Properties</a>
‎            </div>
‎        </div>
‎    </section>
‎
‎    <section id="about" class="about-section">
‎        <div class="container">
‎            <h2 class="section-title">ہمارے بارے میں</h2>
‎            <div class="about-content">
‎                <div class="about-text">
‎                    <p>مدنی ریئل اسٹیٹ ایجنسی آپ کی خدمت میں حاضر ہے۔ ہمارا مقصد آپ کو مناسب قیمت پر بہترین جگہوں پر زمینیں فراہم کرنا ہے۔</p>
‎                    <p>ہمارے پاس مختلف ہاؤسنگ سکیمز میں پلاٹ دستیاب ہیں جن میں المدینہ ہاؤسنگ سکیم بلوچ آباد اور البدر ہاؤسنگ سکیم کلاتک شامل ہیں۔</p>
‎                </div>
‎                <div class="about-image">
‎                    <img src="/mnt/kimi/upload/1000005491.jpg" alt="About">
‎                </div>
‎            </div>
‎        </div>
‎    </section>
‎
‎    <section id="properties" class="container">
‎        <h2 class="section-title">ہمارے پروجیکٹس</h2>
‎        <div class="properties-grid">
‎            <div class="property-card">
‎                <img src="/mnt/kimi/upload/1000005492.jpg" alt="Al Madina 600" class="property-image">
‎                <div class="property-content">
‎                    <h3 class="property-title">المدینہ ہاؤسنگ - 600 گز</h3>
‎                    <p class="property-description">سائز 90×60۔ دونوں اطراف پلازہ اور 30 فٹ کا روڈ۔ مناسب قیمت پر دستیاب۔</p>
‎                    <a href="tel:032075963489" class="contact-btn">📞 032075963489</a>
‎                </div>
‎            </div>
‎            <div class="property-card">
‎                <img src="/mnt/kimi/upload/1000005494.jpg" alt="Al Madina 500" class="property-image">
‎                <div class="property-content">
‎                    <h3 class="property-title">المدینہ ہاؤسنگ - 500 گز</h3>
‎                    <p class="property-description">سائز 67×67۔ بیچ میں 25 فٹ کا روڈ۔ بہترین لوکیشن۔</p>
‎                    <a href="tel:032075963489" class="contact-btn">📞 032075963489</a>
‎                </div>
‎            </div>
‎            <div class="property-card">
‎                <img src="/mnt/kimi/upload/1000005498.jpg" alt="Al Badar" class="property-image">
‎                <div class="property-content">
‎                    <h3 class="property-title">البدر ہاؤسنگ کلاتک</h3>
‎                    <p class="property-description">مسجد اور روڈ کا خاص انتظام۔ 25 فٹ کا راستہ۔</p>
‎                    <a href="tel:032075963489" class="contact-btn">📞 032075963489</a>
‎                </div>
‎            </div>
‎        </div>
‎    </section>
‎
‎    <section id="founder" class="founder-section">
‎        <div class="founder-content">
‎            <div class="founder-image">
‎                <img src="/mnt/kimi/upload/1000005496.jpg" alt="Mohammed Younis">
‎            </div>
‎            <div class="founder-info">
‎                <h3>محمد یونس</h3>
‎                <p class="title">بانی و سی ای او</p>
‎                <p>24 گھنٹے رابطہ کریں۔ ہم آپ کی خدمت میں حاضر ہیں۔</p>
‎                <a href="tel:032075963489" class="phone-number">032075963489</a>
‎            </div>
‎        </div>
‎    </section>
‎
‎    <section id="office" class="office-section">
‎        <div class="container">
‎            <h2 class="section-title">ہمارا دفتر</h2>
‎            <div class="office-content">
‎                <div class="office-info">
‎                    <p>یہ ہمارا دفتر ہے جہاں آپ آکر ہم سے رجوع کر سکتے ہیں۔</p>
‎                    <p>ٹائمنگ: صبح 9:00 تا شام 8:00</p>
‎                </div>
‎                <div class="office-image">
‎                    <img src="/mnt/kimi/upload/1000005495.jpg" alt="Office">
‎                </div>
‎            </div>
‎        </div>
‎    </section>
‎
‎    <footer id="contact">
‎        <div class="footer-content">
‎            <h3>مدنی ریئل اسٹیٹ ایجنسی</h3>
‎            <div class="contact-info">
‎                <p>📞 Founder: 032075963489</p>
‎                <p>📞 Office: 0322-2480359</p>
‎            </div>
‎            <p>&copy; 2026 Madani Real Estate Agency</p>
‎        </div>
‎    </footer>
‎
‎</body>
‎</html>
‎
