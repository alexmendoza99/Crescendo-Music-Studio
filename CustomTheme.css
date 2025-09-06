/* ===== Crio Header & Menu (stable, centered) ===== */

/* ---------- Header container ---------- */
#header, .site-header, #masthead{
  background:#fff !important;
  box-shadow:0 2px 10px rgba(0,0,0,.06);
  border-radius:0;
}


/* ---------- TRUE centered 3-column layout using Grid ---------- */
#masthead .container,
#header   .container{ overflow:visible; }

#masthead .container > .row{
  display:grid !important;
  grid-template-columns: 1fr max-content 1fr; /* left | CENTER | right */
  align-items:center !important;
  justify-content:stretch;
  gap:16px;
  overflow:visible;
}

/* Make each column a flex box so we can align inside the cell */
#masthead .container > .row > [class*="col-"]{
  display:flex !important;
  align-items:center !important;
  min-width:0;
  padding-left:0 !important;
  padding-right:0 !important;
}

/* Left: logo (tight) */
#masthead .container > .row > [class*="col-"]:first-child{
  grid-column:1;
  justify-content:flex-start;
  gap:12px;
  flex:0 0 auto;
}

/* Middle: title + menu (stack) — center & size to content */
#masthead .container > .row > [class*="col-"]:nth-child(2),
#masthead .container > .row > .menu-center{
  grid-column:2;
  justify-self:center;
  display:flex !important;
  flex-direction:column;
  justify-content:center !important;
  align-items:center !important;
  text-align:center;
  width:max-content !important;         /* shrink to content for true center */
  max-width:calc(100vw - 320px);
  min-width:0;
}

/* Right: socials (tight) */
#masthead .container > .row > [class*="col-"]:last-child{
  grid-column:3;
  justify-content:flex-end !important;
  gap:12px;
  flex:0 0 auto;
}

/* ---------- Logo size ---------- */
#masthead .navbar-brand,
#masthead .site-branding{ margin:0 !important; padding:0 !important; }
#masthead .navbar-brand img,
#masthead .custom-logo,
.site-branding .custom-logo{
  max-height:48px !important;
  width:auto !important;
  height:auto;
}

/* ---------- Title (one line, never clipped) ---------- */
#masthead .site-title.header-site-title,
.bgtfw-menu-wrap .site-title{
  margin:0 0 6px 0 !important;
  padding:0 !important;
  width:auto !important;
  max-width:80vw !important;
  text-align:center !important;
  font-family:"Fira Sans", Helvetica, Arial, sans-serif !important;
  font-weight:500 !important;
  font-size:22px !important;
  line-height:1.2 !important;
  letter-spacing:.02em !important;
  text-transform:uppercase !important;
  color:#111 !important;
  white-space:nowrap !important;
  overflow:visible !important;
  text-overflow:clip !important;
}
#masthead .site-title a{ color:inherit !important; text-decoration:none !important; }

/* ---------- Menu base ---------- */
ul#main-menu{
  background:transparent !important;
  border:0 !important;
  box-shadow:none !important;
  width:auto !important;
  max-width:none !important;
  margin:0 auto !important;
  padding:0 !important;

  display:flex !important;              /* will be inline-flex in center override */
  flex-direction:row !important;
  flex-wrap:nowrap !important;
  justify-content:center !important;
  align-items:center !important;
  gap:28px !important;
  list-style:none !important;
}

/* Neutralize color/border utility classes */
ul#main-menu[class*="background-color"],
ul#main-menu[class*="border-color"]{
  background:transparent !important;
  border:0 !important;
}

/* Items */
ul#main-menu > li{
  display:inline-flex !important;
  align-items:center !important;
  margin:0 !important;
  background:transparent !important;
  border:0 !important;
}

/* Links: rounded pill + hover underline */
ul#main-menu > li > a{
  position:relative;
  background:transparent !important;
  border:0 !important;
  color:#222 !important;
  font:400 15px/1.2 Helvetica, Arial, sans-serif;
  letter-spacing:.2px;
  padding:8px 14px;
  border-radius:10px;
  text-decoration:none !important;
  display:inline-block;
  overflow:hidden;                      /* keeps corners round on hover */
  transition:background-color .18s ease, color .18s ease;
}

/* Kill Crio/hover.css sweep layers that cause sharp corners */
ul#main-menu > li::before,
ul#main-menu > li::after,
ul#main-menu > li.hvr-sweep-to-right::before,
ul#main-menu > li.hvr-sweep-to-right::after,
ul#main-menu > li > a.hvr-sweep-to-right::before,
ul#main-menu > li > a[class*="hvr-"]::before{
  display:none !important;
}

/* Underline animation (hover only) */
ul#main-menu > li > a::after{
  content:"";
  position:absolute;
  left:10px; right:10px; bottom:6px;
  height:2px;
  background: currentColor;
  transform: scaleX(0);
  transform-origin: left;
  transition: transform .2s ease;
}
ul#main-menu > li > a:hover::after{ transform: scaleX(1); }

