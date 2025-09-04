
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Have a Nice Day</title>
  <style>
    body {
      background-color: #0f0f0f;
      color: #00ffff;
      font-family: 'Courier New', Courier, monospace;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      margin: 0;
    }

    .container {
      text-align: center;
      border: 2px solid #00ffff;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 0 20px #00ffff;
      animation: pulse 2s infinite;
    }

    h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }

    p {
      font-size: 1.2em;
      margin-top: 0;
    }

    .signature {
      margin-top: 20px;
      font-size: 0.9em;
      color: #cccccc;
    }

    @keyframes pulse {
      0% { box-shadow: 0 0 10px #00ffff; }
      50% { box-shadow: 0 0 30px #00ffff; }
      100% { box-shadow: 0 0 10px #00ffff; }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Hello, mine  👋</h1>
    <p>Just a quick ping from Deveh to say:</p>
    <p><strong>Have a nice day you sexy animal!</strong></p>
    <div class="signature">— "Remember, you have incredible power within you!"</div>
  </div>
</body>
</html>
