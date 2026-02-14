# index.html<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<title>Para você</title>
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

<h1>💗</h1>

<nav>
  <button onclick="show('carta')">Carta</button>
  <button onclick="show('musica')">Músicas</button>
</nav>

<section id="carta" class="active">
  <p>escreve aqui depois</p>
</section>

<section id="musica">
  <p>links das músicas aqui</p>
</section>

<script>
function show(id){
  document.querySelectorAll('section').forEach(s => s.classList.remove('active'));
  document.getElementById(id).classList.add('active');
}
</script>

</body>
</html>
