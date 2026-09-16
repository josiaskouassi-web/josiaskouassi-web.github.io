<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0">
<title>Opération.. Proposer un date a elsie</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,500;1,600&family=Quicksand:wght@400;500;600;700&family=Caveat:wght@500;600&display=swap" rel="stylesheet">
<style>

  :root{
    --snow-white:  #fffdfe;
    --blush:       #fbdce6;
    --blush-deep:  #f6c3d6;
    --rose:        #e8a6c1;
    --rose-deep:   #c9628f;
    --plum:        #5c3a4c;
    --plum-soft:   #8a5f72;
    --radius:      28px;
  }

  *{ box-sizing: border-box; -webkit-tap-highlight-color: transparent; }

  html, body{
    margin:0; padding:0; height:100%;
    overflow:hidden;
    font-family:'Quicksand', sans-serif;
    color: var(--plum);
    background: linear-gradient(180deg, var(--snow-white) 0%, #fdeef3 55%, var(--blush) 100%);
  }

  #snow{
    position:fixed; inset:0; width:100%; height:100%;
    z-index:1; pointer-events:none;
  }

  .hills{ position:fixed; left:0; right:0; bottom:-4vh; height:34vh; z-index:2; pointer-events:none; }
  .hill{ position:absolute; bottom:0; width:70%; height:100%; border-radius:50% 50% 0 0 / 100% 100% 0 0; }
  .hill--back{ left:-10%; width:80%; background: var(--blush); opacity:0.55; height:80%; }
  .hill--mid{ right:-15%; width:75%; background: var(--blush-deep); opacity:0.55; height:65%; }
  .hill--front{ left:8%; width:90%; background: var(--snow-white); height:50%; }

  .stage{
    position:relative; z-index:3; height:100%;
    display:flex; align-items:center; justify-content:center;
    padding: 20px;
  }

  .card{
    position:relative;
    width:100%; max-width:440px;
    padding: 44px 32px 36px;
    text-align:center;
    background: rgba(255,255,255,0.55);
    border: 1px solid rgba(255,255,255,0.8);
    border-radius: var(--radius);
    backdrop-filter: blur(18px);
    -webkit-backdrop-filter: blur(18px);
    box-shadow: 0 30px 60px -25px rgba(201,98,143,0.35);
    overflow:hidden;
  }

  .content{ position:relative; }

  .eyebrow{
    font-size: 13px; letter-spacing: 0.14em; text-transform: uppercase;
    color: var(--rose-deep); margin: 0 0 16px; font-weight:600;
  }

  h1{
    font-family:'Cormorant Garamond', serif;
    font-style: italic; font-weight: 600;
    font-size: clamp(26px, 6vw, 36px);
    line-height: 1.2; margin: 0 0 14px; color: var(--plum);
  }
  h1 span{ color: var(--rose-deep); font-style:normal; }
  .h1-small{ font-size: clamp(21px, 5vw, 26px); }

  .sub{ font-size: 15px; line-height:1.6; color: var(--plum-soft); margin: 0 0 28px; }

  /* frost wipe reveal (only on first screen, on load) */
  .frost-wipe{
    position:absolute; inset: -10% -20%;
    background: linear-gradient(100deg, var(--snow-white) 40%, rgba(255,255,255,0.85) 60%, transparent 100%);
    z-index: 5; transform: translateX(0%);
    animation: wipe 1.6s 0.4s cubic-bezier(.7,0,.3,1) forwards;
    pointer-events:none;
  }
  @keyframes wipe{ to{ transform: translateX(115%); } }

  /* ---------- Screens ---------- */
  .screen{ display:none; position:relative; }
  .screen.active{ display:block; animation: screenIn 0.5s ease; }
  @keyframes screenIn{ from{ opacity:0; transform:translateY(8px);} to{ opacity:1; transform:translateY(0);} }

  #screen-ask{ position:relative; }

  /* ---------- Buttons ---------- */
  .actions--primary{ margin-bottom:12px; }
  .actions--secondary{ display:flex; gap:10px; justify-content:center; }

  .btn{
    font-family:'Quicksand', sans-serif;
    font-weight:600; font-size:15px;
    border-radius:999px; border:none; cursor:pointer;
    padding:14px 26px;
    transition: transform 0.35s ease, box-shadow 0.25s ease;
  }
  .btn:focus-visible{ outline: 3px solid var(--rose-deep); outline-offset: 3px; }

  .btn--primary{
    width:100%;
    background: linear-gradient(135deg, var(--rose) 0%, var(--rose-deep) 100%);
    color: #fff;
    box-shadow: 0 12px 24px -10px rgba(201,98,143,0.6);
  }
  .btn--primary:hover{ transform: translateY(-2px) scale(var(--yes-scale, 1)); }

  .btn--ghost{
    background: transparent;
    color: var(--plum-soft);
    border: 1.5px solid rgba(140,95,114,0.35);
    font-size:14px; padding:11px 20px;
  }

  #no-btn{
    touch-action: none;
    -webkit-user-select: none; user-select: none;
    will-change: transform;
    position:relative;
    z-index:6;
  }

  .hint{
    font-family:'Caveat', cursive; font-size: 18px; color: var(--rose-deep);
    margin-top: 16px; min-height: 24px; opacity:0; transition: opacity 0.4s ease;
  }
  .hint.show{ opacity:1; }

  /* ---------- Reasons (screen aide) ---------- */
  .reasons{ list-style:none; padding:0; margin:0 0 26px; text-align:left; display:flex; flex-direction:column; gap:12px; }
  .reasons li{ font-size:14px; line-height:1.5; color: var(--plum-soft); padding-left:22px; position:relative; }
  .reasons li::before{ content:'❄'; position:absolute; left:0; color: var(--rose-deep); }

  /* ---------- Gifts (screen cadeau) ---------- */
  .gifts{ display:grid; grid-template-columns:1fr 1fr; gap:12px; margin-bottom:4px; }
  .gift-card{
    background: rgba(255,255,255,0.6);
    border: 1px solid rgba(232,166,193,0.45);
    border-radius: 18px; padding: 18px 10px;
    cursor:pointer; font-family:'Quicksand', sans-serif;
    font-weight:600; font-size:13px; color: var(--plum);
    transition: transform .2s ease, box-shadow .2s ease;
  }
  .gift-card:hover, .gift-card:focus-visible{
    transform: translateY(-3px);
    box-shadow: 0 12px 20px -10px rgba(201,98,143,.4);
  }
  .gift-card .emoji{ font-size:28px; display:block; margin-bottom:8px; }

  .signature{ font-family:'Caveat', cursive; font-size: 22px; color: var(--rose-deep); margin-top: 18px; }
  .confirm-actions{ margin-top: 26px; }

  @media (prefers-reduced-motion: reduce){
    .frost-wipe{ animation: none; transform: translateX(115%); }
    .screen.active{ animation:none; }
    #snow{ display:none; }
  }

  @media (max-width: 400px){
    .card{ padding: 36px 20px 30px; }
  }
