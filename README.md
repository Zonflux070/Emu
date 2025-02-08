<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>A Emu</title>
  <style>
    /* Estilo geral*/
body {
  margin: 0px;
  padding: 0px;
  background-color: #259E34;
}
p {
  color: #FFFFFF;
  font-size: 16px;
  font-family: Georgia, 'Times New Roman', Times, serif;
}
h1, h2, h3 {
  font-family: 'Times New Roman', Times, serif;
}
header, main, section, footer {
  width: 100%;
  margin: 0px;
}
/* Cabeçalho */
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #95F8A0;
  padding: 10px;
}
#logo {
  width: 40px;
  height: 40px;
  border: 1px solid #FFFFFF;
  border-radius: 30%;
}
.icon-menu {
  font-size: 35px;
  cursor: pointer;
}
/* Barra de Menu*/
.menu {
  background-color: #12661CB5;
  position: fixed;
  top: 0;
  left: -60%;
  width: 60%;
  height: 100%;
  transition: 0.3s;
}
.menu ul {
  list-style: none;
  text-align: center;
  padding: 20px;
}
.menu ul li {
  margin: 20px 0;
}
.menu a {
  text-decoration: none;
  font-size: 18px;
  color: #FBFBFF;
}
.fechar-menu {
  background: none;
  text-align: right;
  border: none;
  font-size: 30px;
  color: #FFFFFF;
  cursor: pointer;
}
/* secção 1*/
#sect1 {
  text-align: center;
  background-image: url('8d33ffe7-9e84-465c-8f53-932b3221c824.jpeg');
  background-repeat: no-repeat;
  background-size: 100% 100%;
  padding: 10px;
}
#sect1 h1 {
  color: #FFFFFF;
  font-size: 30px;
}
#sect1 a {
  text-decoration: none;
  font-size: 20px;
  border: 1px solid #FFFFFF;
  padding: 1px 80px 1px 80px;
  color: #FFFFFF;
}
/* secção 2*/
#sect2 {
  text-align: center;
}
#sect2 h2 {
  font-size: 16px;
  color: #FFFFFF;
}
/* secção 3*/
#sect3 {
  display: flex;
  justify-content: space-between;
}
#separar31 {
  text-align: justify;
  background-image: url('1f540a9d-a023-4209-92ff-a6296402083c.jpeg');
  background-repeat: no-repeat;
  background-size: 100% 100%;
  text-shadow: 4px 4px 4px #000000;
  font-weight: bold;
  padding: 5px;
  width: 50%;
}
#separar32 {   
  background-image: url('09988813-80e7-43bb-8ab6-2c295fd92fd0.jpeg');
  background-repeat: no-repeat;
  background-size: 100% 100%;
  width: 50%;
}
/* secção 4*/
#sect4 {
  display: flex;
  justify-content: space-between;
}
#sect41 {
background-image: url('6677e222-4050-41b8-b709-545c13b6cee1.jpeg');
background-repeat: no-repeat;
background-size: 100% 100%;
width: 50%;
}
/* secção 5*/
#sect5 img {
  width: 200px;
  height: 300px;
  padding: 10px 1px 20px 0px;
}
/* secção 6*/
#sect6 {
  background-image: url('ac079aca-8315-417c-9089-8f38a3df2658.jpeg');
  background-repeat: no-repeat;
  background-size: 100% 100%;
  text-align: center;
}
#sect6 a {
  color: #FFFFFF;
}
/* secção 7*/
#sect7 {
  display: flex;
  justify-content: space-between;
}
.sect70 {
  color: #FFFFFF;
  width: 50%;
}
.sect70 a {
  color: #FFFFFF;
}
/* secção 8*/
#sect8 {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 0px;
}
#sect8 img {
  width: 100%;
  height: 100%;
}
#sect9 {
  display: flex;
  justify-content: space-between;
  background-image: url('7c5c3cf1-d9dc-4c1d-bccf-1e596383c438.jpeg');
  background-repeat: no-repeat;
  background-size: 100% 100%;
  padding: 5px;
}
#sect90 {
  background-image: url('bf4ef127-1a86-41c4-997d-c3d3a8d26665.jpeg');
  background-repeat: no-repeat;
  background-size: 100% 100%;
  width: 50%;
  padding: 5px;
}
/* Formulário */
form {
    display: flex;
    flex-direction: column;
}


.input-duplo {
    display: flex;
    justify-content: space-between;
}

