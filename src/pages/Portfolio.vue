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
      <div class="col-md-8 col-12" id="galery">
        <!-- Imagem clicável que abre o modal -->
        <img
          src="https://fakeimg.pl/365x365/"
          alt=""
          data-bs-toggle="modal"
          data-bs-target="#exampleModal"
          class="img-fluid col-3"
          style="cursor: pointer"
        />

        <img
          src="https://fakeimg.pl/365x365/"
          alt=""
          data-bs-toggle="modal"
          data-bs-target="#exampleModal"
          class="img-fluid col-3"
          style="cursor: pointer"
        />

        <img
          src="https://fakeimg.pl/365x365/"
          alt=""
          data-bs-toggle="modal"
          data-bs-target="#exampleModal"
          class="img-fluid col-3"
          style="cursor: pointer"
        />

        <img
          src="https://fakeimg.pl/365x365/"
          alt=""
          data-bs-toggle="modal"
          data-bs-target="#exampleModal"
          class="img-fluid col-3"
          style="cursor: pointer"
        />
      </div>

      <!-- Modal -->
      <div
        class="modal fade"
        id="exampleModal"
        tabindex="-1"
        aria-labelledby="exampleModalLabel"
        aria-hidden="true"
      >
        <div class="modal-dialog modal-dialog-centered">
          <div class="modal-content">
            <img
              src="https://fakeimg.pl/365x365/"
              alt=""
              class="img-fluid"
              id="modalImage"
            />
          </div>
        </div>
      </div>
    </div>

    <div class="flecha row col-md-1 col-2 mt-4">
      <a
        href="#
    "
        ><img
          src="..\assets\up.svg"
          class="d-flex justify-content-start align-items-start col-md-6 col-12 m-2"
          alt="Topo da página"
      /></a>
    </div>
  </div>
</template>

<style scoped>
#portfolio {
  background-color: #d1cdc8;
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

.flecha:hover{
opacity: 75%;
}

#galery img:hover {
  opacity: 75%;
}
</style>
