<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>大作 秋祭り｜公式サイト</title>
  <style>
    /* 全体の基本設定 */
    :root {
      --bg-color: #f9f5eb;       /* 温かみのある生成り色 */
      --card-bg: #ffffff;        /* カードの白 */
      --main-brown: #5a3825;     /* 落ち着いた焦げ茶 */
      --accent-red: #c84b31;     /* 秋らしい朱色 */
      --text-color: #333333;     /* 本文の文字色 */
      --border-color: #e6dcc8;   /* 枠線の色 */
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: "Hiragino Kaku Gothic ProN", "Hiragino Sans", Meiryo, sans-serif;
      background-color: var(--bg-color);
      color: var(--text-color);
      line-height: 1.7;
    }

    /* ヘッダー・ナビゲーション */
    header {
      background-color: var(--card-bg);
      border-bottom: 1px solid var(--border-color);
      padding: 15px 20px;
      position: sticky;
      top: 0;
      z-index: 100;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      gap: 10px;
    }

    .header-title {
      font-weight: bold;
      color: var(--accent-red);
      font-size: 1.1rem;
      text-decoration: none;
    }

    nav {
      display: flex;
      gap: 15px;
      font-size: 0.85rem;
      flex-wrap: wrap;
    }

    nav a {
      text-decoration: none;
      color: var(--main-brown);
      font-weight: bold;
    }

    nav a:hover {
      color: var(--accent-red);
    }

    /* メインビジュアル（タイトル部分） */
    .hero {
      background: linear-gradient(135deg, #4a2c1d 0%, #7a492e 100%);
      color: #ffffff;
      text-align: center;
      padding: 72px 20px;
    }

    .hero-sub {
      font-size: 0.95rem;
      letter-spacing: 0.15em;
      color: #f3d5b5;
      margin-bottom: 14px;
    }

    .hero h1 {
      font-size: 3.8rem;
      letter-spacing: 0.1em;
      margin-bottom: 10px;
      line-height: 1.2;
    }

    /* 開催概要の3カラムバー */
    .info-bar {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      background-color: var(--card-bg);
      border-bottom: 1px solid var(--border-color);
    }

    .info-item {
      padding: 24px 14px;
      text-align: center;
      border-right: 1px solid var(--border-color);
    }

    .info-item:last-child {
      border-right: none;
    }

    .info-label {
      font-size: 0.9rem;
      color: #666666;
      margin-bottom: 6px;
      font-weight: bold;
    }

    .info-value {
      font-weight: bold;
      color: var(--main-brown);
      font-size: 1.3rem;
      line-height: 1.4;
    }

    /* コンテンツ共通レイアウト */
    main {
      max-width: 800px;
      margin: 0 auto;
      padding: 40px 20px;
    }

    section {
      margin-bottom: 60px;
    }

    .section-header {
      text-align: center;
      margin-bottom: 25px;
    }

    .section-en {
      font-size: 0.75rem;
      letter-spacing: 0.15em;
      color: var(--accent-red);
      font-weight: bold;
      display: block;
      margin-bottom: 5px;
    }

    .section-title {
      font-size: 1.6rem;
      color: var(--main-brown);
    }

    /* プログラム（時間＋内容）リスト */
    .program-box {
      background-color: var(--card-bg);
      border: 2px solid var(--border-color);
      border-radius: 12px;
      padding: 24px 26px;
    }

    .program-list {
      list-style: none;
    }

    .program-item {
      display: flex;
      gap: 18px;
      padding: 14px 0;
      border-bottom: 1px solid var(--border-color);
      align-items: baseline;
    }

    .program-item:last-child {
      border-bottom: none;
      padding-bottom: 0;
    }

    .program-time {
      font-weight: bold;
      color: var(--accent-red);
      font-size: 1.05rem;
      white-space: nowrap;
      min-width: 110px;
    }

    .program-content {
      font-size: 1rem;
      color: var(--text-color);
      flex: 1;
    }

    /* 「未定」のリンク付きカード枠 */
    .link-card {
      display: block;
      background-color: var(--card-bg);
      border: 2px solid var(--border-color);
      border-radius: 12px;
      padding: 30px 25px;
      text-align: center;
      text-decoration: none;
      color: var(--text-color);
      transition: transform 0.2s, box-shadow 0.2s, border-color 0.2s;
      position: relative;
    }

    .link-card:hover {
      transform: translateY(-3px);
      box-shadow: 0 6px 15px rgba(90, 56, 37, 0.1);
      border-color: var(--accent-red);
    }

    .status-badge {
      display: inline-block;
      background-color: #f3e9d8;
      color: var(--main-brown);
      font-weight: bold;
      padding: 4px 16px;
      border-radius: 20px;
      font-size: 0.95rem;
      margin-bottom: 10px;
    }

    .link-card p {
      font-size: 0.9rem;
      color: #666;
    }

    .link-hint {
      display: inline-block;
      margin-top: 12px;
      font-size: 0.85rem;
      color: var(--accent-red);
      font-weight: bold;
    }

    /* 会場マップ */
    .map-box {
      background-color: var(--card-bg);
      border: 1px solid var(--border-color);
      border-radius: 12px;
      padding: 25px;
      text-align: center;
    }

    .map-box img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
      border: 1px solid #ddd;
      margin-bottom: 15px;
      min-height: 200px;
      background-color: #f0ece1;
      display: block;
      margin-left: auto;
      margin-right: auto;
    }

    .map-description {
      text-align: left;
      font-size: 0.95rem;
      background-color: var(--bg-color);
      padding: 15px;
      border-radius: 8px;
    }

    /* 注意事項 */
    .notice-box {
      background-color: var(--card-bg);
      border: 2px solid #e0b8b0;
      border-radius: 12px;
      padding: 25px 30px;
    }

    .notice-list {
      list-style: none;
    }

    .notice-list li {
      position: relative;
      padding-left: 1.5em;
      margin-bottom: 12px;
      font-size: 0.95rem;
    }

    .notice-list li:last-child {
      margin-bottom: 0;
    }

    .notice-list li::before {
      content: "※";
      position: absolute;
      left: 0;
      color: var(--accent-red);
      font-weight: bold;
    }

    /* フッター */
    footer {
      background-color: var(--main-brown);
      color: #ffffff;
      text-align: center;
      padding: 35px 20px;
      font-size: 0.9rem;
    }

    footer p {
      margin-bottom: 6px;
    }

    .creator {
      font-size: 0.8rem;
      color: #d9c5b2;
      margin-top: 15px;
    }

    /* スマホ画面用の調整 */
    @media (max-width: 600px) {
      .info-bar {
        grid-template-columns: 1fr;
      }

      .info-item {
        border-right: none;
        border-bottom: 1px solid var(--border-color);
        padding: 18px 14px;
      }

      .hero {
        padding: 56px 20px;
      }

      .hero h1 {
        font-size: 2.2rem;
      }

      .info-value {
        font-size: 1.2rem;
      }

      .program-item {
        flex-direction: column;
        gap: 4px;
      }
    }
  </style>
