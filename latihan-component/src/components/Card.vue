<template>
  <div class="bg-white p-4 border-radius-25">
    <a href="#" class="chairs">
        <img class="border-radius-25"
            :src="require('@/assets/img/' + cardImage + '.png')">
    </a>
    <p class="font-weight-bold mt-3 my-0">{{ cardTitle }}</p>
    <p>IDR {{ cardPrice }}</p>

  </div>
</template>

<script>
export default {
    name : "CardComponent",
    props : ["cardTitle", "cardPrice", "cardImage"]
}
</script>

<style>

</style>