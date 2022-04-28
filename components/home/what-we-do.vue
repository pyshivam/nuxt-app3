<template>
  <section class="text-center mt-32" id="what-we-do">
    <div class="text-3xl font-bold my-6">What We Do</div>
    <div class="text-xl text-gray-800 mt-12">
      I help individuals & teams build their life and business system to
      increase their productivity.
    </div>
    <div class="mt-6">
      <div v-for="(val, i) in values" :key="val.title" class="p-6 text-left">
        <div><img :src="`assets/img/${val.img}`" alt="work" /></div>
        <div class="text-xl font-medium py-3">{{ val.title }}</div>
        <div class="text-gray-700 text-lg">{{ val.description }}</div>
        <div
          v-if="i !== values.length - 1"
          class="
            text-center
            py-3
            mt-10
            bg-black
            font-medium
            text-white
            rounded-md
          "
        >
          Get Started
        </div>
        <div v-else class="text-xl mt-10 text-gray-600">Book a call →</div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      values: [
        {
          title: "Workspace Setup",
          description:
            "Build or upgrade your Notion workspace for more organization and efficient workflows. ",
          img: "work.png",
        },
        {
          title: "Workspace Setup",
          description:
            "Build or upgrade your Notion workspace for more organization and efficient workflows. ",
          img: "work.png",
        },
        {
          title: "Lets Chat",
          description:
            "Any questions? Let’s hop on a quick call to learn more about how we can help you with Notion",
          img: "lets-chat.png",
        },
      ],
    };
  },
};
</script>