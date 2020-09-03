<template>
  <footer>
    <span>
      Copyright <strong>Ayrton de Souza</strong> © 2010-2020
    </span>
  </footer>
</template>

<script>
export default {
  name: "Footer"
};
</script>

<style>
footer {
  grid-area: footer;
  background-color: #ddd;
  color: #333;
  width: 100%;

  display: flex;
  align-items: center;
  justify-content: flex-end;
  
}
  span {
    margin-right: 10px;
  }

</style>