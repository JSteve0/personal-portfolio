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
          <span>Overall GPA: 3.67; Major GPA: 3.91</span>
          <span>August 2020 — December 2023</span>

          <!--
          <ul>
            <li>
              <p class="timeline-text">
                Clubs:
                <br />
                Vice President of the Technology Career Network (TCN) where we help students in STEM prepare and apply
                for jobs.
                <br />
                Member of the Coding Club where we work on LeetCode style problems and other coding challenges.
              </p>
            </li>
          </ul>
          -->
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
          <h4 class="h4 timeline-item-title">Technical Support Engineer @ Cargas Systems</h4>

          <span>April 2024 — Present</span>

          <ul class="job-description">
          </ul>

        </li>

        <li class="timeline-item">
          <h4 class="h4 timeline-item-title">Software Engineer Coop @ CNH Industrial</h4>

          <span>January 2023 — April 2024</span>

          <ul class="job-description">
            <li>
              <strong>Deployed and administered Jenkins CI/CD pipelines</strong>, streamlining build and testing processes across <strong>10 SVN repositories</strong>, which significantly boosted development efficiency.
            </li>
            <li>
              <strong>Enhanced functionality and extended features</strong> in a <strong>Windows Presentation Foundation (WPF) combine simulator</strong> using C# and .NET, leading to an improved development cycle across <strong>10 projects</strong>.
            </li>
            <li>
              <strong>Collaboratively extended Python integration tests</strong> using the Pytest framework to ensure application compatibility, with these tests automatically executed prior to merge requests via Jenkins pipelines.
            </li>
          </ul>

        </li>

        <li class="timeline-item">
          <h4 class="h4 timeline-item-title">Computer Science Tutor @ Millersville University</h4>

          <span>September 2023 — May 2024</span>

          <ul class="job-description">
            <li>
              <strong>Provided tutoring support</strong> across <strong>9 different computer science courses</strong> to students of varying skill levels, assisting over <strong>50 students</strong> throughout the academic year.
            </li>
            <li>
              <strong>Specialized in Intro to Programming I & II (Java), Data Structures and Algorithms (C++), and Operating Systems (C, x86 Assembly)</strong>, helping students achieve a higher average grade.
            </li>
            <li>
              <strong>Conducted both one-on-one and group sessions</strong>, utilizing tailored teaching methods and collaborative learning techniques to enhance comprehension and foster academic confidence.
            </li>
          </ul>

        </li>

        <li class="timeline-item">
          <h4 class="h4 timeline-item-title">Computer Science Student Grader @ Millersville University</h4>

          <span>Jan 2022 — May 2024</span>

          <ul class="job-description">
            <li>
              <strong>Served as a student grader</strong> under a professor, responsible for <strong>testing lab assignments</strong> and <strong>grading labs and homework</strong> independently.
            </li>
            <li>
              Participated in a <strong>joint effort for grading exams, quizzes, and papers</strong>, collaborating with the professor to ensure fair and accurate assessments.
            </li>
            <li>
              <strong>Graded assignments for multiple courses</strong>, including Intro to Programming I & II (Java), Data Structures and Algorithms (C++), Programming Languages (OCaml), Computer Architecture (C, x86), and Operating Systems (C).
            </li>
            <li>
              Efficiently <strong>graded for 2 to 3 classes per semester</strong>, each with approximately <strong>25 students</strong>, completing grading for labs and homework within <strong>5 days or less</strong>.
            </li>
          </ul>


        </li>

        <li class="timeline-item">
          <h4 class="h4 timeline-item-title">Application Developer Intern @ Church Mutual Insurance</h4>

          <span>June 2022 — August 2022</span>

          <ul class="job-description">
            <li>
              <strong>Developed user-friendly and modern RESTful websites</strong> for internal use, utilizing <strong>JavaScript, CSS, Node.js, and Vue.js</strong>, resulting in a significant increase in employee productivity across the entire company.
            </li>
            <li>
              <strong>Utilized Java, Spring Boot, Microsoft SQL Server, Maven, and various other tools</strong> to enhance existing REST APIs, resulting in a streamlined and efficient backend for the RESTful web applications.
            </li>
            <li>
              <strong>Utilized Azure DevOps tools</strong> to create a pipeline for deploying to <strong>develop, test, pre-production, and production environments</strong> once the previous stage passed all tests and were reviewed by engineers.
            </li>
          </ul>

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
            <div class="skill-progress-fill" style="width: 80%"></div>
          </div>
        </li>

        <li class="skills-item">
          <div class="title-wrapper">
            <h5 class="h5">Software Development</h5>
            <data value="80">80%</data>
          </div>

          <div class="skill-progress-bg">
            <div class="skill-progress-fill" style="width: 80%"></div>
          </div>
        </li>

        <li class="skills-item">
          <div class="title-wrapper">
            <h5 class="h5">Web Development</h5>
            <data value="60">60%</data>
          </div>

          <div class="skill-progress-bg">
            <div class="skill-progress-fill" style="width: 60%"></div>
          </div>
        </li>
      </ul>
    </section>
  </article>
</template>
<script>
export default {
  name: 'resume-page',
};
</script>
