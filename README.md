# Thunderstev
Bug master all about deploying more
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Floating Word on Colorful BG</title>
  <style>
    /* Full‑screen gradient background */
    body, html {
      margin: 0;
      height: 100%;
      overflow: hidden;
      background: linear-gradient(135deg, #ff6b6b, #feca57, #48dbfb, #1dd1a1, #5f27cd);
      background-size: 400% 400%;
      animation: bgMove 20s ease infinite;
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: sans-serif;
    }
    @keyframes bgMove {
      0% {background-position: 0% 50%;}
      50% {background-position: 100% 50%;}
      100% {background-position: 0% 50%;}
    }
    /* The floating word */
    .float-word {
      font-size: 4rem;
      color: #fff;
      text-shadow: 0 2px 10px rgba(0,0,0,0.6);
      animation: float 6s ease-in-out infinite, pulse 2s ease-in-out infinite;
    }
    @keyframes float {
      0% {transform: translateX(-100%) translateY(-20%);}
      25% {transform: translateX(0) translateY(0);}
      50% {transform: translateX(100%) translateY(-20%);}
      75% {transform: translateX(0) translateY(0);}
      100% {transform: translateX(-100%) translateY(-20%);}
    }
    @keyframes pulse {
      0% {transform: scale(1);}
      50% {transform: scale(1.1);}
      100% {transform: scale(1);}
    }
  </style>
</head>
<body>
  <div class="float-word">Hi every one my name is stev the bug master Follow this link to see my work
    👉👉
  </div>
  <div class="float-word"></div>
  
</body>
</html>
