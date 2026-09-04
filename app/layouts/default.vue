<template>
  <div class="min-h-screen flex flex-col justify-between">
    <!-- El Header se mostrará arriba en todas las páginas que usen este layout -->
    <Header />

    <!-- <slot /> es el espacio dinámico donde Nuxt inyectará el contenido de tus páginas (como index.vue) -->
    <main class="flex-grow">
      <slot />
    </main>

    <!-- El Footer se mostrará abajo en todas las páginas -->
    <Footer />
  </div>
</template>