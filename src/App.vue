<script setup>
import { CheckCircleIcon } from '@heroicons/vue/24/solid'
import { ClockIcon, ListBulletIcon, ChartBarIcon } from '@heroicons/vue/24/outline'
</script>

<template>
  <header class="sticky top-0 z-20 flex items-center justify-between border-b bg-white p-3">
    <a href="#">
      <img src="./assets/logo.png" alt="logo" class="h-9" />
    </a>
    <a href="#" class="text-sm">
      <div v-if="true" class="flex items-center gap-1">
        Day complete!

        <CheckCircleIcon class="h-7 text-green-500" />
      </div>
      <div v-else class="flex items-center gap-1">
        <div>Progress:<span class="font-mono">20%</span></div>
        <div class="h-3 w-3 rounded-full bg-red-500"></div>
      </div>
    </a>
  </header>

  <main class="flex flex-col grow">
    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Animi a optio laudantium commodi quo
    sit deserunt, possimus quibusdam, ipsa incidunt fuga, voluptatem ullam at qui. Id officiis culpa
    corporis quod. Blanditiis vel impedit libero et corporis quae dolorem pariatur magni ducimus,
    consequuntur quos sunt fugit similique iure perspiciatis voluptates. Aut deserunt perferendis
    deleniti. Voluptatum, soluta cum minima delectus obcaecati eveniet. Error numquam tempora
    pariatur laboriosam quos blanditiis nesciunt veniam esse rem architecto ipsa provident id
    expedita, soluta sequi a voluptate, eveniet consequuntur! Perspiciatis doloribus quasi soluta
    architecto dolore itaque sed! Placeat modi earum deserunt doloremque omnis. Eius nobis modi enim
    quam. Fugiat animi reprehenderit reiciendis natus velit quam magni? Perspiciatis hic ipsum ea
    inventore, vitae a aliquam est voluptatem asperiores! Quisquam sit aliquam dicta assumenda vero
    necessitatibus, doloribus sunt eaque et corrupti placeat rerum enim quasi quas dolore quae
    maiores, libero eum iure, fuga optio debitis explicabo? Corrupti, illum quod. Architecto minima
    totam aliquid quibusdam, non velit dolorem obcaecati labore modi, reprehenderit hic corrupti?
    Tenetur corrupti, possimus consequatur assumenda reiciendis doloremque impedit id dicta optio
    facere illo officiis mollitia hic? Sapiente in eveniet eos explicabo impedit. Enim culpa rem
    vitae, quibusdam assumenda in aspernatur quam veniam id tempore voluptatibus libero velit
    explicabo voluptas nesciunt odio non quisquam totam cupiditate minima. Quod animi asperiores
    quisquam voluptatum quis accusantium exercitationem consequatur fugit pariatur expedita earum
    nostrum, illum at dolores eum iusto dolor, vel labore? Doloribus tempore nostrum eveniet in
    necessitatibus voluptate suscipit. Fugit sed, quas accusantium, explicabo excepturi iure sunt
    unde alias aut quibusdam maiores, voluptatibus sit! Perspiciatis asperiores dicta aliquam culpa
    ratione nam ut sunt tempore ea dolore, autem labore obcaecati! Nihil commodi voluptate quisquam
    fuga minima iste quidem doloribus quis. Commodi laboriosam sequi labore quos possimus eveniet
    facilis, molestias quia exercitationem officiis laborum omnis! Magni illum debitis suscipit
    pariatur veritatis. Autem exercitationem omnis vero nam rerum? Quasi, eligendi? Odio rem ab
    doloremque labore? Magni, nemo ipsa! Consequuntur tempora distinctio, esse cumque ipsum veniam
    nobis iste magnam odio corrupti, sit ipsa! Sit voluptas voluptates cupiditate laborum nisi ab
    blanditiis quidem aperiam. Distinctio minus suscipit, nostrum nobis repudiandae velit vero
    obcaecati autem eum a praesentium eos voluptatum harum aperiam facere sint enim! Eius cum ipsam
    aliquid doloribus esse eos quam deserunt suscipit odio iusto tenetur dolore, consequatur magnam
    magni obcaecati voluptates corrupti deleniti rerum omnis aliquam. Aspernatur, quibusdam? Earum
    facilis ipsam debitis. Ipsam iste quod vitae odit incidunt, numquam esse hic aspernatur
    architecto error est. Ratione non, consequuntur eum eius corporis saepe! Cum error quisquam
    fugit nulla deleniti! Consequatur dicta laudantium facilis? Explicabo iste reiciendis quisquam
    quos aperiam quia incidunt possimus quibusdam ratione, sit temporibus praesentium perspiciatis
    vel, dolor rerum veritatis sapiente officiis id similique saepe eum error! Atque iure ipsum
    fugit! Corrupti est cupiditate laboriosam nostrum temporibus, quae eaque, non deleniti
    reprehenderit numquam libero sunt aliquid fugit unde. Molestiae laudantium asperiores, itaque
    aliquid ducimus ab, similique iusto, nemo possimus nesciunt ipsum! Explicabo inventore impedit
    distinctio in consequatur labore, praesentium alias et ab iste laboriosam nostrum ipsum officia
    totam sapiente! Officiis tempore facilis doloremque fuga ea eum eveniet nobis impedit
    dignissimos consequuntur? Tenetur animi dolore est quis qui perferendis. Voluptates quasi
    corrupti beatae fuga perspiciatis, ea aperiam minima corporis consequatur optio animi ex in
    consequuntur vel quidem. Possimus culpa corrupti tempore beatae? Quasi voluptatibus quod
    repudiandae incidunt! Blanditiis autem repudiandae delectus ipsa temporibus ad nemo, sequi modi
    aliquid ipsum quasi vel? Magnam quasi eaque praesentium odit laudantium vitae? Dolore corporis
    accusantium odio? Consectetur obcaecati quidem iusto repellendus! Dolore quo provident nesciunt,
    nostrum dolores eos adipisci nisi consequuntur eius, voluptates excepturi, dicta voluptatum
    possimus voluptate impedit et. Tempore quisquam commodi dignissimos quis dolorem.
  </main>
  <nav class="sticky bottom-0 z-20 bg-white border-t">
    <ul class="flex items-center justify-around">
      <li class="flex-1">
        <a class="flex flex-col p-2 text-xs capitalize" href="#timeline">
          <ClockIcon class="h-6 w-6" />
          Time line
        </a>
      </li>
      <li class="flex-1">
        <a class="flex flex-col p-2 text-xs capitalize" href="#activities">
          <ListBulletIcon class="h-6 w-6" />
          Activities
        </a>
      </li>
      <li class="flex-1">
        <a class="flex flex-col p-2 text-xs capitalize" href="#progress">
          <ChartBarIcon class="h-6 w-6" />
          Progress
        </a>
      </li>
    </ul>
  </nav>
</template>

<style scoped></style>
