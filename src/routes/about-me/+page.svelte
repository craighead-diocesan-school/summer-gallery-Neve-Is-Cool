<script>
  import Header from "$lib/Header.svelte"
  import Footer from "$lib/Footer.svelte"
  import Nav from "$lib/Nav.svelte"
  import Card from "$lib/Card.svelte"
</script>

<Header title="About me" subtitle="And my Card" />

<Nav />

<main>
  <section class="about-me">
    <h2>About me</h2>

    <p>Hi I'm Neve and I am taking level 2 digi.</p>
    <p>
      I'm sure there is other information about me, but none that I really care to spend my time writing about given that I keep forgetting to do my Chemistry homework, so I will be doing that now. There is actually a lot I need to remember for my Chemistry internal next Thursday, so I am going to vaguely attempt to write that down now, so that I can remember everything I need to do. When given the reaction, I need to look at the sheet, which I also need to remember to photocopy for Olivia, to see what the reactants and products are, and write and balance each half equation. Once I have done that I need to find the oxidation numbers for the current half equation, and then write down two reasons why it is either oxidised or reduced. The two reasons will be the number of electrons each total solution loses or gains and the second reason will be how the oxidation number reflects this, and how it impacts each induvidual reacting atom. Then I need to repeat this process for another half
      equation, before balancing out the e- to finalise and balance the entire equation. Then I will need to describe the reaction, explaining with the colours and states of matter of each substance, and how the final solution appears and why.
    </p>
  </section>
</main>

<Card />

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
    color: rgb(45, 67, 42);
    border-top: 2px solid;
    padding-top: 50px;
    text-align: center;
  }

  p {
    margin-bottom: 20px;
    color: rgb(45, 67, 42);
    margin-left: 100px;
    margin-right: 100px;
  }
</style>
