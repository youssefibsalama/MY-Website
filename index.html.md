<!DOCTYPE html>  
<html lang="en">  
<head>  
  <meta charset="UTF-8" />  
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />  
  <title>For Mory ❤️</title>  
  <style>  
    * { box-sizing: border-box; }  
    body {  
      margin: 0;  
      font-family: 'Georgia', serif;  
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);  
      color: #2d2d2d;  
      text-align: center;  
    }  
    section {  
      min-height: 100vh;  
      display: flex;  
      flex-direction: column;  
      justify-content: center;  
      align-items: center;  
      padding: 50px 18px;  
    }  
    h1 {  
      font-size: clamp(2.2rem, 6vw, 3rem);  
      margin-bottom: 12px;  
    }  
    h2 {  
      font-size: clamp(1.6rem, 5vw, 2.2rem);  
      margin-bottom: 18px;  
    }  
    p {  
      max-width: 680px;  
      font-size: clamp(1.05rem, 4vw, 1.25rem);  
      line-height: 1.9;  
    }  
    .heart {  
      font-size: clamp(2.5rem, 8vw, 3.2rem);  
      animation: pulse 1.5s infinite;  
      margin: 22px 0;  
    }  
    @keyframes pulse {  
      0% { transform: scale(1); }  
      50% { transform: scale(1.2); }  
      100% { transform: scale(1); }  
    }  
    button {  
      margin-top: 30px;  
      padding: 14px 28px;  
      border: none;  
      border-radius: 999px;  
      background: #ff5e78;  
      color: white;  
      font-size: 1rem;  
      cursor: pointer;  
      width: 90%;  
      max-width: 320px;  
    }  
    button:hover {  
      background: #ff2f55;  
    }  
    .music {  
      font-size: 0.9rem;  
      opacity: 0.85;  
      margin-top: 18px;  
    }  
  </style>  
</head>  
<body>  
  
<script>  
  const password = prompt("Enter our date (DD/MM/YYYY)");  
  if (password !== "27/3/2022") {  
    document.body.innerHTML = "<h1 style='margin-top:40vh;font-family:Georgia;'>This space is only for us ❤️</h1>";  
    throw new Error('Access denied');  
  }("Enter our date (DD/MM/YYYY)");  
  if (password !== "27/3/2022") {  
    document.body.innerHTML = "<h1 style='margin-top:40vh;font-family:Georgia;'>This space is only for us ❤️</h1>";  
  }  
</script>  
  
<audio autoplay loop>  
  <source src="https://cdn.pixabay.com/download/audio/2022/03/15/audio_0c8f1c0e63.mp3?filename=romantic-piano-112191.mp3" type="audio/mpeg">  
</audio>  
  
  <section id="intro">  
    <h1>Mory ❤️</h1>  
    <p>This little corner of the internet exists for one reason — you.</p>  
    <div class="heart">💗</div>  
    <button onclick="document.getElementById('story').scrollIntoView({behavior:'smooth'})">Start</button>  
    <div class="music">🎶 Put on a Tamer Hosny song before you continue</div>  
  </section>  
  
  <section id="story">  
    <h2>Where It All Started</h2>  
    <p>  
      We were together in church — and somehow, in that simple place,  
      something beautiful began. I didn’t know then how much you would  
      change my life, but I knew you were different.  
    </p>  
    <button onclick="document.getElementById('reasons').scrollIntoView({behavior:'smooth'})">Next</button>  
  </section>  
  
  <section id="reasons">  
    <h2>Why I Love You</h2>  
    <p>  
      I could try to list reasons… but the truth is:  
      I love <strong>everything</strong> about you.  
      Your heart. Your soul. Your presence.  
      You feel like home — even from miles away.  
    </p>  
    <div class="heart">💞</div>  
    <button onclick="document.getElementById('future').scrollIntoView({behavior:'smooth'})">Next</button>  
  </section>  
  
  <section id="future">  
    <h2>What I’m Waiting For</h2>  
    <p>  
      I dream about the day I come back —  
      when we finally do all the things we planned.  
      Every laugh, every walk, every moment.  
      Distance won’t win. Love like ours never lets it.  
    </p>  
    <p><strong>Until then — my heart is already with you.</strong></p>  
    <div class="heart">❤️</div>  
  </section>  
  
  <section id="secret">  
    <h2>One Last Thing…</h2>  
    <p>  
      If you’re reading this, then I want you to know something important.  
      You are my safety. My warmth. My excitement. My calm.  
    </p>  
    <p>  
      I can’t wait for the day I come back —  
      when distance disappears and all our plans finally become real.  
      Until that moment, every heartbeat I have is already yours.  
    </p>  
    <div class="heart">🥹❤️🔥</div>  
    <p><strong>I love you, Mory. Always.</strong></p>  
  </section>  
  
<section id="final" style="background:linear-gradient(135deg,#fbc2eb,#a6c1ee);">  
  <h2>Forever Means This</h2>  
  <p>  
    If you reached this part, I want you to know something very simple and very true.  
    I choose you — in distance, in waiting, in love, and in every future version of us.  
  </p>  
  <p>  
    No matter how far I am, no matter how long it takes,  
    I am coming back to you.  
  </p>  
  <div class="heart">💍❤️</div>  
  <p><strong>You are my forever, Mory.</strong></p>  
</section>  
  
</body>  
</html>  
