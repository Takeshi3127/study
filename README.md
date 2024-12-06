# studyeducation-platform/
│
├── index.html        # ホームページ
├── lessons.html      # 教材ページ
├── css/
│   └── styles.css    # デザイン用CSS
├── js/
│   └── script.js     # 動的機能用JavaScript
└── assets/
    └── images/       # 画像などのメディアファイル

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>未来の教育プラットフォーム</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <header class="main-header">
        <nav>
            <h1>教育プラットフォーム</h1>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="lessons.html">Lessons</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="hero">
            <h2>誰でも学べる無料プラットフォーム</h2>
            <p>あなたの未来を築くために、学びの扉を開きましょう。</p>
            <a href="lessons.html" class="cta-button">教材を見る</a>
        </section>

        <section id="about" class="info-section">
            <h3>私たちの目標</h3>
            <p>教育の平等なアクセスを実現し、全ての人が学ぶ喜びを体験できるようにします。</p>
        </section>
    </main>

    <footer id="contact">
        <p>&copy; 2024 教育プラットフォーム</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>教材一覧</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <header class="main-header">
        <nav>
            <h1>教育プラットフォーム</h1>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="#lessons">Lessons</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="lessons" class="lesson-section">
            <h2>教材一覧</h2>
            <div class="lesson-card">
                <h3>数学</h3>
                <p>基本の計算や代数を学べます。</p>
                <a href="#" class="lesson-link">開始する</a>
            </div>
            <div class="lesson-card">
                <h3>プログラミング</h3>
                <p>HTMLやPythonの基礎を習得しましょう。</p>
                <a href="#" class="lesson-link">開始する</a>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 教育プラットフォーム</p>
    </footer>
</body>
</html>

/* Reset CSS */
body, h1, h2, h3, p, ul, li, a {
    margin: 0;
    padding: 0;
    list-style: none;
    text-decoration: none;
}

/* Body Style */
body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    color: #333;
    background: #f9f9f9;
    margin: 0;
    padding: 0;
}

/* Header Style */
.main-header {
    background: #007BFF;
    color: white;
    padding: 10px 20px;
}

.main-header h1 {
    font-size: 24px;
}

.main-header nav ul {
    display: flex;
    justify-content: flex-end;
}

.main-header nav ul li {
    margin: 0 10px;
}

/* Hero Section */
#hero {
    background: #4CAF50;
    color: white;
    padding: 50px 20px;
    text-align: center;
}

.cta-button {
    background: #333;
    color: white;
    padding: 10px 20px;
    display: inline-block;
    margin-top: 20px;
    border-radius: 5px;
}

.cta-button:hover {
    background: #555;
}

/* Lesson Section */
.lesson-section {
    padding: 20px;
    display: flex;
    gap: 20px;
    justify-content: center;
}

.lesson-card {
    background: white;
    padding: 20px;
    border: 1px solid #ddd;
    border-radius: 5px;
    width: 250px;
    text-align: center;
}
