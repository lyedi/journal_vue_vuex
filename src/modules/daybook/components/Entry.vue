<template>
  <div class="entry-container mb-3 poniter p-2"
  @click="$router.push({name: 'entry', params:{id:10}})"
  >

        <!-- Titulo -->
        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">03</span>
            <span class="mx-1 fs=5">06</span>
            <span class="mx02 fw-light">20222, viernes</span>
        </div>
        <div class="entry-description">
            Minim et labore enim eu quis labore sunt Lorem elit deserunt. 
            Incididunt magna minim excepteur proident reprehenderit consequat
            exercitation incididunt non veniam. Irure excepteur irure cupidatat pariatur quis laborum reprehenderit cillum ipsum. 
            Non id officia Lorem dolor eu. Ipsum sit adipisicing est dolor esse laboris officia minim qui proident tempor cillum. 
            Amet sunt cillum aliqua labore.
        </div>
    


  </div>
</template>
Lo
<script>
export default {

}
</script>

<style lang="scss">
.entry-container{
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;

    &:hover {
     background-color: lighten($color: grey, $amount: 45);
     transition: 0.2s all ease-in;
     }
     .entry-description{
         font-size: 15px;
     }
}



</style>