<script setup></script>
<template>
  <div class="input-wrap">
    <input type="text" />
    <button>CREATE</button>
  </div>
</template>

<style lang="scss" scoped>
.input-wrap {
  display: flex;
  transition: 250ms ease;
  border: 2px solid #b0b0b0;

  &:focus-within {
    box-shadow: 0 -4px 6px -1px rgb(0 0 0 / 0.1),
      0 -2px 4px -2px rgb(0 0 0 / 0.1);
  }

  input {
    width: 100%;
    padding: 8px 6px;
    border: none;

    &:focus {
      outline: none;
    }
  }

  button {
    padding: 8px 16px;
    border: none;
    background-color: #b0b0b0;
  }
  button:hover {
    background-color: #919191;
    cursor: pointer;
    transition: all;
    transition-duration: 300ms;
  }
}
</style>
