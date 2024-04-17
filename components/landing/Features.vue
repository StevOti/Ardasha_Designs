<script setup>
const features = [
  {
    title: "01. Branding",
    description:
      "Get valuable insights and personalized recommendations every step of the way from design and bra.",
    icon: "bx:bxs-briefcase",
  },
  {
    title: "02. Service Design",
    description:
      "Get valuable insights and personalized recommendations every step of the way from design.",
    icon: "bx:bxs-window-alt",
  },
  {
    title: "03. UI /UX Design",
    description:
      "Get valuable insights and personalized recommendations every step of the way from design and bra.",
    icon: "bx:bxs-data",
  },
  {
    title: "04. Web Development",
    description:
      "Get valuable insights and personalized recommendations every step of the way from design and bra.",
    icon: "bx:bxs-bot",
  },
  {
    title: "05. Content  & Copy Writing",
    description:
      "Get valuable insights and personalized recommendations every step of the way from design and bra.",
    icon: "bx:bxs-file-find",
  },
  {
    title: "06. Digital Strategy & Planning ",
    description:
      "Get valuable insights and personalized recommendations every step of the way from design and bra.",
    icon: "bx:bxs-user",
  },
];
</script>

<template>
  <div class="mt-16 md:mt-0">
    <h2 class="text-4xl lg:text-5xl font-bold lg:tracking-tight">
      We Provide Modern Business Design <span class="text-red-600">Solutions</span>
    </h2>
    
  </div>

  <div class="grid sm:grid-cols-2 md:grid-cols-2 mt-16 gap-16">
    <div v-for="item of features" :key="item.features" class="flex gap-4 items-start">
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
</template>
