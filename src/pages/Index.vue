<template>
  <LayoutHero>
    <template slot="hero">
      <hero-container :bg="heroBG">
        <h1 class="text-6xl">Complex viable human.</h1>
      </hero-container>
    </template>
    <div class="flex flex-row bg-white shadow-lg rounded-lg">
      <div
        class="flex-none border-solid border-2 border-teal-500 m-10 bg-black-900 overflow-hidden rounded-full h-64 w-64"
      >
        <g-image
          src="~/assets/img/josh-graffiti.jpg"
          width="500"
          height="500"
          fit="cover"
          >Me</g-image
        >
      </div>

      <!-- How can I get this to sit below???
      <div class="flex-col">
          <h3> Friends and Affiliations </h3>
            Hackalong
            Liminal Village
            MicroSolidarity
            The Dingle Group
            Neon Flea Circus
            RatPark
      </div> -->
      <div class="flex-1 pt-10 pr-10 pb-10 font-sans">
        <h2 id="About">
          Ontological Design and Methodology Dev.
        </h2>
        <p></p>
        <p>
          Given this personal website is intended as a form of public interface
          I'll try to be as straight forward as I can with the philosophical
          impasse of "beingness" or the spiritual non-sequiter of "identity";
          phrasing my answer in a creative way I tend to describe myself as a
          generalised specialist working the dials of spaceship earth to help us
          navigate hazards of the anthropocene.
        </p>
        <p>
          Personally speaking I've embarked on (and am deeply committed to) an
          inner search which has thus far led to the discovery of many
          expressive capacities; art, music, poetry and creative writing. Having
          experienced and found so much within myself already, I notice and
          percieve things that most people don't pickup on. Consequentially I
          have a deep need to hang around and work with interesting and
          intelligent people who help fulfill my primitive desire for novelty
          and flow.
        </p>
        <p>
          At times, I can appear to be an etreamly cerebral cat and I've been
          told that this can seem intelecutally intimidating - despite the fact
          that I actually hold a pretty low bar. I'm often exploring epistemic
          models like semantics, pragmatics and general systematics. Discovering
          new domains of science (rational knowlege) and philosophy (emperical
          wisdom) are general passions and I love to juggle the most abstract
          symbol systems I can possibly find. These engagements have helped me
          develop some prety interesting noetic capabilities that I can call on
          to make sense of disperate and unfamilliar fields. Ordo ab Chao.
        </p>
        <p>
          My world view is requires a lot of paradexterity to comprehend. This
          gets called many things but nearly always contradicts itself (such as
          'the tao which cannot be named'). It's maximally minimal and minimally
          maximal, openly skeptical, inter-subjective, lovingly protective and
          often considered heretical. Some writing that I've enjoyed which
          embodies the flavour well can be found at
          <a ref="embodies it well in its expression">metamoderna.org</a>.
        </p>
        <p>
          Climbing down form the meta-mental and showing up as an embodied being
          here on earth though; I enjoy various forms of coordinated movements,
          excersises and myofascial mobilisations. In particular; board-sports,
          dancing, circus arts, swimming, surfing, playing musical instruments
          and long walks on the beach/mountains!
        </p>
        <p>
          My background has been trecherous; I've been the English person in
          Ireland and the Irish person in England. I don't like the tribalism of
          in/out groups yet admit the necessity of flags in a world thats still
          dealing with its neo-colonialist issues... In other words, when the
          aliens come I'll cease to identify as a citizen of earth and elect
          myself as a cosmic orphan.
        </p>
        <p>
          Actually... given we're all connected as part of a giiiiiiant
          autopoietic network called "life" (that is cognizient and conscious on
          every level); I might as well cease to identity at all! ✨
        </p>
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
    title: "Home",
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
            "blanditiis animi sequi beatae nisi facilis maiores voluptate doloribus necessitatibus est laborum vel. Quasi, nisi. ",
        },
        {
          title: "hello world",
          img: "card.png",
          extraClassImg: "h-64",
          content:
            "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Corporis neque, mollitia a magni ducimus aliquam blanditiis animi sequi beatae nisi facilis maiores voluptate doloribus necessitatibus est laborum vel. Quasi, nisi. ",
        },

        {
          title: "No image here",
          content:
            "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Corporis neque, mollitia a magni ducimus aliquam blanditiis animi sequi beatae nisi facilis maiores voluptate doloribus necessitatibus est laborum vel. Quasi, nisi. ",
        },
      ],
    };
  },
};
</script>

<style lang="scss"></style>
