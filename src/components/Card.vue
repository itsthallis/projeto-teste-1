<template>
  <div id="card">
    <b-card
        v-bind:title = CardTitle
        v-bind:img-src = CardImage
        img-alt="Image"
        img-top
        tag="article"
        style="max-width: 20rem;"
        class="mb-2"
    >
        <b-card-text class="small text-muted">{{ CardInfo }}</b-card-text>

        <b-button href="#" variant="primary">Comprar</b-button>
    </b-card>
  </div>
</template>

<script>

export default {
  name: 'Card',

  props: {
    CardInfo : String,
    CardTitle : String,
    CardImage : String
  }
}
</script>

<style>

</style>
