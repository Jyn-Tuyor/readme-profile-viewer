<template>
  <main class="p-8">
    <div class="readme-container p-2 shadow-2xl bg-black/50">
      <div class="flex flex-col justify-center items-center">
        <div v-if="rendered">
          <div v-html="rendered"></div>
        </div>
      </div>
    </div>
  </main>
</template>

<script>
export default {
  props: {
    rendered: String,
  },
};
</script>
