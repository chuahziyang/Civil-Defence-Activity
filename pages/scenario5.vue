<!-- This example requires Tailwind CSS v2.0+ -->
<template>
  <div>
    <ScenarioPage :scenario="5" title="Beware of Love Scams">
      <img src="~/assets/Scam6.png" />
      <h2>
        After befriending an attractive person (who is usually foreign) online,
        he or she tells a tale about falling into trouble or hard times. The
        scammer persists with the story to gain their victim's trust and
        adoration, then asks for money as proof of love. Once the money is
        transferred, the scammer disappears. What You Should Look Out For:
        <br />- Professes their undying love very quickly after making contact
        with you <br />- Goes to great lengths to gain your interest and trust
        with loving words and even offers to send you gifts <br />- Gives
        excuses whenever you ask for a video call What You Should Do: <br />- Do
        not send money to anyone you have not met in person <br />- Verify the
        identity of the person you are talking to with an online image search,
        here: https://images.google.com/ <br />- Always ask for a LIVE video
        call with the person It’s not wrong to chat with strangers online. But
        in today’s overly-connected digital world, you have to take what people
        say online with a grain of salt. And don’t perform any money transaction
        to people that you don’t know personally. Use the REPORT button on
        social media when you see any suspicious behaviour online. This will
        notify the website admin of the scammer’s profile. Then, use the BLOCK
        button so the scammers won’t be able to contact you ever again. If you
        find yourself caught in a love scam, tell your family and make a police
        report.
      </h2>
    </ScenarioPage>
    <QuizTemplate
      link="/scenario6"
      question="What is NOT a sign that you are dealing with a love scam"
      :answers="[
        {
          text: `Person is a trusted mutual friend, whom you have met in person`,
          value: `1`,
        },
        {
          text: `Person asks you to wire money, especially in the form of a gift card`,
          value: `2`,
        },
        {
          text: `Person makes advances quickly, aka 'love-bombing' you.`,
          value: `3`,
        },
        {
          text: `Person refuses to verify his identity, either by meeting up, or by refusing to video chat.`,
          value: `4`,
        },
      ]"
    />
  </div>
</template>

<script setup></script>
