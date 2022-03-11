<script>
  const webdevDescription = `
  
  I can help build your site or a troubleshoot a problem.`;

  const techDescription = `Part of group that hi-jacked a high-school / cable TV station's Novell network in 90s. 

The skill set has continued to grow.`;

  const mediaDescription = `My broadcasting education, performance work, and writing is available.
  
Technically, it is the only thing I went to school for.`;
</script>

<section class="bg-yellow-400 mt-16">
  <!-- CTA -->
  <div class="relative pb-24 bg-zinc-900">
    <div class="relative max-w-7xl mx-auto pb-24 px-4 sm:pb-32 sm:px-6 lg:px-8">
      <h1
        class="text-4xl font-extrabold tracking-tight text-yellow-400 md:text-5xl lg:text-6xl"
      >
        A little lost?
      </h1>
      <p class="mt-6 max-w-3xl text-xl text-gray-300">
        <span class="font-bold text-red-500">Fat Thunder</span> will use every available
        resource help solve your problem.
      </p>
    </div>
  </div>

  <!-- Overlapping cards -->
  <div
    class="-mt-32 max-w-7xl mx-auto relative z-10 pb-24 px-4 sm:px-6 lg:px-8"
    aria-labelledby="contact-heading"
  >
    <div class="grid grid-cols-1 gap-y-20 lg:grid-cols-3 lg:gap-y-0 lg:gap-x-8">
      <div class="flex flex-col bg-white rounded-2xl shadow-xl">
        <div class="flex-1 relative pt-16 px-6 pb-8 md:px-8">
          <div
            class="absolute top-0 p-5 inline-block bg-red-400 rounded-xl shadow-lg transform -translate-y-1/2"
          >
            <!-- Heroicon name: terminal -->
            <svg
              class="h-6 w-6 text-white"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M8 9l3 3-3 3m5 0h3M5 20h14a2 2 0 002-2V6a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"
              />
            </svg>
          </div>
          <h3 class="text-xl font-medium text-zinc-900">Web Development</h3>
          <p class="mt-4 text-base text-zinc-500 whitespace-pre-line">
            I currently work with <a
              href="https://vuejs.org/"
              class="text-base font-bold text-indigo-400 hover:text-indigo-500"
              >Vue.js</a
            > and <a
              href="https://svelte.dev/"
              class="text-base font-bold text-indigo-400 hover:text-indigo-500"
              >Svelte</a
            >.{webdevDescription}
          </p>
        </div>
        <div class="p-6 bg-yellow-100 rounded-bl-2xl rounded-br-2xl md:px-8">
          <a
            href="mailto:jsrco@hotmail.com?subject=Fat Thunder: Web Development"
            class="text-base font-medium text-red-400 hover:text-red-500"
            >Need a Web Dev?<span aria-hidden="true"> &rarr;</span></a
          >
        </div>
      </div>

      <div class="flex flex-col bg-white rounded-2xl shadow-xl">
        <div class="flex-1 relative pt-16 px-6 pb-8 md:px-8">
          <div
            class="absolute top-0 p-5 inline-block bg-blue-400 rounded-xl shadow-lg transform -translate-y-1/2"
          >
            <!-- Heroicon name: outline/support -->
            <svg
              class="h-6 w-6 text-white"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              aria-hidden="true"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M18.364 5.636l-3.536 3.536m0 5.656l3.536 3.536M9.172 9.172L5.636 5.636m3.536 9.192l-3.536 3.536M21 12a9 9 0 11-18 0 9 9 0 0118 0zm-5 0a4 4 0 11-8 0 4 4 0 018 0z"
              />
            </svg>
          </div>
          <h3 class="text-xl font-medium text-zinc-900">Technical Support</h3>
          <p class="mt-4 text-base text-zinc-500 whitespace-pre-line">
            {techDescription}
          </p>
        </div>
        <div class="p-6 bg-yellow-100 rounded-bl-2xl rounded-br-2xl md:px-8">
          <a
            href="mailto:jsrco@hotmail.com?subject=Fat Thunder: Technical Issue"
            class="text-base font-medium text-blue-400 hover:text-blue-500"
            >IT issues? We have solutions.<span aria-hidden="true">
              &rarr;</span
            ></a
          >
        </div>
      </div>

      <div class="flex flex-col bg-white rounded-2xl shadow-xl">
        <div class="flex-1 relative pt-16 px-6 pb-8 md:px-8">
          <div
            class="absolute top-0 p-5 inline-block bg-green-400 rounded-xl shadow-lg transform -translate-y-1/2"
          >
            <!-- Heroicon name: outline/newspaper -->
            <svg
              class="h-6 w-6 text-white"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              aria-hidden="true"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M19 20H5a2 2 0 01-2-2V6a2 2 0 012-2h10a2 2 0 012 2v1m2 13a2 2 0 01-2-2V7m2 13a2 2 0 002-2V9a2 2 0 00-2-2h-2m-4-3H9M7 16h6M7 8h6v4H7V8z"
              />
            </svg>
          </div>
          <h3 class="text-xl font-medium text-zinc-900">Media Inquiries</h3>
          <p class="mt-4 text-base text-zinc-500 whitespace-pre-line">
            {mediaDescription}
          </p>
        </div>
        <div class="p-6 bg-yellow-100 rounded-bl-2xl rounded-br-2xl md:px-8">
          <a
            href="mailto:jsrco@hotmail.com?subject=Fat Thunder: Media Inquiry"
            class="text-base font-medium text-green-400 hover:text-green-500"
            >Reach Out<span aria-hidden="true"> &rarr;</span></a
          >
        </div>
      </div>
    </div>
  </div>
</section>
