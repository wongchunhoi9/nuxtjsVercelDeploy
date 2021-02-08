<template>
    
        
  
<div>
  <div class="modelcontainter">
           <model-viewer src="/3dmodels/honeycomb.glb" minimumRenderScale="0.1" alt="Orange B by Wong Chun Hoi"   shadow-intensity="1" camera-controls auto-rotate ar ar-scale="auto" quick-look-browsers="chrome safari" > </model-viewer>
                    <script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.js"></script>
                      <script nomodule src="https://unpkg.com/@google/model-viewer/dist/model-viewer-legacy.js"></script>     
        </div>

        <div id="instructions">
          <h1>Honey comb 坪輋</h1>
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

