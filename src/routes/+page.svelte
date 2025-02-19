<script>
  import Header from "$lib/Header.svelte"
  import Footer from "$lib/Footer.svelte"
  import Nav from "$lib/Nav.svelte"
  import Image from "$lib/Image.svelte"
</script>

<Header title="Summer Gallery" subtitle="My summer and some pictures" />

<Nav />
<h2>My Summer 2025!!</h2>

<main>
  <p>My summer was good, although it passed very quickly. After I completed my exams, my year level was given a week off of school, which worked out perfectly for me. This is because I had planned since the beginning of the year to go to Australia from the Thursday of my week off to the following Monday. On the Monday night, I had a celebration with my friends for finishing exams at Zoe’s, and on Wednesday I went to Christchurch. On Thursday I went to Australia in the early morning. In Australia, it was my uncle's 50th birthday celebrations, I spent time with my cousins, and I got lots of my Christmas shopping done.</p>

  <p>The Legitimate holidays started the week after because school had finished. In December, I did not achieve much. The weather was almost always horrendous, and so if I wasn’t hanging out with my friends, I wasn’t doing much else. Christmas was good, but we had it a day early because my brother had shift work on Christmas day, which was a bit odd.</p>

  <p>The period between Christmas day and New Year’s was both calming and confusing, I never knew what day it was, how long it had been since anything, and I lived watching movies on my couch. On the 29th, I went with my parents and my friend Zara, and spent way too much money, as I kept using my card and continued forgetting about my vouchers and cash from Christmas. Then after spending the night in Christchurch, we drove home and Zara stayed at mine for another night before being picked up the next day. New Year’s was just a nice evening with some friends having dinner at mine and then we went to the bay. We were in a line for a ride when the new year came.</p>

  <p>In the new year, I started a Harvard Cs50x computer science course, and that took up most of my spare time. It was then Ruby’s birthday which was lots of fun and there were a lot of people. It was nice to see all my friends since the new year. If you have ever seen the TV show Severance, my entire family loves it, and because of the new release of season 2, an episode at a time, we (my family and my brother's girlfriend) all dressed up as characters from the show and had a viewing party. I also worked a lot during this time, for nearly a week straight, and was even given the responsibility to open up the cafe for the first time.</p>

  <p>I then went to Twizel which is where my grandparents were at the time. I spent two nights in Twizel and then got up early the next day to go to Cromwell. In Twizel, I went to Lake Ohau three times in the span of one day. In Cromwell, my dad, brother and I did the highlands go karting, and then we went to Mt Difficulty Vineyard as a celebration of our work throughout the year. After spending a night in Cromwell, my brother and I drove back to Twizel to pick up our stuff and then drove home the same day. This was a very long trip, and so we decided to make him a playlist for his upcoming 18th party. That evening I had Lucy’s birthday party which was a lot of fun, and I then worked for the remainder of the holidays.</p>
</main>

<div>
  <Image src="New-years.JPG" alt="Neve with friends on New Year's Eve" caption="New Year's Eve with friends" />
  <Image src="Zoe's.JPG" alt="Neve with friends at a friends house" caption="Zoe's with lots of friends" />
</div>

<Footer author="Neve Gaffaney" date="2024" link="https://www.craighead.school.nz/" organisation="Craighead Diocesan School" />

<style>
  div {
    display: flex;
    justify-content: space-around;
    background-color: rgb(192, 214, 189);
  }

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
