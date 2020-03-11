<template>
  <div class="fonts-main">
    <div class="main-color-page color-main2-bg">
      <div class="title one-animate-zoom">Picking Fonts</div>
    </div>
    <div class="psychological-font-effect">
      <div class="psychological-font-effect-title color-main2 one-xxxlarge one-card">
        Font's psychological effect
      </div>
      <div class="psychological-font-effect-desc">
        Every font has a unique personality and purpose.
        While working on a project, it’s imperative to know which font
        matches the intended tone of communication. Serif fonts portray
        tradition, sophistication and a formal tone. Sans serif fonts are modern,
        humanist and neutral. Slab serifs are bold and contemporary. Script fonts are elegant
        , classic, stylish and formal.<br/>
      </div>
      <div class="fonts-details">
        <div class="fonts-details-title one-xxlarge color-main2">
          Serif Fonts
        </div>
        <div class="fonts-details-type">
          <ul class="one-ul one-border">
            <li class="fonts-details-list">Tradition - <a href="">TIMES NEW ROMAN</a></li>
            <li class="fonts-details-list">Respectable - <a href="">TRAJAN</a></li>
            <li class="fonts-details-list">Reliable - <a href="">BASKERVILLE</a></li>
            <li class="fonts-details-list">Comfort - <a href="">GEORGIA ITALIC</a></li>
          </ul>
        </div>
      </div>
      <div class="fonts-details">
        <div class="fonts-details-title one-xxlarge color-main2">
          Sans Serif Fonts
        </div>
        <div class="fonts-details-type">
          <ul class="one-ul one-border">
            <li class="fonts-details-list">Stability - <a href="">HELVITICA BOLD</a></li>
            <li class="fonts-details-list">Objective - <a href="">FRANKLIN GOTHIC</a></li>
            <li class="fonts-details-list">Clean - <a href="">CALIBRI</a></li>
            <li class="fonts-details-list">Modern - <a href="">MYRIAD ITALIC</a></li>
          </ul>
        </div>
      </div>
      <div class="fonts-details">
        <div class="fonts-details-title one-xxlarge color-main2">
          Modern Fonts
        </div>
        <div class="fonts-details-type">
          <ul class="one-ul one-border">
            <li class="fonts-details-list">Strong - <a href="">FUTURA</a></li>
            <li class="fonts-details-list">Progressive - <a href="">ITC AVANT GARDE EXTRA LIGHT</a></li>
            <li class="fonts-details-list">Stylish - <a href="">DIDOT ITALIC</a></li>
            <li class="fonts-details-list">Chic - <a href="">CENTURY GOTHIC</a></li>
          </ul>
        </div>
      </div>
      <div class="fonts-details">
        <div class="fonts-details-title one-xxlarge color-main2">
          Display Fonts
        </div>
        <div class="fonts-details-type">
          <ul class="one-ul one-border">
            <li class="fonts-details-list">Friendly - <a href="">COOPER</a></li>
            <li class="fonts-details-list">Unique - <a href="">SPACEAGE ROUND</a></li>
            <li class="fonts-details-list">Expressive - <a href="">VALENCIA</a></li>
            <li class="fonts-details-list">Amusing - <a href="">GIDDYUP</a></li>
          </ul>
        </div>
      </div>
      <div class="fonts-details">
        <div class="fonts-details-title one-xxlarge color-main2">
          Script Fonts
        </div>
        <div class="fonts-details-type">
          <ul class="one-ul one-border">
            <li class="fonts-details-list">Elegance - <a href="">BICKHAM SCRIPT</a></li>
            <li class="fonts-details-list">Affectionate - <a href="">EDWARDIAN SCRIPT</a></li>
            <li class="fonts-details-list">Creativity - <a href="">LAVANDERIA</a></li>
          </ul>
        </div>
      </div>
    </div>
    <div class="more-fonts one-container">
      <div class="more-fonts-title one-xxxlarge one-card color-main2">
        Some of most used fonts
      </div>
      <FontsCard v-for="(font,idx) in fonts" :key="idx" class="fonts-card" :title='(idx+1) + ". " + font.title' :thumbnail="font.thumbnail" :link="font.link" />
    </div>
  </div>
</template>

<script>
import FontsCard from '~/components/FontsCard'

