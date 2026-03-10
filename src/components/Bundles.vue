<script setup>

</script>

<template>
    <v-container style="background-color: #CFD0D6;" class="mt-12">
        <v-row>
            <div class="text-display-medium mb-12">Bundles and Pricing</div>
        </v-row>

        <v-row>
            <v-col md="3">
                <v-card class="text-center">
                    <v-icon color="#690000" icon="mdi-clock-outline" size="large" class="mt-8"></v-icon>
                    <v-card-title style="color: #690000;">Daily Pass</v-card-title>
                    <v-card-text>500 Ksh</v-card-text>
                </v-card>
            </v-col>
            <v-col md="3">
                <v-card class="text-center">
                    <v-icon color="#690000" icon="mdi-calendar-month" size="large" class="mt-8"></v-icon>
                    <v-card-title style="color: #690000;">1 Month</v-card-title>
                    <v-card-text>4000 Ksh</v-card-text>
                </v-card>
            </v-col>
            <v-col md="3">
                <v-card class="text-center">
                    <v-icon color="#690000" icon="mdi-numeric-3-circle-outline" size="large" class="mt-8"></v-icon>
                    <v-card-title style="color: #690000;">3 Months</v-card-title>
                    <v-card-text>10000 Ksh</v-card-text>
                </v-card>
            </v-col>
            <v-col md="3">
                <v-card class="text-center">
                    <v-icon color="#690000" icon="mdi-numeric-6-circle-outline" size="large" class="mt-8"></v-icon>
                    <v-card-title style="color: #690000;">6 Months</v-card-title>
                    <v-card-text>20000 Ksh</v-card-text>
                </v-card>
            </v-col>
        </v-row>

        <v-row>
            <v-col md="12">
                <v-card class="text-center">
                    <v-icon color="#690000" icon="mdi-timer-sand-full" size="large" class="mt-8"></v-icon>
                    <v-card-title style="color: #690000;">12 Months</v-card-title>
                    <v-card-text>38000 Ksh</v-card-text>
                </v-card>
            </v-col>
        </v-row>
    </v-container>

    <!-- What's Included -->
    <v-container style="background-color: #CFD0D6;" class="mt-12">
        <v-row>
            <div class="text-display-medium mb-12 align">What's Included in our Membership?</div>
        </v-row>

        <v-row class="text-center">
            <v-col md="3">
                <v-card>
                    <v-icon color="#690000" icon="mdi-calendar-clock" size="large" class="mt-8"></v-icon>
                    <v-card-title>24/7 Access</v-card-title>
                </v-card>
            </v-col>
            <v-col md="3">
                <v-card>
                    <v-icon color="#690000" icon="mdi-wifi" size="large" class="mt-8"></v-icon>
                    <v-card-title>Free Wifi</v-card-title>
                </v-card>
            </v-col>
            <v-col md="3">
                <v-card>
                    <v-icon color="#690000" icon="mdi-parking" size="large" class="mt-8"></v-icon>
                    <v-card-title>Free Parking</v-card-title>
                </v-card>
            </v-col>
            <v-col md="3">
                <v-card>
                    <v-icon color="#690000" icon="mdi-shower-head" size="large" class="mt-8"></v-icon>
                    <v-card-title>Sauna and Showers</v-card-title>
                </v-card>
            </v-col>
        </v-row>

        <v-row class="text-center">
            <v-col md="3">
                <v-card>
                    <v-icon color="#690000" icon="mdi-weight-lifter" size="large" class="mt-8"></v-icon>
                    <v-card-title>Professional Trainers</v-card-title>
                </v-card>
            </v-col>
            <v-col md="3">
                <v-card>
                    <v-icon color="#690000" icon="mdi-locker-multiple" size="large" class="mt-8"></v-icon>
                    <v-card-title>Personal Lockers</v-card-title>
                </v-card>
            </v-col>
            <v-col md="3">
                <v-card>
                    <v-icon color="#690000" icon="mdi-account-group" size="large" class="mt-8"></v-icon>
                    <v-card-title>Club Societies</v-card-title>
                </v-card>
            </v-col>
            <v-col md="3">
                <v-card>
                    <v-icon color="#690000" icon="mdi-tag-arrow-down" size="large" class="mt-8"></v-icon>
                    <v-card-title>Special Discounts</v-card-title>
                </v-card>
            </v-col>
        </v-row>
    </v-container>

    <!-- How to Join -->
    <v-container style="background-color: #CFD0D6;" class="mt-12">
        <v-row class="text-center">
            <v-col>
                <div class="text-display-medium mb-12">How to Join?</div>
            </v-col>
        </v-row>
        <v-row>
            <v-col>
                <v-list>
                    <v-list-item>1. Click on the "Join Now" button.</v-list-item>
                    <v-list-item>2. Fill the form ensuring you select your preferred Membership.</v-list-item>
                    <v-list-item>3. Pay either through the front desk at the gym or online using M-PESA.</v-list-item>
                    <v-list-item>4. Come to our gym when you're ready to start your journey.</v-list-item>
                </v-list>
            </v-col>
        </v-row>
    </v-container>
</template>