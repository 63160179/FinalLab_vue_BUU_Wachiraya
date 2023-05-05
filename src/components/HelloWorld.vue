<template>
   <v-container>
      <v-row class="text-center">
         <v-col cols="12">            
            <img
               src="../assets/logo1.jpg"
               class="my-3"
               contain
               height="200"
            />
         </v-col>

         <v-col class="mb-4">
            <h1 class="text-h3 font-weight-bold mb-3"> My Portfolio</h1>

            <p class="subheading font-weight-regular">
               ชื่อ นางสาววชิรญาณ์ วงศ์สมบูรณ์
               <br />อายุ 20
               <br />วันเกิด 30/05/2545
               <br />
               
               
            </p>
         </v-col>
      </v-row>
   </v-container>
</template>

<script>
export default {
   name: 'HelloWorld',

   data: () => ({
      
   })
}
</script>