<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>USASB: Speaker-Attributed ASR and Diarization Benchmark for Urdu</title>
<meta name="description" content="USASB is a benchmark for speaker diarization and speaker-attributed speech recognition on conversational Urdu with overlapping speech, Urdu-English code-switching, and dialectal variation.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Sans:wght@400;500;600&family=Noto+Nastaliq+Urdu:wght@400;600&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#eef3f2; --panel:#ffffff; --ink:#14282a; --muted:#53686a; --line:#cfdcda;
  --teal:#0f6b62; --plum:#8a3b6e; --saffron:#c98a0b; --overlap:rgba(20,40,42,.12);
  --accent:#0f6b62; --on-accent:#fff;
  box-sizing:border-box;
}
@media (prefers-color-scheme:dark){
  :root:not([data-theme="light"]){
    --bg:#0e1a1b; --panel:#15262a; --ink:#e4eeed; --muted:#9db3b2; --line:#2a4044;
    --teal:#3fb8a8; --plum:#d27ab3; --saffron:#e8b440; --overlap:rgba(228,238,237,.14);
    --accent:#3fb8a8; --on-accent:#0e1a1b;
  }
}
:root[data-theme="dark"]{
  --bg:#0e1a1b; --panel:#15262a; --ink:#e4eeed; --muted:#9db3b2; --line:#2a4044;
  --teal:#3fb8a8; --plum:#d27ab3; --saffron:#e8b440; --overlap:rgba(228,238,237,.14);
  --accent:#3fb8a8; --on-accent:#0e1a1b;
}
*,*::before,*::after{box-sizing:inherit}
html{scroll-behavior:smooth}
body{margin:0;background:var(--bg);color:var(--ink);font:16px/1.65 "IBM Plex Sans",system-ui,sans-serif;-webkit-font-smoothing:antialiased}
a{color:var(--accent)}
a:focus-visible,button:focus-visible{outline:3px solid var(--saffron);outline-offset:2px}
.wrap{max-width:1040px;margin:0 auto;padding:0 22px}
nav{display:flex;gap:20px;flex-wrap:wrap;align-items:center;padding:18px 0;font-size:.95rem}
nav a{color:var(--muted);text-decoration:none}
nav a:hover{color:var(--ink)}
nav .brand{font-weight:600;color:var(--ink);margin-right:auto}
header.hero{padding:34px 0 28px}
h1{font-size:clamp(2rem,5vw,3.2rem);line-height:1.12;margin:0 0 14px;font-weight:600;letter-spacing:-.01em;max-width:18ch}
.lede{font-size:1.15rem;color:var(--muted);max-width:62ch;margin:0 0 24px}
.authors{font-size:.95rem;color:var(--muted);margin:0 0 22px}
.btns{display:flex;flex-wrap:wrap;gap:10px;margin-bottom:36px}
.btn{display:inline-block;padding:10px 18px;border-radius:6px;border:1.5px solid var(--accent);color:var(--accent);text-decoration:none;font-weight:500}
.btn.primary{background:var(--accent);color:var(--on-accent)}
.btn:hover{filter:brightness(1.08)}
/* timeline hero */
.tl{background:var(--panel);border:1px solid var(--line);border-radius:10px;padding:18px 18px 14px}
.tl-row{display:grid;grid-template-columns:84px 1fr;align-items:center;gap:10px;margin:8px 0}
.tl-name{font-size:.85rem;color:var(--muted)}
.track{position:relative;height:30px;border-radius:4px;background:repeating-linear-gradient(90deg,transparent 0 calc(10% - 1px),var(--line) calc(10% - 1px) 10%)}
.seg{position:absolute;top:3px;bottom:3px;border-radius:3px;transform-origin:left center;animation:grow .9s ease-out both}
.s1 .seg{background:var(--teal)} .s2 .seg{background:var(--plum)} .s3 .seg{background:var(--saffron)}
.ov{position:absolute;top:-4px;bottom:-4px;border-left:1.5px dashed var(--ink);border-right:1.5px dashed var(--ink);background:var(--overlap);pointer-events:none}
.tl-body{position:relative}
.tl-cap{display:flex;justify-content:space-between;flex-wrap:wrap;gap:8px;font-size:.82rem;color:var(--muted);margin-top:10px;padding-left:94px}
.utts{margin-top:16px;border-top:1px solid var(--line);padding-top:14px;display:grid;gap:10px}
.utt{display:grid;grid-template-columns:84px 1fr;gap:10px;align-items:baseline}
.utt b{font-size:.85rem;font-weight:500}
.utt.s1 b{color:var(--teal)} .utt.s2 b{color:var(--plum)} .utt.s3 b{color:var(--saffron)}
.ur{font-family:"Noto Nastaliq Urdu",serif;direction:rtl;text-align:right;line-height:2.1;font-size:1.05rem;unicode-bidi:plaintext}
.note{font-size:.82rem;color:var(--muted)}
@keyframes grow{from{transform:scaleX(0)}to{transform:scaleX(1)}}
@media (prefers-reduced-motion:reduce){.seg{animation:none}html{scroll-behavior:auto}}
section{padding:46px 0 6px}
h2{font-size:1.7rem;margin:0 0 14px;font-weight:600;letter-spacing:-.005em}
p{max-width:72ch}
.cols{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:30px;margin-top:18px}
.cols h3{margin:0 0 6px;font-size:1.08rem;font-weight:600}
.cols p{margin:0;color:var(--muted)}
.cols>div{border-top:3px solid var(--line);padding-top:12px}
.cols>div:nth-child(1){border-color:var(--teal)}.cols>div:nth-child(2){border-color:var(--plum)}.cols>div:nth-child(3){border-color:var(--saffron)}
.tablewrap{overflow-x:auto;border:1px solid var(--line);border-radius:8px;background:var(--panel)}
table{border-collapse:collapse;width:100%;font-size:.95rem}
th,td{padding:10px 14px;text-align:left;border-bottom:1px solid var(--line);white-space:nowrap}
th{font-weight:600;background:transparent}
tr:last-child td{border-bottom:0}
td.num,th.num{text-align:right;font-variant-numeric:tabular-nums}
.tbd{color:var(--muted);font-style:italic}
pre{background:var(--panel);border:1px solid var(--line);border-radius:8px;padding:16px;overflow-x:auto;font:.88rem/1.55 ui-monospace,Menlo,Consolas,monospace;margin:10px 0}
.pre-wrap{position:relative}
.copy{position:absolute;top:18px;right:10px;font:inherit;font-size:.8rem;padding:4px 10px;border-radius:5px;border:1px solid var(--line);background:var(--bg);color:var(--ink);cursor:pointer}
dl{display:grid;grid-template-columns:max-content 1fr;gap:6px 22px;margin:0}
dt{font-weight:600}dd{margin:0;color:var(--muted)}
footer{margin-top:50px;padding:24px 0 40px;border-top:1px solid var(--line);color:var(--muted);font-size:.9rem}
@media (max-width:560px){.tl-row,.utt{grid-template-columns:62px 1fr}.tl-cap{padding-left:72px}dl{grid-template-columns:1fr}}
</style>
</head>
<body>
<div class="wrap">
<nav aria-label="Primary">
  <span class="brand">USASB</span>
  <a href="#dataset">Dataset</a><a href="#tasks">Tasks</a><a href="#leaderboard">Leaderboard</a><a href="#use">Download</a><a href="#cite">Cite</a>
