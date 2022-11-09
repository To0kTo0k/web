<template>
    <div>
        <header>      
            <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
                <div class="container-fluid">
                    <!-- Site logo (image and text) -->
                    <router-link class="navbar-brand" :to="{name:'home'}" >
                        <img src="../../assets/mainPageLogo.jpg" width="50" class="d-inline-block align-text-center" alt="">
                        <div class="d-inline">Print4U</div> 
                    </router-link>
                    <!-- Site toggler -->
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation" data-target="#collapse-target">
                        <span class="navbar-toggler-icon"></span>
                    </button>
                    <!-- Site menu -->
                    <div class="collapse navbar-collapse" id="navbarNav">
                        <ul class="navbar-nav">
                            <li class="nav-item">
                              <router-link class="nav-link" aria-current="page" :to="{name:'home'}">Главная</router-link>
                            </li>
                            <li class="nav-item">
                              <router-link class="nav-link" :to="{name:'review'}">Отзывы</router-link>
                            </li>
                            <li class="nav-item">
                              <router-link class="nav-link" :to="{name:'about'}">Контакты</router-link>
                            </li>
                            <li class="nav-item">
                              <router-link class="nav-link" :to="{name:'login'}">Войти</router-link>
                            </li>
                        </ul>
                    </div>
                </div>
            </nav>
        </header>
    </div>
</template>

<script>
    export default {
        name: "Header"
    }
</script>

<style scoped>
    header{
        background-color: lightblue;
    }
    nav.navbar {
        background-color: lightblue;
        padding: 0;
    }
    nav.nav-link {
        color: #fff;
    }
    nav.navbar-toggler-icon {

    }
    nav.nav-link:hover {
        color: #ddd;
    }
    header.container {
        display: flex;
        flex-direction: row;
        align-items: center;
    }
    header.logo img {
        width: 200px;
    }
    header nav{
        margin-left: auto;
    }
    header nav ul {
        display: flex;
        list-style: none;
        color: #fff;
        padding: 0;
        margin: 0;
    }
    header nav ul li {
        padding: 15px 15px;
    }

    .router-link-active,
    .nav-link:focus,
    .nav-link:hover
    {
        color: #fff;
    }
</style>