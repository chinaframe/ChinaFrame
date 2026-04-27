## Hi there 👋

<!--
**chinaframe/ChinaFrame** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<title>China Frame</title>
<style>
body {
    font-family: 'Georgia', serif;
    margin: 0;
    background: #ffffff;
    color: #111;
}

.container {
    max-width: 1100px;
    margin: auto;
    padding: 20px;
}

/* HEADER */
.header {
    text-align: center;
    margin-bottom: 40px;
}

.header img {
    height: 60px;
}

.nav {
    display: flex;
    justify-content: center;
    gap: 30px;
    margin-top: 15px;
    font-size: 14px;
    color: #555;
}

/* MAIN */
.main {
    display: flex;
    gap: 30px;
}

/* LEFT */
.left {
    flex: 2;
}

.featured img {
    width: 100%;
    border-radius: 8px;
}

.featured h1 {
    font-size: 28px;
    margin: 15px 0;
}

.featured p {
    color: #666;
}

/* RIGHT */
.right {
    flex: 1;
}

/* SIGNAL BOX */
.signal-box {
    border: 1px solid #ddd;
    border-radius: 10px;
    padding: 20px;
}

.signal-title {
    font-weight: bold;
    font-size: 20px;
    margin-bottom: 10px;
}

.signal-item {
    margin-bottom: 15px;
    font-size: 14px;
}

.signal-item span {
    color: #C9A227;
    font-weight: bold;
}

/* FOOTER */
.footer {
    text-align: center;
    margin-top: 60px;
}

.footer img {
    height: 50px;
}
</style>
</head>

<body>

<div class="container">

    <!-- HEADER -->
    <div class="header">
        <!-- 🔥 여기에 GIPI 로고 넣기 -->
        <img src="YOUR_GIPI_LOGO_URL.png">
        <div class="nav">
            <div>Home</div>
            <div>Archive</div>
            <div>About</div>
            <div>Topics</div>
        </div>
    </div>

    <!-- MAIN -->
    <div class="main">

        <!-- LEFT CONTENT -->
        <div class="left">
            <div class="featured">
                <img src="https://images.unsplash.com/photo-1547981609-4b6bfe67ca0b">
                <h1>중국 부동산은 살아나는가? — 그렇게 단순하지 않다</h1>
                <p>표면적 회복 이면에 구조적 문제가 여전히 존재한다.</p>
            </div>
        </div>

        <!-- RIGHT SIDEBAR -->
        <div class="right">
            <div class="signal-box">
                <div class="signal-title">📊 BEIJING SIGNAL</div>

                <div class="signal-item">
                    <span>금융</span><br>
                    지급준비율 인하 → 단기 유동성 확대
                </div>

                <div class="signal-item">
                    <span>부동산</span><br>
                    대출 규제 완화 → 단기 반등 가능
                </div>

                <div class="signal-item">
                    <span>산업</span><br>
                    전기차 정책 지속 → 산업 경쟁력 강화
                </div>

            </div>
        </div>

    </div>

    <!-- FOOTER -->
    <div class="footer">
        <!-- 🔥 하단 중앙 GIPI 로고 -->
        <img src="YOUR_GIPI_LOGO_URL.png">
    </div>

</div>

</body>
</html>