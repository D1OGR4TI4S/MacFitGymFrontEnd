<script setup>

</script>

<template>
    <v-container max-width="100%" class="pa-4">
        <!-- Hero Banner Image -->
        <v-row class="mb-6 align-center">
            <v-col>
                <v-img src="motivationscreen.jpg" alt="Gym Hero Banner" height="220px" cover></v-img>
            </v-col>
        </v-row>
    </v-container>

    <!-- Quick Access Button -->
    <v-container max-width="100%">
        <v-row class="d-flex justify-center">
            <v-btn color="primary" rounded elevation="2">Start Workout</v-btn>
            <v-btn color="secondary" rounded elevation="2">Track Progress</v-btn>
            <v-btn color="success" rounded elevation="2">Nutrition</v-btn>
            <v-btn color="info" rounded elevation="2">Community</v-btn>
        </v-row>
    </v-container>

    <!-- Today's Workout -->
    <v-container max-width="100%">
        <v-row class="d-flex justify-center">
            <v-card class="mb-6 workout-card" outlined>
            <v-card-title class="text-h6 font-weight-bold">Today's Workout</v-card-title>
            <v-card-text>
                <div class="text-center">
                    <div>
                        <h3 class="text-subtitle-1 font-weight-medium">Full Body Routine</h3>
                        <p class="grey--text">🕒 45 min | 🔥 350 cal</p>
                    </div>
                    <v-btn color="primary" rounded>START</v-btn>
                </div>
            </v-card-text>
            </v-card>
        </v-row>
    </v-container>

    <!-- Progress Section -->
    <v-container>
        <v-card outlined class="progress-card">
            <v-card-title class="text-h6 font-weight-bold">Your Progress</v-card-title>
            <v-card-text>
                <div class="mb-4 text-center grey--text">📈 [Graph Placeholder]</div>
                <v-row>
                    <v-col class="text-center font-weight-medium">Weight: 175 lbs</v-col>
                    <v-col class="text-center font-weight-medium">Reps This Week: 320</v-col>
                    <v-col class="text-center font-weight-medium">Goal Progress: 65%</v-col>
                </v-row>
            </v-card-text>
        </v-card>
    </v-container>


  
</template>

<style scoped>
.overlay-text {
  position: absolute;
  bottom: 16px;
  left: 16px;
}

.workout-card {
  background-color: #fffbea;
}

.progress-card {
  background-color: #eef7ff;
}
</style>