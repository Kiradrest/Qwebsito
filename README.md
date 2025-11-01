my-website/
│
├── index.html
├── style.css
└── script.js# Qwebsito
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Website Pertama Saya</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Halo, Selamat Datang di Website Saya!</h1>
  </header>

  <main>
    <p>Ini website pertama saya yang dihosting di GitHub Pages 🚀</p>
    <button onclick="sayHello()">Klik Saya</button>
  </main>

  <footer>
    <p>© 2025 Dibuat oleh [Nama Kamu]</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  text-align: center;
  background-color: #f9f9f9;
  color: #333;
  margin: 0;
  padding: 0;
}

header {
  background-color: #0078d7;
  color: white;
  padding: 20px 0;
}

button {
  padding: 10px 20px;
  background-color: #0078d7;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

button:hover {
  background-color: #005fa3;
}
function sayHello() {
  alert("Halo! Terima kasih sudah mampir 😊");
}
