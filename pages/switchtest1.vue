<template>
    
        
  
<div>
  <div class="modelcontainter">
           <!-- <model-viewer src="/3dmodels/honeycomb.glb" minimumRenderScale="0.1" alt="Orange B by Wong Chun Hoi"   environment-image="neutral"  camera-controls auto-rotate ar ar-scale="auto" quick-look-browsers="chrome safari" > </model-viewer> -->
           <!-- honey comb by Wong Chun Hoi -->
 
             <!-- Ma shi po tomato by Wong Chun Hoi -->
      <model-viewer id="toggle-model" src="https://poly.googleusercontent.com/downloads/c/fp/1614159411541035/eM4ltBXRD6a/eJbTEPk3etv/mashipotomatoL.gltf" alt="Ma shi po tomato by Wong Chun Hoi" background-color="##AA0000" camera-controls auto-rotate environment-image="neutral" >
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

                        
     const models = ['https://poly.googleusercontent.com/downloads/c/fp/1614159411541035/eM4ltBXRD6a/eJbTEPk3etv/mashipotomatoL.gltf', 'https://poly.googleusercontent.com/downloads/c/fp/1614170083816586/cqgPcFSwxuh/anUzZhMbo7i/tigerteethpepper.gltf'];
      const toggleModel = document.querySelector('#toggle-model');
      let j = 0;
      setInterval(() => toggleModel.setAttribute('src', `${models[j++ % 2]}`), 2000);
 
      
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

