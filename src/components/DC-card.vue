<template>
  <div class="dc_card">
    <div class="card_img">
      <img :src="img" :alt="title" />
    </div>
    <p>{{ title }}</p>
  </div>
</template>

<script>
export default {
  name: "DcCard",
  props: {
    img: String,
    title: String,
  },
};
</script>
