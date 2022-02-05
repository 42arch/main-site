<template>
  <div class="what">
    <div id="content">
      <p id="first"> What can I hold you with? </p>
      <p> I offer you lean streets, desperate sunsets, the
          moon of the jagged suburbs. </p>
      <p> I offer you the bitterness of a man who has looked
          long and long at the lonely moon. </p>
      <p> I offer you my ancestors, my dead men, the ghosts
          that living men have honoured in bronze:
          my father's father killed in the frontier of
          Buenos Aires, two bullets through his lungs,
          bearded and dead, wrapped by his soldiers in
          the hide of a cow; my mother's grandfather
          --just twentyfour-- heading a charge of
          three hundred men in Peru, now ghosts on
          vanished horses. </p>
      <p> I offer you whatever insight my books may hold, 
          whatever manliness or humour my life. </p>
      <p> I offer you the loyalty of a man who has never
          been loyal. </p>
      <p> I offer you that kernel of myself that I have saved,
          somehow --the central heart that deals not
          in words, traffics not with dreams, and is
          untouched by time, by joy, by adversities. </p>
      <p> I offer you the memory of a yellow rose seen at
          sunset, years before you were born. </p>
      <p> I offer you explanations of yourself, theories about
          yourself, authentic and surprising news of 
          yourself. </p>
      <p> I can give you my loneliness, my darkness, the
          hunger of my heart; I am trying to bribe you 
          with uncertainty, with danger, with defeat. </p>
    </div>

    <div class="nav">
      <Navigation></Navigation>
    </div>

  </div>
</template>

<script setup lang="ts">
// import { ref } from 'vue'
import Navigation from "../components/Navigation.vue";

</script>


<style lang="scss" scoped>
  .what {
    color: aliceblue;
    font-size: 1.2rem;
    width: 100vw;
    min-height: 100vh;
    height: auto;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background-color: #081421;

    #content {
      padding: 0 2rem;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: flex-start;
      flex-wrap: wrap;

      p {
        margin-block: 0;
        margin: .3rem 0;
      }

      #first {
        color: red;
        font-size: 1.5rem;
        font-weight: bolder;
      }
    }

    .nav {
      margin: 3rem 0;
    }
  }
</style>