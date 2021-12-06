<template>
  <div class="bg-dark text-dark">
    <div class="row m-0 mt-5 justify-content-center">
      <div class="col-md-2"></div>
      <div class="col-md-8">
        <img class="elevation-3 mt-3 gtpBanner rounded" src="https://i.imgur.com/OWqYRIL.jpg" />
      </div>
      <div class="col-md-2"></div>
    </div>
    <div class="row m-0 mt-5 justify-content-around">
      <div class="col-md-3 card elevation-2 bg-light mt-3 p-3">
        <h5>Coming up for Gaming Theater Presents:</h5>
        <p>Currently, the remaining episodes of Chrono Trigger are being edited and
          posted to the GTP YouTube channel. There's still plenty of episodes left,
          so keep an eye out for the rest of that adventure!
        </p>
        <p>Currently, the team is recording episodes for Secret of Mana, as well as a
          few other side projects when ZombieHand (who is the one playing Scret of Mana for
          the team) can't make it to recordings. You can see Super Ghosts 'N' Ghouls, and soon
          there will be some Phasmophobia with several of the cast taking on new characters
          going on a ghost hunting adventure.
        </p>
        <img src="https://i.imgur.com/lKXYSl9.png">
      </div>
      <div class="col-md-3 card elevation-2 bg-light mt-3">
        BEHIND THE SCENES PHOTOS
      </div>
      <div class="col-md-3 card elevation-2 bg-light mt-3">
        <img class="mt-2" src="https://i.imgur.com/KnHIvZL.jpg" />
        <center>
          <h5>Currently Playing: Secret of Mana</h5>
        </center>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'Home'
  }
</script>

<style scoped lang="scss">
  .gtpBanner {
    max-width: 100%;
    height: auto;
  }
</style>