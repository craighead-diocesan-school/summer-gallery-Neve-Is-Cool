<script>
  import Header from "$lib/Header.svelte"
  import Footer from "$lib/Footer.svelte"
  import Nav from "$lib/Nav.svelte"
  import Card from "$lib/Card.svelte"
</script>

<Header />

<Nav />

<main>
  <section class="about-me">
    <h2>About me</h2>

    <p>Hi I'm Neve and I am taking level 2 digi.</p>
  </section>
</main>

<Card />

<Footer />

<style>
  main {
    background: rgb(192, 214, 189);
    text-align: center;
    padding: 20px;
  }

  h2 {
    background: rgb(192, 214, 189);
    font-size: large;
    font-weight: bold;
    padding-left: 70px;
    color: rgb(45, 67, 42);
    border-top: 2px solid;
    padding-top: 50px;
  }

  p {
    margin-bottom: 20px;
  }
</style>
