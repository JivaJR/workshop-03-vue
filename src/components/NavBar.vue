
<template>
    <div class="grid sm:grid-cols-2 grid-cols-1 items-center justify-between w-full py-2 px-10 bg-[#3a8ced] text-white gap-5 top-0 sticky">
        <div class="flex flex-row w-full bg-white rounded-md menu-my">
            <img src="./icons/lupa.svg" class="p-2">
            <input type="text" placeholder='Busca por cargo, salario, ubicacion o empresa' class="w-[95%] ml-1 p-2 border-none">
        </div>
        <div class="flex gap-2 flex-wrap justify-center">
            <div class="relative inline-block text-left">
                <button type="button" class="inline-flex w-full justify-center gap-x-1.5 rounded-md bg-white px-3 py-2 text-sm font-semibold shadow-sm ring-1 ring-inset ring-gray-300" aria-expanded="true" aria-haspopup="true">
                    Área
                    <svg class="-mr-1 h-5 w-5 " viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
                        <path fill-rule="evenodd" d="M5.23 7.21a.75.75 0 011.06.02L10 11.168l3.71-3.938a.75.75 0 111.08 1.04l-4.25 4.5a.75.75 0 01-1.08 0l-4.25-4.5a.75.75 0 01.02-1.06z" clip-rule="evenodd" />
                    </svg>
                </button>
            </div>
            <div class="relative inline-block text-left">
                <button type="button" class="inline-flex w-full justify-center gap-x-1.5 rounded-md bg-white px-3 py-2 text-sm font-semibold shadow-sm ring-1 ring-inset ring-gray-300" aria-expanded="true" aria-haspopup="true">
                    Cargo
                    <svg class="-mr-1 h-5 w-5 " viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
                        <path fill-rule="evenodd" d="M5.23 7.21a.75.75 0 011.06.02L10 11.168l3.71-3.938a.75.75 0 111.08 1.04l-4.25 4.5a.75.75 0 01-1.08 0l-4.25-4.5a.75.75 0 01.02-1.06z" clip-rule="evenodd" />
                    </svg>
                </button>
            </div>
            <div class="relative inline-block text-left">
                <button type="button" class="inline-flex w-full justify-center gap-x-1.5 rounded-md bg-white px-3 py-2 text-sm font-semibold shadow-sm ring-1 ring-inset ring-gray-300" aria-expanded="true" aria-haspopup="true">
                    Salario
                    <svg class="-mr-1 h-5 w-5 " viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
                        <path fill-rule="evenodd" d="M5.23 7.21a.75.75 0 011.06.02L10 11.168l3.71-3.938a.75.75 0 111.08 1.04l-4.25 4.5a.75.75 0 01-1.08 0l-4.25-4.5a.75.75 0 01.02-1.06z" clip-rule="evenodd" />
                    </svg>
                </button>
            </div>
            <div class="relative inline-block text-left">
                <button type="button" class="inline-flex w-full justify-center gap-x-1.5 rounded-md bg-white px-3 py-2 text-sm font-semibold shadow-sm ring-1 ring-inset ring-gray-300" aria-expanded="true" aria-haspopup="true">
                    Ubicación
                    <svg class="-mr-1 h-5 w-5 " viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
                        <path fill-rule="evenodd" d="M5.23 7.21a.75.75 0 011.06.02L10 11.168l3.71-3.938a.75.75 0 111.08 1.04l-4.25 4.5a.75.75 0 01-1.08 0l-4.25-4.5a.75.75 0 01.02-1.06z" clip-rule="evenodd" />
                    </svg>
                </button>
            </div>
        </div>
    </div>
</template>
<style scoped>
.menu-my{
    border: solid 2px gray;
}
    button{
        color: white;
        border: solid white 1px;
        border-radius: 50rem;
        background-color: transparent
    }
    button:hover{
        cursor: pointer;
        color: black;
        background-color: white;
    }
</style>