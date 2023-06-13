<template>
    <footer class="footer footer-center  p-4 bg-base-100 rounded-lg shadow">

        <!--<div class="grid grid-flow-col gap-4">
            <a routerLink="/privacy" class="link link-hover">Privacy</a>
        </div>-->

        <div>
            <p>
                Copyright &copy; {{ currentYear }} -
                <a href="https://shrewdsquad.com/">ShrewdSquad</a> 
            </p>
        </div>

    </footer>
</template>

<script setup>
    let currentYear = new Date().getFullYear();
</script>