<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Image</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        #container {
            position: relative;
            width: 768px; /* عرض الصورة */
            height: 400px; /* ارتفاع الصورة */
            margin: 20px auto;
            background: url('sbm+.jpg') no-repeat center center;
            background-size: cover;
        }
        .hotspot {
            position: absolute;
            border: 2px solid rgba(0, 0, 0, 0); /* إطار شفاف */
            cursor: pointer;
            transition: all 0.3s ease;
        }
        .hotspot:hover {
            border-color: rgba(0, 0, 0, 0.1); /* لون شفاف قليلاً عند التمرير */
            background-color: rgba(0, 0, 0, 0.2); /* لون شفاف خفيف عند التمرير */
        }

        /* تخصيص المربعات بالمواقع الجديدة */
        #box1 {
            top: 100px; 
            left: 53px; 
            width: 153px; 
            height: 279px; 
        }
        #box2 {
            top: 20px; 
            left: 223px; 
            width: 152px; 
            height: 170px; 
        }
        #box3 {
            top: 20px; 
            left: 390px; 
            width: 152px; 
            height: 170px; 
        }
        #box4 {
            top: 20px; 
            left: 559px; 
            width: 152px; 
            height: 170px; 
        }
        #box5 {
            top: 207px; 
            left: 223px; 
            width: 152px; 
            height: 170px; 
        }
        #box6 {
            top: 207px; 
            left: 390px; 
            width: 152px; 
            height: 170px; 
        }
        #box7 {
            top: 207px; 
            left: 559px; 
            width: 152px; 
            height: 170px; 
        }
        h1 {
            font-size: 36px; /* تكبير حجم الخط */
            color: #333;
            margin: 20px 0;
            letter-spacing: 2px; /* جعل الكلمة طويلة قليلاً */
        }
    </style>
</head>
<body>
    <h1>Signals By Moza</h1>
    <div id="container">
        <!-- الروابط التفاعلية -->
        <a href="general-information.html" class="hotspot" id="box1" title="General Information"></a>
        <a href="channel-subscriptions.html" class="hotspot" id="box2" title="Channel Subscriptions"></a>
        <a href="education-subscriptions.html" class="hotspot" id="box3" title="Education Subscriptions"></a>
        <a href="https://t.me/SignalsByMoza_Bot" class="hotspot" id="box4" title="Telegram Bot for the Channel"></a>
        <a href="https://oemalm.github.io/jpy-calculation/" class="hotspot" id="box5" title="JPY Pairs Calculation"></a>
        <a href="https://oemalm.github.io/other-pairs/" class="hotspot" id="box6" title="Other Pairs Calculation"></a>
        <a href="https://oemalm.github.io/interactive-gold-points/" class="hotspot" id="box7" title="Interactive Gold Points"></a>
    </div>
</body>
</html>
