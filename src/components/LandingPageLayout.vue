<script setup lang="ts">
import UserDetailsForm from './UserDetailsForm.vue';
</script>

<template>

    <v-col>
        <v-row id="first-row">

            <v-col cols="5">
                <v-row class="position_relative">
                    <div id="discount_circle">
                        <div class="position_relative" id="discount_text">
                            <h2 class="font_size_250 white">$1.99 </h2>
                            <p class="white">Original value $500</p>
                        </div>
                    </div>
                    <img class="main_image center" src="../assets/first_row_main.png">
                </v-row>
                <v-row id="images_row center">
                    <v-col>
                        <img class=" row_image center" src="../assets/first_row_low_1.jpg">
                    </v-col>
                    <v-col>
                        <img class="row_image center" src="../assets/first_row_low_2.png">
                    </v-col>
                    <v-col>
                        <img class="row_image center" src="../assets/first_row_low_3.jpg">
                    </v-col>
                </v-row>

            </v-col>
            <v-col>
                <h1 class="font_size_450"> Chance to win a StockX <br> Mystery Box today! </h1> <br />
                <p class="font_size_150">Unleash the Excitement of Mystery Electronics </p>


                <UserDetailsForm />

            </v-col>




        </v-row>
        <v-row id="second_row">
            <div id="second_row_content">

                <h1 class="font_size_350">Top Tech Mystery Box <br>
                    at Unbeatable Prices</h1>

                <p id="second_row_text">Fast shipping | Easy returns | Special discounts for students</p>


            </div>


        </v-row>

        <v-row id="third_row">
            <v-col>
                <img id="third_row_img" width="95%" src="../assets//third_row_img.png" alt="">
            </v-col>
            <v-col class="center_vertically">
                <div id="third_row_text">
                    <h1 class="font_size_300">Curious about the <span class="green">StockX</span> <br>
                        Mystery
                        Box?</h1>
                    <p>Experience the thrill of unboxing cutting-edge gadgets with Stockx Mystery Boxes. Each box is a
                        treasure trove of high-quality electronics, handpicked to elevate your tech game</p>
                    <br>
                    <p>
                        Expect the unexpected! Our boxes are packed with the latest gadgets, from smartphones to gaming
                        consoles, ensuring you get the best tech surprises every time
                    </p>
                </div>

            </v-col>


        </v-row>

        <v-row id="third_row">

            <v-col class="center_vertically">
                <div id="fourth_row_text">
                    <h1 class="font_size_300">Why is everyone buzzing <br> about these boxes?</h1>
                    <p>StockX Mystery Boxes are not just about products; they’re about the experience. Imagine the
                        excitement of unveiling top-tier electronics at a fraction of the cost.</p>
                    <br>
                    <p>
                        Our boxes include a variety of premium tech items, making it a must-have for every tech
                        enthusiast. Join the buzz and see why everyone is raving about the unbeatable value and surprise
                        factor of Stockx Mystery Boxes!
                    </p>
                </div>

            </v-col>
            <v-col>
                <img id="fourth_row_img" width="95%" src="../assets/fourth_row_img.png" alt="">
            </v-col>

        </v-row>


    </v-col>



</template>

<style scoped>
#first_row {
    width: 100%;
    height: 80vh;
    justify-content: center;
}

#discount_circle {

    position: absolute;
    top: 10%;
    right: 5%;
    background-color: #006340;
    width: 160px;
    height: 160px;
    border-radius: 50%;

}

#discount_text {
    top: 20%;
    text-align: center;
}

.main_image {
    width: 90%;
    padding-bottom: 15px;
    padding-top: 50px;
}

#images_row {
    display: flex;
}

.row_image {
    display: block;
    width: 75%;
    border: 2px solid #000000;
    border-radius: 10px 10px 10px 10px;
}


#second_row {
    width: 100%;
    justify-content: center;
}

#second_row_content {
    text-align: center;
}

#second_row_text {
    color: #006340;
    font-size: x-large;
    font-weight: 500;
}

#third_row_img {
    border-radius: 50px;
    float: right;
}

#fourth_row_img {
    border-radius: 50px;
    float: left;
}

#third_row_text {
    width: 90%;
}

#fourth_row_text {
    height: 50%;
    padding-left: 50px;
}
</style>
