<!DOCTYPE html>
<html>
<head>
  <title>Be My Valentine 💖</title>
  <style>
    body {
      background: pink;
      text-align: center;
      font-family: Arial, sans-serif;
      height: 100vh;
      overflow: hidden;
    }
    h1 {
      margin-top: 120px;
    }
    button {
      font-size: 20px;
      padding: 12px 24px;
      margin: 20px;
      border: none;
      border-radius: 10px;
      cursor: pointer;
    }
    #yes {
      background: red;
      color: white;
    }
    #no {
      background: white;
      position: absolute;
    }
  </style>
</head>
<body>

  <h1>Will you be my Valentine? 💘</h1>

  <button id="yes" onclick="alert('YAY!! 💖🥰')">
    YES 💕
  </button>

  <button id="no" onmouseover="moveNo()">
    NO 🙃
  </button>

  <script>
    function moveNo() {
      const no = document.getElementById("no");
      const x = Math.random() * (window.innerWidth - 100);
      const y = Math.random() * (window.innerHeight - 50);
      no.style.left = x + "px";
      no.style.top = y + "px";
    }
  </script>

</body>
</html>