</nav>

<header class="hero">
  <h1>Who said what, in conversational Urdu</h1>
  <p class="lede">USASB is a benchmark for speaker diarization and speaker-attributed speech recognition on Urdu conversations with overlapping speech, Urdu-English code-switching, and dialectal variation.</p>
  <p class="authors">[Author One], [Author Two], [Author Three] &middot; [Institution] &middot; [Venue, Year]</p>
  <div class="btns">
    <a class="btn primary" href="#">Paper</a>
    <a class="btn" href="#">Dataset on Hugging Face</a>
    <a class="btn" href="#">Evaluation code</a>
    <a class="btn" href="#">Leaderboard</a>
  </div>

  <div class="tl" role="img" aria-label="Example timeline: three speakers, with one overlapping stretch where two speak at once">
    <div class="tl-body">
      <div class="tl-row s1"><span class="tl-name">Speaker A</span><div class="track"><span class="seg" style="left:2%;width:30%"></span><span class="seg" style="left:66%;width:26%;animation-delay:.3s"></span></div></div>
      <div class="tl-row s2"><span class="tl-name">Speaker B</span><div class="track"><span class="seg" style="left:28%;width:26%;animation-delay:.15s"></span></div></div>
      <div class="tl-row s3"><span class="tl-name">Speaker C</span><div class="track"><span class="seg" style="left:55%;width:15%;animation-delay:.25s"></span><span class="seg" style="left:92%;width:6%;animation-delay:.4s"></span></div></div>
    </div>
    <div class="tl-cap"><span>0 s</span><span>Dashed regions are overlapped speech</span><span>30 s</span></div>
    <div class="utts">
      <div class="utt s1"><b>Speaker A</b><span class="ur">[Urdu text with an English word, e.g. meeting]</span></div>
      <div class="utt s2"><b>Speaker B</b><span class="ur">[Urdu text, regional variety]</span></div>
    </div>
    <p class="note" style="margin:10px 0 0">Illustrative figure. Replace with a real clip and transcript from the dataset.</p>
  </div>
</header>

