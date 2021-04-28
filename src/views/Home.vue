<template>
  <div class="flex container mx-auto h-screen overflow-y-hidden">
    <header class="w-2/12 overflow-y-auto pt-1">
      <ul class="flex flex-col items-center lg:items-start text-gray-700">
        <li class="mb-5">
          <a
            class="inline-block p-2 rounded-full hover:bg-blue-100"
            href="/home"
          >
            <svg
              class="text-blue-500 w-8 h-8 inline-block"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 512 512"
            >
              <path
                d="M459.37 151.716c.325 4.548.325 9.097.325 13.645 0 138.72-105.583 298.558-298.558 298.558-59.452 0-114.68-17.219-161.137-47.106 8.447.974 16.568 1.299 25.34 1.299 49.055 0 94.213-16.568 130.274-44.832-46.132-.975-84.792-31.188-98.112-72.772 6.498.974 12.995 1.624 19.818 1.624 9.421 0 18.843-1.3 27.614-3.573-48.081-9.747-84.143-51.98-84.143-102.985v-1.299c13.969 7.797 30.214 12.67 47.431 13.319-28.264-18.843-46.781-51.005-46.781-87.391 0-19.492 5.197-37.36 14.294-52.954 51.655 63.675 129.3 105.258 216.365 109.807-1.624-7.797-2.599-15.918-2.599-24.04 0-57.828 46.782-104.934 104.934-104.934 30.213 0 57.502 12.67 76.67 33.137 23.715-4.548 46.456-13.32 66.599-25.34-7.798 24.366-24.366 44.833-46.132 57.827 21.117-2.273 41.584-8.122 60.426-16.243-14.292 20.791-32.161 39.308-52.628 54.253z"
                fill="currentColor"
              /></svg
          ></a>
        </li>
        <li class="flex mb-1">
          <a
            class="flex items-center p-3 lg:pl-1 lg:pr-5 lg:py-3 rounded-full hover:bg-blue-100 hover:text-blue-500"
            href="/home"
          >
            <svg
              class="w-6 h-6 inline-block text-blue-500"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                class="fill-current"
                d="M13 20v-5h-2v5a2 2 0 01-2 2H6a2 2 0 01-2-2v-7.59l-.3.3a1 1 0 11-1.4-1.42l9-9a1 1 0 011.4 0l9 9a1 1 0 01-1.4 1.42l-.3-.3V20a2 2 0 01-2 2h-3a2 2 0 01-2-2zm5 0v-9.59l-6-6-6 6V20h3v-5c0-1.1.9-2 2-2h2a2 2 0 012 2v5h3z"
              />
            </svg>
            <span
              class="hidden lg:flex ml-4 xl:inline-block text-lg text-blue-500 font-bold"
            >
              Home
            </span>
          </a>
        </li>
        <li class="flex mb-1">
          <a
            class="flex items-center p-3 lg:pl-1 lg:pr-5 lg:py-3 rounded-full hover:bg-blue-100 hover:text-blue-500"
            href="/explore"
          >
            <svg
              class="w-6 h-6 inline-block"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                class="fill-current"
                d="M11.03 8h3.94l1.06-4.24a1 1 0 111.94.48L17.03 8H20a1 1 0 010 2h-3.47l-1 4H18a1 1 0 110 2h-2.97l-1.06 4.25a1 1 0 11-1.94-.49l.94-3.76H9.03l-1.06 4.25a1 1 0 11-1.94-.49L6.97 16H4a1 1 0 010-2h3.47l1-4H6a1 1 0 010-2h2.97l1.06-4.24a1 1 0 111.94.48L11.03 8zm-.5 2l-1 4h3.94l1-4h-3.94z"
              />
            </svg>
            <span class="hidden lg:flex ml-4 xl:inline-block text-lg font-bold"
              >Explore</span
            >
          </a>
        </li>
        <li class="flex mb-1">
          <a
            class="flex items-center p-3 lg:pl-1 lg:pr-5 lg:py-3 rounded-full hover:bg-blue-100 hover:text-blue-500"
            href="/notifications"
          >
            <svg
              class="w-6 h-6 inline-block"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                class="fill-current"
                d="M15 19a3 3 0 01-6 0H4a1 1 0 010-2h1v-6a7 7 0 014.02-6.34 3 3 0 015.96 0A7 7 0 0119 11v6h1a1 1 0 010 2h-5zm-4 0a1 1 0 002 0h-2zm0-12.9A5 5 0 007 11v6h10v-6a5 5 0 00-4-4.9V5a1 1 0 00-2 0v1.1z"
              />
            </svg>
            <span class="hidden lg:flex ml-4 xl:inline-block text-lg font-bold"
              >Notifications</span
            >
          </a>
        </li>
        <li class="flex mb-1">
          <a
            class="flex items-center p-3 lg:pl-1 lg:pr-5 lg:py-3 rounded-full hover:bg-blue-100 hover:text-blue-500"
            href="/messages"
          >
            <svg
              class="w-6 h-6 inline-block"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                class="fill-current"
                d="M4 4h16a2 2 0 012 2v12a2 2 0 01-2 2H4a2 2 0 01-2-2V6c0-1.1.9-2 2-2zm16 3.38V6H4v1.38l8 4 8-4zm0 2.24l-7.55 3.77a1 1 0 01-.9 0L4 9.62V18h16V9.62z"
              />
            </svg>
            <span class="hidden lg:flex ml-4 xl:inline-block text-lg font-bold">
              Messages
            </span>
          </a>
        </li>
        <li class="flex mb-1">
          <a
            class="flex items-center p-3 lg:pl-1 lg:pr-5 lg:py-3 rounded-full hover:bg-blue-100 hover:text-blue-500"
            href="/bookmarks"
          >
            <svg
              class="w-6 h-6 inline-block"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                class="fill-current"
                d="M12 18.62l-6.55 3.27A1 1 0 014 21V4c0-1.1.9-2 2-2h12a2 2 0 012 2v17a1 1 0 01-1.45.9L12 18.61zM18 4H6v15.38l5.55-2.77a1 1 0 01.9 0L18 19.38V4z"
              />
            </svg>
            <span class="hidden lg:flex ml-4 xl:inline-block text-lg font-bold"
              >Bookmarks</span
            >
          </a>
        </li>
        <li class="flex mb-1">
          <a
            class="flex items-center p-3 lg:pl-1 lg:pr-5 lg:py-3 rounded-full hover:bg-blue-100 hover:text-blue-500"
            href="/lists"
          >
            <svg
              class="w-6 h-6 inline-block"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                class="fill-current"
                d="M6 2h9a1 1 0 01.7.3l4 4a1 1 0 01.3.7v13a2 2 0 01-2 2H6a2 2 0 01-2-2V4c0-1.1.9-2 2-2zm9 2.41V7h2.59L15 4.41zM18 9h-3a2 2 0 01-2-2V4H6v16h12V9zm-2 7a1 1 0 01-1 1H9a1 1 0 010-2h6a1 1 0 011 1zm0-4a1 1 0 01-1 1H9a1 1 0 010-2h6a1 1 0 011 1zm-5-4a1 1 0 01-1 1H9a1 1 0 110-2h1a1 1 0 011 1z"
              />
            </svg>
            <span class="hidden lg:flex ml-4 xl:inline-block text-lg font-bold"
              >Lists</span
            >
          </a>
        </li>
        <li class="flex mb-1">
          <a
            class="flex items-center p-3 lg:pl-1 lg:pr-5 lg:py-3 rounded-full hover:bg-blue-100 hover:text-blue-500"
            href="/profile"
          >
            <svg
              class="w-6 h-6 inline-block"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                class="fill-current"
                d="M12 12a5 5 0 110-10 5 5 0 010 10zm0-2a3 3 0 100-6 3 3 0 000 6zm9 11a1 1 0 01-2 0v-2a3 3 0 00-3-3H8a3 3 0 00-3 3v2a1 1 0 01-2 0v-2a5 5 0 015-5h8a5 5 0 015 5v2z"
              />
            </svg>
            <span class="hidden lg:flex ml-4 xl:inline-block text-lg font-bold"
              >Profile</span
            >
          </a>
        </li>
        <li class="flex mb-1">
          <button
            type="button"
            class="flex items-center p-3 lg:pl-1 lg:pr-5 lg:py-3 rounded-full hover:bg-blue-100 hover:text-blue-500"
          >
            <svg
              class="w-6 h-6 inline-block"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                class="fill-current"
                d="M4 15a3 3 0 110-6 3 3 0 010 6zm0-2a1 1 0 100-2 1 1 0 000 2zm8 2a3 3 0 110-6 3 3 0 010 6zm0-2a1 1 0 100-2 1 1 0 000 2zm8 2a3 3 0 110-6 3 3 0 010 6zm0-2a1 1 0 100-2 1 1 0 000 2z"
              />
            </svg>
            <span class="hidden lg:flex ml-4 xl:inline-block text-lg font-bold"
              >More</span
            >
          </button>
        </li>
        <li class="flex">
          <a
            class="flex items-center justify-center shadow-lg p-3 rounded-full text-white bg-blue-500 hover:bg-blue-600 lg:px-12"
            href="/compose/tweet"
          >
            <svg
              class="w-6 h-6 inline-block lg:hidden"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                class="fill-current"
                d="M8.8 7.2H5.6V3.9c0-.4-.3-.8-.8-.8s-.7.4-.7.8v3.3H.8c-.4 0-.8.3-.8.8s.3.8.8.8h3.3v3.3c0 .4.3.8.8.8s.8-.3.8-.8V8.7H9c.4 0 .8-.3.8-.8s-.5-.7-1-.7zm15-4.9v-.1h-.1c-.1 0-9.2 1.2-14.4 11.7-3.8 7.6-3.6 9.9-3.3 9.9.3.1 3.4-6.5 6.7-9.2 5.2-1.1 6.6-3.6 6.6-3.6s-1.5.2-2.1.2c-.8 0-1.4-.2-1.7-.3 1.3-1.2 2.4-1.5 3.5-1.7.9-.2 1.8-.4 3-1.2 2.2-1.6 1.9-5.5 1.8-5.7z"
              />
            </svg>
            <span class="hidden lg:flex xl:inline-block text-lg font-bold">
              Tweet
            </span>
          </a>
        </li>
      </ul>
    </header>
    <main class="flex flex-col w-7/12 border-l border-r">
      <div class="flex justify-between border-b p-3">
        <h1 class="text-xl font-bold"><a href="/home">Home</a></h1>
        <a class="" href="">
          <svg
            class="w-6 h-6 inline-block text-blue-500"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              class="fill-current"
              d="M6 18.7V21a1 1 0 01-2 0v-5a1 1 0 011-1h5a1 1 0 110 2H7.1A7 7 0 0019 12a1 1 0 112 0 9 9 0 01-15 6.7zM18 5.3V3a1 1 0 012 0v5a1 1 0 01-1 1h-5a1 1 0 010-2h2.9A7 7 0 005 12a1 1 0 11-2 0 9 9 0 0115-6.7z"
            />
          </svg>
        </a>
      </div>
      <div class="flex flex-col overflow-y-auto">
        <div class="flex p-3 border-b-8 border-gray-300">
          <img
            class="w-12 h-12 rounded-full"
            src="http://source.unsplash.com/rtzN1TGIGWc/60x60"
            alt="profile"
          />
          <form class="w-full" action="">
            <div class="flex items-center">
              <textarea
                class="w-full text-xl pl-2 outline-none resize-none overflow-auto"
                name="tweet"
                id="tweet"
                maxlength="280"
                placeholder="What's happening?"
              ></textarea>
            </div>
            <div class="flex justify-between items-center">
              <div class="flex items-center">
                <div class="px-3">
                  <label for="image">
                    <svg
                      class="inline-block text-blue-500 hover:text-blue-600 w-6 h-6"
                      viewBox="0 0 24 24"
                      xmlns="http://www.w3.org/2000/svg"
                    >
                      <path
                        class="fill-current"
                        d="M4 4h16a2 2 0 012 2v12a2 2 0 01-2 2H4a2 2 0 01-2-2V6c0-1.1.9-2 2-2zm16 8.59V6H4v6.59l4.3-4.3a1 1 0 011.4 0l5.3 5.3 2.3-2.3a1 1 0 011.4 0l1.3 1.3zm0 2.82l-2-2-2.3 2.3a1 1 0 01-1.4 0L9 10.4l-5 5V18h16v-2.59zM15 10a1 1 0 110-2 1 1 0 010 2z"
                      />
                    </svg>
                  </label>
                  <input id="image" class="w-0 h-0 invisible" type="file" />
                </div>
                <div class="px-3">
                  <svg
                    class="w-6 h-6 text-blue-500 hover:text-blue-600"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 24 24"
                  >
                    <path
                      class="fill-current"
                      d="M20 7a2 2 0 012 2v10a2 2 0 01-2 2H4a2 2 0 01-2-2V9c0-1.1.9-2 2-2h2.38l1.73-3.45A1 1 0 019 3h6a1 1 0 01.9.55L17.61 7H20zM9.62 5L7.89 8.45A1 1 0 017 9H4v10h16V9h-3a1 1 0 01-.9-.55L14.39 5H9.62zM12 17a4 4 0 110-8 4 4 0 010 8zm0-2a2 2 0 100-4 2 2 0 000 4z"
                    />
                  </svg>
                </div>
                <div class="px-3">
                  <svg
                    class="w-6 h-6 text-blue-500 hover:text-blue-600"
                    viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      class="fill-current"
                      d="M20 22H4a2 2 0 01-2-2v-8c0-1.1.9-2 2-2h4V8c0-1.1.9-2 2-2h4V4c0-1.1.9-2 2-2h4a2 2 0 012 2v16a2 2 0 01-2 2zM14 8h-4v12h4V8zm-6 4H4v8h4v-8zm8-8v16h4V4h-4z"
                    />
                  </svg>
                </div>
                <div class="px-3">
                  <svg
                    class="w-6 h-6 text-blue-500 hover:text-blue-600"
                    viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      class="fill-current"
                      d="M12 22a10 10 0 110-20 10 10 0 010 20zm0-2a8 8 0 100-16 8 8 0 000 16zm-3.54-4.46a1 1 0 011.42-1.42 3 3 0 004.24 0 1 1 0 011.42 1.42 5 5 0 01-7.08 0zM9 11a1 1 0 110-2 1 1 0 010 2zm6 0a1 1 0 110-2 1 1 0 010 2z"
                    />
                  </svg>
                </div>
                <div class="px-3">
                  <svg
                    class="w-6 h-6 text-blue-500 hover:text-blue-600"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 24 24"
                  >
                    <path
                      class="fill-current"
                      d="M17 4h2a2 2 0 012 2v14a2 2 0 01-2 2H5a2 2 0 01-2-2V6c0-1.1.9-2 2-2h2V3a1 1 0 112 0v1h6V3a1 1 0 012 0v1zm-2 2H9v1a1 1 0 11-2 0V6H5v4h14V6h-2v1a1 1 0 01-2 0V6zm4 6H5v8h14v-8z"
                    />
                  </svg>
                </div>
              </div>
              <div class="flex items-center">
                <div class="mr-3">
                  <hr class="w-0 h-8 border-l border-gray-500" />
                </div>
                <div class="mr-3">
                  <svg
                    class="w-6 h-6 text-blue-500 hover:text-blue-600"
                    viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      class="fill-current"
                      d="M12 22a10 10 0 110-20 10 10 0 010 20zm0-2a8 8 0 100-16 8 8 0 000 16zm1-9h2a1 1 0 010 2h-2v2a1 1 0 01-2 0v-2H9a1 1 0 010-2h2V9a1 1 0 012 0v2z"
                    />
                  </svg>
                </div>
                <div>
                  <button
                    class="bg-blue-500 hover:bg-blue-600 text-white font-bold rounded-full px-4 py-2"
                    type="submit"
                  >
                    Tweet
                  </button>
                </div>
              </div>
            </div>
          </form>
        </div>
        <div class="p-3 border-b">
          <div class="flex">
            <div class="w-1/12 flex-none">
              <img
                class="w-12 h-12 rounded-full"
                src="http://source.unsplash.com/iFgRcqHznqg/60x60"
                alt="John Doe"
              />
            </div>
            <div class="w-11/12 flex-none">
              <div class="flex justify-between">
                <h2 class="font-bold">
                  <a class="hover:underline" href="/JohnDoe"
                    >John Doe
                    <span>
                      <svg
                        aria-label="Verified account"
                        class="inline-block w-5 h-5 text-blue-500"
                        viewBox="0 0 24 24"
                      >
                        <path
                          class="fill-current"
                          d="M22.5 12.5c0-1.58-.875-2.95-2.148-3.6.154-.435.238-.905.238-1.4 0-2.21-1.71-3.998-3.818-3.998-.47 0-.92.084-1.336.25C14.818 2.415 13.51 1.5 12 1.5s-2.816.917-3.437 2.25a3.606 3.606 0 00-1.336-.25c-2.11 0-3.818 1.79-3.818 4 0 .494.083.964.237 1.4-1.272.65-2.147 2.018-2.147 3.6 0 1.495.782 2.798 1.942 3.486-.02.17-.032.34-.032.514 0 2.21 1.708 4 3.818 4 .47 0 .92-.086 1.335-.25.62 1.334 1.926 2.25 3.437 2.25 1.512 0 2.818-.916 3.437-2.25.415.163.865.248 1.336.248 2.11 0 3.818-1.79 3.818-4 0-.174-.012-.344-.033-.513 1.158-.687 1.943-1.99 1.943-3.484zm-6.616-3.334l-4.334 6.5a.749.749 0 01-1.041.208l-.115-.094-2.415-2.415a.749.749 0 111.06-1.06l1.77 1.767 3.825-5.74a.75.75 0 011.25.833z"
                        /></svg></span
                    ><span class="font-normal text-sm text-gray-600">
                      @JohnDoe</span
                    ></a
                  >
                  <span class="font-normal text-sm text-gray-600"> • </span>
                  <time class="font-normal text-gray-600 hover:underline"
                    ><a href="/">20<span class="text-sm">s</span></a></time
                  >
                </h2>
                <a href="">
                  <svg
                    class="w-6 h-6 text-gray-600"
                    viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      class="fill-current"
                      d="M4 15a3 3 0 110-6 3 3 0 010 6zm0-2a1 1 0 100-2 1 1 0 000 2zm8 2a3 3 0 110-6 3 3 0 010 6zm0-2a1 1 0 100-2 1 1 0 000 2zm8 2a3 3 0 110-6 3 3 0 010 6zm0-2a1 1 0 100-2 1 1 0 000 2z"
                    />
                  </svg>
                </a>
              </div>
              <p class="">
                A serious question: why is Morrison behaving like this? OK, he
                doesn’t want to serious action on climate. But then again no
                world leader is proposing the kind of action we need — and yet
                most politicians would have the sense to put themselves in the
                centre of bush fire relief.
              </p>
              <div class="flex justify-between pt-3 pr-24">
                <a class="flex text-gray-600 hover:text-blue-500" href="">
                  <svg
                    class="w-6 h-6 text-gray-500 hover:text-blue-500"
                    viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      class="fill-current"
                      d="M2 15V5c0-1.1.9-2 2-2h16a2 2 0 012 2v15a1 1 0 01-1.7.7L16.58 17H4a2 2 0 01-2-2zM20 5H4v10h13a1 1 0 01.7.3l2.3 2.29V5z"
                    />
                  </svg>
                  <span class="pl-3">1</span>
                </a>
                <a href="">
                  <svg
                    class="w-6 h-6 text-gray-500 hover:text-blue-500"
                    viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      class="fill-current"
                      d="M5.41 16H18a2 2 0 002-2 1 1 0 012 0 4 4 0 01-4 4H5.41l2.3 2.3a1 1 0 01-1.42 1.4l-4-4a1 1 0 010-1.4l4-4a1 1 0 111.42 1.4L5.4 16zM6 8a2 2 0 00-2 2 1 1 0 01-2 0 4 4 0 014-4h12.59l-2.3-2.3a1 1 0 111.42-1.4l4 4a1 1 0 010 1.4l-4 4a1 1 0 01-1.42-1.4L18.6 8H6z"
                    />
                  </svg>
                </a>
                <a class="flex text-gray-600 hover:text-blue-500" href="">
                  <svg
                    class="w-6 h-6 text-gray-500 hover:text-blue-500"
                    viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      class="fill-current"
                      d="M12.76 3.76a6 6 0 018.48 8.48l-8.53 8.54a1 1 0 01-1.42 0l-8.53-8.54a6 6 0 018.48-8.48l.76.75.76-.75zm7.07 7.07a4 4 0 10-5.66-5.66l-1.46 1.47a1 1 0 01-1.42 0L9.83 5.17a4 4 0 10-5.66 5.66L12 18.66l7.83-7.83z"
                    />
                  </svg>
                  <span class="pl-3">4</span>
                </a>
                <a href="">
                  <svg
                    class="w-6 h-6 text-gray-500 hover:text-blue-500"
                    viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      class="fill-current"
                      d="M13 5.41V17a1 1 0 01-2 0V5.41l-3.3 3.3a1 1 0 01-1.4-1.42l5-5a1 1 0 011.4 0l5 5a1 1 0 11-1.4 1.42L13 5.4zM3 17a1 1 0 012 0v3h14v-3a1 1 0 012 0v3a2 2 0 01-2 2H5a2 2 0 01-2-2v-3z"
                    />
                  </svg>
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </main>
    <aside class="flex flex-col w-3/12">
      <div>
        <input type="text" placeholder="Search Twitter" />
      </div>
      <div class="overflow-y-auto"></div>
    </aside>
  </div>
</template>

<script>
export default {
  name: "home"
};
</script>
