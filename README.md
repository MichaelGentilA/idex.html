# idex.html

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>João Alexandre | Links</title>

  <!-- Fonte -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

  <!-- Ícones -->
  <script src="https://kit.fontawesome.com/yourcode.js" crossorigin="anonymous"></script>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      height: 100vh;
      background: linear-gradient(270deg, #0f2027, #203a43, #2c5364);
      background-size: 600% 600%;
      animation: gradient 10s ease infinite;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #fff;
    }

    @keyframes gradient {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    .container {
      text-align: center;
      width: 90%;
      max-width: 420px;
      backdrop-filter: blur(10px);
      background: rgba(255,255,255,0.05);
      border-radius: 15px;
      padding: 30px 20px;
      box-shadow: 0 0 25px rgba(0,0,0,0.3);
    }

    .profile-img {
      width: 110px;
      height: 110px;
      border-radius: 50%;
      border: 3px solid #00d4ff;
      margin-bottom: 15px;
    }

    h1 {
      font-size: 26px;
      margin-bottom: 5px;
    }

    p {
      font-size: 14px;
      color: #ccc;
      margin-bottom: 25px;
    }

    .link {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 10px;
      text-decoration: none;
      color: #fff;
      background: rgba(255,255,255,0.1);
      padding: 12px;
      border-radius: 10px;
      margin: 10px 0;
      transition: 0.3s;
      border: 1px solid rgba(255,255,255,0.2);
    }

    .link:hover {
      background: #00d4ff;
      color: #000;
      transform: translateY(-3px) scale(1.03);
    }

    footer {
      margin-top: 20px;
      font-size: 12px;
      color: #aaa;
    }
  </style>
</head>
<body>

  <div class="container">
    <img src="https://via.placeholder.com/110" class="profile-img" alt="Foto">

    <h1>João Alexandre</h1>
    <p>Estudante de Análise e Desenvolvimento de Sistemas 🚀</p>

    <a href="#" class="link">🌐 Portfólio</a>
    <a href="#" class="link">💼 LinkedIn</a>
    <a href="#" class="link">🐙 GitHub</a>
    <a href="#" class="link">📂 Projetos</a>
    <a href="#" class="link">📧 Contato</a>

    <footer>
      © 2026 João Alexandre
    </footer>
  </div>

</body>
</html>