input, textarea, button {
    margin: 5px 0;
    padding: 10px;
    width: 100%;
}

button {
    background-color: #1F681D;
    color: white;
    border: none;
}

/* Rodapé */
footer {
    font-size: 10px;
    font-family: monospace;
    text-align: center;
    background-color: #487247;
    padding: 10px;
}

footer a {
  font-size: 10px;
  color: #FBFBFF;
}
  </style>
</head>
<body>
  <!-- Cabeçalho -->
 <header>
   <div>
     <img id="logo" src="playlistCropperBoomPlayer.jpg">
   </div>
   <div class="icon-menu" onclick="toggleMenu()">☰</div>
 </header>
   <!-- Barra de Menu -->
  <nav id="menu" class="menu">
    <button class="fechar-menu" onclick="toggleMenu()">✖</button>
    <ul>
      <li><a href="#">Pág 1</a></li>
      <li><a href="#">Pág 2</a></li>
      <li><a href="#">Pág 3</a></li>
    </ul>
  </nav>
 <!-- Corpo -->
 <main>
   <!-- Secção 1 -->
   <section id="sect1">
     <h1>Emu: A Pedra do Infinito e do Labirinto</h1>
     <a href="#">Espectro</a>
   </section>
   <!-- Secção 2 -->
   <section id="sect2">
     <h2>Sobre a Emu</h2>
     <p>No coração do tempo, onde o poder e a ambição se entrelaçam, existe Emu—uma pedra mística de energia infinita, capaz de manipular a mente de qualquer ser vivo. Um artefato tão poderoso que sua existência por si só ameaça o equilíbrio do universo.</p>
   </section>
   <!-- Secção 3 -->
   <section id="sect3">
     <div id="separar31">
       <p>Forjada na Era Distorcida—um tempo onde os fortes arrancavam a liberdade dos fracos—Emu nasceu das mãos de um homem chamado Moyo. Cansado das guerras, da violência e das incontáveis mortes, Moyo ansiava por um mundo sem sofrimento. E assim, ele criou o impossível: uma pedra que poderia subjugar toda a humanidade, impondo uma paz absoluta.</p>
     </div>
     <div id="separar32"></div>
   </section>
   <!-- Secção 4 -->
   <section id="sect4">
     <div id="sect41"></div>
     <div style="width: 50%; padding: 5px">
       <p>Mas a paz forçada é apenas outra forma de opressão. Durante um ano, Moyo dominou as mentes de todos, mas logo percebeu que havia se tornado o que mais temia—um tirano. Na tentativa de reparar seu erro, lançou o mundo em um sono profundo, permitindo que cada ser vivesse para sempre dentro de seus próprios sonhos mais desejados.</p>
     </div>
   </section>
   <!-- Secção 5 -->
   <section id="sect5">
     <img src="4d215ee9-5896-42c7-8849-f6e35df00b6c.jpeg">
     <p>Por três longos anos, o mundo dormiu. Mas a Emu revelava um segredo sombrio: sua energia infinita vinha a um preço terrível. A cada uso, ela roubava a vida de quem a controlava. Moyo entendeu então que, se morresse, ninguém sensato restaria para proteger a pedra do apetite insaciável dos ambiciosos. Ele quebrou o feitiço, libertou a humanidade e desapareceu junto com a Emu.</p>
   </section>
   <!-- Secção 6 -->
   <section id="sect6">
     <p>Os séculos passaram, e com eles, a Grande Guerra trouxe o fim da Era Distorcida. Mas o desejo pelo poder nunca morre. Já sem forças, Moyo procurou o herói que pôs fim à era de opressão e confiou a ele sua maior maldição. Para selá-la, o herói cobriu Emu com um metal que se regenera e o envolveu com um segundo metal indestrutível. Então, lançou a pedra no espaço, acreditando ter enterrado para sempre sua ameaça.<br /><br />Mas o destino é cruel. Milhões de anos depois, Emu retornaria, não como uma relíquia esquecida, mas como o estopim de uma nova guerra.</p>
     <a href="#">Spiderbot</a>
   </section>
   <!-- Secção 7 -->
   <section id="sect7">
     <div class="sect70"><h2>Os Mistérios de Emu</h2></div>
     <div class="sect70" style="text-align: center"><p>Embora seja um artefato inanimado, Emu é inútil sem um guardião. Moyo, temendo seu próprio fracasso, entrelaçou na pedra uma teia de sentimentos conflitantes, criando um labirinto mental incompreensível. Qualquer um que tentasse controlar seu poder ficaria preso em suas próprias obsessões, perdido em um ciclo eterno de desejos e ilusões.</p>
      <a href="#">Gosth</a>
     </div>
   </section>
   <!-- Secção 8 -->
   <section id="sect8">
     <img src="aa1779b5-dfb3-468f-ba2f-4818b941ae7e.jpeg">
     <img src="9ea9b42f-12a0-464c-80d4-1c7653bdd77b.jpeg">
     <img src="515d9c01-f80f-4290-8457-749a82a28b79.jpeg">
     <img src="4d215ee9-5896-42c7-8849-f6e35df00b6c.jpeg">
   </section>
   <!-- Secção 9 -->
   <section id="sect9">
     <p style="width: 50%; font-weight: bold; text-shadow: 4px 4px 4px #000000">Mas seu segredo mais aterrador é a Unimente—um domínio invisível onde todas as mentes do passado e do presente se encontram. Um lugar sem tempo, sem barreiras, onde os ecos dos que tentaram dominar Emu ainda ressoam, sussurrando promessas de poder e condenação.<br /><br />E assim, a pedra aguarda… Dormindo no silêncio do cosmos, esperando a próxima alma ambiciosa o bastante para desafiar seu labirinto.</p>
     <div id="sect90"></div>
   </section>
   <!-- Formulário -->
   <section>
     <h3>O que Achaste:</h3>
     <p>Cada palavra que escrevemos ganha vida através de vocês. Suas vozes, suas emoções e suas interpretações fazem desta história algo maior do que imaginamos. Queremos saber: o que essa jornada desperta em vocês? Compartilhem seus pensamentos, pois é graças a vocês que continuamos a criar.</p>
     <form id="formulario">
       <input type="text" id="nome" placeholder="Escreva o seu nome completo">
       <input type="email" id="email" placeholder="Escreva um e-mail válido">
       <div class="input-duplo">
         <input type="date" id="data">
         <input type="tel" id="contacto" placeholder="+244924465746">
       </div>
       <textarea id="mensagem" placeholder="Diz-nos o que achaste"></textarea>
       <button type="submit">Enviar</button>
     </form>
   </section>
 </main>
 <footer>
   <p>A você, visitante, nosso mais sincero agradecimento por embarcar nesta jornada fascinante sobre o Espectro. Sua curiosidade e dedicação nos motivam a continuar explorando os mistérios deste universo tão único. Esperamos que cada secção lida tenha despertado sua imaginação e lhe oferecido momentos de reflexão e inspiração.</p>
   <a href="#">A Origem</a>
   <p>© 2025 Universo Zônflux. Todos os direitos reservados.</p>
 </footer>
