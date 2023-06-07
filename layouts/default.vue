<template>
    <div class="drawer bg-base-300">

        <input id="my-drawer-3" type="checkbox" class="drawer-toggle" />

        <div class="drawer-content flex flex-col">
            <Header />
            <div class="p-2"><slot /></div>
            <Footer />
        </div>

        <div class="drawer-side rounded">
            <Sidebar />
        </div>

    </div>
</template>
