<!-- This example requires Tailwind CSS v2.0+ -->
<template>
  <div>
    <ScenarioPage
      :scenario="8"
      title="How to prevent malicous software on personal devices"
    >
      <img src="~/assets/Scam8.png" />
    </ScenarioPage>
    <QuizTemplate
      link="/scenario9"
      question="Which of the following could potentially be dangerous"
      :answers="[
        { text: `Downloading suspicious software on the internet`, value: `2` },
        {
          text: `Having your anti-virus/windows defender turned off`,
          value: `3`,
        },
        {
          text: `Not having your devices updated to the latest security patch`,
          value: `4`,
        },
        { text: `All of the above`, value: `1` },
      ]"
    />
  </div>
</template>

<script setup></script>
