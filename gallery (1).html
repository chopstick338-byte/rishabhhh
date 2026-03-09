<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>My Gallery</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,500;1,400;1,500&family=DM+Sans:wght@200;300;400;500&display=swap" rel="stylesheet"/>
<style>
:root{
  --bg:#0e0c09;--bg2:#141210;--bg3:#1a1714;
  --warm:#c8a96e;--warm2:#e2c99a;--warm3:#f0e0bc;
  --wdim:rgba(200,169,110,0.1);--wbdr:rgba(200,169,110,0.2);
  --text:#f0e6d3;--textmd:rgba(240,230,211,0.6);--textsm:rgba(240,230,211,0.3);
  --red:#b94040;--green:#5a9e6f;
  --serif:'Playfair Display',Georgia,serif;
  --sans:'DM Sans',sans-serif;
  --ease:cubic-bezier(0.4,0,0.2,1);
}
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0;}
html{scroll-behavior:smooth;}
body{background:var(--bg);color:var(--text);font-family:var(--sans);font-weight:300;min-height:100vh;overflow-x:hidden;}

/* grain overlay */
body::after{content:'';position:fixed;inset:0;background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='200' height='200'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='200' height='200' filter='url(%23n)' opacity='0.04'/%3E%3C/svg%3E");pointer-events:none;z-index:9998;}

/* ── LOCK ── */
#lock{position:fixed;inset:0;z-index:9999;display:flex;flex-direction:column;align-items:center;justify-content:center;background:var(--bg);}
.l-bg{position:absolute;inset:0;background:radial-gradient(ellipse 70% 50% at 50% 65%,rgba(160,120,50,0.15) 0%,transparent 70%);}
.l-ornament{position:relative;z-index:1;display:flex;align-items:center;gap:18px;margin-bottom:32px;opacity:.4;}
.l-ornament::before,.l-ornament::after{content:'';display:block;width:48px;height:1px;background:var(--warm);}
.l-ornament span{font-size:.6rem;letter-spacing:.3em;text-transform:uppercase;color:var(--warm);}
.l-title{position:relative;z-index:1;font-family:var(--serif);font-size:clamp(2.4rem,7vw,4.2rem);font-weight:400;color:var(--text);text-align:center;line-height:1.1;margin-bottom:6px;}
.l-title em{font-style:italic;color:var(--warm);}
.l-sub{position:relative;z-index:1;font-size:.65rem;letter-spacing:.28em;text-transform:uppercase;color:var(--textsm);margin-bottom:44px;}
.l-field{position:relative;z-index:1;width:320px;max-width:88vw;margin-bottom:12px;}
#li{width:100%;background:rgba(255,255,255,.03);border:1px solid var(--wbdr);color:var(--text);font-family:var(--sans);font-size:.88rem;letter-spacing:.15em;padding:15px 44px 15px 18px;text-align:center;outline:none;transition:border-color .25s,box-shadow .25s;}
#li::placeholder{color:var(--textsm);letter-spacing:.08em;font-size:.8rem;}
#li:focus{border-color:var(--warm);box-shadow:0 0 20px rgba(200,169,110,.1);}
#li.wrong{border-color:var(--red);animation:shake .4s var(--ease);}
@keyframes shake{0%,100%{transform:translateX(0)}25%,75%{transform:translateX(-6px)}50%{transform:translateX(6px)}}
.l-eye{position:absolute;right:14px;top:50%;transform:translateY(-50%);background:none;border:none;color:var(--textsm);cursor:pointer;}
.l-btn{position:relative;z-index:1;width:320px;max-width:88vw;background:linear-gradient(135deg,var(--warm),#8a6020);border:none;color:#0a0805;font-family:var(--sans);font-size:.68rem;font-weight:600;letter-spacing:.24em;padding:16px;text-transform:uppercase;cursor:pointer;transition:opacity .2s,transform .15s;}
.l-btn:hover{opacity:.88;transform:translateY(-1px);}
.l-err{position:relative;z-index:1;color:var(--red);font-size:.72rem;min-height:16px;margin-top:8px;text-align:center;letter-spacing:.04em;}

/* ── NAV ── */
#nav{position:fixed;top:0;left:0;right:0;height:56px;background:rgba(14,12,9,.92);backdrop-filter:blur(20px);border-bottom:1px solid rgba(255,255,255,.04);z-index:1000;display:none;align-items:center;justify-content:space-between;padding:0 36px;}
.n-brand{font-family:var(--serif);font-size:1rem;font-style:italic;color:var(--warm);letter-spacing:.05em;}
.n-links{display:flex;list-style:none;gap:0;}
.n-links a{font-size:.63rem;letter-spacing:.18em;text-transform:uppercase;color:var(--textsm);text-decoration:none;padding:8px 14px;cursor:pointer;transition:color .2s;position:relative;}
.n-links a::after{content:'';position:absolute;bottom:0;left:14px;right:14px;height:1px;background:var(--warm);transform:scaleX(0);transition:transform .25s var(--ease);}
.n-links a:hover,.n-links a.active{color:var(--text);}
.n-links a.active::after,.n-links a:hover::after{transform:scaleX(1);}

/* ── APP ── */
#app{padding-top:56px;display:none;min-height:100vh;}
.page{display:none;min-height:calc(100vh - 56px);padding:48px 40px 80px;max-width:1200px;margin:0 auto;animation:fadeUp .4s var(--ease);}
.page.active{display:block;}
@keyframes fadeUp{from{opacity:0;transform:translateY(10px)}to{opacity:1;transform:translateY(0)}}

.ph{font-family:var(--serif);font-size:clamp(1.8rem,3.5vw,2.6rem);font-weight:400;color:var(--text);margin-bottom:4px;}
.ph em{font-style:italic;color:var(--warm);}
.phr{width:100%;height:1px;background:linear-gradient(90deg,var(--wbdr),transparent);margin-bottom:32px;}
.psub{font-size:.7rem;letter-spacing:.12em;text-transform:uppercase;color:var(--textsm);margin-bottom:32px;}

/* ── PHOTO GRID ── */
.pgrid{columns:4 180px;gap:8px;}
.pgrid .gitem{break-inside:avoid;margin-bottom:8px;position:relative;overflow:hidden;cursor:pointer;background:var(--bg3);}
.pgrid .gitem img{width:100%;display:block;transition:transform .5s var(--ease);}
.pgrid .gitem:hover img{transform:scale(1.04);}
.gitem-ov{position:absolute;inset:0;background:linear-gradient(to top,rgba(0,0,0,.6) 0%,transparent 50%);opacity:0;transition:opacity .3s;display:flex;flex-direction:column;justify-content:flex-end;padding:12px;}
.gitem:hover .gitem-ov{opacity:1;}
.gitem-date{font-size:.62rem;color:rgba(255,255,255,.5);letter-spacing:.08em;}
.gitem-album{font-size:.68rem;color:var(--warm);letter-spacing:.06em;}
.gitem-fav{position:absolute;top:8px;right:8px;background:none;border:none;color:rgba(255,255,255,.4);cursor:pointer;font-size:.95rem;transition:color .2s,transform .2s;opacity:0;}
.gitem:hover .gitem-fav{opacity:1;}
.gitem-fav.on{opacity:1;color:#e05555;}
.gitem-del{position:absolute;top:8px;left:8px;background:rgba(0,0,0,.5);border:none;color:rgba(255,255,255,.5);cursor:pointer;font-size:.62rem;letter-spacing:.1em;padding:4px 8px;opacity:0;transition:opacity .2s;}
.gitem:hover .gitem-del{opacity:1;}
.gitem-del:hover{color:#fff;}

/* ── ALBUMS ── */
.albgrid{display:grid;grid-template-columns:repeat(auto-fill,minmax(200px,1fr));gap:16px;margin-bottom:32px;}
.albcard{position:relative;aspect-ratio:1;overflow:hidden;cursor:pointer;background:var(--bg3);border:1px solid rgba(255,255,255,.04);}
.albcard img{width:100%;height:100%;object-fit:cover;transition:transform .5s var(--ease);}
.albcard:hover img{transform:scale(1.06);}
.albcard-empty{width:100%;height:100%;display:flex;align-items:center;justify-content:center;font-size:2rem;opacity:.2;}
.albcard-ov{position:absolute;inset:0;background:linear-gradient(to top,rgba(0,0,0,.75) 0%,transparent 55%);display:flex;flex-direction:column;justify-content:flex-end;padding:14px;}
.albcard-name{font-family:var(--serif);font-size:1.05rem;font-style:italic;color:var(--text);}
.albcard-count{font-size:.65rem;color:var(--textmd);letter-spacing:.1em;margin-top:2px;}
.alb-new{background:none;border:1px dashed var(--wbdr);color:var(--textmd);cursor:pointer;font-family:var(--sans);font-size:.72rem;letter-spacing:.15em;text-transform:uppercase;aspect-ratio:1;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:8px;transition:all .2s;}
.alb-new:hover{border-color:var(--warm);color:var(--warm);}
.alb-new span{font-size:1.6rem;opacity:.4;}

/* ── ADD PHOTO AREA ── */
.upload-zone{border:1px dashed var(--wbdr);padding:36px 24px;text-align:center;cursor:pointer;transition:all .25s;position:relative;margin-bottom:28px;}
.upload-zone:hover,.upload-zone.drag-over{border-color:var(--warm);background:rgba(200,169,110,.05);}
.upload-zone input{position:absolute;inset:0;opacity:0;cursor:pointer;width:100%;height:100%;}
.uz-icon{font-size:1.8rem;margin-bottom:8px;opacity:.4;}
.uz-txt{font-size:.82rem;color:var(--textmd);letter-spacing:.05em;}
.uz-sub{font-size:.66rem;color:var(--textsm);margin-top:4px;}

/* ── BUTTONS ── */
.btn-gold{background:linear-gradient(135deg,var(--warm),#8a6020);border:none;color:#0a0805;font-family:var(--sans);font-size:.68rem;font-weight:600;letter-spacing:.2em;padding:12px 24px;text-transform:uppercase;cursor:pointer;transition:opacity .2s,transform .15s;}
.btn-gold:hover{opacity:.88;transform:translateY(-1px);}
.btn-out{background:none;border:1px solid var(--wbdr);color:var(--textmd);font-family:var(--sans);font-size:.68rem;letter-spacing:.15em;padding:11px 22px;text-transform:uppercase;cursor:pointer;transition:all .2s;}
.btn-out:hover{border-color:var(--warm);color:var(--warm);}

/* ── EMPTY STATE ── */
.empty{border:1px dashed rgba(255,255,255,.06);padding:64px 24px;text-align:center;}
.empty-icon{font-size:2rem;margin-bottom:14px;opacity:.25;}
.empty-title{font-family:var(--serif);font-style:italic;font-size:1.5rem;color:var(--textmd);}
.empty-sub{font-size:.7rem;letter-spacing:.1em;color:var(--textsm);margin-top:6px;}

/* ── LIGHTBOX ── */
#lb{position:fixed;inset:0;background:rgba(0,0,0,.97);z-index:5000;display:none;align-items:center;justify-content:center;padding:16px;}
#lb.open{display:flex;}
#lb img{max-width:92vw;max-height:88vh;object-fit:contain;user-select:none;}
#lbclose{position:absolute;top:16px;right:16px;background:rgba(255,255,255,.08);border:1px solid rgba(255,255,255,.15);color:#fff;cursor:pointer;font-size:.65rem;letter-spacing:.14em;padding:9px 16px;}
#lbclose:hover{background:rgba(255,255,255,.16);}
.lb-arr{position:absolute;top:50%;transform:translateY(-50%);background:rgba(255,255,255,.07);border:1px solid rgba(255,255,255,.12);color:#fff;cursor:pointer;width:46px;height:46px;font-size:1.3rem;display:flex;align-items:center;justify-content:center;transition:background .2s;}
.lb-arr:hover{background:rgba(255,255,255,.16);}
#lb-prev{left:14px;}
#lb-next{right:14px;}
#lb-counter{position:absolute;top:18px;left:50%;transform:translateX(-50%);font-size:.66rem;color:rgba(255,255,255,.35);letter-spacing:.15em;}
#lb-cap{position:absolute;bottom:20px;left:50%;transform:translateX(-50%);font-family:var(--serif);font-style:italic;font-size:1rem;color:rgba(255,255,255,.45);text-align:center;width:90%;}
@media(max-width:580px){.lb-arr{display:none;}}

/* ── SLIDESHOW ── */
#ss{position:fixed;inset:0;background:#000;z-index:6000;display:none;align-items:center;justify-content:center;}
#ss.open{display:flex;}
#ss img{max-width:100vw;max-height:100vh;object-fit:contain;animation:ssIn .8s var(--ease);}
@keyframes ssIn{from{opacity:0;transform:scale(1.03)}to{opacity:1;transform:scale(1)}}
#ss-close{position:absolute;top:16px;right:16px;background:rgba(255,255,255,.08);border:1px solid rgba(255,255,255,.15);color:#fff;cursor:pointer;font-size:.65rem;letter-spacing:.14em;padding:9px 16px;}
#ss-ctrl{position:absolute;bottom:24px;left:50%;transform:translateX(-50%);display:flex;gap:12px;align-items:center;}
.ss-btn{background:rgba(255,255,255,.08);border:1px solid rgba(255,255,255,.15);color:#fff;cursor:pointer;font-size:.65rem;letter-spacing:.12em;padding:9px 18px;transition:background .2s;}
.ss-btn:hover{background:rgba(255,255,255,.16);}
#ss-counter{font-size:.65rem;color:rgba(255,255,255,.35);letter-spacing:.15em;min-width:60px;text-align:center;}

/* ── MODAL ── */
.mod-bg{position:fixed;inset:0;background:rgba(0,0,0,.65);z-index:4000;display:none;align-items:center;justify-content:center;padding:16px;}
.mod-bg.open{display:flex;}
.mod{background:var(--bg2);border:1px solid var(--wbdr);padding:30px;width:400px;max-width:100%;animation:fadeUp .3s var(--ease);}
.mod h3{font-family:var(--serif);font-style:italic;font-size:1.5rem;color:var(--warm);margin-bottom:18px;}
.fg{margin-bottom:14px;}
.fg label{display:block;font-size:.6rem;letter-spacing:.2em;text-transform:uppercase;color:var(--textsm);margin-bottom:7px;}
.fg input,.fg select{width:100%;background:rgba(255,255,255,.03);border:1px solid rgba(255,255,255,.08);color:var(--text);font-family:var(--sans);font-size:.88rem;font-weight:300;padding:11px 13px;outline:none;transition:border-color .2s;}
.fg input:focus,.fg select:focus{border-color:var(--warm);}
.fg select option{background:var(--bg2);}
.mod-acts{display:flex;gap:10px;margin-top:20px;justify-content:flex-end;}

/* ── TOAST ── */
#toasts{position:fixed;bottom:24px;left:50%;transform:translateX(-50%);z-index:8000;display:flex;flex-direction:column;align-items:center;gap:6px;}
.toast{background:var(--bg2);border:1px solid var(--wbdr);color:var(--text);font-size:.74rem;letter-spacing:.06em;padding:10px 20px;white-space:nowrap;animation:tin .3s var(--ease),tout .3s var(--ease) 2.7s forwards;}
.toast.ok{border-color:rgba(90,158,111,.4);color:#8adba4;}
.toast.err{border-color:rgba(185,64,64,.4);color:#e07070;}
@keyframes tin{from{opacity:0;transform:translateY(8px)}to{opacity:1;transform:none}}
@keyframes tout{from{opacity:1}to{opacity:0;transform:translateY(-6px)}}

/* ── STATS BAR (home) ── */
.stats{display:grid;grid-template-columns:repeat(3,1fr);gap:1px;background:rgba(255,255,255,.04);margin-bottom:40px;}
.stat{background:var(--bg);padding:22px;text-align:center;}
.stat-n{font-family:var(--serif);font-size:2rem;color:var(--warm);}
.stat-l{font-size:.62rem;letter-spacing:.14em;text-transform:uppercase;color:var(--textsm);margin-top:3px;}

/* ── SCROLLBAR ── */
::-webkit-scrollbar{width:4px;}
::-webkit-scrollbar-track{background:var(--bg);}
::-webkit-scrollbar-thumb{background:var(--wbdr);}
::-webkit-scrollbar-thumb:hover{background:var(--warm);}

/* ── MOBILE ── */
@media(max-width:768px){
  #nav{padding:0 16px;}
  .page{padding:32px 16px 64px;}
  .pgrid{columns:2 140px;}
  .albgrid{grid-template-columns:repeat(auto-fill,minmax(140px,1fr));}
  .stats{grid-template-columns:repeat(3,1fr);}
}
</style>
</head>
<body>

<!-- LOCK -->
<div id="lock">
  <div class="l-bg"></div>
  <div class="l-ornament"><span>Gallery</span></div>
  <div class="l-title">My <em>Archive</em></div>
  <div class="l-sub">Private Collection</div>
  <div class="l-field">
    <input type="password" id="li" placeholder="Enter password" autocomplete="off"/>
    <button class="l-eye" onclick="tEye()">👁</button>
  </div>
  <button class="l-btn" onclick="unlock()">Enter</button>
  <div class="l-err" id="lerr"></div>
</div>

<!-- NAV -->
<nav id="nav">
  <div class="n-brand">My Archive</div>
  <ul class="n-links" id="nlinks">
    <li><a class="active" onclick="go('p-home')">Home</a></li>
    <li><a onclick="go('p-all')">All Photos</a></li>
    <li><a onclick="go('p-albums')">Albums</a></li>
    <li><a onclick="go('p-favs')">Favourites</a></li>
  </ul>
</nav>

<!-- APP -->
<div id="app">

  <!-- HOME -->
  <div id="p-home" class="page active">
    <div class="ph">Your <em>Archive</em></div>
    <div class="phr"></div>
    <div class="stats">
      <div class="stat"><div class="stat-n" id="s-photos">0</div><div class="stat-l">Photos</div></div>
      <div class="stat"><div class="stat-n" id="s-albums">0</div><div class="stat-l">Albums</div></div>
      <div class="stat"><div class="stat-n" id="s-favs">0</div><div class="stat-l">Favourites</div></div>
    </div>
    <div id="home-recent-label" class="psub" style="display:none">Recently Added</div>
    <div class="pgrid" id="home-grid"></div>
    <div class="empty" id="home-empty">
      <div class="empty-icon">🎞</div>
      <div class="empty-title">Your archive is empty</div>
      <div class="empty-sub">Add photos to begin your collection</div>
    </div>
  </div>

  <!-- ALL PHOTOS -->
  <div id="p-all" class="page">
    <div style="display:flex;align-items:center;justify-content:space-between;flex-wrap:wrap;gap:12px;margin-bottom:4px;">
      <div class="ph">All <em>Photos</em></div>
      <div style="display:flex;gap:8px;align-items:center">
        <select id="filter-album" onchange="renderAll()" style="background:var(--bg2);border:1px solid var(--wbdr);color:var(--textmd);font-family:var(--sans);font-size:.72rem;padding:8px 12px;outline:none;cursor:pointer;">
          <option value="">All Albums</option>
        </select>
        <button class="btn-gold" onclick="document.getElementById('add-inp').click()">+ Add Photos</button>
        <input type="file" id="add-inp" accept="image/*,video/*" multiple style="display:none" onchange="addPhotos(this)"/>
      </div>
    </div>
    <div class="phr"></div>
    <div class="upload-zone" id="drop-zone" ondragover="dzOver(event)" ondragleave="dzLeave()" ondrop="dzDrop(event)">
      <input type="file" accept="image/*,video/*" multiple onchange="addPhotos(this)"/>
      <div class="uz-icon">🎞</div>
      <div class="uz-txt">Drag & drop photos or videos here</div>
      <div class="uz-sub">or click to browse · JPG, PNG, WEBP, MP4, MOV</div>
    </div>
    <div class="pgrid" id="all-grid"></div>
    <div class="empty" id="all-empty">
      <div class="empty-icon">📷</div>
      <div class="empty-title">No photos yet</div>
      <div class="empty-sub">Drop some photos above to start</div>
    </div>
  </div>

  <!-- ALBUMS -->
  <div id="p-albums" class="page">
    <div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:4px;">
      <div class="ph">My <em>Albums</em></div>
      <button class="btn-gold" onclick="openNewAlbum()">+ New Album</button>
    </div>
    <div class="phr"></div>
    <div class="albgrid" id="alb-grid"></div>
  </div>

  <!-- ALBUM VIEW -->
  <div id="p-album-view" class="page">
    <div style="display:flex;align-items:center;gap:16px;margin-bottom:4px;">
      <button class="btn-out" onclick="go('p-albums')" style="padding:8px 14px;font-size:.6rem">← Back</button>
      <div class="ph" id="av-title">Album</div>
    </div>
    <div class="phr"></div>
    <div style="display:flex;gap:8px;margin-bottom:20px;flex-wrap:wrap;">
      <button class="btn-gold" onclick="document.getElementById('av-inp').click()">+ Add Photos</button>
      <input type="file" id="av-inp" accept="image/*,video/*" multiple style="display:none" onchange="addToAlbum(this)"/>
      <button class="btn-out" onclick="startSlideshow('album')" style="display:flex;align-items:center;gap:6px">▶ Slideshow</button>
      <button class="btn-out" id="av-del-btn" onclick="deleteAlbum()" style="color:var(--red);border-color:rgba(185,64,64,.3)">Delete Album</button>
    </div>
    <div class="pgrid" id="av-grid"></div>
    <div class="empty" id="av-empty">
      <div class="empty-icon">🖼</div>
      <div class="empty-title">Album is empty</div>
      <div class="empty-sub">Add photos to this album</div>
    </div>
  </div>

  <!-- FAVOURITES -->
  <div id="p-favs" class="page">
    <div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:4px;">
      <div class="ph">My <em>Favourites</em></div>
      <button class="btn-out" onclick="startSlideshow('favs')">▶ Slideshow</button>
    </div>
    <div class="phr"></div>
    <div class="pgrid" id="fav-grid"></div>
    <div class="empty" id="fav-empty">
      <div class="empty-icon">♡</div>
      <div class="empty-title">No favourites yet</div>
      <div class="empty-sub">Tap the heart on any photo</div>
    </div>
  </div>

</div>

<!-- LIGHTBOX -->
<div id="lb">
  <button id="lbclose" onclick="cLB()">✕ Close</button>
  <button class="lb-arr" id="lb-prev" onclick="lbNav(-1)">‹</button>
  <img id="lbimg" src="" alt=""/>
  <video id="lbvid" controls style="display:none;max-width:92vw;max-height:88vh;"></video>
  <button class="lb-arr" id="lb-next" onclick="lbNav(1)">›</button>
  <div id="lb-counter"></div>
  <div id="lb-cap"></div>
</div>

<!-- SLIDESHOW -->
<div id="ss">
  <button id="ss-close" onclick="stopSS()">✕ Exit</button>
  <img id="ss-img" src="" alt=""/>
  <div id="ss-ctrl">
    <button class="ss-btn" onclick="ssNav(-1)">‹ Prev</button>
    <div id="ss-counter"></div>
    <button class="ss-btn" onclick="ssToggle()" id="ss-play">⏸ Pause</button>
    <button class="ss-btn" onclick="ssNav(1)">Next ›</button>
  </div>
</div>

<!-- NEW ALBUM MODAL -->
<div class="mod-bg" id="alb-mod">
  <div class="mod">
    <h3>New Album</h3>
    <div class="fg"><label>Album Name</label><input type="text" id="alb-name" placeholder="e.g. Summer 2025"/></div>
    <div class="mod-acts">
      <button class="btn-out" onclick="closeAlbMod()">Cancel</button>
      <button class="btn-gold" onclick="createAlbum()">Create</button>
    </div>
  </div>
</div>

<!-- ADD TO ALBUM MODAL (when adding photos) -->
<div class="mod-bg" id="atoa-mod">
  <div class="mod">
    <h3>Choose Album</h3>
    <div class="fg"><label>Album (optional)</label>
      <select id="atoa-sel"><option value="">No Album</option></select>
    </div>
    <div class="mod-acts">
      <button class="btn-out" onclick="closeAtoA(false)">Cancel</button>
      <button class="btn-gold" onclick="closeAtoA(true)">Add Photos</button>
    </div>
  </div>
</div>

<div id="toasts"></div>

<script>
// ══ DB via IndexedDB ══
// IndexedDB lets us store actual image blobs locally — no size limits like localStorage
const DB_NAME='myarchive', DB_VER=2;
let db=null, photos=[], albums=[];

function openDB(){
  return new Promise((res,rej)=>{
    const req=indexedDB.open(DB_NAME,DB_VER);
    req.onupgradeneeded=e=>{
      const d=e.target.result;
      if(!d.objectStoreNames.contains('photos')) d.createObjectStore('photos',{keyPath:'id'});
      if(!d.objectStoreNames.contains('albums')) d.createObjectStore('albums',{keyPath:'id'});
    };
    req.onsuccess=e=>{ db=e.target.result; res(db); };
    req.onerror=()=>rej();
  });
}

function dbGetAll(store){
  return new Promise(r=>{ const tx=db.transaction(store,'readonly'); const req=tx.objectStore(store).getAll(); req.onsuccess=()=>r(req.result); });
}
function dbPut(store,item){
  return new Promise(r=>{ const tx=db.transaction(store,'readwrite'); tx.objectStore(store).put(item); tx.oncomplete=()=>r(); });
}
function dbDel(store,id){
  return new Promise(r=>{ const tx=db.transaction(store,'readwrite'); tx.objectStore(store).delete(id); tx.oncomplete=()=>r(); });
}

// ══ LOCK ══
const PASS='myarchive2025'; // change this to your password!
document.getElementById('li').addEventListener('keydown',e=>{ if(e.key==='Enter') unlock(); });
function unlock(){
  if(document.getElementById('li').value===PASS){
    const el=document.getElementById('lock');
    el.style.transition='opacity .5s'; el.style.opacity='0';
    setTimeout(()=>{
      el.style.display='none';
      document.getElementById('nav').style.display='flex';
      document.getElementById('app').style.display='block';
      init();
    },520);
  } else {
    const i=document.getElementById('li'); i.classList.add('wrong');
    document.getElementById('lerr').textContent='Wrong password.';
    setTimeout(()=>{ i.classList.remove('wrong'); i.value=''; },500);
  }
}
function tEye(){ const i=document.getElementById('li'); i.type=i.type==='password'?'text':'password'; }

// ══ INIT ══
async function init(){
  await openDB();
  photos=await dbGetAll('photos');
  albums=await dbGetAll('albums');
  renderAll(); renderAlbums(); renderFavs(); renderHome(); updateStats();
  populateAlbumFilter();
}

// ══ NAV ══
let curAlbumId=null;
function go(p){
  document.querySelectorAll('.page').forEach(x=>x.classList.remove('active'));
  document.querySelectorAll('.n-links a').forEach(a=>a.classList.remove('active'));
  document.getElementById(p).classList.add('active');
  const map={'p-home':0,'p-all':1,'p-albums':2,'p-favs':3};
  const idx=map[p]; if(idx!==undefined) document.querySelectorAll('.n-links a')[idx]?.classList.add('active');
  window.scrollTo(0,0);
}

// ══ STATS ══
function updateStats(){
  document.getElementById('s-photos').textContent=photos.length;
  document.getElementById('s-albums').textContent=albums.length;
  document.getElementById('s-favs').textContent=photos.filter(p=>p.fav).length;
}

// ══ ADD PHOTOS ══
let pendingFiles=[], pendingCallback=null;
function addPhotos(inp){ if(!inp.files.length) return; pendingFiles=Array.from(inp.files); inp.value=''; openAtoA(null); }
function addToAlbum(inp){ if(!inp.files.length) return; pendingFiles=Array.from(inp.files); inp.value=''; openAtoA(curAlbumId); }

function openAtoA(preselect){
  const sel=document.getElementById('atoa-sel');
  sel.innerHTML='<option value="">No Album</option>';
  albums.forEach(a=>{ const o=document.createElement('option'); o.value=a.id; o.textContent=a.name; if(preselect===a.id) o.selected=true; sel.appendChild(o); });
  document.getElementById('atoa-mod').classList.add('open');
}
function closeAtoA(proceed){
  document.getElementById('atoa-mod').classList.remove('open');
  if(!proceed||!pendingFiles.length){ pendingFiles=[]; return; }
  const albumId=document.getElementById('atoa-sel').value||null;
  savePhotos(pendingFiles, albumId);
  pendingFiles=[];
}

async function savePhotos(files, albumId){
  let count=0;
  for(const file of files){
    const isVideo=file.type.startsWith('video/');
    const url=await new Promise(r=>{ const rd=new FileReader(); rd.onload=e=>r(e.target.result); rd.readAsDataURL(file); });
    const photo={id:Date.now()+'_'+Math.random().toString(36).slice(2), url, name:file.name, albumId:albumId||null, date:new Date().toLocaleDateString('en-GB',{day:'2-digit',month:'short',year:'numeric'}), fav:false, isVideo};
    await dbPut('photos',photo); photos.unshift(photo); count++;
  }
  if(albumId){ const alb=albums.find(a=>a.id===albumId); if(alb&&!alb.cover){ alb.cover=photos.find(p=>p.albumId===albumId)?.url; await dbPut('albums',alb); } }
  renderAll(); renderHome(); renderFavs(); updateStats(); populateAlbumFilter();
  if(curAlbumId) renderAlbumView(curAlbumId);
  toast(`${count} file${count>1?'s':''} added ✦`,'ok');
}

// ══ RENDER GRID ══
function makeCard(photo, listRef){
  const d=document.createElement('div'); d.className='gitem';
  if(photo.isVideo){
    // video card — show video element with muted preview
    const vid=document.createElement('video');
    vid.src=photo.url; vid.muted=true; vid.loop=true; vid.playsInline=true;
    vid.style.cssText='width:100%;display:block;transition:transform .5s var(--ease);object-fit:cover;max-height:280px;';
    d.addEventListener('mouseenter',()=>vid.play());
    d.addEventListener('mouseleave',()=>{ vid.pause(); vid.currentTime=0; });
    // play icon badge
    const badge=document.createElement('div');
    badge.style.cssText='position:absolute;top:8px;left:8px;background:rgba(0,0,0,.55);color:#fff;font-size:.6rem;letter-spacing:.1em;padding:3px 8px;pointer-events:none;';
    badge.textContent='▶ VIDEO';
    d.appendChild(vid); d.appendChild(badge);
  } else {
    const img=document.createElement('img'); img.src=photo.url; img.loading='lazy'; d.appendChild(img);
  }
  const ov=document.createElement('div'); ov.className='gitem-ov';
  ov.innerHTML=`<div class="gitem-date">${photo.date||''}</div>${photo.albumId?`<div class="gitem-album">${albums.find(a=>a.id===photo.albumId)?.name||''}</div>`:''}`;
  const favBtn=document.createElement('button'); favBtn.className='gitem-fav'+(photo.fav?' on':''); favBtn.textContent=photo.fav?'♥':'♡';
  favBtn.onclick=async(ev)=>{ ev.stopPropagation(); photo.fav=!photo.fav; await dbPut('photos',photo); renderAll(); renderFavs(); renderHome(); updateStats(); if(curAlbumId) renderAlbumView(curAlbumId); };
  const delBtn=document.createElement('button'); delBtn.className='gitem-del'; delBtn.textContent='✕ Remove';
  delBtn.onclick=async(ev)=>{ ev.stopPropagation(); if(!confirm('Delete this?')) return; await dbDel('photos',photo.id); photos=photos.filter(p=>p.id!==photo.id); renderAll(); renderFavs(); renderHome(); updateStats(); if(curAlbumId) renderAlbumView(curAlbumId); toast('Deleted'); };
  d.appendChild(ov); d.appendChild(favBtn); d.appendChild(delBtn);
  d.addEventListener('click', ()=>{ const idx=listRef.indexOf(photo); oLB(photo.url,photo.date,listRef.map(p=>({url:p.url,cap:p.date,isVideo:p.isVideo})),idx); });
  return d;
}

function renderHome(){
  const grid=document.getElementById('home-grid'); const empty=document.getElementById('home-empty');
  const label=document.getElementById('home-recent-label');
  grid.innerHTML='';
  if(!photos.length){ empty.style.display='block'; label.style.display='none'; return; }
  empty.style.display='none'; label.style.display='block';
  photos.slice(0,12).forEach(p=>grid.appendChild(makeCard(p,photos)));
}

function renderAll(){
  const grid=document.getElementById('all-grid'); const empty=document.getElementById('all-empty');
  const fAlbum=document.getElementById('filter-album').value;
  grid.innerHTML='';
  const filtered=fAlbum?photos.filter(p=>p.albumId===fAlbum):photos;
  if(!filtered.length){ empty.style.display='block'; return; }
  empty.style.display='none';
  filtered.forEach(p=>grid.appendChild(makeCard(p,filtered)));
}

function renderFavs(){
  const grid=document.getElementById('fav-grid'); const empty=document.getElementById('fav-empty');
  grid.innerHTML='';
  const favs=photos.filter(p=>p.fav);
  if(!favs.length){ empty.style.display='block'; return; }
  empty.style.display='none';
  favs.forEach(p=>grid.appendChild(makeCard(p,favs)));
}

function renderAlbumView(id){
  curAlbumId=id;
  const alb=albums.find(a=>a.id===id); if(!alb) return;
  document.getElementById('av-title').innerHTML=`<em>${alb.name}</em>`;
  document.getElementById('av-inp').dataset.album=id;
  const grid=document.getElementById('av-grid'); const empty=document.getElementById('av-empty');
  grid.innerHTML='';
  const albPhotos=photos.filter(p=>p.albumId===id);
  if(!albPhotos.length){ empty.style.display='block'; return; }
  empty.style.display='none';
  albPhotos.forEach(p=>grid.appendChild(makeCard(p,albPhotos)));
  go('p-album-view');
}

// ══ ALBUMS ══
function renderAlbums(){
  const grid=document.getElementById('alb-grid'); grid.innerHTML='';
  albums.forEach(alb=>{
    const d=document.createElement('div'); d.className='albcard';
    const cover=photos.find(p=>p.albumId===alb.id);
    const count=photos.filter(p=>p.albumId===alb.id).length;
    if(cover){ const img=document.createElement('img'); img.src=cover.url; img.loading='lazy'; d.appendChild(img); }
    else{ const emp=document.createElement('div'); emp.className='albcard-empty'; emp.textContent='🗂'; d.appendChild(emp); }
    d.innerHTML+=`<div class="albcard-ov"><div class="albcard-name">${alb.name}</div><div class="albcard-count">${count} photo${count!==1?'s':''}</div></div>`;
    d.addEventListener('click',()=>renderAlbumView(alb.id));
    grid.appendChild(d);
  });
  // new album button
  const nb=document.createElement('button'); nb.className='alb-new';
  nb.innerHTML='<span>+</span><div style="font-size:.68rem;letter-spacing:.14em;text-transform:uppercase">New Album</div>';
  nb.onclick=openNewAlbum;
  grid.appendChild(nb);
  updateStats();
}

function openNewAlbum(){ document.getElementById('alb-name').value=''; document.getElementById('alb-mod').classList.add('open'); setTimeout(()=>document.getElementById('alb-name').focus(),100); }
function closeAlbMod(){ document.getElementById('alb-mod').classList.remove('open'); }
document.getElementById('alb-name').addEventListener('keydown',e=>{ if(e.key==='Enter') createAlbum(); });
async function createAlbum(){
  const name=document.getElementById('alb-name').value.trim(); if(!name) return;
  const alb={id:Date.now()+'',name,cover:null};
  await dbPut('albums',alb); albums.push(alb);
  closeAlbMod(); renderAlbums(); populateAlbumFilter(); toast(`Album "${name}" created ✦`,'ok');
}

async function deleteAlbum(){
  if(!confirm('Delete album? Photos inside will remain in All Photos.')) return;
  // unlink photos from album
  const albumPhotos=photos.filter(p=>p.albumId===curAlbumId);
  for(const p of albumPhotos){ p.albumId=null; await dbPut('photos',p); }
  await dbDel('albums',curAlbumId);
  albums=albums.filter(a=>a.id!==curAlbumId);
  curAlbumId=null; renderAlbums(); renderAll(); populateAlbumFilter(); go('p-albums'); toast('Album deleted');
}

function populateAlbumFilter(){
  const sel=document.getElementById('filter-album');
  const cur=sel.value;
  sel.innerHTML='<option value="">All Albums</option>';
  albums.forEach(a=>{ const o=document.createElement('option'); o.value=a.id; o.textContent=a.name; if(cur===a.id) o.selected=true; sel.appendChild(o); });
}

// ══ DRAG & DROP ══
function dzOver(ev){ ev.preventDefault(); document.getElementById('drop-zone').classList.add('drag-over'); }
function dzLeave(){ document.getElementById('drop-zone').classList.remove('drag-over'); }
function dzDrop(ev){ ev.preventDefault(); dzLeave(); const files=Array.from(ev.dataTransfer.files).filter(f=>f.type.startsWith('image/')||f.type.startsWith('video/')); if(!files.length){ toast('Only image or video files!','err'); return; } pendingFiles=files; openAtoA(null); }

// ══ LIGHTBOX ══
let lbItems=[], lbIdx=0;
function oLB(url,cap,items,idx){ lbItems=items||[{url,cap}]; lbIdx=idx??0; lbShow(); document.getElementById('lb').classList.add('open'); document.body.style.overflow='hidden'; }
function lbShow(){
  const it=lbItems[lbIdx];
  const img=document.getElementById('lbimg');
  const vid=document.getElementById('lbvid');
  if(it.isVideo){
    img.style.display='none';
    vid.style.display='block'; vid.src=it.url; vid.play();
  } else {
    vid.style.display='none'; vid.pause(); vid.src='';
    img.style.display='block'; img.src=it.url;
  }
  document.getElementById('lb-cap').textContent=it.cap||'';
  document.getElementById('lb-counter').textContent=lbItems.length>1?`${lbIdx+1} / ${lbItems.length}`:'';
  document.getElementById('lb-prev').style.opacity=lbItems.length>1?'1':'0';
  document.getElementById('lb-next').style.opacity=lbItems.length>1?'1':'0';
}
function lbNav(d){ lbIdx=(lbIdx+d+lbItems.length)%lbItems.length; lbShow(); }
function cLB(){
  document.getElementById('lb').classList.remove('open');
  document.getElementById('lbimg').src='';
  const vid=document.getElementById('lbvid'); vid.pause(); vid.src='';
  document.getElementById('lbvid').style.display='none';
  document.getElementById('lbimg').style.display='block';
  document.body.style.overflow='';
}
document.getElementById('lb').addEventListener('click',ev=>{ if(ev.target===document.getElementById('lb')) cLB(); });
document.addEventListener('keydown',ev=>{
  if(document.getElementById('lb').classList.contains('open')){ if(ev.key==='ArrowLeft') lbNav(-1); else if(ev.key==='ArrowRight') lbNav(1); else if(ev.key==='Escape') cLB(); }
  if(document.getElementById('ss').classList.contains('open')){ if(ev.key==='Escape') stopSS(); }
});
let lbSwX=0;
document.getElementById('lb').addEventListener('touchstart',e=>{ lbSwX=e.touches[0].clientX; },{passive:true});
document.getElementById('lb').addEventListener('touchend',e=>{ const d=lbSwX-e.changedTouches[0].clientX; if(Math.abs(d)>50) lbNav(d>0?1:-1); },{passive:true});

// ══ SLIDESHOW ══
let ssItems=[], ssIdx=0, ssTimer=null, ssPlaying=true;
function startSlideshow(mode){
  let list=[];
  if(mode==='favs') list=photos.filter(p=>p.fav);
  else if(mode==='album') list=photos.filter(p=>p.albumId===curAlbumId);
  else list=[...photos];
  if(!list.length){ toast('No photos to show!','err'); return; }
  ssItems=list; ssIdx=0; ssPlaying=true;
  document.getElementById('ss').classList.add('open');
  document.body.style.overflow='hidden';
  ssShow(); ssTimer=setInterval(()=>{ if(ssPlaying) ssNav(1); },4000);
}
function ssShow(){
  document.getElementById('ss-img').src=ssItems[ssIdx].url;
  document.getElementById('ss-counter').textContent=`${ssIdx+1} / ${ssItems.length}`;
}
function ssNav(d){ ssIdx=(ssIdx+d+ssItems.length)%ssItems.length; ssShow(); }
function ssToggle(){ ssPlaying=!ssPlaying; document.getElementById('ss-play').textContent=ssPlaying?'⏸ Pause':'▶ Play'; }
function stopSS(){ clearInterval(ssTimer); document.getElementById('ss').classList.remove('open'); document.body.style.overflow=''; }

// ══ TOAST ══
function toast(msg,type=''){ const t=document.createElement('div'); t.className='toast '+type; t.textContent=msg; document.getElementById('toasts').appendChild(t); setTimeout(()=>t.remove(),3200); }
</script>
</body>
</html>
