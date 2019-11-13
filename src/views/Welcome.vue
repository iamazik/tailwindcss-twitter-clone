<template>
  <div class="flex flex-col content-between min-h-screen">
    <div class="flex flex-1 flex-col-reverse md:flex-row">
      <div class="flex flex-1 bg-blue-500 justify-center items-center">
        <ul class="max-w-sm text-white text-lg font-bold">
          <li class="flex m-10 md:mx-0">
            <svg class="w-8 h-8 mr-5" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
              <path
                class="fill-current"
                d="M12.906 14.32a8 8 0 1 1 1.414-1.414l5.337 5.337-1.414 1.414-5.337-5.337zM8 14A6 6 0 1 0 8 2a6 6 0 0 0 0 12z"
                fill="none"
                fill-rule="evenodd"
              />
            </svg>
            Follow your interests.
          </li>
          <li class="flex m-10 md:mx-0">
            <svg class="w-8 h-8 mr-5" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
              <path
                class="fill-current"
                d="M7 8a4 4 0 1 0 0-8 4 4 0 0 0 0 8zm0 1a17.93 17.93 0 0 0-6.109 1.086L2 16h1.25L4 20h6l.75-4H12l1.109-5.914A17.93 17.93 0 0 0 7 9zm8.315.171L13.66 18h-1.25l-.375 2H16l.75-4H18l1.109-5.914a18.211 18.211 0 0 0-3.794-.915zM13 0a3.99 3.99 0 0 0-1.329.243A5.964 5.964 0 0 1 13 4a5.964 5.964 0 0 1-1.329 3.757c.418.147.86.243 1.329.243a4 4 0 0 0 0-8z"
                fill="none"
                fill-rule="evenodd"
              />
            </svg>
            Hear what people are talking about.
          </li>
          <li class="flex m-10 md:mx-0">
            <svg class="w-8 h-8 mr-5" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
              <path
                class="fill-current"
                d="M10 15h8.01c1.092 0 1.99-.898 1.99-2.006V3.006A1.998 1.998 0 0 0 18.01 1H1.99C.899 1 0 1.898 0 3.006v9.988C0 14.103.891 15 1.99 15H6v4l4-4zM5 7h2v2H5V7zm4 0h2v2H9V7zm4 0h2v2h-2V7z"
                fill="none"
                fill-rule="evenodd"
              />
            </svg>
            Join the conversation.
          </li>
        </ul>
      </div>
      <div class="flex flex-1 justify-center items-center">
        <div class="flex hidden lg:flex justify-center self-start absolute mt-8">
          <form class="w-full max-w-lg">
            <div class="flex flex-wrap mb-6 sm:mb-0">
              <div class="w-full md:w-2/5 pr-3 mb-6 sm:mb-0">
                <input
                  class="appearance-none block w-full text-gray-700 border border-gray-200 rounded py-3 px-4 leading-tight focus:outline-none focus:border-blue-500"
                  type="text"
                  placeholder="Phone, email, or username"
                />
              </div>
              <div class="w-full md:w-2/5 pr-3 mb-6 sm:mb-0">
                <input
                  class="appearance-none block w-full text-gray-700 border border-gray-200 rounded py-3 px-4 leading-tight focus:outline-none focus:border-blue-500"
                  type="password"
                  placeholder="Password"
                />
                <a class="text-sm text-gray-500 hover:underline" href="#">Forgot password?</a>
              </div>
              <div class="w-full md:w-1/5">
                <button
                  class="w-full text-sm bg-transparent hover:bg-blue-100 text-blue-500 font-bold py-3 px-4 rounded-full focus:outline-none focus:shadow-outline border border-blue-500"
                  type="button"
                >Log in</button>
              </div>
            </div>
          </form>
        </div>
        <div class="max-w-sm px-10 py-5">
          <div class="flex justify-between mb-3">
            <svg
              class="text-blue-500 w-10 h-10"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 512 512"
            >
              <path
                d="M459.37 151.716c.325 4.548.325 9.097.325 13.645 0 138.72-105.583 298.558-298.558 298.558-59.452 0-114.68-17.219-161.137-47.106 8.447.974 16.568 1.299 25.34 1.299 49.055 0 94.213-16.568 130.274-44.832-46.132-.975-84.792-31.188-98.112-72.772 6.498.974 12.995 1.624 19.818 1.624 9.421 0 18.843-1.3 27.614-3.573-48.081-9.747-84.143-51.98-84.143-102.985v-1.299c13.969 7.797 30.214 12.67 47.431 13.319-28.264-18.843-46.781-51.005-46.781-87.391 0-19.492 5.197-37.36 14.294-52.954 51.655 63.675 129.3 105.258 216.365 109.807-1.624-7.797-2.599-15.918-2.599-24.04 0-57.828 46.782-104.934 104.934-104.934 30.213 0 57.502 12.67 76.67 33.137 23.715-4.548 46.456-13.32 66.599-25.34-7.798 24.366-24.366 44.833-46.132 57.827 21.117-2.273 41.584-8.122 60.426-16.243-14.292 20.791-32.161 39.308-52.628 54.253z"
                fill="currentColor"
              />
            </svg>
            <a
              class="lg:hidden text-sm bg-transparent hover:bg-blue-100 text-blue-500 font-bold py-2 px-3 rounded-full focus:outline-none focus:shadow-outline border border-blue-500"
              href="#"
            >Log in</a>
          </div>
          <h1 class="text-2xl font-bold leading-tight">See what's happening in the world right now</h1>
          <div class="mt-10">
            <h2 class="font-bold text-lg mb-3">Join Twitter Today.</h2>
            <div class="flex flex-col">
              <a
                class="w-full mb-4 bg-blue-500 text-white text-center text-sm font-bold py-2 rounded-full focus:outline-none focus:shadow-outline hover:bg-blue-700"
                href="#"
              >Sign up</a>
              <a
                class="w-full bg-transparent text-blue-500 text-center text-sm font-bold py-2 rounded-full border border-blue-500 focus:outline-none focus:shadow-outline hover:bg-blue-100"
                href="#"
              >Log in</a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="bg-white border-t border-gray-200 pt-3 pb-3">
      <ul class="flex justify-center flex-wrap text-gray-500 text-xs">
        <li class="px-2">
          <a class="hover:underline" href="#">About</a>
        </li>
        <li class="px-2">
          <a class="hover:underline" href="#">Help Center</a>
        </li>
        <li class="px-2">
          <a class="hover:underline" href="#">Blog</a>
        </li>
        <li class="px-2">
          <a class="hover:underline" href="#">Status</a>
        </li>
        <li class="px-2">
          <a class="hover:underline" href="#">Jobs</a>
        </li>
        <li class="px-2">
          <a class="hover:underline" href="#">Terms</a>
        </li>
        <li class="px-2">
          <a class="hover:underline" href="#">Privacy Policy</a>
        </li>
        <li class="px-2">
          <a class="hover:underline" href="#">Cookies</a>
        </li>
        <li class="px-2">
          <a class="hover:underline" href="#">Ads info</a>
        </li>
        <li class="px-2">
          <a class="hover:underline" href="#">Brand</a>
        </li>
        <li class="px-2">
          <a class="hover:underline" href="#">Apps</a>
        </li>
        <li class="px-2">
          <a class="hover:underline" href="#">Advertise</a>
        </li>
        <li class="px-2">
          <a class="hover:underline" href="#">Marketing</a>
        </li>
        <li class="px-2">
          <a class="hover:underline" href="#">Businesses</a>
        </li>
        <li class="px-2">
          <a class="hover:underline" href="#">Developers</a>
        </li>
        <li class="px-2">
          <a class="hover:underline" href="#">Directory</a>
        </li>
        <li class="px-2">
          <a class="hover:underline" href="#">Settings</a>
        </li>
        <li class="px-2">&copy; 2019 Twitter</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "welcome"
};
</script>
