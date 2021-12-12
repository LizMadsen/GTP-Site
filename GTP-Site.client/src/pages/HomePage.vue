<template>
  <div class="bg-dark text-dark">
    <div class="row m-0 mt-5 justify-content-center">
      <div class="col-md-2"></div>
      <div class="col-md-8">
        <img class="elevation-3 mt-3 gtpBanner rounded" src="https://i.imgur.com/OWqYRIL.jpg" />
      </div>
      <div class="col-md-2"></div>
    </div>
    <div class="row m-0 mt-3 justify-content-center">
      <div class="col-md-3 card elevation-2 bg-light mt-3 me-5 p-3">
        <h5>Coming up for Gaming Theater Presents:</h5>
        <p>Currently, the remaining episodes of Chrono Trigger are being edited and
          posted to the GTP YouTube channel. There's still plenty of episodes left,
          so keep an eye out for the rest of that adventure!
        </p>
        <p>Currently, the team is recording episodes for Secret of Mana, as well as a
          few other side projects when ZombieHand (who is the one playing Scret of Mana for
          the team) can't make it to recordings. You can see Super Ghouls 'N' Ghosts, and soon
          there will be some Phasmophobia with several of the cast taking on new characters
          going on a ghost hunting adventure.
        </p>
        <img src="https://i.imgur.com/lKXYSl9.png">
      </div>
      <div class="col-md-3 card elevation-2 bg-light mt-3 me-5 p-3">
        <img src=https://i.imgur.com/0Ch7P4C.png />
        <h4>Happy Holidays from everyone at Gaming Theater Presents!</h4>
        <p>If you're in need of some holiday cheer, look no further than GTP's Chrono Trigger
          rendition of The Twelve Days of Christmas!
        </p>
        <p>Can you believe how weirdly difficult it was to find a full, instrumental version of
          this song? But Geek Scorpio managed to find one, and then piece together the last
          parts of it to bring it all together to this final product.</p>
        <p>Also, as a member of the voice cast, this recording session was <i>so</i> fun!</p>
        <iframe width="375" height="200" src="https://www.youtube.com/embed/kCZ84B71SLo" title="YouTube video player"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen></iframe>
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