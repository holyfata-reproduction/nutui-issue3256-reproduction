<template>
  <div class="wrapper1">
    <p>
      <nut-ellipsis direction="end" :content="title" />
    </p>
    <p>
      {{ title }}
    </p>
  </div>
  <div class="wrapper2">
    <p>
      <nut-ellipsis direction="end" :content="title" />
    </p>
    <p>
      {{ title }}
    </p>
  </div>
</template>

<script setup lang="ts">
const title = "我校在人工智能技术论坛，发表了一我校在人工智能技术论坛术论坛术论哈"
</script>
<style lang="scss">
.wrapper1 {
  width: 100%;
  font-size: 23px;
}
.wrapper2 {
  width: 100%;
  font-size: 24px;
}
</style>