export default {
  data() {
    return {
    fonts : [
      {
        title : 'Roboto',
        thumbnail : "https://www.elegantthemes.com/blog/wp-content/uploads/2018/10/roboto-reg.png",
        link : 'https://fonts.google.com/specimen/Roboto'
      },
      {
        title : 'Playfair Display',
        thumbnail : "https://www.elegantthemes.com/blog/wp-content/uploads/2018/10/playfair.jpg",
        link : 'https://fonts.google.com/specimen/Playfair+Display'
      },
      {
        title : 'Open Sans',
        thumbnail : "https://www.elegantthemes.com/blog/wp-content/uploads/2018/10/open-sans.jpg",
        link : 'https://fonts.google.com/specimen/Open+Sans'
      },
      {
        title : 'Lato',
        thumbnail : "https://www.elegantthemes.com/blog/wp-content/uploads/2018/10/lato.jpg",
        link : 'https://fonts.google.com/specimen/Lato'
      },
      {
        title : 'Noto Sans',
        thumbnail : "https://www.elegantthemes.com/blog/wp-content/uploads/2018/10/noto-sans.jpg",
        link : 'https://fonts.google.com/specimen/Roboto'
      },
      {
        title : 'PT Sans',
        thumbnail : "https://www.elegantthemes.com/blog/wp-content/uploads/2018/10/pt-sans.jpg",
        link : 'https://fonts.google.com/specimen/PT+Sans'
      },
      {
        title : 'Nunito Sans',
        thumbnail : "https://www.elegantthemes.com/blog/wp-content/uploads/2018/10/nunito-sans.jpg",
        link : 'https://fonts.google.com/specimen/Nunito+Sans'
      },
      {
        title : 'Josefin Sans',
        thumbnail : "https://www.elegantthemes.com/blog/wp-content/uploads/2018/10/josefin-sans.jpg",
        link : 'https://fonts.google.com/specimen/Josefin+Sans'
      },
      {
        title : 'Ubuntu',
        thumbnail : "https://www.elegantthemes.com/blog/wp-content/uploads/2018/10/ubuntu.jpg",
        link : 'https://fonts.google.com/specimen/Ubuntu'
      },
      {
        title : 'Muli',
        thumbnail : "https://www.elegantthemes.com/blog/wp-content/uploads/2018/10/muli.jpg",
        link : 'https://fonts.google.com/specimen/Muli'
      },
      {
        title : 'Oxygen',
        thumbnail : "https://www.elegantthemes.com/blog/wp-content/uploads/2018/10/oxygen.jpg",
        link : 'https://fonts.google.com/specimen/Oxygen'
      },
      {
        title : 'Noto Serif',
        thumbnail : "https://www.elegantthemes.com/blog/wp-content/uploads/2018/10/noto-serif.jpg",
        link : 'https://fonts.google.com/specimen/Noto+Serif'
      },
      {
        title : 'Nunito',
        thumbnail : "https://www.elegantthemes.com/blog/wp-content/uploads/2018/10/nunito-reg.png",
        link : 'https://fonts.google.com/specimen/Nunito'
      },
      {
        title : 'Abril Fatface',
        thumbnail : "https://www.elegantthemes.com/blog/wp-content/uploads/2018/10/abril-fatface.jpg",
        link : 'https://fonts.google.com/specimen/Abril+Fatface'
      },
      {
        title : 'Exo 2',
        thumbnail : "https://www.elegantthemes.com/blog/wp-content/uploads/2018/10/exo-2.jpg",
        link : 'https://fonts.google.com/specimen/Exo+2'
      },
      {
        title : 'Quicksand',
        thumbnail : "https://www.elegantthemes.com/blog/wp-content/uploads/2018/10/quicksand.jpg",
        link : 'https://fonts.google.com/specimen/Quicksand'
      },
      {
        title : 'Cooper Hewitt',
        thumbnail : "https://www.elegantthemes.com/blog/wp-content/uploads/2018/10/cooper-hewitt.jpg",
        link : 'https://www.fontsquirrel.com/fonts/cooper-hewitt'
      },
      {
        title : 'Ostrich Sans',
        thumbnail : "https://www.elegantthemes.com/blog/wp-content/uploads/2018/10/ostrich-sans.jpg",
        link : 'https://www.fontsquirrel.com/fonts/ostrich-sans'
      },
      {
        title : 'IBM Plex Sans',
        thumbnail : "https://www.elegantthemes.com/blog/wp-content/uploads/2018/10/ibm-plex.jpg",
        link : 'https://fonts.google.com/specimen/IBM+Plex+Sans'
      },
      {
        title : 'Cormonant',
        thumbnail : "https://www.elegantthemes.com/blog/wp-content/uploads/2018/10/cormonant.jpg",
        link : 'https://fonts.google.com/specimen/Cormorant'
      }
    ]
    }
  },
  components:{
    FontsCard
  }
}
</script>

<style>
.main-color-page{
  height: 40vh;
  width: 100%;
}

.title{
  width: fit-content;
  height: 100%;
  vertical-align:bottom;
  margin: auto;
  font-size: 8vw;
  padding-top: 8vh;
  color: rgba(255, 255, 255, 0.5)
}

.psychological-font-effect {
  padding: 40px 10%;
}

.psychological-font-effect-title{
  text-align: center;
  padding: 10px;
}

.psychological-font-effect-desc {
  font-size: 24px;
  width: 75%;
  padding: 20px 15px;
  text-align: justify;
  margin: auto;
}

.fonts-details-title {
  margin: 20px 0px;
}

.fonts-details-list {
  font-size: 20px;
}

.more-fonts{
  padding: 40px 10%;
}

.more-fonts-title{
  text-align: center;
  padding: 10px;
}

.fonts-card{
  margin : 20px 12%;
}
</style>
