<template>
    <Layout>
        <!--section 1-->
      <figure class="logo">
          <g-image src="https://i.imgur.com/ZT0CHO5.png"></g-image>
      </figure>
      <br/>
  
      <div class="firstpart has-text-centered ">
          <h2 class="headertext1">Start Designing The Life Of Your Dreams</h2>
          <h1 class="headertext2 ">By Earning $10,000.00</h1>
          <p class="headertext22">Extra Per Month</p>
          <h4 class="headertext3">With lust <b class="textderation">4 Hours </b> Of Work A Week </h4>
          <p  class="headertext4">( ... You Can Do This Completely On The Side!) </p>
      </div>

      <div class="secondpart has-text-centered ">
          <h1 class="sectext1 ">My #1 Handpicked Best Affiliate Program That Pays Monthly Recurring Commision! </h1>
          <h2 class="sectext2 ">Stop Losing Your Hard Earned Money & Wasting Your Precious Time To Find The Best Affiliate Program!</h2>

          <div class="columns videocloum">
            <div class="column videobox">
               <figure class="image is-16by9">
                  <iframe class="has-ratio" width="540" height="360"
                          src="https://www.youtube.com/embed/MnHgIQHLm3o?showinfo=0" frameborder="0"
                          allowfullscreen></iframe>
                  </figure>
            </div>
            <div class="column bookcoluim">
              <g-image src="~/assets/images/free-book.png"></g-image>
            </div>
          </div>
          <h2 class="offtext1 ">"THE AFFILIATE MARKETING BLUEPRINT" </h2>
          <h1 class="offtext2 ">Take Your FREE Copy NOW! </h1>
      </div>
      <div class="firstpart has-text-centered ">
          <div class="field ">
            <div class="mailinputfiled">
              <input  class="input is-medium" type="email" placeholder="Enter your email address here... ">
            </div>
          </div>
          <div class="has-text-centered">
              <button v-on:click="next" class="button sendbook is-success is-medium">YES! GIVE ME MY FREE COPY NOW! </button>
          </div>
      </div>

      <div class="has-text-centered ">
          <h1 class="prooftext ">PROOF  </h1>
          <div class="columns">
            <div class="column ">
               <g-image src="https://images.clickfunnels.com/b8/45757bd0e14f339ec80cf124ac7383/3.png"></g-image>
            </div>
            <div class="column">
              <g-image src="https://images.clickfunnels.com/7a/7b9dd2429f4a558db8d27fc6b55ca0/4.png"></g-image>
            </div>
          </div>
      </div>
      <br>
      <h2 class="headertext1 has-text-centered" style="color: black">As Seen On </h2>
      <div class="columns footericon">
        <div class="column">
          <g-image src="https://images.squarespace-cdn.com/content/v1/58e9bbcb5016e13683abec44/1492201167150-HNQ5Z78CJK1HIQ1JSQ8R/ke17ZwdGBToddI8pDm48kMABmXfHFJ1hPhaBVAaleilZw-zPPgdn4jUwVcJE1ZvWQUxwkmyExglNqGp0IvTJZUJFbgE-7XRK3dMEBRBhUpxcLMSb-u98vE5T7M6L1cpWXMj3FU9GeFt3G9woqbsI-XeQjidn880xzk_2dDWgBr0/forbes-final.png?format=500w"></g-image>
          
        </div>
        <div class="column">
          <g-image src="https://images.squarespace-cdn.com/content/v1/58e9bbcb5016e13683abec44/1492201737447-B4CXDTKNR01A03KOWWVF/ke17ZwdGBToddI8pDm48kMABmXfHFJ1hPhaBVAaleilZw-zPPgdn4jUwVcJE1ZvWQUxwkmyExglNqGp0IvTJZUJFbgE-7XRK3dMEBRBhUpxcLMSb-u98vE5T7M6L1cpWXMj3FU9GeFt3G9woqbsI-XeQjidn880xzk_2dDWgBr0/home-biz-final.png?format=500w"></g-image>
        </div>
        <div class="column">
          <g-image src="https://images.squarespace-cdn.com/content/v1/58e9bbcb5016e13683abec44/1492201579147-IOP7Z6AS5RYINXP95OMK/ke17ZwdGBToddI8pDm48kMABmXfHFJ1hPhaBVAaleilZw-zPPgdn4jUwVcJE1ZvWQUxwkmyExglNqGp0IvTJZUJFbgE-7XRK3dMEBRBhUpxcLMSb-u98vE5T7M6L1cpWXMj3FU9GeFt3G9woqbsI-XeQjidn880xzk_2dDWgBr0/yahoo-final.png?format=500w"></g-image>
        </div>
        <div class="column">
          <g-image src="https://images.squarespace-cdn.com/content/v1/58e9bbcb5016e13683abec44/1492201328444-8F2X49CUU9IUZ2W8CCFN/ke17ZwdGBToddI8pDm48kMABmXfHFJ1hPhaBVAaleilZw-zPPgdn4jUwVcJE1ZvWQUxwkmyExglNqGp0IvTJZUJFbgE-7XRK3dMEBRBhUpxcLMSb-u98vE5T7M6L1cpWXMj3FU9GeFt3G9woqbsI-XeQjidn880xzk_2dDWgBr0/image-asset.png?format=500w"></g-image>
        </div>
      </div>
      <br>
    </Layout>
</template>



<script>
    export default {
        metaInfo: {
            title: 'Super Affiliate System with John Crestani | 80% Off | Don`t Miss Out on this Amazing Opportunity'
        },
        data() {
            return {
                isActive: false,
            }
        },
        components: {},

        methods: {
            launch: function () {
                this.isActive = true;
            },
            close: function () {
                this.isActive = false;
            }
        },
    }
</script>

<style>
    .home-links a {
        margin-right: 1rem;
    }
</style>