/* Hover pill */
ul#main-menu > li > a:hover{
  background:#222 !important;
  color:#fff !important;
  border-radius:10px !important;
}

/* Active pill (no underline, not bold) */
ul#main-menu > li.active > a,
ul#main-menu > li.current-menu-item > a,
ul#main-menu > li.current_page_item > a,
ul#main-menu > li.current_page_parent > a,
ul#main-menu > li.current-page-ancestor > a,
ul#main-menu > li.selected > a{
  background:#222 !important;
  color:#fff !important;
  font-weight:400 !important;
  border-radius:10px !important;
  box-shadow:none !important;
}
ul#main-menu > li.active > a::after,
ul#main-menu > li.current-menu-item > a::after,
ul#main-menu > li.current_page_item > a::after,
ul#main-menu > li.current_page_parent > a::after,
ul#main-menu > li.current-page-ancestor > a::after,
ul#main-menu > li.selected > a::after{ content:none !important; }

/* ---------- Header content wrapper (generic) ---------- */
.bgtfw-menu-wrap{
  display:flex !important;
  align-items:center !important;
  justify-content:space-between !important;   /* generic default */
  gap:20px;
  padding-top:8px;
  padding-bottom:8px;
}

/* ---------- CENTER OVERRIDES (placed AFTER generic so they win) ---------- */
/* Keep title and menu on the same vertical center line */
#masthead .container > .row > [class*="col-"]:nth-child(2) .site-title{
  align-self:center !important;
}

/* Center the wrapper and UL precisely under the title */
#masthead .container > .row > [class*="col-"]:nth-child(2) .bgtfw-menu-wrap,
#masthead .container > .row > [class*="col-"]:nth-child(2) #main-wrap{
  justify-content:center !important;
  gap:0 !important;
}

#masthead .container > .row > [class*="col-"]:nth-child(2) ul#main-menu{
  display:inline-flex !important;       /* shrink to content */
  width:auto !important;
  margin-left:auto !important;
  margin-right:auto !important;
  padding-left:0 !important;
  padding-right:0 !important;
}

/* Hide hamburger on desktop so it can't offset the UL */
@media (min-width: 992px){
  #masthead .container > .row > [class*="col-"]:nth-child(2) #main-menu-btn,
  #masthead .container > .row > [class*="col-"]:nth-child(2) #main-menu-state{
    display:none !important;
  }
}


/* ---------- Social icons (STRICTLY the header's social area) ---------- */
#masthead #social-wrap a{
  display:inline-flex !important;
  align-items:center;
  justify-content:center;
  width:36px;
  height:36px;
  padding:0 !important;
  border:0 !important;
  border-radius:50%;
  background:#000 !important;   /* black chip */
  color:#fff !important;        /* white glyph */
  text-decoration:none !important;
  transition:background-color .18s ease, color .18s ease;
}
#masthead #social-wrap a:hover{
  background:#222 !important;
  color:#fff !important;
}
#masthead #social-wrap a i,
#masthead #social-wrap a i:before{
  color:#fff !important;
  line-height:1 !important;
  font-size:16px;               /* adjust if you want larger/smaller */
}
/* Remove hover.css sweep only for these icons */
#masthead #social-wrap a.hvr-sweep-to-right::before,
#masthead #social-wrap a[class*="hvr-"]::before{
  display:none !important;
}


/* ---------- Dropdowns ---------- */
ul#main-menu .dropdown-menu{
  position:absolute !important;
  top:100%; left:0;
  border-radius:10px;
  border:1px solid rgba(0,0,0,.06);
  box-shadow:0 12px 30px rgba(0,0,0,.12);
  padding:8px;
}

/* ---------- Mobile ---------- */
@media (max-width:992px){
  ul#main-menu{ flex-wrap:wrap !important; gap:16px 22px !important; }
  .bgtfw-menu-wrap{ flex-direction:column !important; gap:10px; }
  #masthead .site-title.header-site-title{ font-size:18px !important; }
  #masthead .navbar-brand img{ max-height:40px !important; }
}

/* ---------- Reduced motion ---------- */
@media (prefers-reduced-motion:reduce){
  ul#main-menu > li > a,
  #masthead #social-wrap a{ transition:none !important; }
  ul#main-menu > li > a::after{ transition:none !important; }
}

/* Hide the big pale overlay title/tagline in the hero */
.custom-header-media .site-title,
.custom-header-media .site-description{ display:none !important; }

/* Generic site title style (safety) */
#masthead .site-title, #header .site-title, .site-branding .site-title{
  font-family:"Fira Sans", Helvetica, Arial, sans-serif !important;
  font-weight:500 !important;
  color:#111 !important;
}
#masthead .site-title a, #header .site-title a, .site-branding .site-title a{
  color:inherit !important; text-decoration:none !important;
}
