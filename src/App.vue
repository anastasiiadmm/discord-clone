<script setup>

</script>

<template>
  <div class="flex">
    <div class="bg-gray-900 w-20 flex-none flex flex-col min-h-screen h-screen px-2 py-2">
      <div class="overflow-y-auto">
        <ul class="text-center">
          <li>
            <a href="">
              <img src="./assets/images/discord-logo.png"
                   alt="discord"
                   class="w-12 h-12 rounded-full mx-auto"
              />
            </a>
          </li>
          <li class="border-b border-gray-700 mx-4 mt-3"></li>
          <li class="mt-3">
            <a href="#">
              <img src="./assets/images/vue-js-icon.png" alt="vue"
                   class="w-9 h-7 rounded-full mx-auto"
              />
            </a>
          </li>
          <li class="mt-3">
            <a href="#" class="hover:bg-teal-500 hover:text-white">
              <img src="./assets/images/tailwind-css-icon.svg" alt="tailwind"
                   class="w-11 h-10 rounded-full mx-auto"
              />
            </a>
          </li>
          <li class="mt-3">
            <a href="#"
               class="hover:bg-teal-500 hover:text-white w-12 h-12 bg-gray-800 text-teal-500 inline-block rounded-full">
              <img alt="plus" class="w-5 h-5 mx-auto my-3.5" src="./assets/images/plus-sign.png"/>
            </a>
          </li>
          <li class="border-b border-gray-700 mx-4 mt-3"></li>
          <li class="mt-3">
            <a href="#"
               class="hover:bg-teal-500 hover:text-white w-12 h-12 bg-gray-800 text-teal-500 inline-block rounded-full">
              <img alt="compass" class="w-5 h-5 mx-auto my-3.5" src="./assets/images/compass-svgrepo-com.svg"/>
            </a>
          </li>
        </ul>
      </div>
    </div>
    <div class="flex flex-col min-h-screen h-screen">
      <div class="flex text-white h-12">
        <div class="bg-gray-800 border-b border-gray-900 w-56 flex-none flex items-center justify-between px-3 py-2">
          <div>CSS</div>
          <button>
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-caret-down"
                 viewBox="0 0 16 16">
              <path
                  d="M3.204 5h9.592L8 10.481 3.204 5zm-.753.659 4.796 5.48a1 1 0 0 0 1.506 0l4.796-5.48c.566-.647.106-1.659-.753-1.659H3.204a1 1 0 0 0-.753 1.659z"/>
            </svg>
          </button>
        </div>
        <div class="flex-1 bg-gray-700 flex items-center justify-between px-4 border-b border-gray-900">
          <div class="flex items-center">
            <div class="text-gray-500 text-2xl">#</div>
            <div class="ml-2 text-sm text-white">general</div>
            <div class="border-l pl-3 ml-3 border-gray-600 text-xs text-gray-400">tasks-questions</div>
          </div>
          <div class="flex items-center">
            <a href="#" class="ml-4">
              <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-hash"
                   viewBox="0 0 16 16">
                <path
                    d="M8.39 12.648a1.32 1.32 0 0 0-.015.18c0 .305.21.508.5.508.266 0 .492-.172.555-.477l.554-2.703h1.204c.421 0 .617-.234.617-.547 0-.312-.188-.53-.617-.53h-.985l.516-2.524h1.265c.43 0 .618-.227.618-.547 0-.313-.188-.524-.618-.524h-1.046l.476-2.304a1.06 1.06 0 0 0 .016-.164.51.51 0 0 0-.516-.516.54.54 0 0 0-.539.43l-.523 2.554H7.617l.477-2.304c.008-.04.015-.118.015-.164a.512.512 0 0 0-.523-.516.539.539 0 0 0-.531.43L6.53 5.484H5.414c-.43 0-.617.22-.617.532 0 .312.187.539.617.539h.906l-.515 2.523H4.609c-.421 0-.609.219-.609.531 0 .313.188.547.61.547h.976l-.516 2.492c-.008.04-.015.125-.015.18 0 .305.21.508.5.508.265 0 .492-.172.554-.477l.555-2.703h2.242l-.515 2.492zm-1-6.109h2.266l-.515 2.563H6.859l.532-2.563z"/>
              </svg>
            </a>
            <a href="#" class="ml-4">
              <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-bell"
                   viewBox="0 0 16 16">
                <path
                    d="M8 16a2 2 0 0 0 2-2H6a2 2 0 0 0 2 2zM8 1.918l-.797.161A4.002 4.002 0 0 0 4 6c0 .628-.134 2.197-.459 3.742-.16.767-.376 1.566-.663 2.258h10.244c-.287-.692-.502-1.49-.663-2.258C12.134 8.197 12 6.628 12 6a4.002 4.002 0 0 0-3.203-3.92L8 1.917zM14.22 12c.223.447.481.801.78 1H1c.299-.199.557-.553.78-1C2.68 10.2 3 6.88 3 6c0-2.42 1.72-4.44 4.005-4.901a1 1 0 1 1 1.99 0A5.002 5.002 0 0 1 13 6c0 .88.32 4.2 1.22 6z"/>
              </svg>
            </a>
            <a href="#" class="ml-4">
              <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                   class="bi bi-pin-angle-fill" viewBox="0 0 16 16">
                <path
                    d="M9.828.722a.5.5 0 0 1 .354.146l4.95 4.95a.5.5 0 0 1 0 .707c-.48.48-1.072.588-1.503.588-.177 0-.335-.018-.46-.039l-3.134 3.134a5.927 5.927 0 0 1 .16 1.013c.046.702-.032 1.687-.72 2.375a.5.5 0 0 1-.707 0l-2.829-2.828-3.182 3.182c-.195.195-1.219.902-1.414.707-.195-.195.512-1.22.707-1.414l3.182-3.182-2.828-2.829a.5.5 0 0 1 0-.707c.688-.688 1.673-.767 2.375-.72a5.922 5.922 0 0 1 1.013.16l3.134-3.133a2.772 2.772 0 0 1-.04-.461c0-.43.108-1.022.589-1.503a.5.5 0 0 1 .353-.146z"/>
              </svg>
            </a>
            <a href="#" class="ml-4">
              <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                   class="bi bi-people-fill" viewBox="0 0 16 16">
                <path d="M7 14s-1 0-1-1 1-4 5-4 5 3 5 4-1 1-1 1H7zm4-6a3 3 0 1 0 0-6 3 3 0 0 0 0 6z"/>
                <path fill-rule="evenodd"
                      d="M5.216 14A2.238 2.238 0 0 1 5 13c0-1.355.68-2.75 1.936-3.72A6.325 6.325 0 0 0 5 9c-4 0-5 3-5 4s1 1 1 1h4.216z"/>
                <path d="M4.5 8a2.5 2.5 0 1 0 0-5 2.5 2.5 0 0 0 0 5z"/>
              </svg>
            </a>
            <a href="#" class="ml-4">
              <form action="#" class="relative">
                <input type="text" placeholder="Search" class="rounded bg-gray-900 text-gray-200 text-xs px-2 py-1"/>
                <span class="absolute right-0 top-0 mr-1" style="top:6px">
                  <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                       class="bi bi-search" viewBox="0 0 16 16"
                  >
                      <path
                          d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z"/>
                  </svg>
                </span>
              </form>
            </a>
            <a href="#" class="ml-4">
              <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                   class="bi bi-inbox-fill" viewBox="0 0 16 16">
                <path
                    d="M4.98 4a.5.5 0 0 0-.39.188L1.54 8H6a.5.5 0 0 1 .5.5 1.5 1.5 0 1 0 3 0A.5.5 0 0 1 10 8h4.46l-3.05-3.812A.5.5 0 0 0 11.02 4H4.98zm-1.17-.437A1.5 1.5 0 0 1 4.98 3h6.04a1.5 1.5 0 0 1 1.17.563l3.7 4.625a.5.5 0 0 1 .106.374l-.39 3.124A1.5 1.5 0 0 1 14.117 13H1.883a1.5 1.5 0 0 1-1.489-1.314l-.39-3.124a.5.5 0 0 1 .106-.374l3.7-4.625z"/>
              </svg>
            </a>
            <a href="#" class="ml-4">
              <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                   class="bi bi-question-circle" viewBox="0 0 16 16">
                <path d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14zm0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16z"/>
                <path
                    d="M5.255 5.786a.237.237 0 0 0 .241.247h.825c.138 0 .248-.113.266-.25.09-.656.54-1.134 1.342-1.134.686 0 1.314.343 1.314 1.168 0 .635-.374.927-.965 1.371-.673.489-1.206 1.06-1.168 1.987l.003.217a.25.25 0 0 0 .25.246h.811a.25.25 0 0 0 .25-.25v-.105c0-.718.273-.927 1.01-1.486.609-.463 1.244-.977 1.244-2.056 0-1.511-1.276-2.241-2.673-2.241-1.267 0-2.655.59-2.75 2.286zm1.557 5.763c0 .533.425.927 1.01.927.609 0 1.028-.394 1.028-.927 0-.552-.42-.94-1.029-.94-.584 0-1.009.388-1.009.94z"/>
              </svg>
            </a>
          </div>
        </div>
      </div>
      <div class="flex-1 bg-blue-500 flex overflow-y-hidden">
        <div class="bg-gray-800 w-56 flex-none flex flex-col justify-between">
          <div class="text-sm overflow-y-auto">
            <ul class="px-2 py-3">
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-900 rounded">
                <a href="#" class="flex items-center">
                  <span class="text-xl">#</span>
                  <span class="ml-2">questions</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-900 rounded">
                <a href="#" class="flex items-center">
                  <span class="text-xl">#</span>
                  <span class="ml-2">announcements</span>
                </a>
              </li>
            </ul>

            <button class="flex items-center text-gray-500 hover:text-gray-200 uppercase">
              <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-caret-down mr-2 ml-1"
                   viewBox="0 0 16 16">
                <path
                    d="M3.204 5h9.592L8 10.481 3.204 5zm-.753.659 4.796 5.48a1 1 0 0 0 1.506 0l4.796-5.48c.566-.647.106-1.659-.753-1.659H3.204a1 1 0 0 0-.753 1.659z"/>
              </svg>
              General
            </button>
            <ul class="px-2 py-3">
              <li class="text-white px-2 hover:text-gray-200 hover:bg-gray-900 bg-gray-700 rounded">
                <a href="#" class="flex items-center">
                  <span class="text-xl">#</span>
                  <span class="ml-2">tasks-questions</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-900 rounded">
                <a href="#" class="flex items-center">
                  <span class="text-xl">#</span>
                  <span class="ml-2">tests-questions</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-900 rounded">
                <a href="#" class="flex items-center">
                  <span class="text-xl">#</span>
                  <span class="ml-2">just-for-fun</span>
                </a>
              </li>
            </ul>

            <button class="flex items-center text-gray-500 hover:text-gray-200 uppercase">
              <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-caret-down mr-2 ml-1"
                   viewBox="0 0 16 16">
                <path
                    d="M3.204 5h9.592L8 10.481 3.204 5zm-.753.659 4.796 5.48a1 1 0 0 0 1.506 0l4.796-5.48c.566-.647.106-1.659-.753-1.659H3.204a1 1 0 0 0-.753 1.659z"/>
              </svg>
              Useful information
            </button>
            <ul class="px-2 py-3">
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-900 rounded">
                <a href="#" class="flex items-center">
                  <span class="text-xl">#</span>
                  <span class="ml-2">random</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-900 rounded">
                <a href="#" class="flex items-center">
                  <span class="text-xl">#</span>
                  <span class="ml-2">materials-links</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-900 rounded">
                <a href="#" class="flex items-center">
                  <span class="text-xl">#</span>
                  <span class="ml-2">materials-information</span>
                </a>
              </li>
            </ul>

          </div>
          <div class="bg-slate-900 py-2 py-2 flex items-center justify-between">
            <div class="flex items-center">
              <a href="">
                <img src="./assets/images/discord-logo.png"
                     alt="discord"
                     class="w-8 h-8 rounded-full mx-auto"
                />
              </a>
              <div class="text-xs ml-2">
                <div class="text-white">user</div>
                <div class="text-gray-700 text-xs">#4576</div>
              </div>
            </div>
            <div class="flex items-center text-gray-500">
              <a href="#" class="ml-3">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-mic-mute-fill" viewBox="0 0 16 16">
                  <path d="M13 8c0 .564-.094 1.107-.266 1.613l-.814-.814A4.02 4.02 0 0 0 12 8V7a.5.5 0 0 1 1 0v1zm-5 4c.818 0 1.578-.245 2.212-.667l.718.719a4.973 4.973 0 0 1-2.43.923V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 1 0v1a4 4 0 0 0 4 4zm3-9v4.879L5.158 2.037A3.001 3.001 0 0 1 11 3z"/>
                  <path d="M9.486 10.607 5 6.12V8a3 3 0 0 0 4.486 2.607zm-7.84-9.253 12 12 .708-.708-12-12-.708.708z"/>
                </svg>
              </a>
              <a href="#" class="ml-3">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-headphones" viewBox="0 0 16 16">
                  <path d="M8 3a5 5 0 0 0-5 5v1h1a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V8a6 6 0 1 1 12 0v5a1 1 0 0 1-1 1h-1a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1h1V8a5 5 0 0 0-5-5z"/>
                </svg>
              </a>
              <a href="#" class="ml-3 mr-3">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-gear-fill" viewBox="0 0 16 16">
                  <path d="M9.405 1.05c-.413-1.4-2.397-1.4-2.81 0l-.1.34a1.464 1.464 0 0 1-2.105.872l-.31-.17c-1.283-.698-2.686.705-1.987 1.987l.169.311c.446.82.023 1.841-.872 2.105l-.34.1c-1.4.413-1.4 2.397 0 2.81l.34.1a1.464 1.464 0 0 1 .872 2.105l-.17.31c-.698 1.283.705 2.686 1.987 1.987l.311-.169a1.464 1.464 0 0 1 2.105.872l.1.34c.413 1.4 2.397 1.4 2.81 0l.1-.34a1.464 1.464 0 0 1 2.105-.872l.31.17c1.283.698 2.686-.705 1.987-1.987l-.169-.311a1.464 1.464 0 0 1 .872-2.105l.34-.1c1.4-.413 1.4-2.397 0-2.81l-.34-.1a1.464 1.464 0 0 1-.872-2.105l.17-.31c.698-1.283-.705-2.686-1.987-1.987l-.311.169a1.464 1.464 0 0 1-2.105-.872l-.1-.34zM8 10.93a2.929 2.929 0 1 1 0-5.86 2.929 2.929 0 0 1 0 5.858z"/>
                </svg>
              </a>
            </div>
          </div>
        </div>
        <div class="flex-1 flex justify-between">
          <div class="bg-gray-700 flex-1 flex flex-col justify-between">
            <div class="overflow-y-auto">
              Display. Integer condimentum at massa in vulputate. Proin nec odio elementum, placerat mauris vitae,
              dignissim diam. Donec ullamcorper imperdiet fermentum. Integer sagittis, lectus tempor pretium semper,
              elit
              augue consequat quam, blandit elementum erat libero id diam. In sodales tincidunt nunc, eu iaculis turpis
              suscipit a. In porta neque eleifend eleifend congue. Ut ac hendrerit mauris, efficitur lobortis massa.
              Duis
              tristique ligula eget arcu venenatis dignissim. Aliquam euismod nisi vitae vestibulum facilisis. Fusce
              sagittis metus nec justo interdum suscipit quis ut felis. Nullam sed imperdiet erat. Cras sed leo
              efficitur,
              vehicula ipsum at, euismod libero. Nulla eleifend facilisis malesuada. Nunc vehicula ac elit sit amet
              sollicitudin. Quisque feugiat justo at erat venenatis, in efficitur massa feugiat.
              In nisl metus, consectetur in sollicitudin eu, semper vel elit. Nunc nunc erat, ornare at ullamcorper ac,
              pulvinar at sapien. Sed nec feugiat lorem, eu porta ipsum. Proin finibus neque mauris, sit amet convallis
              leo elementum quis. Vestibulum vitae pellentesque arcu, a blandit tellus. Aliquam consequat blandit felis,
              quis ullamcorper est sagittis nec. Sed tristique a tortor blandit viverra. In eu nulla eget lectus
              eleifend
              aliquet.
            </div>
            <div class="bg-gray-500 bottom">
              Bottom
            </div>
          </div>

          <div class="bg-indigo-600 w-56 flex-none overflow-y-auto">Users. Integer condimentum at massa in vulputate.
            Proin nec odio elementum, placerat mauris vitae, dignissim diam. Donec ullamcorper imperdiet fermentum.
            Integer sagittis, lectus tempor pretium semper, elit augue consequat quam, blandit elementum erat libero id
            diam. In sodales tincidunt nunc, eu iaculis turpis suscipit a. In porta neque eleifend eleifend congue. Ut
            ac
            hendrerit mauris, efficitur lobortis massa. Duis tristique ligula eget arcu venenatis dignissim. Aliquam
            euismod nisi vitae vestibulum facilisis. Fusce sagittis metus nec justo interdum suscipit quis ut felis.
            Nullam sed imperdiet erat. Cras sed leo efficitur, vehicula ipsum at, euismod libero. Nulla eleifend
            facilisis
            malesuada. Nunc vehicula ac elit sit amet sollicitudin. Quisque feugiat justo at erat venenatis, in
            efficitur
            massa feugiat.

            In nisl metus, consectetur in sollicitudin eu, semper vel elit. Nunc nunc erat, ornare at ullamcorper ac,
            pulvinar at sapien. Sed nec feugiat lorem, eu porta ipsum. Proin finibus neque mauris, sit amet convallis
            leo
            elementum quis. Vestibulum vitae pellentesque arcu, a blandit tellus. Aliquam consequat blandit felis, quis
            ullamcorper est sagittis nec. Sed tristique a tortor blandit viverra. In eu nulla eget lectus eleifend
            aliquet.
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>

</style>
