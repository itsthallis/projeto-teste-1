<template>
  <div>
    <b-row>
        <b-col>
            <card
                CardImage="https://source.unsplash.com/random/400x600"
                CardTitle="LG K40S"
                CardInfo="Moderno e funcional, o Smartphone LG K40s vai te surpreender. 
                Equipado com as últimas soluções tecnológicas, ele vai modificar por completo a forma como você interage com mundo,
                oferecendo recursos especiais para facilitar o seu dia a dia e economizar seu tempo."/></b-col>
        
        <b-col>
            <card
                CardImage="https://source.unsplash.com/random/800x600"
                CardTitle="iPhone 7"
                CardInfo="A Apple sempre procurando se superar a cada lançamento. E com o poderoso iPhone 7 
                não seria diferente. Além de ser resistente à água e respingos, que garante maior segurança 
                contra pequenos acidentes, conta também com sistema de alto-falantes estéreo e tela com mais 
                brilho e cores, que ampliam sua experiência visual, em imagens nitidamente mais brilhantes e 
                vívidas que se aproximam do real."/></b-col>

        <b-col>
            <card
                CardImage="https://source.unsplash.com/random/900x600"
                CardTitle="Moto G7 Play"
                CardInfo="Misturando coisas que realmente importam para você com modernidade e inovação, a 
                Lenovo apresenta o moto g7 play, um smartphone capaz de apresentar a tecnologia necessária 
                para que você tenha mais praticidade no seu dia a dia e descubra um universo de coisas incríveis."/></b-col>

        <b-col>
            <card
                CardImage="https://source.unsplash.com/random/700x600"
                CardTitle="Galaxy s10"
                CardInfo="Get the latest Galaxy experience on your phone. Update your software to explore the new features 
                now available to you. Lorem ipsum dolor sit amet consectetur adipisicing elit. Distinctio a, vero facilis fuga, 
                at reiciendis amet tempora maiores temporibus accusantium obcaecati assumenda voluptatibus iure earum similique 
                vitae minus ipsum sapiente."/></b-col>
    </b-row>
  </div>
</template>

<script>
import Card from './Card.vue'

export default {
  name: 'card-wrapper',

  components: {
      Card
  }
}
</script>

<style>

</style>