</head>
<body>
  <!-- ヘッダー -->
  <header>
    <a href="#" class="header-title">大作 秋祭り</a>
    <nav>
      <a href="#program">プログラム</a>
      <a href="#performers">出演団体</a>
      <a href="#stalls">出店一覧</a>
      <a href="#map">会場マップ</a>
      <a href="#notice">注意事項</a>
      <a href="#sponsors">協賛</a>
    </nav>
  </header>

  <!-- トップタイトル -->
  <div class="hero">
    <p class="hero-sub">✦ COMMUNITY & FESTIVAL ✦</p>
    <h1>大作 秋祭り</h1>
  </div>

  <!-- 開催概要 -->
  <div class="info-bar">
    <div class="info-item">
      <div class="info-label">開催日時</div>
      <div class="info-value">11月8日（日） 10:00〜19:00</div>
    </div>
    <div class="info-item">
      <div class="info-label">会場</div>
      <div class="info-value">最蔵寺駐車場</div>
    </div>
    <div class="info-item">
      <div class="info-label">入場</div>
      <div class="info-value">無料</div>
    </div>
  </div>

  <!-- メインコンテンツ -->
  <main>
    <!-- プログラム一覧 -->
    <section id="program">
      <div class="section-header">
        <span class="section-en">TODAY'S SCHEDULE</span>
        <h2 class="section-title">プログラム一覧</h2>
      </div>
      <!-- ▼ 「時間」と「内容」を書き換えて使います。行を増やしたいときは <li class="program-item">〜</li> をコピーして追加してください -->
      <div class="program-box">
        <ul class="program-list">
          <li class="program-item">
            <span class="program-time">10:00〜</span>
            <span class="program-content">（ここにプログラム内容を入力）</span>
          </li>
          <li class="program-item">
            <span class="program-time">13:00〜</span>
            <span class="program-content">（ここにプログラム内容を入力）</span>
          </li>
          <li class="program-item">
            <span class="program-time">16:00〜</span>
            <span class="program-content">（ここにプログラム内容を入力）</span>
          </li>
        </ul>
      </div>
    </section>

    <!-- 出演団体 -->
    <section id="performers">
      <div class="section-header">
        <span class="section-en">STAGE & PERFORMERS</span>
        <h2 class="section-title">出演団体</h2>
      </div>
      <!-- ▼ href="ここに飛ばしたいURLを入れる" -->
      <a href="#" target="_blank" rel="noopener noreferrer" class="link-card">
        <span class="status-badge">未定</span>
        <p>決定次第、こちらでお知らせいたします。</p>
        <span class="link-hint">詳細ページを見る →</span>
      </a>
    </section>

    <!-- 出店一覧 -->
    <section id="stalls">
      <div class="section-header">
        <span class="section-en">FOOD & MARKET</span>
        <h2 class="section-title">出店一覧</h2>
      </div>
      <!-- ▼ href="ここに飛ばしたいURLを入れる" -->
      <a href="#" target="_blank" rel="noopener noreferrer" class="link-card">
        <span class="status-badge">未定</span>
        <p>決定次第、こちらでお知らせいたします。</p>
        <span class="link-hint">詳細ページを見る →</span>
      </a>
    </section>

    <!-- 会場マップ -->
    <section id="map">
      <div class="section-header">
        <span class="section-en">VENUE GUIDE</span>
        <h2 class="section-title">会場マップ</h2>
      </div>
      <div class="map-box">
        <!-- ▼ src="ここに画像ファイル名（例: map.jpg）を入れる" -->
        <img src="map.jpg" alt="大作秋祭り 会場マップ（準備中）">
        <div class="map-description">
          <p><strong>【会場のご案内】</strong><br>
          ここに会場マップの説明文が入ります。ステージの位置や飲食エリア、所定の喫煙所、お手洗いなどのご案内を記載できます。</p>
        </div>
      </div>
    </section>

    <!-- 注意事項 -->
    <section id="notice">
      <div class="section-header">
        <span class="section-en">INFORMATION</span>
        <h2 class="section-title">注意事項</h2>
      </div>
      <div class="notice-box">
        <ul class="notice-list">
          <li>敷地内にはゴミ箱を設置していません。購入したお店に渡すか、各自お持ち帰りください。</li>
          <li>敷地内は禁煙です。所定の喫煙所でのみ喫煙可能です。</li>
          <li>近隣住民のご迷惑となりますので、立ち入り・ポイ捨て・路上喫煙などの行為はおやめください。</li>
        </ul>
      </div>
    </section>

    <!-- 協賛 -->
    <section id="sponsors">
      <div class="section-header">
        <span class="section-en">SPECIAL THANKS</span>
        <h2 class="section-title">協賛</h2>
      </div>
      <!-- ▼ href="ここに飛ばしたいURLを入れる" -->
      <a href="#" target="_blank" rel="noopener noreferrer" class="link-card">
        <span class="status-badge">未定</span>
        <p>決定次第、こちらでお知らせいたします。</p>
        <span class="link-hint">詳細ページを見る →</span>
      </a>
    </section>
  </main>

  <!-- フッター -->
  <footer>
    <p><strong>大作 秋祭り</strong></p>
    <p>11月8日（日） 10:00〜19:00 ｜ 最蔵寺駐車場</p>
    <p>主催：大作青年会</p>
    <p class="creator">作成：石黒</p>
  </footer>
</body>
</html>
