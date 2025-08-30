<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Download My App</title>
  <style>
    /* Body & Background */
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(to bottom right, #1e3c72, #2a5298);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      color: #fff;
      text-align: center;
      overflow: hidden;
    }

    /* Animated floating circles */
    .circle {
      position: absolute;
      border-radius: 50%;
      opacity: 0.3;
      animation: float 10s infinite;
    }

    .circle:nth-child(1){width:150px;height:150px;top:10%;left:15%;background:#ff6b6b;animation-delay:0s;}
    .circle:nth-child(2){width:100px;height:100px;top:50%;left:70%;background:#feca57;animation-delay:2s;}
    .circle:nth-child(3){width:120px;height:120px;top:80%;left:30%;background:#48dbfb;animation-delay:4s;}

    @keyframes float {
      0% {transform: translateY(0px);}
      50% {transform: translateY(-30px);}
      100% {transform: translateY(0px);}
    }

    /* Heading */
    h1 {
      font-size: 3em;
      margin-bottom: 10px;
      text-shadow: 2px 2px 10px rgba(0,0,0,0.5);
    }

    /* Subtext */
    p {
      font-size: 1.2em;
      margin-bottom: 40px;
      text-shadow: 1px 1px 5px rgba(0,0,0,0.3);
    }

    /* Download Button */
    a button {
      background: linear-gradient(45deg, #ff6b6b, #f06595);
      border: none;
      padding: 20px 60px;
      font-size: 1.5em;
      color: white;
      border-radius: 50px;
      cursor: pointer;
      box-shadow: 0 8px 15px rgba(0,0,0,0.3);
      transition: all 0.3s ease;
    }

    a button:hover {
      transform: scale(1.1);
      box-shadow: 0 12px 20px rgba(0,0,0,0.4);
    }

    /* Info Box */
    .info-box {
      background: rgba(255,255,255,0.1);
      padding: 20px 40px;
      border-radius: 20px;
      margin-top: 30px;
      backdrop-filter: blur(10px);
      box-shadow: 0 8px 15px rgba(0,0,0,0.2);
    }

    .info-box p {
      margin: 5px 0;
      font-size: 1em;
      color: #fff;
    }
  </style>
</head>
<body>

  <!-- Floating circles -->
  <div class="circle"></div>
  <div class="circle"></div>
  <div class="circle"></div>

  <h1>MyApp APK</h1>
  <p>Click below to download the latest version</p>

  <a href="[https://github.com/hshahzsh02-ops/TAPTAPSEND/releases/download/v1.0/app.apk]" download>
    <button>Download APK</button>
  </a>

  <div class="info-box">
    <p>Version: 1.0</p>
    <p>File size: 25 MB</p>
    <p>Compatible: Android 5.0+</p>
  </div>

</body>
</html># TAPTAPSEND
Fast transfer/service. Trusted wallet
