<template>
  <b-navbar class="navbar_cn" toggleable type="dark" variant="dark">
        <b-navbar-brand href="#" >
        <img class="icon_control_hamburger" src="hamburget.png" alt="" srcset="">
         <img class="icon_control_main" src="favicon.png" alt="" srcset="">
    </b-navbar-brand>

<div class="right_control">

        <b-nav-item>
               <img class="icon_control_manify" src="manify.png" alt="" srcset="">
        </b-nav-item>

    <b-nav-item-dropdown text="TH" right >
          <b-dropdown-item href="#">EN</b-dropdown-item>
          <b-dropdown-item href="#">ES</b-dropdown-item>
          <b-dropdown-item href="#">RU</b-dropdown-item>
          <b-dropdown-item href="#">FA</b-dropdown-item>
        </b-nav-item-dropdown>




</div>
  </b-navbar>
</template>


<style>
.navbar_cn{
    display: flex;
    flex-direction: row;
    align-content: center;
    align-items: center;
    padding: 40px 100px;
    background:#1f1e19 !important;
     height:140px;


}
.navbar_cn a{
    color: #fff !important;
}
.navbar_cn .dropdown-item{
    color: #000 !important;
}
.navbar_cn li{
    list-style-type: none;  
}
.navbar_cn img{
    
}
.right_control{
    display: flex;
    flex-direction: row;
}
.icon_control_hamburger{
    width: 50px;
}
.icon_control_main{
    width: 220px;
    margin-left: 30px;
}
.icon_control_manify{
    width: 30px;
}
</style>

