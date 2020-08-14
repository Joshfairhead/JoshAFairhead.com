<template>
  <LayoutHero>
    <template slot="hero">
      <hero-container :bg="heroBG">
        <h1 class="text-6xl">Balancing Natural Chaos</h1>
      </hero-container>
    </template>
    <div class="flex flex-row bg-white shadow-lg rounded-lg">
      <div class="flex-none m-10 bg-black-900 rounded-full h-64 w-64"><!--This should be a picture, how to embed images--></div>
      <!-- Why wont you sit below???
      <div class="flex-col">
          <h3> Friends and Affiliations </h3>
            Hackalong
            Liminal Village
            MicroSolidarity
            The Dingle Group
            Neon Flea Circus
            RatPark
      </div> -->
      <div class="flex-1 pt-10 pr-10 pb-10">
        <h2 id="About">About me - Sensemaker / Lunatic 🌙</h2>
        <p>Identity... hmmm, tough one to express generically for a website but I'll try! </p>
        <p> Ok - so as a singular entity I'd consider my thought as integral or non-dual, my inner landscape is often exploring the philosophy of language and playing with symbols which I consider an expressive capacity. As an embodied being I enjoy various forms of coordinated movements, excersise and myofascial mobilisations - such as board-sports, dancing, circus arts, swimming, surfing, playing musical instruments or long walks on the beach/mountains!</p>
        <p>As a collective being I tend to relate well with divergent communities - those who are working on something radically different from the current status quo of extraction and zero sum games. The Tao which can be named is not the eternal Tao, so I'll avoid trying to articulate the intereior collective any further :). Lastly we have the exterior collective to identitfy with and for me thats spaceship earth. Nationalisim has never worked in my favour, I've been the English person in Ireland and the Irish person in England - tribalistic in/out groups tend to bring issues (though admittedly they can engender a sense of belonging). When the aliens come I'll cease to identify as a citizen of earth and instead as one of the syntropic Kosmos.</p>
        <p>In that regard, given we're likeley connected as part of a giant autopoietic network that is cognizient and conscious on every level; I might as well cease to identity at all! ✨</p>
      </div>
    </div>
    
    <!-- ========================== CARDS
    <div class="flex flex-wrap my-10">
      card v-for="card in cards" v-bind="card" :key="card.title"></card> 
    </div>
    -->
  </LayoutHero>
</template>

<script>
export default {
  metaInfo: {
    title: "Home"
  },

  data() {
    return {
      heroBG: "waterfractal.jpg",
      cards: [
        {
          title: "this one has a link",
          img: "https://picsum.photos/600/300",
          link: "https://vuejs.org/v2/guide/components-props.html",
          content:
            "blanditiis animi sequi beatae nisi facilis maiores voluptate doloribus necessitatibus est laborum vel. Quasi, nisi. "
        },
        {
          title: "hello world",
          img: "card.png",
          extraClassImg: "h-64",
          content:
            "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Corporis neque, mollitia a magni ducimus aliquam blanditiis animi sequi beatae nisi facilis maiores voluptate doloribus necessitatibus est laborum vel. Quasi, nisi. "
        },

        {
          title: "No image here",
          content:
            "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Corporis neque, mollitia a magni ducimus aliquam blanditiis animi sequi beatae nisi facilis maiores voluptate doloribus necessitatibus est laborum vel. Quasi, nisi. "
        }
      ]
    };
  }
};
</script>

<style lang="scss">
</style>
