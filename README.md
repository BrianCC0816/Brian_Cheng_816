# Brian_Cheng_816
Try

<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <title>世界旅遊資訊網</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f5faff; }
        header { background: #004080; color: white; padding: 20px; text-align: center; }
        header img { height: 50px; vertical-align: middle; }
        nav { background: #0066cc; padding: 10px; text-align: center; }
        nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
        nav a:hover { text-decoration: underline; }
        main { padding: 20px; text-align: center; }
        .destination { display: inline-block; width: 250px; margin: 15px; background: white; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.2); }
        .destination img { width: 100%; border-radius: 8px 8px 0 0; }
        .destination h3 { background: #004080; color: white; padding: 10px; margin: 0; border-radius: 0 0 8px 8px; }
        footer { background: #004080; color: white; text-align: center; padding: 15px; margin-top: 20px; }
    </style>
</head>
<body>
    <header>
        <img width="100" src="./Image/logo.png" alt="網站標誌">
        <h1 id="top">世界旅遊資訊網(BCC)</h1>
    </header>

    <nav>
        <a href="BCC_Try EX.html">首頁</a>
        <a href="BCC_Iceland(冰島).html">冰島 - 冰島</a>
        <a href="BCC_Tokyo(東京).html">日本 - 東京</a>
        <a href="BCC_Seoul(首爾).html">南韓 - 首爾</a>
        <a href="BCC_Vancouver(溫哥華).html">加拿大 - 溫哥華</a>
    </nav>

    <!-- Alert 1 -->
    <div class="alert alert-primary alert-dismissible fade show">
        <button type="button" class="close" data-dismiss="alert">&times;</button>
        <strong>注意!</strong> 按 <a href="https://www.skyscanner.com.hk/news/10-dream-holiday-destinations-around-the-world" 
        class="alert-link" target="_blank">這裏</a> 了解更多值得旅行的地點！
    </div>

    <main>
        <h2>&#128755; 旅行，不只是目的地，更是故事的開始 &#128746;</h2>
        <p>在我們這個網站，可以了解到四個來自不同國家的旅遊熱地，其中包含歷史、文化、景點以及旅遊資訊，讓您的旅程更加豐富。</p>
        
        <div class="destination">
            <a href="BCC_Iceland(冰島).html"><img src="./Image/Iceland.jpg" alt="冰島"></a>
            <a href="BCC_Iceland(冰島).html"><h3>冰島 - 冰島 &#10052;</h3></a>
        </div>
        <div class="destination">
            <a href="BCC_Tokyo(東京).html"><img src="./Image/Japan.jpg" alt="日本"></a>
            <a href="BCC_Tokyo(東京).html"><h3>日本 - 東京 &#127800;</h3></a>
        </div>
        <div class="destination">
            <a href="BCC_Seoul(首爾).html"><img src="./Image/Seoul.jpg" alt="首爾"></a>
            <a href="BCC_Seoul(首爾).html"><h3>南韓 - 首爾 <br> &#127810;</h3></a>
        </div>
        <div class="destination">
            <a href="BCC_Vancouver(溫哥華).html"><img src="./Image/Canada.jpg" alt="加拿大"></a>
            <a href="BCC_Vancouver(溫哥華).html"><h3>加拿大 - 溫哥華 &#128059;</h3></a>
        </div>
    </main>
    
    <!--Dialog-->
        <div class="row">
           <div class="col-4"></div>
                <button onclick="document.getElementById('請留步～打開我@3@').showModal()">請留步～<br>打開我@3@</button>
                <dialog id="請留步～打開我@3@">
                <p><h1>Wishing you all the best!</h1></p><br>
                <h3>Hope you have a Good Day!</h3>
                <button class="close-btn" id="closeModal">走先啦係 咁先啦 下次再玩啦</button>
                </dialog>
                <div class="col-3"></div>
                <form method="get" action="./Feedback(意見收集箱).html" target="_blank"> 
                <input type="submit" name="submit-btn" value="意見收集箱">
                </form> 
            <div class="col-5"></div>
        </div>
    
    <footer>
        <a href="#top">Back to Top</a> <br>
        <p>© 2025 BCC推介之世界旅遊資訊網 | Designer & Author: Brian Cheng</p>
    </footer>

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <script>
  const dialog = document.getElementById('請留步～打開我@3@');
  const closeBtn = document.getElementById('closeModal');

  closeBtn.addEventListener('click', () => {
    dialog.close();   // 關閉對話框
  });
    </script>

</body>
</html>
