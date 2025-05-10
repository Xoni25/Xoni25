<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>XONI - Futuristic DJ</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Orbitron', sans-serif;
      background-color: #0d0d0d;
      color: #00fff7;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      text-align: center;
    }header {
  font-size: 2.5rem;
  text-shadow: 0 0 10px #00fff7, 0 0 20px #00bcd4;
  margin-bottom: 20px;
}

.intro {
  max-width: 600px;
  padding: 0 20px;
  line-height: 1.6;
  color: #e0f7fa;
}
.background-glow { 
.background-glow {
  position: absolute;
  width: 100%;
  height: 100%;
  background: radial-gradient(circle at center, rgba(0,255,247,0.15), transparent 70%);
  animation: pulse 3s infinite ease-in-out;
  z-index: -1;
}

@keyframes pulse {
  0%, 100% { opacity: 0.2; }
  50% { opacity: 0.5; }
}
  position: absolute;
  width: 100%;
  height: 100%;
  background: radial-gradient(circle at center, rgba(0,255,247,0.15), transparent 70%);
  animation: pulse 3s infinite ease-in-out;
  z-index: -1;
}

@keyframes pulse {
  0%, 100% { opacity: 0.2; }
  50% { opacity: 0.5; }
}
.neon-button {
  margin-top: 30px;
  padding: 15px 30px;
  background: transparent;
  border: 2px solid #00fff7;
  color: #00fff7;
  text-transform: uppercase;
  font-weight: bold;
  cursor: pointer;
  transition: all 0.3s ease;
  box-shadow: 0 0 10px #00fff7, 0 0 20px #00bcd4;
}

.neon-button:hover {
  background: #00fff7;
  color: #0d0d0d;
  box-shadow: 0 0 20px #00fff7, 0 0 30px #00bcd4;
}

  </style>
</head>
<body>
  <header>Welcome to XONI's World</header>
  <div class="intro">
    <p>XONI is a virtual DJ, mixing the future with the present. Follow the beat, feel the neon pulse, and get lost in sound.</p>
    <button class="neon-button">Listen Now</button>
  </div>
</body>
</html>
