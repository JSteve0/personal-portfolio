<template>
  <aside class="sidebar" data-sidebar>
    <div class="sidebar-info">
      <figure class="avatar-box">
        <img src="@/assets/images/my-avatar.png" alt="Justin Stevens" width="80" />
      </figure>

      <div class="info-content">
        <h1 class="name" title="Justin Stevens">Justin Stevens</h1>

        <p class="title">
          Computer Scientist @ Millersville University
          <br />
          Software Engineer Intern @ CNH Industrial
        </p>
      </div>

      <button class="info_more-btn" data-sidebar-btn>
        <span>Show Contacts</span>

        <ion-icon name="chevron-down"></ion-icon>
      </button>
    </div>

    <div class="sidebar-info_more">
      <div class="separator"></div>

      <ul class="contacts-list">
        <li class="contact-item">
          <div class="icon-box">
            <ion-icon name="mail-outline"></ion-icon>
          </div>

          <div class="contact-info">
            <p class="contact-title">Email</p>

            <a href="mailto:jmsteve1@millersville.edu" class="contact-link"
              >jmsteve1@millersville.edu</a
            >
          </div>
        </li>

        <li class="contact-item">
          <div class="icon-box">
            <ion-icon name="location-outline"></ion-icon>
          </div>

          <div class="contact-info">
            <p class="contact-title">Location</p>

            <address>Millersville, Pennsylvania, USA</address>
          </div>
        </li>
      </ul>

      <div class="separator"></div>

      <ul class="social-list">
        <li class="social-item">
          <a href="https://github.com/JSteve0" class="social-link" target="_blank">
            <ion-icon name="logo-github"></ion-icon>
          </a>
        </li>

        <li class="social-item">
          <a
            href="https://www.linkedin.com/in/justin-stevens-77546021b/"
            class="social-link"
            target="_blank"
          >
            <ion-icon name="logo-linkedin"></ion-icon>
          </a>
        </li>
      </ul>
    </div>
  </aside>
</template>

<script>
export default {
  name: 'SideBar'
}
</script>

<style scoped></style>
