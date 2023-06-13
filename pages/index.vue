<template>

    <!-- Hero -->
    <div class="card bg-base-100 shadow">
        <div class="card-body items-center text-center">

            <h2 class="card-title">eTools by ShrewdSquad</h2>
            <p class="">An evergrowing collection of online Tools &amp; Utilities </p>

            <br />
            <a class="btn btn-primary" onclick="notifications.showModal()">Read More</a>
        </div>
    </div>

    <!-- Tools -->
    <div class="py-2 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-3 justify-evenly">
        <div class="card bg-base-100 shadow" v-for="tool in tools">
            <div class="card-body items-center text-center">

                <h2 class="card-title">
                    {{tool.name}}
                </h2>

                <p class="_text-medium my-5 _text-gray-700">
                    A Small, Simple and Straight Forward
                    <br />
                    {{tool.description}}
                </p>

                <NuxtLink :to="tool.url" class="btn-useTool">
                    Use Tool
                </NuxtLink>

            </div>
        </div>
    </div>

</template>

<script setup>

    let tools = [
        {
            name: 'Tool 1',
            description: 'Dummy Tool 1',
            url: '/tools/dummy-tool',
        },
        {
            name: 'Tool 2',
            description: 'Dummy Tool 2',
            url: '/tools/dummy-tool',
        },
        {
            name: 'Tool 3',
            description: 'Dummy Tool 3',
            url: '/tools/dummy-tool',
        },
        {
            name: 'Tool 4',
            description: 'Dummy Tool 4',
            url: '/tools/dummy-tool',
        },
    ];

</script>
