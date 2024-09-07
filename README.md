# trip_media_test

<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Codejump_中級編(2カラムブログ)</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="./css/style.css">
</head>
<body>
  <!-- ヘッダー -->
  <header>
    <div class="header-content">
      <div class="logo-area">
        <div class="logo-img">
          <img src="./img/logo.svg" alt="">
        </div>
      </div>
      <nav class="menu-area">
        <ul>
          <li><a href="#">NEW</a></li>
          <li><a href="#">COLUMN</a></li>
          <li><a href="#">SERIES</a></li>
          <li><a href="#">Q&A</a></li>
          <li><a href="#">CONTACT</a></li>
        </ul>
      </nav>
    </div>
  </header>
  <main>
    <div class="main-area">
      <!-- ピックアップエリア -->
      <div class="pickup-area0">
        <div class="pickup-area" id="pickup">
          <div class="pickup-content">
            <img src="./img/top-img1.jpg" alt="">
            <h3>タイトルテキストテキストテキストテキストテキストテキストテキスト</h3>
            <a href="#" class="read-more-btn">READ MORE</a>
          </div>
          <div class="pickup-content">
            <img src="./img/top-img2.jpg" alt="">
            <h3>タイトルテキストテキストテキストテキストテキストテキストテキスト</h3>
            <a href="#" class="read-more-btn">READ MORE</a>
          </div>
          <div class="pickup-content">
            <img src="./img/top-img3.jpg" alt="">
            <h3>タイトルテキストテキストテキストテキストテキストテキストテキスト</h3>
            <a href="#" class="read-more-btn">READ MORE</a>
          </div>
        </div>
      </div>
      <!-- メインエリア -->
      <div id="container">
        <!-- メインコンテンツ -->
        <div class="main-content">
          <div class="main-content-main">
            <!-- 記事 -->
            <div class="article">
              <a href="#"><h2>タイトルテキストテキストテキストテキストテキスト</h2></a>
              <div class="date-and-category">
                <a href="#">#2020/01/01</a>
                <a href="#">#カテゴリ1</a>
              </div>
              <a href="#"><img src="./img/content-img1.jpg" alt=""></a>
              <p>本文テキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキスト テキストテキストテキストテキストテキストテキストテキストテキストテキスト</p>
              <a href="#" class="read-more-btn">READ MORE</a>
            </div>
            <div class="article article-next">
              <a href="#"><h2>タイトルテキストテキストテキストテキストテキスト</h2></a>
              <div class="date-and-category">
                <a href="#">#2020/01/01</a>
                <a href="#">#カテゴリ1</a>
              </div>
              <a href="#"><img src="./img/content-img2.jpg" alt=""></a>
              <p>本文テキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキスト テキストテキストテキストテキストテキストテキストテキストテキストテキスト</p>
              <a href="#" class="read-more-btn">READ MORE</a>
            </div>
            <div class="article article-next">
              <a href="#"><h2>タイトルテキストテキストテキストテキストテキスト</h2></a>
              <div class="date-and-category">
                <a href="#">#2020/01/01</a>
                <a href="#">#カテゴリ1</a>
              </div>
              <a href="#"><img src="./img/content-img3.jpg" alt=""></a>
              <p>本文テキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキストテキスト テキストテキストテキストテキストテキストテキストテキストテキストテキスト</p>
              <a href="#" class="read-more-btn">READ MORE</a>
            </div>
          </div>
        </div>
        <!-- サイドコンテンツ -->
        <div class="side-content">
          <div class="side-content-main">
            <!-- プロフィール -->
            <div class="profile">
              <img src="./img/profile-img.jpg" alt="">
              <h2>Name Name</h2>
              <p>プロフィールテキストテキストテキストテキストテキストテキストテキスト テキストテキストテキストテキストテキストテキストテキストテキストテキスト テキストテキストテキストテキストテキストテキストテキストテキストテキスト</p>
            </div>
            <!-- ランキング -->
            <div class="ranking">
              <h2>Ranking</h2>
              <a href="#">
                <div class="ranking-content">
                  <img src="./img/side-img1.jpg" alt="">
                  <p>タイトルテキストテキストテキストテキストテキストテキスト</p>
                </div>
              </a>
              <a href="#">
                <div class="ranking-content">
                  <img src="./img/side-img2.jpg" alt="">
                  <p>タイトルテキストテキストテキストテキストテキストテキスト</p>
                </div>
              </a>
              <a href="#">
                <div class="ranking-content">
                  <img src="./img/side-img3.jpg" alt="">
                  <p>タイトルテキストテキストテキストテキストテキストテキスト</p>
                </div>
              </a>
            </div>
            <!-- アーカイブ -->
            <div class="archive">
              <h2>Archive</h2>
              <ul>
                <li><a href="#">XXXX年XX月(XX)</a></li>
                <li><a href="#">XXXX年XX月(XX)</a></li>
                <li><a href="#">XXXX年XX月(XX)</a></li>
                <li><a href="#">XXXX年XX月(XX)</a></li>
                <li><a href="#">XXXX年XX月(XX)</a></li>
                <li><a href="#">XXXX年XX月(XX)</a></li>
                <li><a href="#">XXXX年XX月(XX)</a></li>
                <li><a href="#">XXXX年XX月(XX)</a></li>
                <li><a href="#">XXXX年XX月(XX)</a></li>
                <li><a href="#">XXXX年XX月(XX)</a></li>
                <li><a href="#">XXXX年XX月(XX)</a></li>
                <li><a href="#">XXXX年XX月(XX)</a></li>
                <li><a href="#">XXXX年XX月(XX)</a></li>
                <li><a href="#">XXXX年XX月(XX)</a></li>
                <li><a href="#">XXXX年XX月(XX)</a></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </main>
  <!-- フッター -->
  <footer>
    <div class="footer-area">
      <div class="footer-area-main">
        <div class="about">
          <h2>About</h2>
          <p>テキストテキストテキストテキストテキストテキストテキストテキストテキストテキスト テキストテキストテキストテキストテキストテキストテキストテキストテキストテキスト テキストテキストテキストテキストテキストテキストテキストテキストテキストテキスト</p>
          <ul>
            <li><a href="#">プロフィール詳細</a></li>
            <li><a href="#">お仕事の依頼</a></li>
            <li><a href="#">お問い合わせ</a></li>
          </ul>
        </div>
        <div class="menu">
          <h2>Menu</h2>
          <ul>
            <li><a href="#">NEW</a></li>
            <li><a href="#">CATEGORY</a></li>
            <li><a href="#">COLUMN</a></li>
            <li><a href="#">SERIES</a></li>
            <li><a href="#">Q&A</a></li>
          </ul>
        </div>
        <div class="twitter">
            <h2>Twitter</h2>
            <div class="twitter-link-area">
              <a class="twitter-timeline" href="https://twitter.com/X?ref_src=twsrc%5Etfw" data-height="319px">Tweets by X</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
            </div>
        </div>
      </div>
    </div>
    <div class="copyright"><p>© Travel & Blog</p></div>
  </footer>
  
  <script src="./script.js"></script>
</body>
</html>
