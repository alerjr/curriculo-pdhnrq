<script setup>
</script>

<template>
  <div class="col text-center" id="homecard">
    <!-- Divisao de colunas no meio -->
    <div class="row col-12 m-0 min-vh-100">
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
          <div class="guides">
            <a href="#aboutMe"><p class="mt-2">Sobre mim</p></a>
            <a href="#experience"><p>Experiência</p></a>
            <a href="#portfolio"><p>Portfólio</p></a>
          </div>
        </div>

        <!-- Bio -->
        <div class="mt-4 mb-4">
          Lorem ipsum dolor sit amet. Eum perspiciatis recusandae et aperiam
          illum ut<br />
          reiciendis dolor. Qui esse consequatur qui voluptate corrupti est
          adipisci quasi.<br />
        </div>
      </div>

      <!-- Coluna 2 -->
      <div
        class="col-md-6 col-12 d-flex justify-content-center align-items-center"
        id="col-2"
      >
        <!-- Foto -->
        <img src="..\assets\01.jpg" class="w-75 p-2" alt="Foto" />
      </div>
    </div>
  </div>
</template>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Indie+Flower&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Inter+Tight:ital,wght@0,100..900;1,100..900&display=swap");

#col-1 {
  background-color: #f5e9dd;
}

#col-2 {
  background-color: #e2dcce;
}

#homecard {
  font-family: "Inter Tight", serif;
  font-optical-sizing: auto;
  font-weight: 400;
  font-style: normal;
}

#homecardGuides {
  font-family: "Indie Flower", serif;
  text-transform: uppercase;
  font-size: 1.4rem;
  color: rgb(76, 3, 3);
  letter-spacing: -1.2px;
}

.display-6 {
  font-weight: 600;
}

.display-1 {
  letter-spacing: -5px;
}

.guides {
  position: absolute;
  left: 34%;
  margin-top: 2rem;
  font-size: 2.5vw;
  line-height: 0.8;
}

.guides p:hover {
  opacity: 75%;
  cursor: pointer;
}

a {
  text-decoration: none;
  color: inherit;
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
