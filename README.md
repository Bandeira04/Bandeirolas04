# Bandeirolas04
Repositório 3º Trimestre
<button onclick="alert('O botão verde foi acionado!')" class="botao-verde">CLIQUE AQUI</button>
<h1> Alura Fone </h1>
 <section class="teclado">
    <input type="button" value="1">
    <input type="button" value="2">
    <input type="button" value="3">
    <input type="button" value="4">
    <input type="button" value="5">
    <input type="button" value="6">
    <input type="button" value="7">
    <input type="button" value="8">
    <input type="button" value="9">
    <input type="button" value="*">
    <input type="button" value="0">
    <input type="button" value="#">
  </section>
  <input type="tel" placeholder="Digite seu telefone">
  * {
    box-sizing: border-box;
  }
  
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    background-color: #191919;
    min-height: 100vh;
  }
  
  input {
    border: none;
    color: inherit;
    font-size: inherit;
    font-weight: inherit;
    font-family: inherit;
  }
  
  h1 {
    font-family: 'Montserrat', sans-serif;
    font-size: 24px;
    color: #fff;
  }
  
  .teclado {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 10px; 
    background-color: #cccccc;
    border-radius: 30px;
    padding: 10px;
  }
  
  input[type=button] {
    border-radius: 20px;
    cursor: pointer;
    font-family: 'Montserrat', sans-serif;
    height: 80px;
    width: 80px;
  }
  
  input[type=tel] {
    background-color: #cccccc;
    border-radius: 10px;
    font-family: monospace;
    font-size: 22px;
    height: 40px;
    margin-bottom: 24px;
    padding: 10px;
    text-align: center;
    width: 280px;
  }
  document.querySelector('input[type=tel]');
  document.querySelector('#tecla_sol')
  <section>
    <button class="tecla-buzina">BEEP BEEP!</button>
    </section> 
         
    <audio src="sons/buzina.wav" id="som_buzina"></audio>
    ocument.querySelector('#som_buzina').play()
  }
  
  document.querySelector('.tecla_buzina').onclick = tocaBuzina
  var lista De Teclas = document.querySelector(‘#tecla’);
  var lista De Teclas = document.querySelector(‘#tecla’);
  while (contador,listaDeTeclas.length) { 
    listaDeTeclas[contador].onclick = função () {
     tocaSom(‘.som_tecla_pom’);
    }
    }
    function tocaSom () {
      document.querySelector(idElementoAudio).play();
  }
  
  `O time ${primeiroLugar} foi o grande vencedor do campeonato, marcando um total de ${quantidade} gols!`

  var nomes = ["Joy", "Beethoven", "Jully", "Leopoldo"];

  for (var contador = 0; contador < nomes.length; contador++) {
      console.log(nomes[contador]);
  }
  const listaDeTeclas = document.querySelectorAll('input[type=button]');
  const inputTel = document.querySelector('input[type=tel]');
  
  for (let indice = 0; indice < listaDeTeclas.length; indice++) {
  
    const tecla = listaDeTeclas[indice];
  
    tecla.onclick = function () {
      inputTel.value = inputTel.value + tecla.value;
    }
  }
  const listaDeTeclas = document.querySelectorAll('input[type=button]');

for (let indice = 0; indice < listaDeTeclas.length; indice++) {
const tecla = listaDeTeclas[indice];

tecla.onkeydown = function (evento) {
if(evento.code === "Enter" || evento.code === "Space") {
tecla.classList.add('ativa');
}
}
tecla.onkeyup = function () {
tecla.classList.remove('ativa');
}
}const tempo = 0
let tempo = 0
let tempo = “zero”
let tempo = “0”
if (idade >= 16 || idade === "autorização") {
console.log("Sua compra foi aprovada!");
}

let hora = 14;

if (hora < 12) {
console.log("Bom dia!");
} else {
console.log("Boa tarde!");
}
function entregaPacote(corDoPacote) {
if (corDoPacote == 'vermelho') {
mandaProCeara();
}
if (corDoPacote == 'azul') {
mandaProRioDeJaneiro();
}
}
