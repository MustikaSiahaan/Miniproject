<template>
<div>
    <v-container>
        <v-row align="center" justify="center">
            <v-col lg="4">
                <v-form>
                    <h3 align="center">Order Form</h3>
                    <v-text-field label="Name"></v-text-field>
                    <v-text-field label="Phone"></v-text-field>
                    <v-text-field label="Product"></v-text-field>
                    <v-textarea label="Message"></v-textarea>
                    <v-btn color="success" @click="submit">Order</v-btn>
                </v-form>
                
            </v-col>
        </v-row>
    </v-container>
    
</div>

</template>

<script>
export default{
    name: "OrderResult",
    data: () => ({
    product: [
      'Maincourse',
      'Salad',
      'Smoothies',
    ],
    })
}
</script>

<style scoped>
    div{
        margin-top: 20px;

   }
  
</style>