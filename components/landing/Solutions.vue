<template>
    <div class="bg-[url('~/assets/img/solutionsimg.jpg')] bg-black bg-opacity-75 bg-cover bg-center bg-blend-darken h-[700px] relative">
      <div class="absolute inset-0 opacity-50"></div>
      <main class="absolute inset-0 p-4 md:p-24 flex flex-col justify-center text-white">
        <div class="gap-20 mx-auto md:flex md:justify-between">
          <!-- Left Div -->
          <div class="md:text-left mb-8 md:mb-0 md:w-1/2 md:block">
            <h6 class="text-red-600">Why Choose Us</h6>
            <span class="text-red-600">&rarr;</span>
            <h1 class="text-3xl md:text-3xl lg:text-4xl xl:text-5xl font-bold l:tracking-normal">
              Elevated Design <wbr/><span class="text-red-600 md:inline">Solutions</span>
            </h1>

            <div class="grid sm:grid-cols-1 md:grid-cols-1 mt-16 gap-16">
                <div v-for="item of solution" :key="item.solution" class="flex gap-4 items-start">
                    <div class="mt-1 bg-red-600 rounded-full p-2 w-8 h-8 shrink-0">
                        <Icon class="text-white" :name="item.icon" />
                    </div>
                    <div>
                        <h2 class="font-bold text-lg">{{ item.title }}</h2>
                        <p class="text-slate-500 mt-2 leading-relaxed pb-3">
                            {{ item.description }}
                        </p>
                        <hr>
                    </div>
                </div>
            </div>
          </div>

          <!-- Right Div -->
          <div class="md:w-1/2 relative hidden md:block">
            <img src="@/assets/img/solutionsimgone.jpg" class="absolute top-28 left-0 w-full h-auto" alt="First Image">
            <img src="@/assets/img/solutionsimgthree.jpg" class="absolute bottom-24 left-20 w-full h-auto" alt="Second Image">
          </div>
        </div>
      </main>
    </div>
  </template>

<script setup>
const solution = [
{
    title: "Professional Engineers & Designers",
    description:
      "Proin efficitur, mauris vel condimentum pulvinar, velit orci consectetur ligula, eget egestas magna mi ut arcu.",
    icon: "bx:bx-check",
  },
  {
    title: "428+ Successfully Projects",
    description:
      "Proin efficitur, mauris vel condimentum pulvinar, velit orci consectetur ligula, eget egestas magna mi ut arcu.",
    icon: "bx:bx-check",
  },
]
</script>
  