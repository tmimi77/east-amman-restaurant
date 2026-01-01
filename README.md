<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>مطعم إطلالة شرق عمان</title>
<style>
    body {
        font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
        direction: rtl;
        margin: 0;
        padding: 0;
        background: #f8f8f8;
    }
    header {
        background: url('https://images.pexels.com/photos/262959/pexels-photo-262959.jpeg') center/cover no-repeat;
        height: 350px;
        text-align: center;
        color: white;
        padding-top: 120px;
        font-size: 40px;
        font-weight: bold;
        text-shadow: 2px 2px 6px #000;
    }
    nav {
        background: #b71c1c;
        padding: 10px;
        text-align: center;
    }
    nav a {
        color: white;
        text-decoration: none;
        margin: 0 15px;
        font-size: 18px;
    }
    section {
        padding: 30px;
    }
    .about img {
        width: 100%;
        border-radius: 12px;
    }
    .menu {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
        gap: 15px;
    }
    .menu-item {
        background: white;
        padding: 15px;
        border-radius: 8px;
        text-align: center;
        box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    .menu-item img {
        width: 100%;
        border-radius: 8px;
    }
    footer {
        background: #333;
        color: white;
        text-align: center;
        padding: 12px 0;
        margin-top: 30px;
    }
</style>
</head>
<body>

<header>
    🍽️ مطعم إطلالة شرق عمان
</header>

<nav>
    <a href="#about">عن المطعم</a>
    <a href="#menu">قائمة الطعام</a>
    <a href="#contact">تواصل معنا</a>
</nav>

<section id="about" class="about">
    <h2>عن المطعم</h2>
    <p>مطعم إطلالة شرق عمان يقدم ألذ المأكولات الشرقية والعالمية بجودة عالية وأجواء هادئة تناسب العائلات والأصدقاء.</p>
    <img src="https://images.pexels.com/photos/262959/pexels-photo-262959.jpeg" alt="صورة مطعم">
</section>

<section id="menu">
    <h2>قائمة الطعام</h2>
    <div class="menu">
        <div class="menu-item">
            <img src="https://images.pexels.com/photos/70497/pexels-photo-70497.jpeg" alt="وجبة">
            <h3>المنسف الأردني</h3>
            <p>لحم طري مع الزبادي والأرز.</p>
        </div>
        <div class="menu-item">
            <img src="https://images.pexels.com/photos/461198/pexels-photo-461198.jpeg" alt="وجبة">
            <h3>شاورما لحم</h3>
            <p>شاورما مميزة مع صوص خاص.</p>
        </div>
        <div class="menu-item">
            <img src="https://images.pexels.com/photos/262959/pexels-photo-262959.jpeg" alt="وجبة">
            <h3>مشاوي مشكّلة</h3>
            <p>مشاوي طازجة على الفحم.</p>
        </div>
    </div>
</section>

<section id="contact">
    <h2>تواصل معنا</h2>
    <p>📍 شرق عمان – شارع الإطلالة</p>
    <p>📞 +962 7 1234 5678</p>
    <p>📧 email@example.com</p>
</section>

<footer>
    &copy; 2026 مطعم إطلالة شرق عمان
</footer>

</body>
</html>
