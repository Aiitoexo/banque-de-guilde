<template>
    <div class="main-color w-full h-12 shadow-2xl text-white text-2xl">
        <ul class="flex h-full w-full grid grid-cols-10 gap-x-2">
            <li class="col-span-1 flex items-center justify-center border-r-2 border-gray-700 border-opacity-30">
                <a :href="route('dashboard')">Compagnie</a>
            </li>

            <li class="col-span-1 flex items-center justify-center border-r-2 border-gray-700 border-opacity-30">
                <a :href="route('bank')">Banque</a>
            </li>

            <li class="col-span-1 flex items-center justify-center border-r-2 border-gray-700 border-opacity-30">
                <a :href="route('contribution')">Contribution</a>
            </li>

            <li class="col-span-1 flex items-center justify-center border-r-2 border-gray-700 border-opacity-30">
                <a :href="route('squad')">Escouade</a>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    name: "NavBar"
}
</script>

<style scoped>

</style>