<section id="about">
  <h2>What makes it hard</h2>
  <div class="cols">
    <div><h3>Overlapping speech</h3><p>[X]% of speech time has two or more simultaneous speakers, so systems must separate and attribute words, not just segment audio.</p></div>
    <div><h3>Code-switching</h3><p>Speakers mix Urdu and English within a sentence. Transcripts mark both languages so errors can be scored by language.</p></div>
    <div><h3>Dialectal variation</h3><p>Recordings cover [list varieties, e.g. Punjabi-, Pashto-, Sindhi-influenced Urdu], each labeled for per-dialect analysis.</p></div>
  </div>
</section>

<section id="dataset">
  <h2>Dataset</h2>
  <p>[One or two sentences on sources, recording conditions, and how annotation was done, including annotator count and agreement.]</p>
  <div class="tablewrap"><table>
    <thead><tr><th>Split</th><th class="num">Hours</th><th class="num">Recordings</th><th class="num">Speakers</th><th class="num">Overlap %</th><th class="num">Code-switch %</th></tr></thead>
    <tbody>
      <tr><td>Train</td><td class="num tbd">[ ]</td><td class="num tbd">[ ]</td><td class="num tbd">[ ]</td><td class="num tbd">[ ]</td><td class="num tbd">[ ]</td></tr>
      <tr><td>Dev</td><td class="num tbd">[ ]</td><td class="num tbd">[ ]</td><td class="num tbd">[ ]</td><td class="num tbd">[ ]</td><td class="num tbd">[ ]</td></tr>
      <tr><td>Test</td><td class="num tbd">[ ]</td><td class="num tbd">[ ]</td><td class="num tbd">[ ]</td><td class="num tbd">[ ]</td><td class="num tbd">[ ]</td></tr>
    </tbody>
  </table></div>
</section>

<section id="tasks">
  <h2>Tasks and metrics</h2>
  <dl>
    <dt>Diarization</dt><dd>Diarization error rate (DER), reported with and without overlapped regions.</dd>
    <dt>ASR</dt><dd>Word error rate (WER) and character error rate (CER), with a split by Urdu and English tokens.</dd>
    <dt>Speaker-attributed ASR</dt><dd>cpWER and tcpWER, which count a word as wrong if the speaker is wrong.</dd>
  </dl>
</section>

<section id="leaderboard">
  <h2>Leaderboard</h2>
  <p>Results on the test set. To submit, open an issue or pull request with your system description and outputs.</p>
  <div class="tablewrap"><table>
    <thead><tr><th>System</th><th class="num">DER &darr;</th><th class="num">WER &darr;</th><th class="num">cpWER &darr;</th><th class="num">tcpWER &darr;</th></tr></thead>
    <tbody>
      <tr><td>[Pyannote + Whisper]</td><td class="num tbd">[ ]</td><td class="num tbd">[ ]</td><td class="num tbd">[ ]</td><td class="num tbd">[ ]</td></tr>
      <tr><td>[Baseline 2]</td><td class="num tbd">[ ]</td><td class="num tbd">[ ]</td><td class="num tbd">[ ]</td><td class="num tbd">[ ]</td></tr>
    </tbody>
  </table></div>
</section>

<section id="use">
  <h2>Download and evaluate</h2>
  <div class="pre-wrap"><button class="copy" data-target="code1">Copy</button>
<pre id="code1"><code>from datasets import load_dataset

ds = load_dataset("YOUR_ORG/USASB", split="test")
print(ds[0])  # audio, transcript, speaker turns, language and dialect tags</code></pre></div>
  <div class="pre-wrap"><button class="copy" data-target="code2">Copy</button>
<pre id="code2"><code>git clone https://github.com/YOUR_ORG/usasb
cd usasb && pip install -r requirements.txt
python evaluate.py --task sa-asr --hyp outputs/ --ref data/test</code></pre></div>
  <p>License: [CC BY 4.0 / CC BY-NC 4.0]. Access: [open / gated, with the request form link].</p>
</section>

<section id="cite">
  <h2>Citation</h2>
  <div class="pre-wrap"><button class="copy" data-target="bib">Copy</button>
<pre id="bib"><code>@inproceedings{usasb2026,
  title     = {USASB: A Benchmark for Speaker-Attributed Speech Recognition
               and Diarization in Urdu},
  author    = {Author One and Author Two and Author Three},
  booktitle = {[Venue]},
  year      = {2026}
}</code></pre></div>
</section>

<footer>
  Contact: [email]. Annotated by [team]. Funded by [funder]. Source for this page lives in the project repository.
</footer>
</div>

<script>
document.querySelectorAll('.copy').forEach(function(b){
  b.addEventListener('click',function(){
    var t=document.getElementById(b.dataset.target).innerText;
    var done=function(){b.textContent='Copied';setTimeout(function(){b.textContent='Copy'},1500)};
    if(navigator.clipboard){navigator.clipboard.writeText(t).then(done)}else{done()}
  });
});
</script>
</body>
</html>
