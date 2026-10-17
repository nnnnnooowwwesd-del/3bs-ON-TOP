<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>3BS FC | فريق عبسي</title>
<link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;500;600;700;800;900&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
<style>
:root{--bg:#080a0f;--panel:#11151d;--panel2:#171c26;--line:#292f3b;--text:#f5f7fb;--muted:#9ba4b4;--accent:#d7ff3f;--accent2:#a6cc12;--red:#ff5d67}
*{box-sizing:border-box;margin:0;padding:0}html{scroll-behavior:smooth}body{font-family:'Cairo',sans-serif;background:var(--bg);color:var(--text);line-height:1.7}a{color:inherit;text-decoration:none}.wrap{width:min(1180px,92%);margin:auto}
.topbar{position:sticky;top:0;z-index:10;background:#080a0feF;border-bottom:1px solid var(--line);backdrop-filter:blur(14px)}.nav{height:76px;display:flex;align-items:center;justify-content:space-between;gap:20px}.brand{display:flex;align-items:center;gap:12px;font-weight:900;letter-spacing:.5px}.logo{width:46px;height:46px;display:grid;place-items:center;background:var(--accent);color:#080a0f;border-radius:13px;font-weight:900;font-size:18px;transform:skew(-5deg)}.brand small{display:block;color:var(--muted);font-size:11px;font-weight:600;letter-spacing:0}.navlinks{display:flex;align-items:center;gap:24px;color:#c4cad4;font-size:14px}.navlinks a:hover{color:var(--accent)}.nav-cta{background:var(--accent);color:#10130a;padding:10px 16px;border-radius:10px;font-weight:900;font-size:13px}
.hero{position:relative;overflow:hidden;padding:80px 0 70px;border-bottom:1px solid var(--line);background:radial-gradient(ellipse at 80% 25%,#d7ff3f1b,transparent 34%),radial-gradient(ellipse at 15% 90%,#526bff18,transparent 30%),linear-gradient(135deg,#11151d,#080a0f 65%)}.hero:after{content:'3BS';position:absolute;left:-15px;bottom:-95px;font-size:clamp(190px,30vw,390px);font-weight:900;line-height:1;color:#ffffff05;pointer-events:none}.hero-grid{display:grid;grid-template-columns:1.15fr .85fr;align-items:center;gap:48px;position:relative;z-index:1}.eyebrow{display:inline-flex;align-items:center;gap:8px;color:var(--accent);font-size:12px;font-weight:800;letter-spacing:1px;border:1px solid #d7ff3f45;border-radius:100px;padding:6px 12px;background:#d7ff3f0c}.hero h1{font-size:clamp(38px,5vw,68px);line-height:1.18;font-weight:900;margin:20px 0 15px;letter-spacing:-1.5px}.hero h1 span{color:var(--accent)}.hero p{max-width:590px;color:#aeb6c4;font-size:16px}.actions{display:flex;flex-wrap:wrap;gap:12px;margin-top:28px}.btn{display:inline-flex;align-items:center;justify-content:center;gap:9px;padding:13px 18px;border-radius:11px;font-weight:800;font-size:14px;transition:.2s}.btn:hover{transform:translateY(-3px)}.btn-primary{background:var(--accent);color:#11140a}.btn-outline{border:1px solid #414958;background:#ffffff05}.hero-visual{min-height:320px;border:1px solid #ffffff17;border-radius:25px;background:linear-gradient(145deg,#d7ff3f1c,#ffffff03 55%),url('https://images.unsplash.com/photo-1508098682722-e99c43a406b2?q=80&w=1200&auto=format&fit=crop') center/cover;position:relative;overflow:hidden;box-shadow:0 25px 90px #0008}.hero-visual:before{content:'';position:absolute;inset:0;background:linear-gradient(0deg,#080a0f 0%,transparent 70%)}.visual-mark{position:absolute;bottom:22px;right:22px;left:22px;display:flex;align-items:end;justify-content:space-between}.visual-mark strong{font-size:42px;line-height:1;font-weight:900;color:var(--accent)}.visual-mark span{font-size:12px;color:#d7dce5}
.section{padding:66px 0}.section-head{display:flex;align-items:end;justify-content:space-between;gap:20px;margin-bottom:26px}.kicker{font-size:11px;color:var(--accent);font-weight:900;letter-spacing:1.5px}.section h2{font-size:clamp(25px,3vw,36px);line-height:1.3;font-weight:900;margin-top:5px}.sub{color:var(--muted);font-size:13px;margin-top:5px}.match-feature{display:grid;grid-template-columns:1fr 1.15fr 1fr;align-items:center;gap:15px;padding:30px;border-radius:20px;border:1px solid #d7ff3f55;background:linear-gradient(120deg,#d7ff3f0d,transparent 55%),var(--panel);position:relative;overflow:hidden}.team{text-align:center}.team-badge{width:78px;height:78px;border-radius:22px;background:var(--panel2);border:1px solid var(--line);display:grid;place-items:center;margin:0 auto 12px;font-size:22px;font-weight:900;color:var(--accent)}.team h3{font-size:20px;font-weight:900}.team p{color:var(--muted);font-size:12px}.match-mid{text-align:center}.vs{font-size:30px;font-weight:900;color:var(--accent);letter-spacing:2px}.match-mid .date{color:var(--muted);font-size:12px;margin-top:8px}.status{display:inline-flex;gap:7px;align-items:center;background:#ffffff08;border:1px solid var(--line);border-radius:99px;padding:5px 10px;color:#cbd2de;font-size:11px;margin-top:10px}.status i{color:var(--accent)}.status.live{color:#fff;background:#ff303b20;border-color:#ff303b88;font-weight:900}.status.live i{color:#ff303b;animation:livePulse 1s infinite}@keyframes livePulse{0%,100%{opacity:1;transform:scale(1)}50%{opacity:.25;transform:scale(.72)}}.coach-announcement p{font-size:13px;color:#cbd2de}.notice{font-size:12px;color:var(--muted);margin-top:13px}
.stats{display:grid;grid-template-columns:repeat(3,1fr);gap:15px;margin-top:18px}.stat{background:var(--panel);border:1px solid var(--line);border-radius:15px;padding:18px;display:flex;align-items:center;gap:13px}.stat-icon{width:42px;height:42px;display:grid;place-items:center;background:#d7ff3f12;border-radius:12px;color:var(--accent);font-size:18px}.stat strong{font-size:20px;display:block;line-height:1.3}.stat span{color:var(--muted);font-size:11px}
.players{display:grid;grid-template-columns:repeat(3,1fr);gap:14px}.player{background:var(--panel);border:1px solid var(--line);border-radius:16px;padding:18px;transition:.2s}.player:hover{border-color:#d7ff3f75;transform:translateY(-3px)}.player-top{display:flex;align-items:center;justify-content:space-between;gap:10px}.player-icon{width:44px;height:44px;display:grid;place-items:center;border-radius:13px;background:var(--panel2);color:var(--accent);font-size:18px}.number{color:var(--accent);font-size:12px;font-weight:900;background:#d7ff3f10;padding:4px 9px;border-radius:7px}.player h3{font-size:16px;font-weight:800;margin-top:15px;direction:ltr;text-align:right}.player p{color:var(--muted);font-size:12px}.player .role{margin-top:4px}
.content-grid{display:grid;grid-template-columns:1fr 1fr;gap:18px}.content-grid.results-grid{grid-template-columns:1fr}.panel{background:var(--panel);border:1px solid var(--line);border-radius:18px;padding:22px}.panel h3{font-size:18px;margin-bottom:15px}.result{display:flex;align-items:center;justify-content:space-between;gap:12px;padding:13px 0;border-bottom:1px solid var(--line);font-size:13px}.result:last-child{border-bottom:0}.result strong{white-space:nowrap}.win{color:var(--accent)}.loss{color:var(--red)}.newsline{display:flex;gap:12px;padding:12px 0;border-bottom:1px solid var(--line)}.newsline:last-child{border:0}.news-icon{flex:0 0 38px;height:38px;display:grid;place-items:center;background:var(--panel2);color:var(--accent);border-radius:11px}.newsline p{font-size:13px}.newsline small{display:block;color:var(--muted);font-size:11px;margin-top:4px}
.media-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:16px}.media-card{min-height:190px;border:1px solid var(--line);border-radius:18px;overflow:hidden;position:relative;background-size:cover;background-position:center;display:flex;align-items:end}.media-card:before{content:'';position:absolute;inset:0;background:linear-gradient(0deg,#07090ef2,#07090e12 95%);transition:.2s}.media-card:hover:before{background:linear-gradient(0deg,#07090ef5,#d7ff3f20)}.media-card.one{background-image:url('https://images.unsplash.com/photo-1518091043644-c1d4457512c6?q=80&w=900&auto=format&fit=crop')}.media-card.two{background-image:url('https://images.unsplash.com/photo-1508098682722-e99c43a406b2?q=80&w=900&auto=format&fit=crop')}.media-content{position:relative;padding:20px;width:100%;display:flex;align-items:end;justify-content:space-between;gap:15px}.media-content h3{font-size:17px}.media-content p{font-size:12px;color:#b9c1cf}.play{width:43px;height:43px;flex:0 0 43px;display:grid;place-items:center;border-radius:50%;background:var(--accent);color:#10130a}.media-note{font-size:11px;color:var(--muted);margin-top:12px}.panel video{display:block}.panel img{object-fit:contain}
footer{border-top:1px solid var(--line);padding:25px 0;color:var(--muted);font-size:12px}.foot{display:flex;align-items:center;justify-content:space-between;gap:15px}.foot strong{color:var(--accent)}
@media(max-width:800px){.navlinks{display:none}.hero{padding:55px 0}.hero-grid{grid-template-columns:1fr;gap:28px}.hero-visual{min-height:230px}.match-feature{padding:20px 12px;gap:6px}.team-badge{width:58px;height:58px;border-radius:17px;font-size:17px}.team h3{font-size:15px}.vs{font-size:23px}.players{grid-template-columns:repeat(2,1fr)}.stats{gap:8px}.stat{padding:12px;gap:8px}.stat strong{font-size:17px}.content-grid{grid-template-columns:1fr}.section{padding:48px 0}}@media(max-width:480px){.nav{height:65px}.nav-cta{font-size:11px;padding:9px 11px}.hero h1{font-size:38px}.hero p{font-size:14px}.match-feature{grid-template-columns:1fr 65px 1fr}.team h3{font-size:13px}.team p{font-size:10px}.match-mid .date{font-size:10px}.players{grid-template-columns:1fr 1fr}.player{padding:13px}.player h3{font-size:13px;overflow-wrap:anywhere}.player p{font-size:11px}.stats{grid-template-columns:1fr}.media-grid{grid-template-columns:1fr}.section-head{align-items:start;flex-direction:column}.foot{align-items:flex-start;flex-direction:column}}

/* قائمة الخدمات الجديدة */
#quickMenuWrap{position:fixed;top:14px;right:14px;z-index:10001;direction:rtl;font-family:'Cairo',sans-serif}
#quickMenuToggle{width:46px;height:46px;border:1px solid #353d4b;border-radius:14px;background:#11151d;color:#d7ff3f;font-size:21px;cursor:pointer;box-shadow:0 8px 24px #0006}
#quickMenuPanel{display:none;position:absolute;top:54px;right:0;width:230px;padding:8px;background:#11151d;border:1px solid #343b49;border-radius:15px;box-shadow:0 18px 45px #000a}
#quickMenuPanel.open{display:block}
.quick-menu-item{display:flex;align-items:center;gap:10px;width:100%;padding:12px;border:0;border-radius:10px;background:transparent;color:#f5f7fb;text-align:right;font:700 13px Cairo,sans-serif;cursor:pointer}
.quick-menu-item:hover{background:#d7ff3f16;color:#d7ff3f}
#quickModal{display:none;position:fixed;inset:0;z-index:10002;background:#000b;align-items:center;justify-content:center;padding:18px;direction:rtl;font-family:'Cairo',sans-serif}
#quickModal.open{display:flex}
.quick-modal-card{width:min(520px,100%);max-height:90vh;overflow:auto;background:#11151d;border:1px solid #343b49;border-radius:20px;padding:22px;box-shadow:0 24px 80px #000b}
.quick-modal-head{display:flex;align-items:center;justify-content:space-between;gap:12px;margin-bottom:15px}
.quick-modal-head h2{font-size:21px}
.quick-close{background:#242a35;color:#fff;border:0;border-radius:9px;width:36px;height:36px;font-size:20px;cursor:pointer}
.quick-field{margin:13px 0}.quick-field label{display:block;font-size:13px;color:#cbd2de;margin-bottom:6px}.quick-field input,.quick-field textarea{width:100%;background:#080a0f;color:#fff;border:1px solid #343b49;border-radius:10px;padding:12px;font:14px Cairo,sans-serif}.quick-field textarea{min-height:125px;resize:vertical}
.quick-submit{border:0;border-radius:10px;background:#d7ff3f;color:#080a0f;padding:12px 16px;font:900 13px Cairo,sans-serif;cursor:pointer}
.quick-note{font-size:11px;color:#9ba4b4;margin-top:10px}
@media(max-width:480px){#quickMenuWrap{top:9px;right:9px}#quickMenuToggle{width:42px;height:42px}.brand{margin-right:48px}}

/* تحسين بصري إضافي مع الحفاظ على أقسام الموقع ومحتواه */
:root{--bg:#07090d;--panel:#10151e;--panel2:#171e29;--line:#2b3442;--accent:#d7ff3f;--red:#ff3548}
.topbar{box-shadow:0 8px 30px #0003}.brand{gap:14px}.logo{box-shadow:0 0 24px #d7ff3f20}.hero{background:radial-gradient(ellipse at 82% 22%,#d7ff3f20,transparent 32%),radial-gradient(ellipse at 8% 85%,#526bff14,transparent 35%),linear-gradient(135deg,#121925,#07090d 68%)}
.panel,.stat,.player,.match-feature,.media-card{box-shadow:0 12px 35px #0002;transition:border-color .2s,transform .2s,box-shadow .2s}.panel:hover,.stat:hover{border-color:#d7ff3f38}.section{padding-top:74px;padding-bottom:74px}.section-head{margin-bottom:30px}.status{font-weight:800;letter-spacing:.1px}.status.live{background:#ff303b1c;border-color:#ff303b99;color:#fff}.status.live i{color:#ff303b}
#quickMenuToggle{border-radius:50%;width:48px;height:48px;background:linear-gradient(145deg,#171d27,#0c1017);border-color:#465064;box-shadow:0 10px 30px #0007;transition:.2s}#quickMenuToggle:hover{border-color:var(--accent);transform:translateY(-2px)}#quickMenuPanel{width:min(270px,calc(100vw - 28px));padding:10px;backdrop-filter:blur(16px)}.quick-menu-item{padding:14px;border-radius:12px;font-size:14px}
.team-account-list{display:grid;gap:10px}.team-account-link{display:flex;align-items:center;gap:10px;padding:12px 14px;background:#ffffff07;border:1px solid #ffffff12;border-radius:12px;color:#f5f7fb;font-weight:800}.team-account-link:hover{border-color:var(--accent);color:var(--accent)}
@media(max-width:600px){.section{padding-top:52px;padding-bottom:52px}.hero-visual{border-radius:20px}.match-feature{border-radius:17px}}

/* Match history management and developer credit */
.developer-credit{color:var(--muted)}.developer-credit strong{color:var(--accent)}
.admin-match-list{display:grid;gap:8px;margin-top:14px}.admin-match-row{display:flex;align-items:center;justify-content:space-between;gap:10px;padding:10px;border:1px solid #343c4a;border-radius:10px;background:#0d1119;font-size:12px}.admin-match-row span{min-width:0}.admin-match-row button{flex-shrink:0;padding:7px 10px;font-size:11px}.history-empty{color:#9ba4b4;font-size:12px;padding:8px 0}
@media(max-width:680px){.foot{flex-direction:column;align-items:flex-start}.admin-match-row{align-items:flex-start}}
</style>
<style>
#adminLaunch{position:fixed;bottom:18px;left:18px;z-index:9998;background:#d7ff3f;color:#080a0f;border:0;border-radius:14px;padding:12px 16px;font:800 13px Cairo,sans-serif;box-shadow:0 8px 30px #0008;cursor:pointer}
#adminOverlay{display:none;position:fixed;inset:0;z-index:9999;background:#05070bea;backdrop-filter:blur(10px);padding:16px;overflow:auto;font-family:Cairo,sans-serif}#adminOverlay.open{display:block}.admin-shell{max-width:1000px;margin:2vh auto;background:#10141d;border:1px solid #303847;border-radius:22px;overflow:hidden;color:#f5f7fb;box-shadow:0 25px 100px #0009}.admin-head{padding:20px 24px;background:linear-gradient(110deg,#d7ff3f18,transparent);display:flex;align-items:center;justify-content:space-between;gap:12px;border-bottom:1px solid #292f3b}.admin-head h2{margin:0;font-size:23px}.admin-head p{color:#9ba4b4;font-size:12px}.admin-close{background:#252b37;border:1px solid #3b4352;color:#fff;border-radius:10px;padding:9px 13px;cursor:pointer}.admin-grid{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:14px;padding:18px}.admin-card{background:#171c26;border:1px solid #292f3b;border-radius:15px;padding:16px;min-width:0}.admin-card h3{margin:0 0 12px;font-size:15px;color:#d7ff3f}.admin-field{display:grid;gap:5px;margin:10px 0}.admin-field label{font-size:12px;color:#c4cad4}.admin-field input,.admin-field textarea,.admin-field select{width:100%;background:#090c12;color:#f5f7fb;border:1px solid #343c4a;border-radius:9px;padding:10px;font:13px Cairo,sans-serif;outline:none}.admin-field textarea{min-height:75px;resize:vertical}.admin-actions{display:flex;flex-wrap:wrap;gap:10px;padding:0 18px 18px}.admin-btn{border:0;border-radius:10px;padding:11px 16px;font:800 13px Cairo,sans-serif;cursor:pointer}.admin-save{background:#d7ff3f;color:#080a0f}.admin-reset{background:#252b37;color:#fff;border:1px solid #3b4352}.admin-note{padding:0 18px 18px;color:#9ba4b4;font-size:11px}.admin-toast{color:#d7ff3f;font-size:12px;align-self:center}.live-dot{display:inline-block;width:8px;height:8px;background:#ff303b;border-radius:50%;animation:adminPulse 1s infinite}@keyframes adminPulse{50%{opacity:.25;transform:scale(.7)}}
@media(max-width:650px){.admin-grid{grid-template-columns:1fr;padding:12px}.admin-head{padding:16px}.admin-head h2{font-size:18px}#adminOverlay{padding:8px}.admin-shell{margin:0 auto}}

/* تحسين بصري إضافي مع الحفاظ على أقسام الموقع ومحتواه */
:root{--bg:#07090d;--panel:#10151e;--panel2:#171e29;--line:#2b3442;--accent:#d7ff3f;--red:#ff3548}
.topbar{box-shadow:0 8px 30px #0003}.brand{gap:14px}.logo{box-shadow:0 0 24px #d7ff3f20}.hero{background:radial-gradient(ellipse at 82% 22%,#d7ff3f20,transparent 32%),radial-gradient(ellipse at 8% 85%,#526bff14,transparent 35%),linear-gradient(135deg,#121925,#07090d 68%)}
.panel,.stat,.player,.match-feature,.media-card{box-shadow:0 12px 35px #0002;transition:border-color .2s,transform .2s,box-shadow .2s}.panel:hover,.stat:hover{border-color:#d7ff3f38}.section{padding-top:74px;padding-bottom:74px}.section-head{margin-bottom:30px}.status{font-weight:800;letter-spacing:.1px}.status.live{background:#ff303b1c;border-color:#ff303b99;color:#fff}.status.live i{color:#ff303b}
#quickMenuToggle{border-radius:50%;width:48px;height:48px;background:linear-gradient(145deg,#171d27,#0c1017);border-color:#465064;box-shadow:0 10px 30px #0007;transition:.2s}#quickMenuToggle:hover{border-color:var(--accent);transform:translateY(-2px)}#quickMenuPanel{width:min(270px,calc(100vw - 28px));padding:10px;backdrop-filter:blur(16px)}.quick-menu-item{padding:14px;border-radius:12px;font-size:14px}
.team-account-list{display:grid;gap:10px}.team-account-link{display:flex;align-items:center;gap:10px;padding:12px 14px;background:#ffffff07;border:1px solid #ffffff12;border-radius:12px;color:#f5f7fb;font-weight:800}.team-account-link:hover{border-color:var(--accent);color:var(--accent)}
@media(max-width:600px){.section{padding-top:52px;padding-bottom:52px}.hero-visual{border-radius:20px}.match-feature{border-radius:17px}}

/* 3BS FC BLUE EDITION */
:root{--bg:#06101e;--panel:#0b1b30;--panel2:#102641;--line:#203b5c;--text:#f4f8ff;--muted:#a6bad3;--accent:#36a8ff;--accent2:#1677d2;--red:#ff5268}
body{background:var(--bg)}
.logo,#quickMenuToggle,.nav-cta,.btn-primary,.play,.quick-submit,#adminLaunch,.admin-save{background:linear-gradient(135deg,#42b4ff,#1674d1)!important;color:#fff!important}
.hero{background:radial-gradient(ellipse at 82% 22%,#168cff2b,transparent 34%),radial-gradient(ellipse at 8% 85%,#3b82f620,transparent 35%),linear-gradient(135deg,#102641,#06101e 68%)}
.eyebrow{color:#61bdff;border-color:#36a8ff66;background:#168cff12}
.hero h1 span,.kicker,.win,.team-badge,.stat-icon,.player-icon,.number,.visual-mark strong,.status i,.admin-card h3{color:#55b7ff}
.match-feature{border-color:#36a8ff66;background:linear-gradient(120deg,#168cff14,transparent 55%),var(--panel)}
.panel,.stat,.player,.match-feature,.media-card{box-shadow:0 12px 35px #0004}
.panel:hover,.stat:hover,.player:hover{border-color:#36a8ff80}
.team-account-link:hover,.quick-menu-item:hover{border-color:#36a8ff;color:#55b7ff}
#quickMenuToggle{color:#55b7ff}
#adminLaunch{box-shadow:0 8px 30px #0008}
.admin-head{background:linear-gradient(110deg,#168cff22,transparent)}
.admin-head h2 i{color:#55b7ff!important}
.admin-save{background:linear-gradient(135deg,#42b4ff,#1674d1)!important}
.hero-visual{background-image:linear-gradient(145deg,#168cff24,#ffffff03 55%),url('https://images.unsplash.com/photo-1508098682722-e99c43a406b2?q=80&w=1200&auto=format&fit=crop')}
@media(prefers-reduced-motion:reduce){*{scroll-behavior:auto!important;animation-duration:.01ms!important;transition-duration:.01ms!important}}
/* Team crest loading screen */
#teamLoader{position:fixed;inset:0;z-index:20000;display:flex;align-items:center;justify-content:center;flex-direction:column;gap:22px;background:radial-gradient(circle at center,#10345a 0,#06101e 60%,#030813 100%);transition:opacity .45s ease,visibility .45s ease}
#teamLoader.done{opacity:0;visibility:hidden;pointer-events:none}
.loader-crest{width:124px;height:124px;border-radius:28px;border:2px solid #4db6ff;display:grid;place-items:center;color:#fff;font-size:34px;font-weight:900;background:linear-gradient(145deg,#167bd1,#071a31);box-shadow:0 0 0 8px #36a8ff12,0 0 55px #168cff55;animation:crestSpin 1.8s linear infinite}
.loader-ring{width:158px;height:158px;position:absolute;border:2px solid transparent;border-top-color:#68c5ff;border-left-color:#167bd1;border-radius:50%;animation:crestSpin 1.25s linear infinite}
.loader-caption{color:#d9ecff;font:800 13px Cairo,sans-serif;letter-spacing:2px}
@keyframes crestSpin{to{transform:rotate(360deg)}}
@media(prefers-reduced-motion:reduce){.loader-crest,.loader-ring{animation:none}}

</style>

<style>
/* Enhanced live status + match countdown */
.kick-live-chip{display:flex;align-items:center;gap:10px;flex-wrap:wrap;margin-top:20px;padding:12px 14px;width:fit-content;max-width:100%;border:1px solid #36a8ff50;border-radius:14px;background:linear-gradient(100deg,#168cff18,#0b1b30cc);font-size:12px;color:#dcecff}
.kick-live-chip a{color:#65c0ff;font-weight:900;margin-right:4px}
.kick-live-dot{width:9px;height:9px;flex:0 0 9px;border-radius:50%;background:#ffb84d;box-shadow:0 0 0 5px #ffb84d18}
.kick-live-chip.is-live{border-color:#ff4058a8;background:linear-gradient(100deg,#ff263b26,#0b1b30cc)}
.kick-live-chip.is-live .kick-live-dot{background:#ff4058;box-shadow:0 0 0 5px #ff405825;animation:livePulse 1s infinite}
.kick-live-chip.is-offline .kick-live-dot{background:#8b98aa;box-shadow:0 0 0 5px #8b98aa18}
.countdown-panel{display:grid;grid-template-columns:1fr 1.1fr;align-items:center;gap:28px;padding:clamp(22px,4vw,42px);border:1px solid #36a8ff55;border-radius:24px;background:radial-gradient(ellipse at 15% 10%,#168cff22,transparent 50%),linear-gradient(140deg,#102641,#091526);box-shadow:0 22px 65px #0005}
.countdown-copy h2{font-size:clamp(24px,3vw,36px);font-weight:900;margin:8px 0}
.countdown-copy p{color:var(--muted);font-size:13px;margin-bottom:20px}
.countdown-clock{display:grid;grid-template-columns:repeat(4,minmax(0,1fr));gap:10px}
.countdown-clock>div{text-align:center;padding:20px 8px;border:1px solid #36a8ff45;border-radius:16px;background:#06101eaa}
.countdown-clock strong{display:block;font-size:clamp(25px,4vw,44px);line-height:1.2;color:#65c0ff;font-weight:900;font-variant-numeric:tabular-nums}
.countdown-clock span{display:block;color:#a6bad3;font-size:11px;margin-top:8px}
@media(max-width:760px){.countdown-panel{grid-template-columns:1fr;gap:22px}.countdown-clock{gap:6px}.countdown-clock>div{padding:15px 4px}.countdown-clock span{font-size:10px}.kick-live-chip{font-size:11px}}

/* إدارة الإضافات: عناصر التحرير لا تظهر للزوار */
#club-hub input, #club-hub textarea, #club-hub select, #club-hub button:not(.tunnel-content button) { display:none; }
body.admin-unlocked #club-hub input, body.admin-unlocked #club-hub textarea, body.admin-unlocked #club-hub select, body.admin-unlocked #club-hub button:not(.tunnel-content button) { display:initial; }
#club-hub .admin-field, #club-hub .tactics-controls, #club-hub .theme-picker-row { display:none; }
body.admin-unlocked #club-hub .admin-field, body.admin-unlocked #club-hub .tactics-controls, body.admin-unlocked #club-hub .theme-picker-row { display:block; }
#club-hub .award-grid select, #club-hub .award-grid input { display:none; }
body.admin-unlocked #club-hub .award-grid select, body.admin-unlocked #club-hub .award-grid input { display:block; }
.user-created-post button { display:none; } body.admin-unlocked .user-created-post button { display:inline-flex; }
#adminEditModeBtn { margin:10px 0; }
#adminModeBadge { display:none; position:fixed; z-index:9998; bottom:16px; right:16px; border-radius:12px; padding:10px 14px; color:#fff; background:#1679d8; box-shadow:0 6px 24px #0005; font-weight:800; border:0; cursor:pointer; }
body.admin-unlocked #adminModeBadge { display:block; }
</style>


<style>
/* 3BS FC — custom portrait background */
.hero {
  background:
    linear-gradient(90deg, rgba(3,10,22,.94) 0%, rgba(3,10,22,.78) 48%, rgba(3,10,22,.38) 100%),
    linear-gradient(0deg, rgba(4,12,24,.72), rgba(4,12,24,.08)),
    url('data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAABCMAAAPyCAYAAABGihXMAAAAAXNSR0IArs4c6QAAAARzQklUCAgICHwIZIgAACAASURBVHic7L1rj+RIkq73mLuTjIjMrKyq6Z7rrnvECBIOIAnYL5J+saAz+idonH0PVAErTYPXvOnpnp7UtsmjMKZa76Ye5MxiRERlZldVd1T1pjerIuJB0ku5Ot9dee01ov1JmJiLlL/* ... */
</style>
</head>
<body>
<!-- المحتوى كامل متوفر في الملف المرفق -->
</body>
</html>
