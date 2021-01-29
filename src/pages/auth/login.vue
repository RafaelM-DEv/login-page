<template>
    <q-page class="login">
      <div class="login__modal shadow-7">
        <div class="logo column">
            <!-- TODO remover depois da documentação -->
          <!-- <img id="astronaut" src="../../assets/astronaut.png" alt="Astronaut"> -->
          <span class="anime_astronaut">
            <img id="astronaut" src="../../assets/astronaut.png" alt="Astronaut">
          </span>
          <div class="my-font text-red-6 logo__text">
              login.
          </div>
        </div>
        <div class="login__section column fit create animate__animated animate__fadeIn">
           <div class="q-mb-md my-font text-h5 text-cyan-7">login</div>
           <q-input class="q-mb-md" color="cyan-7" dense outlined  label="Email" type="email"/>
           <q-input color="cyan-7" dense outlined label="Password" type="password"/>
           <div class="q-gutter-md q-mt-sm">
             <q-btn flat class="bg-cyan-7 text-white" label="log in" />
             <q-btn flat label="sign up" />
             <!-- <q-btn flat label="sign up" @click="animate"  /> -->
           </div>
        </div>
      </div>
    </q-page>
</template>

<script>
export default {

  methods: {
    //   TODO implementar corretamente
    // animate () {
    //   const element = document.querySelector('.create')
    //   element.classList.add('animate__animated', 'animate__fadeOut')
    //   element.addEventListener('animationend', () => {
    //     this.$router.replace({ path: '/signup' })
    //   })
    // }
  }
}
</script>
