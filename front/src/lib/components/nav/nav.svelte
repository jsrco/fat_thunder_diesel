<script>
    import { page } from "$app/stores";
</script>

<nav class="bg-zinc-900 fixed flex opacity-75 w-full z-50" aria-label="Breadcrumb">
    <ol role="list" class="flex items-center space-x-4">
        <li>
            <div>
                <a
                    href="/#"
                    class="{$page.path === '/'
                        ? 'text-yellow-400'
                        : 'text-white'} hover:text-yellow-400"
                >
                    <!-- Heroicon name: solid/home -->
                    <svg
                        class="flex-shrink-0 h-5 w-5"
                        xmlns="http://www.w3.org/2000/svg"
                        viewBox="0 0 20 20"
                        fill="currentColor"
                        aria-hidden="true"
                    >
                        <path
                            d="M10.707 2.293a1 1 0 00-1.414 0l-7 7a1 1 0 001.414 1.414L4 10.414V17a1 1 0 001 1h2a1 1 0 001-1v-2a1 1 0 011-1h2a1 1 0 011 1v2a1 1 0 001 1h2a1 1 0 001-1v-6.586l.293.293a1 1 0 001.414-1.414l-7-7z"
                        />
                    </svg>
                    <span class="sr-only">Home</span>
                </a>
            </div>
        </li>

        <li>
            <div class="flex items-center">
                <svg
                    class="flex-shrink-0 h-5 w-5 text-gray-100"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="currentColor"
                    viewBox="0 0 20 20"
                    aria-hidden="true"
                >
                    <path d="M5.555 17.776l8-16 .894.448-8 16-.894-.448z" />
                </svg>
                <a
                    href="/blog"
                    class="{$page.path === '/blog'
                        ? 'text-red-400'
                        : 'text-white'} hover:text-red-400">Blog</a
                >
            </div>
        </li>

        <li>
            <div class="flex items-center">
                <svg
                    class="flex-shrink-0 h-5 w-5 text-gray-100"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="currentColor"
                    viewBox="0 0 20 20"
                    aria-hidden="true"
                >
                    <path d="M5.555 17.776l8-16 .894.448-8 16-.894-.448z" />
                </svg>
                <a
                    href="/portfolio"
                    class="{$page.path === '/portfolio'
                        ? 'text-blue-400'
                        : 'text-white'} hover:text-blue-400"
                    aria-current="page">Portfolio</a
                >
            </div>
        </li>

        <li>
            <div class="flex items-center">
                <svg
                    class="flex-shrink-0 h-5 w-5 text-gray-100"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="currentColor"
                    viewBox="0 0 20 20"
                    aria-hidden="true"
                >
                    <path d="M5.555 17.776l8-16 .894.448-8 16-.894-.448z" />
                </svg>
                <a
                    href="/about"
                    class="{$page.path === '/about'
                        ? 'text-green-400'
                        : 'text-white'} hover:text-green-400"
                    aria-current="page">About</a
                >
            </div>
        </li>
    </ol>
</nav>
