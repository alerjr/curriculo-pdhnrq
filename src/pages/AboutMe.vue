<script>
</script>

<template>
  <div class="min-vh-100">
    <div
      class="min-vh-100 d-flex justify-content-center align-items-center"
      id="aboutMe"
    >
      <!-- Primeira coluna com foto de perfil e dados -->

      <div class="row col-md-12 col-10" id="profile">
        <div class="col-md-2 col-12">
          <!-- Foto de perfil -->
          <img
            src="..\assets\04.jpg"
            class="mt-2 mx-auto d-block col-md-12 col-6"
            alt="Foto"
          />
          <!-- Link linkedin -->
          <a href="https://www.linkedin.com/in/pedrohrqf"
            ><img
              src="..\assets\linkedin.svg"
              class="col-md-2 col-1 mx-auto d-block"
              alt="Linkedin"
          /></a>
          <div class="col-2"></div>
          <!-- Dados -->
          <p class="mt-2 col-12">
            22 anos<br />
            São Paulo, <b>SP</b><br />
            <a href="https://wa.me/+5511984406059">(11) 98440 - 6059</a><br />
            <a href="mailto:pedrohrqf@gmail.com">pedrohrqf@gmail.com</a>
          </p>
        </div>
        <!-- Segunda coluna com as abas sobre mim e formacao -->
        <div class="col-md-5 col-12">
          <hr />
          <h3 class="mt-sm-2">Sobre mim</h3>
          <p>
            Estudante de Publicidade e Propaganda no Centro Universitário das
            Américas, com experiência anterior como estagiário nas áreas de
            marketing e comunicação. Sou apaixonado por música e cultura pop, e
            esses interesses influenciam minha visão criativa e estratégica.
            Busco uma oportunidade de trabalho para aplicar meus conhecimentos
            em planejamento criativo, fotografia, design gráfico e estratégias
            de comunicação. Sou dinâmico, proativo, comunicativo e tenho
            experiência em trabalho em equipe, sempre focado em contribuir para
            resultados inovadores e eficazes.
          </p>
          <hr />
          <h3 class="mt-sm-2">Formação</h3>
          <p>
            <strong
              >Graduação em Publicidade e Propaganda - Centro Universitário das
              Américas</strong
            ><br />
            Cursando - 2025<br /><br />
            <strong
              >Curso Técnico em Web Design SENAI - Serviço Nacional de
              Aprendizagem Industrial</strong
            ><br />Concluído em Dezembro de 2018<br /><br />
            <strong
              >Idioma Inglês Avançado CNA - Cultural Norte Americano</strong
            ><br />
            2012 - 2020
          </p>
        </div>
        <!-- Terceira coluna com habilidades -->
        <div class="col-md-5 col-12">
          <hr />
          <h3>Habilidades</h3>
          <div>
            Pacote Office: Excel, PowerPoint, Word.<br />
            Adobe: Photoshop, Illustrator, Premiere, InDesign<br />
            Hubspot<br />
            GoToWebinar/StreamYard<br />
            Canva<br />
            Fotografia<br />
            Redes Sociais<br />
            Edição de Vídeos<br />
            Criação de Conteúdo
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
* {
  background-color: #d1cdc8;
}

#aboutMe {
  /* border-top: 2.5rem solid rgb(32, 32, 32); */
  /* border-bottom: 2.5rem solid rgb(32, 32, 32); */
  padding: 1rem;
}

p {
  font-family: "Inter Tight", serif;
  font-optical-sizing: auto;
  font-weight: 400;
  font-style: normal;
}

h3 {
  font-family: "Inter Tight", serif;
  font-optical-sizing: auto;
  font-weight: 700;
  font-style: normal;
}

#profile a {
  text-decoration: none;
  color: inherit;
  font-size: 13px;
  width: 50%;
}

.flecha:hover{
opacity: 75%;
}

@media (max-width: 768px) {
  a {
    font-size: 1rem;
  }
}
</style>