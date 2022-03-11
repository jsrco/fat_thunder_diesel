<script>
    import Container from "$lib/components/containers/container.svelte";
</script>

<Container>
    <section
        class="flex pt-24 pb-8 mx-auto max-w-md px-4 sm:max-w-3xl sm:px-6 lg:px-8 lg:max-w-7xl text-gray-300 lg:flex-row flex-col-reverse items-center justify-evenly"
    >
        <div>
            <h4 class="text-4xl font-extrabold text-blue-500">
                Ryan Orlando
            </h4>
            <p class="mt-1">
                <span class="text-blue-400 font-bold">Web Developer</span>
                <span class="text-yellow-400 font-bold">&nbsp;/&nbsp;</span>
                <span class="text-blue-400 font-bold">IT Support</span>
                <span class="text-yellow-400 font-bold">&nbsp;/&nbsp;</span>
                <span class="text-blue-400 font-bold">Broadcast Production</span>
            </p>

            <div class="mt-6 flex">
                <div
                    class="mr-4 flex-shrink-0 md:h-12 md:w-12 rounded-md flex items-center justify-center"
                >
                    <svg
                        xmlns="http://www.w3.org/2000/svg"
                        class="text-blue-300"
                        viewBox="0 0 20 20"
                        fill="currentColor"
                    >
                        <path
                            fill-rule="evenodd"
                            d="M12.316 3.051a1 1 0 01.633 1.265l-4 12a1 1 0 11-1.898-.632l4-12a1 1 0 011.265-.633zM5.707 6.293a1 1 0 010 1.414L3.414 10l2.293 2.293a1 1 0 11-1.414 1.414l-3-3a1 1 0 010-1.414l3-3a1 1 0 011.414 0zm8.586 0a1 1 0 011.414 0l3 3a1 1 0 010 1.414l-3 3a1 1 0 11-1.414-1.414L16.586 10l-2.293-2.293a1 1 0 010-1.414z"
                            clip-rule="evenodd"
                        />
                    </svg>
                </div>
                <div class="pr-7">
                    <h4 class="text-lg text text-blue-400 font-bold">
                        Programming Languages:
                    </h4>
                    <p>
                        With a focus on
                        <a href="https://vuejs.org/" target="_blank">
                            <span
                                class="font-bold text-indigo-400 hover:text-indigo-500"
                                >Vue.js</span
                            >
                        </a> and <a href="https://svelte.dev/" target="_blank">
                            <span
                                class="font-bold text-indigo-400 hover:text-indigo-500"
                                >Svelte</span
                            >
                        </a>
                    </p>
                    <p class="text-blue-200">
                        <span class="text-blue-400 font-extrabold">[</span>
                        JavaScript
                        <span class="text-blue-400 font-extrabold">,</span> Rust
                        <span class="text-blue-400 font-extrabold">,</span> C#
                        <span class="text-blue-400 font-extrabold">]</span>
                    </p>
                </div>
            </div>
            <div class="mt-6 flex">
                <div
                    class="mr-4 flex-shrink-0 md:h-12 md:w-12 rounded-md flex items-center justify-center"
                >
                    <svg
                        xmlns="http://www.w3.org/2000/svg"
                        class="text-blue-300"
                        fill="none"
                        viewBox="0 0 24 24"
                        stroke="currentColor"
                    >
                        <path
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            stroke-width="2"
                            d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"
                        />
                    </svg>
                </div>
                <div class="pr-7">
                    <h4 class="text-lg text-blue-400 font-bold">
                        Scrum or Agile:
                    </h4>
                    <p class="mt-1">
                        Worked with teams from different disciplines and
                        workflows.
                    </p>
                    <p class="text-blue-200">
                        <span class="text-blue-400 font-extrabold">[</span>
                        Jira
                        <span class="text-blue-400 font-extrabold">,</span>
                        Trello
                        <span class="text-blue-400 font-extrabold">,</span>
                        Slack
                        <span class="text-blue-400 font-extrabold">
                        <span class="text-blue-400 font-extrabold">]</span>
                    </p>
                </div>
            </div>
            <div class="mt-6 flex">
                <div
                    class="mr-4 flex-shrink-0 md:h-12 md:w-12 rounded-md flex items-center justify-center"
                >
                    <svg
                        xmlns="http://www.w3.org/2000/svg"
                        class="text-blue-300"
                        fill="none"
                        viewBox="0 0 24 24"
                        stroke="currentColor"
                    >
                        <path
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            stroke-width="2"
                            d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z"
                        />
                    </svg>
                </div>
                <div class="pr-7">
                    <h4 class="text-lg text-blue-400 font-bold">
                        Responsive Problem Solving
                    </h4>
                    <p class="mt-1">
                        Metric improvements on all projects and workflows.
                    </p>
                    <p class="text-blue-200">
                        <span class="text-blue-400 font-extrabold">[</span>
                        Customer Curiosity
                        <span class="text-blue-400 font-extrabold">,</span>
                        Collaboration
                        <span class="text-blue-400 font-extrabold">,</span>
                        Creative Problem-solving
                        <span class="text-blue-400 font-extrabold">]</span>
                    </p>
                </div>
            </div>
        </div>
        <div class="mr-4 mb-4 flex-shrink-0">
            <img
                class="object-cover shadow-lg rounded-lg"
                src="./assets/image0.jpg"
                alt="Fat Thunder hiking in Issaquah"
            />
        </div>
    </section>

    <section class="relative bg-dark py-16">
        <div
            class="mx-auto max-w-md px-4 text-center sm:max-w-3xl sm:px-6 lg:px-8 lg:max-w-7xl"
        >
            <h2
                class="text-3xl font-semibold tracking-wider text-yellow-300 uppercase"
            >
                Portfolio
            </h2>
            <p
                class="mt-2 text-2xl font-extrabold text-white tracking-tight sm:text-4xl"
            >
                Experience
                <span class="text-yellow-400 font-black">&nbsp;/&nbsp;</span
                >Education
            </p>
            <p class="mt-5 max-w-prose mx-auto text-xl text-gray-100">
                A work ethic that is a force of nature. Change... is the law of
                life.
            </p>
            <div class="mt-12">
                <div
                    class="grid grid-cols-1 gap-8 sm:grid-cols-2 lg:grid-cols-3"
                >
                <div class="pt-6">
                    <div class="flow-root bg-dark rounded-lg px-6 pb-8">
                        <div class="-mt-6">
                            <div>
                                <span
                                    class="md:h-24 md:w-24 inline-flex items-center justify-center p-3 text-blue-400 rounded-md shadow-lg"
                                >
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                    <path d="M11 17a1 1 0 001.447.894l4-2A1 1 0 0017 15V9.236a1 1 0 00-1.447-.894l-4 2a1 1 0 00-.553.894V17zM15.211 6.276a1 1 0 000-1.788l-4.764-2.382a1 1 0 00-.894 0L4.789 4.488a1 1 0 000 1.788l4.764 2.382a1 1 0 00.894 0l4.764-2.382zM4.447 8.342A1 1 0 003 9.236V15a1 1 0 00.553.894l4 2A1 1 0 009 17v-5.764a1 1 0 00-.553-.894l-4-2z" />
                                  </svg>
                                </span>
                            </div>
                            <h3
                                class="mt-1 text-sm text-yellow-300 tracking-tight font-bold"
                            >
                                Vue Engineer
                            </h3>
                            <h3
                                class="text-lg font-bold text-indigo-400 hover:text-indigo-500 tracking-tight"
                            >
                                <a
                                    href="https://www.evidentchange.org/"
                                    target="_blank">Evident Change</a
                                >
                            </h3>
                        </div>
                    </div>
                </div>

                    <div class="pt-6">
                        <div class="flow-root bg-dark rounded-lg px-6 pb-8">
                            <div class="-mt-6">
                                <div>
                                    <span
                                        class="md:h-24 md:w-24 inline-flex items-center justify-center p-3 text-blue-400 rounded-md shadow-lg"
                                    >
                                        <svg
                                            xmlns="http://www.w3.org/2000/svg"
                                            viewBox="0 0 20 20"
                                            fill="currentColor"
                                        >
                                            <path
                                                d="M5 3a2 2 0 00-2 2v2a2 2 0 002 2h2a2 2 0 002-2V5a2 2 0 00-2-2H5zM5 11a2 2 0 00-2 2v2a2 2 0 002 2h2a2 2 0 002-2v-2a2 2 0 00-2-2H5zM11 5a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2V5zM14 11a1 1 0 011 1v1h1a1 1 0 110 2h-1v1a1 1 0 11-2 0v-1h-1a1 1 0 110-2h1v-1a1 1 0 011-1z"
                                            />
                                        </svg>
                                    </span>
                                </div>
                                <h3
                                    class="mt-1 text-sm text-yellow-300 tracking-tight font-bold"
                                >
                                    <span class="text-blue-200">Freelance</span>
                                    <span class="text-yellow-400 font-black"
                                        >&nbsp;/&nbsp;</span
                                    >Web Developer
                                </h3>
                                <h3
                                    class="text-lg font-bold text-indigo-400 hover:text-indigo-500 tracking-tight"
                                >
                                    <a
                                        href="https://openfin.co/"
                                        target="_blank">OpenFin.co</a
                                    >
                                </h3>
                                <ul class="text-base text-gray-200">
                                    <li class="mt-5">
                                        Built new cms web components in
                                        <a
                                            href="https://vuejs.org/"
                                            target="_blank"
                                        >
                                            <span
                                                class="font-bold text-indigo-400 hover:text-indigo-500"
                                                >Vue.js</span
                                            > / JSX
                                        </a>
                                        and
                                        <a
                                            href="https://tailwindcss.com/"
                                            target="_blank"
                                        >
                                            <span
                                                class="font-bold text-indigo-400 hover:text-indigo-500"
                                                >Tailwind CSS</span
                                            >
                                        </a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>

                    <div class="pt-6">
                        <div class="flow-root bg-dark rounded-lg px-6 pb-8">
                            <div class="-mt-6">
                                <div>
                                    <span
                                        class="md:h-24 md:w-24 inline-flex items-center justify-center p-3 text-blue-400 rounded-md shadow-lg"
                                    >
                                        <svg
                                            xmlns="http://www.w3.org/2000/svg"
                                            viewBox="0 0 20 20"
                                            fill="currentColor"
                                        >
                                            <path
                                                fill-rule="evenodd"
                                                d="M6 2a2 2 0 00-2 2v12a2 2 0 002 2h8a2 2 0 002-2V7.414A2 2 0 0015.414 6L12 2.586A2 2 0 0010.586 2H6zm2 10a1 1 0 10-2 0v3a1 1 0 102 0v-3zm2-3a1 1 0 011 1v5a1 1 0 11-2 0v-5a1 1 0 011-1zm4-1a1 1 0 10-2 0v7a1 1 0 102 0V8z"
                                                clip-rule="evenodd"
                                            />
                                        </svg>
                                    </span>
                                </div>
                                <h3
                                    class="mt-1 text-sm text-yellow-300 tracking-tight font-bold"
                                >
                                    <span class="text-blue-200">Freelance</span>
                                    <span class="text-yellow-400 font-black"
                                        >&nbsp;/&nbsp;</span
                                    >Content Distribution Model
                                </h3>
                                <h3
                                    class="text-lg font-bold text-indigo-400 hover:text-indigo-500 tracking-tight"
                                >
                                    <a
                                        href="https://techability.education/"
                                        target="_blank">TechAbility.Education</a
                                    >
                                </h3>
                                <ul class="text-base text-gray-200">
                                    <li class="mt-5">
                                        Advised on class system implementation
                                    </li>
                                    <li class="mt-5">
                                        Reduced impact on staffing by
                                        <span class="font-bold text-blue-400"
                                            >40%</span
                                        >
                                    </li>
                                    <li class="mt-5">
                                        Interview teaching, coding, and
                                        curriculum production candidates
                                    </li>
                                    <li class="mt-5">
                                        Develop new training widgets using
                                        <a
                                            href="https://vuejs.org/"
                                            target="_blank"
                                        >
                                            <span
                                                class="font-bold text-indigo-400 hover:text-indigo-500"
                                                >Vue.js</span
                                            >
                                        </a>
                                        and
                                        <a
                                            href="https://tailwindcss.com/"
                                            target="_blank"
                                        >
                                            <span
                                                class="font-bold text-indigo-400 hover:text-indigo-500"
                                                >Tailwind CSS</span
                                            >
                                        </a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>

                    <div class="pt-6">
                        <div class="flow-root bg-dark rounded-lg px-6 pb-8">
                            <div class="-mt-6">
                                <div>
                                    <span
                                        class="md:h-24 md:w-24 inline-flex items-center justify-center p-3 text-blue-400 rounded-md shadow-lg"
                                    >
                                        <svg
                                            xmlns="http://www.w3.org/2000/svg"
                                            viewBox="0 0 20 20"
                                            fill="currentColor"
                                        >
                                            <path
                                                d="M8.433 7.418c.155-.103.346-.196.567-.267v1.698a2.305 2.305 0 01-.567-.267C8.07 8.34 8 8.114 8 8c0-.114.07-.34.433-.582zM11 12.849v-1.698c.22.071.412.164.567.267.364.243.433.468.433.582 0 .114-.07.34-.433.582a2.305 2.305 0 01-.567.267z"
                                            />
                                            <path
                                                fill-rule="evenodd"
                                                d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-13a1 1 0 10-2 0v.092a4.535 4.535 0 00-1.676.662C6.602 6.234 6 7.009 6 8c0 .99.602 1.765 1.324 2.246.48.32 1.054.545 1.676.662v1.941c-.391-.127-.68-.317-.843-.504a1 1 0 10-1.51 1.31c.562.649 1.413 1.076 2.353 1.253V15a1 1 0 102 0v-.092a4.535 4.535 0 001.676-.662C13.398 13.766 14 12.991 14 12c0-.99-.602-1.765-1.324-2.246A4.535 4.535 0 0011 9.092V7.151c.391.127.68.317.843.504a1 1 0 101.511-1.31c-.563-.649-1.413-1.076-2.354-1.253V5z"
                                                clip-rule="evenodd"
                                            />
                                        </svg>
                                    </span>
                                </div>
                                <h3
                                    class="mt-1 text-sm text-yellow-300 tracking-tight font-bold"
                                >
                                    <span class="text-blue-200"
                                        >Front End Web Developer</span
                                    >
                                    <span class="text-yellow-400 font-black"
                                        >&nbsp;/&nbsp;</span
                                    >Marketing Team
                                </h3>
                                <h3
                                    class="text-lg font-bold text-indigo-400 hover:text-indigo-500 tracking-tight"
                                >
                                    <a
                                        href="https://chroniclesofelyria.com/"
                                        target="_blank">Soulbound Studios</a
                                    >
                                </h3>
                                <ul class="text-base text-gray-200">
                                    <li class="mt-5">
                                        Implemented and maintained community
                                        engagement events generating
                                        <span class="font-bold text-blue-400"
                                            >$4 million</span
                                        > in crowdfunding
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>

                    <div class="pt-6">
                        <div class="flow-root bg-dark rounded-lg px-6 pb-8">
                            <div class="-mt-6">
                                <div>
                                    <span
                                        class="md:h-24 md:w-24 inline-flex items-center justify-center p-3 text-blue-400 rounded-md shadow-lg"
                                    >
                                        <svg
                                            xmlns="http://www.w3.org/2000/svg"
                                            viewBox="0 0 20 20"
                                            fill="currentColor"
                                        >
                                            <path
                                                fill-rule="evenodd"
                                                d="M12 1.586l-4 4v12.828l4-4V1.586zM3.707 3.293A1 1 0 002 4v10a1 1 0 00.293.707L6 18.414V5.586L3.707 3.293zM17.707 5.293L14 1.586v12.828l2.293 2.293A1 1 0 0018 16V6a1 1 0 00-.293-.707z"
                                                clip-rule="evenodd"
                                            />
                                        </svg>
                                    </span>
                                </div>
                                <h3
                                    class="mt-1 text-sm text-yellow-300 tracking-tight font-bold"
                                >
                                    <span class="text-blue-200"
                                        >Front End Engineer</span
                                    >
                                    <span class="text-yellow-400 font-black"
                                        >&nbsp;/&nbsp;</span
                                    >DSS
                                </h3>
                                <h3
                                    class="text-lg font-bold text-indigo-400 hover:text-indigo-500 tracking-tight"
                                >
                                    <a
                                        href="https://chroniclesofelyria.com/domains#/"
                                        target="_blank"
                                        >Domain and Settlement Selection</a
                                    >
                                </h3>
                                <ul class="text-base text-gray-200">
                                    <li class="mt-5">
                                        Designed, implemented, and maintained
                                        front end of application, used
                                        <a
                                            href="https://vuejs.org/"
                                            target="_blank"
                                        >
                                            <span
                                                class="font-bold text-indigo-400 hover:text-indigo-500"
                                                >Vue.js</span
                                            >
                                        </a>
                                        and
                                        <a
                                            href="https://leafletjs.com/"
                                            target="_blank"
                                        >
                                            <span
                                                class="font-bold text-indigo-400 hover:text-indigo-500"
                                                >Leaftlet.js</span
                                            >
                                        </a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>

                    <div class="pt-6">
                        <div class="flow-root bg-dark rounded-lg px-6 pb-8">
                            <div class="-mt-6">
                                <div>
                                    <span
                                        class="md:h-24 md:w-24 inline-flex items-center justify-center p-3 text-blue-400 rounded-md shadow-lg"
                                    >
                                        <svg
                                            xmlns="http://www.w3.org/2000/svg"
                                            viewBox="0 0 20 20"
                                            fill="currentColor"
                                        >
                                            <path
                                                fill-rule="evenodd"
                                                d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z"
                                                clip-rule="evenodd"
                                            />
                                        </svg>
                                    </span>
                                </div>
                                <h3
                                    class="mt-1 text-sm text-yellow-300 tracking-tight font-bold"
                                >
                                    <span class="text-blue-200">Merch by</span>
                                    <span class="text-yellow-400 font-black"
                                        >&nbsp;/&nbsp;</span
                                    >Seller Support
                                </h3>
                                <h3
                                    class="text-lg font-bold text-indigo-400 hover:text-indigo-500 tracking-tight"
                                >
                                    <a
                                        href="https://merch.amazon.com/landing"
                                        target="_blank">Merch by Amazon</a
                                    >
                                </h3>
                                <ul class="text-base text-gray-200">
                                    <li class="mt-5">
                                        Designed, implemented and maintained web
                                        application to automate case responses.
                                    </li>
                                    <li class="mt-5">
                                        Reduced the average case handling time
                                        <span class="font-bold text-blue-400"
                                            >2</span
                                        > minutes
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>

                    <div class="pt-6">
                        <div class="flow-root bg-dark rounded-lg px-6 pb-8">
                            <div class="-mt-6">
                                <div>
                                    <span
                                        class="md:h-24 md:w-24 inline-flex items-center justify-center p-3 text-blue-400 rounded-md shadow-lg"
                                    >
                                        <svg
                                            xmlns="http://www.w3.org/2000/svg"
                                            viewBox="0 0 20 20"
                                            fill="currentColor"
                                        >
                                            <path
                                                fill-rule="evenodd"
                                                d="M12.316 3.051a1 1 0 01.633 1.265l-4 12a1 1 0 11-1.898-.632l4-12a1 1 0 011.265-.633zM5.707 6.293a1 1 0 010 1.414L3.414 10l2.293 2.293a1 1 0 11-1.414 1.414l-3-3a1 1 0 010-1.414l3-3a1 1 0 011.414 0zm8.586 0a1 1 0 011.414 0l3 3a1 1 0 010 1.414l-3 3a1 1 0 11-1.414-1.414L16.586 10l-2.293-2.293a1 1 0 010-1.414z"
                                                clip-rule="evenodd"
                                            />
                                        </svg>
                                    </span>
                                </div>
                                <h3
                                    class="mt-1 text-sm text-yellow-300 tracking-tight font-bold"
                                >
                                    <span class="text-blue-200"
                                        >Front End Cert</span
                                    >
                                    <span class="text-yellow-400 font-black"
                                        >&nbsp;/&nbsp;</span
                                    >freeCodeCamp, 2017
                                </h3>
                                <h3
                                    class="text-lg font-bold text-indigo-400 hover:text-indigo-500 tracking-tight"
                                >
                                    <a
                                        href="https://www.freecodecamp.org/"
                                        target="_blank">freeCodeCamp.org</a
                                    >
                                </h3>
                                <ul class="text-base text-gray-200">
                                    <li class="mt-5">
                                        Front End Development Certificate
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                    <div class="pt-6">
                        <div class="flow-root bg-dark rounded-lg px-6 pb-8">
                            <div class="-mt-6">
                                <div>
                                    <span
                                        class="md:h-24 md:w-24 inline-flex items-center justify-center p-3 text-blue-400 rounded-md shadow-lg"
                                    >
                                        <svg
                                            xmlns="http://www.w3.org/2000/svg"
                                            viewBox="0 0 20 20"
                                            fill="currentColor"
                                        >
                                            <path
                                                fill-rule="evenodd"
                                                d="M10.496 2.132a1 1 0 00-.992 0l-7 4A1 1 0 003 8v7a1 1 0 100 2h14a1 1 0 100-2V8a1 1 0 00.496-1.868l-7-4zM6 9a1 1 0 00-1 1v3a1 1 0 102 0v-3a1 1 0 00-1-1zm3 1a1 1 0 012 0v3a1 1 0 11-2 0v-3zm5-1a1 1 0 00-1 1v3a1 1 0 102 0v-3a1 1 0 00-1-1z"
                                                clip-rule="evenodd"
                                            />
                                        </svg>
                                    </span>
                                </div>
                                <h3
                                    class="mt-1 text-sm text-yellow-300 tracking-tight font-bold"
                                >
                                    <span class="text-blue-200"
                                        >BS Film and Broadcasting</span
                                    >
                                    <span class="text-yellow-400 font-black"
                                        >&nbsp;/&nbsp;</span
                                    >CMSU, 2004
                                </h3>
                                <h3
                                    class="text-lg font-bold text-indigo-400 hover:text-indigo-500 tracking-tight"
                                >
                                    <a
                                        href="https://www.ucmo.edu/"
                                        target="_blank"
                                        >Central Missouri State University</a
                                    >
                                </h3>
                                <ul class="text-base text-gray-200">
                                    <li class="mt-5">
                                        Focused on production and business
                                        communication
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>

                    <div class="pt-6">
                        <div class="flow-root bg-dark rounded-lg px-6 pb-8">
                            <div class="-mt-6">
                                <div>
                                    <span
                                        class="md:h-24 md:w-24 inline-flex items-center justify-center p-3 text-blue-400 rounded-md shadow-lg"
                                    >
                                        <svg
                                            xmlns="http://www.w3.org/2000/svg"
                                            viewBox="0 0 20 20"
                                            fill="currentColor"
                                        >
                                            <path
                                                d="M13 6a3 3 0 11-6 0 3 3 0 016 0zM18 8a2 2 0 11-4 0 2 2 0 014 0zM14 15a4 4 0 00-8 0v3h8v-3zM6 8a2 2 0 11-4 0 2 2 0 014 0zM16 18v-3a5.972 5.972 0 00-.75-2.906A3.005 3.005 0 0119 15v3h-3zM4.75 12.094A5.973 5.973 0 004 15v3H1v-3a3 3 0 013.75-2.906z"
                                            />
                                        </svg>
                                    </span>
                                </div>
                                <h3
                                    class="mt-1 text-sm text-yellow-300 tracking-tight font-bold"
                                >
                                    <span class="text-blue-200"
                                        >Eagle Scout</span
                                    >
                                    <span class="text-yellow-400 font-black"
                                        >&nbsp;/&nbsp;</span
                                    >Troop 95, 2000
                                </h3>
                                <h3
                                    class="text-lg font-bold text-indigo-400 hover:text-indigo-500 tracking-tight"
                                >
                                    <a
                                        href="https://www.scouting.org/resources/guide-to-advancement/eagle-scout-rank/"
                                        target="_blank"
                                        >Boy Scouts of America
                                    </a>
                                </h3>
                                <ul class="text-base text-gray-200">
                                    <li class="mt-5">
                                        Planned, developed, and lead a community
                                        service project
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</Container>
