<!-- This example requires Tailwind CSS v2.0+ -->
<template>
  <div>
    <ScenarioPage :scenario="12" title="Importance of 2 factor Authentication">
      <img src="~/assets/Scam12.jpg" />
      <h2>
        Two-factor authentication (2FA), sometimes referred to as two-step
        verification or dual-factor authentication, is a security process in
        which users provide two different authentication factors to verify
        themselves. 2FA is implemented to better protect both a user's
        credentials and the resources the user can access. Two-factor
        authentication provides a higher level of security than authentication
        methods that depend on single-factor authentication (SFA), in which the
        user provides only one factor -- typically, a password or passcode.
        Two-factor authentication methods rely on a user providing a password as
        the first factor and a second, different factor -- usually either a
        security token or a biometric factor, such as a fingerprint or facial
        scan. Two-factor authentication adds an additional layer of security to
        the authentication process by making it harder for attackers to gain
        access to a person's devices or online accounts because, even if the
        victim's password is hacked, a password alone is not enough to pass the
        authentication check.
      </h2>
    </ScenarioPage>

    <QuizTemplate
      link="/scenario13"
      question="Which of the following is true about 2FA?"
      :answers="[
        {
          text: `You should use 2FA whenever possible especially for important accounts such as your google or bank account`,
          value: `1`,
        },
        {
          text: `2FA is not an effective security measure to safe-keep your account`,
          value: `2`,
        },
        {
          text: `2FA refers to only using a single method to verify someone's identity`,
          value: `3`,
        },
        {
          text: `All of the above`,
          value: `4`,
        },
      ]"
    />
  </div>
</template>

<script setup></script>
