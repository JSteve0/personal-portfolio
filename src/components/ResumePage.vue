<template>
  <article class="resume" data-page="resume">

    <header>
      <h2 class="h2 article-title">Resume</h2>
    </header>

    <section class="timeline">

      <div class="title-wrapper">
        <div class="icon-box">
          <ion-icon name="book-outline"></ion-icon>
        </div>

        <h3 class="h3">Education</h3>
      </div>

      <ol class="timeline-list">

        <li class="timeline-item">

          <h4 class="h4 timeline-item-title">Millersville University</h4>

          <span>Bachelor of Science in Computer Science</span>
          <span>3.67 GPA</span>
          <span>August 2020 — December 2023</span>

          <ul>
            <li>
              <p class="timeline-text">
                Clubs:
                <br>
                Vice President of the Technology Career Network (TCN) where we help students in STEM prepare and apply
                for jobs.
                <br>
                Member of the Coding Club where we work on LeetCode style problems and other coding challenges.
              </p>
            </li>
          </ul>

        </li>

      </ol>

    </section>

    <section class="timeline">

      <div class="title-wrapper">
        <div class="icon-box">
          <ion-icon name="book-outline"></ion-icon>
        </div>

        <h3 class="h3">Experience</h3>
      </div>

      <ol class="timeline-list">

        <li class="timeline-item">

          <h4 class="h4 timeline-item-title">Software Engineer Coop @ CNH Industrial</h4>

          <span>January 2023 — Present</span>

          <p class="timeline-text">
            Nemo enim ipsam voluptatem blanditiis praesentium voluptum delenit atque corrupti, quos dolores et qvuas
            molestias
            exceptur.
          </p>

        </li>

        <li class="timeline-item">

          <h4 class="h4 timeline-item-title">Computer Science Tutor @ Millersville University</h4>

          <span>September 2023 — Present</span>

          <p class="timeline-text">
            Nemo enims ipsam voluptatem, blanditiis praesentium voluptum delenit atque corrupti, quos dolores et
            quas molestias
            exceptur.
          </p>

        </li>

        <li class="timeline-item">

          <h4 class="h4 timeline-item-title">Computer Science Student Grader @ Millersville University</h4>

          <span>Jan 2022 — Present</span>

          <p class="timeline-text">
            Nemo enims ipsam voluptatem, blanditiis praesentium voluptum delenit atque corrupti, quos dolores et
            quas molestias
            exceptur.
          </p>

        </li>
        <li class="timeline-item">

          <h4 class="h4 timeline-item-title">Application Developer Intern @ Church Mutual Insurance</h4>

          <span>June 2022 — August 2022</span>

          <p class="timeline-text">
            Nemo enims ipsam voluptatem, blanditiis praesentium voluptum delenit atque corrupti, quos dolores et
            quas molestias
            exceptur.
          </p>

        </li>

      </ol>

    </section>

    <section class="skill">

      <h3 class="h3 skills-title">My skills</h3>

      <ul class="skills-list content-card">

        <li class="skills-item">

          <div class="title-wrapper">
            <h5 class="h5">Game Development in Unity</h5>
            <data value="80">80%</data>
          </div>

          <div class="skill-progress-bg">
            <div class="skill-progress-fill" style="width: 80%;"></div>
          </div>

        </li>

        <li class="skills-item">

          <div class="title-wrapper">
            <h5 class="h5">Software Development</h5>
            <data value="80">80%</data>
          </div>

          <div class="skill-progress-bg">
            <div class="skill-progress-fill" style="width: 80%;"></div>
          </div>

        </li>

        <li class="skills-item">

          <div class="title-wrapper">
            <h5 class="h5">Web Development</h5>
            <data value="60">60%</data>
          </div>

          <div class="skill-progress-bg">
            <div class="skill-progress-fill" style="width: 60%;"></div>
          </div>

        </li>

      </ul>

    </section>

  </article>
</template>
<script>
export default {
  name: 'resume-page'
}
</script>