<template>
  <footer class="footer">
    <div class="container-fluid">
      <ul class="nav">
        <li class="nav-item">
          <a
            href="https://SerIOT.cl"
            target="_blank"
            rel="noopener"
            class="nav-link"
          >
            SerIOT.cl
          </a>
        </li>
        <li class="nav-item">
          <a
            href="https://SerIOT.cl"
            target="_blank"
            rel="noopener"
            class="nav-link"
          >
            Sobre Nosotros
          </a>
        </li>
        <li class="nav-item">
          <a
            href="hhttps://SerIOT.cl"
            target="_blank"
            rel="noopener"
            class="nav-link"
          >
            Blog
          </a>
        </li>
      </ul>
      <div class="copyright">
        &copy; {{ year }}, Hecho con <i class="tim-icons icon-heart-2"></i> por
        
        <a
          href="https://IorSER.cl"
          target="_blank"
          rel="noopener"
          >SER IOT</a
        >
        para una mejor web.
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  data() {
    return {
      year: new Date().getFullYear()
    };
  }
};
</script>
<style></style>
