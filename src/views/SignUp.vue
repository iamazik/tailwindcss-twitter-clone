<template>
  <div class="flex justify-center items-center min-h-screen bg-gray-400">
    <div class="p-5 w-full max-w-xl bg-white sm:rounded-lg">
      <header class="relative mb-5">
        <div class="flex justify-center">
          <svg class="w-8 h-8 fill-current text-blue-500" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
            <path d="M459.37 151.716c.325 4.548.325 9.097.325 13.645 0 138.72-105.583 298.558-298.558 298.558-59.452 0-114.68-17.219-161.137-47.106 8.447.974 16.568 1.299 25.34 1.299 49.055 0 94.213-16.568 130.274-44.832-46.132-.975-84.792-31.188-98.112-72.772 6.498.974 12.995 1.624 19.818 1.624 9.421 0 18.843-1.3 27.614-3.573-48.081-9.747-84.143-51.98-84.143-102.985v-1.299c13.969 7.797 30.214 12.67 47.431 13.319-28.264-18.843-46.781-51.005-46.781-87.391 0-19.492 5.197-37.36 14.294-52.954 51.655 63.675 129.3 105.258 216.365 109.807-1.624-7.797-2.599-15.918-2.599-24.04 0-57.828 46.782-104.934 104.934-104.934 30.213 0 57.502 12.67 76.67 33.137 23.715-4.548 46.456-13.32 66.599-25.34-7.798 24.366-24.366 44.833-46.132 57.827 21.117-2.273 41.584-8.122 60.426-16.243-14.292 20.791-32.161 39.308-52.628 54.253z"/>
          </svg>
        </div>
        <div class="flex justify-end">
          <button class="px-5 py-1 absolute top-0 rounded-full text-sm font-bold bg-blue-500 text-white appearance-none hover:bg-blue-700 focus:outline-none focus:shadow-outline" type="button">Next</button>
        </div>
      </header>
      <main>
        <h1 class="mb-5 text-gray-900 text-2xl font-bold">Create your account</h1>
        <form action="">
          <div class="mb-10">
            <input class="w-full px-2 py-3 appearance-none text-lg text-gray-800 rounded bg-blue-100 border-b-2 border-gray-600 focus:outline-none focus:border-blue-500" type="text" placeholder="Name">
          </div>
          <div class="mb-10">
            <input class="w-full px-2 py-3 appearance-none text-lg text-gray-800 rounded bg-blue-100 border-b-2 border-gray-600 focus:outline-none focus:border-blue-500" type="email" placeholder="Email address">
          </div>
          <div class="mb-10">
            <input class="w-full px-2 py-3 appearance-none text-lg text-gray-800 rounded bg-blue-100 border-b-2 border-gray-600 focus:outline-none focus:border-blue-500" type="password" placeholder="Password">
          </div>
          <div class="mb-10">
            <input class="w-full px-2 py-3 appearance-none text-lg text-gray-800 rounded bg-blue-100 border-b-2 border-red-500 focus:outline-none focus:border-blue-500" type="password" placeholder="Password confirmation">
            <p class="text-red-500 text-xs italic">Password doesn't match</p>
          </div>
          <div class="flex justify-center">
            <button class="w-full max-w-xs py-2 rounded-full font-bold bg-blue-500 text-white hover:bg-blue-700 focus:outline-none focus:shadow-outline" type="submit">Sign Up</button>
          </div>
        </form>
      </main>
    </div>
  </div>
</template>
<script>
export default {
  name: "signup"
}
</script>
