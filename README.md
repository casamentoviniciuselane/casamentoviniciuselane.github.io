<!DOCTYPE html>
<html lang="pt">
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"></meta>
   <meta charset="UTF-8"></meta>
      <meta name="viewport" content="width=device-width, initial-scale=1.0"></meta>
    <title>V | E</title>
    <link rel="preconnect" href="https://fonts.googleapis.com"></link>
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous"></link>
    <link href="https://fonts.googleapis.com/css2?family=Pinyon+Script&amp;display=swap" rel="stylesheet"></link>
    <link rel="preconnect" href="https://fonts.googleapis.com"></link>
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous"></link>
    <link href="https://fonts.googleapis.com/css2?family=Trirong:wght@400;700&amp;display=swap" rel="stylesheet"></link>
    <style>

/* Estilos para telas menores que 768px (smartphones) */
@media (max-width: 768px) {
  /* Adicione aqui os estilos para dispositivos móveis */
}

/* Estilos para telas entre 768px e 1024px (tablets) */
@media (min-width: 768px) and (max-width: 1024px) {
  /* Adicione aqui os estilos para tablets */
}
.map-container {
    width: 1200px;
    height: 600px;
    margin: 20px auto;
    border: 2px solid #333;
    border-radius: 10px;
}

@media (max-width: 768px) {
    .map-container {
        width: 80%; /* Ajuste a largura para 90% da tela em dispositivos móveis */
        height: 400px; /* Ajuste a altura para dispositivos móveis */
    }
}
footer {
    background-color: black;
    color: white;
    text-align: center;
    padding: 20px 0;
    font-family: 'Pinyon Script', cursive;
    font-size: 24px;
    margin-top: 20px; /* Adiciona espaço acima do rodapé, se necessário */
}
        body {
            font-family:'Trirong', serif; /* Fonte Trirong */
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: white;
            color: #333;
        }
    
header {
    background: url('https://i.imgur.com/CLxeSDg.jpeg') no-repeat center;
    background-size: cover;
    color: #556B2F;
    padding: 60px 20px;
    font-size: 50px;
    font-weight: bold;
    overflow: hidden;
    height: 80%; /* Defina a altura desejada */
}

header span {
            color: #556B2F; /* Verde oliva escuro */
            font-family: 'Pinyon Script', cursive; /* Fonte Pinyon Script */
            font-size: 40px; /* Aumenta o tamanho da fonte */
            display: block;
}

        nav {
    background-color: black;
    padding: 10px 0; /* Ajuste o espaçamento conforme necessário */
    margin: 0; /* Garante que não haja margens indesejadas */
    text-align: center; /* Centraliza os links dentro do menu */
}

#home h2,
#presen h2,
#gifts h2,
#location h2 {
    font-size: 28px;
    font-family: 'Pinyon Script', cursive;
    color: green; /* Define a cor do texto como verde */
}
nav a {
    margin: 0 15px;
    text-decoration: none;
    color: white;
    font-weight: bold;
}

        section {
            padding: 20px;
        }
        .hidden {
            display: none;
        }
        .gift-item {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 10px;
            border-bottom: 1px solid #ddd;
        }
        .gift-item img {
            width: 80px;
            height: 80px;
            object-fit: cover;
            border-radius: 5px;
            margin-right: 15px;
        }
        .gift-info {
            display: flex;
            align-items: center;
            flex-grow: 1;
            text-align: left;
        }
        .chosen {
            text-decoration: line-through;
            color: gray;
        }
#gifts button {
    background-color: black;
    color: white;
    padding: 5px 10px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

#gifts button:hover {
    background-color: #556B2F; /* Cor de fundo mais escura ao passar o mouse */
}

#gifts button.remove {
    background-color: #556B2F; /* Mantém a cor vermelha para o botão "Desfazer" */
}

