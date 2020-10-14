<template>
  <footer class="footer">
    <div class="container-fluid">
      <ul class="nav">
        
        <li class="nav-item">
          <a class="nav-link" href="#">
            ระบบควบคุมประตูน้ำ
          </a>
        </li>
      </ul>
      <div class="copyright">
        © {{year}} developed by
        <a href="#" target="_blank" rel="noopener">IoT Team</a>
      </div>
    </div>
  </footer>
</template>
<script>
  export default {
    data() {
      return {
        year: new Date().getFullYear()
      }
    }
  };
</script>
<style>
</style>
