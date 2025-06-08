<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <title>Hai Kamu 🌼</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #fbc2eb, #a6c1ee);
      text-align: center;
      padding: 50px;
      color: #333;
    }
    h1 {
      font-size: 36px;
    }
    p {
      font-size: 20px;
      margin: 10px 0;
    }
    button {
      margin-top: 20px;
      font-size: 18px;
      padding: 10px 25px;
      background: #ffb3c6;
      border: none;
      border-radius: 12px;
      cursor: pointer;
      color: white;
    }
    button:hover {
      background: #ff8fab;
    }
    #messages {
      margin-top: 30px;
      font-size: 22px;
      font-style: italic;
    }
  </style>
</head>
<body>
  <h1>Hai kamu 👋</h1>
  <p>Lagi lihat ini ya?</p>
  <button onclick="showMessage()">Klik untuk pesan rahasia 🎁</button>

  <div id="messages"></div>

  <script>
    const messages = [
      "Semoga harimu menyenangkan ya! 😊",
      "Jangan lupa makan dan istirahat cukup 🍽️💤",
      "Kamu itu unik dan berharga ✨",
      "Aku senang bisa kenal kamu, walau cuma sebentar 🌼",
      "Kadang dunia cuma butuh senyummu untuk jadi lebih baik 😌"
    ];

    function showMessage() {
      const i = Math.floor(Math.random() * messages.length);
      document.getElementById("messages").innerText = messages[i];
    }
  </script>
</body>
</html>
