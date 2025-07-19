<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>May I Court You? 💘</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: radial-gradient(circle at top left, #ffe0ec, #fff5f8);
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: flex-start;
      min-height: 100vh;
      overflow-x: hidden;
      text-align: center;
      position: relative;
    }
    h1 {
      font-size: 3rem;
      color: #d6336c;
      animation: pulse 2s infinite;
    }
    @keyframes pulse {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.05); }
    }
    .message {
      margin-top: 20px;
      max-width: 90%;
      padding: 20px;
      background-color: #fff0f5;
      border-radius: 16px;
      color: #444;
      font-size: 1rem;
      text-align: left;
      white-space: pre-wrap;
      line-height: 1.6;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }
    p, .message-intro {
      font-size: 1.2rem;
      margin: 20px;
      max-width: 600px;
      color: #444;
      background: #ffffffc7;
      padding: 10px 20px;
      border-radius: 12px;
    }
    #buttons {
      margin-top: 40px;
    }
    button {
      padding: 15px 30px;
      font-size: 1.1rem;
      border: none;
      border-radius: 30px;
      margin: 10px;
      cursor: pointer;
      transition: 0.3s ease;
      box-shadow: 0px 4px 12px rgba(0,0,0,0.1);
    }
    #yesBtn {
      background-color: #ff6f91;
      color: white;
      animation: bounce 1.5s infinite;
    }
    @keyframes bounce {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-8px); }
    }
    #noBtn {
      background-color: #fce4ec;
      color: #8e24aa;
      position: absolute;
    }
    .heart {
      position: absolute;
      top: -10px;
      width: 20px;
      height: 20px;
      background: pink;
      transform: rotate(45deg);
      animation: fall 5s linear infinite;
      z-index: 0;
    }
    .heart::before,
    .heart::after {
      content: "";
      position: absolute;
      width: 20px;
      height: 20px;
      background: pink;
      border-radius: 50%;
    }
    .heart::before {
      top: -10px;
      left: 0;
    }
    .heart::after {
      top: 0;
      left: -10px;
    }
    @keyframes fall {
      0% { transform: translateY(-10px) rotate(45deg); opacity: 1; }
      100% { transform: translateY(100vh) rotate(45deg); opacity: 0; }
    }
    #letterBtn, #surpriseBtn {
      margin-top: 20px;
      background: #ffd6e0;
      color: #8c2f39;
    }
    footer {
      position: relative;
      bottom: 10px;
      font-size: 0.9rem;
      color: #888;
    }
    #surpriseMsg {
      display: none;
      font-size: 1.5rem;
      color: #d6336c;
      background-color: #fff0f5;
      padding: 15px;
      border-radius: 20px;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <div class="message">
    <strong>Hello Paula,</strong><br><br>
    First of all, thank you — truly — for spending almost four beautiful months getting to know each other again. It still amazes me how everything seemed to align for us to reconnect, like the universe had this little plan all along. Every conversation we've had, no matter how random or deep, has led me to rediscover you — not just the you I once knew, but the you you've become… and wow, I’m so glad I got to meet her again.

    When you reached out — even if it was through Jaja — alam mo ba, I was really hoping for something like that. I had been quietly waiting, not expecting, but hoping. And when it finally happened, it felt like all the prayers, all the quiet manifestations I made for the past 2 to 3 years suddenly found their way back to me… through you. It felt surreal. Like life handed me the exact person I was trying to forget, only to realize I never truly wanted to.

    Of course, I won’t pretend that our RPW days didn’t hurt. They did — and not just once, but many times over. HAHAHAHA. But I know, deep inside, it wasn’t just me who felt that pain. You were hurting too. And in those moments, even when I was hurt, even after everything, I still loved you. I still *chose* you — in silence, in thought, and in heart.

    I’ve been in a relationship since then — one with someone I thought I really liked, someone who was actually an old crush. But during that time, I realized something painfully clear: it wasn’t her I truly wanted. Being with her made me realize the difference between being with someone who fits the surface versus someone who touches your soul. With her, it felt like effort; with you, it felt like home.

    I can’t even explain how or when it happened, but you became the person I kept seeing in every little “what if” scenario in my head — those quiet moments when I wondered, “Paano kung makasabay ko siya sa mall?” or “What if nagkita kami ulit sa ganitong lugar?” — those little daydreams that never left. You were always there, tucked into the back of my mind, like a quiet wish I was too afraid to say out loud.

    And then, our early talks — grabe, I was so nervous. I was scared to try again, scared to mess things up, scared that maybe you'd changed or maybe I had. But you — you reminded me that your intentions were genuine. And that alone gave me comfort. The way you spoke to me, the way you let me in again… I felt safe. I felt seen.

    Now, every interaction we have, no matter how small, feels meaningful. I value this connection so much. And whatever this is, whatever it turns into, I want you to know that I appreciate you — deeply and sincerely. Thank you for coming back into my life, Paula. Thank you for being you.

    Let’s continue writing whatever chapter this is together — slow, steady, and honest. I'm here for it. I'm here for *you*.

    — Me
  </div>

  <h1>Can I Court You? 🥺👉👈</h1>
  <p class="message-intro">I made this page just for you. I could’ve just said it in chat, but where’s the fun in that? 😅<br>
     You’re amazing, and I’d be honored to take a step closer to your world 💗</p>

  <div id="buttons">
    <button id="yesBtn">Yes, you may ❤️</button>
    <button id="noBtn">No, you may not 😅</button>
  </div>

  <button id="letterBtn">Read my heart 💌</button>
  <button id="surpriseBtn">Click for a sweet surprise 🍭</button>
  <div id="surpriseMsg">You’re even more beautiful when you smile 😍</div>

  <footer>Hand-coded with love &lt;3</footer>

  <script>
    const noBtn = document.getElementById('noBtn');
    noBtn.addEventListener('mouseover', () => {
      const x = Math.random() * (window.innerWidth - noBtn.offsetWidth);
      const y = Math.random() * (window.innerHeight - noBtn.offsetHeight);
      noBtn.style.left = `${x}px`;
      noBtn.style.top = `${y}px`;
    });

    document.getElementById('yesBtn').addEventListener('click', () => {
      confetti();
      alert("YESSSS!!! 😭 Thank you! You just made my whole month!");
    });

    document.getElementById('letterBtn').addEventListener('click', () => {
      const win = window.open('', '_blank', 'width=400,height=500');
      win.document.write(`
        <h2 style='color:#d6336c;'>Dear Crush 💖,</h2>
        <p style='font-family: sans-serif;'>
        You light up my days like the sun peeking after a rainy afternoon.
        I admire not only your beauty but your kindness, your humor, and that spark in your eyes.
        Getting the chance to know you more, to make you smile on purpose — that would mean the world to me.<br><br>
        This page is silly, but my intentions are real.
        Would you let me make you feel special — every single day?
        </p>
        <p style='text-align:right; margin-top:30px;'>— Your hopeful coder 💻💘</p>
      `);
    });

    document.getElementById('surpriseBtn').addEventListener('click', () => {
      const msg = document.getElementById('surpriseMsg');
      msg.style.display = 'block';
      msg.style.animation = 'pulse 1s ease';
    });

    function createHeart() {
      const heart = document.createElement('div');
      heart.classList.add('heart');
      heart.style.left = Math.random() * window.innerWidth + 'px';
      document.body.appendChild(heart);
      setTimeout(() => heart.remove(), 5000);
    }
    setInterval(createHeart, 250);

    function confetti() {
      for (let i = 0; i < 100; i++) {
        const conf = document.createElement('div');
        conf.style.width = '10px';
        conf.style.height = '10px';
        conf.style.background = `hsl(${Math.random()*360}, 100%, 70%)`;
        conf.style.position = 'absolute';
        conf.style.left = Math.random()*100 + '%';
        conf.style.top = '-20px';
        conf.style.opacity = 1;
        conf.style.transition = 'top 2s ease, opacity 2s';
        conf.style.borderRadius = '50%';
        document.body.appendChild(conf);
        setTimeout(() => {
          conf.style.top = Math.random()*100 + '%';
          conf.style.opacity = 0;
        }, 100);
        setTimeout(() => conf.remove(), 2100);
      }
    }
  </script>
</body>
</html>
