<!-- This example requires Tailwind CSS v2.0+ -->
<template>
  <div>
    <ScenarioPage :scenario="3" title="Tech Support Scams">
      <img src="~/assets/Scam3.png" />
      <h2>
        Anyone who believes they have fallen prey to such scams should take
        these immediate steps: Uninstall any software that you have installed at
        the instructions of the scammers. Log off and turn off your computer to
        limit any further activities that the scammers can execute. Report the
        incident to your bank to halt further activities relating to your bank
        accounts. Change your Internet banking credentials and remove any
        unauthorised payees who may have been added to your bank accounts.
        Report the matter to the police.
      </h2>
    </ScenarioPage>
    <QuizTemplate
      link="/scenario4"
      question="What are some indicators of a tech support scam?"
      :answers="[
        {
          text: `Caller asks you to download remote access software`,
          value: `1`,
        },
        {
          text: `You call the caller at their official number found on their website`,
          value: `2`,
        },
        {
          text: `Caller refers you to official resources, such as official microsoft help resources`,
          value: `2`,
        },
        { text: `All of the above`, value: `2` },
      ]"
    />
  </div>
</template>

<script setup></script>
