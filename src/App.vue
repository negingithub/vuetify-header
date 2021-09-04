<template>
  <v-app>
    <v-app-bar
      app
      color="green darken-3"
      dark
      clipped-left
      collapse-on-scroll
      fixed
      rounded
      height="100px"
    >
      <div style="float:left" >
        <v-img 
          src="..\src\assets\download.png"
          transition="scale-transition"
          width="80"
        />
      </div>
      <div style="margin-left:30px">
          <span>شرکت تجارت الکترونیکی ارتباط فردا</span>

      </div>

      <v-spacer></v-spacer>

      <v-btn rounded small color="green darken-3" @click="toggle()">
       <v-badge class="mx-2" content="3" color="red" v-model="content">
         <v-icon small >
           mdi-bell
        </v-icon>
       </v-badge>
      </v-btn>
      <v-btn rounded small color="green darken-3" >
           <v-badge class="mx-2" content="8">
         <v-icon small>
           mdi-home
        </v-icon>
       </v-badge>
        </v-btn>
         <v-btn rounded small color="green darken-3">
         <v-icon small class="mx-2">
           mdi-dots-vertical
        </v-icon>
        </v-btn>
      

     
    </v-app-bar>

    <v-main>
      fgdfgdfgdg
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  components: {
  },
  methods:{
    toggle(){
      this.content=!this.content
    }
  },

  data: () => ({
    content:true,
  }),

  
};
</script>
