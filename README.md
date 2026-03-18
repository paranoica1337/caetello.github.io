[caetello.html](https://github.com/user-attachments/files/26082094/caetello.html)
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Мой профиль</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css" />
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: Arial, Helvetica, sans-serif;
      background:
        radial-gradient(circle at top, #1a1a1a 0%, #0d0d0d 35%, #050505 100%);
      color: #f2f2f2;
      overflow: hidden;
    }

    .background-glow {
      position: fixed;
      inset: 0;
      pointer-events: none;
      background:
        radial-gradient(circle at 50% 45%, rgba(255,255,255,0.05), transparent 25%),
        radial-gradient(circle at 20% 80%, rgba(255,255,255,0.025), transparent 20%),
        radial-gradient(circle at 80% 20%, rgba(255,255,255,0.025), transparent 20%);
      filter: blur(10px);
    }

    .card {
      position: relative;
      width: min(92vw, 430px);
      padding: 42px 28px;
      border-radius: 28px;
      background: linear-gradient(180deg, #181818 0%, #111111 100%);
      border: 1px solid rgba(255, 255, 255, 0.08);
      box-shadow:
        0 20px 60px rgba(0, 0, 0, 0.55),
        inset 0 1px 0 rgba(255, 255, 255, 0.05);
      text-align: center;
      backdrop-filter: blur(8px);
    }

    h1 {
      font-size: 30px;
      font-weight: 700;
      margin-bottom: 12px;
      letter-spacing: 0.5px;
    }

    .subtitle {
      color: #a8a8a8;
      font-size: 14px;
      line-height: 1.5;
      margin-bottom: 30px;
    }

    .socials {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 16px;
      margin-top: 4px;
    }

    .icon-link {
      width: 58px;
      height: 58px;
      border-radius: 18px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-decoration: none;
      background: linear-gradient(180deg, #202020 0%, #171717 100%);
      border: 1px solid rgba(255, 255, 255, 0.08);
      box-shadow: inset 0 1px 0 rgba(255,255,255,0.04);
      transition: transform 0.2s ease, background 0.2s ease, border-color 0.2s ease;
    }

    .icon-link:hover {
      transform: translateY(-3px) scale(1.05);
      background: linear-gradient(180deg, #2a2a2a 0%, #1b1b1b 100%);
      border-color: rgba(255, 255, 255, 0.25);
      box-shadow:
        0 0 12px rgba(255,255,255,0.15),
        0 0 24px rgba(255,255,255,0.08);
    }

    .icon-link i {
      font-size: 24px;
      color: #f5f5f5;
      line-height: 1;
      transition: transform 0.2s ease, text-shadow 0.2s ease;
    }

    .icon-link:hover i {
      transform: scale(1.15);
      text-shadow: 0 0 8px rgba(255,255,255,0.6);
    }

    .footer {
      margin-top: 24px;
      font-size: 12px;
      color: #7f7f7f;
      letter-spacing: 0.3px;
    }

    @media (max-width: 480px) {
      .card {
        padding: 30px 20px;
        border-radius: 24px;
      }

      h1 {
        font-size: 26px;
      }

      .socials {
        gap: 12px;
      }

      .icon-link {
        width: 54px;
        height: 54px;
        border-radius: 16px;
      }
    }
  </style>
</head>
<body>
  <div class="background-glow"></div>

  <main class="card">
    <h1>caetello</h1>
    <p class="subtitle">
      Discord<br>
      caetellouwu
    </p>

    <div class="socials">
      <a class="icon-link" href="https://steamcommunity.com/id/tx0" target="_blank" aria-label="Steam">
        <i class="bi bi-steam"></i>
      </a>

      <a class="icon-link" href="https://instagram.com/caetellouwu" target="_blank" aria-label="Instagram">
        <i class="bi bi-instagram"></i>
      </a>

      <a class="icon-link" href="https://t.me/caetellouwu" target="_blank" aria-label="Telegram">
        <i class="bi bi-telegram"></i>
      </a>
    </div>

    <div class="footer"></div>
  </main>
</body>
</html>
