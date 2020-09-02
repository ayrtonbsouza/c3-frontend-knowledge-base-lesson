<template>
  <footer>
    <span>Copyright <strong>Ayrton de Souza ©</strong> 2010-2020</span>
  </footer>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<style>
  .footer {
    grid-area: footer;
    background-color: #DDD;
    color: #333;

    display: flex;
    align-items: center;
    justify-content: flex-end;
    padding-right: 10px;
  }
</style>