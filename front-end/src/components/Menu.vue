<template>
  <div class="menu">
      <button>Home</button>
      <button>Quem somos</button>
      <button>Turmas</button>
      <button>Galeria de fotos</button>
      <button>Contato</button>
  </div>
</template>

<script>
export default {

}
</script>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@700&display=swap');

    .menu {
        display: grid;
        grid-template-columns: 1fr 1fr 1fr 1fr 1fr;
        margin-left: 221px;
        justify-items: center;
        align-items: center;
        position: relative;
        height: 100%;
    }

    button {
        font-family: 'Montserrat', sans-serif;
        font-size: 18px;
        color: #FFFFFF;
        background: transparent;
        border: none !important;
        height: 100%;
        width: 70%;
        border-radius: 50px;
    }

    button:hover {
        height: 100%;
        width: 90%;
        transition-duration: 300ms;
        border-radius: 17px;
        background-color: #10266d;
    }


</style>