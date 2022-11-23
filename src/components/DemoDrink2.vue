<template>
  <div id="app">
    <md-card class="md-with-hover">
      <md-card-header>
        <div class="md-title">
          {{ msg1 }}
        </div>
        <img src="https://openimage.interpark.com/goods_image_big/2/3/7/5/6549172375_l.jpg">
      </md-card-header>
      <md-card-content>
        <md-button class="md-icon-button md-raised md-accent">
          <md-icon>thumb_up</md-icon>
        </md-button>
      </md-card-content>
    </md-card>
    <md-card class="md-with-hover">
      <md-card-header>
        <div class="md-title">
          {{ msg2 }}
        </div>
        <img src="https://img.danawa.com/prod_img/500000/945/970/img/1970945_1.jpg?shrink=330:330&_v=20211110135448">
      </md-card-header>
      <md-card-content>
        <md-button class="md-icon-button md-raised md-accent">
          <md-icon>thumb_up</md-icon>
        </md-button>
      </md-card-content>
    </md-card>
        <md-card class="md-with-hover">
      <md-card-header>
        <div class="md-title">
          {{ msg3 }}
        </div>
      </md-card-header>
      <md-card-content>
        <md-button class="md-icon-button md-raised md-accent">
          <md-icon>thumb_up</md-icon>
        </md-button>
      </md-card-content>
    </md-card>
        <md-card class="md-with-hover">
      <md-card-header>
        <div class="md-title">
          {{ msg4 }}
        </div>
      </md-card-header>
      <md-card-content>
        <md-button class="md-icon-button md-raised md-accent">
          <md-icon>thumb_up</md-icon>
        </md-button>
      </md-card-content>
    </md-card>
    
  </div>
</template>

<style>
  .md-card {
    width: 320px;
    margin: 4px;
    display: inline-block;
    vertical-align: top;
  }
</style>

<script>
export default {
  name: 'DemoDrink1',
  props: {
    msg1: String,
    msg2: String,
    msg3: String,
    msg4: String
  }
}
</script>