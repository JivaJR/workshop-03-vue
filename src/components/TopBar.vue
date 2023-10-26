<template>
    <div class="top-header flex relative flex-nowrap items-center justify-between py-[0.3rem] px-[0.5rem] bg-[#f8f9fa]">
        <img alt="Peak logo" class="w-14 h-14" src="../assets/logo-blue.png"/>
        <div class="flex items-center">
            <div class="mr-2">
                <button class="mr-2 btn-my">
                    <img src="./icons/iconBell.svg" alt="bell">
                </button>
            </div>
            <div class="mr-2 flex items-center gap-2 btn-my">
                    <span class="p-1 rounded-[50%] bg-[#343a40] text-white">
                        <svg width="1em" height="1em" xmlns="http://www.w3.org/2000/svg" fill="currentColor" >
                            <path d="M8 8a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm2-3a2 2 0 1 1-4 0 2 2 0 0 1 4 0zm4 8c0 1-1 1-1 1H3s-1 0-1-1 1-4 6-4 6 3 6 4zm-1-.004c-.001-.246-.154-.986-.832-1.664C11.516 10.68 10.289 10 8 10c-2.29 0-3.516.68-4.168 1.332-.678.678-.83 1.418-.832 1.664h10z"/>
                        </svg>
                    </span>
                    <span class="text-black">
                        Javier
                    </span>
                </div>
        </div>
    </div>
</template>
<style scoped>
    .btn-my{
        background-color: transparent;
        border: none;
        padding: 0.5rem;
        border-radius: 5px;
    }
    .btn-my:hover{
        background-color: aquamarine;
        cursor: pointer
    }
    .top-header{
        box-shadow: 0 .5rem 1rem rgba(0,0,0,.15);
        border-bottom: 1px solid #dee2e6;
    }
    
</style>