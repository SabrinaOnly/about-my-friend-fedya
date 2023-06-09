<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <!-- header-start -->
<div class="bg-white">
  <header class="absolute inset-x-0 top-0 z-50">
    <nav class="flex items-center justify-between p-6 lg:px-8" aria-label="Global">
      <div class="flex lg:flex-1"></div>
      <div class="flex lg:hidden">
        <button type="button" class="-m-2.5 inline-flex items-center justify-center rounded-md p-2.5 text-gray-700">
          <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true">
            <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
          </svg>
        </button>
      </div>
      <div class="hidden lg:flex lg:gap-x-12">
        <RouterLink class="text-sm font-semibold leading-6 text-gray-900" to="/about">О нем </RouterLink>
        <RouterLink class="text-sm font-semibold leading-6 text-gray-900" to="/about">Его характер</RouterLink>
        <RouterLink class="text-sm font-semibold leading-6 text-gray-900" to="/about">Его путь </RouterLink>
        <RouterLink class="text-sm font-semibold leading-6 text-gray-900" to="/about">Читать больше </RouterLink>       
      </div>
      <div class="hidden lg:flex lg:flex-1 lg:justify-end">
        <a href="#" class="text-sm font-semibold leading-6 text-gray-900"> <span aria-hidden="true">&rarr;</span></a>
      </div>
    </nav>
    <!-- Mobile menu, show/hide based on menu open state. -->
    <div class="lg:hidden" role="dialog" aria-modal="true">
      <!-- Background backdrop, show/hide based on slide-over state. -->
      <div class="fixed inset-0 z-50"></div>
      <div class="fixed inset-y-0 right-0 z-50 w-full overflow-y-auto bg-white px-6 py-6 sm:max-w-sm sm:ring-1 sm:ring-gray-900/10">
        <div class="flex items-center justify-between">
          <a href="#" class="-m-1.5 p-1.5">
            <span class="sr-only">Your Company</span>
            <img class="h-8 w-auto" src="https://tailwindui.com/img/logos/mark.svg?color=indigo&shade=600" alt="">
          </a>
          <button type="button" class="-m-2.5 rounded-md p-2.5 text-gray-700">
            <span class="sr-only">Close menu</span>
            <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true">
              <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
            </svg>
          </button>
        </div>
        <div class="mt-6 flow-root">
          <div class="-my-6 divide-y divide-gray-500/10">
            <div class="space-y-2 py-6"> 
              <a class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-gray-900 hover:bg-gray-50">Features</a>
              <a class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-gray-900 hover:bg-gray-50">Marketplace</a>
              <a class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-gray-900 hover:bg-gray-50">Company</a>
            </div>
            <div class="py-6">
              <a href="#" class="-mx-3 block rounded-lg px-3 py-2.5 text-base font-semibold leading-7 text-gray-900 hover:bg-gray-50">Log in</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>

  <div class="relative isolate px-6 pt-14 lg:px-8">
    <div class="absolute inset-x-0 -top-40 -z-10 transform-gpu overflow-hidden blur-3xl sm:-top-80" aria-hidden="true">
      <div class="relative left-[calc(50%-11rem)] aspect-[1155/678] w-[36.125rem] -translate-x-1/2 rotate-[30deg] bg-gradient-to-tr from-[#ff80b5] to-[#9089fc] opacity-30 sm:left-[calc(50%-30rem)] sm:w-[72.1875rem]" style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)"></div>
    </div>
    <div class="mx-auto max-w-2xl py-32 sm:py-48 lg:py-56">
      <div class="hidden sm:mb-8 sm:flex sm:justify-center">
      </div>
      <div class="text-center">
        <h1 class="text-4xl font-bold tracking-tight text-gray-900 sm:text-6xl">Веб сайт посвщянный лучшему человеку </h1>
        <p class="mt-6 text-lg leading-8 text-gray-600">И этим лучшим человеком в моей жизни является дорогой мне по сути Фирдавс он для меня он считается одним из лучших ниже я обосновала почему  </p>
        <div class="mt-10 flex items-center justify-center gap-x-6">
          <a class="rounded-md bg-indigo-600 px-3.5 py-2.5 text-sm font-semibold text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600">Lorem, ipsum.</a>
          <a class="text-sm font-semibold leading-6 text-gray-900">Lorem, ipsum dolor. <span aria-hidden="true">→</span></a>
        </div>
      </div>
    </div>
    <div class="absolute inset-x-0 top-[calc(100%-13rem)] -z-10 transform-gpu overflow-hidden blur-3xl sm:top-[calc(100%-30rem)]" aria-hidden="true">
      <div class="relative left-[calc(50%+3rem)] aspect-[1155/678] w-[36.125rem] -translate-x-1/2 bg-gradient-to-tr from-[#ff80b5] to-[#9089fc] opacity-30 sm:left-[calc(50%+36rem)] sm:w-[72.1875rem]" style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)"></div>
    </div>
  </div>
