---
pageSize: A4
---

<style>

/* DEFAULT GMBINDER PHB CSS */
.phb .cover-image{position:absolute;top:-5mm;left:-5mm;width:824px;width:220mm;hieght:307mm;}
.phb .cover-diamond{background-image:url('https://www.gmbinder.com/assets/img/DiamondDD.png');background-size:400px;background-repeat:no-repeat;position:absolute;left:210px;top:115px;width:400px;height:12px}
.phb .cover-splotch{background-image:url('https://www.gmbinder.com/assets/img/UNR8ilF.png');background-size:350px;position:absolute;left:0;bottom:180px;width:345px;height:56px}
.phb .cover-footer{position:absolute;font-family:ScalySans;font-size:20px;color:white;bottom:50px;right:55px;width:700px;text-shadow:1px 1px 2px #000000,-1px 1px 2px #000000,1px -1px 2px #000000,-1px -1px 2px #000000;filter:opacity(100%);text-align:center}
.phb .back-cover-image{position:absolute;height:1066px;left:0;top:0;width:475px;background-image:url('https://www.gmbinder.com/assets/img/backcover-bg.png');background-size:475px 1066px;z-index:-1}
.phb .back-cover-diamond{background-image:url('https://www.gmbinder.com/assets/img/DiamondDD.png');background-size:280px;background-repeat:no-repeat;position:absolute;left:90px;top:110px;width:280px;height:8px}
.phb .back-cover-logo{background-image:url('https://www.gmbinder.com/assets/img/logo-stacked-light.png');background-size:120px;position:absolute;left:165px;bottom:95px;width:120px;height:74px}
.phb .back-cover-logo-link{text-align:center;font-family:sans-serif;position:absolute;bottom:30px;left:145px}
.phb .back-cover-logo-link p{font-family:ScalySans,sans-serif;line-height:1.6em !important;font-size:16px;padding-bottom:25px}
.phb .back-cover-logo-link a{color:#fff;text-decoration:none}
.phb .back-cover-header{color:#ff2a1a;font-family:NodestoCaps,sans-serif;font-size:64px;text-align:center;text-shadow:1px 1px 2px #000000,-1px 1px 2px #000000,1px -1px 2px #000000,-1px -1px 2px #000000}
.phb .back-cover-header p{text-indent:0;padding-bottom:15px}
.phb .back-cover-header p+p{text-indent:0}
.phb .back-cover-text{color:#fff;font-family:sans-serif}
.phb .back-cover-text a{color:#AC8F66}
.phb .back-cover-text p{font-family:ScalySans,sans-serif;line-height:1.6em !important;font-size:16px;padding-bottom:25px}
.phb .back-cover-text p+p{text-indent:0}
.phb .back-cover-close{color:#fff;text-align:center;font-family:sans-serif}
.phb .back-cover-close a{color:#AC8F66}
.phb .back-cover-close p{font-family:ScalySans,sans-serif;line-height:1.6em !important;font-size:16px;padding-bottom:25px}
.phb .back-cover-close p+p{text-indent:0}
.phb .back-cover-right{padding-left:60px}
.phb .image-top{position:absolute;left:0;top:0;width:824px}
.phb .image-right{position:absolute;right:0;top:0;height:1066px}
.phb .image-bottom{position:absolute;left:0;bottom:0;width:824px}
.phb .image-left{position:absolute;left:0;top:0;height:1066px}
.phb .image-top-left{position:absolute;left:0;top:0}
.phb .image-top-right{position:absolute;right:0;top:0}
.phb .image-bottom-right{position:absolute;right:0;bottom:0}
.phb .image-bottom-left{position:absolute;left:0;bottom:0}
.phb .partpage{text-align:center;position:absolute;top:0;left:0;right:0;background-image:url('https://www.gmbinder.com/assets/img/pph.png');background-size:cover;background-position:center;height:217px}
.phb .partpage h1{font-family:NodestoCaps;font-size:64pt;font-weight:normal;letter-spacing:-2px;margin:12px 0 -17.5px 0}
.phb .partpage h5{font-family:ScalySans;font-size:13pt;color:#58180D}
.phb .partpage-dmg{text-align:center;position:absolute;top:0;left:0;right:0;background-image:url('https://www.gmbinder.com/assets/img/pph-dmg.png');background-size:cover;background-position:center;height:206px}
.phb .partpage-dmg h1{font-family:NodestoCaps;font-size:64pt;font-weight:normal;letter-spacing:-2px;margin:12px 0 -12.5px 0}
.phb .partpage-dmg h5{font-family:ScalySans;font-size:13pt;color:black}
.phb .back-cover-right-image{position:absolute;height:1066px;right:0;top:0;z-index:-2}
.phb .back-cover-right-text{padding-left:60px;color:white;z-index:-1}
@font-face{font-family:BookSanity;src:url('../../css/fonts/Bookinsanity.otf') format('opentype');font-weight:normal;font-style:normal}
@font-face{font-family:BookSanity;src:url('../../css/fonts/Bookinsanity%20Bold.otf') format('opentype');font-weight:bold;font-style:normal}
@font-face{font-family:BookSanity;src:url('../../css/fonts/Bookinsanity%20Italic.otf') format('opentype');font-weight:normal;font-style:italic}
@font-face{font-family:BookSanity;src:url('../../css/fonts/Bookinsanity%20Bold Italic.otf') format('opentype');font-weight:bold;font-style:italic}
@font-face{font-family:NodestoCaps;src:url('../../css/fonts/Nodesto%20Caps%20Condensed.otf') format('opentype');font-weight:normal;font-style:normal}
@font-face{font-family:NodestoCaps;src:url('../../css/fonts/Nodesto%20Caps%20Condensed%20Bold.otf') format('opentype');font-weight:bold;font-style:normal}
@font-face{font-family:NodestoCaps;src:url('../../css/fonts/Nodesto%20Caps%20Condensed%20Italic.otf') format('opentype');font-weight:normal;font-style:italic}
@font-face{font-family:NodestoCaps;src:url('../../css/fonts/Nodesto%20Caps%20Condensed%20Bold%20Italic.otf') format('opentype');font-weight:bold;font-style:italic}
@font-face{font-family:ScalySans;src:url('../../css/fonts/Scaly%20Sans.otf') format('opentype');font-weight:normal;font-style:normal}
@font-face{font-family:ScalySans;src:url('../../css/fonts/Scaly%20Sans%20Bold.otf') format('opentype');font-weight:bold;font-style:normal}
@font-face{font-family:ScalySans;src:url('../../css/fonts/Scaly%20Sans%20Italic.otf') format('opentype');font-weight:normal;font-style:italic}
@font-face{font-family:ScalySans;src:url('../../css/fonts/Scaly%20Sans%20Bold%20Italic.otf') format('opentype');font-weight:bold;font-style:italic}
@font-face{font-family:ScalySansSmallCaps;src:url('../../css/fonts/ScalySansCaps-fixed.otf') format('opentype');font-weight:normal;font-style:normal}
@font-face{font-family:ScalySansSmallCaps;src:url('../../css/fonts/ScalySansCaps-Bold-fixed.otf') format('opentype');font-weight:bold;font-style:normal}
@font-face{font-family:ScalySansSmallCaps;src:url('../../css/fonts/ScalySansCaps-Italic-fixed.otf') format('opentype');font-weight:normal;font-style:italic}
@font-face{font-family:ScalySansSmallCaps;src:url('../../css/fonts/ScalySansCaps-BoldItalic-fixed.otf') format('opentype');font-weight:bold;font-style:italic}
@font-face{font-family:Solberry;src:url('../../css/fonts/Solbera%20Imitation.otf') format('opentype');font-weight:normal;font-style:normal}
@font-face{font-family:MrJeeves;src:url('../../css/fonts/Mr%20Eaves%20Small%20Caps.otf') format('opentype');font-weight:normal;font-style:normal}
@font-face{font-family:Genesys;src:url('../../css/fonts/Genesys.ttf') format('truetype');font-weight:normal;font-style:normal}
@font-face{font-family:Genesys1;src:url('../../css/fonts/EotE_Symbol-Regular_v1.otf') format('opentype');font-weight:normal;font-style:normal}
@font-face{font-family:Bebas Neue;src:url('../../css/fonts/BebasNeue%20Regular.otf') format('opentype');font-weight:normal;font-style:normal}
@font-face{font-family:Bebas Neue;src:url('../../css/fonts/BebasNeue%20Bold.otf') format('opentype');font-weight:bold;font-style:normal}

/* IMPORTS */

@import url('https://fonts.googleapis.com/css?family=Crimson+Text:400,600,600i,700');

/* MY DOC CHANGES */
.phb{
    height: 297mm;
    width: 210mm;
    column-gap: 6mm;
}

@media print { 
    .phb { 
      height: 297mm;
      width: 210mm;
    }
}

/* Main Background */

.phb:nth-child(odd) {
    background-image: url('../imgs/EotER.jpg');
    background-size: cover;
    background-size: 215mm 305mm;
    background-position:center;
    padding:12mm 22mm;
}
.phb:nth-child(even) {
    background-image: url('../imgs/EotEL.jpg');
    background-size: cover;
    background-size: 215mm 305mm;
    background-position:center;
    padding:12mm 22mm;
}

.phb{
    
}

/* Fonts */

.phb {
    font-family: 'Crimson Text', serif;
}

.phb h1, .phb h2, .phb h3, .phb h4, .phb h5, .phb h6 { 
    letter-spacing: 0.6px;
    font-family: 'Bebas Neue';
}

.phb h1{
    color: #1ABEEF;
    font-weight:400;
    font-variant: uppercase;
    font-size:42pt;
    margin-bottom:30px;
}

/* Makes the bigger 'first letter' in paragraphs under H1 and H2*/
.phb h1 + p:first-letter, .phb h2 + p:first-letter  {
    font-family: 'Crimson Text';
    color: #326DA1;
    font-size:32pt;    
    line-height:95%;
    margin-bottom:-9px;
    margin-right:2px;
    margin-top:-5px;
    float:left;
}

.phb h2 {
    color: #1ABEEF;
    font-variant: small-caps;
    display:table;
    font-size:32pt;
    font-weight:300;
    column-span:all;
}

/* create the offset underline under h2s */
.phb h2:after {
    content:'';
    border-bottom: 2px solid #CCCCCC;
    display: table;
    width:100%;
    margin-top:-5px;
    margin-left:20px;
}

.phb h3 {
    color: #1ABEEF;
    font-variant: small-caps;
    font-size: 18pt;
    font-weight:1;
    border:none;
}

.phb h4 {
    color: #ed9629;
    font-variant: small-caps;
    font-size: 16pt;
    text-align:center;
}

.phb h5 {
    color: #326DA1;
    font-weight: 1;
    font-variant: small-caps;
    font-size: 16pt;
}

.phb h6 {
    color: #ea702b;
    font-variant: small-caps;
    font-size: 16pt;
    display: table;
    border-bottom: 1px solid #ea702b;
}

.phb p { 
    font-size: 15px; 
    letter-spacing: -0.4px;
    line-height:1.15em;
    text-indent:0px !important;
    font-weight:400;
    padding-bottom:1px;
    column-fill:balance;
  }
  
.phb p + p {
    margin-top:0px;  
  }

.phb wide {clear:both;}
.phb ul {list-style: none;}
.phb ul li::before {
    content: '•'; 
    color: #F69337;
    display: inline-block;
    width: 1em;
    margin-left: -1em;
  }

/* Tables */
.phb td {
    font-family: 'Crimson Text', serif;
    font-size:7pt;
    font-weight:400;
    text-align:left;
}
.phb td, th {border: 1px solid gray;}
.phb table {overflow:auto;}
.phb table tr:nth-child(odd) td {background-color: #E0F4FC;}
.phb table thead th {
    color: white; 
    background-color: #F69337; 
    padding-top: 0.2em;
    padding-left: 0.6em;
    text-transform: uppercase;
}
.phb table tbody tr td {  padding: 0.4em;}
.phb table thead {display: table-row-group; }
.phb table .subheader td {
    color:white;
    text-transform:uppercase;
    padding-bottom:2px;
    background-color: #2D4864 !important;
    font-size:8pt;
    font-weight:bold;
    }

/* Genesys Notes */

.phb .note
{
    position:relative;
    color: white;
    background-color: #2D4864;
    border-radius: 0px 0px 30px 0px;
    padding: 10px 20px;  
    font-family: 'Crimson Text';
    letter-spacing: 0.5px;
    font-size:12ptx;
    font-weight:600
    }    

.phb .note:before {
    position:absolute;
    content:' ';
    border-style:solid;
    border-width:1px;
    -moz-border-image: -moz-linear-gradient(-45deg, rgba(219,219,219,.7) 0%, rgba(219,219,219,0) 50%, rgba(219,219,219,0) 100%);
    -webkit-border-image: -webkit-linear-gradient(-45deg, rgba(219,219,219,.7) 0%,rgba(219,219,219,0) 50%,rgba(219,219,219,0) 100%);
    border-image: linear-gradient(135deg, rgba(219,219,219,.7) 0%,rgba(219,219,219,0) 50%,rgba(219,219,219,0) 100%); 
    left:4px;
    top:4px;
    right:4px;
    bottom:4px;
    border-image-slice:1;
}

.phb .note h5 {color:white;}
.phb .note td {color:black;}
.phb .note table tr:nth-child(even) td { background-color: #ffffff;}
  
  
/* Example Block */

.phb .example
{
    position:relative;
    color: black;
    background: rgba(204, 203, 199, 0.4);
    border-radius: 0px 0px 30px 0px;
    padding: 14px 20px;
}

/* Read-aloud */

.phb .read {
    display:block;
    font-family: 'Crimson Text';
    font-size:10pt;
    font-style: italic;
    color: rgb(230,0,0);
    border: 1px dotted rgb(230,0,0);
    border-radius:30px;
    padding:15px;
    position:relative;
}

.phb .read:before {
    content:'';
    position:absolute;
    display:block;
    border: 1px dotted rgb(230,0,0);
    border-radius:30px;
    left:2px;
    top:2px;
    right:2px;
    bottom:2px;
    }

/* Footer */
.phb .pageNumber { color: #000000}
.phb .footnote { color: #000000 }
.phb:nth-child(odd) .pageNumber { color: black;
  right: 40px;
  bottom: 52px;
  width: 50px;
  text-align: center;
    font-family: 'Bebas Neue';
    font-size:11pt;
    font-weight:bold;
}

.phb:nth-child(even) .pageNumber { color: black;
  left: 40px;
  bottom: 52px;
  width: 50px;
    text-align: center;
    font-family: 'Bebas Neue';
    font-size:11pt;
    font-weight:bold;
}

.phb:after {
        display: none;
    }

.phb .footnote { color: black 
    font-family: 'Bebas Neue' 
    font-weight: bold 
    vertical-align: center;
    padding-top:11px;
}

.phb:nth-child(even) .footnote {border-left:2px solid black;
    padding-left:6px;
}

.phb:nth-child(odd) .footnote {border-right:2px solid black;
    padding-right:6px;
}

.phb:after { 
    background-image:url('none') 
}

/* Dice and Symbols */

@font-face {
  font-family: 'Genesys';
  src: local('Genesys');
}
.phb .symbols {
    font-family: Genesys;
}

@font-face {
  font-family: 'Genesys1';
  src: local('EotE Symbol');
}
.phb .dice {
    font-family: Genesys1;
}


.phb .setback {
    font-family: Genesys1;
    color: black;
    text-shadow: -1px 0 #000000,0 1px #000000,1px 0 #000000,0 -1px #000000;
}

.phb .note .setback, .phb .note .boost, .phb .note .challenge, .phb .note .proficiency, .phb .note .difficulty, .phb .note .ability {
    text-shadow: -1px 0 #ffffff,0 1px #ffffff,1px 0 #ffffff,0 -1px #ffffff;
}

.phb .note  td > .setback, .phb .note td > .boost, .phb .note td > .challenge, .phb .note td > .proficiency, .phb .note td >  .difficulty, .phb .note td.ability {
    text-shadow:  -1px 0 #000000,0 1px #000000,1px 0 #000000,0 -1px #000000;
}

.phb .boost {
    font-family: Genesys1;
    color: #76CDDB;
    text-shadow: -1px 0 #000000,0 1px #000000,1px 0 #000000,0 -1px #000000;
}

.phb .challenge {
    font-family: Genesys1;
    color: #751317;
    text-shadow: -1px 0 #000000,0 1px #000000,1px 0 #000000,0 -1px #000000;
}

.phb .proficiency {
    font-family: Genesys1;
    color: #FEF035;
    text-shadow: -1px 0 #000000,0 1px #000000,1px 0 #000000,0 -1px #000000;
}

.phb .difficulty {
    font-family: Genesys1;
    color: #52287E;
    text-shadow: -1px 0 #000000,0 1px #000000,1px 0 #000000,0 -1px #000000;
}

.phb .ability {
    font-family: Genesys1;
    color: #46AC4E;
    text-shadow: -1px 0 #000000,0 1px #000000,1px 0 #000000,0 -1px #000000;
}

/* Archetypes */

.phb .archetype {
    background-image: url('https://gmbinder.com/images/wk1XTwj.png');
    height:62px;
    width:329px;
    background-size:100%;
    font-family: 'Bebas Neue';
    font-size:14pt;

    }

.phb .archetype .bra {
    position:relative;
    left:14px;
    top:6px;
    text-align:center;
    display:inline-block;
    width:25px;
}

.phb .archetype .agi {
    position:relative;
    left:42px;
    top:6px;
    width:25px;
    text-align:center;
    display:inline-block;
}
.phb .archetype .int {
    position:relative;
    left:68px;
    top:6px;
    width:25px;
    text-align:center;
    display:inline-block;
}

.phb .archetype .cun {
    position:relative;
    left:95px;
    top:6px;
    width:25px;
    text-align:center;
    display:inline-block;
}
.phb .archetype .wil {
    position:relative;
    left:122px;
    top:6px;
    width:25px;
    text-align:center;
    display:inline-block;
}
.phb .archetype .pre {
    position:relative;
    left:148px;
    top:6px;
    width:25px;
    text-align:center;
    display:inline-block;
}
/* Adversaries */

.phb .adversary {
    background-image: url('https://gmbinder.com/images/ks1JaPU.png');
    height:47px;
    width:329px;
    background-position: -3px 0px;
    background-size:102%;
    font-family: 'Bebas Neue';
    font-size:14pt;
}

.phb .adversary .soak {
    position:relative;
    left:26px;
    top:13px;
    width:25px;
    text-align:center;
    display:inline-block;
}
.phb .adversary .wound {
    position:relative;
    left:79px;
    top:13px;
    width:25px;
    text-align:center;
    display:inline-block;
}
.phb .adversary .strain {
    position:relative;
    left:135px;
    top:13px;
    width:25px;
    text-align:center;
    display:inline-block;
}
.phb .adversary .mdef {
    position:relative;
    left:176px;
    top:13px;
    width:25px;
    text-align:center;
    display:inline-block;
}
.phb .adversary .rdef {
    position:relative;
    left:175px;
    top:13px;
    width:25px;
    text-align:center;
    display:inline-block;
}

/* MINION STAT BLOCK */

.phb .minion {
    background-image: url('https://gmbinder.com/images/K1aEwZa.png');
    height:63px;
    width:329px;
    background-position: 42px 0px;
    background-repeat:no-repeat;
    background-size:75%;
    font-family: 'Bebas Neue';
    font-size:14pt;
}

.phb .minion .soak {
    position:relative;
    left:71px;
    top:13px;
    width:25px;
    text-align:center;
    display:inline-block;
}

.phb .minion .wound {
    position:relative;
    left:125px;
    top:13px;
    width:25px;
    text-align:center;
    display:inline-block;
}

.phb .minion .mdef {
    position:relative;
    left:165px;
    top:13px;
    width:25px;
    text-align:center;
    display:inline-block;
}
.phb .minion .rdef {
    position:relative;
    left:165px;
    top:13px;
    width:25px;
    text-align:center;
    display:inline-block;
}

/* Vehicles */

.phb .vehicle {
    background-image: url('https://gmbinder.com/images/JEgri2b.png');
    height:80px;
    width:329px;
    background-size: 100%;
    background-repeat:no-repeat;
    font-family: 'Bebas Neue';
    font-size:14pt;
}


.phb .vehicle .sil {
    position:relative;
    left:14px;
    top:6px;
    text-align:center;
    display:inline-block;
    width:25px;
}

.phb .vehicle .speed {
    position:relative;
    left:41px;
    top:6px;
    text-align:center;
    display:inline-block;
    width:25px;
}

.phb .vehicle .hand {
    position:relative;
    left:67px;
    top:6px;
    text-align:center;
    display:inline-block;
    width:25px;
}

.phb .vehicle .armor {
    position:relative;
    left:107px;
    top:12px;
    text-align:center;
    display:inline-block;
    width:25px;
}
.phb .vehicle .def {
    position:relative;
    left:163px;
    top:12px;
    text-align:center;
    display:inline-block;
    width:25px;    
}
.phb .vehicle .ht {
    position:relative;
    left:53px;
    top:53px;
    text-align:center;
    display:inline-block;
    width:25px;    
}

.phb .vehicle .ss {
    position:relative;
    left:107px;
    top:53px;
    text-align:center;
    display:inline-block;
    width:25px;    
}

/*Index*/

.phb .index-letter {
    color:rgb(118,18,19);
    font-size:24pt;font-weight:bold; 
    font-family:'Bebas Neue';
    line-height:1.1em;
}

.phb .index {
    list-style:none;
    padding:0;
    overflow-x:hidden;
    max-width:329px;
}

.phb .index li::before {
            content: ''; }
            
.phb .index li {
    
    display:flex;
}
            
.phb .index li span:first-child {
    margin-right:0.2em;
    order:1;
}
            
.phb .index li::after {
  content: '';
  border-bottom: 1px dotted;
  flex-grow: 1;
  order: 2;
  position:relative;
  top:-5px
}

.phb .index span + span {
    order:3;
    margin-left:0.2em;
    }
    
/* NON BLENDED IMAGE BORDER */
    
.phb .non-blended {
    padding:10px;
    border-width:2px;
    border-style:solid;
    border-image:linear-gradient(135deg, rgba(230,0,0,1) 0%,rgba(230,0,0,0.01) 99%,rgba(230,0,0,0) 100%);
    -moz-border-image:-moz-linear-gradient(-45deg, rgba(230,0,0,1) 0%, rgba(230,0,0,0.01) 99%, rgba(230,0,0,0) 100%); -webkit-border-image:-webkit-linear-gradient(-45deg, rgba(230,0,0,1) 0%,rgba(230,0,0,0.01) 99%,rgba(230,0,0,0) 100%);
    border-image-slice: 1;
}

.phb:after { content: ""; }
.phb:nth-child(even):after { background-image: none; }
.phb:nth-child(odd):after { background-image: none; }

.phb#p2{
    background-image:url(https://blenderartists.org/uploads/default/original/3X/9/5/95759fb054aa6ee343e5bd237c72c82a2c1c796c.jpg);
    background-size: cover;
    background-position: right;
}

.phb#p2 p{
    width: 100%;
	height: 100%;
	font-family: "Droid Sans", arial, verdana, sans-serif;
	font-weight: 500;
	font-size:15.5pt;
	color: #ff6;
	line-height: 140%;
}

.phb .cover-splotch {background-image:url('../imgs/splotch.png');filter: hue-rotate(202deg) brightness(35%) contrast(120%)}

.phb#p1:after { display:none; }

.phb#p1 {
    padding : 6mm;
    column-gap: 6mm;
}

.phb#p2 h2:after {
    display: none;
}

.phb#p4 h2:after {
    display: none;
}

.phb#p2 {
    padding : 8mm 2mm 2mm 2mm;
}

.phb#p4 {
    padding : 10mm;
}

.center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100%;
}

</style>

<div class='wide'>

<img src='../imgs/hyperdrive.jpg' class='cover-image'/>

<div class='cover-header'><img src='../imgs/sw-logo.png' class='center'/></div>

<div class='cover-splotch'></div>

<img src='../imgs/logo.png' style="position:absolute;bottom:4.7cm;left:0.3cm;width:9mm;z-index:+1;">

<div style="position:absolute;bottom:194px;left:50px;color:white;font-family:NodestoCaps;text-transform: uppercase;font-size:22px;font-weight:bold;">SWSE Homebrew Campaign</div>

<!-- <div class='cover-footer'>Genterated on : 12 JAN 2020 : 13:30PM : GMT+1000</div> -->

</div>

\page

<div class='wide' style="margin-left: 25%; margin-right: 25%;">

## A long time ago in a galaxy far,<br>far away&hellip;

</div>

<div class='wide' style="margin-left: 15%; margin-right: 15%; margin-top:2.5mm; margin-bottom:2.5mm;">

<img src='../imgs/sw-logo.png' style="width: 100%; margin-top:5mm;"/>

</div>

<div class='wide' style="margin-left: 25%; margin-right: 25%; text-align: center;">

EPISODE 0 </br>THE FATE OF THE JERICHO VII

</div>

<div class='wide' style="margin-left: 25%; margin-right: 25%;">

It is 205 years after the BATTLE OF YAVIN IV, and all is not well in the GALAXY&hellip;

UNEXPLAINED ATTACKS are targeting the WILD SPACE territories, with several planets having gone dark, being cut off from the HOLONET.
	
The latest being DOSUUN, with reports from survivors saying that STARSHIPS of UNKNOWN DESIGNS have both sent in ALIEN TROOPS to defeat the defenders of these worlds, then proceeding to turn the surfaces of these worlds to a form of glass.

On a shakedown run to the planet of MARAT V aboard the JERICHO VII, both it and its CREW come under attack by these UNKOWN ADVERSARIES. The CREW are ordered to jettison its CARGO, then abandon ship. YOU are part of this CREW&hellip;

</div>

\page

<style>

.phb#p3 h1{
    margin-bottom:0mm;
}

.phb#p3 h2{
    margin-bottom:1mm;
    margin-top:1mm;
}

.phb#p3 h3{
    margin-bottom:0mm;
    margin-top:0mm;
}

.phb#p3 h4{
    margin-bottom:0mm;
    margin-top:0mm;
    text-align:left;
    margin-left:0mm;
}

.phb#p3 table {
    table-layout: fixed;
}

