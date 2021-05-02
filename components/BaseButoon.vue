<template>
  <div :class="`mb-10 mx-auto ${classPosition}`">
    <a
      :href="link"
      :class="`font-semibold md:text-lg xl:text-base px-4 md:px-5 xl:px-4 py-3 md:py-4 xl:py-3 leading-tight shadow-md ${classShape} ${classBackGroundColor} ${classBackGroundHoverColor} ${classTextColor}`"
    >
      {{ name }}
    </a>
  </div>
</template>

<script>
export default {}
</script>

<style></style>
