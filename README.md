# Structure
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>STRUCTURE — Accompagnement Structurant | structure.expert</title>
<meta name="description" content="STRUCTURE est un accompagnement structurant, humain et exigeant. Pas du coaching. Un protocole construit sur ta réalité pour remettre de l'ordre durablement.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;1,300;1,400;1,500&family=DM+Sans:ital,wght@0,300;0,400;0,500;1,300&family=DM+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
:root{
  --bg:#0C0B09;
  --card:#181512;
  --raised:#1E1B17;
  --border:#28231E;
  --border-s:#342E28;
  --muted:#5C554D;
  --gray:#8A8078;
  --body:#CEC8BF;
  --heading:#EDE8E1;
  --white:#F5F1EB;
  --gold:#B8943A;
  --gold-l:#D4AA50;
  --gold-d:rgba(184,148,58,.08);
  --gold-b:rgba(184,148,58,.2);
}
html{scroll-behavior:smooth}
body{background:var(--bg);color:var(--body);font-family:'DM Sans',sans-serif;font-weight:300;font-size:17px;line-height:1.85;overflow-x:hidden}

/* ── UTILITY ── */
.w{max-width:1000px;margin:0 auto;padding:0 40px}
.wn{max-width:720px;margin:0 auto;padding:0 40px}
.ws{max-width:580px;margin:0 auto;padding:0 40px}

/* ── NAV ── */
nav{padding:26px 0;border-bottom:1px solid var(--border);position:sticky;top:0;background:rgba(12,11,9,.96);backdrop-filter:blur(20px);z-index:100}
.nav-in{max-width:1000px;margin:0 auto;padding:0 40px;display:flex;justify-content:space-between;align-items:center}
.nav-logo{font-family:'Cormorant Garamond',serif;font-size:18px;letter-spacing:6px;color:var(--heading);text-transform:uppercase;font-weight:400}
.nav-cta{font-family:'DM Mono',monospace;font-size:10px;letter-spacing:2px;text-transform:uppercase;color:var(--gold);border:1px solid var(--gold-b);padding:9px 20px;text-decoration:none;transition:background .25s,color .25s}
.nav-cta:hover{background:var(--gold-d);color:var(--gold-l)}

