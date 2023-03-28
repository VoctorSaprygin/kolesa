<template>
  <div class="centrV">
    <div class="PpP">
      <p>
        Выберите марку
      </p>
      <p>
        Выбирите Модель
      </p>
      <p>
        Год выпуска
      </p>
    </div>
    <div id="Inputs">

      <select name="select">
        <option value="value#" selected></option>
        <option value="value#">Значение 1</option>
        <option value="value#">Значение 3</option>
      </select>


      <select name="select">
        <option value="value#" selected></option>
        <option value="value#">Значение 1</option>
        <option value="value#">Значение 3</option>
      </select>


      <select name="select">
        <option value="value#" selected></option>
        <option value="value#">Значение 1</option>
        <option value="value#">Значение 3</option>
      </select>
    </div>
    <div>
      <NuxtLink to="battle">
      <button id="search">Найти
        </button>
    </NuxtLink>
    </div>
  </div>
</template>

<script>
export default {
  name: "Battle"
}
</script>

<style scoped>
.centrV{
  display: flex;
  align-items: center;
  justify-content: center;
  height: 50vh;

}
.centrV select{
  display: flex;
  flex-direction: column;
  margin: 15px;

}
#search{
  display: flex;
  align-items: center;
  border: none;
  cursor: pointer;
  font-size: 17px;
  padding: 0.3em 1.2em;
  border: transparent;
  box-shadow: 2px 2px 4px rgba(0,0,0,0.4);
  background: dodgerblue;
  color: white;
  border-radius: 4px;
}
 a {
  text-decoration: none;

}


</style>
