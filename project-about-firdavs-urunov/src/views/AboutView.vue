<template>
  <!-- HEADER-START -->
  <div class="relative isolate overflow-hidden bg-gray-900 py-16 sm:py-24 lg:py-32">
    <div class="mx-auto max-w-7xl px-6 lg:px-8">
      <div class="mx-auto grid max-w-2xl grid-cols-1 gap-x-8 gap-y-16 lg:max-w-none lg:grid-cols-2">
        <div class="max-w-xl lg:max-w-lg">
          <h2 class="text-3xl font-bold tracking-tight text-white sm:text-4xl">Главные черты его <br> характера</h2>
          <p class="mt-4 text-lg leading-7 text-gray-300">Одним из его главных достоинств является заботливость. Он всегда
            готов выслушать меня и поддержать в трудный момент. Кроме того, он стимулирует меня на успех и помогает
            достигать поставленных целей.
            У нас много общих интересов, мы часто проводим время вместе.
            С ним я становлюсь лучше и развиваюсь каждый день. У нас есть общие цели и мечты, и я уверена, что мы сможем
            достичь их вместе. Я благодарна ему за то, что он присутствует в моей жизни, за его заботу и поддержку. Я им
            безумно доружу </p>
          <div class="mt-6 flex max-w-md gap-x-4">
            <RouterLink
              class="flex-none rounded-md bg-indigo-500 px-3.5 py-2.5 text-sm font-semibold text-white shadow-sm hover:bg-indigo-400 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-500"
              to="/">Вернуться в главную 
            </RouterLink>
          </div>
        </div>
        <dl class="grid grid-cols-1 gap-x-8 gap-y-10 sm:grid-cols-2 lg:pt-2">
          <div class="flex flex-col items-start">
            <dt class="mt-4 font-semibold text-white">Факты </dt>
            <dd class="mt-2 leading-7 text-gray-400">Феде всего двадцать и <br> в свои 20 он добился высокого карьерного роста</dd>
          </div>
          <div class="flex flex-col items-start">
            <dt class="mt-4 font-semibold text-white">Так же</dt>
            <dd class="mt-2 leading-7 text-gray-400">Он работает в алиф банке в ккачестве front-end разработчка, он так же
              любит помогать людям, любит чувствовать себя полезным </dd>
          </div>
        </dl>
      </div>
    </div>
    <div class="absolute left-1/2 top-0 -z-10 -translate-x-1/2 blur-3xl xl:-top-6" aria-hidden="true">
      <div class="aspect-[1155/678] w-[72.1875rem] bg-gradient-to-tr from-[#ff80b5] to-[#9089fc] opacity-30"
        style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)" />
    </div>
  </div>
  <!-- HEADER-END -->

  <!-- MAIN-START  -->
  <div class="main-content ml-40 mt-10">
      <h2 class="font-bold text-5xl">Моя точка зрения о <br> нем и его <span class="">темпираменте</span>  </h2>
      <p class=" text-slate-600 mt-9 text-xl w-[80%]">Фирдавс Урунов Front-end разработчик выше я упомянала об этом любит заниматься созданием веб-сайтов, саморазвитием 
       и поэтому он постоянно обновляет свои знания и работая над своими навыками. Главная черта его характера-коммуникабельность он открытый веселый человек по типу темпирамента сангвинник самореализация чрезвычайно важна для него...   
      С самого детства родители приучили его к самостоятельности
    они никогда не стояли над ним, заставляя делать уроки, даже если что то не получалось он не бежал за помощью к своим родителям, старался все делать сам, это самоястоятельность воспитала его внутренней мир... </p>
  </div>
  <!-- INTERFACE -->
  <div class="bg-white  mt-[-100px] py-24 sm:py-32">
  <div class="mx-auto max-w-7xl px-6 lg:px-8">
    <div class="mx-auto max-w-2xl sm:text-center">
      <h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl"></h2>
      <p class="mt-6 text-lg leading-8 text-gray-600"></p>
    </div>
    <div class="mx-auto max-w-2xl rounded-3xl ring-1 ring-gray-200 sm:mt-20 lg:mx-0 lg:flex lg:max-w-none">
      <div class="p-8 sm:p-10 lg:flex-auto">
        <h3 class="text-2xl font-bold tracking-tight text-gray-900">Качества</h3>
        <p class="mt-6 text-base leading-7 text-gray-600">Lorem ipsum dolor sit amet consect etur adipisicing elit. Itaque amet indis perferendis blanditiis repellendus etur quidem assumenda.</p>
        <div class="mt-10 flex items-center gap-x-4">
          <h4 class="flex-none text-sm font-semibold leading-6 text-indigo-600">Lorem ipsum dolor sit amet consectetur adipisicing elit.</h4>
          <div class="h-px flex-auto bg-gray-100"></div>
        </div>
        <ul role="list" class="mt-8 grid grid-cols-1 gap-4 text-sm leading-6 text-gray-600 sm:grid-cols-2 sm:gap-6">
          <li class="flex gap-x-3">
            <svg class="h-6 w-5 flex-none text-indigo-600" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
              <path fill-rule="evenodd" d="M16.704 4.153a.75.75 0 01.143 1.052l-8 10.5a.75.75 0 01-1.127.075l-4.5-4.5a.75.75 0 011.06-1.06l3.894 3.893 7.48-9.817a.75.75 0 011.05-.143z" clip-rule="evenodd" />
            </svg>
            <RouterLink to="/about"></RouterLink>  
          </li>
          <li class="flex gap-x-3">
            <svg class="h-6 w-5 flex-none text-indigo-600" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
              <path fill-rule="evenodd" d="M16.704 4.153a.75.75 0 01.143 1.052l-8 10.5a.75.75 0 01-1.127.075l-4.5-4.5a.75.75 0 011.06-1.06l3.894 3.893 7.48-9.817a.75.75 0 011.05-.143z" clip-rule="evenodd" />
            </svg>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Expedita soluta architecto tenetur, libero necessitatibus adipisci cumque tempore nam dolorum non officiis nulla ducimus quas quia eius quisquam exercitationem neque minus.
          </li>
          <li class="flex gap-x-3">
            <svg class="h-6 w-5 flex-none text-indigo-600" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
              <path fill-rule="evenodd" d="M16.704 4.153a.75.75 0 01.143 1.052l-8 10.5a.75.75 0 01-1.127.075l-4.5-4.5a.75.75 0 011.06-1.06l3.894 3.893 7.48-9.817a.75.75 0 011.05-.143z" clip-rule="evenodd" />
            </svg>
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Culpa ullam officia earum consequatur odio velit nam aliquam distinctio molestiae saepe voluptate voluptatibus, adipisci modi, porro sit repellat esse quam dicta?
          </li>
          <li class="flex gap-x-3">
            <svg class="h-6 w-5 flex-none text-indigo-600" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
              <path fill-rule="evenodd" d="M16.704 4.153a.75.75 0 01.143 1.052l-8 10.5a.75.75 0 01-1.127.075l-4.5-4.5a.75.75 0 011.06-1.06l3.894 3.893 7.48-9.817a.75.75 0 011.05-.143z" clip-rule="evenodd" />
            </svg>
            Lorem, ipsum dolor.
          </li>
        </ul>
      </div>
      <div class="-mt-2 p-2 lg:mt-0 lg:w-full lg:max-w-md lg:flex-shrink-0">
        <div class="rounded-2xl bg-gray-50 py-10 text-center ring-1 ring-inset ring-gray-900/5 lg:flex lg:flex-col lg:justify-center lg:py-16">
          <div class="mx-auto max-w-xs px-8">
            <p class="text-base font-semibold text-gray-600">Помогает в любое время</p>
            <p class="mt-6 flex items-baseline justify-center gap-x-2">
              <span class="text-5xl font-bold tracking-tight text-gray-900">24/7</span>
              <span class="text-sm font-semibold leading-6 tracking-wide text-gray-600">в сети</span>
            </p>
            <a href="#" class="mt-10 block w-full rounded-md bg-indigo-600 px-3 py-2 text-center text-sm font-semibold text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600">Он молодец</a>
            <p class="mt-6 text-xs leading-5 text-gray-600">Lorem ipsum dolor sit amet.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
<!-- interface-end -->
<!--  -->

  
</template>



<style>
</style>
