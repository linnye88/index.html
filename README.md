# index.html<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<title>Oie meu docinho pao com banana 👀</title>
<style>
body {
  font-family: Arial, sans-serif;
  background: #fff0f6;
  text-align: center;
  padding: 30px;
}
nav button {
  margin: 5px;
  padding: 10px 15px;
}
section { display: none; }
section.active { display: block; }
</style>
</head>

<body>

<h1>babi ai lob iu 🩷</h1>

<nav>
  <button onclick="show('carta')">Carta</button>
  <button onclick="show('musica')">Músicas</button>
</nav>

<section id="carta" class="active">
  <p>CARTINHA PRO MEU NENE</p>
</section>

<section id="musica">
  <p>https://open.spotify.com/playlist/5Q5gFE1kmGLFHhTNLI6NYn?si=Ho6s6mXiTQuyIoFkS3F5Ag&pt=076193588b4395579adf64beb18204fc&pi=9i0NRke8QAKfD</p>
</section>

<script>
function show(id){
  document.querySelectorAll('section').forEach(s => s.classList.remove('active'));
  document.getElementById(id).classList.add('active');
}
</script>

</body>
</html>
