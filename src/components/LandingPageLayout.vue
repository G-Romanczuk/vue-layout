<script setup lang="ts">
import UserDetailsForm from './UserDetailsForm.vue';
</script>

<template>

    <v-col>
        <v-row id="first-row">

            <v-col cols="5" style="padding-top: 50px;">
                <v-row style="position: relative;">
                    <div id="discount_circle">
                        <div id="discount_text">
                            <h2>$1.99 </h2>
                            <h4>Original value $500</h4>
                        </div>
                    </div>
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

                <h1 style="font-size: 350%;">Top Tech Mystery Box <br>
                    at Unbeatable Prices</h1>

                <h3>Fast shipping | Easy returns | Special discounts for students</h3>


            </div>


        </v-row>

        <v-row id="third_row">
            <v-col>
                <img id="third_row_img" width="95%" src="../assets//third_row_img.png" alt="">
            </v-col>
            <v-col>
                <div id="third_row_text">
                    <h1 style="font-size: 300%;">Curious about the <span style="color:#006340;">StockX</span> Mystery
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

            <v-col>
                <div id="fourth_row_text">
                    <h1 style="font-size: 300%;">Why is everyone buzzing <br> about these boxes?</h1>
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
                <img id="third_row_img" width="95%" src="../assets/fourth_row_img.png" alt="" style="float: left;">
            </v-col>

        </v-row>


    </v-col>




</template>

<style scoped>
#main_layout {
    width: 90vw;
    margin: auto;

}

#first_row {
    width: 100%;
    background-color: #000000;
    height: 80vh;
    justify-content: center;
}

#discount_circle {

    position: absolute;
    top: 0%;
    right: 0%;
    background-color: #006340;
    width: 160px;
    height: 160px;
    border-radius: 50%;

}

#discount_text {
    position: relative;
    top: 20%;
    text-align: center;
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

h2 {
    color: white;
    font-size: 250%;
}

h3 {
    font-size: 150%;
    font-weight: 600;
    color: #006340;
}

h4 {
    color: white;
    font-size: 100%;
    font-weight: 100;

}

#second_row {
    width: 100%;
    justify-content: center;
}

#second_row_content {
    text-align: center;
}



#third_row_img {
    border-radius: 50px;
    float: right;
}

#third_row_text {
    width: 90%;
    position: relative;
    top: 25%;
    height: 50%;
    vertical-align: middle;
}

#fourth_row_text {
    position: relative;
    top: 30%;
    height: 50%;
    vertical-align: middle;
    padding-left: 50px;
}
</style>
