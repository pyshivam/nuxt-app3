<template>
  <section class="mt-32 md:h-screen hero" id="hero">
    <div class="flex flex-col md:flex-row">
      <div class="mt-32 md:flex-1">
        <div class="text-4xl md:text-5xl font-bold" style="line-height: 1.2">
          Better organization, more business done.
        </div>
        <div class="my-6 text-gray-900 text-xl">
          I help small businesses and corporations build better systems for projects,
          docs, and more.
        </div>
        <div
          class="text-center py-3 mt-10 bg-black font-medium text-white rounded-md md:max-w-xs"
        >
          Get in Touch
        </div>
      </div>
      <div class="md:flex-1 md:flex md:justify-center md:items-center">
        <img class="mt-16 md:mt-0 md:h-72" src="/img/hero.png" />
      </div>
    </div>
  </section>
</template>

<style>
.hero {
  width: 100%;
  height: max-content;
  max-height: max(768px, 100vh);
}

@media (min-width: 768px) {
  .hero {
    min-height: min(680px, 100vh);
  }
}
@media (max-height: 768px) {
  .hero {
    min-height: min(768px, 100vh);
  }
}
</style>
