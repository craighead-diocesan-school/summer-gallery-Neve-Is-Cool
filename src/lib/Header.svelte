<script>
  export let title = "Main heading"
  export let subtitle = "Secondary heading"
</script>

<header class="hero">
  <div class="hero-body">
    <h1 class="title">{title}</h1>
    <h2 class="subtitle">{subtitle}</h2>
  </div>
</header>

<style>
  .hero {
    background: rgb(45, 67, 42);
  }

  .title {
    color: aliceblue;
    font-weight: bold;
    font-size: xx-large;
  }

  .subtitle {
    color: beige;
    font-size: x-large;
  }
</style>
