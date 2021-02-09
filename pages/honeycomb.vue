<template>
    
        
  
<div>
  <div class="modelcontainter">
           <!-- <model-viewer src="/3dmodels/honeycomb.glb" minimumRenderScale="0.1" alt="Orange B by Wong Chun Hoi"   environment-image="neutral"  camera-controls auto-rotate ar ar-scale="auto" quick-look-browsers="chrome safari" > </model-viewer> -->
           <!-- honey comb by Wong Chun Hoi -->
          <model-viewer src="https://poly.googleusercontent.com/downloads/c/fp/1612890832356051/7qY6Szu2llj/6QHs0XGXAfD/model.gltf" alt="honey comb by Wong Chun Hoi" background-color="##fafafa" camera-controls auto-rotate > </model-viewer>
                    <script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.js"></script>
                      <script nomodule src="https://unpkg.com/@google/model-viewer/dist/model-viewer-legacy.js"></script>     
        </div>

        <div id="instructions">
          <h1>蜜蜂巢</h1>
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

