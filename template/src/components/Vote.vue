<template>
    <div class="container-fluid">
        <div class="content">
           <br/><br/><br/><br/><br/><br/>
           
           <b-btn v-b-toggle="'iv1'" variant="success">Inline Vote 1</b-btn>&nbsp;&nbsp;&nbsp;
           <b-btn v-b-toggle="'iv2'" variant="success">Inline Vote 1</b-btn>&nbsp;&nbsp;&nbsp;
           <b-btn v-b-toggle="'iv3'" variant="success">Inline Vote 1</b-btn>&nbsp;&nbsp;&nbsp;
           <b-btn v-b-toggle="'iv4'" variant="success">Inline Vote 1</b-btn>&nbsp;&nbsp;&nbsp;
           
            <br/><br/><br/><br/><br/>
             
             <b-collapse id="iv1">

                  <b-card class="IV1">
                       
                        <iframe height="720px" width="100%" frameborder="0" scrolling="auto" sandbox="allow-forms allow-scripts allow-same-origin" src="LinkToVotingSite"></iframe>
                  
                  </b-card>

              </b-collapse>
             
             <b-collapse id="iv2">

                  <b-card class="IV">
                       
                        <iframe height="720px" width="100%" frameborder="0" scrolling="auto" sandbox="allow-forms allow-scripts allow-same-origin" src="LinkToVotingSite"></iframe>
                  
                  </b-card>

              </b-collapse>
             
             <b-collapse id="iv3">

                  <b-card class="IV">
                       
                        <iframe height="720px" width="100%" frameborder="0" scrolling="auto" sandbox="allow-forms allow-scripts allow-same-origin" src="LinkToVotingSite"></iframe>
                  
                  </b-card>

             </b-collapse>
             
             <b-collapse id="iv4">

                  <b-card class="IV">
                       
                        <iframe height="720px" width="100%" frameborder="0" scrolling="auto" sandbox="allow-forms allow-scripts allow-same-origin" src="LinkToVotingSite"></iframe>
                  
                  </b-card>

              </b-collapse>
            <br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'vote'
    }
    
</script>

<style scoped>
    .container-fluid{
        background-color: #383838;
    }
    .IV{
        background-color: #383838;
    }
    html,body {
      height:100%;
      margin:0;
    }
    .content {
      height:100%;
      min-height:100%;/*for mozilla*/
    }
    div{
      height:auto;
    }
</style>