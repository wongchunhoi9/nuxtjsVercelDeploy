<template>
    
        
  
<div>
  <b-container class="wholecontainer">
    <b-row>
      <b-col>
          <NuxtLink to="/honeycomb">
            <div>
              <h2>蜜蜂巢</h2>
              <b-img src="~assets/images/honeycomb.jpg"></b-img>
            </div> 
          </NuxtLink>
      </b-col>
      <b-col>
        <NuxtLink to="/farmerstick">
            <h2> 花梨木 禾早草擔挑</h2>
            <b-img src="~assets/images/farmerstick.jpg"></b-img>
          </NuxtLink>
      </b-col>
      <b-col>
        <NuxtLink to="/turnip">
            <h2> 蘿蔔</h2>
            <b-img src="~assets/images/turnip.jpg"></b-img>
          </NuxtLink>
      </b-col>
       <b-col>
        <NuxtLink to="/chickenlegbread">
            <h2> 雞脾包</h2>
            <b-img src="~assets/images/chickenlegbread.jpg"></b-img>
          </NuxtLink>
      </b-col>
       <b-col>
        <NuxtLink to="/tomato">
            <h2> Tomato</h2>
            <!-- <b-img src="~assets/images/chickenlegbread.jpg"></b-img> -->
          </NuxtLink>
      </b-col>
             <b-col>
        <NuxtLink to="/tigerteethpepper">
            <h2> Tiger teeth pepper</h2>
            <!-- <b-img src="~assets/images/chickenlegbread.jpg"></b-img> -->
          </NuxtLink>
      </b-col>
    </b-row>
  </b-container>
  

  
</div>
        
        
    

</template>

<script>
  export default {
    data() {
      return {
        title: 'Home page'
      }
    },
    head() {
      return {
        title: this.title,
        meta: [
          {
            hid: 'description',
            name: 'description',
            content: 'Home page description'
          }
        ]
      }
    }
  }
</script>


<style  scoped>

.wholecontainer { 
background-color: black;

}

h2 {
  color: aliceblue;
}

model-viewer { 
    width: 100%;
    height: 100%;

}

.modelcontainter {
position:absolute;
width:100%;
height:100%;
}
#instructions {
  position: absolute;
  top: 10px;
  left: 30px;
}

</style>

