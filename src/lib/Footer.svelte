<script>
  export let author
  export let date
  export let organisation
  export let link
</script>

<footer>
  <p>&copy;{author} {date}</p>
  <a href={link}>{organisation}</a>
</footer>

<style>
  footer {
    background: rgb(45, 67, 42);
    text-align: center;
    padding: 20px;
  }

  p {
    color: beige;
  }
</style>
