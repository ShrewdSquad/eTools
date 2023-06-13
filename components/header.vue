<template>
    <div class="navbar bg-base-100 rounded-lg shadow">

        <div class="navbar-start">
            <label for="my-drawer-3" class="btn btn-square btn-ghost">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h7" />
                </svg>
            </label>
        </div>

        <div class="navbar-center">
            <NuxtLink to="/" class="btn btn-ghost normal-case text-xl">eTools</NuxtLink>
        </div>

        <div class="navbar-end">

            <button class="btn btn-ghost btn-circle">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
                </svg>
            </button>

            <button class="btn btn-ghost btn-circle" onclick="notifications.showModal()">
                <div class="indicator">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9" />
                    </svg>
                    <span class="badge badge-xs badge-primary indicator-item"></span>
                </div>
            </button>

        </div>

    </div>

    <!-- Notifications Modal -->
    <dialog id="notifications" class="modal">
        <form method="dialog" class="modal-box">
            <h3 class="font-bold text-lg">Hi there, thanks for using eTools!</h3>
            <p class="pt-4 pb-1">
                The site is in very early stage of development!
                <br />
                <br />
                <small>~ ShrewdSquad</small>
            </p>
            <div class="modal-action mt-1">
                <button class="btn btn-primary">Awesome!</button>
            </div>
        </form>
    </dialog>
</template>