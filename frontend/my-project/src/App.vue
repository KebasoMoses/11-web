<template>
  <div class="max-w-none w-auto min-h-screen grid grid-cols-[20rem,1fr,16rem] gap-4">
    <div class="sticky h-screen bg-slate-500  left-0">
      <div class="m-2">
        <button class="w-full bg-green-500 rounded-sm shadow-sm bg-gradient-to-tr hover:bg-green-900 hover:text-white hover:outline-red-600">MoBlog</button>
      </div>
      <ul>
        <div class="p-3 m-2 cursor-pointer bg-slate-50 shadow-md rounded-md bg-gradient-to-br">
          <button class="">Home</button>
        </div>
        <div class="p-3 m-2 cursor-pointer  bg-red-300 shadow-md rounded-md bg-gradient-to-br">
          <button class="">shop</button>
        </div>
        <div class="p-3 m-2 cursor-pointer  bg-slate-600 shadow-md rounded-md bg-gradient-to-br">
          <button class="">contact</button>
        </div>
        
        <li></li>
        <li></li>
      </ul>
      <div class="mt-9 p-3">
        <a class="mx-1 w-12 h-12 bg-gray-700 text-white rounded-full inline-flex justify-center items-center hover:bg-white" href="#">
          <i class="fa fa-twitter text-white hover:text-black text-lg p-1"></i>
        </a>
        <a class="mx-1 w-12 h-12 bg-gray-700 text-white rounded-full inline-flex justify-center items-center hover:bg-white" href="#">
          <i class="fa fa-linkedin text-white hover:text-black text-lg p-1"></i>
        </a>
        <a class="mx-1 w-12 h-12 bg-gray-700 text-white rounded-full inline-flex justify-center items-center hover:bg-white" href="#">
          <i class="fa fa-github text-white hover:text-black text-lg p-1"></i>
        </a>
        <a class="mx-1 w-12 h-12 bg-gray-700 text-white rounded-full inline-flex justify-center items-center hover:bg-white" href="#">
          <i class="fa fa-facebook text-white hover:text-black text-lg p-1"></i>
        </a>
        <a class="mx-1 w-12 h-12 bg-gray-700 text-white rounded-full inline-flex justify-center items-center hover:bg-white" href="#">
          <i class="fa fa-youtube text-white hover:text-black text-lg p-1"></i>
        </a>
        
      </div>

      <div class="max-w-none bg-teal-700 text-white mt-12 m-8 p-3 flex items-center relative">
        <img src="https://images.pexels.com/photos/7562313/pexels-photo-7562313.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=100" alt="" class="w-16 h-16 object-cover mr-4 rounded-md">
        <div>
          <p class=" text-lg font-bold">Moses Mecha</p>
          <span class="text-sm opacity-90">Software Engineer</span>
        </div>
        <div class="text-orange-400 mr-1 absolute top-2 right-1">
          <i class="fa fa-star"></i>
          <span>5.0</span>
        </div>
      </div>


      <div class="mt-7 p-5 absolute bottom-0">
        <div class="flex gap-3">
          <span>
            <button class=" bg-black text-white rounded-md p-3">Upgrade</button>
          </span>
          <span>
            <button class=" bg-orange-200 text-white rounded-md p-3">Settings</button>
          </span>
          <span>
            <button class=" bg-amber-200 text-white rounded-md p-3">contact</button>
          </span>
        </div>
      </div>
    </div>
    <!-- Second child -->
    <div class=" m-0 bg-red-300 overflow-y-scroll">
      <header class="flex justify-between items-center bg-white py-5 px-6">
        <a href="#" class="flex-1">
          <img class="inline h-7" src="https://res.cloudinary.com/thirus/image/upload/v1628614672/logos/circleai_dm9slt.png" alt="" />
        </a>
        <ul class=" inline-flex">
          <li>
            <a  href="" class="inline-block mx-5">Home</a>
          </li>
          <li>
            <a  href="" class="inline-block mx-5">About Us</a>
          </li>
          <li>
            <a  href="" class="inline-block mx-5">Pricing</a>
          </li>
          <li>
            <a  href="" class="inline-block mx-5">Products</a>
          </li>
        </ul>
        <span class=" text-right  bg-blue-500 text-white p-3 rounded-full">
          <a href="#" class="btn justify-center">Join us</a>
        </span>
      </header>

      <div class="mt-5 grid sm:grid-cols-2 md:grid-cols-3 gap-x-4 gap-y-4 max-w-7xl p-3 mx-auto">
        <div class=" rounded-lg bg-white">
          <img class="w-full h-auto object-cover rounded-t-lg" src="https://picsum.photos/400/300" alt="" />
          <div class="p-4">
            <h2 class="font-bold text-2xl">Blog title 1</h2>
            <p class="mt-2 mb-1">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nemo assumenda porro inventore repellendus
              ipsum.</p>
            <a href="#" class="text-lg font-bold text-purple-600">Read more</a>
          </div>
        </div>
        <div class=" rounded-lg bg-white">
          <img class="w-full h-auto object-cover rounded-t-lg" src="https://picsum.photos/400/302" alt="" />
          <div class="p-4">
            <h2 class="font-bold text-2xl">Blog title 2</h2>
            <p class="mt-2 mb-1">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nemo assumenda porro inventore repellendus
              ipsum.</p>
            <a href="#" class="text-lg font-bold text-purple-600">Read more</a>
          </div>
        </div>
        <div class=" rounded-lg bg-white">
          <img class="w-full h-auto object-cover rounded-t-lg" src="https://picsum.photos/400/303" alt="" />
          <div class="p-4">
            <h2 class="font-bold text-2xl">Blog title 3</h2>
            <p class="mt-2 mb-1">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nemo assumenda porro inventore repellendus
              ipsum.</p>
            <a href="#" class="text-lg font-bold text-purple-600">Read more</a>
          </div>
        </div>
        <div class=" rounded-lg bg-white">
          <img class="w-full h-auto object-cover rounded-t-lg" src="https://picsum.photos/400/304" alt="" />
          <div class="p-4">
            <h2 class="font-bold text-2xl">Blog title 3</h2>
            <p class="mt-2 mb-1">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nemo assumenda porro inventore repellendus
              ipsum.</p>
            <a href="#" class="text-lg font-bold text-purple-600">Read more</a>
          </div>
        </div>
        <div class=" rounded-lg bg-white">
          <img class="w-full h-auto object-cover rounded-t-lg" src="https://picsum.photos/400/305" alt="" />
          <div class="p-4">
            <h2 class="font-bold text-2xl">Blog title 3</h2>
            <p class="mt-2 mb-1">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nemo assumenda porro inventore repellendus
              ipsum.</p>
            <a href="#" class="text-lg font-bold text-purple-600">Read more</a>
          </div>
        </div>
      </div>
      
  
      <p></p> 
      <p></p>
      <p></p>
    </div>
    <!-- Third Child -->
    <div class=" bg-slate-400 p-1 sticky h-screen right-0">
        <div class="relative h-15 w-15">
          <img class=" items-center flex mx-auto h-15 w-15 rounded-full " src="https://res.cloudinary.com/thirus/image/upload/v1635414289/images/avatar_jq0fmw.png" alt="">
          <span class="absolute top-0 right-0">2</span>
        </div>
      
      <div class="items-center text-center mx-auto">
        <h1>Moses Mecha</h1>
        <p>Software engineer</p>
      </div>
      <div class="max-w-none bg-white  mx-auto p-2 mt-3 rounded-lg flex items-center">
        <i class="fa fa-bell mr-2"></i>
        <span class="text-lg">Notifications</span>
        <span class="py-px px-2 bg-blue-50 text-blue-800 text-lg rounded ml-auto">2</span>
      </div>
      <div class="p-1 mt-5">
        <div
            class="flex border-2 border-gray-200 rounded-md focus-within:ring-2 ring-teal-500"
          >
            <input
              type="text"
              class="w-full rounded-tl-md rounded-bl-md px-2 py-3 text-sm text-gray-600 focus:outline-none"
              placeholder="Search"
            />
            <button
              class="rounded-tr-md rounded-br-md px-2 py-3 hidden md:block"
            >
              <svg
                class="w-4 h-4 fill-current"
                fill="currentColor"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z"
                  clip-rule="evenodd"
                ></path>
              </svg>
            </button>
          </div>
      </div>
      <p></p>
      <p></p>
      <p></p>
      <p></p>
    </div>
  </div>
</template>