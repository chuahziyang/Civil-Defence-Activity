<!-- This example requires Tailwind CSS v2.0+ -->
<template>
  <div>
    <ScenarioPage :scenario="9" title="Fake Jobs scam">
      <h2 class="">
        You receive an unsolicited job offer via messaging apps, social media,
        etc. Very often, potential ‘employers’ will offer high pay with very
        little time commitment or effort. There are a number of different job
        scams. ‘Affiliate Marketing’ jobs where you are asked to pay for
        products in advance to boost the sales of sellers in return for
        commission. 'Agent' jobs require you to process fund transfers using
        your personal bank account, then transfer the money through online
        banking or money transfer services such as Western Union or MoneyGram.
        Applicants for jobs like 'Assistant Purchaser', 'Stock Takers' or 'Trial
        Participant' may be asked to reveal details like name, identity card
        number, phone security code or OTPs. This allows the scammers to access
        your mobile phone to make online purchases. 'Male Social Escort' jobs
        promise introductions to wealthy female clients, but only after you pay
        a registration fee. You may also be asked to pay additional fees such as
        insurance or membership.
      </h2>
      <img src="~/assets/Scam9.jpg" />
    </ScenarioPage>

    <QuizTemplate
      link="/scenario10"
      question="Is the above job offer likely to be legitimate?"
      :answers="[
        {
          text: `Legitimate`,
          value: `2`,
        },
        { text: `Illegitimate`, value: `1` },
      ]"
    />
  </div>
</template>

<script setup></script>
