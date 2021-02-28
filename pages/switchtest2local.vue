<template>
    
        
  
<div>
  <div class="modelcontainter">
 
             <!-- Ma shi po tomato by Wong Chun Hoi -->
      <model-viewer id="toggle-model" src="/3dmodels/honeycomb.glb" alt="Ma shi po tomato by Wong Chun Hoi" background-color="##AA0000" camera-controls auto-rotate environment-image="neutral" >
        <!-- <div class="buttonContatiner">
           <b-button class="nextbutton">next</b-button>
           next
        </div> -->
       
       </model-viewer> 
                    <script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.js"></script>
                    <script nomodule src="https://unpkg.com/@google/model-viewer/dist/model-viewer-legacy.js"></script>    
   
        </div>

        <div id="instructions">
          <!-- <h1>Tomato</h1> -->
        </div>
</div>
        

</template>

<script>
      const models = ['farmerstick.glb', 'honeycomb.glb'];
      const toggleModel = document.querySelector('#toggle-model');
      // document.querySelector('#toggle-model').setAttribute('src', `${models[j++ % 2]}`)
      let j = 0;
      setInterval(() => toggleModel.setAttribute('src', `/3dmodels/${models[j++ % 2]}`), 2000);
                      
 
      
  </script>


<style  scoped>


model-viewer { 
    width: 100%;
    height: 100%;
    background-color: rgb(0, 0, 0);

}

.buttonContatiner {
  display: flex;
  float: right;
  justify-content: center;
  align-items: center;
  top: 50%;
  
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

