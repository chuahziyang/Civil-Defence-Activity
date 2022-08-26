<!-- This example requires Tailwind CSS v2.0+ -->
<template>
  <div>
    <ScenarioPage :scenario="7" title="How to pick the perfect password">
      <img src="~/assets/Scam7.jpg" />
    </ScenarioPage>
    <QuizTemplate
      link="/scenario8"
      question="Which of the following is a good password to use"
      :answers="[
        { text: `password123`, value: `2` },
        {
          text: `google99`,
          value: `2`,
        },
        { text: `1234567890`, value: `2` },
        { text: `x210CYer21`, value: `1` },
      ]"
    />
  </div>
</template>

<script setup></script>
