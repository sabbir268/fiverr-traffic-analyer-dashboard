<template>
  <footer class="footer">
    <div class="container-fluid">
      <ul class="nav">
        <li class="nav-item">
          <a class="nav-link" href="#"> Traffic Analyzer </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/"> Blog </a>
        </li>
      </ul>
      <div class="copyright">
        © {{ year }}  Allrights reserved by TrafficAnalyzer.org
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  data() {
    return {
      year: new Date().getFullYear(),
    };
  },
};
</script>
<style>
</style>
