<template>
<div class="container">
  <div class="centerMenu">
  <div class="logo">
    <nuxt-link to="#"><img class="krisha" src="@/assets/kolesa.png"></nuxt-link>
  </div>
  <div class="menu">

    <ul>
      <li><nuxt-link to="#">Машины</nuxt-link></li>
      <li><nuxt-link to="#">Авто от Kolesa.kz<span class="New">New</span></nuxt-link></li>
      <li><nuxt-link to="#">Новые авто</nuxt-link></li>

      <li><nuxt-link to="#">Запчасти</nuxt-link></li>
      <li><nuxt-link to="#">Ремонт и услуги</nuxt-link></li>
      <li><nuxt-link to="#">Коммерческие</nuxt-link></li>
      <li><nuxt-link to="#">Прочитать</nuxt-link></li>
      <li><nuxt-link to="#">Гид</nuxt-link></li>
    </ul>
  </div>
  <div class="btn">
    <button >Подать заявление</button>

  </div>
</div>
  <span class="peoples"> 415 567 уже на сайте</span>
  <div class="background-color">
    <p>Kolesa Batlle</p>
</div>
</div>

</template>

<script>
export default {
  name: "TheHeader"
}
</script>

<style scoped >
.container{

  max-width: 1180px;
  margin: 0 auto;

}
.centerMenu{
  display: flex;
  justify-content: space-between;
}
.menu{
  display: flex;
  justify-content: space-between;
  font-size: 14px;
}
.menu ul{
  display: flex;

}
.menu li {
  padding: 0 8px;

}
a{
  text-decoration:none;
  color:#2a81dd;}

li{
  list-style-type: none;
  /*padding: 0 5% ;*/
}
.peoples{
 display: flex;
 justify-content: flex-end;
}
.New{
background-color: #f33;
color: #fff;
border-radius: 3px;
margin-left: 3px;
padding: 2px 4px ;
}
.krisha{
  width: 149px;
}
.btn button{

  border: none;
   outline: none;
   color:#2a81dd;
   cursor:pointer;
   font-size: 14px;
   min-width: 188px;
 min-height: 36px;
 border-radius: 8px;
    border: 1px solid rgba(42,129,221,.1);
    background: #fff;
    box-shadow: 0 2px 4px rgba(28,24,25,.1);
    transition: box-shadow .3s ease;
    cursor:pointer;
}
.btn {
  display: flex;
  justify-content: center;

}
.filter{
  display: flex;

}
.searchButton{
color:#fff;
background-color:#2a81dd;
border: none;
border-radius: 3px;
padding: 5px 15px;
margin-right: 10px;
}
.buttonsSearch{
display: flex;
margin: 1%;
}
.map{
  display: flex;
  border:none;
  align-content: center;
  border-radius: 3px;
}
.map img{
  height: 13px;
  margin-right: 3px;

}
.background-color{
  width: 100%;
  background-color: #fae8bb;
  height: 10vh;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 26px;
}
.checkbox{
  display: flex;

}
#checkbox1{
  /* margin: 0 20px; */
  padding: 10px 20px;
  display: flex;
  align-items: flex-start;
}
.newBuildings{

border-radius: 3px;

}
.newBuildings :hover{
  background: white;
border-radius: 3px;

}
.hoverNewBuildings {
  background: #fde8a3;
}
.hoverNewBuildings a  {
display: none;
}
.hoverNewBuildings p  {
  display: none;
}

.hoverNewBuildings:hover{
  background: white;
  color: black;
position: relative;
display:block;
  /* border:  solid black 2px; */
}
.kursor{
  position: relative;
  top:15px ;
  left:10px;
 height:20px;
 transform: rotate(-35deg);
}
.categories{
  margin:1%;
}
.categories select{
  margin: 0 5px;
  font-size: 12px;
  color:grey;
}
.filter1{
  margin: 1%;
}
.filter1 input{
  width: 4vw;
  font-size: 12px;
}





</style>
