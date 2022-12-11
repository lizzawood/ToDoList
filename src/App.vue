<template>
  <div id="app2">
  
  </div>
</template>



<style>
*{
  box-sizing: border-box;
}
:root{
--checkbox-color:rgba(202,60,60);
--checkbox-shadow:rgba(238,156,167,0.2);
--add-button:rgba(255,255,255,0.7);
}
#app2{
  width: 100%;
  height:100vh;
  margin:0;
  padding:15px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-image: url("../src/assets/fondo-azul.jpg");
  overflow: hidden;
  font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  list-style: none;
}

input{
  outline: none;

}
ul{
  list-style: none;
  padding: 0;
}
.app-container{
  max-width: 480px;
  width: 100%;
  max-height:100% ;
  background-color: rgba(255,255,255,0.3);
  padding: 25px;
  border-radius: 25px;
  overflow: auto;
  color:#222;
}
.header-tolist{
  font-size: 20px;
  line-height: 32px;
  margin: 0 0 12px 0;
  text-align: center;
  color:#FFFFFF;
}

.btn-agregar{
  border-radius: 50%;
  cursor: pointer;
  size: 18px;
  flex-shrink: 0;
  border: none;
  width: 32px;
  height: 32px;

}
.btn-delete{
  color:red;
  font-weight: bold;
  margin-left: auto;
  margin-right: 5px;
  display: block;
  border-radius: 50%;
  cursor: pointer;
  size: 18px;
  flex-shrink: 0;
  border: none;
  width: 32px;
  height: 32px;

}

.agregar-tarea{

height:40px ;
font-size: 14px;
display: flex;
}
.agregar-input{
  width: 85%;
  padding: 0 5px;
  outline: none;
  border: none;
  border-bottom: 1px solid #ccc;
  background-color: transparent;
  margin-right: 15px;
  color: #272727;
box-shadow: none;
}
.agregar-input::placeholder{
  color: #272727;
}
.list-item{
  background-color: #FFFFFF;
  display: flex;
  align-items: center;
  padding: 8px;
  border-radius: 35px;
  margin-bottom: 12px;
}

.item-check{
width: 16px;
height: 16px;
border-radius: 50%;
border:  1px solid #272727;
flex-shrink: 0;
margin-top: 4px;
margin-right: 8px;
}

</style>
