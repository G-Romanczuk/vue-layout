<script setup lang="ts">

</script>

<template>
    <v-card id="userForm_card">
        <h2>Enter Details</h2>
        <v-col class="center" cols="11">
            <v-form>
                <v-row no-gutters>
                    <v-col>
                        <v-text-field model-value="First Name" variant="outlined" readonly
                            style="padding-right: 10px;"></v-text-field>
                    </v-col>

                    <v-col>
                        <v-text-field model-value="Last Name" variant="outlined" readonly
                            style="padding-left: 10px;"></v-text-field>
                    </v-col>
                </v-row>
                <v-row no-gutters>
                    <v-text-field model-value="Street" variant="outlined" readonly></v-text-field>
                </v-row>
                <v-row no-gutters>
                    <v-col>
                        <v-text-field model-value="Postal Code" variant="outlined" readonly
                            style="padding-right: 10px;"></v-text-field>
                    </v-col>
                    <v-col>
                        <v-text-field model-value="City" variant="outlined" readonly
                            style="padding-left: 10px;"></v-text-field>
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









        </v-col>
    </v-card>


</template>

<style scoped>
#userForm_card {
    width: 90%;
    height: 90%;
    text-align: center;
    justify-content: center;
}



.center {
    margin: auto;
}
</style>
