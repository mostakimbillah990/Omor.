<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ওমর </title>
    <style>
        /* সাধারণ স্টাইল */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }

        /* হেডার স্টাইল */
        .header {
            background-color: #4CAF50;
            color: white;
            padding: 3em 1em;
            text-align: center;
        }

        .header-content h1 {
            font-size: 2.5em;
            margin-bottom: 0.5em;
        }

        .header-content p {
            font-size: 1.2em;
        }

        /* পরিচিতি সেকশন */
        .about {
            padding: 3em 1em;
            text-align: center;
            background-color: #f4f4f4;
        }

        .about h2 {
            font-size: 2em;
            color: #333;
            margin-bottom: 0.5em;
        }

        .about p {
            font-size: 1.1em;
            color: #666;
            max-width: 600px;
            margin: 0 auto;
        }

        /* দক্ষতা সেকশন */
        .skills {
            padding: 3em 1em;
            text-align: center;
        }

        .skills h2 {
            font-size: 2em;
            color: #333;
            margin-bottom: 1em;
        }

        .skill-grid {
            display: flex;
            gap: 20px;
            justify-content: center;
            flex-wrap: wrap;
        }

        .skill-card {
            background-color: #ffffff;
            border: 1px solid #ddd;
            padding: 1.5em;
            width: 250px;
            text-align: center;
            transition: transform 0.3s;
            text-decoration: none;
            color: #333;
        }

        .skill-card:hover {
            transform: translateY(-10px);
        }

        .skill-card h3 {
            font-size: 1.5em;
            color: #4CAF50;
            margin-bottom: 0.5em;
        }

        .skill-card p {
            font-size: 1em;
            color: #666;
        }

        /* ফুটার */
        .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1.5em 0;
        }

        /* রেসপন্সিভ ডিজাইন */
        @media (max-width: 768px) {
            .skill-grid {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>

    <!-- হেডার সেকশন -->
    <header class="header">
        <div class="header-content">
            <h1>ওমর স্মৃতি ঘর</h1>
            <p>আমি ওমর, আমি একজন মুসলিম</p>
        </div>
    </header>

    <!-- পরিচিতি সেকশন -->
    <section class="about" id="about">
        <h2>আমার সম্পর্কে</h2>
        <p>আমি আবুতোহা আদনান ওমর (আলিফ)জন্ম তারিখ ৭ জুলাই ২০২৪ সাল।পিতা :মোস্তাকিম বিল্লাহ। মাতা :রাজিয়া সুলতানা। ঠিকানা - জেলা : নারায়ণগঞ্জ। থানা : বন্দর। গ্রাম :বুরুন্দি।</p>
    </section>

    <!-- দক্ষতা সেকশন -->
    <section class="skills" id="skills">
        <h2> লিস্ট </h2>
        <div class="skill-grid">
            <a href="1tp4.html" class="skill-card">
                <h3>১-৪</h3>
                <p>১ থেকে চার মাস বয়স পর্যন্ত ওমরের তোলা বিভিন্ন পিক এবং ভিডিও</p>
            </a>
            <a href="1tp4" class="skill-card">
                <h3>৪-৫</h3>
                <p>৪ থেকে ৫ মাস বয়স পর্যন্ত ওমরের বিভিন্ন পিক এবং ভিডিও</p>
            </a>
            <a href="page3.html" class="skill-card">
                <h3>JavaScript</h3>
                <p>ওয়েবসাইটের ইন্টারঅ্যাকশন উন্নত করার জন্য JavaScript ব্যবহার করি।</p>
            </a>
        </div>
    </section>

    <!-- ফুটার -->
    <footer class="footer">
        <p>&copy; ২০২৪ আমার ওয়েবসাইট। সর্বস্বত্ব সংরক্ষিত।</p>
    </footer>

</body>
</html>