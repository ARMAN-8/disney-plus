<template>
    <div id="app" class="flex bg-gray-900 text-white min-h-screen">
        <link rel="stylesheet"
              href="https://use.fontawesome.com/releases/v5.2.0/css/all.css"
              integrity="sha384-hWVjflwFxL6sNzntih27bfxkr27PmbbK/iSvJ+a4+0owXq79v+lsFkW54bOGbiDQ"
              crossorigin="anonymous">
        <div class="nav w-24 fixed min-h-screen text-gray-500 flex justify-center items-center">
            <sidebar-navgation>

            </sidebar-navgation>
            <ul>
                <li class="mb-10">
                    <a href="#" class="hover:text-white">
                        <i class="myIconSize fas fa-search"/>
                    </a>
                </li>
                <li class="mb-10">
                    <a href="#" class="hover:text-white">
                        <i class="myIconSize fas fa-home"/>
                    </a>
                </li>
                <li class="mb-10">
                    <a href="#" class="hover:text-white">
                        <i class="myIconSize fas fa-plus"/>
                    </a>
                </li>
                <li class="mb-10">
                    <a href="#" class="hover:text-white">
                        <i class="myIconSize fas fa-film"/>
                    </a>
                </li>
                <li class="mb-10">
                    <a href="#" class="hover:text-white">
                        <i class="myIconSize fas fa-tv"/>
                    </a>
                </li>
                <li class="mb-10">
                    <a href="#" class="hover:text-white">
                        <i class="myIconSize fas fa-star"/>
                    </a>
                </li>
                <li class="mb-10">
                    <a href="#" class="hover:text-white">
                        <i class="myIconSize fas fa-cog"/>
                    </a>
                </li>
            </ul>
        </div>
        <div class="w-full ml-24">
            <div class="container mx-auto">
                <router-view/>
            </div>
        </div>
    </div>
</template>

<script>
    /*import {sidebarNavigation} from './components/sidebarNavigation'*/

    export default {
        components: {
            /*sidebarNavigation*/
        }
    };
</script>

<style>
    @import "assets/css/tailwind.css";
    @import "assets/css/main.css";
</style>
