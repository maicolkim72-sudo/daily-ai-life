<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <title>AI와 함께하는 일상 이야기</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #111; /* 어두운 배경 */
      color: #fff;
    }
    header {
      background-color: #2196f3; /* 파란 배너 */
      padding: 15px;
      text-align: center;
      font-size: 1.5em;
    }
    .today {
      padding: 20px;
      text-align: center;
    }
    .today img, .today video {
      max-width: 100%;
      border-radius: 10px;
    }
    .today audio {
      margin-top: 15px;
    }
    .past {
      padding: 20px;
    }
    .past h2 {
      margin-bottom: 10px;
    }
    .past-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 10px;
    }
    .past-grid div {
      background: #333;
      padding: 10px;
      border-radius: 8px;
      text-align: center;
    }
    footer {
      text-align: center;
      padding: 10px;
      background: #222;
    }
  </style>
</head>
<body>
  <header>AI와 함께하는 일상 이야기</header>

  <section class="today">
    <h2>오늘 이야기</h2>
    <img src="today.jpg" alt="오늘 사진">
    <p>오늘의 음악</p>
    <audio controls>
      <source src="today.mp3" type="audio/mpeg">
    </audio>
  </section>

  <section class="past">
    <h2>지난 이야기</h2>
    <div class="past-grid">
      <div>3월 23일 기록</div>
      <div>3월 22일 기록</div>
      <div>3월 21일 기록</div>
      <div>3월 20일 기록</div>
    </div>
  </section>

  <footer>© 2026 요삐의 하루</footer>
</body>
</html>
