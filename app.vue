<template>
  <div>
    <div class="bg-theme1 p-3">
      <h1 class="text-white d-inline-block">Ready to build something awesome!&nbsp;</h1>
      <div class="spinner-border text-white" role="status">
        <span class="visually-hidden">Loading...</span>
      </div>
    </div>
    <NuxtPage />
  </div>
</template>

<script>
export default {
  head() {
    return {
      script: [
        {
          src: "https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js",
        },
      ]
    }
  }
}
</script>
