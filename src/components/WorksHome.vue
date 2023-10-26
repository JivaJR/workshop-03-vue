<script setup>
const data = {
    items: [
        {   id: 1, 
            icon:'/ofertas/datacenter.jpg',
            name: 'Desarrollador Java', 
            empresa:'Datacenter Colombia',
            place:'remoto',
            skills:[{id:'skill1',name:'java'},{id:'skill2',name:'java'}],
            salary:'5M - 5.2M COP',
            vacantes:'4',
            publicacion:'hace 7 horas'
        },
        {   id: 2, 
            icon:'/ofertas/vichara.jpeg',
            name: 'Ejecutivo de ventas bilingue', 
            empresa:'VICHARA TECHNOLOGIES',
            place:'remoto',
            skills:[{id:'skill1',name:'Cold prospecting'},{id:'skill2',name:'Business'}],
            salary:'condifencial',
            vacantes:'1',
            publicacion:'hace 3 dias'
        },
        {   id: 3, 
            icon:'/ofertas/datacenter.jpg',
            name: 'Desarrollador Java', 
            empresa:'Datacenter Colombia',
            place:'remoto',
            skills:[{id:'skill1',name:'java'},{id:'skill2',name:'java'}],
            salary:'5M - 5.2M COP',
            vacantes:'4',
            publicacion:'hace 7 horas'
        },
        {   id: 4, 
            icon:'/ofertas/vichara.jpeg',
            name: 'Ejecutivo de ventas bilingue', 
            empresa:'VICHARA TECHNOLOGIES',
            place:'remoto',
            skills:[{id:'skill1',name:'Cold prospecting'},{id:'skill2',name:'Business'}],
            salary:'condifencial',
            vacantes:'1',
            publicacion:'hace 3 dias'
        },
        {   id: 5, 
            icon:'/ofertas/datacenter.jpg',
            name: 'Desarrollador Java', 
            empresa:'Datacenter Colombia',
            place:'remoto',
            skills:[{id:'skill1',name:'java'},{id:'skill2',name:'java'}],
            salary:'5M - 5.2M COP',
            vacantes:'4',
            publicacion:'hace 7 horas'
        },
        {   id: 6, 
            icon:'/ofertas/vichara.jpeg',
            name: 'Ejecutivo de ventas bilingue', 
            empresa:'VICHARA TECHNOLOGIES',
            place:'remoto',
            skills:[{id:'skill1',name:'Cold prospecting'},{id:'skill2',name:'Business'}],
            salary:'condifencial',
            vacantes:'1',
            publicacion:'hace 3 dias'
        },
        {   id: 7, 
            icon:'/ofertas/datacenter.jpg',
            name: 'Desarrollador Java', 
            empresa:'Datacenter Colombia',
            place:'remoto',
            skills:[{id:'skill1',name:'java'},{id:'skill2',name:'java'}],
            salary:'5M - 5.2M COP',
            vacantes:'4',
            publicacion:'hace 7 horas'
        },
        {   id: 8, 
            icon:'/ofertas/vichara.jpeg',
            name: 'Ejecutivo de ventas bilingue', 
            empresa:'VICHARA TECHNOLOGIES',
            place:'remoto',
            skills:[{id:'skill1',name:'Cold prospecting'},{id:'skill2',name:'Business'}],
            salary:'condifencial',
            vacantes:'1',
            publicacion:'hace 3 dias'
        },
        {   id: 9, 
            icon:'/ofertas/datacenter.jpg',
            name: 'Desarrollador Java', 
            empresa:'Datacenter Colombia',
            place:'remoto',
            skills:[{id:'skill1',name:'java'},{id:'skill2',name:'java'}],
            salary:'5M - 5.2M COP',
            vacantes:'4',
            publicacion:'hace 7 horas'
        },
        {   id: 10, 
            icon:'/ofertas/vichara.jpeg',
            name: 'Ejecutivo de ventas bilingue', 
            empresa:'VICHARA TECHNOLOGIES',
            place:'remoto',
            skills:[{id:'skill1',name:'Cold prospecting'},{id:'skill2',name:'Business'}],
            salary:'condifencial',
            vacantes:'1',
            publicacion:'hace 3 dias'
        },
        ]
}
</script>

<template>
    <div>
        <ul>
            <li v-for="(item) in data.items" :key="item.id">
                <div class="m-2 flex flex-row items-center border rounded-md text-black">
                    <div class="justify-center items-center p-3">
                        <img class='rounded h-16 w-16' :src="item.icon" alt="">
                    </div>
                    <div class="flex flex-col justify-center p-3 w-full gap-4">
                        <div class="flex flex-row gap-2">
                            <h2 class="font-bold text-2xl">
                                {{ item.name }}
                            </h2>
                            <div v-for="(skill) in item.skills" :key="item.id + skill.id" class="flex px-2 justify-center items-center rounded-2xl border">
                                <span>{{ skill.name }}</span>
                            </div>
                        </div>
                        <div class="hidden md:flex justify-between w-full">
                            <div class="flex flex-row gap-1">
                                <img src="/icons/works/place.svg" alt="">
                                <span>{{ item.empresa }}</span>
                            </div>
                            <div class="flex flex-row gap-1">
                                <img src="/icons/works/iconMap.svg" alt="">
                                <span>{{ item.place }} </span>
                            </div>
                            <div class="flex flex-row gap-1">
                                <img src="/icons/works/bill.svg" alt="">
                                <span> {{ item.salary }}</span>
                            </div>
                            <div class="flex flex-row gap-1">
                                <img src="/icons/works/vacantes.svg" alt="">
                                <span>{{ item.vacantes }} vacantes</span>
                            </div>
                            <div class="flex flex-row gap-1">
                                <img src="/icons/works/calendar.svg" alt="">    
                                <span>{{ item.publicacion }}</span>
                            </div>
                        </div>
                    </div>
                </div>
            </li>
        </ul>
    </div>
</template>
<style scoped>

</style>