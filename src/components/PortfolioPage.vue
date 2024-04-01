<template>
  <article class="portfolio" data-page="portfolio">
    <header>
      <h2 class="h2 article-title">Portfolio</h2>
    </header>

    <section class="projects">
      <ul class="filter-list">
        <li class="filter-item">
          <button class="active" data-filter-btn>All</button>
        </li>

        <li class="filter-item">
          <button data-filter-btn>Game Development</button>
        </li>

        <li class="filter-item">
          <button data-filter-btn>Applications</button>
        </li>

        <li class="filter-item">
          <button data-filter-btn>Web development</button>
        </li>
      </ul>

      <div class="filter-select-box">
        <button class="filter-select" data-select>
          <div class="select-value" data-selecct-value>Select category</div>

          <div class="select-icon">
            <ion-icon name="chevron-down"></ion-icon>
          </div>
        </button>

        <ul class="select-list">
          <li class="select-item">
            <button data-select-item>All</button>
          </li>

          <li class="select-item">
            <button data-select-item>C</button>
          </li>

          <li class="select-item">
            <button data-select-item>Applications</button>
          </li>

          <li class="select-item">
            <button data-select-item>Web development</button>
          </li>
        </ul>
      </div>

      <ul class="project-list">
        <li class="project-item active" data-filter-item data-category="web development">
          <a href="https://mucsci-students.github.io/2023sp-420-Maryjane/" target="_blank">
            <figure class="project-img">
              <div class="project-item-icon-box">
                <ion-icon name="eye-outline"></ion-icon>
              </div>

              <img
                src="@/assets/images/project-images/spelling-bee.png"
                alt="Spelling Bee"
                loading="lazy"
                height="849"
                width="1467"
              />
            </figure>

            <h3 class="project-title">Spelling Bee</h3>

            <p class="project-category">Web development</p>
          </a>
        </li>

        <li class="project-item active" data-filter-item data-category="game development web development">
          <a href="https://jsteve0.github.io/P5Game/" target="_blank">
            <figure class="project-img">
              <div class="project-item-icon-box">
                <ion-icon name="eye-outline"></ion-icon>
              </div>

              <img src="@/assets/images/project-images/frostbyt3-the-videogame.png" alt="orizon" loading="lazy" />
            </figure>

            <h3 class="project-title">FrostByt3TheVideogame</h3>

            <p class="project-category">Game Development & Web Development</p>
          </a>
        </li>

        <li class="project-item active" data-filter-item data-category="applications game development">
          <!--<a href="#">-->

          <figure class="project-img">
            <!--<div class="project-item-icon-box">
              <ion-icon name="eye-outline"></ion-icon>
            </div>-->

            <img src="@/assets/images/project-images/simulator.png" alt="Microsurgical Simulator" loading="lazy" />
          </figure>

          <h3 class="project-title">Microsurgical Simulator</h3>

          <p class="project-category">Application & Game Development</p>

          <!--</a>-->
        </li>

        <li class="project-item active" data-filter-item data-category="game development web development">
          <a href="https://jsteve0.github.io/Pong/" target="_blank">
            <figure class="project-img">
              <div class="project-item-icon-box">
                <ion-icon name="eye-outline"></ion-icon>
              </div>

              <img src="@/assets/images/project-images/pong.png" alt="Pong Replica" loading="lazy" />
            </figure>

            <h3 class="project-title">Pong Replica</h3>

            <p class="project-category">Game Development & Web Development</p>
          </a>
        </li>

        <li class="project-item active" data-filter-item data-category="applications">
          <a href="https://github.com/JSteve0/OpenAI-Image-Generator" target="_blank">
            <figure class="project-img">
              <div class="project-item-icon-box">
                <ion-icon name="eye-outline"></ion-icon>
              </div>

              <img src="@/assets/images/project-images/image-generator.png" alt="Image Generator" loading="lazy" />
            </figure>

            <h3 class="project-title">OpenAI Image Generator</h3>

            <p class="project-category">Application</p>
          </a>
        </li>

        <li class="project-item active" data-filter-item data-category="applications">
          <a href="https://github.com/JSteve0/OpenGLGraphicsEngine" target="_blank">
            <figure class="project-img">
              <div class="project-item-icon-box">
                <ion-icon name="eye-outline"></ion-icon>
              </div>

              <img src="@/assets/images/project-images/image-generator.png" alt="Graphics Engine" loading="lazy" />
            </figure>

            <h3 class="project-title">OpenGL Graphics Engine</h3>

            <p class="project-category">Application</p>
          </a>
        </li>

        <li class="project-item active" data-filter-item data-category="game development">
          <a href="https://github.com/JSteve0/2022fa-475-AmazingEscape" target="_blank">
            <figure class="project-img">
              <div class="project-item-icon-box">
                <ion-icon name="eye-outline"></ion-icon>
              </div>

              <img src="@/assets/images/project-images/amazing-escape.png" alt="Amazing Escape" loading="lazy" />
            </figure>

            <h3 class="project-title">Amazing Escape</h3>

            <p class="project-category">Game Development</p>
          </a>
        </li>

        <li class="project-item active" data-filter-item data-category="game development">
          <a href="https://github.com/JSteve0/2022fa-475-HoppingHome" target="_blank">
            <figure class="project-img">
              <div class="project-item-icon-box">
                <ion-icon name="eye-outline"></ion-icon>
              </div>

              <img src="@/assets/images/project-images/hopping-home.png" alt="Hopping Home" loading="lazy" />
            </figure>

            <h3 class="project-title">Hopping Home</h3>

            <p class="project-category">Game Development</p>
          </a>
        </li>

        <li class="project-item active" data-filter-item data-category="game development">
          <!--<a href="https://github.com/JSteve0/2022fa-475-HoppingHome" target="_blank">-->

          <figure class="project-img">
            <!--<div class="project-item-icon-box">
              <ion-icon name="eye-outline"></ion-icon>
            </div>-->

            <img src="@/assets/images/project-images/bloons-copied-us.png" alt="Bloons Copied Us" loading="lazy" />
          </figure>

          <h3 class="project-title">Bloons Copied Us</h3>

          <p class="project-category">Game Development</p>

          <!--</a>-->
        </li>
      </ul>
    </section>
  </article>
</template>
<script>
export default {
  name: 'portfolio-page',
};
</script>
