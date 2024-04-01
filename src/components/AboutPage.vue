<template>
  <article class="about active" data-page="about">
    <header>
      <h2 class="h2 article-title">About me</h2>
    </header>

    <section class="about-text">
      <p>
        I'm a Senior Computer Science major at Millersville University, and I'm passionate about technology. I'm
        currently gaining hands-on experience as a Software Engineer Intern at CNH Industrial in New Holland, PA, where
        I'm working on developing and maintaining complex software systems. It's been a great opportunity to apply what
        I've learned in the classroom to real-world situations, learn about the latest technologies and industry trends,
        and collaborate with a team of experienced engineers.
      </p>

      <p>
        In addition to my internship, I'm also conducting research on building a microsurgery simulator in Unity. My
        specific focus is on developing a more advanced and lifelike suture to improve the simulator's realism and
        effectiveness as a training tool. I'm excited to be writing a thesis on this research, which will allow me to
        explore the intersection of technology and healthcare more deeply. Through this project, I'm able to apply my
        programming skills in a unique way and contribute to the advancement of medical training.
      </p>

      <p>
        Apart from my internship and research, I also serve as a student grader for the Computer Science department at
        Millersville University. This role has allowed me to sharpen my leadership and communication skills while
        contributing to the growth of future Computer Science students. It's been a great opportunity to connect with my
        peers and share my knowledge and experience with others who are just starting on their own journeys in the
        field.
      </p>

      <p>
        Overall, my academic and practical experiences have equipped me with a strong foundation in computer science
        theory and practical application, as well as the skills needed to make meaningful contributions to the tech
        industry. I'm excited to see where my passions and experiences will take me in the future, whether it's pursuing
        a career in software engineering or research.
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
