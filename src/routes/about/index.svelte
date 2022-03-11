<script>
    import Container from "$lib/components/containers/container.svelte";
</script>

<Container>
    <!-- More info on being awesome -->
    <section class="bg-dark pb-8 px-4 sm:px-6 pt-24 lg:px-8">
        <div class="relative max-w-lg mx-auto lg:max-w-7xl">
            <div>
                <h2
                    class="text-2xl tracking-tight font-extrabold text-green-300 sm:text-4xl"
                >
                    About Fat Thunder
                </h2>
                <div
                    class="mt-3 sm:mt-4 lg:grid lg:grid-cols-2 lg:gap-5 lg:items-center"
                >
                    <p class="text-xl text-white">Who I am - what I do?</p>
                </div>
            </div>
            <div
                class="mt-1 pt-10 grid gap-16 lg:grid-cols-2 lg:gap-x-5 lg:gap-y-12"
            >
                <div>
                    <div href="#" class="mt-1 block">
                        <p class="text-3xl font-semibold text-green-400">
                            Work to live, not live to work.
                        </p>
                        <p class="mt-3 text-xl text-gray-300">
                            My house works to experience life. Not the other way
                            around.
                            <br />
                            <br />The unique skill-set make up of Fat Thunder
                            allows us to pick clients. With that, brings a
                            passion for product.
                            <span class="text-red-500">I love my work</span>!
                            <br />
                            <br />Whether personal or professional projects, we
                            guarantee the same commitment.
                        </p>
                    </div>
                </div>
                <div>
                    <div href="#" class="mt-1 block">
                        <p class="text-3xl font-semibold text-green-400">
                            Have fun and learn.
                        </p>
                        <p class="mt-3 text-xl text-gray-300">
                            So far in 2021,
                            <span class="text-green-300">Fat Thunder</span> has:
                        </p>
                        <ul class="ml-3 text-xl text-gray-200">
                            <li>- taught myself archery</li>
                            <li>- made a kid</li>
                            <li>- began work on <a href="https://www.croplike.com/" target="_blank">
                                <span
                                    class="font-bold text-indigo-400 hover:text-indigo-500"
                                    >Croplike</span
                                ></a
                            ></li>
                            <li>- hiked... a lot</li>
                        </ul>
                        <p class="mt-3 text-xl text-gray-300">
                            Remember that all work and no play === a loss of
                            production.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Who is Who section -->
    <section class="bg-dark pb-24">
        <div class="mx-auto px-4 max-w-7xl sm:px-6  lg:px-8">
            <div class="space-y-12">
                <div
                    class="space-y-5 sm:space-y-4 md:max-w-xl lg:max-w-3xl xl:max-w-none"
                >
                    <h2
                        class="text-4xl font-extrabold tracking-tight sm:text-4xl text-green-300"
                    >
                        My Team
                    </h2>
                    <p class="text-2xl text-white">
                        Cursed with being awesome.
                    </p>
                </div>
                <ul
                    class="space-y-12 sm:grid sm:grid-cols-2 sm:gap-x-6 sm:gap-y-12 sm:space-y-0 lg:grid-cols-3 lg:gap-x-8"
                >
                    <li>
                        <div class="space-y-4">
                            <div class="aspect-w-3 aspect-h-2">
                                <img
                                    class="object-cover shadow-lg rounded-lg"
                                    src="../assets/image01.jpg"
                                    alt
                                />
                            </div>
                            <div class="space-y-2">
                                <div
                                    class="text-lg leading-6 font-medium space-y-1"
                                >
                                    <h3 class="text-green-400">Ryan Orlando</h3>
                                    <p class="text-green-300">
                                        Web Developer / Consultant
                                    </p>
                                </div>
                                <ul class="flex space-x-5">
                                    <li>
                                        <a
                                            href="https://twitter.com/fat_thunder"
                                            class="text-gray-200 hover:text-blue-400"
                                        >
                                            <span class="sr-only">Twitter</span>
                                            <svg
                                                class="w-5 h-5"
                                                fill="currentColor"
                                                viewBox="0 0 20 20"
                                                aria-hidden="true"
                                            >
                                                <path
                                                    d="M6.29 18.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0020 3.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.073 4.073 0 01.8 7.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 010 16.407a11.616 11.616 0 006.29 1.84"
                                                />
                                            </svg>
                                        </a>
                                    </li>
                                    <li>
                                        <a
                                            href="https://www.linkedin.com/in/ryanorlando/"
                                            class="text-gray-200 hover:text-blue-500"
                                        >
                                            <span class="sr-only">LinkedIn</span
                                            >
                                            <svg
                                                class="w-5 h-5"
                                                fill="currentColor"
                                                viewBox="0 0 20 20"
                                                aria-hidden="true"
                                            >
                                                <path
                                                    fill-rule="evenodd"
                                                    d="M16.338 16.338H13.67V12.16c0-.995-.017-2.277-1.387-2.277-1.39 0-1.601 1.086-1.601 2.207v4.248H8.014v-8.59h2.559v1.174h.037c.356-.675 1.227-1.387 2.526-1.387 2.703 0 3.203 1.778 3.203 4.092v4.711zM5.005 6.575a1.548 1.548 0 11-.003-3.096 1.548 1.548 0 01.003 3.096zm-1.337 9.763H6.34v-8.59H3.667v8.59zM17.668 1H2.328C1.595 1 1 1.581 1 2.298v15.403C1 18.418 1.595 19 2.328 19h15.34c.734 0 1.332-.582 1.332-1.299V2.298C19 1.581 18.402 1 17.668 1z"
                                                    clip-rule="evenodd"
                                                />
                                            </svg>
                                        </a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </li>
                    <!-- More people... -->
                    <li>
                        <div class="space-y-4">
                            <div class="aspect-w-3 aspect-h-2">
                                <img
                                    class="object-cover shadow-lg rounded-lg"
                                    src="../assets/chloe0.png"
                                    alt
                                />
                            </div>

                            <div class="space-y-2">
                                <div
                                    class="text-lg leading-6 font-medium space-y-1"
                                >
                                    <h3 class="text-green-400">Chloe Orlando</h3>
                                    <p class="text-green-300">
                                        Chairwoman of Responsibility
                                    </p>
                                </div>
                                <ul class="flex space-x-5">
                                    <li>
                                        <a
                                            href="https://twitter.com/chloe_lunaire/"
                                            class="text-gray-200 hover:text-blue-400"
                                        >
                                            <span class="sr-only">Twitter</span>
                                            <svg
                                                class="w-5 h-5"
                                                fill="currentColor"
                                                viewBox="0 0 20 20"
                                                aria-hidden="true"
                                            >
                                                <path
                                                    d="M6.29 18.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0020 3.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.073 4.073 0 01.8 7.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 010 16.407a11.616 11.616 0 006.29 1.84"
                                                />
                                            </svg>
                                        </a>
                                    </li>
                                    <li>
                                        <a
                                            href="https://www.linkedin.com/in/chloe-orlando/"
                                            class="text-gray-200 hover:text-blue-500"
                                        >
                                            <span class="sr-only">LinkedIn</span
                                            >
                                            <svg
                                                class="w-5 h-5"
                                                fill="currentColor"
                                                viewBox="0 0 20 20"
                                                aria-hidden="true"
                                            >
                                                <path
                                                    fill-rule="evenodd"
                                                    d="M16.338 16.338H13.67V12.16c0-.995-.017-2.277-1.387-2.277-1.39 0-1.601 1.086-1.601 2.207v4.248H8.014v-8.59h2.559v1.174h.037c.356-.675 1.227-1.387 2.526-1.387 2.703 0 3.203 1.778 3.203 4.092v4.711zM5.005 6.575a1.548 1.548 0 11-.003-3.096 1.548 1.548 0 01.003 3.096zm-1.337 9.763H6.34v-8.59H3.667v8.59zM17.668 1H2.328C1.595 1 1 1.581 1 2.298v15.403C1 18.418 1.595 19 2.328 19h15.34c.734 0 1.332-.582 1.332-1.299V2.298C19 1.581 18.402 1 17.668 1z"
                                                    clip-rule="evenodd"
                                                />
                                            </svg>
                                        </a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </li>
                    <!-- More people... -->
                    <li>
                        <div class="space-y-4">
                            <div class="aspect-w-3 aspect-h-2">
                                <img
                                    class="object-cover shadow-lg rounded-lg"
                                    src="../assets/n3.jpg"
                                    alt
                                />
                            </div>

                            <div class="space-y-2">
                                <div
                                    class="text-lg leading-6 font-medium space-y-1"
                                >
                                    <h3 class="text-green-400">
                                        Nadja September
                                    </h3>
                                    <p class="text-green-300">
                                        "Bow before your queen!"
                                    </p>
                                </div>
                            </div>
                        </div>
                    </li>
                    <!-- More people... -->
                    <li>
                        <div class="space-y-4">
                            <div class="aspect-w-3 aspect-h-2">
                                <img
                                    class="object-cover shadow-lg rounded-lg"
                                    src="../assets/elly0.png"
                                    alt
                                />
                            </div>

                            <div class="space-y-2">
                                <div
                                    class="text-lg leading-6 font-medium space-y-1"
                                >
                                    <h3 class="text-green-400">Elly</h3>
                                    <p class="text-green-300">
                                        The ole bitch of morale
                                    </p>
                                </div>
                            </div>
                        </div>
                    </li>
                    <!-- More people... -->
                </ul>
            </div>
        </div>
    </section>
</Container>
