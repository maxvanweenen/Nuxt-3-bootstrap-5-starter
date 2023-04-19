<template>
  <div class="container-fluid">
    <h2>I am loaded from a page!</h2>

    <!-- Button trigger js modal -->
    <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">
      Launch demo modal
    </button>

    <!-- Modal -->
    <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="modal-header">
            <h5 class="modal-title" id="exampleModalLabel">Modal title</h5>
            <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
          </div>
          <div class="modal-body">
            I am bootstrap modal using JS!
          </div>
          <div class="modal-footer">
            <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
          </div>
        </div>
      </div>
    </div>

    <!--  Example how you could render api data -->
    <!--  <div v-for="video in videos.data">-->
    <!--    <nuxt-link to="/">-->
    <!--      Title-->
    <!--    </nuxt-link>-->
    <!--  </div>-->

  </div>

</template>

<script setup>
// load your data, for example:
// const {data: videos} = await useFetch('http://localhost:1337/api/videos')
</script>
