<!-- This example requires Tailwind CSS v2.0+ -->
<template>
  <div>
    <ScenarioPage :scenario="14" title="Cypto Investment Scams">
      <img src="~/assets/Scam14.png" />
      <h2>
        Investment scams involve promises of big payouts, quick money or
        guaranteed returns. Always be suspicious of any investment opportunities
        that promise a high return with little or no risk – if it seems too good
        to be true, it probably is – and is highly likely to be a scam.
      </h2>
    </ScenarioPage>

    <QuizTemplate
      link="/scenario15"
      question="What are some signs that a crypto scam is taking place?"
      :answers="[
        {
          text: `Unsustainably high returns`,
          value: `4`,
        },
        {
          text: `Typographical errors and obvious misspellings in emails, on social media posts, or in any marketing/promotional materials `,
          value: `3`,
        },
        {
          text: `Promises of free money, or the 'next big project' `,
          value: `2`,
        },
        {
          text: `All of the above`,
          value: `1`,
        },
      ]"
    />
  </div>
</template>

<script setup></script>
