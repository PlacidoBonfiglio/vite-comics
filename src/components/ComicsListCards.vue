<script>

export default {
  data() {
    return {

    }
  },

  props: {
    comicsImgUrl: {
        type: String,
        required: true
    },
    comicsPrice: {
        type: String,
        required: false,
    },
    comicsSeries: {
        type: String,
        required: true,
    },
    comicsType: {
        type: String,
        required: false,
    }
  }
}

</script>

<template>
    <section id="comics" class="row">
        <div>
            <a href="#"><img :src="comicsImgUrl" alt=""></a>
            <a href="#">{{ comicsSeries }}</a>
        </div>
    </section>
</template>

<style lang="scss" scoped>
    #comics {
        width: 100%;

        div {
            text-align: center;

            img {
                height: 200px;
                width: 200px;
                object-fit: cover;
            }

            a {
                color: white;
                text-align: center;
            }
        }
    }
</style>