<script>
  function toggleMenu() {
  const menu = document.getElementById('menu');
  if (menu.style.left === "0px") {
    menu.style.left = "-60%";
    document.removeEventListener("click", closeMenuOnClickOutside);
  } else {
    menu.style.left = "0px";
    setTimeout(() => {
      document.addEventListener("click", closeMenuOnClickOutside);
    }, 100);
  }
}

function closeMenuOnClickOutside(event) {
  const menu = document.getElementById('menu');
  const menuIcon = document.querySelector(".menu-icon");

  if (!menu.contains(event.target) && !menuIcon.contains(event.target)) {
    menu.style.left = "-60%";
    document.removeEventListener("click", closeMenuOnClickOutside);
  }
}

document.getElementById("formulario").addEventListener("submit", function(event) {
  event.preventDefault();

  let nome = document.getElementById("nome").value;
  let email = document.getElementById("email").value;
  let data = document.getElementById("data").value;
  let contato = document.getElementById("contacto").value;
  let mensagem = document.getElementById("mensagem").value;

  if (nome && email && data && contato && mensagem) {
    let dados = {
      nome,
      email,
      data,
      contato,
      mensagem
    };

    // Armazena os dados no LocalStorage
    localStorage.setItem("formularioTelethra", JSON.stringify(dados));

    alert("Agradecemos pelo seu feedback!");

    setTimeout(() => {
      document.getElementById("mensagem-sucesso").style.display = "none";
    }, 3000);

    document.getElementById("formulario").reset();
  } else {
    alert("Preencha todos os campos!");
  }
});
</script>
</body>
</html>
<!--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 /// -->
