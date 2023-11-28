<template> 
<v-card class="mx-auto" >
 <h1 class="text">Los más populares</h1>
  <div class="conteiner">
      <Card
        v-for="(card, index) in cards"
        :key="index"
        :imageSrc="card.imageSrc"
        :title="card.title"
        :subtitle="card.subtitle"
      />
</div>
<h1 class="text">Secundaria</h1>
<div class="conteiner">
      <Card
        v-for="(card, index) in cards2"
        :key="index"
        :imageSrc="card.imageSrc"
        :title="card.title"
        :subtitle="card.subtitle"
      />
</div>
</v-card>
</template>

<script>
import Card from '@/components/Card.vue'; 

export default {
  components: {
    Card,
  },
  data() {
    return {
      cards: [
        { imageSrc: 'https://picsum.photos/200/300?random=3', title: 'Geografía', subtitle: 'Lorem, ipsum dolor sit Quos quae nobis corrupti suscipit architecto epellat doloribus' },
        { imageSrc: 'https://picsum.photos/200/300?random=1', title: 'Historia', subtitle: 'Lorem, ipsum dolor sit Quos quae nobis corrupti suscipit architecto epellat doloribus' },
        { imageSrc: 'https://picsum.photos/200/300?random=5', title: 'Matematicas', subtitle: 'Lorem, ipsum dolor sit Quos quae nobis corrupti suscipit architecto epellat doloribus' },
        { imageSrc: 'https://picsum.photos/200/300?random=2', title: 'Español', subtitle: 'Lorem, ipsum dolor sit Quos quae nobis corrupti suscipit architecto epellat doloribus' },
       
        
      ],
      cards2: [
        { imageSrc: 'https://picsum.photos/200/300?random=7', title: 'Geografía', subtitle: 'Lorem, ipsum dolor sit Quos quae nobis corrupti suscipit architecto epellat doloribus' },
        { imageSrc: 'https://picsum.photos/200/300?random=8', title: 'Historia', subtitle: 'Lorem, ipsum dolor sit Quos quae nobis corrupti suscipit architecto epellat doloribus' },
        { imageSrc: 'https://picsum.photos/200/300?random=9', title: 'Matematicas', subtitle: 'Lorem, ipsum dolor sit Quos quae nobis corrupti suscipit architecto epellat doloribus' },
        { imageSrc: 'https://picsum.photos/200/300?random=6', title: 'Español', subtitle: 'Lorem, ipsum dolor sit Quos quae nobis corrupti suscipit architecto epellat doloribus' },
       
        
      ],
    };
  },
 
};
</script>

<style scoped>
.conteiner{
display: flex;
padding: 6% 10px 50px 10px;
margin-top: 35px;
margin-left: 15%;
background-color: #F1F2F4;
width: 90%;
border-radius: 10px;
}

.text{
  position: absolute;
  padding-left: 18%;
  padding-top: 4%;
  font-size: x-large;

}
</style>