<script>
  export let src = ""
  export let alt = ""
  export let caption = ""
</script>

<figure>
  <div class="image">
    <img {src} {alt} />
  </div>
  <figcaption>{caption}</figcaption>
</figure>

<style>
  figure {
    padding: 20px;
    background-color: rgb(192, 214, 189);
  }

  .image {
    width: 45vw;
  }

  figcaption {
    color: #186b3c;
    font-style: italic;
    font-size: small;
  }
</style>
