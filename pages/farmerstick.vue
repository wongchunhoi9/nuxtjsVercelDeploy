<template>
    
        
  
<div>
  <div class="modelcontainter">
           <!-- <model-viewer src="/3dmodels/farmerstick.glb" minimumRenderScale="0.1" alt="Orange B by Wong Chun Hoi"   environment-image="neutral"  camera-controls auto-rotate ar ar-scale="auto" quick-look-browsers="chrome safari" > </model-viewer> -->
           <!-- famrer stick by Wong Chun Hoi -->
<model-viewer src="https://poly.googleusercontent.com/downloads/c/fp/1612892621883960/5yBseBmnGyQ/cYXl1N4iEMC/model.gltf" alt="famrer stick by Wong Chun Hoi" background-color="##fafafa" camera-controls auto-rotate > </model-viewer>
           
                    <script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.js"></script>
                      <script nomodule src="https://unpkg.com/@google/model-viewer/dist/model-viewer-legacy.js"></script>     
        </div>

        <div id="instructions">
          <h1>花梨木 禾早草擔挑</h1>
        </div>
</div>
        
        
    

</template>

<style  scoped>


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

