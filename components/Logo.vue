<template>
  <div class="Logo">
    <i class="fas fa-pepper-hot"></i>
  </div>
</template>

<style scope>
i.fas {
  color: #ab5ea5;
  font-size: larger;
  padding: 0.5rem 0.5rem;
  background: #ffdfa6;
  border-radius: 100%;
}

i.fas:hover {
  background: var(--color-purple);
}
i.fas:focus {
  background: var(--color-blue);
}
i.fas > .focusElement {
  background: var(--color-blue);
}
/* .VueToNuxtLogo {
  display: inline-block;
  animation: turn 1s linear forwards 0.3s;
  transform: rotateX(180deg);
  position: relative;
  overflow: hidden;
  height: 90px;
  width: 122px;
  border-radius: 15px;
}

.Triangle {
  position: absolute;
  top: 0;
  left: 0;
  width: 0;
  height: 0;
  border-radius: 15px;
}

.Triangle--one {
  border-left: 60px solid transparent;
  border-right: 60px solid transparent;
  border-bottom: 90px solid var(--color-pink);
  border-radius: 15px;
}

.Triangle--two {
  top: 30px;
  left: 35px;
  animation: goright 0.1s linear forwards 3.5s;
  border-left: 47px solid transparent;
  border-right: 47px solid transparent;
  border-bottom: 75px solid #fff;
  border-radius: 15px;
}

.Triangle--three {
  top: 60px;
  left: 35px;
  animation: goright 0.1s linear forwards 3.5s;
  border-left: 35px solid transparent;
  border-right: 35px solid transparent;
  border-bottom: 60px solid var(--color-turqouise);
  border-radius: 15px;
}

.Triangle--four {
  top: 120px;
  left: 70px;
  animation: godown 0.1s linear forwards 3s;
  border-left: 17px solid transparent;
  border-right: 17px solid transparent;
  border-bottom: 30px solid #fff;
  border-radius: 15px;
}

@keyframes turn {
  100% {
    transform: rotateX(0deg);
  }
}

@keyframes godown {
  100% {
    top: 180px;
  }
}

@keyframes goright {
  100% {
    left: 70px;
  }
} */
</style>
