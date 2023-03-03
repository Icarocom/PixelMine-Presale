<template>
  <footer class="ud-footer-presale">
    <div
      class="wrapper d-flex flex-column justify-content-center align-items-center"
    >
      <div class="ud-mb-60">
        <router-link to="/">
          <img
            src="../../assets/img/logo.svg"
            alt="Pixel Mine Logo"
            class="ud-footer__logo-img"
          />
        </router-link>
      </div>

      <nav class="ud-nav ud-nav--footer ud-mb-25">
        <ul class="ud-nav-list">
          <li class="ud-nav__item">
            <a class="ud-nav__link">
              Pixel Mine © {{ new Date().getFullYear() }}
            </a>
          </li>
        </ul>
      </nav>
    </div>
  </footer>
</template>
