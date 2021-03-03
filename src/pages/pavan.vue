<template>
<div>
    <h1 class="a">Hello From pavan</h1>
    <div class="q-pa-md q-gutter-sm">
    <q-banner dense class="bg-primary text-white">
      Unfortunately, the credit card did not go through, please try again.
      <template v-slot:action>
        <q-btn flat color="white" label="Dismiss" />
        <q-btn flat color="white" label="Update Credit Card" />
      </template>
    </q-banner>

    <q-banner dense class="bg-grey-3">
      <template v-slot:avatar>
        <q-icon name="signal_wifi_off" color="primary" />
      </template>
      You have lost connection to the internet. This app is offline.
      <template v-slot:action>
        <q-btn flat color="primary" label="Turn on Wifi" />
      </template>
    </q-banner>

    <q-banner dense inline-actions class="text-white bg-red">
      You have lost connection to the internet. This app is offline.
      <template v-slot:action>
        <q-btn flat color="white" label="Turn ON Wifi" />
      </template>
    </q-banner>
  </div>
  <div class="q-pa-md q-gutter-md">
    <div>
      <q-chip icon="event">Add to calendar</q-chip>
      <q-chip icon="bookmark">Bookmark</q-chip>
      <q-chip icon="alarm" label="Set alarm" />
      <q-chip class="glossy" icon="directions">Get directions</q-chip>
    </div>
    <div>
      <q-chip color="primary" text-color="white" icon="event">
        Add to calendar
      </q-chip>
      <q-chip color="teal" text-color="white" icon="bookmark">
        Bookmark
      </q-chip>
      <q-chip class="glossy" color="orange" text-color="white" icon-right="star">
        Star
      </q-chip>
      <q-chip color="red" text-color="white" icon="alarm" label="Set alarm" />
      <q-chip color="deep-orange" text-color="white" icon="directions">
        Get directions
      </q-chip>
      <q-chip>
        <q-avatar icon="bookmark" color="red" text-color="white" />
        Bookmark
      </q-chip>
      <q-chip>
        <q-avatar color="red" text-color="black">30</q-avatar>
        Emails
      </q-chip>
      <q-chip>
        
        pavan
      </q-chip>
    </div>
  </div>
   <div class="q-pa-md q-gutter-sm">
    <q-avatar color="red" text-color="white" icon="directions" />
    <q-avatar color="primary" text-color="white">J</q-avatar>
    <q-avatar size="100px" font-size="52px" color="teal" text-color="white" icon="directions" />
    <q-avatar size="24px" color="orange">J</q-avatar>
    <q-avatar>
      <img src="https://cdn.quasar.dev/img/avatar.png">
    </q-avatar>
  </div>
</div>
  
</template>

<script>
export default {

}
</script>

<style scoped>
.a{
    color: rgb(32, 75, 167);
    text-decoration-style: dotted;
}

</style>