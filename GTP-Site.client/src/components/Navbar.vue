<template>
  <div class="row m-0 headerBG">
    <div class="col-1 my-2">
      <button
        class="btn text-light"
        type="button"
        data-bs-toggle="offcanvas"
        data-bs-target="#offcanvasExample"
        aria-controls="offcanvasExample"
      >
        <img class="hamburger" src="https://i.imgur.com/9Kt26jI.png" />
      </button>

      <div
        class="offcanvas offcanvas-start offCanvasSize"
        tabindex="-1"
        id="offcanvasExample"
        aria-labelledby="offcanvasExampleLabel"
      >
        <div class="offcanvas-header">
          <h5 class="offcanvas-title" id="offcanvasExampleLabel">NAVIGATION</h5>
          <button
            type="button"
            class="btn-close text-reset"
            data-bs-dismiss="offcanvas"
            aria-label="Close"
          ></button>
        </div>
        <div class="offcanvas-body">
          <div>
            <ul class="me-auto">
              <router-link
                :to="{ name: 'Home' }"
                class="btn selectable offCanvasFont"
              >
                ⯁ Home
              </router-link>
              <br />
              <router-link
                :to="{ name: 'About' }"
                class="btn selectable offCanvasFont"
              >
                ⯁ About
              </router-link>
              <br />
              <router-link
                :to="{ name: 'Crew' }"
                class="btn selectable offCanvasFont"
              >
                ⯁ Meet the Crew
              </router-link>
            </ul>
          </div>
        </div>
      </div>
    </div>

    <div class="col-3 my-3">
      <router-link :to="{ name: 'Home' }">
        <img
          class="headerText"
          alt="logo"
          src="https://i.imgur.com/kk5u6j0.png"
        />
      </router-link>
    </div>
  </div>
</template>

<script>
import { AuthService } from '../services/AuthService'
import { AppState } from '../AppState'
import { computed } from 'vue'
export default {
  setup() {
    return {
      user: computed(() => AppState.user),
      async login() {
        AuthService.loginWithPopup()
      },
      async logout() {
        AuthService.logout({ returnTo: window.location.origin })
      }
    }
  }
}
</script>

<style scoped>
/* .dropdown-menu {
  user-select: none;
  display: block;
  transform: scale(0);
  transition: all 0.15s linear;
}
.dropdown-menu.show {
  transform: scale(1);
}
.hoverable {
  cursor: pointer;
}
a:hover {
  text-decoration: none;
}
.nav-link {
  text-transform: uppercase;
}
.navbar-nav .router-link-exact-active {
  border-bottom: 2px solid var(--bs-success);
  border-bottom-left-radius: 0;
  border-bottom-right-radius: 0;
} */
.hamburger {
  height: 1.5rem;
}
.headerBG {
  background-color: #c21e36;
}
.offCanvasFont {
  color: #1872cc;
}
.offCanvasSize {
  width: 20rem;
}
</style>
