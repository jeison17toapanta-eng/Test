<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Test del Amor 💕</title>
<style>
body {font-family: Arial; background:#ffe0ec; text-align:center; padding:40px;}
.container {background:white; padding:25px; border-radius:12px; max-width:350px; margin:auto; box-shadow:0 0 10px rgba(0,0,0,0.1);}
button {background:#ff4f8b; color:white; border:none; padding:12px; font-size:16px; border-radius:8px; cursor:pointer; width:100%; margin-top:10px;}
button:hover {opacity:.9;}
#preguntas, #procesando, #sorpresa, #final {display:none;}
</style>
</head>
<body>

<div class="container">
<h2>💘 Test del Amor 💘</h2>

<div id="preguntas">
<p>1. ¿Me amas mucho o muchísimo? 😌</p>
<button onclick="procesar()">Mucho 💞</button>
<button onclick="procesar()">Muchísimo ❤️</button>
</div>

<div id="procesando">
<p>Analizando tus respuestas... 🤓💭</p>
<p>Calculando amor verdadero 💗...</p>
<img src="https://i.gifer.com/ZZ5H.gif" width="80">
</div>

<div id="sorpresa">
<p>Pregunta sorpresa 😏</p>
<p>Si tuvieras que elegirme una y mil veces más…  
¿Lo harías? 💍💖</p>
<button onclick="final()">Sí, mil veces 💘</button>
<button onclick="final()">Por supuesto 😍</button>
</div>

<div id="final">
<p>✅ Resultado del test:</p>
<h3>💝 ¡Aprobaste con 100% de amor! 💝</h3>
<p>Solo quería decirte que…</p>
<h2>✨ TE AMO CON TODO MI CORAZÓN ✨</h2>
<p>Gracias por estar conmigo 💕</p>
</div>

</div>

<script>
document.getElementById("preguntas").style.display="block";

function procesar() {
document.getElementById("preguntas").style.display="none";
document.getElementById("procesando").style.display="block";
setTimeout(()=>{
document.getElementById("procesando").style.display="none";
document.getElementById("sorpresa").style.display="block";
}, 2000);
}

function final() {
document.getElementById("sorpresa").style.display="none";
document.getElementById("final").s
