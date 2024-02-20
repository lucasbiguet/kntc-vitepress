---
title: KNTC
intro: Modern rock duo from Lyon FR
image: /images/uploads/bg-home.jpg
---
<section class="h-screen relative flex flex-1 shrink-0 items-center justify-center overflow-hidden bg-gray-100 py-16 shadow-lg md:py-20 xl:py-48">
  <img :src="$frontmatter.image" loading="lazy" alt="" class="absolute inset-0 h-full w-full object-cover object-center" />
  <div class="absolute inset-0 bg-gray-300 mix-blend-multiply"></div>
  <div class="relative flex flex-col items-center p-4 sm:max-w-xl">
    <h1 class="mb-4 text-center text-4xl font-bold text-white sm:text-5xl md:text-6xl">{{ $frontmatter.title }}</h1>
    <p class="mb-8 text-center text-lg text-red-200 sm:text-xl md:mb-12">{{ $frontmatter.intro }}</p>
    <div class="flex w-full flex-col gap-2.5 sm:flex-row sm:justify-center">
      <a href="#" class="inline-block rounded-lg bg-red-500 px-8 py-3 text-center text-sm font-semibold text-white outline-none ring-red-300 transition duration-100 hover:bg-red-600 focus-visible:ring active:bg-red-700 md:text-base">Start now</a>
      <a href="#" class="inline-block rounded-lg bg-gray-200 px-8 py-3 text-center text-sm font-semibold text-gray-500 outline-none ring-red-300 transition duration-100 hover:bg-gray-300 focus-visible:ring active:text-gray-700 md:text-base">Take tour</a>
    </div>
  </div>
</section>
