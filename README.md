<!DOCTYPE html>
<html>
<head>
  <title>Important Question ❤️</title>
  <style>
    body {
      background-color: #ffdde1;
      font-family: Arial, sans-serif;
      text-align: center;
      padding-top: 100px;
    }

    h1 {
      font-size: 28px;
    }

    .btn {
      padding: 12px 25px;
      font-size: 18px;
      margin: 10px;
      border: none;
      border-radius: 25px;
      cursor: pointer;
      transition: 0.3s;
    }

    #yes {
      background-color: #ff4d6d;
      color: white;
    }

    #no {
      background-color: #6c757d;
      color: white;
      position: absolute;
    }
  </style>
</head>
<body>

  <h1>Will you be my Valentine Lakku? 💘</h1>

  <button id="yes" class="btn" onclick="yesClicked()">Yes ❤️</button>
  <button id="no" class="btn" onmouseover="moveButton()">No 😢</button>

  <script>
    function yesClicked() {
      document.body.innerHTML = "<h1>Yayyyy!!! 💖 See you on Feb 14 😘</h1>";
    }

    function moveButton() {
      const button = document.getElementById("no");
      const x = Math.random() * window.innerWidth - 100;
      const y = Math.random() * window.innerHeight - 50;
      button.style.left = x + "px";
      button.style.top = y + "px";
    }
  </script>

</body>
</html>
