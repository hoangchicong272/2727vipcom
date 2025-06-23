# 2727vipcom
vpcom
<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Trang Cá Nhân</title>
  <style>
    body {
      background-color: #f0f8ff;
      font-family: Arial, sans-serif;
      text-align: center;
      padding: 50px;
    }

    .container {
      background: white;
      border-radius: 10px;
      box-shadow: 0 0 10px #ccc;
      max-width: 500px;
      margin: auto;
      padding: 30px;
    }

    .avatar {
      width: 150px;
      border-radius: 50%;
      margin-bottom: 20px;
    }

    button {
      padding: 10px 20px;
      font-size: 16px;
      background-color: #0077cc;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    button:hover {
      background-color: #005fa3;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Xin chào, mình là An!</h1>
    <img src="https://i.imgur.com/4AiXzf8.jpeg" alt="Ảnh đại diện" class="avatar">
    <p>Mình đang học lập trình web với HTML, CSS và JavaScript.</p>
    <button onclick="chao()">Nhấn để chào</button>
  </div>

  <script>
    function chao() {
      alert("Chào bạn! Cảm ơn đã ghé thăm trang web của mình 😊");
    }
  </script>
</body>
</html>
