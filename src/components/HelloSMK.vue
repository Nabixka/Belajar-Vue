<script setup>
import { ref } from 'vue';

const hitung = ref(0)

</script>

<template>
    <div class="flex flex-col gap-10 justify-center align-center items-center pt-10">
        <h1 class="text-4xl font-bold text-red-500">Belajar Vue</h1>
        <div class="text-md">
            <h4>Nama: Fadhil</h4>
            <h4>Grade: XI-RPL</h4>
            <h4>Origin: Jakarta</h4>
        </div>
        <div class="flex gap-10 text-sm">
            <h6>083806331362</h6>
            <h6>nabixka05@gmail.com</h6>
        </div>
        <button class="w-1/4 bg-gray-300 font-bold rounded shadow-lg" type="submit" @click="hitung++">Jumlah hitungan {{ hitung }}</button>
    </div>
</template>

<style scoped>

</style>