</style>
</head>
<body>

  <canvas id="snow"></canvas>

  <div class="hills" aria-hidden="true">
    <div class="hill hill--back"></div>
    <div class="hill hill--mid"></div>
    <div class="hill hill--front"></div>
  </div>

  <div class="stage">
    <div class="card" id="card">
      <div class="content" id="content">
        <div class="frost-wipe" aria-hidden="true"></div>

        <!-- Écran 1 : la question -->
        <section class="screen active" id="screen-ask">
          <p class="eyebrow">❄ iiii, Opération Date Elsie...❄</p>
          <h1><span id="recipient-name">Elsie</span> ça te dirait d'aller a un top resto aek moi?</h1>
          <p class="sub">Moi je veux vraiment, Enfin vu que le message te pressait pas a répondre, j'ai voulu essayer un autre truc.</p>

          <div class="actions actions--primary">
            <button id="yes-btn" type="button" class="btn btn--primary">Oui, avec plaisir 🌸</button>
          </div>
          <div class="actions actions--secondary">
            <button id="no-btn" type="button" class="btn btn--ghost">Non</button>
            <button id="help-btn" type="button" class="btn btn--ghost">Aide 💌</button>
          </div>
          <p class="hint" id="hint"></p>
        </section>

        <!-- Écran 2 : aide / conviction -->
        <section class="screen" id="screen-convince">
          <p class="eyebrow">❄ pour t'aider à dire oui❄</p>
          <h1 class="h1-small">Alors, Les raisons pour lesquel tu devrais dire oui..</h1>
          <ul class="reasons" id="reasons-list"></ul>
          <div class="actions actions--primary">
            <button type="button" class="btn btn--primary" id="convince-yes-btn">Oui, tu m'as convaincu(e) 🌸</button>
          </div>
          <div class="actions actions--secondary">
            <button type="button" class="btn btn--ghost" id="back-btn">← Retour</button>
          </div>
        </section>

        <!-- Écran 3 : choix du cadeau -->
        <section class="screen" id="screen-gift">
          <p class="eyebrow">❄ l'endroit❄</p>
          <h1 class="h1-small">On va choisir le genre du resto ou on ira se le faire, ce petit rencard</h1>
          <div class="gifts" id="gifts-list"></div>
        </section>

        <!-- Écran 4 : confirmation -->
        <section class="screen" id="screen-confirm">
          <p class="eyebrow">❄ réponse reçue ❄</p>
          <h1>Le meilleur jour de l'année 🤍🩷</h1>
          <p class="sub" id="confirm-text"></p>
          <p class="signature" id="signature"></p>
          <div class="actions actions--secondary confirm-actions">
            <button type="button" class="btn btn--ghost" id="home-btn">← Retour à l'accueil</button>
          </div>
        </section>

      </div>
    </div>
  </div>