</div>
<!-- header-end -->

<!-- main-start -->
<div class="overflow-hidden bg-white">
  <div class="pb-80 pt-16 sm:pb-40 sm:pt-24 lg:pb-48 lg:pt-40">
    <div class="relative mx-auto max-w-7xl px-4 sm:static sm:px-6 lg:px-8">
      <div class="sm:max-w-lg">
        <h1 class="text-4xl font-bold tracking-tight text-gray-900 sm:text-6xl">Предисловие ...</h1>
        <p class="mt-4 lea text-xl text-gray-500"> Федя - это человек, который привнес в мою жизнь новые краски и наполнение. при первом же знакомстве я сразу же ощутила, что он - исключительный, с самого начала меня привлекло его остроумие и способность сохранять спокойствие в любой ситуации...
        </p>
      </div>
      <div>
        <div class="mt-10">
          <!-- decorative-image-grid -->
          <div aria-hidden="true" class="pointer-events-none lg:absolute lg:inset-y-0 lg:mx-auto lg:w-full lg:max-w-7xl">
            <div class="absolute transform sm:left-1/2 sm:top-0 sm:translate-x-8 lg:left-1/2 lg:top-1/2 lg:-translate-y-1/2 lg:translate-x-8">
              <div class=" mt-[1700px]  flex items-center space-x-6 lg:space-x-8">
                <div class="grid flex-shrink-0 grid-cols-1 gap-y-6 lg:gap-y-8">
                  <div class="h-64 w-44 overflow-hidden rounded-lg sm:opacity-0 lg:opacity-100">
                    <img src="./assets/2.jpg" alt="" class="h-full w-full object-cover object-center">
                  </div>
                  <div class="h-64 w-44 overflow-hidden rounded-lg">
                    <img src="./assets/3.jpg" alt="" class="h-full w-full object-cover object-center">
                  </div>
                </div>
                <div class="grid flex-shrink-0 grid-cols-1 gap-y-6 lg:gap-y-8">
                  <div class="h-64 w-44 overflow-hidden rounded-lg">
                    <img src="./assets/5.jpg" alt="" class="h-full w-full object-cover object-center">
                  </div>
                  <div class="h-64 w-44 overflow-hidden rounded-lg">
                    <img src="./assets/4.jpg" alt="" class="h-full w-full object-cover object-center">
                  </div>
                  <div class="h-64 w-44 overflow-hidden rounded-lg">
                    <img src="https://tailwindui.com/img/ecommerce-images/home-page-03-hero-image-tile-05.jpg" alt="" class="h-full w-full object-cover object-center">
                  </div>
                </div>
                <div class="grid flex-shrink-0 grid-cols-1 gap-y-6 lg:gap-y-8">
                  <div class="h-64 w-44 overflow-hidden rounded-lg">
                    <img src="https://tailwindui.com/img/ecommerce-images/home-page-03-hero-image-tile-06.jpg" alt="" class="h-full w-full object-cover object-center">
                  </div>
                  <div class="h-64 w-44 overflow-hidden rounded-lg">
                    <img src="https://tailwindui.com/img/ecommerce-images/home-page-03-hero-image-tile-07.jpg" alt="" class="h-full w-full object-cover object-center">
                  </div>
                </div>
              </div>
            </div>
          </div>
          <nav>
            <RouterLink class="rounded-md bg-indigo-600 px-3.5 py-2.5 text-sm font-semibold text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600" to="/about"> Его темпирамент </RouterLink> &nbsp; &nbsp;
            <RouterLink class="text-sm font-semibold leading-6 text-gray-900" to="/">Закрыть <span aria-hidden="true">→</span></RouterLink>
          </nav>
        </div>
      </div>
    </div>
  </div>
<!-- main-end -->

<!-- about-fedya-start -->
<h1 class="font-bold text-4xl ml-40 mt-60">
      О Феде Урунове и о его <br> качесвах которыми я восхищаюсь
      <p class=" text-lg font-normal mt-6 w-[80%] ">Он выдающийся программист, который создает захватывающие веб-сайты и приложения. Я всегда восхищаюсь его способностью решать сложные задачи и находить изысканные решения
      он очень увлечен своей работой и всегда готов делиться своими знаниями со мной. Я часто слушаю его, когда он говорит об технологиях в сфере программирования.
      Но несмотря на то, что он так интенсивно занимается своей работой, он всегда находит время для меня. Он заботится о моих чувствах и всегда готов выслушать меня.
      Я ценю его за его ум и талант, но еще больше за его доброту и заботу. Я счастлива, что мы имеем такую сильную связь, основанную на взаимном уважении друг к другу...
      так же он является талантливым человеком, который создает удивительные сайты и приложения. Я люблю наблюдать за его творческим процессом и удивляться его способностям, Он всегда находит вдохновение в новых технологиях и передает свои знания через свои работы. Я часто обсуждаю с ним свои проекты и наслаждаюсь его техническими идеями.
      Но не только его талант делает его особенным но и его внимание он также заботится о моих чувствах и всегда готов выслушать меня. Я ценю его за его чуткость к ближнему. 
