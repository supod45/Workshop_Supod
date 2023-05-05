<template>
   <v-container>
      <v-row class="text-center">
         <v-col cols="12">            
            <img
               src="../assets/9k.png"
               class="my-3"
               contain
               height="200"
            />
         </v-col>

         <v-col class="mb-4">
            <h1 class="text-h3 font-weight-bold mb-3">Welcome to Profile</h1>
            <v-icon>mdi mdi-face-man-shimmer</v-icon>
            <p class="subheading font-weight-regular">
            Name : นาย สุพจน์ จันทร์อ่อน
         <br />NickName : เอ(A)
         <br />Age : 21
         <br />Hobby : เล่นเกม อ่านการ์ตูน
         <br />*---------------------------------------*
            </p>
         </v-col>
      </v-row>
   </v-container>
</template>

<script>
export default {
   name: 'HelloWorld',
     props: {
    msg: String,
  },
   data: () => ({
      
   })
}
</script>
