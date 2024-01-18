<template>
    <section class="bg-indigo-100 rounded p-5 text-gray-700">
        <div class="container mx-auto">
            <div class="flex">
                <a href="" class="text-3xl font-bold pr-5 border-r border-indigo-500 mr-5">Kavisoftek</a>

                <div class="my-auto">
                    <button class="lg:hidden">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                            stroke="currentColor" class="w-6 h-6">
                            <path stroke-linecap="round" stroke-linejoin="round"
                                d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25H12" />
                        </svg>
                    </button>

                    <ul class="flex font-bold text-gray-600 hidden lg:flex">
                        <li class="pr-5"><a class="px-3 py-2 border border-indigo-100 hover:border-indigo-300 rounded"
                                href="">Home</a></li>
                        <li class="pr-5"><a class="px-3 py-2 border border-indigo-100 hover:border-indigo-300 rounded"
                                href="">About</a></li>
                        <li class="pr-5"><a class="px-3 py-2 border border-indigo-100 hover:border-indigo-300 rounded"
                                href="">Service</a></li>
                        <li class="pr-5"><a class="px-3 py-2 border border-indigo-100 hover:border-indigo-300 rounded"
                                href="">Contact</a></li>
                    </ul>

                </div>

                <a href="" class="ml-auto font-bold bg-indigo-600 rounded px-3 py-2 text-white flex"> <svg
                        xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                        stroke="currentColor" class="w-6 h-6">
                        <path stroke-linecap="round" stroke-linejoin="round"
                            d="m3.75 13.5 10.5-11.25L12 10.5h8.25L9.75 21.75 12 13.5H3.75Z" />
                    </svg>
                    <span class="hidden lg:block">&nbsp;Get Started</span></a>

            </div>
            <ul class="font-bold text-gray-600 lg:hidden">
                <li class="mt-1"><a class="py-2"
                        href="">Home</a></li>
                <li class="mt-1"><a class="py-2"
                        href="">About</a></li>
                <li class="mt-1"><a class="py-2"
                        href="">Service</a></li>
                <li class="mt-1"><a class="py-2"
                        href="">Contact</a></li>
            </ul>
        </div>
    </section>
</template>

<script>
export default {
    name: 'NavBar',
}
</script>

<style scoped></style>