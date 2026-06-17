<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Isac Andrade — Profile Header</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    .card {
      background: #0d1117;
      border-radius: 12px;
      padding: 48px 52px 52px;
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
      max-width: 640px;
    }

    .greeting {
      font-size: 11px;
      color: #58a6ff;
      letter-spacing: 3px;
      text-transform: uppercase;
      opacity: 0.55;
      margin-bottom: 20px;
      font-family: 'Fira Code', 'Courier New', monospace;
    }

    .name {
      font-size: 38px;
      font-weight: 700;
      color: #e6edf3;
      letter-spacing: -1px;
      line-height: 1;
      margin-bottom: 6px;
    }

    .name-sub {
      font-size: 13px;
      color: #484f58;
      letter-spacing: 0.3px;
      margin-bottom: 28px;
    }

    .accent {
      width: 32px;
      height: 2px;
      background: #58a6ff;
      border-radius: 2px;
      opacity: 0.6;
      margin-bottom: 28px;
    }

    .typing {
      font-size: 16px;
      color: #e6edf3;
      min-height: 26px;
      font-family: 'Fira Code', 'Courier New', monospace;
      letter-spacing: 0.2px;
    }

    .cursor {
      display: inline-block;
      width: 2px;
      height: 18px;
      background: #58a6ff;
      margin-left: 3px;
      vertical-align: middle;
      animation: blink 0.8s step-end infinite;
    }

    @keyframes blink {
      50% { opacity: 0; }
    }
  </style>
</head>
<body>

  <div class="card">
    <p class="greeting">// hello world</p>
    <h1 class="name">Isac Andrade</h1>
    <p class="name-sub">Brazil · Software Developer</p>
    <div class="accent"></div>
    <p class="typing" id="typing"></p>
  </div>

</body>
</html>
