# OlhonoBairrorecife.com
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<title>Recife Seguro - Olho no Bairro</title>

<style>

body{
font-family: Arial, sans-serif;
margin:0;
background:#eef3f7;
}

header{
background:#0a4da3;
color:white;
padding:25px;
text-align:center;
}

nav{
background:#063a7a;
padding:12px;
text-align:center;
}

nav a{
color:white;
margin:15px;
text-decoration:none;
font-weight:bold;
}

.container{
max-width:1000px;
margin:auto;
padding:20px;
}

.card{
background:white;
padding:20px;
margin-bottom:20px;
border-radius:10px;
box-shadow:0 4px 10px rgba(0,0,0,0.1);
}

h2{
color:#0a4da3;
}

input,select,textarea{
width:100%;
padding:10px;
margin-top:5px;
margin-bottom:15px;
border-radius:5px;
border:1px solid #ccc;
}

button{
background:#0a4da3;
color:white;
border:none;
padding:12px 20px;
border-radius:6px;
font-size:16px;
cursor:pointer;
}

button:hover{
background:#063a7a;
}

footer{
background:#222;
color:white;
text-align:center;
padding:15px;
}

</style>

</head>

<body>

<header>
<h1>Recife Seguro</h1>
<p>Projeto Olho no Bairro</p>
</header>

<nav>
<a href="#">Início</a>
<a href="#">Reportar Problema</a>
<a href="#">Mapa</a>
<a href="#">Sobre</a>
</nav>

<div class="container">

<div class="card">
<h2>Sobre o Projeto</h2>
<p>O Recife Seguro é uma plataforma digital que permite aos moradores registrar problemas urbanos como buracos, lixo acumulado e iluminação quebrada. O objetivo é ajudar a melhorar os bairros da cidade.</p>
</div>

<div class="card">
<h2>Registrar Problema</h2>

<form>

<label>Bairro</label>
<input type="text">

<label>Tipo de problema</label>
<select>
<option>Lixo acumulado</option>
<option>Buraco na rua</option>
<option>Iluminação quebrada</option>
<option>Esgoto aberto</option>
</select>

<label>Descrição</label>
<textarea rows="4"></textarea>

<button>Enviar denúncia</button>

</form>

</div>

</div>

<footer>
Projeto Integrador • Recife Seguro
</footer>

</body>
</html>
