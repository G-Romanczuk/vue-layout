<script setup lang="ts">
import UserDetailsForm from './UserDetailsForm.vue';
</script>

<template>

    <v-col cols="12">
        <v-row id="first-row">

            <v-col cols="5">
                <v-row>
                    <img class="main_image" src="../assets/first_row_main.png">


                </v-row>
                <v-row id="images_row">
                    <v-col>
                        <img class=" row_image" src="../assets/first_row_low_1.jpg">
                    </v-col>
                    <v-col>
                        <img class="row_image" src="../assets/first_row_low_2.png">
                    </v-col>
                    <v-col>
                        <img class="row_image" src="../assets/first_row_low_3.jpg">
                    </v-col>
                </v-row>

            </v-col>
            <v-col>
                <v-row>
                    <h1> Chance to win a StockX Mystery Box today! </h1> <br />
                    <h3>Unleash the Excitement of Mystery Electronics </h3>


                </v-row>
                <v-row>
                    <UserDetailsForm />
                </v-row>
            </v-col>




        </v-row>
        <v-row id="second_row">
            <div id="second_row_content">

                <h1>Top Tech Mystery Box <br>
                    at Unbeatable Prices</h1>

                <h3>Fast shipping | Easy returns | Special discounts for students</h3>


            </div>


        </v-row>





    </v-col>




</template>

<style scoped>
#main_layout {
    width: 90vw;

}

#first_row {
    width: 100%;
    height: 80vh;
    justify-content: center;
}

.main_image {
    width: 90%;
    margin: auto;
    padding-bottom: 15px;
}

#images_row {
    margin: auto;
    display: flex;
}

.row_image {
    display: block;
    width: 75%;
    border: 2px solid #000000;
    border-radius: 10px 10px 10px 10px;
    margin: auto;
}

h1 {
    font-size: 450%;
}

h3 {
    font-size: 150%;
    font-weight: 100;
}

#second_row {
    width: 100%;
    height: 20vh;
    justify-content: center;
}

#second_row_content {
    text-align: center;
}
</style>
