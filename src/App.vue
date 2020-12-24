<template> <!-- HTML -->
  <div id="app">
    <CommonHeader></CommonHeader>
    <body>
      <main>
        <div id="eyecatch">
          <p>機械ではできない仕事を</p>
          <div class="news">
            <div class="news-box1">2019/01/01<br />ニュースタイトルがここに入ります。3月の決算報告書</div>
            <div class="news-box2">news</div>
          </div>
        </div>
        <div id="about" class="wrap">
          <div class="about-box">
            <div class="pict-right">
              <img src="@/assets/img/mission-img.jpg" alt="" />
            </div>
          </div>
          <div class="about-left">
            <p class="title">お客様のために進化する成長企業であり続ける</p>
            <p>顧客主導型サービスを提供する企業として、お客様の会社経営に必要なサービスと情報を提供し続ける企業支援会社を目指します。企業が現在直面している「勝ち残るため」の戦略を提供できる会社として、ホームページをはじめ、各種マーケティングをご提供いたします。</p>
            <button @click="userClic">ミッション詳細</button>
            <div class="pict"></div>
          </div>
        </div>
      </main>
      <main2>
        <div class="box-2">
          <h5 class="section--title">service</h5>
          <div class="text--box1">
            <div class="content-1">web制作事業</div>
            <p>コーチングのミッション</p>
            <p>ユーザーが求める物を分析し、ユーザビリティを備えた最適なサイトを提供。建設業から美容、ブライダル、飲食店まで多種多様な業種の製作実績があります</p>
            <a class="link-2" href="#">サービス詳細</a>
          </div>
          <div class="text--box2">
            <div class="content-1">web制作事業</div>
            <p>コーチングのミッション</p>
            <p>ユーザーが求める物を分析し、ユーザビリティを備えた最適なサイトを提供。建設業から美容、ブライダル、飲食店まで多種多様な業種の製作実績があります</p>
            <a class="link-2" href="#">サービス詳細</a>
          </div>
          <div class="pict-1">
            <img src="@/assets/img/service2.jpg" />
          </div>
          <div class="pict-2">
            <img src="@/assets/img/service1.jpg" />
          </div>
        </div>
    
        <div class="business">
          <div class="flex around business-wrap">
            <div class="pict-3">
              <img src="@/assets/img/company.jpeg" />
              <div class="label-1">
                <h5 class="company">company</h5>
                <p class="p1">会社概要</p>
              </div>
            </div>
            <div class="pict-4">
              <img src="@/assets/img/recruit.jpg" />
              <div class="label-2">
                <h5 class="recruit">recruit</h5>
                <p class="p2">採用情報</p>
              </div>
            </div>
          </div>
        </div>
        <div class="business-2">
          <div class="label-3">
            <h5 class="faq">FAQ</h5>
            <p class="p3">良くある質問</p>
          </div>
        </div>
      </main2>
    
      <div class="contact">
        <h5 class="title-contact">contact</h5>
        <p>お問い合わせ</p>
        <p class="p4">お気軽にお問い合わせください。</p>
        <p class="p5">資料請求・お問い合わせなどなんでも気軽にお問い合わせください。お仕事のご連絡もお問い合わせページに飛んでいただいて、入力フォームにご記入お願いいたします。</p>
        <a class="link-3" href="#">お問い合わせへ</a>
      </div>
    
      <div class="flex between">
        <h5 class="footer-logo">estra inc.</h5>
        <nav class="footer-nav">
          <ul>
            <li><a href="#">home</a></li>
            <li><a href="#">about</a></li>
            <li><a href="#">service</a></li>
            <li><a href="#">works</a></li>
            <li><a href="#">price</a></li>
            <li><a href="#">contact</a></li>
          </ul>
        </nav>
      </div>
    </body>
    <CommonFooter></CommonFooter>
  </div>
</template>

<script> // JavaScript
import CommonHeader from "./components/CommonHeader.vue";
import CommonFooter from "./components/CommonFooter.vue";
export default {
  components: {
    CommonHeader,
    CommonFooter
  }
};
</script>

