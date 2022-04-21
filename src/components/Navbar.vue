<template>
    <div class="flex flex-row ">
        <div class="logo py-3 px-4 bg-gray-300 rounded-lg">
            <h1 class="text-gray-800 text-5xl lowercase font-semibold">Miracle.</h1>
            <p class="tracking-widest lowercase">frontend developer</p>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Navbar',
}
</script>

<style>
    .logo {
        border-radius: 50px;
        background: #e0e0e0;
        box-shadow:  20px 20px 60px #bebebe,
             -20px -20px 60px #ffffff;
    }
    .role{
        letter-spacing: 2px;
    }
</style>