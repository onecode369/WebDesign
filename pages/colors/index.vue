<template>
  <div>
    <div class="main-color-page color-main2-bg">
      <div class="title one-animate-zoom">Picking Colors</div>
    </div>
    <div class="colors one-container">
      <div class="colors-title color-main2 one-card">
        Triadic Colors
      </div>
      <div class="one-row">
        <div class="one-quater">
          <img src="~assets/images/triadic.png" alt="Triadic Colors" class="one-col colors-image-img"></div>
        <div class="colors-detail one-thirdquater">
            Composed of 3 colors on separate ends of the color spectrum. There is a very easy way to create a Triadic color scheme:<br /><br/>
          <ul>
            <li>Take a color wheel, and choose your base color.</li>
            <li>Draw an Equilateral Triangle from this point.</li>
            <li>The three points of the triangle will form your tri-color scheme.</li>
          </ul>
          <br/>
          By using an Equilateral Triangle, you can ensure the colors have equal vibrancy and compliment each other properly.
        </div>
      </div>
      <div class="colors-list">
          <div class="one-row one-center">
            <div class="colors-list-li color-main2 one-card one-quarter"><img src="~assets/images/t1.png" alt="t1"><br />Hex Codes : <br />#FFAE42 & #0D98BA & #C71585<br /></div>
            <div class="colors-list-li color-main2 one-card one-quarter"><img src="~assets/images/t2.png" alt="t2"><br />Hex Codes : <br />#FFFF00 & #0000FF & #FF0000<br/></div>
            <div class="colors-list-li color-main2 one-card one-quarter"><img src="~assets/images/t3.png" alt="t3"><br />Hex Codes : <br />#9ACD32 & #8A2BE2 & #FF5349<br /></div>
            <div class="colors-list-li color-main2 one-card one-quarter"><img src="~assets/images/t4.png" alt="t4"><br />Hex Codes : <br />#00FF00 & #7F00FF & #FFA500<br/></div>
          </div>
      </div>
    </div>
    <div class="colors one-container">
      <div class="colors-title color-main2 one-card">
        Compound Colors
      </div>
      <div class="one-row">
        <div class="one-quater">
          <img src="~assets/images/compound.png" alt="Triadic Colors" class="one-col colors-image-img"></div>
        <div class="colors-detail one-thirdquater">
            The Compound color scheme is based on providing a range of Complementary Colors: two colors are chosen from opposite ends of the color spectrum. By doing so, the designer is allowed more freedom in their design while also benefiting from the visual appeal of complementary colors.
        </div>
      </div>
      <div class="colors-list">
          <div class="one-row one-center">
            <div class="colors-list-li color-main2 one-card one-third"><img src="~assets/images/c1.png" alt="c1"><br />Hex Codes : <br />#F9BC02 & #FB9902 & #3E01A6 & #0247FE<br /></div>
            <div class="colors-list-li color-main2 one-card one-third"><img src="~assets/images/c2.png" alt="c2"><br />Hex Codes : <br />#FD5308 & #FE2712 & #0392CE & #66B033<br/></div>
            <div class="colors-list-li color-main2 one-card one-third"><img src="~assets/images/c3.png" alt="c3"><br />Hex Codes : <br />#A7194B & #8601B0 & #D1EA2C & #FFFE34<br /></div>
          </div>
      </div>
    </div>
    <div class="colors one-container">
      <div class="colors-title color-main2 one-card">
        Analogous Colors
      </div>
      <div class="one-row">
        <div class="one-quater">
          <img src="~assets/images/triadic.png" alt="Triadic Colors" class="one-col colors-image-img"></div>
        <div class="colors-detail one-thirdquater">
          An Analogous color scheme is based on a careful selection of colors in the same area of the color spectrum. Usually the colors are differentiated by their vibrancy, and their contrast when compared to each other.
          Two examples of an Analogous color scheme are:
          <ul>
            <li>Shades Yellow and Orange</li>
            <li>A Monochromatic Selection (Shades of a base color)</li>
          </ul>
          <br/>
        </div>
      </div>
      <div class="colors-list">
          <div class="one-row one-center">
            <div class="colors-list-li color-main2 one-card one-quarter"><img src="~assets/images/a1.png" alt="a1"><br />Hex Codes : <br />#FFFE34 & #F9BC02 & #FB9902<br /></div>
            <div class="colors-list-li color-main2 one-card one-quarter"><img src="~assets/images/a2.png" alt="a2"><br />Hex Codes : <br />#FD5308 & #FE2712 & #A7194B<br/></div>
            <div class="colors-list-li color-main2 one-card one-quarter"><img src="~assets/images/a3.png" alt="a3"><br />Hex Codes : <br />#8601B0 & #3E01A6 & #0247FE<br /></div>
            <div class="colors-list-li color-main2 one-card one-quarter"><img src="~assets/images/a4.png" alt="a4"><br />Hex Codes : <br />#0392CE & #66B033 & #D3EC30<br/></div>
          </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {

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

.colors{
  padding: 40px 10%;
}

.colors-title{
  text-align-last: center;
  width: 100%;
  font-size: 42px;
  margin-bottom: 30px;
}

.colors-list-li{
  padding: 20px;
}

.colors-image-img{
  padding: 6rem;
  width: 30rem;
}
.colors-detail {
  font-size: 24px;
  min-height: 30rem;
  margin-top: 6rem;
}
</style>
