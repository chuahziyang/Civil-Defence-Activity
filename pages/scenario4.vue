<!-- This example requires Tailwind CSS v2.0+ -->
<template>
  <div>
    <ScenarioPage
      :scenario="4"
      title="Beware of Phishing Scams"
      nextlink="/scenario5"
    >
      <img src="~/assets/Scam4.png" />
      <h2>
        <br />The police has advised the public to observe these crime
        prevention measures: <br />Do not click on dubious URL links provided in
        unsolicited text messages. Banks do not send SMSes containing links

        <br />Always verify the authenticity of claims of problems with your
        bank account or cards issued by the bank with the official bank website
        or sources

        <br />Never disclose your personal or Internet banking details and OTPs
        to anyone

        <br />Report any fraudulent transactions to your bank immediately "Bank
        officers will never ask for your banking details or OTPs over the phone
        or by SMS," SPF said.
      </h2>
    </ScenarioPage>
    <QuizTemplate
      link="/scenario5"
      question="Which of the following is NOT a phishing link"
      :answers="[
        {
          text: `https://accounts.google.com/o/oauth2/v2/auth`,
          value: `1`,
        },
        {
          text: `https://google.authenticathor.com/login.html`,
          value: `2`,
        },
        { text: `https://m-facebook-profile.item4324853.com`, value: `2` },
        { text: `https://secure.runescape.com-as.ru`, value: `2` },
      ]"
    />
  </div>
</template>

<script setup></script>
