<script setup lang="ts">
console.log('hello script setup')
</script>

<template>

    <v-col>
        <v-row id="footer_first_row">
            <v-col>
                <h5>How can I win? </h5>
                <p>Thanks to your membership, you also participate in our contest to win the iPhone15. We sellect a
                    winner among every 600 participants. The next winner will be selected on 06.10.2023, and will be
                    notified directly by e-mail. If the reward is out of stock, the winner will receive a similar
                    product of equal or greater value instead. </p>
            </v-col>
            <v-col>
                <h5> No hidden fees?</h5>
                <p>We ensure that our members are provided with a detailed history of transactions so that they know
                    exactly what they are paying for. Credit card information is only required to facilitate future
                    purchases. There will be no charges on your credit card statement if you do not upgrade to PREMIUM
                    membership and do not make a purchase. </p>
            </v-col>
            <v-col>
                <h5>Why do we need your billing information? </h5>
                <p>By joining this service, you will receive a 5-day trial of our partner's program. If you continue
                    with a subscription beyond the 5-day trial period, you will be charged an amount on your credit card
                    which varies depending on the choice of the tariff. When your contribution is deducted from your
                    credit card or other payment method, you will have access to these services which are reserved
                    exclusively for members of our partner's website </p>
            </v-col>
        </v-row>
        <v-row id="footer_second_row">
            <v-col>

                We accept the following credit cards


                <img width="100%" src="../assets/cards.png" alt="">





            </v-col>
        </v-row>
    </v-col>

</template>

<style scoped>
#footer_first_row {
    padding-top: 40px;
    background-color: #F5F5F5;
    padding-bottom: 20px;
}

#footer_second_row {
    padding-top: 10px;
    width: 30%;
    margin: auto;
    text-align: center;
}
</style>
