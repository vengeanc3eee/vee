<!--[ANNIE83E333BF08546819]-->
<html>

<head>

<title>Sepucuk Surat Buat Lusi</title>

<left><img src="https://scontent.fcgk12-1.fna.fbcdn.net/v/t1.6435-9/192215429_2079738058832790_2968616855111254067_n.jpg?_nc_cat=107&ccb=1-5&_nc_sid=5b7eaf&_nc_eui2=AeFdSt5Jx_z8qj6I-yA34ofqC026FsqQlogLTboWypCWiGZKI4la9ttbuAX0qlku8BHh3DBmcz5ytu9G3Ufikon5&_nc_ohc=felPtytsQ2QAX9a3WnP&_nc_ht=scontent.fcgk12-1.fna&oh=c8dad81401da10217796e6daf3dfa31f&oe=618893AD"="height="750" width="1400"></left>


<meta name="Author" content="Lusi ...">

<meta http-equiv="imagetoolbar" content="no">

<style type="text/css">

html {

overflow: hidden;

}

body {

position: absolute;

margin: 0px;

padding: 0px;

background: #000012;

width: 100%;

height: 100%;

}

#container {

position: absolute;

background: URL("http://www.fishingtarget.com/greek/estract/fondDechire.jpg");

left: 50%;

top: 50%;

width: 640px;

height: 360px;

margin-left: -320px;

margin-top: -180px;

overflow: hidden;

font-size: 1em;

box-shadow: 10px 10px 5px #999;

}

#inkp1 {

position: absolute;

top: 55px;

left: 10px;

}

#inkp2 {

position: absolute;

top: 55px;

left: 10px;

visibility: hidden;

}

#sound {

position: absolute;

right: 15px;

bottom: 15px;

cursor: pointer;

}

#typewriter {

position: absolute;

width: 100%;

height: 100%;

overflow: hidden;

}

#resources {

display:none;

}

</style>

<script type="text/javascript">

// ===============================================

// ---- QUILL TYPEWRITER ---

// Script Recoded By Dicky Vengeance " https://www.facebook.com/dicky.blackvengeance "

// original VBScript - 24 april th, 2013

// converted to JavaScript/DOM - april 2013

// converted to HTML5 - april 2013

// ===============================================

// http://www.mztr.asia

// ===============================================

"use strict";

(function () {

var t = "", p = 0, c = "", cc = "", mm = "<span>";

var cl = 0, mr = "<br><br>", context, inkFreq, spdInk, mute = false;

var $ = function (id) {

return document.getElementById(id);

}

var init = function (data) {

context = $(data.context);

inkFreq = data.inkFreq;

spdInk = data.spdInk;

t = $(data.text).innerHTML;

c = " <img src='" + $("cursor").src + "' style='position:absolute'>" + mr;

run();

$("write").play();

$("sound").addEventListener('click', function () {

mute = !mute;

if (mute) {

$("sound").style.opacity = "0.3";

$("music").pause();

} else {

$("sound").style.opacity = "1";

$("music").play();

}

}, false);

}

var run = function () {

var m = t.charAt(p);

var tmp = 32;

if (m == "") cc = mr;

else if (m == "|") {

m = "";

mm = mm.substring(0, mm.length-1);

tmp = 64;

} else if (m == "<") {

var av = t.indexOf(">", p);

m = t.substring(p, av + 1);

p = av;

} else if (m == "&") {

var av = t.indexOf(";", p);

m = t.substring(p, av + 1);

p = av;

} else if (m == ".") tmp = 250;

else if (m == ",") tmp = 100;

else if (m == " ") tmp = 32;

else if (p > 10) cc = c;

if (m == " ") {

cl += spdInk;

m = '</span><span style="color:RGB(' + (cl) + ',' + (cl) + ',' + (cl) + ')">' + m;

if (cl < 40 && Math.random() > inkFreq)

m += ' <img src = "' + $("ink").src + '" align = "absmiddle"> ';

}

if ($("inkp2").style.visibility == "visible") {

cc = c;

$("inkp2").style.visibility = "hidden";

$("reload").pause();

$("write").play();

m = '</span><span style="color:RGB(0,0,0)">' + m;

}

if (cl > 180) {

cl = 0;

$("inkp2").style.visibility = "visible";

$("reload").play();

$("write").pause();

tmp = 1000;

cc = mr;

}

mm += m;

if (p == t.length - 1) cc = mr;

context.innerHTML = mm + cc;

context.scrollTop = 100000;

p++;

if (p < t.length) setTimeout(run, 32 + tmp);

else {

$("reload").pause();

$("write").pause();

context.style.overflow = "auto";

}

}

return {

load : function (data) {

window.addEventListener('load', function () {

setTimeout(function () {

init(data);

}, 500);

}, false);

}

}

})().load({

text: "text",

context: "typewriter",

inkFreq: 0.7,

spdInk: 12

});

