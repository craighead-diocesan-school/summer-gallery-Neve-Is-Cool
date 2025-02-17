<script>
  import Header from "$lib/Header.svelte"
  import Footer from "$lib/Footer.svelte"
  import Nav from "$lib/Nav.svelte"
  import Image from "$lib/Image.svelte"
</script>

<Header title="Summer Gallery" subtitle="Images from summer" />

<Nav />
<h2>Subheading about the main content</h2>

<main>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum suscipit eget diam ut pharetra. Duis euismod odio a elit interdum consectetur sit amet a nulla. Integer a venenatis nibh. Maecenas vitae faucibus turpis. Praesent gravida vulputate nisi at bibendum. Cras ac eros et felis aliquet interdum. Nullam blandit leo sit amet risus laoreet, quis ullamcorper dui efficitur. Mauris vestibulum libero lectus, sit amet sagittis velit maximus quis. Pellentesque nec leo nec urna convallis elementum vel quis eros.</p>

  <p>Etiam nec sapien a tellus bibendum tempus. Vivamus interdum hendrerit dui non lobortis. Praesent commodo condimentum tortor eget consequat. Duis eget vehicula nulla. Donec iaculis nunc molestie, commodo eros et, fermentum turpis. Pellentesque est purus, vestibulum ut blandit eu, hendrerit non sem. Suspendisse velit justo, cursus sit amet auctor ut, gravida a metus. Cras vitae commodo felis, maximus lacinia quam. Suspendisse auctor ex non condimentum mollis. Phasellus dictum lacinia ligula vitae facilisis. Nunc posuere metus non tellus ultricies, et ultrices tellus feugiat. Nullam sed neque non augue molestie tristique eget a libero. Curabitur eget velit non sem ultrices consequat et a sapien. Nullam accumsan velit massa, a fringilla magna maximus at. Proin nisl sem, lacinia eu sollicitudin vitae, dignissim a ipsum. Nulla sit amet faucibus nisl.</p>

  <p>Nullam molestie semper elementum. Curabitur vitae nibh gravida, lobortis mauris in, sodales massa. Cras eu nulla nec urna consequat pharetra et in quam. Praesent dignissim orci at nisi aliquet malesuada. Curabitur in ligula vel massa ullamcorper hendrerit et a risus. Donec purus elit, luctus quis gravida id, maximus eu mi. Ut quis mollis lorem, eget faucibus risus. Quisque varius metus ut massa luctus viverra. Maecenas sit amet elit mattis, placerat lectus semper, hendrerit purus. Phasellus justo urna, vestibulum feugiat finibus sed, sagittis ac tortor. Donec in dolor bibendum, ultrices sem nec, laoreet ex. Integer faucibus eros sapien, et rutrum tellus luctus sed. Cras sit amet vulputate lorem.</p>

  <p>Cras pellentesque sagittis neque a lacinia. Duis eu faucibus nunc. Cras ullamcorper, purus ac cursus iaculis, turpis ligula dictum leo, id tincidunt sapien quam vitae nulla. Nulla facilisis eu nisi ac aliquam. Cras id erat eleifend justo tristique malesuada. Quisque id nisi dolor. Vestibulum enim tortor, finibus ut dui ut, dignissim elementum dui. Fusce interdum neque nec orci laoreet molestie.</p>

  <p>Quisque id velit arcu. Duis gravida efficitur tincidunt. Pellentesque mattis consequat pellentesque. Integer blandit mollis lectus, sed porta elit pharetra non. Sed nec faucibus mauris. Donec bibendum eros ac justo vestibulum, aliquam vehicula tortor malesuada. Vestibulum vitae risus sagittis, dignissim odio non, tempus est.</p>
</main>

<Image src="New-years.JPG" alt="Neve with friends on New Year's Eve" caption="New Year's Eve with friends" />
<Image src="New-years.JPG" alt="Neve with friends on New Year's Eve" caption="New Year's Eve with friends" />
<!--Comment -- change images to what hasn;t beeen used.-->

<Footer author="Neve Gaffaney" date="2024" link="https://www.craighead.school.nz/" organisation="Craighead Diocesan School" />

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
