# CatarinaXV
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Convite XV Catarina</title>
  <style>
    body {
      background-color: #000;
      text-align: center;
      font-family: Arial, sans-serif;
    }
    .escondido {
      display: none;
    }
    img {
      max-width: 100%;
      height: auto;
      cursor: pointer;
    }
    .convite-icones {
      position: relative;
    }
    .icone {
      position: absolute;
      cursor: pointer;
    }
    /* Posições dos ícones no convite */
    #confirmar {
      top: 75%;
      left: 20%;
      width: 15%;
    }
    #presentes {
      top: 75%;
      left: 42.5%;
      width: 15%;
    }
    #mapa {
      top: 75%;
      left: 67%;
      width: 15%;
    }
  </style>
</head>
<body>

  <!-- Imagem da carta -->
  <img id="carta" src="Carta.png" alt="Convite XV Catarina">

  <!-- Imagem do convite e links -->
  <div id="convite" class="escondido">
    <div class="convite-icones">
      <img src="Convite.png" alt="Convite XV Catarina">
      
      <!-- Ícones clicáveis -->
      <a href="https://portal.derlo.com.br/landings/convidados_autoinsert/add" target="_blank">
        <div class="icone" id="confirmar"></div>
      </a>

      <div class="icone" id="presentes" onclick="mostrarPresentes()"></div>

      <a href="https://www.google.com/maps/dir//Ballroom+Barra+Ol%C3%ADmpica+-+Estrada+Coronel+Pedro+Corr%C3%AAa+-+Jacarepagu%C3%A1,+Rio+de+Janeiro" target="_blank">
        <div class="icone" id="mapa"></div>
      </a>
    </div>
  </div>

  <!-- Imagem da sugestão de presentes -->
  <div id="presentesImagem" class="escondido">
    <img src="Presentes.png" alt="Sugestão de Presentes">
  </div>

  <script>
    // Ao clicar na carta, mostrar o convite
    document.getElementById("carta").onclick = function() {
      document.getElementById("carta").style.display = "none";
      document.getElementById("convite").classList.remove("escondido");
    };

    // Mostrar a sugestão de presentes
    function mostrarPresentes() {
      document.getElementById("convite").style.display = "none";
      document.getElementById("presentesImagem").classList.remove("escondido");
    }
  </script>

</body>
</html>
![Carta](https://github.com/user-attachments/assets/e7f4d428-3e85-4a1d-ae47-d95ad26637e3)
![Presentes](https://github.com/user-attachments/assets/6974e1d8-2b45-4a55-82ff-0cefd92f07b9)
![Convite](https://github.com/user-attachments/assets/a51ff766-1043-4880-91cb-6b7154d0ca36)

