<template>
  <header
    :style="{
     // backgroundColor: 'brown',
      width: '100%',
      height: '10%',
      display: 'flex',
      justifyContent: 'center',
    }"
  >
    <div
      :style="{
        backgroundColor: '#c71818',
        width: '80%',
        height: '100%',
        display: 'flex',
        flexDirection: 'row',
      }"
    >
      <div
        :style="{
         // backgroundColor: 'greenyellow',
          width: '10%',
          height: '100%',
          display: 'flex',
          justifyContent: 'center',
          alignItems: 'center',
        }"
      >
      <img  :style="{
         // backgroundColor: 'orange',
          width: '50%',
          height: '70%',
          }" :src="logoURL">
      </div>
      <div
        :style="{
         // backgroundColor: 'orange',
          width: '20%',
          height: '100%',
          display: 'flex',
          justifyContent: 'center',
          alignItems: 'center',
        }"
      >
        <h3 :style="{
         color:'#FFFFFF'
        }">TINE</h3>
      </div>
      <div
        :style="{
         // backgroundColor: 'pink',
          width: '70%',
          height: '100%',
          display: 'flex',
          justifyContent: 'end',
          marginRight: '20px',
          alignItems: 'center',
        }"
      >
        <h3 :style="{
         color:'#FFFFFF'
         
        }">Contact us</h3>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "TLAHeader",
  computed: {
    logoURL() {
      return require('../assets/img/icon_lorem.png');
    },
  },
};
</script>
