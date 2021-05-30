<template>
    <div class="slidecont">
        <hooper class="photos" :autoPlay="true" :playSpeed="2500" :infiniteScroll="true" :transition="1000" :touchDrag="false" :shortDrag="false" :rtl="true" :itemsToShow="3">
        <slide>
          <img src="../assets/1.jpg">
        </slide>
        <slide>
          <img src="../assets/2.jpg">
        </slide>
        <slide>
          <img src="../assets/3.jpg">
        </slide>
      </hooper>  
    </div>
</template>

<script>
import { Hooper, Slide } from 'hooper';
import 'hooper/dist/hooper.css';

export default {
    name: 'App',
    components: {
      Hooper,
      Slide
    }
  }

</script>

<style scoped>
.slidecont{
    display: flex;
    justify-content: flex-start;
    
}

.photos{
      margin-top: 7px;
      height: auto;
      display: flex;
      justify-content: center;
}

img{
  height: 745px;
  width: 1000px;
  align-items: center;
}

@media screen and (max-width: 1200px) {
  img{
    width: auto;
    height: 500px;
    align-items: center;
  }
}
</style>