<template>
  <div class="bg-white">
    <div
      class="max-w-2xl mx-auto py-24 px-4 grid items-center grid-cols-1 gap-y-16 gap-x-8 sm:px-6 sm:py-32 lg:max-w-7xl lg:px-8 lg:grid-cols-2"
    >
      <div>
        <h2
          class="text-3xl font-extrabold tracking-tight text-gray-900 sm:text-4xl"
        >
          3TPT Digital Defence Activity
        </h2>
        <p class="mt-4 text-xl text-gray-500">
          This activity consists of 4 parts:
        </p>

        <dl
          class="mt-4 grid grid-cols-1 gap-x-6 gap-y-10 sm:grid-cols-2 sm:gap-y-16 lg:gap-x-8"
        >
          <div
            v-for="feature in features"
            :key="feature.name"
            class="border-t border-gray-200 pt-4"
          >
            <dt class="font-medium text-gray-900">{{ feature.name }}</dt>
            <dd class="mt-2 text-sm text-gray-500">
              {{ feature.description }}
            </dd>
          </div>
          <a href="/login"
            ><button
              class="bg-blue-700 hover:bg-blue-900 text-white font-bold py-2 px-4 rounded"
            >
              Begin
            </button></a
          >
        </dl>
      </div>
    </div>
  </div>
</template>

<script setup>
const features = [
  {
    name: "Sign-up Page",
    description:
      "You will be taken to a mock signup page. You may enter any username/email/password. The system will make recommendations based on your input!",
  },
  {
    name: "Quiz/Informative Pages",
    description:
      "Each page will have an infographic and a quiz for you to test your knowledge! You may only move to next infographic once you have answered the quiz correctly!",
  },
  {
    name: "End-Page",
    description:
      "This page compiles various cyber security resources that you can check out to get more info!",
  },
  {
    name: "Feedback",
    description:
      "Do give the NSFC Team feedback so we can improve these activities in the future!",
  },
];
</script>
