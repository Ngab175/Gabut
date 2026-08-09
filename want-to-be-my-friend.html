<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Want to be my friend?</title>
<link rel="icon" href="data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22><text y=%22.9em%22 font-size=%2290%22>%F0%9F%93%9D</text></svg>">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Kalam:wght@400;700&family=Nunito:wght@400;600;800&display=swap" rel="stylesheet">
<style>
  :root {
    --paper: #eef4f7;
    --rule: #c9dde6;
    --margin-line: #e8878f;
    --ink: #2b2e33;
    --ink-soft: #6b7280;
    --pink: #ff92ab;
    --pink-dark: #e04569;
    --blue: #4c8fbd;
    --green: #43a06a;
  }

  * { box-sizing: border-box; }
  html, body { height: 100%; }

  body {
    margin: 0;
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 24px;
    font-family: 'Nunito', sans-serif;
    background: linear-gradient(160deg, #fdf0e7, #e7f0f6);
    position: relative;
    overflow: hidden;
  }

  .ambient { position: fixed; inset: 0; pointer-events: none; z-index: 0; }

  .doodle {
    position: absolute;
    animation-name: drift;
    animation-timing-function: ease-in-out;
    animation-iteration-count: infinite;
  }

  @keyframes drift {
    0%, 100% { transform: translateY(0) rotate(0deg); }
    50% { transform: translateY(-22px) rotate(10deg); }
  }

  .note {
    position: relative;
    z-index: 1;
    width: min(440px, 100%);
    min-height: 440px;
    background:
      repeating-linear-gradient(to bottom, transparent 0px, transparent 34px, var(--rule) 35px, var(--rule) 36px),
      var(--paper);
    padding: 56px 30px 40px 54px;
    box-shadow: 0 24px 50px -18px rgba(43, 46, 51, 0.35);
    clip-path: polygon(
      0% 4%, 4% 1%, 9% 4%, 14% 0%, 19% 3%, 24% 1%, 29% 4%, 34% 0%, 40% 3%,
      46% 1%, 52% 4%, 58% 1%, 64% 3%, 70% 0%, 76% 3%, 82% 1%, 88% 4%, 94% 1%, 100% 3%,
      100% 100%, 0% 100%
    );
    transform: rotate(-1.5deg) translateY(-40px);
    opacity: 0;
    animation: dropIn 0.7s cubic-bezier(.2, .8, .3, 1.2) 0.15s forwards;
  }

  .note::before {
    content: '';
    position: absolute;
    left: 32px;
    top: 0;
    bottom: 0;
    width: 2px;
    background: var(--margin-line);
    opacity: 0.55;
  }

  @keyframes dropIn {
    0% { opacity: 0; transform: rotate(-6deg) translateY(-60px) scale(0.96); }
    70% { opacity: 1; transform: rotate(1.4deg) translateY(4px) scale(1.01); }
    100% { opacity: 1; transform: rotate(-1deg) translateY(0) scale(1); }
  }

  .tape {
    position: absolute;
    top: -14px;
    left: 26px;
    width: 84px;
    height: 26px;
    background: repeating-linear-gradient(45deg, var(--blue), var(--blue) 6px, rgba(255,255,255,0.4) 6px, rgba(255,255,255,0.4) 12px);
    opacity: 0.8;
    transform: rotate(-6deg);
    box-shadow: 0 2px 4px rgba(0,0,0,0.15);
  }

  .stage { display: grid; }
  .stage > * { grid-area: 1 / 1; transition: opacity 0.35s ease, transform 0.35s ease; }

  .result { opacity: 0; transform: translateY(8px); pointer-events: none; align-self: center; }
  .note.answered .prompt { opacity: 0; transform: translateY(-8px); pointer-events: none; }
  .note.answered .result { opacity: 1; transform: translateY(0); pointer-events: auto; }

  .eyebrow {
    font-weight: 800;
    font-size: 13px;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    color: var(--ink-soft);
    margin: 0 0 8px;
  }

  .question {
    font-family: 'Kalam', cursive;
    font-weight: 700;
    font-size: clamp(30px, 8vw, 44px);
    line-height: 1.18;
    color: var(--ink);
    margin: 0 0 40px;
  }

  .choices { position: relative; display: flex; flex-wrap: wrap; gap: 30px; min-height: 140px; }

  .choice-box {
    display: flex;
    align-items: center;
    gap: 10px;
    background: none;
    border: none;
    cursor: pointer;
    font-family: 'Kalam', cursive;
    font-size: 24px;
    color: var(--ink);
    padding: 6px;
    height: fit-content;
  }

  .choice-box .box {
    width: 30px;
    height: 30px;
    flex-shrink: 0;
    border: 2.5px solid var(--ink);
    border-radius: 5px;
    display: flex;
    align-items: center;
    justify-content: center;
    transform: rotate(-2deg);
    transition: transform 0.15s ease, border-color 0.15s ease, background 0.15s ease;
  }

  .choice-box:hover .box { transform: rotate(-2deg) scale(1.06); }
  .choice-box:focus-visible .box { outline: 3px dashed var(--blue); outline-offset: 3px; }

  #yesBox .box { border-color: var(--pink-dark); }

  #noBox { position: relative; transition: left 0.35s cubic-bezier(.3, 1.6, .4, 1), top 0.35s cubic-bezier(.3, 1.6, .4, 1); }
  #noBox.dodging { position: absolute; }

  .choice-box.pulse .box { animation: pulse 0.4s ease; }
  @keyframes pulse {
    30% { transform: rotate(-2deg) scale(1.1); }
    100% { transform: rotate(-2deg) scale(1); }
  }

  .check {
    width: 18px;
    height: 18px;
    stroke: var(--pink-dark);
    stroke-width: 3;
    fill: none;
    stroke-linecap: round;
    stroke-linejoin: round;
    stroke-dasharray: 30;
    stroke-dashoffset: 30;
    transition: stroke-dashoffset 0.35s ease 0.05s;
  }

  .choice-box.checked .box { background: var(--pink); border-color: var(--pink-dark); }
  .choice-box.checked .check { stroke-dashoffset: 0; }

  .result-emoji { font-size: 46px; margin: 0 0 12px; }
  .status { font-weight: 700; font-size: 19px; color: var(--ink); margin: 0; }

  .retry {
    margin-top: 18px;
    background: none;
    border: 2px solid var(--ink);
    border-radius: 999px;
    padding: 8px 18px;
    font-family: 'Nunito', sans-serif;
    font-weight: 800;
    font-size: 14px;
    color: var(--ink);
    cursor: pointer;
  }
  .retry:hover { background: var(--ink); color: var(--paper); }

  .burst-piece { position: absolute; pointer-events: none; opacity: 0; animation: burst 0.9s ease-out forwards; }
  @keyframes burst {
    0% { opacity: 1; transform: translate(0, 0) scale(0.6) rotate(0deg); }
    100% { opacity: 0; transform: translate(var(--dx), var(--dy)) scale(1.1) rotate(var(--rot)); }
  }

  @media (prefers-reduced-motion: reduce) {
    .note { animation: none; opacity: 1; transform: none; }
    .doodle { animation: none; }
    .choice-box.pulse .box { animation: none; }
  }

  @media (max-width: 380px) {
    .note { padding: 50px 20px 34px 44px; }
    .question { margin-bottom: 30px; }
  }
</style>
</head>
<body>

<div class="ambient" id="ambient"></div>

<main class="note" id="note">
  <div class="tape"></div>
  <div class="stage">
    <div class="prompt">
      <p class="eyebrow">a note, just for you</p>
      <h1 class="question">Want to be my friend?</h1>
      <div class="choices">
        <button class="choice-box" id="yesBox" type="button" aria-label="Yes">
          <span class="box"><svg class="check" viewBox="0 0 24 24"><path d="M4 12l5 5L20 6"/></svg></span>
          <span>Yes</span>
        </button>
        <button class="choice-box" id="noBox" type="button" aria-label="No">
          <span class="box"><svg class="check" viewBox="0 0 24 24"><path d="M4 12l5 5L20 6"/></svg></span>
          <span>No</span>
        </button>
      </div>
    </div>
    <div class="result">
      <p class="result-emoji" id="resultEmoji">📝</p>
      <p class="status" id="status" aria-live="polite">Sending…</p>
      <button class="retry" id="retryBtn" type="button" hidden>Try again</button>
    </div>
  </div>
</main>

<noscript>
  <p style="position:fixed;inset:0;display:flex;align-items:center;justify-content:center;background:#eef4f7;font-family:sans-serif;padding:24px;text-align:center;">
    This page needs JavaScript turned on to send your answer.
  </p>
</noscript>

<script>
(function () {
  var prefersReducedMotion = window.matchMedia('(prefers-reduced-motion: reduce)').matches;
  var EMAIL = 'yusufngabdilah23@gmail.com';
  var QUESTION = 'Want to be my friend?';

  function shapePath(shape) {
    if (shape === 'star') {
      return '<path d="M12 2 L14 9 L21 9 L15.5 13.5 L17.5 21 L12 16.5 L6.5 21 L8.5 13.5 L3 9 L10 9 Z" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linejoin="round"/>';
    }
    if (shape === 'heart') {
      return '<path d="M12 20 C6 15 3 11.5 3 8 C3 5 5.2 3 8 3 C9.8 3 11.2 4 12 5.3 C12.8 4 14.2 3 16 3 C18.8 3 21 5 21 8 C21 11.5 18 15 12 20 Z" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linejoin="round"/>';
    }
    return '<path d="M3 12 Q7 4 12 12 T21 12" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round"/>';
  }

  function makeSvg(shape, size) {
    var wrap = document.createElement('div');
    wrap.innerHTML = '<svg viewBox="0 0 24 24" width="' + size + '" height="' + size + '">' + shapePath(shape) + '</svg>';
    return wrap.firstElementChild;
  }

  var ambient = document.getElementById('ambient');
  var shapes = ['star', 'heart', 'swirl'];
  var colors = ['var(--pink)', 'var(--blue)', 'var(--green)'];

  if (!prefersReducedMotion) {
    var count = window.innerWidth < 480 ? 5 : 8;
    for (var i = 0; i < count; i++) {
      var shape = shapes[i % shapes.length];
      var el = makeSvg(shape, 16 + Math.random() * 14);
      el.classList.add('doodle');
      el.style.left = (Math.random() * 92) + 'vw';
      el.style.top = (Math.random() * 88) + 'vh';
      el.style.color = colors[i % colors.length];
      el.style.opacity = (0.22 + Math.random() * 0.18).toFixed(2);
      el.style.animationDuration = (9 + Math.random() * 8) + 's';
      el.style.animationDelay = (Math.random() * 4) + 's';
      ambient.appendChild(el);
    }
  }

  var note = document.getElementById('note');
  var yesBox = document.getElementById('yesBox');
  var noBox = document.getElementById('noBox');
  var resultEmoji = document.getElementById('resultEmoji');
  var status = document.getElementById('status');
  var retryBtn = document.getElementById('retryBtn');
  var submitted = false;

  function dodgeNo() {
    var stage = noBox.parentElement;
    var stageRect = stage.getBoundingClientRect();
    var boxRect = noBox.getBoundingClientRect();
    var maxX = Math.max(stageRect.width - boxRect.width, 0);
    var maxY = Math.max(stageRect.height - boxRect.height, 0);
    var x = Math.random() * maxX;
    var y = Math.random() * maxY;
    noBox.classList.add('dodging');
    noBox.style.left = x + 'px';
    noBox.style.top = y + 'px';
    yesBox.classList.remove('pulse');
    void yesBox.offsetWidth;
    yesBox.classList.add('pulse');
  }

  if (!prefersReducedMotion) {
    noBox.addEventListener('mouseenter', function () {
      if (!submitted) dodgeNo();
    });
    noBox.addEventListener('touchstart', function (e) {
      if (submitted) return;
      e.preventDefault();
      dodgeNo();
    }, { passive: false });
  }

  function burst() {
    if (prefersReducedMotion) return;
    var rect = resultEmoji.getBoundingClientRect();
    var noteRect = note.getBoundingClientRect();
    var originX = rect.left - noteRect.left + rect.width / 2;
    var originY = rect.top - noteRect.top + rect.height / 2;
    for (var i = 0; i < 10; i++) {
      var el = makeSvg(i % 2 === 0 ? 'star' : 'heart', 16);
      el.classList.add('burst-piece');
      el.style.left = originX + 'px';
      el.style.top = originY + 'px';
      el.style.color = i % 3 === 0 ? 'var(--blue)' : 'var(--pink)';
      var angle = Math.random() * Math.PI * 2;
      var dist = 60 + Math.random() * 70;
      el.style.setProperty('--dx', Math.cos(angle) * dist + 'px');
      el.style.setProperty('--dy', (Math.sin(angle) * dist - 20) + 'px');
      el.style.setProperty('--rot', (Math.random() * 240 - 120) + 'deg');
      note.appendChild(el);
      (function (node) {
        setTimeout(function () { node.remove(); }, 1000);
      })(el);
    }
  }

  function resetToPrompt() {
    submitted = false;
    note.classList.remove('answered');
    yesBox.classList.remove('checked');
    noBox.classList.remove('checked', 'dodging');
    noBox.style.position = '';
    noBox.style.left = '';
    noBox.style.top = '';
    retryBtn.hidden = true;
  }

  function submitAnswer(answer, boxEl) {
    if (submitted) return;
    submitted = true;
    boxEl.classList.add('checked');
    note.classList.add('answered');
    resultEmoji.textContent = '📝';
    status.textContent = 'Sending…';
    retryBtn.hidden = true;

    fetch('https://formsubmit.co/ajax/' + EMAIL, {
      method: 'POST',
      headers: { 'Content-Type': 'application/json', 'Accept': 'application/json' },
      body: JSON.stringify({
        question: QUESTION,
        answer: answer,
        _subject: 'New answer: "' + QUESTION + '" \u2192 ' + answer,
        _template: 'table',
        _captcha: 'false'
      })
    })
      .then(function (res) {
        return res.json().catch(function () { return null; }).then(function (data) {
          return { ok: res.ok, data: data };
        });
      })
      .then(function (result) {
        if (!result.ok || !result.data) throw new Error('bad response');
        if (answer === 'Yes') {
          resultEmoji.textContent = '🎉';
          status.textContent = 'You can chat me in insta :)';
          burst();
        } else {
          resultEmoji.textContent = '📮';
          status.textContent = 'Why.';
        }
      })
      .catch(function () {
        resultEmoji.textContent = '😅';
        status.textContent = "Try again :)";
        retryBtn.hidden = false;
      });
  }

  yesBox.addEventListener('click', function () { submitAnswer('Yes', yesBox); });
  noBox.addEventListener('click', function () { submitAnswer('No', noBox); });
  retryBtn.addEventListener('click', resetToPrompt);
})();
</script>

</body>
</html>
