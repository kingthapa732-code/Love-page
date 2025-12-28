<!DOCTYPE html>  
<html lang="en">  
<head>  
  <meta charset="UTF-8">  
  <title>For You ❤️</title>  
  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">  
  
  <style>  
    body {  
      margin: 0;  
      min-height: 100vh;  
      font-family: 'Segoe UI', sans-serif;  
      background: linear-gradient(135deg, #ff758c, #ff7eb3);  
      display: flex;  
      align-items: center;  
      justify-content: center;  
    }  
  
    .container {  
      background: rgba(255, 255, 255, 0.18);  
      backdrop-filter: blur(12px);  
      border-radius: 20px;  
      padding: 30px;  
      width: 90%;  
      max-width: 420px;  
      text-align: center;  
      color: white;  
      box-shadow: 0 10px 30px rgba(0,0,0,0.15);  
    }  
  
    h1 {  
      margin-bottom: 8px;  
    }  
  
    p {  
      opacity: 0.9;  
      margin-bottom: 20px;  
    }  
  
    button {  
      width: 100%;  
      padding: 14px;  
      margin: 10px 0;  
      border: none;  
      border-radius: 30px;  
      background: white;  
      color: #ff4d6d;  
      font-size: 16px;  
      font-weight: 600;  
      cursor: pointer;  
      transition: transform 0.2s ease, box-shadow 0.2s ease;  
    }  
  
    button:hover {  
      transform: scale(1.03);  
      box-shadow: 0 6px 14px rgba(0,0,0,0.15);  
    }  
  
    #message {  
      margin-top: 25px;  
      font-size: 18px;  
      min-height: 70px;  
      opacity: 0;  
      transition: opacity 0.3s ease;  
    }  
  </style>  
  
  <script>  
    function showMessage(text) {  
      const msg = document.getElementById("message");  
      msg.style.opacity = 0;  
      setTimeout(() => {  
        msg.innerText = text;  
        msg.style.opacity = 1;  
      }, 200);  
    }  
  </script>  
</head>  
  
<body>  
  
  <div class="container">  
    <h1>Hey Love ❤️</h1>  
    <p>Tap the buttons below</p>  
  
    <button onclick="showMessage('I fell in love with you without even noticing. It just happened naturally.')">  
      Why I Love You  
    </button>  
  
    <button onclick="showMessage('Your presence feels like home, and your smile makes everything feel right.')">  
      How You Make Me Feel  
    </button>  
  
    <button onclick="showMessage('Loving you is the easiest and most beautiful thing I have ever done.')">  
      What You Mean to Me  
    </button>  
  
    <button onclick="showMessage('No matter what happens, I choose you. Today, tomorrow, always.')">  
      My Promise  
    </button>  
  
    <button onclick="showMessage('You are not just someone I love — you are my safe place.')">  
      One More Thing ❤️  
    </button>  
  
    <div id="message"></div>  
  </div>  
  
</body>  
</html>  
