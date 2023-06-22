<template>
  <section class="bg-cover bg-no-repeat bg-[url('/src/assets/Headerback.png')] h-[100vh] bg-gray-500 bg-blend-multiply">
     <!-- Navbar --> 
    <nav
      class="relative flex w-full items-center justify-between py-2 shadow-sm bg-transparent lg:flex-wrap lg:justify-start"
      data-te-navbar-ref>
      <div class="flex w-full flex-wrap items-center justify-between px-6">
        <div class="flex items-center">
          <!-- Toggle button -->
          <button
            class="block border-0 bg-transparent py-2 pr-2.5 text-neutral-500 hover:no-underline hover:shadow-none focus:no-underline focus:shadow-none focus:outline-none focus:ring-0 dark:text-neutral-200 lg:hidden"
            type="button" data-te-collapse-init data-te-target="#navbarSupportedContentY"
            aria-controls="navbarSupportedContentY" aria-expanded="false" aria-label="Toggle navigation">
            <span class="[&>svg]:w-7">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="h-7 w-7">
                <path fill-rule="evenodd"
                  d="M3 6.75A.75.75 0 013.75 6h16.5a.75.75 0 010 1.5H3.75A.75.75 0 013 6.75zM3 12a.75.75 0 01.75-.75h16.5a.75.75 0 010 1.5H3.75A.75.75 0 013 12zm0 5.25a.75.75 0 01.75-.75h16.5a.75.75 0 010 1.5H3.75a.75.75 0 01-.75-.75z"
                  clip-rule="evenodd" />
              </svg>
            </span>
          </button>

          <a class="text-primary dark:text-primary-400" href="#!">
            <img class="w-48" src="../assets/Logo.png">
          </a>
        </div>

        <div class="my-1 flex items-center lg:my-0 lg:ml-auto gap-4">
          <a href="" class="py-4 px-2 text-white border-b-2 border-teal-300 font-semibold">Accueil</a>
          <a href="" class="py-4 px-2 text-white font-semibold hover:text-teal-300 transition duration-300">Qui sommes-nous ?</a>
          <a href="" class="py-4 px-2 text-white font-semibold hover:text-teal-300 transition duration-300">Menu</a>
          <a href="" class="py-4 px-2 text-white font-semibold hover:text-teal-300 transition duration-300">Contact</a>
          <button class="bg-white text-teal-500 px-5 py-2">Commander</button>
        </div>
      </div>
      
    </nav>
    <!-- Navbar -->
  <div class="flex h-full items-center justify-center">
          <div class="px-6 text-center text-white md:px-12">
            <h1 class="mb-0 mt-2 text-5xl font-bold tracking-tight md:text-6xl xl:text-7xl">
              MONGOO
            </h1>
            <h1 class="italic font-normal ml-48 text-3xl -rotate-6">C'est frais pour vous !</h1>
          </div>
        </div>
  </section>
  
  
  <section class="bg-cover bg-no-repeat bg-[url('/src/assets/back1.png')] h-[100vh]">
    <div class="grid grid-rows-3 grid-flow-col gap-4">
  <div class="row-span-3 ...">01</div>
  <div class="row-span-2 col-span-2 ...">
    <img class="block w-[72vw] m-0" src="../assets/salade-detoure.png">
  </div>
</div>
  </section>
</template>

<script>
export default {
  name: 'MongooApp',
  props: {
    msg: String
  }
}
</script>

<style scoped></style>
