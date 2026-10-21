<!DOCTYPE html>
<html lang="it">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Giuliana Spano · CV e Portfolio</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Anton&family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
:root{color-scheme:dark;--bg:#131313;--bg2:#1c1c1c;--glass:rgba(255,255,255,.05);--ink:#ecece8;--mut:#9b9b97;--line:#2e2e2e;--acc:#8b2236;--acc2:#b4425a;
--disp:'Anton','Impact','Arial Narrow',sans-serif;--body:'Poppins','Helvetica Neue',Arial,sans-serif;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
html{scroll-padding-top:env(safe-area-inset-top,0px);height:100%}
*,*::before,*::after{box-sizing:inherit}
body{margin:0;height:100%;background:var(--bg);color:var(--ink);font:400 15px/1.65 var(--body);overflow:hidden}
[hidden]{display:none!important}
button{font:inherit;color:inherit;background:none;border:0;cursor:pointer}
:focus-visible{outline:2px solid var(--acc2);outline-offset:3px}
.tex{background-color:var(--bg);background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='220' height='220'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='.8' numOctaves='2'/%3E%3CfeColorMatrix values='0 0 0 0 1 0 0 0 0 1 0 0 0 0 1 0 0 0 .07 0'/%3E%3C/filter%3E%3Crect width='220' height='220' filter='url(%23n)'/%3E%3C/svg%3E")}

.lang{position:fixed;z-index:50;top:calc(env(safe-area-inset-top,0px) + 16px);right:clamp(14px,3vw,40px);display:flex;gap:2px;padding:3px;border:1px solid #444;border-radius:99px;background:rgba(19,19,19,.8);backdrop-filter:blur(8px)}
.lang button{padding:4px 12px;border-radius:99px;font-size:.78rem;color:var(--mut);transition:all .2s}
.lang button[aria-pressed=true]{background:var(--acc);color:#fff}
/* HOME */
.home{position:fixed;inset:0;z-index:20;display:flex;padding-top:env(safe-area-inset-top,0px)}
.home.open{visibility:hidden;transition:visibility 0s .9s}
.half{flex:1;position:relative;display:flex;flex-direction:column;justify-content:flex-end;padding:clamp(20px,4vw,56px);text-align:left;transition:transform .9s cubic-bezier(.77,0,.18,1)}
.half.l{border-right:1px solid var(--line)}
.half .t{font:400 clamp(2.2rem,7vw,6rem)/1 var(--disp);letter-spacing:.01em;text-transform:uppercase;position:relative;width:max-content;max-width:100%}
.half .t::after{content:"";position:absolute;left:0;bottom:-.12em;height:4px;width:34%;background:var(--acc);transition:width .5s}
.half:hover .t::after,.half:focus-visible .t::after{width:100%}
.half .s{margin:.9em 0 0;color:var(--mut);font-weight:300;max-width:24ch}
.half.r{text-align:right;align-items:flex-end}
.half.r .t::after{left:auto;right:0}
.open .half.l{transform:translateX(-101%)}.open .half.r{transform:translateX(101%)}
.name{position:absolute;z-index:2;top:clamp(18px,4vw,48px);left:0;right:0;text-align:center;pointer-events:none;transition:opacity .4s,transform .6s}
.name h1{margin:0;font:400 clamp(3.4rem,15.5vw,13rem)/.88 var(--disp);text-transform:uppercase;letter-spacing:.005em}
.name p{margin:1.1em 0 0;font-weight:300;font-size:clamp(.95rem,2vw,1.35rem);color:var(--mut)}
.open .name{opacity:0;transform:translateY(-30px)}
.chev{position:absolute;left:clamp(14px,3vw,40px);top:clamp(14px,3vw,40px);display:flex;gap:6px;opacity:.55}
.chev i{display:block;width:clamp(34px,6vw,76px);aspect-ratio:.8;background:radial-gradient(circle,#8a8a86 1.3px,transparent 1.8px) 0 0/7px 7px;clip-path:polygon(0 0,52% 0,100% 50%,52% 100%,0 100%,48% 50%)}
.chev i:nth-child(2){opacity:.7}.chev i:nth-child(3){opacity:.4}

/* VIEWS */
.view{position:fixed;inset:0;overflow-y:auto;z-index:10;opacity:0;visibility:hidden;transition:opacity .6s .35s,visibility 0s .95s;padding-top:env(safe-area-inset-top,0px)}
.view.on{opacity:1;visibility:visible;transition:opacity .6s .35s}
.bar{position:sticky;top:0;z-index:5;display:flex;gap:6px;align-items:center;padding:14px clamp(18px,4vw,56px);padding-right:calc(clamp(18px,4vw,56px) + 96px);background:rgba(19,19,19,.88);backdrop-filter:blur(10px);border-bottom:1px solid var(--line)}
.bar .home-b{font:400 1.5rem/1 var(--disp);letter-spacing:.04em;margin-right:auto;padding:6px 0}
.bar .tab{padding:6px 14px;color:var(--mut);border-bottom:2px solid transparent;transition:color .2s}
.bar .tab:hover{color:var(--ink)}.bar .tab.cur{color:var(--ink);border-color:var(--acc)}
.wrap{max-width:1180px;margin:0 auto;padding:clamp(28px,5vw,72px) clamp(18px,4vw,56px) 90px}
h2{font:400 clamp(2rem,4.5vw,3.4rem)/1 var(--disp);text-transform:uppercase;margin:0 0 .6em}
h3{font:500 .8rem/1.2 var(--body);letter-spacing:.12em;margin:0 0 14px;color:var(--mut);text-transform:none}
.panel{background:var(--glass);border:1px solid var(--line);border-radius:18px;padding:26px 28px;margin-bottom:22px;backdrop-filter:blur(6px)}

/* CV */
.cv{display:grid;grid-template-columns:minmax(0,340px) minmax(0,1fr);gap:clamp(24px,4vw,64px);align-items:start}
@media(max-width:860px){.cv{grid-template-columns:1fr}}
.side{position:sticky;top:84px}
@media(max-width:860px){.side{position:static}}
.hero{font:400 clamp(2.6rem,6vw,4.4rem)/.92 var(--disp);text-transform:uppercase;margin:0}
.role{color:var(--mut);font-weight:300;margin:.8em 0 1.4em}
.about{font-size:.9rem;color:#c9c9c5}
.contacts a{color:var(--ink);text-decoration:none;border-bottom:1px solid var(--acc);display:inline-block;margin:0 14px 6px 0;font-size:.88rem}
.contacts a:hover{color:var(--acc2)}
.edu li,.edu{list-style:none;margin:0;padding:0}
.edu li{display:flex;gap:10px;justify-content:space-between;align-items:flex-start;margin-bottom:14px;font-size:.88rem}
.edu b{font-weight:500;display:block}.edu span{color:var(--mut);font-size:.8rem}
.go{flex:none;width:34px;height:34px;border-radius:50%;border:1px solid var(--acc);display:grid;place-items:center;color:var(--ink);transition:background .25s}
.go:hover{background:var(--acc)}
.go svg{width:16px;height:16px}
.sk{display:grid;grid-template-columns:1fr auto;gap:2px 12px;align-items:center;font-size:.84rem;margin-bottom:9px}
.bars{display:flex;gap:3px}.bars i{width:16px;height:5px;background:#3a3a3a;border-radius:2px}.bars i.f{background:var(--acc)}
.tags{display:flex;flex-wrap:wrap;gap:8px;margin:0 0 10px}
.tag{padding:7px 16px;border:1px solid #444;border-radius:99px;font-size:.84rem;color:#cfcfcb;transition:all .2s}
.tag:hover{border-color:var(--acc2)}.tag[aria-pressed=true]{background:var(--acc);border-color:var(--acc);color:#fff}
.count{color:var(--mut);font-size:.82rem;margin:0 0 26px;min-height:1.4em}
.exp{list-style:none;margin:0 0 50px;padding:0;border-left:1px solid var(--line)}
.exp li{position:relative;padding:0 0 28px 28px}
.exp li::before{content:"";position:absolute;left:-5px;top:.55em;width:9px;height:9px;border-radius:50%;background:var(--bg);border:2px solid var(--acc)}
.exp .p{font-size:.78rem;color:var(--mut)}
.exp h4{margin:.1em 0 0;font:500 1.05rem/1.35 var(--body)}
.exp .o{color:#b9b9b5;font-size:.86rem;font-weight:300}
.exp p{margin:.5em 0 .6em;font-size:.9rem;color:#c9c9c5;max-width:62ch}
.exp .m{display:flex;gap:6px;flex-wrap:wrap}.exp .m em{font-style:normal;font-size:.72rem;color:var(--mut);border:1px solid var(--line);border-radius:99px;padding:1px 10px}
.list{margin:0;padding:0;list-style:none;font-size:.88rem;color:#c9c9c5}.list li{margin-bottom:8px}

/* PORTFOLIO */
.cats{border-top:1px solid var(--line)}
.cat{display:grid;grid-template-columns:1fr auto;gap:4px 20px;align-items:end;width:100%;text-align:left;padding:26px 4px;border-bottom:1px solid var(--line);position:relative}
.cat .n{font:400 clamp(1.8rem,5vw,3.6rem)/1 var(--disp);text-transform:uppercase;transition:transform .35s,color .3s}
.cat .d{color:var(--mut);font-weight:300;grid-column:1}
.cat .c{grid-row:1/3;grid-column:2;color:var(--mut);font-size:.85rem}
.cat::after{content:"";position:absolute;left:0;bottom:-1px;height:3px;width:0;background:var(--acc);transition:width .5s}
.cat:hover::after,.cat:focus-visible::after{width:100%}.cat:hover .n{transform:translateX(12px);color:#fff}

/* CAROUSEL */
.car{position:fixed;inset:0;z-index:40;background:rgba(10,10,10,.94);backdrop-filter:blur(12px);display:flex;flex-direction:column;align-items:center;justify-content:center;padding:clamp(16px,4vw,48px);padding-top:calc(clamp(16px,4vw,48px) + env(safe-area-inset-top,0px));opacity:0;visibility:hidden;transition:opacity .35s,visibility 0s .35s}
.car.on{opacity:1;visibility:visible;transition:opacity .35s}
.x{position:absolute;top:calc(66px + env(safe-area-inset-top,0px));right:clamp(16px,3vw,40px);width:46px;height:46px;border-radius:50%;border:1px solid var(--acc);display:grid;place-items:center;font-size:1.3rem;transition:background .25s}
.x:hover{background:var(--acc)}
.stage{display:flex;align-items:center;gap:clamp(8px,2vw,24px);width:100%;max-width:1000px}
.arr{flex:none;width:44px;height:44px;border-radius:50%;border:1px solid #444;font-size:1.3rem;transition:border-color .2s}.arr:hover{border-color:var(--acc2)}
.slide{flex:1;aspect-ratio:3/2;border-radius:14px;overflow:hidden;display:grid;place-items:center;text-align:center;color:#8d8d89;font-weight:300;font-size:.9rem;border:1px solid var(--line)}
.slide img{width:100%;height:100%;object-fit:cover}
.cap{max-width:1000px;width:100%;margin-top:18px;text-align:left;padding:0 clamp(0px,6vw,68px)}
.cap b{font:400 1.5rem/1.2 var(--disp);text-transform:uppercase;display:block}.cap span{color:#b9b9b5;font-size:.9rem}
.dots{display:flex;gap:8px;margin-top:14px}.dots i{width:22px;height:3px;background:#3a3a3a;transition:background .3s}.dots i.on{background:var(--acc2)}
@media(prefers-reduced-motion:reduce){*{transition-duration:.01s!important;transition-delay:0s!important}}
</style>
</head>
<body class="tex">
<div class="lang" role="group" aria-label="Lingua / Language"><button data-l="it" lang="it" aria-pressed="true">IT</button><button data-l="en" lang="en" aria-pressed="false">EN</button></div>

<main class="home tex" id="home">
  <div class="chev" aria-hidden="true"><i></i><i></i><i></i></div>
  <div class="name"><h1>Giuliana<br>Spano</h1><p>Grafica, fotografa e creativa digitale</p></div>
  <button class="half l tex" data-go="cv"><span class="t">CV</span><span class="s">Esperienze, studi e competenze</span></button>
  <button class="half r tex" data-go="portfolio"><span class="t">Portfolio</span><span class="s">Lavori, commissioni e progetti</span></button>
</main>

<section class="view tex" id="cv" aria-label="Curriculum">
  <div class="bar"><button class="home-b" data-go="">GS</button><button class="tab cur" data-go="cv">CV</button><button class="tab" data-go="portfolio">Portfolio</button></div>
  <div class="wrap cv">
    <aside class="side">
      <h1 class="hero">Giuliana Mariangela Spano</h1>
      <p class="role">Grafica, fotografa e creativa digitale</p>
      <div class="contacts"><a href="mailto:amyl91@live.it">amyl91@live.it</a><a href="https://www.instagram.com/404amyl" target="_blank" rel="noopener">Instagram</a><a href="https://www.linkedin.com/in/giuliana-mariangela-spano-amyl" target="_blank" rel="noopener">LinkedIn</a></div>
      <div class="panel" style="margin-top:22px"><h3>Chi sono</h3><div class="about">Creativa, dinamica e versatile, amo affrontare nuove sfide e imparare rapidamente. Ho una forte attitudine al problem solving, all’organizzazione e alla collaborazione. Mi appassiona tutto ciò che unisce arte, tecnologia e comunicazione. Precisa e attenta ai dettagli, do sempre il massimo in ogni progetto.</div></div>
      <div class="panel"><h3>Istruzione</h3><ul class="edu" id="edu"></ul></div>
      <div class="panel"><h3>Competenze</h3><div id="skills"></div></div>
    </aside>
    <div>
      <h2>Esperienze</h2>
      <p style="margin:-.2em 0 14px;color:var(--mut);font-weight:300">Scegli uno o più ambiti per vedere solo le esperienze correlate.</p>
      <div class="tags" id="tags" role="group" aria-label="Filtra per ambito"></div>
      <p class="count" id="count" aria-live="polite"></p>
      <ol class="exp" id="exp"></ol>
      <div class="panel"><h3>Corsi attestati</h3><ul class="list"><li>YTiA Online, Game Developer: C# e Unity di base, modellazione e animazione 3D con Maya (2020)</li><li>Tecniche base di contabilità, Formindustria (2025)</li></ul></div>
      <div class="panel"><h3>Riconoscimenti e premi</h3><ul class="list"><li>3° posto, premio “Sezione Grafica”, A.F.A. (2005)</li><li>Premio all’elaborato grafico, AIFO Cinquantenario (2011)</li><li>2° premio “Miglior Elaborato Grafico”, concorso per le scuole della Provincia di Catania (2011)</li></ul></div>
      <div class="panel"><h3>Pubblicazioni</h3><ul class="list"><li>D.O.M.A. Diary of Magic Adventures, Tora Edizioni (2020)</li></ul></div>
    </div>
  </div>
</section>

<section class="view tex" id="portfolio" aria-label="Portfolio">
  <div class="bar"><button class="home-b" data-go="">GS</button><button class="tab" data-go="cv">CV</button><button class="tab cur" data-go="portfolio">Portfolio</button></div>
  <div class="wrap">
    <h2>Portfolio</h2>
    <p style="margin:-.2em 0 34px;color:var(--mut);font-weight:300">Scegli una raccolta per sfogliare i lavori.</p>
    <div class="cats" id="cats"></div>
  </div>
</section>

<div class="car tex" id="car" role="dialog" aria-modal="true" aria-label="Galleria">
  <button class="x" id="x" aria-label="Chiudi galleria">✕</button>
  <div class="stage"><button class="arr" id="pv" aria-label="Precedente">‹</button><div class="slide" id="sl"></div><button class="arr" id="nx" aria-label="Successiva">›</button></div>
  <div class="cap"><b id="ct"></b><span id="cd"></span><div class="dots" id="dt"></div></div>
</div>

<script>
const $=s=>document.querySelector(s);
const TAGS={design:'Design',foto:'Fotografia',vendita:'Vendita',clienti:'Cura del cliente',office:'Gestione office',it:'Informatica',web:'Web e social',handmade:'Handmade',rist:'Ristorazione'};
const EXP=[
['Lug – Set 2025','Tecnico informatico','S1-NE SRLS, Cervignano del Friuli','Riparazione e manutenzione on-site di PC, dispositivi HP e stampanti; installazione e configurazione di router e connessioni di rete.',['it','clienti']],
['Dic 2022 – Nov 2023','Addetto alle vendite','Mediaworld, Villesse','Consulenza nel reparto informatica, TV e console; supporto tecnico e configurazione dei dispositivi.',['vendita','clienti','it']],
['Ago – Nov 2022','Aiuto commessa','Inside, Villesse','Vendita assistita, gestione di cassa e pagamenti, ordine ed esposizione della merce.',['vendita','clienti','office']],
['Mag 2021 – Feb 2022','Addetto alle vendite','IKEA, Villesse','Front office, accoglienza al reparto progettazione, pratiche di finanziamento e consegne, appuntamenti in showroom, catalogazione e prezzatura.',['vendita','clienti','office']],
['Set 2020 – Mar 2021','Addetto alle vendite (stage)','IKEA, Villesse','Vendita diretta e dimostrazione dei prodotti nella grande distribuzione.',['vendita','clienti']],
['Dic 2019 – Feb 2020','Operatore di ristorazione','La Caveja, Gorizia','Organizzazione del lavoro in cucina, conservazione e preparazione delle vivande nel rispetto degli standard di qualità.',['rist']],
['Dic 2019 – Gen 2020','Operatore di ristorazione','McDonald’s, Villesse','Servizio alla clientela rapido e preciso anche nei momenti di maggiore affluenza.',['rist','clienti']],
['Mag 2018 – Mag 2019','Grafico e fotografo','Clan Gaming Center a.s.d., Catania','In smartworking: grafiche digitali per il web e locandine promozionali per la comunicazione degli eventi.',['design','web']],
['Dic 2017 – Feb 2018','Apprendista','Gameplay, Giarre','Cura del negozio, servizio ai clienti, scarico merci, registrazione bolle, inventario e gestione delle postazioni gaming.',['clienti','office','vendita']],
['Ott 2016 – Ott 2017','Grafico, fotografo e web manager','Istituto Musicale Brahms, Riposto','Grafiche e nuovo logo, foto degli eventi, pagine web e social, e-mail di comunicazione agli studenti.',['design','foto','web']],
['Set 2012 – Ago 2013','Grafico e fotografo','Ass. Diversamente Noi, Giarre','Ideazione e realizzazione di tutte le vesti grafiche; foto durante le manifestazioni.',['design','foto']],
['Dal 2013','Fotografo','Commissioni a privati','Servizi fotografici per clienti ed eventi, con fotoritocco quando necessario.',['foto']],
['Dal 2013','Grafico','Commissioni a privati','Lavori grafici per clienti diversi, anche a distanza, cercando l’incontro tra un buon lavoro e le esigenze del cliente.',['design','clienti']],
['Dal 2013','Web entertainer','Twitch','Dirette con un vasto pubblico online: intrattenimento, recensioni e notizie sul mondo dei videogiochi, illustrazioni mostrate dal vivo.',['web']],
['Dal 2011','Crafter di oggetti e costumi di scena','Commissioni a privati','Costumi e oggetti di scena, da piccole spille a piccole scenografie.',['handmade']],
['Dal 2008','Illustratrice','Freelance','Illustrazioni di vario genere su richiesta.',['design']],
['Progetto','Ex vicepresidente','ASD 404 Gaming Not Found','Gestione documentale e organizzativa, pianificazione di eventi, coordinamento di piattaforme web e social, supporto ai team sportivi e comunicazione con gli associati.',['office','web']]];
const EDU=[['Diploma Accademico in Arti Tecnologiche, 1° livello','Accademia di Belle Arti di Catania, 2018','formazione'],['Diploma d’Arte in Grafica pubblicitaria','Liceo Artistico Brunelleschi, Acireale, 2013','formazione']];
const SK=[['Suite Adobe',4],['Corel Draw',5],['Suite Office',4],['Contabilità di base',3],['Elaborazione con IA',3],['Informatica tecnica e pratica',5],['Modellazione 3D con Maya',2],['Modellazione 3D con Blender',3]];
const PF={
lavoro:{n:'Lavoro',d:'Grafiche, loghi e foto per realtà con cui ho collaborato',s:[['Identità dell’Istituto Brahms','Didascalia di esempio: nuovo logo e grafiche per gli eventi.'],['Locandine per eventi','Didascalia di esempio: materiali promozionali per Clan Gaming Center.'],['Reportage eventi','Didascalia di esempio: fotografie realizzate durante le manifestazioni.']]},
commissioni:{n:'Commissioni',d:'Illustrazioni, grafiche, foto e costumi su richiesta',s:[['Illustrazione su richiesta','Didascalia di esempio.'],['Costume di scena','Didascalia di esempio.'],['Servizio fotografico','Didascalia di esempio.']]},
formazione:{n:'Formazione ed educazione',d:'Elaborati dagli studi artistici e dai corsi',s:[['Arti Tecnologiche, Accademia di Belle Arti','Didascalia di esempio: elaborato del corso.'],['Modellazione 3D con Maya','Didascalia di esempio: modello realizzato durante il corso.'],['Grafica pubblicitaria, Liceo Artistico','Didascalia di esempio.']]},
progetti:{n:'Progetti',d:'404 Gaming Not Found e D.O.M.A.',s:[['404 Gaming Not Found','Didascalia di esempio: grafiche dell’associazione.'],['D.O.M.A. Diary of Magic Adventures','Didascalia di esempio: pubblicazione Tora Edizioni, 2020.']]}};
/* Per usare immagini vere: aggiungi un terzo valore con l'indirizzo, es. ['Titolo','Didascalia','img/foto.jpg'] */

const icon='<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="4" width="18" height="16" rx="2"/><circle cx="9" cy="10" r="1.7"/><path d="m21 16-5-5-9 9"/></svg>';
/* LINGUA: l'italiano è nei dati e nell'HTML; l'inglese sta qui sotto. Ogni nuovo contenuto va aggiunto in entrambe le lingue. */
let L='it';try{L=localStorage.getItem('lang')==='en'?'en':'it'}catch(_){}
const T=(it,en)=>L==='en'?en:it;
const EN={
tags:{design:'Design',foto:'Photography',vendita:'Sales',clienti:'Customer care',office:'Office management',it:'IT',web:'Web & social',handmade:'Handmade',rist:'Food service'},
exp:[
['Jul – Sep 2025','IT technician','S1-NE SRLS, Cervignano del Friuli','On-site repair and maintenance of PCs, HP devices and office printers; installation and configuration of routers and network connections.'],
['Dec 2022 – Nov 2023','Sales associate','Mediaworld, Villesse','Advice in the IT department on computers, TVs and gaming consoles; technical support and device setup.'],
['Aug – Nov 2022','Shop assistant','Inside, Villesse','Assisted selling, till and payment handling, merchandise order and display.'],
['May 2021 – Feb 2022','Sales associate','IKEA, Villesse','Front office, welcoming customers at the planning department, financing and delivery paperwork, showroom appointments, cataloguing and pricing.'],
['Sep 2020 – Mar 2021','Sales associate (internship)','IKEA, Villesse','Direct selling and product demonstrations in large-scale retail.'],
['Dec 2019 – Feb 2020','Food service operator','La Caveja, Gorizia','Kitchen work organisation, food storage and preparation to quality standards.'],
['Dec 2019 – Jan 2020','Food service operator','McDonald’s, Villesse','Fast, accurate customer service, even at the busiest times.'],
['May 2018 – May 2019','Graphic designer and photographer','Clan Gaming Center a.s.d., Catania','Remote work: digital graphics for the web and promotional posters to support event communication.'],
['Dec 2017 – Feb 2018','Apprentice','Gameplay, Giarre','Store upkeep, customer service, unloading goods, delivery notes, inventory and management of the gaming stations.'],
['Oct 2016 – Oct 2017','Graphic designer, photographer and web manager','Istituto Musicale Brahms, Riposto','Graphics and a new logo, event photography, web pages and social media, email communication to students.'],
['Sep 2012 – Aug 2013','Graphic designer and photographer','Ass. Diversamente Noi, Giarre','Design and production of all the association’s graphics; photography at its events.'],
['Since 2013','Photographer','Private commissions','Photo shoots for clients and events, with retouching when needed.'],
['Since 2013','Graphic designer','Private commissions','Graphic work for a range of clients, often remotely, finding the balance between good work and what the client wants.'],
['Since 2013','Web entertainer','Twitch','Live streams to a large online audience: entertainment, reviews and video game news, with illustrations shown live.'],
['Since 2011','Crafter of props and costumes','Private commissions','Costumes and props, from small pins to small set pieces.'],
['Since 2008','Illustrator','Freelance','Illustrations of all kinds on request.'],
['Project','Former vice president','ASD 404 Gaming Not Found','Document and organisational management, event planning, coordination of web and social platforms, support for esports teams and communication with members.']],
edu:[['Academic Diploma in Technological Arts, 1st level','Accademia di Belle Arti di Catania, 2018'],['Art Diploma in Advertising Graphics','Liceo Artistico Brunelleschi, Acireale, 2013']],
sk:['Adobe Suite','Corel Draw','Office Suite','Basic accounting','AI-assisted work','Technical and practical IT','3D modelling with Maya','3D modelling with Blender'],
pf:{
lavoro:['Work','Graphics, logos and photos for the organisations I worked with',[['Istituto Brahms identity','Sample caption: new logo and graphics for events.'],['Event posters','Sample caption: promotional material for Clan Gaming Center.'],['Event reportage','Sample caption: photographs taken at events.']]],
commissioni:['Commissions','Illustrations, graphics, photos and costumes on request',[['Illustration on request','Sample caption.'],['Stage costume','Sample caption.'],['Photo shoot','Sample caption.']]],
formazione:['Education and training','Pieces from art studies and courses',[['Technological Arts, Academy of Fine Arts','Sample caption: coursework piece.'],['3D modelling with Maya','Sample caption: model made during the course.'],['Advertising graphics, Art high school','Sample caption.']]],
progetti:['Projects','404 Gaming Not Found and D.O.M.A.',[['404 Gaming Not Found','Sample caption: association graphics.'],['D.O.M.A. Diary of Magic Adventures','Sample caption: Tora Edizioni publication, 2020.']]]}};
/* Testi fissi dell'HTML: italiano (come scritto nella pagina) -> inglese */
const UI_EN={
'Grafica, fotografa e creativa digitale':'Graphic designer, photographer and digital creative',
'Esperienze, studi e competenze':'Experience, studies and skills',
'Lavori, commissioni e progetti':'Work, commissions and projects',
'Chi sono':'About me',
'Creativa, dinamica e versatile, amo affrontare nuove sfide e imparare rapidamente. Ho una forte attitudine al problem solving, all’organizzazione e alla collaborazione. Mi appassiona tutto ciò che unisce arte, tecnologia e comunicazione. Precisa e attenta ai dettagli, do sempre il massimo in ogni progetto.':'Creative, dynamic and versatile, I love taking on new challenges and learning fast. I have a strong aptitude for problem solving, organisation and teamwork. I’m passionate about everything that brings together art, technology and communication. Precise and detail-oriented, I always give my best on every project.',
'Istruzione':'Education','Competenze':'Skills','Esperienze':'Experience',
'Scegli uno o più ambiti per vedere solo le esperienze correlate.':'Pick one or more areas to see only the related experience.',
'Corsi attestati':'Certified courses',
'YTiA Online, Game Developer: C# e Unity di base, modellazione e animazione 3D con Maya (2020)':'YTiA Online, Game Developer: C# and Unity basics, 3D modelling and animation with Maya (2020)',
'Tecniche base di contabilità, Formindustria (2025)':'Basic accounting techniques, Formindustria (2025)',
'Riconoscimenti e premi':'Awards',
'3° posto, premio “Sezione Grafica”, A.F.A. (2005)':'3rd place, “Graphics Section” prize, A.F.A. (2005)',
'Premio all’elaborato grafico, AIFO Cinquantenario (2011)':'Graphic work award, AIFO 50th anniversary (2011)',
'2° premio “Miglior Elaborato Grafico”, concorso per le scuole della Provincia di Catania (2011)':'2nd prize “Best Graphic Work”, schools competition of the Province of Catania (2011)',
'Pubblicazioni':'Publications',
'Scegli una raccolta per sfogliare i lavori.':'Pick a collection to browse the work.'};
const tg=k=>L==='en'?EN.tags[k]:TAGS[k];
const ex=i=>L==='en'?EN.exp[i]:EXP[i];
const ed=i=>L==='en'?EN.edu[i]:EDU[i];
const pf=k=>L==='en'?{n:EN.pf[k][0],d:EN.pf[k][1],s:EN.pf[k][2]}:PF[k];
function renderDyn(){
 $('#edu').innerHTML=EDU.map((e,i)=>`<li><div><b>${ed(i)[0]}</b><span>${ed(i)[1]}</span></div><button class="go" data-pf="${e[2]}" aria-label="${T('Vedi i lavori collegati','See the related work')}">${icon}</button></li>`).join('');
 $('#skills').innerHTML=SK.map((s,i)=>`<div class="sk"><span>${T(s[0],EN.sk[i])}</span><span class="bars">${[1,2,3,4,5].map(n=>`<i class="${n<=s[1]?'f':''}"></i>`).join('')}</span></div>`).join('')+`<div class="sk" style="margin-top:14px"><span>${T('Italiano','Italian')}</span><span style="color:var(--mut)">${T('madrelingua','native')}</span><span>${T('Inglese','English')}</span><span style="color:var(--mut)">${T('avanzato','advanced')}</span></div>`;
 $('#exp').innerHTML=EXP.map((e,i)=>{const x=ex(i);return `<li data-i="${i}"><div class="p">${x[0]}</div><h4>${x[1]}</h4><div class="o">${x[2]}</div><p>${x[3]}</p><div class="m">${e[4].map(t=>`<em>${tg(t)}</em>`).join('')}</div></li>`}).join('');
 $('#tags').innerHTML=`<button class="tag" data-t="">${T('Tutte','All')}</button>`+Object.keys(TAGS).map(k=>`<button class="tag" data-t="${k}">${tg(k)}</button>`).join('');
 $('#cats').innerHTML=Object.keys(PF).map(k=>{const c=pf(k);return `<button class="cat" data-pf="${k}"><span class="n">${c.n}</span><span class="d">${c.d}</span><span class="c">${c.s.length} ${T('lavori','works')}</span></button>`}).join('');
 filt();
}
const norm=s=>s.replace(/\s+/g,' ').trim();
function applyLang(){
 document.documentElement.lang=L;
 document.title=T('Giuliana Spano · CV e Portfolio','Giuliana Spano · CV and Portfolio');
 $('#x').setAttribute('aria-label',T('Chiudi galleria','Close gallery'));$('#pv').setAttribute('aria-label',T('Precedente','Previous'));$('#nx').setAttribute('aria-label',T('Successiva','Next'));
 const w=document.createTreeWalker(document.body,NodeFilter.SHOW_TEXT);let n;
 while(n=w.nextNode()){
  if(n.parentElement.closest('script,#exp,#tags,#cats,#edu,#skills,.car'))continue;
  if(n.__it===undefined){if(!UI_EN[norm(n.nodeValue)])continue;n.__it=n.nodeValue}
  n.nodeValue=L==='en'?UI_EN[norm(n.__it)]:n.__it;
 }
}
function setLang(l){
 L=l;try{localStorage.setItem('lang',l)}catch(_){}
 document.querySelectorAll('.lang button').forEach(b=>b.setAttribute('aria-pressed',b.dataset.l===L));
 renderDyn();applyLang();if(cur&&$('#car').classList.contains('on'))draw();
}
$('.lang').onclick=e=>{const b=e.target.closest('[data-l]');if(b)setLang(b.dataset.l)};


/* filtro tag */
const sel=new Set();


function filt(){
  document.querySelectorAll('#exp li').forEach(li=>{li.hidden=sel.size&&!EXP[li.dataset.i][4].some(t=>sel.has(t))});
  document.querySelectorAll('.tag').forEach(b=>b.setAttribute('aria-pressed',b.dataset.t?sel.has(b.dataset.t):!sel.size));
  const n=document.querySelectorAll('#exp li:not([hidden])').length;
  $('#count').textContent=sel.size?T(`${n} ${n==1?'esperienza':'esperienze'} su ${EXP.length}`,`${n} of ${EXP.length} ${n==1?'experience':'experiences'}`):'';
}
$('#tags').onclick=e=>{const b=e.target.closest('.tag');if(!b)return;const t=b.dataset.t;if(!t)sel.clear();else sel.has(t)?sel.delete(t):sel.add(t);filt()};

/* portfolio list */


/* navigazione */
function show(v){
  document.body.dataset.view=v;
  $('#home').classList.toggle('open',!!v);
  document.querySelectorAll('.view').forEach(e=>{e.classList.toggle('on',e.id===v);if(e.id===v)e.scrollTop=0});
  try{history.replaceState(null,'',v?'#'+v:location.pathname)}catch(_){}
}
document.addEventListener('click',e=>{
  const g=e.target.closest('[data-go]');if(g)show(g.dataset.go);
  const p=e.target.closest('[data-pf]');if(p)openCar(p.dataset.pf,p);
});

/* carosello */
let cur=null,idx=0,opener=null;
function draw(){
  const s=pf(cur).s[idx],im=PF[cur].s[idx][2];
  $('#sl').innerHTML=im?`<img src="${im}" alt="${s[0]}">`:`<div style="width:100%;height:100%;display:grid;place-items:center;background:linear-gradient(${120+idx*40}deg,#222,#363636 55%,#2a2024)">${T('Immagine da inserire','Image to be added')}</div>`;
  $('#ct').textContent=s[0];$('#cd').textContent=s[1];
  $('#dt').innerHTML=PF[cur].s.map((_,i)=>`<i class="${i==idx?'on':''}"></i>`).join('');
}
function openCar(k,from){cur=k;idx=0;opener=from;draw();$('#car').classList.add('on');$('#x').focus()}
function closeCar(){$('#car').classList.remove('on');if(opener)opener.focus()}
function step(d){const n=PF[cur].s.length;idx=(idx+d+n)%n;draw()}
$('#x').onclick=closeCar;$('#pv').onclick=()=>step(-1);$('#nx').onclick=()=>step(1);
$('#car').addEventListener('click',e=>{if(e.target.id==='car')closeCar()});
document.addEventListener('keydown',e=>{if(!$('#car').classList.contains('on'))return;if(e.key==='Escape')closeCar();if(e.key==='ArrowLeft')step(-1);if(e.key==='ArrowRight')step(1)});
setLang(L);
show(['cv','portfolio'].includes(location.hash.slice(1))?location.hash.slice(1):'');
</script>
</body>
</html>
