<!-- This example requires Tailwind CSS v2.0+ -->
<template>
  <div>
    <ScenarioPage :scenario="10" title="Dangers of public wifi">
      <img src="~/assets/Scam10.jpg" />
    </ScenarioPage>

    <QuizTemplate
      link="/scenario11"
      question="What are NOT some steps you can take to be safe when connected to public wifi"
      :answers="[
        {
          text: `Check that every website you connect to has https(lock icon) `,
          value: `2`,
        },
        {
          text: `Check banking info quickly so people cannot steal your info`,
          value: `1`,
        },
        {
          text: `Leave your firewall on when connected to public wifi`,
          value: `3`,
        },
        {
          text: `User a VPN so public wifi cannot track the websites you visit`,
          value: `4`,
        },
      ]"
    />
  </div>
</template>

<script setup></script>
