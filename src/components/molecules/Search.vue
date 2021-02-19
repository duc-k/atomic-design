<template>
  <form class="search">
    <input type="text" placeholder="Buscar" />
    <button type="submit">
      <img src="@/assets/images/icons/search.svg" alt="Buscar" />
    </button>
  </form>
</template>

<style lang="scss" scoped>
.search {
  position: relative;
  width: max-content;

  input {
    border: none;
    border-radius: 1rem;
    padding: 0.5rem 1rem;
    box-shadow: 0 5px 5px rgba(#000, 0.08);

    &::placeholder {
      color: #a9b0be;
    }
  }

  button {
    top: 50%;
    right: 3px;
    width: 30px;
    height: 30px;
    border: none;
    display: grid;
    position: absolute;
    border-radius: 5rem;
    background: #ff895f;
    justify-items: center;
    align-content: center;
    transform: translateY(-50%);
  }
}
</style>
