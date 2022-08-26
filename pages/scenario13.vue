<!-- This example requires Tailwind CSS v2.0+ -->
<template>
  <div>
    <ScenarioPage :scenario="13" title="Importance of Online Privacy">
      <img src="~/assets/Scam13.jpg" />
    </ScenarioPage>

    <QuizTemplate
      link="/scenario14"
      question="which is NOT a way you can maintain your privacy online"
      :answers="[
        {
          text: `Use a VPN as another layer to your internet use`,
          value: `4`,
        },
        {
          text: `Install a browser plugin like Collusion to check how many companies are tracking you every day.`,
          value: `2`,
        },
        {
          text: `Close websites immediately after you are done to prevent them from tracking you`,
          value: `1`,
        },
        {
          text: `Turn off cookies ond stick to the regular font stack`,
          value: `3`,
        },
      ]"
    />
  </div>
</template>

<script setup></script>
