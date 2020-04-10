<template>
  <div id="card">
    <b-row>
      <b-col
        v-for = "post in posts"
        :key = "post.id">
        <b-card
            :title = "post.title"
            :img-src = "post.img"
            img-alt="Image"
            img-top
            tag="article"
            style="max-width: 20rem;"
            class="mb-2"
        >
          <b-card-text class="small text-muted">{{ post.author }}</b-card-text>
          <b-button href="#" variant="primary">Comprar</b-button>
        </b-card>
      </b-col>
    </b-row>
  </div>
</template>

<script>

export default {
  name: 'Card',

  data() {
    return { posts: [] }
  },

  props: {

  },
  mounted() {
    this.axios
      .get( "http://localhost:3000/posts" )
      .then( response => ( this.posts = response.data ))
  }
}
</script>

<style>

</style>
