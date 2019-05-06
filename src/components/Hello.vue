<template>
<b-container class="mx-auto">
  <div class="hello mx-auto">
    <b-row>
      <b-col cols="12">
    <a href="http://www.glitter-graphics.com/myspace/text_generator.php" target=_blank><img src="http://text.glitter-graphics.net/heart/h.gif" border=0><img src="http://text.glitter-graphics.net/heart/a.gif" border=0><img src="http://text.glitter-graphics.net/heart/p.gif" border=0><img src="http://text.glitter-graphics.net/heart/p.gif" border=0><img src="http://text.glitter-graphics.net/heart/y.gif" border=0><img src="http://dl3.glitter-graphics.net/empty.gif" width=20 border=0><img src="http://text.glitter-graphics.net/heart/b.gif" border=0><img src="http://text.glitter-graphics.net/heart/i.gif" border=0><img src="http://text.glitter-graphics.net/heart/r.gif" border=0><img src="http://text.glitter-graphics.net/heart/t.gif" border=0><img src="http://text.glitter-graphics.net/heart/h.gif" border=0><img src="http://text.glitter-graphics.net/heart/d.gif" border=0><img src="http://text.glitter-graphics.net/heart/a.gif" border=0><img src="http://text.glitter-graphics.net/heart/y.gif" border=0><img src="http://dl3.glitter-graphics.net/empty.gif" width=20 border=0><img src="http://text.glitter-graphics.net/heart/s.gif" border=0><img src="http://text.glitter-graphics.net/heart/k.gif" border=0></a>
      </b-col>
    </b-row>
    <b-row class="pt-4">
      <b-col lg="3"><b-img src="./static/baby-cat-l.gif" class="babycats" fluid/></b-col>
    <b-col lg="6"><b-img src="./static/multiplying-sk.gif" class="multiply" fluid-grow/></b-col>
    <b-col lg="3"><b-img src="./static/baby-cat-r.gif" class="babycats" fluid/></b-col>

    </b-row>
    <b-row class="p-3">
      <b-col cols="12"><h1>HAPPY BIRTHDAY, BUNNY! WE ALL LOVE YOU SO MUCH AND WANT TO CELEBRATE YOU!</h1></b-col>
    </b-row>
    <b-row class="pb-3">
      <b-col><b-img src="./static/bunny-hop.gif"/></b-col>
    </b-row>
    <b-row class="p-3">
      <b-col lg="6">
      <b-card class="cards">
      <h2>FROM ZOE</h2>
      <iframe src="https://player.vimeo.com/video/334082651" frameborder="0" allow="autoplay; fullscreen" allowfullscreen fluid-grow height="auto" width="auto"></iframe>
      </b-card>
      </b-col>
      <b-col lg="6">
      <b-card class="cards">
      <h2>FROM SIMON</h2>
      <iframe src="https://player.vimeo.com/video/334082799" frameborder="0" allow="autoplay; fullscreen" allowfullscreen fluid-grow height="auto" width="auto"></iframe>
      </b-card>
      </b-col>
    </b-row>
    <b-row class="p-3">
      <b-col lg="6">
        <b-card class="cards">
          <h2>FROM D'ANGELO MADSEN</h2>
        <b-carousel
      id="carousel-1"
      class="carousel"
      v-model="slide"
      :interval="50000"
      controls
      indicators
      background="#ababab"
      style="text-shadow: 1px 1px 2px #333; max-height: 50rem;"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
      fluid-grow
    >
      <!-- Text slides with image -->
      <b-carousel-slide img-src="./static/100_0709.jpg"></b-carousel-slide>

      <!-- Slides with custom text -->
      <b-carousel-slide img-src="./static/100_0710.jpg">
      </b-carousel-slide>

      <!-- Slides with image only -->
      <b-carousel-slide img-src="./static/100_0711.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0710.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0721.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0723.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0724.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0725.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0726.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0729.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0731.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0732.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0733.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0735.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0736.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0737.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0738.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0739.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0740.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0741.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0744.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0745.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0746.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0747.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0750.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0751.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0753.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0754.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0755.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0758.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0751.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0753.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0754.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0755.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0758.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0760.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0761.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0762.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/100_0763.jpg"></b-carousel-slide>
</b-carousel>
    </b-card>
      </b-col>
       <b-col lg="6">
      <b-card class="cards">
      <h2>FROM CARRIE</h2>
     <b-carousel
      id="carousel-2"
      class="carousel"
      v-model="slide"
      :interval="50000"
      controls
      indicators
      background="#ababab"
      style="text-shadow: 1px 1px 2px #333;"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
      fluid-grow
    >
     

      <!-- Slides with image only -->
      <b-carousel-slide img-src="./static/image4.jpg" class="slides"></b-carousel-slide>
      <b-carousel-slide img-src="./static/image3.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/image2.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/image1.jpg"></b-carousel-slide>
     
</b-carousel>
      </b-card>
      </b-col>
    </b-row>
    <b-row class="p-3">
      <b-col lg="6">
      <b-card class="cards">
      <h2>FROM OWEN</h2>
      <b-img src="./static/the-kellies-shipwreck.gif" fluid/>
      </b-card>
      </b-col>
      <b-col lg="6">
      <b-card class="cards">
      <h2>FROM EMMETT</h2>
     <b-carousel
      id="carousel-3"
      class="carousel"
      v-model="slide"
      :interval="50000"
      controls
      indicators
      background="#ababab"
      style="text-shadow: 1px 1px 2px #333;"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
      fluid-grow
    >
  
      <!-- Slides with image only -->
      <b-carousel-slide img-src="./static/img_1527.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/img_1916.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/img_2026.jpg"></b-carousel-slide>
     
</b-carousel>
<div class="pt-3">
<iframe src="https://player.vimeo.com/video/334345019" height="auto" width="auto" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>
<p><a href="https://vimeo.com/334345019">Emmett</a> from <a href="https://vimeo.com/user39447217">jaffa</a> on <a href="https://vimeo.com">Vimeo</a>.</p>
</div>
      </b-card>
      </b-col>
      </b-row>
  </div>
  <b-row class="p-3">
      <b-col lg="6">
      <b-card class="cards">
      <h2>FROM NASTALIE</h2>
     <b-carousel
      id="carousel-4"
      class="carousel"
      v-model="slide"
      :interval="50000"
      controls
      indicators
      background="#ababab"
      style="text-shadow: 1px 1px 2px #333;"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
      fluid-grow
      no-animation
    >
  
      <!-- Slides with image only -->
      <b-carousel-slide img-src="./static/nasty1.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/nasty2.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/nasty3.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/nasty4.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/nasty5.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/nasty6.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/nasty7.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/nasty8.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/nasty9.jpg"></b-carousel-slide>
      <b-carousel-slide img-src="./static/nasty10.jpg"></b-carousel-slide>
     
</b-carousel>
      </b-card>
      </b-col>
  </b-row>
  </b-container>
</template>

<script>
  export default {
    data () {
      return {
        slide: 0,
        sliding: null
      }
    },
    methods: {
      onSlideStart (slide) {
        this.sliding = true
      },
      onSlideEnd (slide) {
        this.sliding = false
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
  font-family: 'Press Start 2P', cursive;
  color: #FF6D7C;
}

.babycats {
  max-height: 10rem;
}
.slides {
  max-height: 20rem;
}
.multiply {
  min-width: 50%;
}
ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

.cards {
  background-color: #4BB8CC
}
/* a {
  color: #42b983;
} */

</style>