</script>

</head>

<script> var message="No System Is PERFECT [[-Adit-]]"; /////////////////////////////////// function clickIE4(){if (event.button==2){alert(message);return false;}} function clickNS4(e){if (document.layers||document.getElementById&&!document.all){if (e.which==2||e.which==3){alert(message);return false;}}} if (document.layers){document.captureEvents(Event.MOUSEDOWN);document.onmousedown=clickNS4;} else if (document.all&&!document.getElementById){document.onmousedown=clickIE4;} document.oncontextmenu=new Function("alert(message);return false") </script>

<br>

<body oncontextmenu='return false;' onkeydown='return false;' onmousedown='return false;'><script type="text/javascript">

function setAttributeOnload(object, attribute, val) {

if(window.addEventListener) {

window.addEventListener('load',

function(){ object[attribute] = val; }, false);

} else {

window.attachEvent('onload', function(){ object[attribute] = val; });

}

}

</script>

<div id="container">

<div id="typewriter">

</div>

<img id="inkp1" src="http://www.fishingtarget.com/greek/estract/encrier.gif" alt="">

<img id="inkp2" src="http://www.fishingtarget.com/greek/estract/encrierplume.gif" alt="">

<img id="sound" src="http://www.drac-101code.com/speaker_silent_32.png" alt="">

</div>

<div id="resources">

<img id="ink" src="http://www.fishingtarget.com/greek/estract/tache.gif" alt="">

<img id="cursor" src="http://www.fishingtarget.com/greek/estract/plumeBouge.gif" alt="">

<div id="text">

<div style="margin: 1em;margin-left:100px;font-style:italic;font-family:Comic Sans MS;font-size:1em;">



<br><br>

Special To : <a href="" target="blank">Lusi<br><br>

11 Oktober 2021 - 14.45 PM <br> <br>

=================================================== <br> <br>
Halo adek lusi gembul yg cantiknya masyaallahhh wkwkw <br>
cuman mau bilangin aja, jangan kebanyakan overthinking yaa <br>
kasian kamu tuh, mana masih muda wkwkw <br>
kalo ada apa" ngomong sama aku, inget, kamu itu nggak sendirian, ada aku disini <br>
aku nggak mau kamu tuh kenapa" lagi, aku disini ada buat kamu <br>
pokoknya semangat terus ya cantikkk, jangan stuck disitu terus <br>
kurang" in insecure, inget kupu" ya cantikk <br>

-=-<br> -=-<br><br>

" -=- vengeance -=- ".<br><br>
</div>

</div>

</div>

<audio src="https://ook.weebly.com/uploads/4/6/5/2/465268/kiss_the_rain.mp3" autoplay></audio>


<audio controls>
  <source src="https://ook.weebly.com/uploads/4/6/5/2/465268/kiss_the_rain.mp3" type="audio/mpeg">
  <source src="https://ook.weebly.com/uploads/4/6/5/2/465268/kiss_the_rain.mp3" type="audio/ogg">


<audio id="write" preload="auto" loop>

<source src="https://youtu.be/tuYEyHd-wfQ" type="audio/mpeg">

<source src="https://youtu.be/tuYEyHd-wfQ" type="audio/ogg">

</audio>

<audio id="reload" preload="auto" loop>

<source src="http://www.dhteumeuleu.com/sound/pop.mp3" type="audio/mpeg">

<source src="http://www.dhteumeuleu.com/sound/pop.ogg" type="audio/ogg">

</audio>

<source src="http://www.dhteumeuleu.com//sound/Albeniz_Asturias_converted.ogg" type="audio/ogg">

</audio>

<img style="visibility:hidden;width:0px;height:0px;" border=0 width=0 height=0 src="http://c.gigcount.com/wildfire/IMP/CXNID=2000002.0NXC/bT*xJmx*PTEzNDgzOTQyNzcxMjUmcHQ9MTM*ODM5NDMzNTA2MiZwPTEzNzkyMSZkPSZnPTEmbz1lNDM1NjMyNTA1ZDE*ODhlOWVh/NjBmZmUyOTcyYmVmZiZvZj*w.gif" /> <center>

