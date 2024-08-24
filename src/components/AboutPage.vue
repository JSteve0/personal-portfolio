<template>
  <article class="about active" data-page="about">
    <header>
      <h2 class="h2 article-title">About me</h2>
    </header>

    <section class="about-text">
      <p>
        I'm a Technical Support Engineer at Cargas Systems, where I provide technical support for a range of applications built with HTML, JavaScript, CSS, C#, and Microsoft SQL Server. I hold a Bachelor's Degree in Computer Science from Millersville University, with a focus on Game Development, Computer Graphics, and Artificial Intelligence.
      </p>
      <p>
        During my undergraduate studies, I conducted research on developing a microsurgical simulator, specifically targeting eye surgery. My thesis, titled Modeling a Microsurgical Suture in Unity, explores the intricacies of simulating microsurgical procedures in a virtual environment.
      </p>
      <p>
        Looking ahead, I aspire to transition into a software developer role, where I can leverage my technical skills to build innovative solutions. In my free time, I enjoy working on personal projects, mainly using HTML, JavaScript, CSS, and C#. Outside of coding, I love playing golf, ping pong, and gaming—currently, I'm immersed in Red Dead Redemption 2.
      </p>
    </section>

    <!--
      - service
    -->

    <section class="service">
      <h3 class="h3 service-title">What I'm doing</h3>

      <ul class="service-list">
        <li class="service-item">
          <div class="service-icon-box">
            <img
              src="@/assets/images/icon-design.svg
                "
              alt="design icon"
              width="40"
            />
          </div>

          <div class="service-content-box">
            <h4 class="h4 service-item-title">Software Development</h4>

            <p class="service-item-text">
              Designing and engineering robust software solutions with a focus on efficiency and scalability.
            </p>
          </div>
        </li>

        <li class="service-item">
          <div class="service-icon-box">
            <img src="@/assets/images/icon-dev.svg" alt="Web development icon" width="40" />
          </div>

          <div class="service-content-box">
            <h4 class="h4 service-item-title">Web development</h4>

            <p class="service-item-text">
              Building dynamic and user-centric web applications with modern design and seamless functionality.
            </p>
          </div>
        </li>

        <li class="service-item">
          <div class="service-icon-box">
            <img src="@/assets/images/icon-controller.png" alt="controller icon" width="40" />
          </div>

          <div class="service-content-box">
            <h4 class="h4 service-item-title">Game Development</h4>

            <p class="service-item-text">
              Crafting immersive and innovative gaming experiences with cutting-edge technology.
            </p>
          </div>
        </li>

        <li class="service-item">
          <div class="service-icon-box">
            <img src="@/assets/images/icon-rl.png" alt="brain icon" width="40" />
          </div>

          <div class="service-content-box">
            <h4 class="h4 service-item-title">Reinforcement Learning</h4>

            <p class="service-item-text">
              Advancing intelligent systems through cutting-edge reinforcement learning algorithms and techniques.
            </p>
          </div>
        </li>
      </ul>
    </section>

    <!--
      - testimonials
    -->

    <!-- <section class="testimonials">

      <h3 class="h3 testimonials-title">Testimonials</h3>

      <ul class="testimonials-list has-scrollbar">

        <li class="testimonials-item">
          <div class="content-card" data-testimonials-item>

            <figure class="testimonials-avatar-box">
              <img src="./assets/images/avatar-1.png" alt="Daniel lewis" width="60" data-testimonials-avatar>
            </figure>

            <h4 class="h4 testimonials-item-title" data-testimonials-title>Daniel lewis</h4>

            <div class="testimonials-text" data-testimonials-text>
              <p>
                Richard was hired to create a corporate identity. We were very pleased with the work done. She has a
                lot of experience
                and is very concerned about the needs of client. Lorem ipsum dolor sit amet, ullamcous cididt
                consectetur adipiscing
                elit, seds do et eiusmod tempor incididunt ut laborels dolore magnarels alia.
              </p>
            </div>

          </div>
        </li>

        <li class="testimonials-item">
          <div class="content-card" data-testimonials-item>

            <figure class="testimonials-avatar-box">
              <img src="./assets/images/avatar-2.png" alt="Jessica miller" width="60" data-testimonials-avatar>
            </figure>

            <h4 class="h4 testimonials-item-title" data-testimonials-title>Jessica miller</h4>

            <div class="testimonials-text" data-testimonials-text>
              <p>
                Richard was hired to create a corporate identity. We were very pleased with the work done. She has a
                lot of experience
                and is very concerned about the needs of client. Lorem ipsum dolor sit amet, ullamcous cididt
                consectetur adipiscing
                elit, seds do et eiusmod tempor incididunt ut laborels dolore magnarels alia.
              </p>
            </div>

          </div>
        </li>

        <li class="testimonials-item">
          <div class="content-card" data-testimonials-item>

            <figure class="testimonials-avatar-box">
              <img src="./assets/images/avatar-3.png" alt="Emily evans" width="60" data-testimonials-avatar>
            </figure>

            <h4 class="h4 testimonials-item-title" data-testimonials-title>Emily evans</h4>

            <div class="testimonials-text" data-testimonials-text>
              <p>
                Richard was hired to create a corporate identity. We were very pleased with the work done. She has a
                lot of experience
                and is very concerned about the needs of client. Lorem ipsum dolor sit amet, ullamcous cididt
                consectetur adipiscing
                elit, seds do et eiusmod tempor incididunt ut laborels dolore magnarels alia.
              </p>
            </div>

          </div>
        </li>

        <li class="testimonials-item">
          <div class="content-card" data-testimonials-item>

            <figure class="testimonials-avatar-box">
              <img src="./assets/images/avatar-4.png" alt="Henry william" width="60" data-testimonials-avatar>
            </figure>

            <h4 class="h4 testimonials-item-title" data-testimonials-title>Henry william</h4>

            <div class="testimonials-text" data-testimonials-text>
              <p>
                Richard was hired to create a corporate identity. We were very pleased with the work done. She has a
                lot of experience
                and is very concerned about the needs of client. Lorem ipsum dolor sit amet, ullamcous cididt
                consectetur adipiscing
                elit, seds do et eiusmod tempor incididunt ut laborels dolore magnarels alia.
              </p>
            </div>

          </div>
        </li>

      </ul>

    </section> -->

    <!--
      - testimonials modal
    -->

    <!-- <div class="modal-container" data-modal-container>

      <div class="overlay" data-overlay></div>

      <section class="testimonials-modal">

        <button class="modal-close-btn" data-modal-close-btn>
          <ion-icon name="close-outline"></ion-icon>
        </button>

        <div class="modal-img-wrapper">
          <figure class="modal-avatar-box">
            <img src="./assets/images/avatar-1.png" alt="Daniel lewis" width="80" data-modal-img>
          </figure>

          <img src="./assets/images/icon-quote.svg" alt="quote icon">
        </div>

        <div class="modal-content">

          <h4 class="h3 modal-title" data-modal-title>Daniel lewis</h4>

          <time datetime="2021-06-14">14 June, 2021</time>

          <div data-modal-text>
            <p>
              Richard was hired to create a corporate identity. We were very pleased with the work done. She has a
              lot of experience
              and is very concerned about the needs of client. Lorem ipsum dolor sit amet, ullamcous cididt
              consectetur adipiscing
              elit, seds do et eiusmod tempor incididunt ut laborels dolore magnarels alia.
            </p>
          </div>

        </div>

      </section>

    </div> -->

    <!--
      - clients
    -->

    <!-- <section class="clients">

      <h3 class="h3 clients-title">Clients</h3>

      <ul class="clients-list has-scrollbar">

        <li class="clients-item">
          <a href="#">
            <img src="./assets/images/logo-1-color.png" alt="client logo">
          </a>
        </li>

        <li class="clients-item">
          <a href="#">
            <img src="./assets/images/logo-2-color.png" alt="client logo">
          </a>
        </li>

        <li class="clients-item">
          <a href="#">
            <img src="./assets/images/logo-3-color.png" alt="client logo">
          </a>
        </li>

        <li class="clients-item">
          <a href="#">
            <img src="./assets/images/logo-4-color.png" alt="client logo">
          </a>
        </li>

        <li class="clients-item">
          <a href="#">
            <img src="./assets/images/logo-5-color.png" alt="client logo">
          </a>
        </li>

        <li class="clients-item">
          <a href="#">
            <img src="./assets/images/logo-6-color.png" alt="client logo">
          </a>
        </li>

      </ul>

    </section> -->
  </article>
</template>
<script>
export default {
  name: 'about-page',
};
</script>