</p>
</h1>
<!-- avout-fedya-end -->

<!-- section-start -->
<section class="relative isolate overflow-hidden bg-white px-6 py-24 sm:py-32 lg:px-8">
  <div class="absolute inset-0 -z-10 bg-[radial-gradient(45rem_50rem_at_top,theme(colors.indigo.100),white)] opacity-20"></div>
  <div class="absolute inset-y-0 right-1/2 -z-10 mr-16 w-[200%] origin-bottom-left skew-x-[-30deg] bg-white shadow-xl shadow-indigo-600/10 ring-1 ring-indigo-50 sm:mr-28 lg:mr-0 xl:mr-16 xl:origin-center"></div>
  <div class="mx-auto max-w-2xl lg:max-w-4xl">
    <img class="mx-auto h-12" src="https://tailwindui.com/img/logos/workcation-logo-indigo-600.svg" alt="">
    <figure class="mt-10">
      <blockquote class="text-center text-xl font-semibold leading-8 text-gray-900 sm:text-2xl sm:leading-9">
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Cumque nobis eos quisquam aliquid repudiandae? Illo adipisci sunt beatae voluptates, in quia dolorem eum! Non iure animi corrupti maxime numquam aperiam.</p>
      </blockquote>
      <figcaption class="mt-10">
        <img class="mx-auto h-20 w-20 rounded-full" src="./assets/1.jpg" alt="">
        <div class="mt-4 flex items-center justify-center space-x-3 text-base">
          <div class="font-semibold text-gray-900">Firdavs Urunov</div>
          <svg viewBox="0 0 2 2" width="3" height="3" aria-hidden="true" class="fill-gray-900">
            <circle cx="1" cy="1" r="1" />
          </svg>
          <div class="text-gray-600">Frontend developer</div>
        </div>
      </figcaption>
    </figure>
  </div>
</section>
</div>
<!-- section-end -->

<!-- content-start -->
<div class="mt-[-100px] bg-white py-24 sm:py-32">
  <div class="mx-auto max-w-7xl px-6 lg:px-8">
    <div class="mx-auto max-w-2xl lg:mx-0">
      <h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">Eго путь к фронтенд <br> разработке</h2>
      <p class="mt-2 leading-8 text-gray-600 text-sm">Опыт в разработке 2 года</p>
      <p class="">Как и любой другой путь, путь во фронтенд разработку требует терпения, упорства и постоянного обучения.  Он уже прошел почти все эти этапы и стал известным веб-разработчиком среди города Худжанда</p>
    </div>
    <div class="mx-auto mt-10 grid max-w-2xl grid-cols-1 gap-x-8 gap-y-16 border-t border-gray-200 pt-10 sm:mt-16 sm:pt-16 lg:mx-0 lg:max-w-none lg:grid-cols-3">
      <article class="flex max-w-xl flex-col items-start justify-between">
        <div class="flex items-center gap-x-4 text-xs">
          <time datetime="2020-03-16" class="text-gray-500">June 08, 2023</time>
          <div  class="relative z-10 rounded-full bg-gray-50 px-3 py-1.5 font-medium text-gray-600 hover:bg-gray-100">Frontend Developer</div>
        </div>
        <div class="group relative">
          <h3 class="mt-3 text-lg font-semibold leading-6 text-gray-900 group-hover:text-gray-600">
            <a href="#">
              <span class="absolute inset-0"></span>
              Lorem ipsum dolor sit.
            </a>
          </h3>
          <p class="mt-5 line-clamp-3 text-sm leading-6 text-gray-600">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorem nulla veritatis natus perferendis magnam possimus ea vero quis optio repellat neque asperiores nostrum sint corporis, mollitia numquam eum! Esse, fugit.</p>
        </div>
        <div class="relative mt-8 flex items-center gap-x-4">
          <img src="https://images.unsplash.com/photo-1519244703995-f4e0f30006d5?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="" class="h-10 w-10 rounded-full bg-gray-50">
          <div class="text-sm leading-6">
            <p class="font-semibold text-gray-900">
              <a href="#">
                <span class="absolute inset-0"></span>
                Firdavs Urunov
              </a>
            </p>
            <p class="text-gray-600">Frontend Developer</p>
          </div>
        </div>
      </article>
    </div>
  </div>
</div>
<!-- content-end -->
</template>




<style scoped>

</style>
