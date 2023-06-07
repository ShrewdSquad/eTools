<template>
    <footer class="footer footer-center gap-y-2 p-4 bg-base-100 text-base-content rounded sticky top-[100vh] shadow">

        <div class="grid grid-flow-col gap-4">
            <!--<a routerLink="/privacy" class="link link-hover">Privacy</a>-->
        </div>

        <div>
            <p>Copyright &copy; {{ currentYear }} - ShrewdSquad</p>
        </div>

    </footer>
</template>

<script setup>
    let currentYear = new Date().getFullYear();
</script>