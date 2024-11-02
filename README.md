<html lang="ar">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>بوابة السفراء جامعة آل البيت</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: white; /* جعل الخلفية بيضاء */
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            margin: 0;
            color: #333; /* لون النص */
            text-align: center;
        }

        h1 {
            margin-bottom: 20px;
            font-size: 2.5em;
            color: #45a247; /* لون العنوان */
        }

        .form-container {
            background: rgba(255, 255, 255, 0.9);
            border-radius: 10px;
            padding: 30px;
            box-shadow: 0 8px 30px rgba(0, 0, 0, 0.2);
            max-width: 600px;
            width: 90%; /* جعل عرض النموذج 90% ليتناسب مع الشاشات الصغيرة */
            margin: 20px auto;
            display: none; /* إخفاء النموذج بشكل افتراضي */
        }

        iframe {
            width: 100%;
            height: 600px;
            border: none;
            border-radius: 5px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
        }

        .note {
            font-size: 1.1em;
            margin: 10px 0;
            color: #333;
        }

        .submit-button {
            background-color: #45a247; /* لون الزر */
            color: white;
            border: none;
            border-radius: 5px;
            padding: 15px 25px;
            font-size: 1.2em;
            cursor: pointer;
            transition: background-color 0.3s ease;
            width: 100%;
            margin-top: 10px;
        }

        .submit-button:hover {
            background-color: #388e3c; /* ظل أغمق عند التمرير */
        }

        .start-button {
            background-color: #45a247; /* لون زر البداية */
            color: white;
            border: none;
            border-radius: 5px;
            padding: 15px 25px;
            font-size: 1.2em;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .start-button:hover {
            background-color: #388e3c;
        }

        .logos-container {
            display: flex; /* استخدام Flexbox لتنسيق الشعارين */
            justify-content: center; /* مركز الشعارين */
            margin-bottom: 20px; /* مسافة تحت الشعارين */
        }

        .logo {
            max-width: 150px; /* تحديد العرض الأقصى للشعار */
            height: auto; /* الحفاظ على نسبة العرض إلى الطول */
            margin: 0 10px; /* مسافة بين الشعارين */
        }

        .footer-text {
            margin-top: 20px;
            font-size: 1em;
            color: #333; /* لون النص في الفوتر */
        }

        /* تحسينات للوسائط */
        @media (max-width: 768px) {
            h1 {
                font-size: 2em; /* تقليل حجم العنوان للشاشات الصغيرة */
            }

            .form-container {
                padding: 20px; /* تقليل padding في النموذج */
            }

            .submit-button,
            .start-button {
                padding: 10px 20px; /* تقليل padding للأزرار */
                font-size: 1em; /* تقليل حجم الخط للأزرار */
            }

            .logo {
                max-width: 100px; /* تقليل عرض الشعار على الشاشات الصغيرة */
            }
        }

        @media (max-width: 480px) {
            h1 {
                font-size: 1.5em; /* حجم خط أصغر للشاشات الصغيرة جداً */
            }

            .form-container {
                width: 95%; /* جعل عرض النموذج أكبر قليلاً */
            }

            .submit-button,
            .start-button {
                padding: 8px 15px; /* تقليل padding أكثر للأزرار */
                font-size: 0.9em; /* تقليل حجم الخط للأزرار */
            }
        }
    </style>
</head>

<body>
    <div class="logos-container"> <!-- حاوية الشعارين -->
        <img src="https://assets.onecompiler.app/42wttk5ev/42wttjqj4/22%20(3).png" alt="شعار إضافي" class="logo"> <!-- الشعار الأول -->
        <img src="https://assets.onecompiler.app/42wttk5ev/42wttjqj4/logo%20(2).png" alt="شعار الجامعة" class="logo"> <!-- الشعار الثاني -->
    </div>

    <h1>بوابة سفراء نحن جامعة آل البيت</h1>

    <button class="start-button" onclick="showForm()">ابدأ الدخول للبوابة</button> <!-- زر لبدء التعبئة -->

    <div class="form-container" id="formContainer"> <!-- إضافة id للنموذج -->
        <iframe src="https://docs.google.com/forms/d/e/1FAIpQLScVfhqYoq_YsgKPmuGJ2LIOSIhRC46UH8aWsKDEUlvofo7qqw/viewform?embedded=true" frameborder="0">جارٍ التحميل…</iframe>
        <p class="note">ملاحظة: سيتم الدخول بعد إكمال تعبئة البيانات.</p>
        <button class="submit-button" onclick="submitForm()">الدخول</button>
    </div>

    <p class="footer-text">تم تصميم هذه البوابة من قبل المهندس فرحان الخوالدة</p> <!-- نص الفوتر -->

    <script>
        function showForm() {
            document.getElementById('formContainer').style.display = 'block'; // إظهار النموذج
        }

        function submitForm() {
            window.location.href = "[https://fa893.github.io/nahno---Al-al-Bayt-University-/]"; // الانتقال للموقع بعد الضغط على "إرسال"
        }
    </script>
</body>

</html>