/* ── HERO ── */
.hero{padding:140px 0 120px;position:relative;overflow:hidden}
.hero::before{content:'';position:absolute;top:-180px;right:-280px;width:700px;height:700px;background:radial-gradient(circle,rgba(184,148,58,.055) 0%,transparent 62%);pointer-events:none}
.hero::after{content:'';position:absolute;bottom:0;left:0;right:0;height:1px;background:linear-gradient(90deg,transparent,var(--border),transparent)}
.hero-kicker{font-family:'DM Mono',monospace;font-size:10px;color:var(--gold);letter-spacing:3px;text-transform:uppercase;margin-bottom:36px;display:flex;align-items:center;gap:14px;opacity:.85}
.hero-kicker::before{content:'';display:block;width:36px;height:1px;background:var(--gold)}
h1{font-family:'Cormorant Garamond',serif;font-size:clamp(60px,8.5vw,108px);font-weight:300;line-height:.96;letter-spacing:-1.5px;color:var(--heading);margin-bottom:36px}
h1 em{font-style:italic;color:var(--gold-l)}
.hero-intro{font-size:20px;color:var(--body);max-width:500px;line-height:1.75;margin-bottom:18px}
.hero-human{font-size:17px;color:var(--gray);max-width:480px;line-height:1.85;margin-bottom:52px;font-style:italic}
.hero-human strong{color:var(--body);font-style:normal;font-weight:400}
.btn-gold{display:inline-flex;align-items:center;gap:14px;background:var(--gold);color:#0C0B09;padding:17px 38px;font-family:'DM Mono',monospace;font-size:11px;letter-spacing:2px;text-transform:uppercase;text-decoration:none;border:none;cursor:pointer;font-weight:500;transition:background .25s,gap .25s}
.btn-gold:hover{background:var(--gold-l);gap:22px}
.hero-note{margin-top:20px;font-size:13px;color:var(--muted);font-style:italic;letter-spacing:.3px}

/* ── SECTION BASE ── */
section{padding:112px 0}
.sep{border:none;border-top:1px solid var(--border)}
.sk{font-family:'DM Mono',monospace;font-size:10px;color:var(--muted);letter-spacing:3px;text-transform:uppercase;margin-bottom:24px}
.sk.g{color:var(--gold);opacity:.8}
h2{font-family:'Cormorant Garamond',serif;font-size:clamp(38px,5vw,58px);font-weight:300;line-height:1.1;color:var(--heading);margin-bottom:24px;letter-spacing:-.5px}
h2 em{font-style:italic;color:var(--gold-l)}
.s-lead{font-size:17px;color:var(--body);max-width:520px;line-height:1.85;margin-bottom:64px}
.s-lead strong{color:var(--heading);font-weight:400}

/* ── HUMANIZING QUOTE ── */
.hq{border-left:2px solid var(--gold);padding:28px 40px;margin:0 0 72px;background:var(--gold-d)}
.hq-t{font-family:'Cormorant Garamond',serif;font-size:clamp(20px,2.8vw,27px);font-weight:300;color:var(--heading);line-height:1.55;font-style:italic}
.hq-t strong{font-style:normal;font-weight:400;color:var(--white)}

/* ── CONSTAT ── */
.cg{display:grid;grid-template-columns:1fr 1fr;gap:1px;background:var(--border);border:1px solid var(--border)}
.cn{background:var(--card);padding:48px 40px;transition:background .35s}
.cn:hover{background:var(--raised)}
.cn-n{font-family:'Cormorant Garamond',serif;font-size:56px;font-weight:300;color:var(--gold);opacity:.15;line-height:1;margin-bottom:20px}
.cn-body{font-size:16px;color:var(--body);line-height:1.8}
.cn-body strong{color:var(--heading);font-weight:400;display:block;margin-bottom:8px;font-size:17px}

/* ── POSITIONNEMENT ── */
.pos{display:grid;grid-template-columns:1fr 1fr;gap:56px;margin-top:16px}
.pos-h{font-family:'DM Mono',monospace;font-size:10px;letter-spacing:2px;text-transform:uppercase;padding-bottom:18px;margin-bottom:28px;border-bottom:1px solid var(--border)}
.pos-h.not{color:var(--muted)}
.pos-h.yes{color:var(--gold);border-color:var(--gold-b);opacity:.85}
.pos-l{list-style:none;display:flex;flex-direction:column;gap:16px}
.pos-l li{font-size:16px;color:var(--body);padding-left:22px;position:relative;line-height:1.7}
.pos-l.not li::before{content:'—';position:absolute;left:0;color:var(--muted)}
.pos-l.yes li::before{content:'→';position:absolute;left:0;color:var(--gold);opacity:.8}

/* ── PULLQUOTE ── */
.pq{margin:80px 0;padding:64px 80px;background:var(--card);border:1px solid var(--border);border-left:3px solid var(--gold);position:relative}
.pq-t{font-family:'Cormorant Garamond',serif;font-size:clamp(22px,3vw,31px);font-weight:300;color:var(--heading);line-height:1.55;font-style:italic}
.pq-t strong{font-style:normal;font-weight:400}
.pq-attr{margin-top:24px;font-family:'DM Mono',monospace;font-size:10px;color:var(--muted);letter-spacing:2px;text-transform:uppercase}

/* ── AXES ── */
.axes{display:grid;grid-template-columns:repeat(5,1fr);gap:1px;background:var(--border);border:1px solid var(--border)}
.axe{background:var(--card);padding:36px 24px;transition:background .35s;cursor:default}
.axe:hover{background:var(--raised)}
.axe-bar{width:24px;height:1px;background:var(--gold);opacity:.4;margin-bottom:20px}
.axe-t{font-size:14px;font-weight:400;color:var(--heading);margin-bottom:10px;line-height:1.45}
.axe-d{font-size:12px;color:var(--gray);line-height:1.65}

/* ── PROCESS ── */
.process{display:flex;flex-direction:column;gap:1px;background:var(--border);border:1px solid var(--border)}
.ph{background:var(--card);padding:48px 52px;display:grid;grid-template-columns:160px 1fr 120px;gap:40px;align-items:start;transition:background .35s}
.ph:hover{background:var(--raised)}
.ph-tag{font-family:'DM Mono',monospace;font-size:10px;color:var(--gold);letter-spacing:2px;text-transform:uppercase;padding-top:4px;opacity:.8}
.ph-step{font-size:11px;color:var(--muted);margin-top:6px;letter-spacing:1px}
.ph-name{font-family:'Cormorant Garamond',serif;font-size:28px;font-weight:400;color:var(--heading);margin-bottom:12px;letter-spacing:.3px}
.ph-desc{font-size:15px;color:var(--body);line-height:1.8}
.ph-badge{font-family:'DM Mono',monospace;font-size:10px;letter-spacing:1px;text-transform:uppercase;color:var(--muted);border:1px solid var(--border);padding:6px 10px;height:fit-content;text-align:center;white-space:nowrap}

/* ── ONBOARDING ── */
.onboard{display:grid;grid-template-columns:repeat(4,1fr);gap:1px;background:var(--border);border:1px solid var(--border)}
.ob-step{background:var(--card);padding:36px 28px;transition:background .35s}
.ob-step:hover{background:var(--raised)}
.ob-n{font-family:'Cormorant Garamond',serif;font-size:52px;font-weight:300;color:var(--gold);opacity:.14;line-height:1;margin-bottom:16px}
.ob-t{font-size:14px;font-weight:400;color:var(--heading);margin-bottom:10px;line-height:1.4}
.ob-d{font-size:13px;color:var(--body);line-height:1.7}

/* ── BENEFITS ── */
.benefits{display:grid;grid-template-columns:1fr 1fr;gap:1px;background:var(--border);border:1px solid var(--border)}
.benefit{background:var(--card);padding:40px 36px;transition:background .35s;display:flex;gap:20px}
.benefit:hover{background:var(--raised)}
.benefit-icon{font-size:22px;flex-shrink:0;margin-top:2px;opacity:.7}
.benefit-body{}
.benefit-t{font-size:15px;font-weight:400;color:var(--heading);margin-bottom:8px;line-height:1.4}
.benefit-d{font-size:14px;color:var(--body);line-height:1.75}

/* ── RÉSULTATS ── */
.results{display:grid;grid-template-columns:repeat(3,1fr);gap:1px;background:var(--border);border:1px solid var(--border)}
.result{background:var(--card);padding:36px 30px;transition:background .35s}
.result:hover{background:var(--raised)}
.result-week{font-family:'DM Mono',monospace;font-size:10px;color:var(--gold);letter-spacing:2px;text-transform:uppercase;margin-bottom:16px;opacity:.8}
.result-t{font-size:15px;font-weight:400;color:var(--heading);margin-bottom:12px;line-height:1.4}
.result-l{list-style:none;display:flex;flex-direction:column;gap:8px}
.result-l li{font-size:13px;color:var(--body);padding-left:16px;position:relative;line-height:1.6}
.result-l li::before{content:'—';position:absolute;left:0;color:var(--muted);font-size:12px}

/* ── LIMITES ── */
.limits{display:grid;grid-template-columns:1fr 1fr;gap:40px;margin-top:8px}
.limit-col-h{font-family:'DM Mono',monospace;font-size:10px;letter-spacing:2px;text-transform:uppercase;padding-bottom:14px;margin-bottom:24px;border-bottom:1px solid var(--border)}
.limit-col-h.is{color:var(--gold);border-color:var(--gold-b)}
.limit-col-h.not{color:var(--muted)}
.limit-l{list-style:none;display:flex;flex-direction:column;gap:12px}
.limit-l li{font-size:15px;color:var(--body);padding-left:20px;position:relative;line-height:1.65}
.limit-l.is li::before{content:'✓';position:absolute;left:0;color:var(--gold);font-size:12px;top:3px;opacity:.8}
.limit-l.not li::before{content:'×';position:absolute;left:0;color:var(--muted);font-size:13px;top:2px}

/* ── POUR QUI ── */
.who{display:grid;grid-template-columns:1fr 1fr;gap:1px;background:var(--border);border:1px solid var(--border)}
.who-c{background:var(--card);padding:48px 40px}
.who-h{font-family:'DM Mono',monospace;font-size:10px;letter-spacing:2px;text-transform:uppercase;padding-bottom:16px;margin-bottom:28px;border-bottom:1px solid var(--border)}
.who-h.yes{color:var(--gold);border-color:var(--gold-b);opacity:.85}
.who-h.no{color:var(--muted)}
.who-l{list-style:none;display:flex;flex-direction:column;gap:16px}
.who-l li{font-size:15px;color:var(--body);padding-left:22px;position:relative;line-height:1.7}
.who-l.yes li::before{content:'–';position:absolute;left:0;color:var(--gold);opacity:.8}
.who-l.no li::before{content:'×';position:absolute;left:0;color:var(--muted);top:2px;font-size:13px}

/* ── NIVEAUX ── */
.niv{display:grid;grid-template-columns:repeat(3,1fr);gap:1px;background:var(--border);border:1px solid var(--border)}
.nv{background:var(--card);padding:48px 36px;display:flex;flex-direction:column;transition:background .35s}
.nv:hover{background:var(--raised)}
.nv-n{font-family:'Cormorant Garamond',serif;font-size:72px;font-weight:300;color:var(--gold);opacity:.12;line-height:1;margin-bottom:16px}
.nv-name{font-family:'Cormorant Garamond',serif;font-size:30px;font-weight:400;color:var(--heading);margin-bottom:20px;letter-spacing:.3px}
.nv-l{list-style:none;flex:1;display:flex;flex-direction:column;gap:12px;margin-bottom:36px}
.nv-l li{font-size:14px;color:var(--body);padding-left:18px;position:relative;line-height:1.6}
.nv-l li::before{content:'—';position:absolute;left:0;color:var(--muted)}
.nv-p{font-family:'DM Mono',monospace;font-size:11px;color:var(--gold);padding-top:20px;border-top:1px solid var(--border);letter-spacing:1px;opacity:.85}

/* ── POURQUOI MOI ── */
.wme{padding:112px 0;background:var(--raised);border-top:1px solid var(--border);border-bottom:1px solid var(--border)}
.wme-in{display:grid;grid-template-columns:1fr 1.2fr;gap:88px;align-items:start}
.wme-q{font-family:'Cormorant Garamond',serif;font-size:clamp(28px,3.8vw,42px);font-weight:300;font-style:italic;color:var(--heading);line-height:1.42}
.wme-q strong{font-style:normal;font-weight:400}
.wme-body{display:flex;flex-direction:column;gap:20px}
.wme-body p{font-size:16px;color:var(--body);line-height:1.9}
.wme-body p strong{color:var(--heading);font-weight:400}

/* ── CTA ── */
.cta-s{padding:140px 0;text-align:center;position:relative;overflow:hidden}
.cta-s::before{content:'';position:absolute;bottom:-60px;left:50%;transform:translateX(-50%);width:900px;height:500px;background:radial-gradient(ellipse,rgba(184,148,58,.05) 0%,transparent 58%);pointer-events:none}
.cta-k{font-family:'DM Mono',monospace;font-size:10px;color:var(--muted);letter-spacing:3px;text-transform:uppercase;margin-bottom:28px;opacity:.7}
.cta-t{font-family:'Cormorant Garamond',serif;font-size:clamp(52px,8vw,100px);font-weight:300;line-height:1.02;color:var(--heading);margin-bottom:28px;letter-spacing:-1.5px}
.cta-t em{font-style:italic;color:var(--gold-l)}
.cta-sub{font-size:17px;color:var(--body);max-width:420px;margin:0 auto 52px;line-height:1.8}
.cta-note{margin-top:20px;font-size:13px;color:var(--muted);font-style:italic}

/* ── LEGAL ── */
.legal{padding:56px 0;border-top:1px solid var(--border)}
.legal-t{font-family:'DM Mono',monospace;font-size:10px;color:var(--muted);letter-spacing:3px;text-transform:uppercase;margin-bottom:18px;opacity:.7}
.legal-b{font-size:12px;color:var(--muted);line-height:2;max-width:820px}

/* ── FOOTER ── */
footer{padding:40px 0;border-top:1px solid var(--border)}
.foot-in{max-width:1000px;margin:0 auto;padding:0 40px;display:flex;justify-content:space-between;align-items:center}
.foot-logo{font-family:'Cormorant Garamond',serif;font-size:17px;letter-spacing:5px;color:var(--muted);text-transform:uppercase}
.foot-r{font-family:'DM Mono',monospace;font-size:10px;color:var(--muted);text-align:right;line-height:1.9;letter-spacing:.5px}

/* ── ANIMATIONS ── */
@keyframes rise{from{opacity:0;transform:translateY(24px)}to{opacity:1;transform:translateY(0)}}
.rise{animation:rise .85s cubic-bezier(.16,1,.3,1) both}
.d1{animation-delay:.1s}.d2{animation-delay:.24s}.d3{animation-delay:.38s}.d4{animation-delay:.50s}

/* ── RESPONSIVE ── */
@media(max-width:860px){
  .w,.wn,.ws{padding:0 24px}
  .nav-in{padding:0 24px}
  h1{font-size:50px}
  section{padding:80px 0}
  .cg,.pos,.who,.niv,.limits{grid-template-columns:1fr}
  .axes{grid-template-columns:1fr 1fr}
  .ph{grid-template-columns:1fr;gap:12px;padding:32px 28px}
  .ph-badge{display:none}
  .onboard{grid-template-columns:1fr 1fr}
  .benefits,.results{grid-template-columns:1fr}
  .wme-in{grid-template-columns:1fr;gap:48px}
  .pq{padding:40px 36px}
  .foot-in{flex-direction:column;gap:16px;text-align:center}
  .foot-r{text-align:center}
}
</style>
</head>
<body>

<!-- NAV -->
<nav>
  <div class="nav-in">
    <div class="nav-logo">Structure</div>
    <a href="#diagnostic" class="nav-cta">Diagnostic gratuit</a>
  </div>
</nav>

<!-- HERO -->
<div class="hero">
  <div class="w">
    <div class="hero-kicker rise">Accompagnement structurant</div>
    <h1 class="rise d1">Remettre<br>de l'ordre<br>dans <em>ta vie.</em></h1>
    <p class="hero-intro rise d2">Pas des conseils. Pas de la motivation.</p>
    <p class="hero-human rise d3">Le problème n'est pas que tu es faible.<br><strong>Le problème est que tu essaies de te reconstruire seul — sans cadre, sans structure, sans quelqu'un qui tient le fil quand toi tu lâches.</strong></p>
    <a href="#diagnostic" class="btn-gold rise d4">Demander un diagnostic <span>→</span></a>
    <p class="hero-note rise d4">Appel de 60 à 90 min. Gratuit. Sans engagement avant cet échange.</p>
  </div>
</div>

<hr class="sep">

<!-- CONSTAT -->
<section>
  <div class="w">
    <div class="sk">Le constat</div>
    <h2>Tu sais ce que<br>tu devrais faire.</h2>
    <p class="s-lead">Ce n'est pas l'information qui manque. C'est la structure pour transformer ce que tu sais en ce que tu fais réellement — de façon stable, durable, quotidienne.</p>

    <div class="hq">
      <p class="hq-t">Tu n'as pas besoin d'être parfait.<br>Tu as besoin d'un cadre qui t'aide <strong>enfin à tenir.</strong></p>
    </div>

    <div class="cg">
      <div class="cn">
        <div class="cn-n">01</div>
        <div class="cn-body"><strong>Tu recommences les mêmes schémas.</strong>Tu le sais. Tu le refais quand même. Ce n'est pas un problème de volonté — c'est l'absence d'un cadre externe qui te tient responsable.</div>
      </div>
      <div class="cn">
        <div class="cn-n">02</div>
        <div class="cn-body"><strong>Tu as déjà essayé seul.</strong>Les apps, les livres, les résolutions du dimanche soir. Ça tient quelques jours. Puis la vie reprend. Il te faut quelqu'un qui ne lâche pas quand toi tu décroches.</div>
      </div>
      <div class="cn">
        <div class="cn-n">03</div>
        <div class="cn-body"><strong>Tu fonctionnes, mais en mode dégradé.</strong>Pas en crise totale — juste en dessous de ce que tu pourrais être. Cette impression de tourner à 60% de ta capacité. Depuis trop longtemps.</div>
      </div>
      <div class="cn">
        <div class="cn-n">04</div>
        <div class="cn-body"><strong>Tu ne cherches pas à être motivé.</strong>Tu cherches quelqu'un qui maintient le cadre quand toi tu décroches. Quelqu'un qui te confronte à la réalité avec lucidité — pas avec jugement.</div>
      </div>
    </div>
  </div>
</section>

<hr class="sep">

<!-- POSITIONNEMENT -->
<section>
  <div class="w">
    <div class="sk g">Ce qu'est STRUCTURE</div>
    <h2>Ni thérapie.<br>Ni coaching.<br><em>Autre chose.</em></h2>
    <p class="s-lead">STRUCTURE est un accompagnement structurant. L'intensité s'adapte progressivement à ton niveau réel — pas à ce que tu penses pouvoir faire.</p>

    <div class="pos">
      <div>
        <div class="pos-h not">Ce que tu trouveras ailleurs</div>
        <ul class="pos-l not">
          <li>Des séances pour parler de tes problèmes</li>
          <li>Des outils à appliquer seul, sans suivi</li>
          <li>De la motivation qui s'évapore en 48h</li>
          <li>Quelqu'un qui valide tes choix pour te rassurer</li>
          <li>Des formations à regarder sans jamais appliquer</li>
        </ul>
      </div>
      <div>
        <div class="pos-h yes">Ce que tu trouveras ici</div>
        <ul class="pos-l yes">
          <li>Un diagnostic précis de ton déséquilibre réel</li>
          <li>Un protocole adapté à ta réalité, appliqué progressivement avec toi</li>
          <li>Un suivi régulier avec une accountability véritable</li>
          <li>Quelqu'un qui maintient le cadre quand toi tu décroches</li>
          <li>Une intervention directe dans ton environnement réel si nécessaire</li>
        </ul>
      </div>
    </div>

    <div class="pq">
      <p class="pq-t">Tu ne paies pas pour être écouté.<br>Tu paies pour que <strong>la distance entre ce que tu veux faire et ce que tu fais réellement</strong> se réduise — concrètement, durablement, à ton rythme.</p>
    </div>
  </div>
</section>

<hr class="sep">

<!-- CE QUE TU RESSENTIRAS -->
<section>
  <div class="w">
    <div class="sk g">La transformation visée</div>
    <h2>Ce que tu<br><em>ressentiras après.</em></h2>
    <p class="s-lead">Les protocoles et les routines ne sont pas la finalité. Ils sont le chemin. Ce qui compte, c'est l'état intérieur que tu retrouves.</p>

    <div class="benefits">
      <div class="benefit">
        <div class="benefit-icon">◈</div>
        <div class="benefit-body">
          <div class="benefit-t">Clarté mentale retrouvée</div>
          <div class="benefit-d">Arrêter de vivre dans le bruit de ta tête. Savoir quoi faire, dans quel ordre, sans t'épuiser à y penser.</div>
        </div>
      </div>
      <div class="benefit">
        <div class="benefit-icon">◈</div>
        <div class="benefit-body">
          <div class="benefit-t">Sortir du mode survie</div>
          <div class="benefit-d">Ne plus subir les journées. Commencer à les construire — avec une structure qui tient même quand la motivation n'est pas là.</div>
        </div>
      </div>
      <div class="benefit">
        <div class="benefit-icon">◈</div>
        <div class="benefit-body">
          <div class="benefit-t">Retrouver de l'énergie</div>
          <div class="benefit-d">Le désordre chronique épuise. Quand l'environnement et les habitudes sont structurés, l'énergie remonte naturellement.</div>
        </div>
      </div>
      <div class="benefit">
        <div class="benefit-icon">◈</div>
        <div class="benefit-body">
          <div class="benefit-t">Reprendre confiance dans ta capacité à tenir</div>
          <div class="benefit-d">Pas de la confiance générale. La confiance spécifique de savoir que tu peux tenir ce que tu décides — parce que tu l'as prouvé.</div>
        </div>
      </div>
      <div class="benefit">
        <div class="benefit-icon">◈</div>
        <div class="benefit-body">
          <div class="benefit-t">Stabilité au quotidien</div>
          <div class="benefit-d">Moins de chaos, moins de réactions impulsives, moins de culpabilité. Un rythme de vie qui te ressemble et que tu construis toi-même.</div>
        </div>
      </div>
      <div class="benefit">
        <div class="benefit-icon">◈</div>
        <div class="benefit-body">
          <div class="benefit-t">Arrêter de vivre en réaction</div>
          <div class="benefit-d">Passer de "je subie ma journée" à "j'ai décidé ce que j'allais faire de ma journée". C'est un changement fondamental.</div>
        </div>
      </div>
    </div>
  </div>
</section>

<hr class="sep">

<!-- 5 AXES -->
<section>
  <div class="w">
    <div class="sk">Les domaines d'intervention</div>
    <h2>Un seul problème.<br><em>Cinq manifestations.</em></h2>
    <p class="s-lead">Ces cinq axes ne sont pas cinq offres séparées. Ils sont les symptômes d'un même déséquilibre fondamental : l'absence de structure personnelle.</p>
    <div class="axes">
      <div class="axe"><div class="axe-bar"></div><div class="axe-t">Désorganisation chronique</div><div class="axe-d">Pas de routine stable, journées subies, absence de repères concrets au quotidien</div></div>
      <div class="axe"><div class="axe-bar"></div><div class="axe-t">Habitudes problématiques</div><div class="axe-d">Comportements compulsifs non cliniques qui s'installent et se répètent malgré toi</div></div>
      <div class="axe"><div class="axe-bar"></div><div class="axe-t">Agitation mentale</div><div class="axe-d">Pensées dispersées, difficulté à tenir une direction, surcharge cognitive du quotidien</div></div>
      <div class="axe"><div class="axe-bar"></div><div class="axe-t">Dégradation physique</div><div class="axe-d">Sommeil, alimentation, énergie — laissés progressivement à la dérive sans s'en rendre compte</div></div>
      <div class="axe"><div class="axe-bar"></div><div class="axe-t">Isolement & manque de cadre</div><div class="axe-d">Absence d'environnement structurant, repli progressif, perte des ancrages sociaux</div></div>
    </div>
  </div>
</section>

<hr class="sep">

<!-- PROCESS -->
<section>
  <div class="w">
    <div class="sk">Comment ça fonctionne</div>
    <h2>Ce qui se passe<br><em>concrètement.</em></h2>
    <p class="s-lead">Le cadre évolue progressivement selon ta capacité réelle à tenir. L'intensité de l'accompagnement s'adapte — elle ne t'est pas imposée.</p>
    <div class="process">
      <div class="ph">
        <div><div class="ph-tag">Phase 01</div><div class="ph-step">Session initiale</div></div>
        <div>
          <div class="ph-name">Diagnostic</div>
          <div class="ph-desc">60 à 90 minutes. On cartographie ta situation réelle — habitudes, environnement, déclencheurs, niveau de déséquilibre. Pas un bilan générique : une analyse de ton cas précis. À l'issue : soit un protocole adapté, soit une orientation vers le bon professionnel.</div>
        </div>
        <div class="ph-badge">Visio</div>
      </div>
      <div class="ph">
        <div><div class="ph-tag">Phase 02</div><div class="ph-step">Semaines 1 à 4 min.</div></div>
        <div>
          <div class="ph-name">Structuration</div>
          <div class="ph-desc">Un protocole construit sur ta réalité — des règles structurantes, un rythme quotidien, des ancrages stables. Le cadre est progressivement appliqué, ajusté et renforcé avec toi. Suivi hebdomadaire, messagerie 5j/7, reporting quotidien.</div>
        </div>
        <div class="ph-badge">1 visio / sem.</div>
      </div>
      <div class="ph">
        <div><div class="ph-tag">Phase 03</div><div class="ph-step">Si nécessaire</div></div>
        <div>
          <div class="ph-name">Renforcement</div>
          <div class="ph-desc">Activé uniquement si le déséquilibre le nécessite ou si tu stagnes. L'intensité monte — 2 visios par semaine, suivi quotidien structuré, travail approfondi sur les comportements résistants et leurs déclencheurs.</div>
        </div>
        <div class="ph-badge">2 visios / sem.</div>
      </div>
      <div class="ph">
        <div><div class="ph-tag">Phase 04</div><div class="ph-step">Option avancée</div></div>
        <div>
          <div class="ph-name">Intervention terrain</div>
          <div class="ph-desc">Intervenir directement dans l'environnement réel lorsque certaines habitudes ou déséquilibres nécessitent un travail concret sur le terrain. Toujours sur consentement écrit explicite — jamais imposé, jamais précipité.</div>
        </div>
        <div class="ph-badge">Présentiel</div>
      </div>
    </div>
  </div>
</section>

<hr class="sep">

<!-- ONBOARDING -->
<section>
  <div class="w">
    <div class="sk">Après acceptation</div>
    <h2>Un cadre dès<br><em>le premier jour.</em></h2>
    <p class="s-lead">L'accompagnement commence avant même la première session de travail. Dès que tu es accepté, un processus d'intégration rigoureux est mis en place.</p>
    <div class="onboard">
      <div class="ob-step">
        <div class="ob-n">01</div>
        <div class="ob-t">Contrat et cadre légal</div>
        <div class="ob-d">Signature du contrat de prestation. Définition du cadre, des limites, des responsabilités de chaque partie.</div>
      </div>
      <div class="ob-step">
        <div class="ob-n">02</div>
        <div class="ob-t">Questionnaire approfondi</div>
        <div class="ob-d">Un questionnaire complémentaire au diagnostic pour cartographier tes habitudes précises, ton environnement, tes déclencheurs.</div>
      </div>
      <div class="ob-step">
        <div class="ob-n">03</div>
        <div class="ob-t">Protocole initial</div>
        <div class="ob-d">Construction de ton protocole personnalisé lors de la première session : rythme, règles structurantes, système de reporting.</div>
      </div>
      <div class="ob-step">
        <div class="ob-n">04</div>
        <div class="ob-t">Premiers jalons définis</div>
        <div class="ob-d">Les critères de progression sont posés dès le départ. Tu sais exactement ce qu'on vise et comment on mesure l'avancée réelle.</div>
      </div>
    </div>
  </div>
</section>

<hr class="sep">

<!-- RÉSULTATS ATTENDUS -->
<section>
  <div class="w">
    <div class="sk">Transformations observables</div>
    <h2>Résultats<br><em>attendus.</em></h2>
    <p class="s-lead">Pas des promesses. Des transformations observables — dans les comportements, dans le quotidien, dans la façon de se tenir face à soi-même.</p>
    <div class="results">
      <div class="result">
        <div class="result-week">Semaines 1 — 2</div>
        <div class="result-t">Les premières bases</div>
        <ul class="result-l">
          <li>Rythme de lever stable</li>
          <li>3 règles structurantes tenues</li>
          <li>Reporting quotidien régulier</li>
          <li>Première cartographie des déclencheurs</li>
        </ul>
      </div>
      <div class="result">
        <div class="result-week">Semaines 3 — 5</div>
        <div class="result-t">La stabilisation</div>
        <ul class="result-l">
          <li>Compliance > 70% sur les règles</li>
          <li>Réduction des comportements compulsifs</li>
          <li>Amélioration perceptible de l'énergie</li>
          <li>Journées moins subies, plus construites</li>
        </ul>
      </div>
      <div class="result">
        <div class="result-week">Semaines 6 — clôture</div>
        <div class="result-t">L'autonomie</div>
        <ul class="result-l">
          <li>Protocole tenu sans rappel externe</li>
          <li>Environnement restructuré et stable</li>
          <li>Capacité à nommer ses propres déclencheurs</li>
          <li>Confiance retrouvée dans sa capacité à tenir</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<hr class="sep">

<!-- LIMITES -->
<section>
  <div class="w">
    <div class="sk">Transparence totale</div>
    <h2>Ce que STRUCTURE<br><em>est et n'est pas.</em></h2>
    <p class="s-lead">La clarté sur les limites d'un service est le premier signe de son sérieux. Voici exactement ce que STRUCTURE peut — et ne peut pas — faire.</p>
    <div class="limits">
      <div>
        <div class="limit-col-h is">Ce que STRUCTURE est</div>
        <ul class="limit-l is">
          <li>Un accompagnement structurant non médical, rigoureux et personnalisé</li>
          <li>Un cadre externe qui tient quand la motivation ne suffit pas</li>
          <li>Un protocole adaptatif — qui évolue avec ta réalité</li>
          <li>Une présence qui te confronte à la réalité avec lucidité</li>
          <li>Un système qui construit ton autonomie, pas ta dépendance</li>
        </ul>
      </div>
      <div>
        <div class="limit-col-h not">Ce que STRUCTURE n'est pas</div>
        <ul class="limit-l not">
          <li>Une solution miracle ou un raccourci</li>
          <li>Un remplacement à un suivi médical ou psychiatrique</li>
          <li>Une source de motivation artificielle</li>
          <li>Un système passif — il exige une implication réelle de ta part</li>
          <li>Un accompagnement adapté aux situations de crise médicale active</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<hr class="sep">

<!-- POUR QUI -->
<section>
  <div class="w">
    <div class="sk">Sélection stricte</div>
    <h2>Pour qui.<br><em>Pour qui pas.</em></h2>
    <p class="s-lead">STRUCTURE n'est pas fait pour tout le monde — et c'est ce qui en fait la valeur. La sélection est non négociable, pour ton intérêt et pour la qualité du travail.</p>
    <div class="who">
      <div class="who-c">
        <div class="who-h yes">C'est fait pour toi si</div>
        <ul class="who-l yes">
          <li>Tu as entre 20 et 45 ans, tu fonctionnes, mais tu es en déséquilibre chronique depuis trop longtemps</li>
          <li>Tu es conscient du problème et tu as déjà tenté de t'en sortir seul — sans résultat durable</li>
          <li>Tu cherches quelqu'un qui maintient le cadre, pas quelqu'un qui t'encourage</li>
          <li>Tu es prêt à t'engager dans un cadre structurant et progressif</li>
          <li>Tu as besoin d'accountability réelle, pas de validation émotionnelle</li>
        </ul>
      </div>
      <div class="who-c" style="background:var(--bg)">
        <div class="who-h no">Ce n'est pas fait pour toi si</div>
        <ul class="who-l no">
          <li>Tu souffres de troubles psychiatriques diagnostiqués ou d'une dépendance sévère nécessitant un suivi médical</li>
          <li>Tu cherches un thérapeute, un médecin ou un accompagnement social spécialisé</li>
          <li>Tu veux être encouragé et validé dans tes choix actuels</li>
          <li>Tu n'es pas prêt à t'engager réellement — juste à observer</li>
          <li>Tu traverses une crise médicale ou psychiatrique active</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<hr class="sep">

<!-- NIVEAUX -->
<section>
  <div class="w">
    <div class="sk">Les formules</div>
    <h2>Un niveau.<br><em>Choisi ensemble.</em></h2>
    <p class="s-lead">Le niveau est déterminé à l'issue du diagnostic — pas avant. On ne choisit pas à l'aveugle l'intensité dont tu as besoin. La tarification est définie lors de cet échange.</p>
    <div class="niv">
      <div class="nv">
        <div class="nv-n">01</div>
        <div class="nv-name">Base</div>
        <ul class="nv-l">
          <li>Diagnostic complet</li>
          <li>Protocole personnalisé progressif</li>
          <li>1 visio de suivi par semaine</li>
          <li>Messagerie structurée 5j/7</li>
          <li>Reporting et ajustements continus</li>
          <li>Session de clôture et plan d'autonomie</li>
        </ul>
        <div class="nv-p">Tarification définie à l'issue du diagnostic</div>
      </div>
      <div class="nv" style="background:var(--raised)">
        <div class="nv-n">02</div>
        <div class="nv-name">Renforcé</div>
        <ul class="nv-l">
          <li>Tout le Niveau 1</li>
          <li>2 visios de suivi par semaine</li>
          <li>Suivi quotidien structuré</li>
          <li>Travail comportemental approfondi</li>
          <li>Accountability renforcée et reporting détaillé</li>
        </ul>
        <div class="nv-p">Tarification définie à l'issue du diagnostic</div>
      </div>
      <div class="nv">
        <div class="nv-n">03</div>
        <div class="nv-name">Terrain</div>
        <ul class="nv-l">
          <li>Tout le Niveau 2</li>
          <li>Intervention directe en lieu de vie</li>
          <li>Restructuration de l'environnement physique</li>
          <li>Consentement écrit avant chaque intervention</li>
          <li>France & Belgique</li>
        </ul>
        <div class="nv-p">Tarification définie à l'issue du diagnostic</div>
      </div>
    </div>
  </div>
</section>

<!-- POURQUOI MOI -->
<div class="wme">
  <div class="w">
    <div class="wme-in">
      <div class="wme-q">"Je ne suis pas un expert de formation.<br>Je suis quelqu'un qui a compris, de l'intérieur, <strong>ce que coûte vraiment le désordre chronique.</strong>"</div>
      <div class="wme-body">
        <p>Ce que j'ai compris, c'est qu'on ne manque pas de volonté. On manque de structure. Pendant des années, j'ai fonctionné avec cette impression permanente d'être en dessous de ce que je pouvais être — sans jamais comprendre pourquoi les choses ne tenaient pas.</p>
        <p>Ce qui a changé, ce n'est pas une révélation. <strong>C'est un cadre.</strong> Des règles claires. Un système qui n'attendait pas que la motivation soit au rendez-vous pour fonctionner.</p>
        <p>STRUCTURE n'est pas né d'une théorie. Il est né de cette expérience — et de la certitude que ce qui m'a sorti du désordre peut être construit pour quelqu'un d'autre, de façon rigoureuse, personnalisée et ancrée dans le réel.</p>
      </div>
    </div>
  </div>
</div>

<!-- CTA -->
<section class="cta-s" id="diagnostic">
  <div class="w">
    <div class="cta-k">Première étape</div>
    <h2 class="cta-t">Diagnostic<br><em>gratuit.</em></h2>
    <p class="cta-sub">60 à 90 minutes pour analyser ta situation réellement. Pas un argumentaire de vente — un diagnostic honnête. À l'issue : soit un protocole, soit une orientation vers mieux adapté.</p>
    <a href="REMPLACER_PAR_LIEN_TYPEFORM" class="btn-gold">Demander mon diagnostic <span>→</span></a>
    <p class="cta-note">Formulaire de pré-qualification requis avant l'appel. Places limitées.</p>
  </div>
</section>

<!-- LEGAL -->
<div class="legal">
  <div class="wn">
    <div class="legal-t">Informations légales</div>
    <p class="legal-b">STRUCTURE est un service d'accompagnement structurant non médical. Il ne constitue pas un acte de soins, une thérapie, un suivi psychologique ou psychiatrique, ni une formation professionnelle au sens légal du terme. L'Accompagnateur STRUCTURE n'est pas un professionnel de santé au sens du Code de la santé publique français (art. L4161-1) ni de la loi belge du 10 mai 2015 relative à l'exercice des professions des soins de santé. Tout accompagnement est conditionné à la signature préalable d'un contrat de prestation de service privé. Données personnelles traitées conformément au RGPD (UE 2016/679) — contact@structure.expert</p>
  </div>
</div>

<!-- FOOTER -->
<footer>
  <div class="foot-in">
    <div class="foot-logo">Structure</div>
    <div class="foot-r">structure.expert<br>France & Belgique — 2025<br>contact@structure.expert</div>
  </div>
</footer>

</body>
</html>
