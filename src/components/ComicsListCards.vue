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
    <article>
        <a href="#"><img :src="comicsImgUrl" alt=""></a>
        <div>
            <p>{{ comicsSeries }}</p>
        </div>
        
    </article>
</template>

<style lang="scss" scoped>

    article {
        width: calc(100% / 6);

            img {
                width: 200px;
                height: 200px;
                object-fit: cover;
                display: block;
                margin-left: auto;
                margin-right: auto;
                margin-bottom: 15px;
            }

            p {
                color: white;
                text-align: center;
                margin-bottom: 50px;
            }
        }
</style>