<template>
    <header class="header">
        <div class="logo">
            <img src="../assets/letra-j.gif" alt="">
            <span>effrin</span> 
        </div>
        <nav class="nav"><img src="../assets/menu.png" alt=""></nav>

        
    </header>
</template>

<style>
    .header{
        width: 100%;
        display: flex;
        border-bottom: 2px solid rgb(159, 245, 185);
        justify-content: space-between;
        box-shadow: 0 0 10px rgb(98, 221, 135);
        position: fixed;top: 0;
        background-color: rgb(255, 255, 255);
    }
    .logo{
        width: 4%;
        padding: 0px 10px;
        display: flex ;
        cursor: pointer;
        
    }
    .logo img{
        width: 40px;

    }
    .logo span{
        margin-top: 20%;
        font-weight: 900;
        font-size: 20px;

    }
    .nav{
        width: 4%;
        padding: 0px 60px;
    }
    .nav img{
        width: 40px;
        cursor: pointer;
    }
</style>