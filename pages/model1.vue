<template>
    
        
        <div>
            <b-container fluid>
            <b-row>
                
               
                    <model-viewer src="/3dmodels/honeycomb.glb" alt="Orange B by Wong Chun Hoi" background-color="##ffffff" camera-controls auto-rotate ar ar-scale="auto" quick-look-browsers="chrome safari" > </model-viewer>
                    <script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.js"></script>
                      <script nomodule src="https://unpkg.com/@google/model-viewer/dist/model-viewer-legacy.js"></script>     
                
            </b-row>

            
        </b-container>
        </div>
        
    

</template>

<style  scoped>

model-viewer { 
    width: 100%;
    height:800px;

}
</style>

