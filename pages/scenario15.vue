<!-- This example requires Tailwind CSS v2.0+ -->
<template>
  <div>
    <ScenarioPage :scenario="15" title="Avoiding identity theft">
      <img src="~/assets/Scam15.png" />
    </ScenarioPage>

    <QuizTemplate
      link="/endpage"
      question="What should you do if you suspect you are a victim of identity theft?"
      :answers="[
        {
          text: `There is no need to do anything`,
          value: `2`,
        },
        {
          text: `Report the incident to the police`,
          value: `1`,
        },
        {
          text: `Loosen the security settings of your account`,
          value: `3`,
        },
        {
          text: `None of the above`,
          value: `4`,
        },
      ]"
    />
  </div>
</template>

<script setup></script>
