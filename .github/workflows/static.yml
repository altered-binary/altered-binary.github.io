<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Altered Binary</title>
  <style>
    :root {
      --bg: #0a0a0a;
      --fg: #eaeaea;
      --muted: #888;
      --accent: #00ffcc;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Inter", "Segoe UI", sans-serif;
    }

    body {
      background: var(--bg);
      color: var(--fg);
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .center {
      display: flex;
      align-items: center;
      gap: 14px;
    }

    .logo {
      font-weight: 600;
      letter-spacing: 3px;
      font-size: 18px;
    }

    .logo span {
      color: var(--accent);
    }

    .binary {
      font-size: 13px;
      color: var(--muted);
      letter-spacing: 2px;
      font-family: monospace;
      animation: flicker 2s infinite alternate;
    }

    @keyframes flicker {
      0%   { opacity: 0.4; }
      20%  { opacity: 1; }
      40%  { opacity: 0.5; }
      60%  { opacity: 1; }
      80%  { opacity: 0.6; }
      100% { opacity: 1; }
    }
  </style>
</head>
<body>

  <div class="center">
    <div class="logo">ALTERED <span>BINARY</span></div>
    <div class="binary">01001101 → 01011101</div>
  </div>

</body>
</html>
