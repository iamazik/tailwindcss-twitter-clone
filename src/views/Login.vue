<template>
  <div class="min-h-screen bg-gray-200">
    <header
      class="text-sm font-semibold text-gray-600 bg-white border-b border-gray-400"
    >
      <div class="container mx-auto px-6 sm:px-0">
        <nav class="flex justify-between items-center">
          <div class="flex items-center">
            <router-link
              class="flex items-center pr-3 py-3 focus:outline-none"
              to="/"
            >
              <svg
                class="w-5 h-5 fill-current text-blue-500"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 512 512"
              >
                <path
                  d="M459.37 151.716c.325 4.548.325 9.097.325 13.645 0 138.72-105.583 298.558-298.558 298.558-59.452 0-114.68-17.219-161.137-47.106 8.447.974 16.568 1.299 25.34 1.299 49.055 0 94.213-16.568 130.274-44.832-46.132-.975-84.792-31.188-98.112-72.772 6.498.974 12.995 1.624 19.818 1.624 9.421 0 18.843-1.3 27.614-3.573-48.081-9.747-84.143-51.98-84.143-102.985v-1.299c13.969 7.797 30.214 12.67 47.431 13.319-28.264-18.843-46.781-51.005-46.781-87.391 0-19.492 5.197-37.36 14.294-52.954 51.655 63.675 129.3 105.258 216.365 109.807-1.624-7.797-2.599-15.918-2.599-24.04 0-57.828 46.782-104.934 104.934-104.934 30.213 0 57.502 12.67 76.67 33.137 23.715-4.548 46.456-13.32 66.599-25.34-7.798 24.366-24.366 44.833-46.132 57.827 21.117-2.273 41.584-8.122 60.426-16.243-14.292 20.791-32.161 39.308-52.628 54.253z"
                />
              </svg>
              <span class="hidden md:flex pl-2">Home</span>
            </router-link>
            <router-link class="hidden md:flex pl-3" to="/about"
              >About</router-link
            >
          </div>
          <div class="hidden md:flex relative">
            <a
              class="flex items-center hover:underline"
              href="#supported_languages"
            >
              <small class="pr-1 text-xs font-light">Language: </small>
              English
              <svg
                class="fill-current h-4 w-4"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 20 20"
              >
                <path
                  d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"
                ></path>
              </svg>
            </a>
            <div
              class="hidden flex flex-wrap justify-between absolute w-40 right-0 rounded bg-white border-t-2 border-gray-200 text-xs font-light shadow-md"
            >
              <a
                class="w-1/2 px-4 p-3 hover:bg-blue-500 hover:text-white"
                href="?lang='en'"
                >Bengali</a
              >
              <a
                class="w-1/2 px-4 p-3 hover:bg-blue-500 hover:text-white"
                href="?lang='en'"
                >English</a
              >
              <a
                class="w-1/2 px-4 p-3 hover:bg-blue-500 hover:text-white"
                href="?lang='en'"
                >Hindi</a
              >
              <a
                class="w-1/2 px-4 p-3 hover:bg-blue-500 hover:text-white"
                href="?lang='en'"
                >Arabic</a
              >
              <a
                class="w-1/2 px-4 p-3 hover:bg-blue-500 hover:text-white"
                href="?lang='en'"
                >Dutch</a
              >
              <a
                class="w-1/2 px-4 p-3 hover:bg-blue-500 hover:text-white"
                href="?lang='en'"
                >French</a
              >
              <a
                class="w-1/2 px-4 p-3 hover:bg-blue-500 hover:text-white"
                href="?lang='en'"
                >German</a
              >
              <a
                class="w-1/2 px-4 p-3 hover:bg-blue-500 hover:text-white"
                href="?lang='en'"
                >Swiss</a
              >
              <a
                class="w-1/2 px-4 p-3 hover:bg-blue-500 hover:text-white"
                href="?lang='en'"
                >Icelandinc</a
              >
              <a
                class="w-1/2 px-4 p-3 hover:bg-blue-500 hover:text-white"
                href="?lang='en'"
                >Spanish</a
              >
            </div>
          </div>
        </nav>
      </div>
    </header>
    <main
      class="container mx-auto px-6 md:px-32 py-6 mt-2 bg-white border border-b-0 border-gray-400"
    >
      <div class="hidden relative md:px-20 md:py-3 text-gray-600 shadow-md">
        <button class="absolute right-0 pr-2 md:pr-5" type="button">
          <svg
            class="w-2 h-2 fill-current"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 20 20"
          >
            <path
              d="M10 8.586L2.929 1.515 1.515 2.929 8.586 10l-7.071 7.071 1.414 1.414L10 11.414l7.071 7.071 1.414-1.414L11.414 10l7.071-7.071-1.414-1.414L10 8.586z"
            />
          </svg>
        </button>
        <p class="text-sm text-center pt-2 md:pt-0">
          The username and password you entered did not match our records.
          Please double-check and try again.
        </p>
      </div>
      <div class="w-full max-w-xs">
        <h1 class="text-2xl font-medium">Log in to Kokil</h1>
        <form class="mt-4" action="">
          <div class="mb-4">
            <input
              class="w-full px-1 leading-loose appearance-none font-light text-sm text-gray-800 border rounded focus:outline-none focus:border-blue-500"
              type="text"
              placeholder="Phone, email or username"
            />
          </div>
          <div>
            <input
              class="w-full px-1 leading-loose appearance-none font-light text-sm text-gray-800 border rounded focus:outline-none focus:border-blue-500"
              type="password"
              placeholder="Password"
            />
          </div>
          <div class="mt-4 flex items-center">
            <label for="remember">
              <input
                class="text-xs focus:outline-none focus:shadow-outline"
                id="remember"
                type="checkbox"
                checked
              />
              <span class="ml-2 text-sm text-gray-800 tracking-wide"
                >Remember me</span
              >
            </label>
          </div>
          <div class="mt-6 flex justify-between items-center">
            <button
              class="px-5 py-2 rounded-full tracking-wider bg-blue-500 font-medium text-sm text-white hover:bg-blue-700 focus:outline-none focus:shadow-outline"
              type="submit"
            >
              Log in
            </button>
            <a
              class="text-sm text-blue-500 hover:underline focus:outline-none focus:underline"
              href="/"
              >Forgot password?</a
            >
          </div>
        </form>
      </div>
    </main>
    <footer
      class="container mx-auto px-6 md:px-32 py-6 text-sm text-gray-700 border border-t-0 border-gray-400 bg-blue-100"
    >
      <p>
        New to Twitter?
        <a class="text-blue-500 hover:underline" href="/signup"
          >Sign up now »</a
        >
      </p>
      <p>
        Already using Twitter via text message?
        <a class="text-blue-500 hover:underline" href="/"
          >Activate your account »</a
        >
      </p>
    </footer>
  </div>
</template>
<script>
export default {
  name: "login"
};
</script>
