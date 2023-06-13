<template>
    <div class="grid grid-cols-12 gap-3 justify-evenly">

        <!-- Tool -->
        <div class="col-span-12 lg:col-span-8">
            <slot />
        </div>

        <!-- Sidebar -->
        <div class="col-span-12 lg:col-span-4">
            <div class="grid grid-cols-1 gap-2">

                <!-- SCleaner -->
                <div class="card bg-base-100">
                    <div class="card-body">

                        <h2 class="card-title">SCleaner</h2>
                        <hr class="my-2" />

                        <p>A Small and Simple System Cleanup Utility for Windows</p>

                        <a target="_blank"
                           href="https://shrewdsquad.com/products/scleaner"
                           class="mt-2 btn btn-primary">
                            Download Now
                        </a>

                    </div>
                </div>

                <!-- Related eTools -->
                <div class="card bg-base-100">
                    <div class="card-body">

                        <h2 class="card-title">Related eTools</h2>
                        <hr class="my-2" />

                        <div class="flex max-w-sm flex-col gap-2 text-left">
                            Coming Soon
                        </div>

                    </div>
                </div>

            </div>
        </div>

    </div>
</template>
