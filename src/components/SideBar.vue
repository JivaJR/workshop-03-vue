<script setup>
    import SideBarItem from './SideBarItem.vue';
    const MENU_ITEMS = {
        items: [
            { id: 1, icon:'/icons/sidebar/portFolio.svg',name: 'Empleos'},
            { id: 2, icon:'/icons/sidebar/postulaciones.svg',name: 'Postulaciones'},
            { id: 3, icon:'/icons/sidebar/cursos.svg',name: 'Cursos'},
            { id: 4, icon:'/icons/sidebar/preguntas.svg',name: 'Preguntas'},
            { id: 5, icon:'/icons/sidebar/bootcamp.svg',name: 'Bootcamp'},
            { id: 6, icon:'/icons/sidebar/premios.svg',name: 'Premios'},
            { id: 7, icon:'/icons/sidebar/cv.svg',name: 'Tu Cv'},
        ]
    }
</script>
<template>
    <button class="w-6 h-6 rounded-full fixed z-10 text-black bg-red-200 left-[77px] bottom-14">b</button>
    <div class="m-0 p-0 flex flex-col border-r w-[90px] bg-white fixed left-0 h-full overflow-x-hidden">
        <ul class="mt-2 flex flex-col items-center">
            <li class="flex justify-center items-center text-center w-[80px] overflow-hidden" v-for="(item) in MENU_ITEMS.items" :key="item.id">
                <SideBarItem>
                    <template #icon>
                        <img :src='item.icon' :alt="item.name" style="width: 20px; height: 20px;">
                    </template>
                    <template #heading>{{ item.name }}</template>
                </SideBarItem>
            </li>
        </ul>
    </div>
</template>