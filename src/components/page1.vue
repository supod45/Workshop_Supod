<template>
  <div>

    <h1>{{ text }}</h1>
    <p class="subheading font-weight-regular">
           <v-icon>mdi mdi-email</v-icon> Email : Supod.j@ku.th
        <br/><v-icon>mdi mdi-phone-in-talk</v-icon>Phone : 0631583714
        <br />มหาวิทยาลัยเกษตรศาสตร์ วิทยาเขตศรีราชา
    </p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      text: "Contact",
    };
  },
};
</script>