#gifts button.remove:hover {
    background-color: black; /* Cor de fundo vermelha mais clara ao passar o mouse */
}

        button {
            cursor: pointer;
            background: #007bff;
            color: white;
            border: none;
            padding: 5px 10px;
            border-radius: 5px;
            margin-left: 5px;
        }
        .remove {
            background: #ff4d4d;
        }
   .location-image {
    width: 90%; /* Ajuste a largura da imagem */
    height: auto; /* Mantém a proporção da imagem */
    display: block; /* Garante que a imagem ocupe toda a largura disponível */
    margin: 20px auto; /* Centraliza a imagem horizontalmente e adiciona espaço vertical */
    border-radius: 10px; /* Opcional: adiciona bordas arredondadas */
    object-fit: cover; /* Garante que a imagem cubra o espaço alocado */
}

@media (max-width: 768px) {
    .location-image {
        width: 95%; /* Ajuste a largura para telas menores */
    }
}     
/* Nova regra para o h2 */

h2 {
    font-size: 28px;
    font-family: 'Pinyon Script', cursive;
}

#presen a {
    background-color: black;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
}

#presen a:hover {
    background-color: #556B2F; /* Cor de fundo mais escura ao passar o mouse */
}

#presen .image-gallery img {
    width: 400px; /* Defina a largura desejada para as imagens */
    height: auto; /* Mantém a proporção da imagem */
    margin: 0 10px; /* Adiciona espaçamento entre as imagens */
    border-radius: 5px; /* Adiciona bordas arredondadas (opcional) */
    object-fit: cover; /* Garante que as imagens cubram o espaço alocado */
}
    </style>
</head>
<body>
<header>♡</header>

<nav>
    <a href="#" onclick="showSection('home')">Início</a>
<a href="#" onclick="showSection('presen')">Confirmar Presença</a>
    <a href="#" onclick="showSection('gifts')">Lista de Presentes</a>
    <a href="#" onclick="showSection('location')">Local</a>
</nav>

<section id="home">
    <h2>Seja bem-vindo!</h2>
    <p>Se você está aqui, é porque faz parte da nossa história!</p>
<p>Como a felicidade é muito mais gostosa quando compartilhada, criamos esse site para dividir alguns detalhes do nosso dia com você.</p>
<p>Um lembrete muito importante: É imprescindível que você confirme a sua presença! Para isso, clique no menu <strong>"Confirmar Presença"</strong>.</p>
<p>Caso queira nos presentear, disponibilizamos uma lista, você achará no menu <strong>"Lista de Presentes"</strong>.</p>
<p>Contamos principalmente com a sua presença, felicitações e orações!</p>
<p>Com amor,</p>
<p>Vinícius e Elane.</p>
<p>19.08.2025</p>
  <img src="https://i.imgur.com/SimAcF7.jpeg" alt="Casamento" width="70%"></img>
</section>

<section id="presen" class="hidden">
    <h2>Querido Convidado,</h2>
    <p>Clicando no botão <strong>"Confirme Aqui"</strong>, você será redirecionado ao WhatsAPP.</p>
    <p>Somente os nomes confirmados até o dia 19.07.2025 serão colocados na organização, por isso, pedimos gentilmente que não se esqueça!</p>
<p></p>
   <div style="height: 50px;"></div><a href="https://wa.me/82996099454?text=Confirmação%20de%20presença%20no%20casamento" target="_blank">Confirme Aqui</a>
<p></p>
  <div style="height: 50px;"></div> <div class="image-gallery">
  <img src="https://i.imgur.com/NEee348.jpeg" alt="Descrição da segunda imagem"></img>
          <img src="https://i.imgur.com/ULGNd2m.jpeg" alt="Descrição da primeira imagem"></img>
      <img src="https://i.imgur.com/nypNHrc.jpeg" alt="Descrição da terceira imagem"></img>
    </div>
</section>

