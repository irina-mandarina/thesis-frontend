<!-- <script setup>
  import GAuth from 'vue3-google-oauth2'
  import { createApp } from 'vue'
  const app = createApp(App)

  const gAuthOptions = { clientId: '1045612066490-onub3orv8hplavb7e873m4d8nedpej5o.apps.googleusercontent.com', scope: 'email', prompt: 'consent', fetch_basic_profile: false }
  app.use(GAuth, gAuthOptions)
</script> -->
<template>
  <Head>
    <Link rel="stylesheet" type="text/css" href="//fonts.googleapis.com/css?family=Heebo" />
    <Link rel="stylesheet" type="text/css" href="//fonts.googleapis.com/css?family=Metrophobic" />
    <Link rel="stylesheet" type="text/css" href="//fonts.googleapis.com/css?family=Droid+Serif" />
    <Link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css" />
  </Head>
  <NuxtPage />
</template>
<style>
  :root {
    --brown: #502419;
    --asparagus: #7EA172;
    --khaki: #C7CB85;
    --fawn: #E7A977;
    --peach: #EBBE9B;
    --phtalo: #14342B;
    --dark-blue: #06032b;
  }

  body {
    color: var(--dark-blue)
  }

  body:focus {
    outline: none;
  }

  .bg-peach {
    background-color: var(--peach);
  }

  .bg-fawn {
    background-color: var(--fawn);
  }

  .bg-brown {
    background-color: var(--brown);
  }

  .bg-asparagus {
    background-color: var(--asparagus);
  }

  .bg-pthalo {
    background-color: var(--pthalo);
  }

  .bg-khaki {
    background-color: var(--khaki);
  }

  .text-brown {
    color: var(--brown);
  }
  
  .text-peach {
    color: var(--peach);
  }

  .text-fawn {
    color: var(--fawn);
  }

  .text-khaki {
    color: var(--khaki);
  }
  
  .text-asparagus {
    color: var(--asparagus);
  }
  
  .text-phtalo {
    color: var(--phtalo);
  }

  .border-phtalo {
    border-color: var(--phtalo);
  }

  .border-peach {
    border-color: var(--peach);
  }
  
  .border-asparagus {
    border-color: var(--asparagus);
  }

  .border-khaki {
    border-color: var(--khaki);
  }

  .border-dark-blue {
    border-color: var(--dark-blue);
  }

  .font-heebo {
    font-family: Heebo;
  }
  
  .font-droid {
    font-family: 'Droid Serif';
    font-weight: 300;
  }
  
  .font-metrophobic {
    font-family: Metrophobic;
    font-weight: light;
  }

  body {
    font-family: Metrophobic;
  }

  .font-oblique {
    font-style: oblique;
  }
</style>
