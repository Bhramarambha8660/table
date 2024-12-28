<template>
  <q-page class="bg-deep-purple-1" >

  <div class="row bg-primary">
    <div class="col ">
    <div style="max-width: 650px; margin-left: auto; margin-right: auto; text-align: center;">
  <div class="text-h4 text-bold text-white q-mt-xl q-pt-xl q-mb-lg"> Learn fullstack development from IT Experts</div>
  <div  class=" text-h6 text-white q-pl-lg q-pr-lg q-pb-sm">join the code expoert youtube channel to increase your coding skill</div>

  <q-input
        v-model="search"
        color="black"
        bg-color="white"
        filled
        placeholder="Your Email.."
        class="q-pl-lg q-pr-lg q-pb-lg"
      >
        <template v-slot:prepend>
          <q-icon name="email" />
        </template>

        <template v-slot:append>
          <q-btn color="purple">Start Learning</q-btn>
        </template>
      </q-input>
    </div>
  </div>

  <div class="col gt-sm">
  <q-img src="quasarlogo.png"
  style="margin-left: auto; margin-right: auto; display:block"
></q-img>
  </div>
</div>

<div class="row">
<div class="text-h5 text-bold q-px-md q-pt-sm">Latest Session</div>
</div>
<div class="row">
<div class="col col-12 col-md-4 col-sm-6">
  <div class="q-pa-md">
    <q-card class="my-card">
      <q-video src="https://www.youtube.com/embed/IlU-zDU6aQ0?rel=0" />

      <q-card-section>
        <div class="text-h6">Our Changing Planet</div>
        <div class="text-subtitle2">by John Doe</div>
      </q-card-section>

      <q-card-section class="q-pt-none">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
        eiusmod tempor incididunt ut labore et dolore magna aliqua.
      </q-card-section>
    </q-card>
  </div>
</div>


<div class="col col-12 col-md-4 col-sm-6">
  <div class="q-pa-md">
    <q-card class="my-card">
      <q-video src="https://www.youtube.com/embed/dQw4w9WgXcQ?rel=0" />

      <q-card-section>
        <div class="text-h6">Our Changing Planet</div>
        <div class="text-subtitle2">by John Doe</div>
      </q-card-section>

      <q-card-section class="q-pt-none">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
        eiusmod tempor incididunt ut labore et dolore magna aliqua.
      </q-card-section>
    </q-card>
  </div>
</div>



<div class="col col-12 col-md-4 col-sm-6">
  <div class="q-pa-md">
    <q-card class="my-card">
      <q-video src="https://www.youtube.com/embed/k3_tw44QsZQ?rel=0"  />

      <q-card-section>
        <div class="text-h6">Our Changing Planet</div>
        <div class="text-subtitle2">by John Doe</div>
      </q-card-section>

      <q-card-section class="q-pt-none">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
        eiusmod tempor incididunt ut labore et dolore magna aliqua.
      </q-card-section>
    </q-card>
  </div>
</div>


<div class="col col-12 col-md-4 col-sm-6">
  <div class="q-pa-md">
    <q-card class="my-card">
      <q-video src="https://www.youtube.com/embed/UAhRf3U50lM?rel=0"  />

      <q-card-section>
        <div class="text-h6">Our Changing Planet</div>
        <div class="text-subtitle2">by John Doe</div>
      </q-card-section>

      <q-card-section class="q-pt-none">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
        eiusmod tempor incididunt ut labore et dolore magna aliqua.
      </q-card-section>
    </q-card>
  </div>
</div>


<div class="col col-12 col-md-4 col-sm-6">
  <div class="q-pa-md">
    <q-card class="my-card">
      <q-video src="https://www.youtube.com/embed/mNBmG24djoY?rel=0"  />

      <q-card-section>
        <div class="text-h6">Our Changing Planet</div>
        <div class="text-subtitle2">by John Doe</div>
      </q-card-section>

      <q-card-section class="q-pt-none">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
        eiusmod tempor incididunt ut labore et dolore magna aliqua.
      </q-card-section>
    </q-card>
  </div>
</div>

<div class="col col-12 col-md-4 col-sm-6">
  <div class="q-pa-md">
    <q-card class="my-card">
      <q-video src="https://www.youtube.com/embed/IlU-zDU6aQ0?rel=0" />

      <q-card-section>
        <div class="text-h6">Our Changing Planet</div>
        <div class="text-subtitle2">by John Doe</div>
      </q-card-section>

      <q-card-section class="q-pt-none">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
        eiusmod tempor incididunt ut labore et dolore magna aliqua.
      </q-card-section>
    </q-card>
  </div>
</div>


</div>


<div class="row">
<div class="text-h5 text-bold q-pl-md">Featured Lession...</div>
</div>

<div class="row">
<div class="col-md col-12">
  <div class="q-pa-md">
    <q-card class="my-card">

    <div class="row">
    <div class="col-12 col-md-4 q-pa-md">
    <q-img src="card.jpg" />
    </div>
    <div class="col-12 col-md-8">
    <div class="text-h5 text-bold q-pl-md q-pt-sm text-purple" >Getting startted with quasar Fram work in vue JS</div>
    <div class="q-pa-md text-sm text-blue-grey-10 text-bold">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem excepturi nulla sit iure temporibus ex eos debitis ratione eligendi obcaecati optio facere vitae ad asperiores, alias provident delectus exercitationem. Nostrum.</div>
    </div>
    </div>

 
    </q-card>
  </div>
</div>
</div>
  
  </q-page>
</template>

<script setup>
//
</script>