<script>
  // 🔧 Personnalise ici avant d'envoyer la page
  const config = {
    recipientName: "Elsie",   // 👉 remplace par son vrai prénom
    senderName: "josias",            // 👉 optionnel : ton prénom, pour signer le message final

    reasons: [
      "je ferai tout pour que tu te sente comme une reine, pcq euh... t'est vraiment une reine.",
      "j'ai plein de petites idée et je compte faire de la sortie, un Top dinner.",
      "De toute façon, impossible pour toi de choisir ..non.. tu l'a sans doute remarquer, hihi.",
      "Rien ne t'empeche d'essayer."
    ],

    gifts: [
      { emoji: "🏢🍷", label: "Très chic.. grand hotel du genre 2 février, ONOMO??" },
      { emoji: "☀️🍹", label: "Plage en mode, Blue turtle, Marcelo beach?" },
      { emoji: "🎳🍻", label: "Aek des jeux en mode Harmonie signature, Factory??" },
      { emoji: "🌔🚀", label: "Oub tu préfère un resto sur la lune..." }
    ]
  };

  document.getElementById('recipient-name').textContent = config.recipientName;
  if(config.senderName){
    document.getElementById('signature').textContent = '— ' + config.senderName;
  }

  const reduceMotion = window.matchMedia('(prefers-reduced-motion: reduce)').matches;

  /* ---------------- Neige qui tombe ---------------- */
  const canvas = document.getElementById('snow');
  const ctx = canvas.getContext('2d');
  let flakes = [];

  function resize(){ canvas.width = window.innerWidth; canvas.height = window.innerHeight; }
  window.addEventListener('resize', resize);
  resize();

  function makeFlakes(){
    const count = Math.round((canvas.width * canvas.height) / 9000);
    flakes = Array.from({length: count}, () => ({
      x: Math.random() * canvas.width,
      y: Math.random() * canvas.height,
      r: Math.random() * 2.6 + 1,
      speed: Math.random() * 0.9 + 0.4,
      drift: Math.random() * 0.6 - 0.3,
      hue: Math.random() > 0.5 ? '255,255,255' : '248,196,219'
    }));
  }
  makeFlakes();

  function drawFlakes(){
    ctx.clearRect(0, 0, canvas.width, canvas.height);
    flakes.forEach(f => {
      ctx.beginPath();
      ctx.arc(f.x, f.y, f.r, 0, Math.PI * 2);
      ctx.fillStyle = `rgba(${f.hue},0.85)`;
      ctx.fill();
      if(!reduceMotion){
        f.y += f.speed; f.x += f.drift;
        if(f.y > canvas.height){ f.y = -5; f.x = Math.random() * canvas.width; }
      }
    });
    if(!reduceMotion){ requestAnimationFrame(drawFlakes); }
  }
  drawFlakes();

  /* ---------------- Navigation entre écrans ---------------- */
  function showScreen(id){
    document.querySelectorAll('.screen').forEach(s => s.classList.remove('active'));
    document.getElementById(id).classList.add('active');
  }

  /* ---------------- Bouton "Non" qui esquive dès le toucher ---------------- */
  const noBtn = document.getElementById('no-btn');
  const yesBtn = document.getElementById('yes-btn');
  const hint = document.getElementById('hint');
  const askScreen = document.getElementById('screen-ask');

  const hints = [
    "psst, le bouton 'Oui' est juste à côté 👀",
    "oups hihi",
    "tu es sûr(e) ? je suis le bouton non, je sens que tu l'aime bien, donc fliip",
    "on dirait qu'il ne veut pas être cliqué 😏",
    "essaie encore, je ne me lasse pas 🌸"
  ];
  let dodges = 0;

  function showHint(){
    hint.textContent = hints[dodges % hints.length];
    hint.classList.add('show');
  }

  function dodge(){
    if(reduceMotion) return;
    dodges++;

    const screenRect = askScreen.getBoundingClientRect();
    const btnRect = noBtn.getBoundingClientRect();

    const targetX = screenRect.left + Math.random() * Math.max(0, screenRect.width - btnRect.width);
    const targetY = screenRect.top + Math.random() * Math.max(0, screenRect.height - btnRect.height);

    const dx = targetX - btnRect.left;
    const dy = targetY - btnRect.top;

    const prevX = parseFloat(noBtn.dataset.tx || '0');
    const prevY = parseFloat(noBtn.dataset.ty || '0');
    const newX = prevX + dx;
    const newY = prevY + dy;

    noBtn.dataset.tx = newX;
    noBtn.dataset.ty = newY;
    noBtn.style.transform = `translate(${newX}px, ${newY}px)`;

    yesBtn.style.setProperty('--yes-scale', Math.min(1.3, 1 + Math.min(dodges, 6) * 0.05));
    showHint();
  }

  // Toucher (Android / iOS) : esquive dès le contact, avant même le "clic"
  noBtn.addEventListener('pointerdown', (e) => {
    e.preventDefault();
    dodge();
  });
  // Souris (desktop) : esquive aussi au survol, pour le même effet
  noBtn.addEventListener('pointerenter', (e) => {
    if(e.pointerType === 'mouse') dodge();
  });
  // Clavier : reste accessible, pas d'esquive, juste un indice
  noBtn.addEventListener('keydown', (e) => {
    if(e.key === 'Enter' || e.key === ' '){
      e.preventDefault();
      showHint();
    }
  });

  /* ---------------- Bouton "Aide" ---------------- */
  const reasonsList = document.getElementById('reasons-list');
  config.reasons.forEach(r => {
    const li = document.createElement('li');
    li.textContent = r;
    reasonsList.appendChild(li);
  });

  document.getElementById('help-btn').addEventListener('click', () => {
    showScreen('screen-convince');
  });

  // Retour à l'écran de départ, avec réinitialisation du bouton "Non"
  function resetAsk(){
    noBtn.style.transform = '';
    noBtn.dataset.tx = '0';
    noBtn.dataset.ty = '0';
    dodges = 0;
    hint.classList.remove('show');
    yesBtn.style.setProperty('--yes-scale', 1);
    showScreen('screen-ask');
  }
  document.getElementById('back-btn').addEventListener('click', resetAsk);
  document.getElementById('home-btn').addEventListener('click', resetAsk);

  /* ---------------- Bouton "Oui" (depuis les deux écrans) ---------------- */
  function goToGifts(){
    showScreen('screen-gift');
  }
  yesBtn.addEventListener('click', goToGifts);
  document.getElementById('convince-yes-btn').addEventListener('click', goToGifts);

  /* ---------------- Écran cadeau ---------------- */
  const giftsList = document.getElementById('gifts-list');
  config.gifts.forEach(gift => {
    const btn = document.createElement('button');
    btn.type = 'button';
    btn.className = 'gift-card';
    btn.innerHTML = `<span class="emoji">${gift.emoji}</span>${gift.label}`;
    btn.addEventListener('click', () => chooseGift(gift));
    giftsList.appendChild(btn);
  });

  function chooseGift(gift){
    document.getElementById('confirm-text').textContent =
      `${config.recipientName}, .. t'a cliquer sur : ${gift.emoji} ${gift.label}. Hihi, Donc on va faire ça je m'en occupe, promis. 🎉`;
    showScreen('screen-confirm');
    burstPetals();
  }

  function burstPetals(){
    if(reduceMotion) return;
    const emojis = ['🌸','🩷','❄️','🤍'];
    for(let i = 0; i < 26; i++){
      setTimeout(() => {
        const p = document.createElement('div');
        p.textContent = emojis[Math.floor(Math.random() * emojis.length)];
        p.style.position = 'fixed';
        p.style.left = Math.random() * 100 + 'vw';
        p.style.top = '-5vh';
        p.style.fontSize = (14 + Math.random() * 14) + 'px';
        p.style.zIndex = 4;
        p.style.pointerEvents = 'none';
        p.style.transition = `transform ${3 + Math.random() * 2}s linear, opacity ${3 + Math.random() * 2}s linear`;
        document.body.appendChild(p);
        requestAnimationFrame(() => {
          p.style.transform = `translateY(105vh) rotate(${Math.random() * 360}deg)`;
          p.style.opacity = '0.15';
        });
        setTimeout(() => p.remove(), 5500);
      }, i * 90);
    }
  }
</script>
</body>
</html>
