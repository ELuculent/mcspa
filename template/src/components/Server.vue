<template>
<div class="container-fluid" style="background-color: #383838;">
<br /><br /><br />
  <center>
    <div class="container-fluid">
        <!-- vue-carousel -->
         <carousel-3d :autoplay="true" :autoplay-timeout="2500" :display="3" :width="1000" :height="600">
              <!-- Carousel Slides. Duplicate the slides if you need more. -->
              <slide :index="0">
                <img src="">
                Text to go along, delete if you want.
              </slide>
              <slide :index="1">
                  <img src="">
              </slide>
              <slide :index="2">
                <img src="">
              </slide>
         </carousel-3d>
    </div>
  </center>
   <br /><br /><br />
   <br /><br /><br />
    <div class="row">
        <div class="col">
            <b-btn v-b-toggle="'collapse1'" variant="success">Toggle Server Status</b-btn>
             <b-collapse id="collapse1">

                  <b-card class="server-status">
                        <h1 class="status-head">Server status</h1>
                        <h2>Server Name</h2>
                        <p>
                            <span class="onlineQuery"></span><br />
                            <span class="motd"></span><br />
                            There are <span class="count"></span>/<span class="max"></span> players online <br />
                            The server was last online on: <span class="last-online"></span>
                        </p>
                  </b-card>

              </b-collapse>
                <br/><br/><br/><br/>
              
               <h1>Social</h1>
               <iframe src="discordAppWidget" width="350" height="500" allowtransparency="true" frameborder="0"></iframe>
        </div>
        <div class="col-1">

        </div>
        <div class="col">
            <h1>News</h1>
            <br/><br/><br/>
            <!-- News Card duplicate from the card div to the final <br/> tag to get more -->
            <div class="card">
              <div class="card-block" style="background-color:wheat;">
                <!-- Non functional button (for style) -->
                <h3 class="card-title btn-block btn-primary">Title</h3>
                <p class="card-text" style="color:black">Text Here. Vivamus ultricies nec lorem id egestas. Curabitur iaculis mauris id eros commodo blandit. Nullam posuere mi sit amet ex pharetra interdum at sed dolor. Duis nulla velit, eleifend quis congue eget, sodales id nibh. Mauris quis lacus eros. In nisl eros, dapibus quis tincidunt et, ullamcorper in erat. Morbi feugiat, nibh in lacinia porttitor, ex ligula pellentesque lorem, sit amet volutpat nisi elit at leo. </p> 
              </div>
            </div>
            <br/><br/><br/>
            <div class="card">
              <div class="card-block" style="background-color:wheat;">
                <h3 class="card-title btn-block btn-primary">Title</h3>
                <p class="card-text" style="color:black">Text Here. Vivamus ultricies nec lorem id egestas. Curabitur iaculis mauris id eros commodo blandit. Nullam posuere mi sit amet ex pharetra interdum at sed dolor. Duis nulla velit, eleifend quis congue eget, sodales id nibh. Mauris quis lacus eros. In nisl eros, dapibus quis tincidunt et, ullamcorper in erat. Morbi feugiat, nibh in lacinia porttitor, ex ligula pellentesque lorem, sit amet volutpat nisi elit at leo. </p> 
              </div>
            </div>
            
        </div>
  </div>
  <div class="row">
    <div class="col">
       
    </div>
    <div class="col-1">

    </div>
    <div class="col">

    </div>
  </div>
</div>


</template>

<script>
    export default {
        name: 'server'
    }

</script>

<style scoped>
    .server-status {
        background-color: #323232;
        color: #00ffff;
    }
    
    .onlineQuery {
        color: #00ffff;
    }
    
    .status-head {
        color: red;
    }
    
    .count {
        color: red;
    }
    
    .max {
        color: red;
    }
    
    .last-online {
        color: red;
    }
    
    .container-fluid {
        background-color: #383838;
        color: white;
    }

</style>
