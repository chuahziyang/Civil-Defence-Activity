<!-- This example requires Tailwind CSS v2.0+ -->
<template>
  <div>
    <ScenarioPage
      :scenario="1"
      title="Stranger Messages you with a suspicious link:"
    >
      <img src="~/assets/Scam1.jpg" />
      <h2>
        Social Media Impersonation Scams Scammers would usually ask the victims
        for their personal details such as their mobile number, Internet banking
        account details and One-Time Password (OTP) on the pretext of helping
        them to sign up for fake contests or promotions allegedly organised by
        Lazada, Shopee and Qoo10. Victims would later discover that fraudulent
        transactions had been made from their bank accounts and mobile wallets
        without their consent. Never share your Internet banking account details
        and OTPs with anybody – legitimate contests or promotions will never ask
        for such details. Your OTP is like your ATM pin, do not reveal it to
        anyone.
      </h2>
    </ScenarioPage>
    <QuizTemplate
      link="/scenario2"
      question="What is an indicator that a message
      
    is malicous"
      :answers="[
        { text: `Message is coming from an unknown number`, value: `2` },
        {
          text: `Message asks for personal details such as name, banking details, OTPs `,
          value: `2`,
        },
        { text: `Message is unexpected`, value: `2` },
        { text: `All of the above`, value: `1` },
      ]"
    />
  </div>
</template>

<script setup></script>
