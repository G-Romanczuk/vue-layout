<script setup lang="ts">

</script>

<template>
    <v-card id="userForm_card">
        <h2 class="font_size_250">Enter details</h2>
        <v-col class="center" cols="11">
            <v-form>
                <v-row no-gutters>
                    <v-col>
                        <v-text-field class="padding_right_10px" model-value="First Name" variant="outlined"
                            readonly></v-text-field>
                    </v-col>

                    <v-col>
                        <v-text-field class="padding_left_10px" model-value="Last Name" variant="outlined"
                            readonly></v-text-field>
                    </v-col>
                </v-row>
                <v-row no-gutters>
                    <v-text-field model-value="Street" variant="outlined" readonly></v-text-field>
                </v-row>
                <v-row no-gutters>
                    <v-col>
                        <v-text-field class="padding_right_10px" model-value="Postal Code" variant="outlined"
                            readonly></v-text-field>
                    </v-col>
                    <v-col>
                        <v-text-field class="padding_left_10px" model-value="City" variant="outlined"
                            readonly></v-text-field>
                    </v-col>
                </v-row>
                <v-row no-gutters>
                    <v-text-field model-value="Phone Number" variant="outlined" readonly></v-text-field>
                </v-row>
                <v-row no-gutters>
                    <v-text-field model-value="E-mail" variant="outlined" readonly></v-text-field>
                </v-row>
                <v-row no-gutters>
                    <v-btn class="center" base-color="#006340" variant="elevated" size="x-large" width="95%">PROCEED TO
                        PAYMENT</v-btn>
                </v-row>

            </v-form>

            <v-row class="center" id="logo_row">
                <v-col>
                    <img class="logo_img" src="../assets/mcAfee.png" alt="">
                </v-col>
                <v-col>
                    <img class="logo_img" src="../assets/trust.png" alt="">
                </v-col>
                <v-col>
                    <img class="logo_img" src="../assets/256bit.png" alt="">
                </v-col>
            </v-row>








        </v-col>
    </v-card>


</template>

<style scoped>
#userForm_card {
    padding-top: 10px;
    width: 98%;
    text-align: center;
    justify-content: center;
}

#logo_row {
    padding-top: 15px;
    width: 50%;
}

.logo_img {
    width: 90%;
}

.v-text-field ::v-deep(.v-field) {
    border-radius: 20px;
}
</style>