<style> /* css */
  @charset "UTF-8";

  /* リセットcss */
  html,
  body,
  div,
  span,
  object,
  iframe,
  h1,
  h2,
  h3,
  h4,
  h5,
  h6,
  p,
  blockquote,
  pre,
  abbr,
  address,
  cite,
  code,
  del,
  dfn,
  em,
  img,
  ins,
  kbd,
  q,
  samp,
  small,
  strong,
  sub,
  sup,
  var,
  b,
  i,
  dl,
  dt,
  dd,
  ol,
  ul,
  li,
  fieldset,
  form,
  label,
  legend,
  table,
  caption,
  tbody,
  tfoot,
  thead,
  tr,
  th,
  td,
  article,
  aside,
  canvas,
  details,
  figcaption,
  figure,
  footer,
  header,
  hgroup,
  menu,
  nav,
  section,
  summary,
  time,
  mark,
  audio,
  video {
  margin: 0;
  padding: 0;
  border: 0;
  outline: 0;
  font-size: 100%;
  vertical-align: baseline;
  background: transparent;
  }

  body {
  line-height: inherit;
  }

  article,
  aside,
  details,
  figcaption,
  figure,
  footer,
  header,
  hgroup,
  menu,
  nav,
  section {
  display: block;
  }

  nav ul {
  list-style: none;
  }

  blockquote,
  q {
  quotes: none;
  }

  blockquote:before,
  blockquote:after,
  q:before,
  q:after {
  content: "";
  content: none;
  }

  a {
  margin: 0;
  padding: 0;
  font-size: 100%;
  vertical-align: baseline;
  background: transparent;
  }

  /* change colours to suit your needs */
  ins {
  background-color: #ff9;
  color: #000;
  text-decoration: none;
  }

  /* change colours to suit your needs */
  mark {
  background-color: #ff9;
  color: #000;
  font-style: italic;
  font-weight: bold;
  }

  del {
  text-decoration: line-through;
  }

  abbr[title],
  dfn[title] {
  border-bottom: 1px dotted;
  cursor: help;
  }

  table {
  border-collapse: collapse;
  border-spacing: 0;
  }

  /* change border colour to suit your needs */
  hr {
  display: block;
  height: 1px;
  border: 0;
  border-top: 1px solid #cccccc;
  margin: 1em 0;
  padding: 0;
  }

  input,
  select {
  vertical-align: middle;
  }

  /* 共通のスタイル */
  body {
  font-size: 10px;
  }

  img {
  display: block;
  width: 100%;
  }
  /*
  .wrap {
  width: 80%;
  margin: 0 auto 50px;
  }*/

  .flex {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  background-color: #000;
  }

  .between {
  justify-content: space-between;
  }

  .around {
  justify-content: space-around;
  }

  /* eyecatch */
  #eyecatch {
  height: 600px;
  position: relative;
  background: url(./assets/img/eyecatch.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  }

  #eyecatch p {
  position: absolute;
  top: 45%;
  left: 5%;
  font-weight: bold;
  color: #fff;
  font-size: 40px;
  }

  .news {
  display: flex;
  flex-wrap: nowrap;
  width: 100%;
  justify-content: flex-end;
  position: absolute;
  bottom: 0;
  }

  .news-box1 {
  background-color: #fff;
  padding: 1% 15% 1% 0;
  text-indent: -1em;
  padding-left: 2em;
  bottom: 0;
  }

  .news-box2 {
  background-color: #000;
  color: #fff;
  align-items: center;
  padding: 2% 5%;
  bottom: 0;
  }

  /* about */
  .about-box {
  position: relative;
  height: 300px;
  background-color: #000;
  }

  .pict-right {
  position: absolute;
  width: 35%;
  right: 5%;
  bottom: -20%;
  z-index: 2;
  }

  .title {
  font-size: 18px;
  font-weight: bold;
  }

  #about {
    position: relative;
  }

  .title,
  .about-left p {
  margin-bottom: 15px;
  color: #fff;
  }

  .about-left {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  z-index: 3;
  }

  .link {
  padding: 5px 15px;
  text-decoration: none;
  cursor: pointer;
  border: 1px solid #fff;
  transition: 0.4s ease;
  background-color: #fff;
  color: #000;
  }

  /* box2 */
  .box-2 {
  position: relative;
  height: 1200px;
  background-color: #ccc;
  }

  .section--title {
  top: 100px;
  width: 100%;
  margin-top: 8%;
  font-weight: bold;
  padding: 1% 0;
  text-align: center;
  font-size: 18px;
  background-color: #ccc;
  }

  .content-1,
  .content-2 {
  padding: 0 0 10px 0;
  font-weight: bold;
  }

  .text--box1 p,
  .text--box2 p {
  padding: 0 0 10px 0;
  }

  .text--box1 {
  width: 30%;
  padding: 48px;
  position: absolute;
  top: 10%;
  left: 20%;
  z-index: 2;
  background-color: #fff;
  }

  .text--box2 {
  width: 30%;
  padding: 48px;
  position: absolute;
  right: 20%;
  bottom: 13%;
  z-index: 2;
  background-color: #fff;
  }

  .link-2 {
  padding: 5px 15px;
  text-decoration: none;
  cursor: pointer;
  border: 1px #000 solid;
  transition: 0.4s ease;
  background-color: #fff;
  color: #000;
  float: right;
  }

  .pict-1 img {
  width: 55%;
  position: absolute;
  top: 5%;
  right: 0;
  z-index: 1;
  }

  .pict-2 img {
  width: 55%;
  position: absolute;
  bottom: 10%;
  left: 0px;
  z-index: 1;
  }

  /* business */
  .business {
  display: flex;
  position: relative;
  height: 250px;
  margin-top: 20px;
  background-color: #fff;
  }

  .company,
  .recruit,
  .faq,
  .title-contact {
  font-size: 18px;
  color: #fff;
  }

  .label-1 {
  width: 48%;
  text-align: center;
  position: absolute;
  top: 50%;
  left: 0;
  transform: translateY(-50px);
  z-index: 2;
  }

  .label-2 {
  width: 48%;
  text-align: center;
  position: absolute;
  top: 50%;
  right: 0;
  transform: translateY(-50px);
  z-index: 2;
  }

  .p1,
  .p2 {
  color: #fff;
  z-index: 2;
  }

  .label-3 {
  width: 70%;
  align-items: center;
  display: flex;
  margin-left: auto;
  margin-right: auto;
  background-color: #000;
  padding: 25px;
  }

  .p3 {
  margin: 0 auto;
  color: #fff;
  z-index: 2;
  }

  .pict-3 img {
  width: 48%;
  height: 60%;
  position: absolute;
  top: 10%;
  left: 0;
  z-index: 1;
  }
  .pict-4 img {
  width: 48%;
  height: 60%;
  position: absolute;
  top: 10%;
  right: 0;
  z-index: 1;
  }

  .business-2 {
  height: 200%;
  position: relative;
  margin-bottom: 5%;
  }

  /* contact */
  .contact {
  position: relative;
  text-align: center;
  padding: 100px 0;
  height: 150px;
  background-image: url(./assets/img/contact-bg.jpg);
  background-size: cover;
  background-position: center;
  color: #fff;
  }

  .p4 {
  font-size: 20px;
  padding: 15px;
  }

  .p5 {
  padding: 0 0 20px 0;
  font-size: 8px;
  }

  .link-3 {
  padding: 5px 15px;
  text-decoration: none;
  cursor: pointer;
  border: 1px #fff solid;
  transition: 0.4s ease;
  color: #fff;
  text-align: center;
  z-index: 2;
  }

   .footer-logo {
    font-weight: bold;
    margin-left: 35px;
    color: #fff;
    line-height: 20px;
  }

  .footer-nav li {
    display: inline-block;
    margin-right: 35px;
  }

  .footer-nav a {
    text-decoration: none;
    color: #fff;
  }

  @media screen and (max-width: 768px) {
    /* box-2 */
    .box-2 {
    height: 900px;
    }

    .text--box1 {
    width: 80%;
    position: absolute;
    padding: 5%;
    top: 30%;
    left: 50%;
    transform: translateX(-50%);
    }

    .text--box2 {
    width: 80%;
    position: absolute;
    padding: 5%;
    left: 50%;
    bottom: 5%;
    transform: translateX(-50%);
    }

    .pict-1 img {
    width: 90%;
    height: 25%;
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
    }

    .pict-2 img {
    width: 90%;
    height: 25%;
    position: absolute;
    left: 50%;
    bottom: 23%;
    transform: translateX(-50%);
    }

    /* business */
    .business {
      position: relative;
      height: 380px;
    }

    .pict-3 img {
      width: 100%;
      height: 50%;
      position: absolute;
      top: 0;
    }

    .pict-4 img {
      width: 100%;
      height: 50%;
      position: absolute;
      top: auto;
    }

    .label-1 {
      position: absolute;
      top: 20%;
      left: 50%;
      transform: translate(-50%);
    }

    .label-2 {
      position: absolute;
      top: 70%;
      left: 50%;
      transform: translate(-50%);
    }

    /* business-2 */
    .business-2 {
      margin: 5% 0;
    }
    .label-3 {
      width: 80%;
    }

    /* contact */
    .contact {
      padding-left: 20%;
      padding-right: 20%;
    }

    .footer-logo {
      max-width: 768px;
      margin: auto;
      font-size: 18px;
    }

    .footer-nav {
    display: none;
    }

  }
</style>