<section id="gifts" class="hidden">
    <h2>Lista de Presentes</h2>
    <p>Clique para escolher ou desfazer a escolha do presente. É importante que você selecione o presente escolhido, assim evita que outra pessoa compre o mesmo!</p>
    <div id="gift-list">
        <div class="gift-item" data-id="1">
            <div class="gift-info">
              <img src="https://source.unsplash.com/80x80/?dinner-set" alt="Jogo de pratos"></img>
                <span>Jogo de pratos</span>
            </div>
            <button onclick="chooseGift(this)">Escolher</button>
            <button class="remove hidden" onclick="removeGift(this)">Desfazer</button>
        </div>
        <div class="gift-item" data-id="2">
            <div class="gift-info">
              <img src="https://source.unsplash.com/80x80/?iron" alt="Ferro de passar"></img>
                <span>Ferro de passar</span>
            </div>
            <button onclick="chooseGift(this)">Escolher</button>
            <button class="remove hidden" onclick="removeGift(this)">Desfazer</button>
        </div>
        <div class="gift-item" data-id="3">
            <div class="gift-info">
                <img src="https://source.unsplash.com/80x80/?tableware" alt="Aparelho de jantar"></img>
                <span>Aparelho de jantar</span>
            </div>
            <button onclick="chooseGift(this)">Escolher</button>
            <button class="remove hidden" onclick="removeGift(this)">Desfazer</button>
        </div>
    </div>
</section>

<section id="location" class="hidden">
    <h2>Local do Casamento</h2>
    <p>Aqui está a localização da igreja onde acontecerá a cerimônia:</p>
    <div class="map-container">
        <iframe
    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3933.2416858678857!2d-35.72936962521106!3d-9.660378990428343!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x701459d9ead828d%3A0x4f66fc5593a66a62!2sIgreja%20Matriz%20de%20Nosso%20Senhor%20do%20Bomfim!5e0!3m2!1spt-BR!2sbr!4v1740453026048!5m2!1spt-BR!2sbr"
    width="100%"
    height="100%"
    style="border:0;"
    allowfullscreen=""
    loading="lazy"
>
</iframe>
    </div>
 <img src="https://i.imgur.com/K7DQgE2.jpeg" alt="Descrição da imagem do local" class="location-image"></img>
</section>

<script>
    function showSection(section) {
        document.getElementById('home').classList.add('hidden');
	document.getElementById('presen').classList.add('hidden');
        document.getElementById('gifts').classList.add('hidden');
        document.getElementById('location').classList.add('hidden');
        document.getElementById(section).classList.remove('hidden');
    }

    function saveGifts() {
        let chosenGifts = [];
        document.querySelectorAll(".gift-item.chosen").forEach(item => {
            chosenGifts.push(item.getAttribute("data-id"));
        });
        localStorage.setItem("chosenGifts", JSON.stringify(chosenGifts));
    }

    function loadGifts() {
        let chosenGifts = JSON.parse(localStorage.getItem("chosenGifts")) || [];
        document.querySelectorAll(".gift-item").forEach(item => {
            let id = item.getAttribute("data-id");
            if (chosenGifts.includes(id)) {
                item.classList.add("chosen");
                item.querySelector("button").classList.add("hidden");
                item.querySelector(".remove").classList.remove("hidden");
            }
        });
    }

    function chooseGift(button) {
        let item = button.parentElement;
        item.classList.add("chosen");
        button.classList.add("hidden");
        item.querySelector(".remove").classList.remove("hidden");
        saveGifts();
    }

    function removeGift(button) {
        let item = button.parentElement;
        item.classList.remove("chosen");
        item.querySelector("button").classList.remove("hidden");
        button.classList.add("hidden");
        saveGifts();
    }

    document.addEventListener("DOMContentLoaded", loadGifts);
</script>
 <footer>
        <p>Assim, permanecem agora estes três: a fé, a esperança e o amor. O maior destes, porém, é o amor!</p>
    </footer>

    <script>
        /* ... seu código JavaScript ... */
    </script>

</body>
</html>
