<template>
    <div class="drawer bg-base-300">

        <input id="my-drawer-3" type="checkbox" class="drawer-toggle" />

        <div class="drawer-content flex flex-col min-h-screen">
            <Header />
            <div class="p-2"><slot /></div>
            <Footer  class="mt-auto"/>
        </div>

        <div class="drawer-side">
            <Sidebar />
        </div>

    </div>
</template>
