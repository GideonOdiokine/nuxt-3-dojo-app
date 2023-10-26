<template>
  <div>
    <p>Product details for {{ id }}</p>
    <p>
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tempore
      assumenda, unde, cumque cum, aliquam provident dolorem totam libero
      asperiores saepe enim eligendi excepturi porro aut minus. Distinctio quod
      illum animi?
    </p>
  </div>
</template>

<script setup>
definePageMeta({
  layout: "products",
});
const { id } = useRoute().params;
</script>

<style lang="scss" scoped></style>
