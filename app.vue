<template>
  <div class="flex flex-col min-h-screen">
    <SiteHeader />
    <div class="flex flex-col grow bg-repeat bg-[url('@/assets/backgrounds/windows95-tile320x240.jpg')]">
      <main class="grow mx-auto max-w-5xl px-2 sm:px-6 lg:px-8 items-start w-full bg-gray-100/95 rounded-2xl my-5 pb-5 shadow-2xl">
        <NuxtPage />
      </main>
    </div>
    <SiteFooter />
  </div>
</template>