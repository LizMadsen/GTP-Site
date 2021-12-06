<template>
  <div class="row m-0 mt-5 justify-content-center">
    <div class="col-2 mt-3 mx-2 card elevation-2">
      <img class="mt-2" src="https://i.imgur.com/klS7Q0U.png" />
      <b><h5>Geek Scorpio</h5></b>
      <span>
        <a href="https://twitter.com/geek_scorpio"
          ><img class="socialsImg me-1" src="https://i.imgur.com/49GvGxp.png"
        /></a>
        <a href="https://www.instagram.com/geekscorpio/"
          ><img class="socialsImg" src="https://i.imgur.com/K9cb6IF.png"
        /></a>
      </span>
      <br />Founder, voice actor, researcher, writer, director, narrator
    </div>
    <div class="col-2 mt-3 mx-2 card elevation-2">
      <img class="mt-2" src="https://i.imgur.com/G3KqoKt.png" />
      <b><h5>ZombieHand</h5></b>
      [Socials go here]
      <br />
      <p>Artist, voice actor, researcher, writer, narrator</p>
    </div>
    <div class="col-2 mt-3 mx-2 card elevation-2">
      <img class="mt-2" src="https://i.imgur.com/GSXxNA5.png" />
      <b><h5>DnDaine</h5></b>
      [Socials go here]
      <br />
      <p>Voice actor, narrator</p>
    </div>
    <div class="col-2 mt-3 mx-2 card elevation-2">
      <img class="mt-2" src="https://i.imgur.com/i0tx6jv.png" />
      <b><h5>Rob</h5></b>
      [Socials go here]
      <br />
      <p>Voice actor, researcher, narrator</p>
    </div>
  </div>
  <div class="row m-0 justify-content-center">
    <div class="col-2 mt-3 mx-2 card elevation-2">
      <img class="mt-2" src="https://i.imgur.com/V9EgFdP.png" />
      <b><h5>Darien</h5></b>
      [Socials go here]
      <br />
      <p>Voice actor, writer, researcher, narrator</p>
    </div>
    <div class="col-2 mt-3 mx-2 card elevation-2">
      <img class="mt-2" src="https://i.imgur.com/CzhLJp2.png" />
      <b><h5>Arem the Red</h5></b>
      [Socials go here]
      <br />
      <p>Voice actor, narrator</p>
    </div>
    <div class="col-2 mt-3 mx-2 card elevation-2">
      <img class="mt-2" src="https://i.imgur.com/1iA2dT3.png" />
      <b><h5>Moontastical</h5></b>
      [Socials go here]
      <br />
      <p>Voice actor, narrator</p>
    </div>
    <div class="col-2 mt-3 mx-2 card elevation-2">CREW PAGE BITCH</div>
  </div>
</template>

<script>
export default {
  name: 'Home'
}
</script>

<style scoped lang="scss">
.home {
  display: grid;
  height: 80vh;
  place-content: center;
  text-align: center;
  user-select: none;
  .home-card {
    width: 50vw;
    > img {
      height: 200px;
      max-width: 200px;
      width: 100%;
      object-fit: contain;
      object-position: center;
    }
  }
}
.socialsImg {
  height: 1.5rem;
}
</style>
