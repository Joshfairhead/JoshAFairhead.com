<template>
  <LayoutHero>
    <template slot="hero">
      <hero-container :bg="heroBG">
        <h1 class="text-6xl">Balancing Natural Chaos</h1>
      </hero-container>
    </template>

    <div class="flex flex-wrap my-10">
      <card v-for="card in cards" v-bind="card" :key="card.title"></card>
    </div>

    <div class="bg-white shadow-lg p-10">
      <h2>About - sensemaker/lunatic</h2>
      <p>
        Identity... hmmm, tough one to express generically but I'll try! Ok - so as a singular entity I'd consider my thought as integral or non-dual, my inner landscape is often exploring the philosophy of language and playing with symbols which I interpret as expressive capacity. As an embodied being I enjoy various forms of coordinated movements, excersise and myofascial mobilisations - such as board-sports, dancing, circus arts, swimming, surfing, playing musical instruments or long walks on the beach/mountains!
      </p>
      <p>
        As a collective being I tend to relate with divergent communities - those who are working on something radically different from the current status quo of extraction and zero sum games. The Tao which can be named is not the eternal Tao, so I'll avoid trying to articulate the intereior collective any further :). Lastly we have the exterior collective to identitfy with and for me thats spaceship earth. Nationalisim has never worked in my favour, I've been the English person in Ireland and the Irish person in England - tribalistic in/out groups tend to bring issues (though admittedly they can engender a sense of belonging). When the aliens come I'll cease to identify as a citizen of earth and instead as one of the syntropic Kosmos.
      </p>
      <p>
        In that regard, given we're likeley connected as part of a giant autopoietic network that is cognizient and conscious on every level, I might as well cease to identity at all! ✨
      </p>

      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam lacinia egestas vehicula. Nunc congue augue nunc. Nam fringilla ornare ante a ultricies. Sed tincidunt consequat lorem at lacinia. Donec sit amet commodo augue, sed lacinia arcu. Quisque lacinia risus egestas viverra tincidunt. Donec molestie tellus vel nunc euismod, in suscipit risus fringilla. Nunc congue tincidunt nisi sed eleifend. Nam interdum mauris sed massa viverra, eu porttitor velit ullamcorper. Mauris ac nibh fermentum, faucibus metus eu, placerat ipsum.
        Nunc nec nisi et mauris finibus ultrices nec in neque. Vivamus ut eleifend arcu. Morbi laoreet malesuada congue. Nam mattis tristique finibus. Nulla mattis rhoncus augue in tincidunt. Proin nec lacus ac urna vulputate euismod. Praesent sit amet risus elit. Nulla eget orci vel arcu vestibulum consectetur vel sit amet massa. Nullam congue tincidunt purus, at gravida eros. Donec vitae odio massa. Sed condimentum lectus sit amet arcu luctus, eget suscipit mauris pretium. Sed ac egestas neque. Mauris tortor velit, venenatis et justo sit amet, venenatis lacinia tortor. Nunc nec laoreet magna.
        Vestibulum ac viverra enim. Proin vitae imperdiet tortor. Fusce sed ex pharetra mi elementum efficitur. Sed turpis ligula, lacinia id imperdiet sit amet, viverra eget erat. Maecenas ullamcorper, mi eu pulvinar vulputate, odio lectus fringilla risus, id semper ante nunc in libero. Ut id ipsum augue. Nulla condimentum tellus leo, sed mattis mauris accumsan elementum. Ut aliquet posuere ante sit amet varius. Mauris luctus sed elit nec consectetur. Pellentesque bibendum tellus a venenatis mollis.
        Ut id blandit nibh. Nulla facilisi. Vestibulum in diam varius, ultricies erat id, interdum tellus. Phasellus in purus ut dolor pretium molestie ac at purus. Nullam ullamcorper nec dui eu rutrum. Proin porttitor odio eget odio feugiat blandit ut sed nibh. Nunc sollicitudin quis turpis vitae malesuada. Vivamus dapibus consectetur erat eget lacinia. Nam vel urna lacus. Suspendisse euismod lorem vitae mi convallis, ut interdum enim feugiat. In scelerisque tortor eu elit pharetra sagittis. Sed semper libero ut scelerisque luctus. Morbi vitae dui ex. Phasellus risus odio, laoreet non risus at, placerat consequat tortor. Proin vitae massa iaculis, posuere quam nec, ultrices ante. Nulla tincidunt cursus nibh vel elementum.
        Proin et mauris erat. Nulla ut lacinia leo. Cras sollicitudin diam pellentesque, molestie libero vel, ultricies justo. Duis ut volutpat risus. Donec nec nulla in erat tempus molestie eget nec purus. Cras blandit velit at lorem venenatis, ut condimentum dui luctus. Nullam ornare porttitor fringilla. Donec mauris sapien, imperdiet in magna eget, pellentesque faucibus urna. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec iaculis lorem in ante bibendum, at congue enim condimentum. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Fusce non diam bibendum, rhoncus lacus et, sagittis lorem.
      </p>
      <h3 id="details">Details</h3>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam lacinia egestas vehicula. Nunc congue augue nunc. Nam fringilla ornare ante a ultricies. Sed tincidunt consequat lorem at lacinia. Donec sit amet commodo augue, sed lacinia arcu. Quisque lacinia risus egestas viverra tincidunt. Donec molestie tellus vel nunc euismod, in suscipit risus fringilla. Nunc congue tincidunt nisi sed eleifend. Nam interdum mauris sed massa viverra, eu porttitor velit ullamcorper. Mauris ac nibh fermentum, faucibus metus eu, placerat ipsum.
        Nunc nec nisi et mauris finibus ultrices nec in neque. Vivamus ut eleifend arcu. Morbi laoreet malesuada congue. Nam mattis tristique finibus. Nulla mattis rhoncus augue in tincidunt. Proin nec lacus ac urna vulputate euismod. Praesent sit amet risus elit. Nulla eget orci vel arcu vestibulum consectetur vel sit amet massa. Nullam congue tincidunt purus, at gravida eros. Donec vitae odio massa. Sed condimentum lectus sit amet arcu luctus, eget suscipit mauris pretium. Sed ac egestas neque. Mauris tortor velit, venenatis et justo sit amet, venenatis lacinia tortor. Nunc nec laoreet magna.
        Vestibulum ac viverra enim. Proin vitae imperdiet tortor. Fusce sed ex pharetra mi elementum efficitur. Sed turpis ligula, lacinia id imperdiet sit amet, viverra eget erat. Maecenas ullamcorper, mi eu pulvinar vulputate, odio lectus fringilla risus, id semper ante nunc in libero. Ut id ipsum augue. Nulla condimentum tellus leo, sed mattis mauris accumsan elementum. Ut aliquet posuere ante sit amet varius. Mauris luctus sed elit nec consectetur. Pellentesque bibendum tellus a venenatis mollis.
        Ut id blandit nibh. Nulla facilisi. Vestibulum in diam varius, ultricies erat id, interdum tellus. Phasellus in purus ut dolor pretium molestie ac at purus. Nullam ullamcorper nec dui eu rutrum. Proin porttitor odio eget odio feugiat blandit ut sed nibh. Nunc sollicitudin quis turpis vitae malesuada. Vivamus dapibus consectetur erat eget lacinia. Nam vel urna lacus. Suspendisse euismod lorem vitae mi convallis, ut interdum enim feugiat. In scelerisque tortor eu elit pharetra sagittis. Sed semper libero ut scelerisque luctus. Morbi vitae dui ex. Phasellus risus odio, laoreet non risus at, placerat consequat tortor. Proin vitae massa iaculis, posuere quam nec, ultrices ante. Nulla tincidunt cursus nibh vel elementum.
        Proin et mauris erat. Nulla ut lacinia leo. Cras sollicitudin diam pellentesque, molestie libero vel, ultricies justo. Duis ut volutpat risus. Donec nec nulla in erat tempus molestie eget nec purus. Cras blandit velit at lorem venenatis, ut condimentum dui luctus. Nullam ornare porttitor fringilla. Donec mauris sapien, imperdiet in magna eget, pellentesque faucibus urna. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec iaculis lorem in ante bibendum, at congue enim condimentum. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Fusce non diam bibendum, rhoncus lacus et, sagittis lorem.
      </p>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam lacinia egestas vehicula. Nunc congue augue nunc. Nam fringilla ornare ante a ultricies. Sed tincidunt consequat lorem at lacinia. Donec sit amet commodo augue, sed lacinia arcu. Quisque lacinia risus egestas viverra tincidunt. Donec molestie tellus vel nunc euismod, in suscipit risus fringilla. Nunc congue tincidunt nisi sed eleifend. Nam interdum mauris sed massa viverra, eu porttitor velit ullamcorper. Mauris ac nibh fermentum, faucibus metus eu, placerat ipsum.
        Nunc nec nisi et mauris finibus ultrices nec in neque. Vivamus ut eleifend arcu. Morbi laoreet malesuada congue. Nam mattis tristique finibus. Nulla mattis rhoncus augue in tincidunt. Proin nec lacus ac urna vulputate euismod. Praesent sit amet risus elit. Nulla eget orci vel arcu vestibulum consectetur vel sit amet massa. Nullam congue tincidunt purus, at gravida eros. Donec vitae odio massa. Sed condimentum lectus sit amet arcu luctus, eget suscipit mauris pretium. Sed ac egestas neque. Mauris tortor velit, venenatis et justo sit amet, venenatis lacinia tortor. Nunc nec laoreet magna.
        Vestibulum ac viverra enim. Proin vitae imperdiet tortor. Fusce sed ex pharetra mi elementum efficitur. Sed turpis ligula, lacinia id imperdiet sit amet, viverra eget erat. Maecenas ullamcorper, mi eu pulvinar vulputate, odio lectus fringilla risus, id semper ante nunc in libero. Ut id ipsum augue. Nulla condimentum tellus leo, sed mattis mauris accumsan elementum. Ut aliquet posuere ante sit amet varius. Mauris luctus sed elit nec consectetur. Pellentesque bibendum tellus a venenatis mollis.
        Ut id blandit nibh. Nulla facilisi. Vestibulum in diam varius, ultricies erat id, interdum tellus. Phasellus in purus ut dolor pretium molestie ac at purus. Nullam ullamcorper nec dui eu rutrum. Proin porttitor odio eget odio feugiat blandit ut sed nibh. Nunc sollicitudin quis turpis vitae malesuada. Vivamus dapibus consectetur erat eget lacinia. Nam vel urna lacus. Suspendisse euismod lorem vitae mi convallis, ut interdum enim feugiat. In scelerisque tortor eu elit pharetra sagittis. Sed semper libero ut scelerisque luctus. Morbi vitae dui ex. Phasellus risus odio, laoreet non risus at, placerat consequat tortor. Proin vitae massa iaculis, posuere quam nec, ultrices ante. Nulla tincidunt cursus nibh vel elementum.
        Proin et mauris erat. Nulla ut lacinia leo. Cras sollicitudin diam pellentesque, molestie libero vel, ultricies justo. Duis ut volutpat risus. Donec nec nulla in erat tempus molestie eget nec purus. Cras blandit velit at lorem venenatis, ut condimentum dui luctus. Nullam ornare porttitor fringilla. Donec mauris sapien, imperdiet in magna eget, pellentesque faucibus urna. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec iaculis lorem in ante bibendum, at congue enim condimentum. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Fusce non diam bibendum, rhoncus lacus et, sagittis lorem.
      </p>
    </div>
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
