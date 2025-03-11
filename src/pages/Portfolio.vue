<script>
</script>

<template>
  <div class="min-vh-30" id="portfolio">
    <div class="p-2 d-md-flex d-block justify-content-between align-items-top">
      <div class="col-md-4 col-12">
        <hr />
        <h2 class="text-start">Portfólio</h2>
        <p class="text-start">
          Alguns projetos desenvolvidos por mim durante o período de formação e
          trabalho na área de Marketing e Comunicação.
        </p>
      </div>
      <div class="col-md-8 col-12 p-2" id="galery">
        <!-- Imagem clicável que abre o modal -->

        <a
          href="https://www.behance.net/gallery/219069405/projeto-parede-para-sala-de-descompressao"
          target="_blank"
          rel="noopener noreferrer"
        >
          <img
            src="..\assets\thumb1.jpg"
            alt=""
            class="img-fluid col-3"
            style="cursor: pointer"
        /></a>

        <a
          href="https://www.behance.net/gallery/219069321/projeto-para-redes-sociais"
          target="_blank"
          rel="noopener noreferrer"
        >
          <img
            src="..\assets\thumb10.jpg"
            alt=""
            class="img-fluid col-3"
            style="cursor: pointer"
        /></a>

        <a
          href="https://www.behance.net/gallery/219069183/logotipo"
          target="_blank"
          rel="noopener noreferrer"
        >
          <img
            src="..\assets\thumb9.jpg"
            alt=""
            class="img-fluid col-3"
            style="cursor: pointer"
        /></a>

        <a
          href="https://www.behance.net/gallery/219069103/projeto-de-reformulacao-da-identidade-visual"
          target="_blank"
          rel="noopener noreferrer"
        >
          <img
            src="..\assets\thumb8.jpg"
            alt=""
            class="img-fluid col-3"
            style="cursor: pointer"
        /></a>

        <a
          href="https://www.behance.net/gallery/219069051/biscoito-globo-projeto-integrado"
          target="_blank"
          rel="noopener noreferrer"
        >
          <img
            src="..\assets\thumb7.jpg"
            alt=""
            class="img-fluid col-3"
            style="cursor: pointer"
        /></a>

        <a
          href="https://www.behance.net/gallery/219068983/neosaldina-projeto-de-faculdade"
          target="_blank"
          rel="noopener noreferrer"
        >
          <img
            src="..\assets\thumb6.jpg"
            alt=""
            class="img-fluid col-3"
            style="cursor: pointer"
        /></a>

        <a
          href="https://www.behance.net/gallery/219068915/projeto-leia-para-uma-crianca"
          target="_blank"
          rel="noopener noreferrer"
        >
          <img
            src="..\assets\thumb5.jpg"
            alt=""
            class="img-fluid col-3"
            style="cursor: pointer"
        /></a>

        <a
          href="https://www.behance.net/gallery/219068773/farm-projeto-integrado"
          target="_blank"
          rel="noopener noreferrer"
        >
          <img
            src="..\assets\thumb4.jpg"
            alt=""
            class="img-fluid col-3"
            style="cursor: pointer"
        /></a>

        <a
          href="https://www.behance.net/gallery/219068825/projeto-de-rebranding-7UP"
          target="_blank"
          rel="noopener noreferrer"
        >
          <img
            src="..\assets\thumb3.jpg"
            alt=""
            class="img-fluid col-3"
            style="cursor: pointer"
        /></a>

        <a
          href="https://www.behance.net/gallery/219068543/projeto-integrado-pr-tcc"
          target="_blank"
          rel="noopener noreferrer"
        >
          <img
            src="..\assets\thumb2.jpg"
            alt=""
            class="img-fluid col-3"
            style="cursor: pointer"
        /></a>
      </div>
    </div>

    <div class="flecha row col-md-1 col-2 mt-4">
      <a
        href="#
    "
        ><img
          src="..\assets\up.svg"
          class="d-flex justify-content-start align-items-start col-md-6 col-12 m-2 mb-md-5 mb-2"
          alt="Topo da página"
      /></a>
    </div>
  </div>
</template>

<style scoped>
#portfolio {
  background-color: #50bfe6;
}

.modal-body {
  background-color: #252525;
}
p {
  font-family: "Inter Tight", serif;
  font-optical-sizing: auto;
  font-weight: 400;
  font-style: normal;
}

h2 {
  font-family: "Inter Tight", serif;
  font-optical-sizing: auto;
  font-weight: 700;
  font-style: normal;
}

.flecha:hover {
  opacity: 75%;
}

#galery img {
  transition: opacity 0.3s ease;
  background-color: black;
}

#galery img:hover {
  opacity: 0.5;
}
</style>
