<template>
  <div id="app">
    <main>
      <router-view />
    </main>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed,
figure, figcaption, footer, header, hgroup,
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  font: inherit;
  vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure,
footer, header, hgroup, menu, nav, section {
  display: block;
}
body {
  line-height: 1;
  color: #2c2e33;
}
ol, ul {
  list-style: none;
}
blockquote, q {
  quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
  content: '';
  content: none;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}

.screen-box {
  background: #fdfdfd;
  width: 100vw;
  height: 100vh;
  overflow: scroll;
}

.item-box {
  border-radius: 5px;
  background: #fff;
  box-shadow: 0px 0px 5px 1px #eaeaea;
  -moz-box-shadow: 0px 0px 5px 1px #eaeaea;
  -webkit-box-shadow: 0px 0px 5px 1px #eaeaea;
}

.item-box__media img {
  width:100%;
  border-top-left-radius: 5px;
  border-top-right-radius: 5px;
}

.item-box__content {
  padding: 10px;
}

.screen-box__main {
  padding: 20px;
}
</style>
