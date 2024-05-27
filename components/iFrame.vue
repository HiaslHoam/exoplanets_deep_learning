<template>
   
  <div>
         
        <iframe :width="width" :height="height" :src="link"></iframe>
                
  </div>

</template>

<script>

import axios from "axios";

export default{
  props: {
      src: String,
      width: Number,
      height: Number,
    },
   name:"Camera",
   data(){
       return{
       link:this.src,
       width:this.width,
       height:this.height,
       
   };
   },
  methods:{
      
      OnSelectCam(link){
          this.link = link;
      },    
          
      },
 
}   
 
</script>