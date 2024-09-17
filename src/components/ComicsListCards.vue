<script>

export default {
  data() {
    return {

    }
  },

  props: {
    imgUrl: {
        type: String,
        required: true
    },
    comicsPrice: {
        type: String,
        required: true,
    },
    comicsSeries: {
        type: String,
        required: true,
    },
    comicsType: {
        type: String,
        required: true,
    }
  }
}

</script>

<template>
    <h1>
        COMICS CARD
    </h1>
</template>

<style lang="scss" scoped>
    h1 {
        color: white;
    }
</style>