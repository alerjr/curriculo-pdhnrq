<script setup>
</script>

<template>
  <div class="col text-center" id="homecard">
    <!-- Divisao de colunas no meio -->
    <div class="row col-12 m-0">
      <!-- Coluna 1 -->
      <div class="col-md-6 col-12" id="col-1">
        <!-- Titulo -->
        <div class="display-6 mt-4">
          Currículo
          <hr />
        </div>
        <br />

        <!-- Nome -->
        <div class="display-1 text-uppercase">Pedro<br />Henrique</div>
        <br />

        <!-- Fotos -->
        <div id="homecardGuides" class="mt-2 d-flex">
          <div class="m-4">
            <img src="..\assets\02.jpg" class="col-md-3 col-6 p-2" alt="Foto" />
            <img src="..\assets\03.jpg" class="col-md-3 col-6 p-2" alt="Foto" />
          </div>

          <!-- Abas -->
        </div>

        <div class="guides d-flex justify-content-around">
          <a href="#aboutMe"><p>Sobre mim</p></a>
          <a href="#experience"><p>Experiência</p></a>
          <a href="#portfolio"><p>Portfólio</p></a>
        </div>

        <!-- Bio -->
        <div class="mt-2 mb-4">
          Por aqui você pode conferir melhor sobre mim, <br>minhas habilidades, projetos e trajetória até o momento :)
        </div>
      </div>

      <!-- Coluna 2 -->
      <div
        class="col-md-6 col-12 d-flex justify-content-center align-items-center"
        id="col-2"
      >
        <!-- Foto -->
        <img src="..\assets\01.jpg" class="w-75 p-2" alt="Foto" id="picHome" />
      </div>
    </div>
  </div>
</template>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Indie+Flower&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Inter+Tight:ital,wght@0,100..900;1,100..900&display=swap");

#col-1 {
  background-color: 	#f67a93;
}

#col-2 {
  background-color: #f23857;
}

#homecard {
  font-family: "Inter Tight", serif;
  font-optical-sizing: auto;
  font-weight: 400;
  font-style: normal;
}

.guides {
  font-family: "Indie Flower", serif;
  text-transform: uppercase;
  font-size: 1.4rem;
  color: #1f1f1f;
  letter-spacing: -1.2px;
}

.display-6 {
  font-weight: 600;
}

.display-1 {
  letter-spacing: -5px;
}

.guides p:hover {
  opacity: 75%;
  cursor: pointer;
}

a {
  text-decoration: none;
  color: inherit;
}

#picHome:hover {
  animation: shakeX;
  animation-duration: 2s;
}

@media (max-width: 767px) {
  .guides {
    left: 73%;
    font-size: 5vw;
    margin-top: -1rem;
    line-height: 0.6;
  }
}
</style>
