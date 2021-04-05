<template>

  <main class="dark:bg-gray-800 bg-white relative overflow-hidden h-screen">
    <header class="h-24 sm:h-32 flex items-center z-30 w-full">
      <div class="container mx-auto px-6 flex items-center justify-between">
        <div class="uppercase text-gray-800 dark:text-white font-black text-3xl">
          Fundz.ME
        </div>
        <div class="flex items-center">
          <nav class="font-sen text-gray-800 dark:text-white uppercase text-lg lg:flex items-center hidden">
            <a href="#" class="py-2 px-6 flex">
              Login
            </a>
          </nav>
          <button class="lg:hidden flex flex-col ml-4">
                    <span class="w-6 h-1 bg-gray-800 dark:bg-white mb-1">
                    </span>
            <span class="w-6 h-1 bg-gray-800 dark:bg-white mb-1">
                    </span>
            <span class="w-6 h-1 bg-gray-800 dark:bg-white mb-1">
                    </span>
          </button>
        </div>
      </div>
    </header>
    <div class="bg-white dark:bg-gray-800 flex relative z-20 items-center overflow-hidden">
      <div class="container mx-auto px-6 flex relative py-16">
        <div class="sm:w-2/3 lg:w-2/5 flex flex-col relative z-20">
                <span class="w-20 h-2 bg-gray-800 dark:bg-white mb-12">
                </span>
          <h1 class="font-bebas-neue uppercase text-6xl sm:text-8xl font-black flex flex-col leading-none dark:text-white text-gray-800">
            Fundz
            <span class="text-5xl sm:text-7xl">
                        by Gabriel
                    </span>
          </h1>
          <p class="text-sm sm:text-base text-gray-700 dark:text-white">
            A centralized place where he makes all his payments
          </p>
          <div class="flex mt-8">
            <div class="inline-flex rounded-md shadow">
              <a href="#" class="inline-flex items-center justify-center px-5 py-3 border border-transparent text-base leading-6 font-medium rounded-md text-white bg-indigo-600 hover:bg-indigo-500 focus:outline-none focus:shadow-outline transition duration-150 ease-in-out">
                Create an account
              </a>
            </div>          <div class="ml-3 inline-flex rounded-md shadow">
            <a href="https://github.com/humaneguy/fundz" class="inline-flex items-center justify-center px-5 py-3 border border-transparent text-base leading-6 font-medium rounded-md text-indigo-600 bg-white hover:text-indigo-500 focus:outline-none focus:shadow-outline transition duration-150 ease-in-out">
              Login
            </a>
          </div>
          </div>
        </div>
        <div class="hidden sm:block sm:w-1/3 lg:w-3/5 relative">
          <img class="max-w-xs md:max-w-sm m-auto" src="../assets/fundz.png">



<!--          <img src="/images/object/10.png" class="max-w-xs md:max-w-sm m-auto"/>-->
        </div>
      </div>
    </div>
  </main>

</template>

<script>
export default {
name: "Header",
}
</script>

<style scoped>

</style>