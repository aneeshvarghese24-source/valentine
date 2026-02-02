# valentine
index.html
<!DOCTYPE html>
<html>
<head>
  <title>Be My Valentine 💘</title>
  <style>
    body {
      background: linear-gradient(to right, #ff758c, #ff7eb3);
      font-family: Arial, sans-serif;
      text-align: center;
      padding-top: 100px;
      color: white;
    }
    button {
      padding: 15px 25px;
      font-size: 18px;
      margin: 10px;
      border: none;
      border-radius: 30px;
      cursor: pointer;
    }
    .yes { background-color: #ff4d6d; color: white; }
    .no { background-color: #fff; color: #ff4d6d; }
  </style>
</head>

<body>
  <h1>💌 Will you be my Valentine? 💌</h1>

  <button class="yes" onclick="yesClicked()">Yes 💕</button>
  <button class="no" onclick="noClicked()">No 😜</button>

  <script>
    function yesClicked() {
      document.body.innerHTML = `
        <h1>YAY!!! 💖🥰</h1>
        <h2>Our Virtual Date Ideas 💑</h2>
        <p>🍿 Watch a movie together on Netflix</p>
        <p>🎧 Share a playlist & listen together</p>
        <p>🍕 Order food & eat together on video call</p>
        <p>🎮 Play an online game together</p>
        <p>💬 Long late-night video call</p>
        <h3>I can't wait ❤️</h3>
      `;
    }

    function noClicked() {
      alert("Are you sure? 😏 Try again!");
    }
  </script>
</body>
</html>
