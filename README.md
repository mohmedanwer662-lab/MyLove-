<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>معرض الـ 10 صور</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
        }

        .gallery {
            display: grid;
            /* سيقوم بإنشاء أعمدة تلقائية بناءً على حجم الشاشة */
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            width: 100%;
            max-width: 1200px;
        }

        .gallery-item {
            background: #fff;
            padding: 10px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }

        .gallery-item:hover {
            transform: scale(1.05);
        }

        .gallery-item img {
            width: 100%;
            height: auto;
            border-radius: 5px;
            display: block;
        }

        h1 { color: #333; }
    </style>
</head>
<body>

    <h1>معرض الصور الخاص بي</h1>

    <div class="gallery">
        <div class="gallery-item"><img src="img1.jpg" alt="صورة 1"></div>
        <div class="gallery-item"><img src="img2.jpg" alt="صورة 2"></div>
        <div class="gallery-item"><img src="img3.jpg" alt="صورة 3"></div>
        <div class="gallery-item"><img src="img4.jpg" alt="صورة 4"></div>
        <div class="gallery-item"><img src="img5.jpg" alt="صورة 5"></div>
        <div class="gallery-item"><img src="img6.jpg" alt="صورة 6"></div>
        <div class="gallery-item"><img src="img7.jpg" alt="صورة 7"></div>
        <div class="gallery-item"><img src="img8.jpg" alt="صورة 8"></div>
        <div class="gallery-item"><img src="img9.jpg" alt="صورة 9"></div>
        <div class="gallery-item"><img src="img10.jpg" alt="صورة 10"></div>
    </div>

</body>
</html>