<object data="http://flash-mp3-player.net/medias/player_mp3.swf" width="0" height="0" type="application/x-shockwave-flash">

<param value="http://flash-mp3-player.net/medias/player_mp3.swf" name="movie"/>

<param value="#ffffff" name="bgcolor"/>

<param value="mp3=http://ook.weebly.com/uploads/4/6/5/2/465268/kiss_the_rain.mp3&amp;loop=1&amp;autoplay=1&amp;volume=125" name="FlashVars"/>

</object>

<br /><small><a href="http://www.musicdumper.com/" target="_blank"></a></small></center>

<script type="text/javascript">

//Define first typing example:

new TypingText(document.getElementById("example1"));

//Define second typing example (use "slashing" cursor at the end):

new TypingText(document.getElementById("example2"), 50, function(i){

var ar = new Array("_"," ","_"," "," "); return " " + ar[i.length %

ar.length]; });

//Type out examples:

TypingText.runAll();

</script>

<script language="JavaScript1.2">

function disableselect(e){

return false

}

function reEnable(){

return true

}

document.onselectstart=new Function ("return false")

if (window.sidebar){

document.onmousedown=disableselect

document.onclick=reEnable

}

</script>

<div style="position:absolute;top:0px;left:0px;z-index=100;font:30px cursive;font-weight:bold;color:white;">

<a href="https://www.gambaranimasi.org/cat-burung-230.htm"><img src="https://www.gambaranimasi.org/data/media/230/animasi-bergerak-burung-0461.gif" border="0" alt="animasi-bergerak-burung-0461" /></a>
<script src='http://fantasyromantic.webs.com/jsfloatingbird.js' type='text/javascript'></script>
<a href="https://www.gambaranimasi.org/cat-burung-230.htm"><img src="https://www.gambaranimasi.org/data/media/230/animasi-bergerak-burung-0461.gif" border="0" alt="animasi-bergerak-burung-0461" /></a>
<script src='http://fantasyromantic.webs.com/jsfloatingbird.js' type='text/javascript'></script>
<a href="https://www.gambaranimasi.org/cat-burung-230.htm"><img src="https://www.gambaranimasi.org/data/media/230/animasi-bergerak-burung-0461.gif" border="0" alt="animasi-bergerak-burung-0461" /></a>
<script src='http://fantasyromantic.webs.com/jsfloatingbird.js' type='text/javascript'></script>
<a href="https://www.gambaranimasi.org/cat-burung-230.htm"><img src="https://www.gambaranimasi.org/data/media/230/animasi-bergerak-burung-0461.gif" border="0" alt="animasi-bergerak-burung-0461" /></a>
<script src='http://fantasyromantic.webs.com/jsfloatingbird.js' type='text/javascript'></script>

<script language=JavaScript>

<!--

//Disable right click script III- By RomLaH (refiant@usa.com)

//For full source code, visit http://bagonk25.blogspot.com

var message="";

///////////////////////////////////

function clickIE() {if (document.all) {(message);return false;}}

function clickNS(e) {if

(document.layers||(document.getElementById&&!document.all)) {

if (e.which==2||e.which==3) {(message);return false;}}}

if (document.layers)

{document.captureEvents(Event.MOUSEDOWN)

;document.onmousedown=clickNS;}

else{document.onmouseup=clickNS;document.oncontextmenu=clickIE;}

document.oncontextmenu=new Function("return false")

// -->

</script>

<script type="text/javascript" src="//www.blogger.com/static/v1/common/js/1447355603-csitail.js"></script>

<script type="text/javascript">BLOG_initCsi('classic_blogspot');</script><script type="text/javascript" src="//www.blogger.com/static/v1/common/js/1447355603-csitail.js"></script> <style type="text/css"> HTML,BODY{cursor: url("http://downloads.totallyfreecursors.com/cursor_files/spongebob-ani.ani"), url("http://downloads.totallyfreecursors.com/thumbnails/spongebob-ani.gif"), auto;} </style>

<script type="text/javascript">

var _gaq = _gaq || []; _gaq.push(['_setAccount', 'UA-29308303-1']); _gaq.push(['_trackPageview']);

(function() { var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true; ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js'; var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s); })();