.phb#p3 table:before {
    margin:0mm;
}

.phb#p3 th:nth-of-type(1),th:nth-of-type(4) {
    width: 15%;
}

.phb#p3 th:nth-of-type(2),th:nth-of-type(3),th:nth-of-type(5),th:nth-of-type(6) {
    width: 20%;
}

</style>

# Campaign House Rules

___
<p>Players are to abide by the following campaign house rules when creating their characters in this campaign.</p>

</br>

<div style="margin-bottom:15mm;">

### Default:

* The [2008 Errata](http://holocast.terceiraterra.com/wp-content/uploads/2011/10/SW_errata_A4_Out2008.pdf) will be in effect.
* 28 point buy (Slightly higher than default)
* May **NOT** have Non-Heroic classes
* At Campaign start, Characters begin at 3<sup>rd</sup> level, with the Wealth according to the below table.
* Instead of using Destiny Points (DP), I'll be using Backgrounds. Information on these can be found in the ***Rebellion Era Campaign Guide***, on pages 16&mdash;22.

### Species:

* Species given a “PC write-up” may be selected as PC races but I may restrict species based on campaign setting.  Other species including those with a NPC write-up may be selected with my approval.
* Yuuzhan Vong do receive Force Points equal to 3 + &frac12; heroic level each time they level in a heroic class.  They however may NOT take Force Sensitivity and are restricted like droids when it comes to how they can spend those points. Reason: the Vong Force Immunity in no way makes up for this lack of a vital game resource.

### Classes:

* Jedi have 4 + INT modifer.
* If going for a specific theme of class (Variant Force traditions, etc), see next section.

</br>

</div><div style="margin-bottom:-25mm;">

#### The following Class Traits can be substituted as</br>followed:

* Lightsaber may be replaced with Advanced Melee Weapons, Martial Arts I, or an Exotic weapon subject to GM approval.
* Rifles may be replaced with Advanced Melee Weapons.
* Rifles plus Pistols may be replaced with Lightsaber; the Lightsaber may then be exchanged as above.
* Rifles plus Armor (Lights & Medium) may be replaced with Martial Arts I.

### Skills:

* Use Computer:  Astrogate &ndash; This aspect of the skill may be used untrained by a ships system operator/pilot who is using a Navicomputer.

### Feats:

* Dodge: Instead of designating a single opponent you may designate either a single opponent, all ranged attacks, or all melee attacks against which you gain the +1 Reflex Defense.  You make this designation as a free action on your turn.  Reason:  Add functionality to the feat.
* Linguist:  Change prerequisite to INT 11.

### Combat:

* Diagonal Movement:  Counts as one square of movement.


### Player Specific Rules:

* Richard, at any point, is **NOT** allowed to munchkin the game. If he does so, he will harshly penalised. This includes via proxy.

### Banned Content

* Any *Tech Specialist* related items are banned.

</div>

<div class='wide'>

## Wealth by Level for Characters after 1st level

<!---
Character</br>Level | Starting</br>Credits | w/ Wealth</br>Talent
|:---:|:-----------:|:-----------:
1 | Max Class Credit Roll | Max Class Credit Roll + Wealth
2 | 4,000 | 8,000
3 | 12,000 | 24,000
4 | 24,000 | 48,000
5 | 40,000 | 80,000
6 | 60,000 | 120,000
7 | 84,000 | 168,000
8 | 112,000 | 224,000
9 | 144,000 | 288,000
10 | 180,000 | 360,000

</br>

Character</br>Level | Starting</br>Credits | w/ Wealth</br>Talent
|:---:|:-----------:|:-----------:
11 | 220,000 | 440,000
12 | 264,000 | 528,000
13 | 312,000 | 624,000
14 | 364,000 | 728,000
15 | 420,000 | 840,000
16 | 480,000 | 960,000
17 | 544,000 | 1,088,000
18 | 612,000 | 1,224,000
19 | 684,000 | 1,368,000
20 | 760,000 | 1,520,000
-->

| Character</br>Level | Starting</br>Credits | w/ Wealth</br>Talent | Character</br>Level | Starting</br>Credits | w/ Wealth</br>Talent |
|:---:|:-----------:|:-----------:|:---:|:-----------:|:-----------:|
| 1 | Max Class Credit Roll | Max Class Credit Roll + Wealth | 11 | 220,000 | 440,000 |
| 2 | 4,000 | 8,000 | 12 | 264,000 | 528,000 |
| 3 | 12,000 | 24,000 | 13 | 312,000 | 624,000 |
| 4 | 24,000 | 48,000 | 14 | 364,000 | 728,000 |
| 5 | 40,000 | 80,000 | 15 | 420,000 | 840,000 |
| 6 | 60,000 | 120,000 | 16 | 480,000 | 960,000 |
| 7 | 84,000 | 168,000 | 17 | 544,000 | 1,088,000 |
| 8 | 112,000 | 224,000 | 18 | 612,000 | 1,224,000 |
| 9 | 144,000 | 288,000 | 19 | 684,000 | 1,368,000 |
| 10 | 180,000 | 360,000 | 20 | 760,000 | 1,520,000 |

</div>

<div class='pageNumber auto'></div>

\page

<style>

/** Change the p2 to whatever page number is the last page in your document **/
.phb#p4:after { display:none; }

</style>

<div class='back-cover-image' style="height:300mm;"></div>

<div style='margin-top:20px;'></div>

<div class='back-cover-header'>

<img src='../imgs/cockpit.jpg' class='cover-image' style="transform: scaleX(-1);height:307mm;width:50cm;z-index:-10;position:absolute;top:;0cm;left:-20cm;"/>

## Prepare to enter Hyperspace&hellip;

</div>

<div class='back-cover-text'>

With a Session 0 & 1 Soundtrack playlist containing AC/DC, DragonForce, and a player piano Cantina Theme, players should find themselves rocking out with their sabers out.

</div>

<div style="margin-top:125mm;">

### A Campaign by RJBPrime

### Featuring: Mayhem, Wonder, and 

### Gratuitous Explosions

</div>

<img src='../imgs/logo.png' style="position:absolute;bottom:26mm;left:5cm;width:25mm;z-index:+1;">

</div>
