<script setup>
import { ref, onMounted, watchEffect, nextTick } from 'vue'
import HelloWorld from './components/HelloWorld.vue'
import Modal from './components/Modal.vue'

// const modal = ref(null)

// async function showModal(event){
//   modal.value.show = true
//   await nextTick()
// }

</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </header>

  <main class="container">
    <div class="interior">
      <a class="btn" href="#open-modal">Show Modal</a>
    </div>
  </main>

  <Modal id="open-modal" title="Demo">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam vitae finibus nibh. Donec sed est eu orci condimentum volutpat eu non velit. Maecenas at aliquet tortor, vel luctus nulla. Integer eget nunc pretium, finibus ligula quis, facilisis mi. Aenean a risus in dolor luctus dignissim in eget est. Nunc eu tellus est. Sed fringilla sagittis risus, eget facilisis velit maximus non. Duis consequat hendrerit sapien, sed elementum purus rhoncus eget. Nulla facilisi.
    Vestibulum fringilla lectus eget ex tempus dictum. Suspendisse cursus eros id tortor tincidunt facilisis. Etiam nulla ligula, dapibus ut orci fermentum, iaculis aliquam nisi. Aliquam erat volutpat. Curabitur viverra, lacus vestibulum consectetur dignissim, turpis libero dictum dui, vel dapibus turpis dui non lectus. Vivamus gravida hendrerit metus, fringilla accumsan diam feugiat a. Maecenas consectetur diam id mauris sollicitudin, id luctus orci malesuada.
    Fusce auctor mi maximus efficitur feugiat. Nam gravida condimentum lacus. Mauris placerat, lorem id volutpat accumsan, urna justo lobortis nulla, sed mattis augue lectus eu libero. Curabitur suscipit, justo at feugiat luctus, felis mi facilisis risus, et vehicula ipsum eros nec tortor. Aliquam erat volutpat. Nam consectetur risus a nibh tincidunt, sed blandit quam ullamcorper. Duis lobortis leo elementum, vulputate nisi et, bibendum lectus. In mi dui, rhoncus et velit nec, accumsan bibendum mauris. Aliquam lobortis eros ligula, ut pretium nibh pretium in. Pellentesque hendrerit pellentesque leo. In pharetra ipsum ex, eu convallis nibh molestie vitae. Nulla suscipit eu erat eu porta. Quisque laoreet euismod sodales. Quisque arcu justo, tincidunt quis varius vitae, venenatis sit amet sapien.
    Interdum et malesuada fames ac ante ipsum primis in faucibus. Pellentesque et tincidunt ligula, nec pharetra neque. Donec vel elit sit amet dolor ornare ullamcorper non id felis. Etiam vitae est et eros blandit sodales et eu enim. Aliquam in turpis velit. Maecenas ac ante odio. Morbi finibus lacinia interdum. Suspendisse potenti. Aenean lobortis metus quis turpis molestie lobortis. Etiam dictum at ligula at tincidunt. Suspendisse ullamcorper rhoncus erat eget volutpat.
    Maecenas dignissim erat a tortor sollicitudin eleifend. Sed magna tortor, fringilla pellentesque urna sed, molestie vestibulum ante. Vivamus tempor turpis dolor, non mollis odio aliquet at. Interdum et malesuada fames ac ante ipsum primis in faucibus. Morbi tempus, orci et ornare iaculis, nulla lectus ornare nunc, at facilisis justo leo consectetur nunc. Duis vel sapien at purus maximus elementum. Nunc consequat, justo ut viverra tempor, risus mi ultricies risus, non semper nunc tellus quis ante. Nunc ut enim ut ipsum ultrices venenatis commodo eget neque. Nunc fringilla metus a mi tincidunt, vel convallis neque volutpat. Mauris luctus varius faucibus. Etiam ultrices volutpat purus, in mollis sapien porttitor at.
  </Modal>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>


