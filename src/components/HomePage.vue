<script setup>

</script>

<template>
  <v-app>
    <v-main>
      <v-container fluid class="pa-0 homepage">
        <!-- Hero Banner Image -->
        <v-row no-gutters>
          <v-col>
            <v-img
              src="motivationscreen.jpg"
              alt="Gym Hero Banner"
              height="290px"
              class="hero-banner"
              cover
            >
            </v-img>
          </v-col>
        </v-row>

        <!-- Quick Access Buttons -->
        <v-row class="my-6" justify="space-around">
          <v-btn color="primary" rounded elevation="2">Start Workout</v-btn>
          <v-btn color="secondary" rounded elevation="2">Track Progress</v-btn>
          <v-btn color="success" rounded elevation="2">Nutrition</v-btn>
          <v-btn color="info" rounded elevation="2">Community</v-btn>
        </v-row>

        <!-- Today's Workout -->
        <v-card class="mb-6 workout-card" outlined>
          <v-card-title class="text-h6 font-weight-bold">Today's Workout</v-card-title>
          <v-card-text>
            <div class="d-flex justify-space-between align-center">
              <div>
                <h3 class="text-subtitle-1 font-weight-medium">Full Body Routine</h3>
                <p class="grey--text">🕒 45 min | 🔥 350 cal</p>
              </div>
              <v-btn color="primary" rounded>START</v-btn>
            </div>
          </v-card-text>
        </v-card>

        <!-- Progress Section -->
        <v-card outlined class="progress-card mb-12">
          <v-card-title class="text-h6 font-weight-bold">Your Progress</v-card-title>
          <v-card-text>
            <v-img src="18334.jpg"></v-img>
            <v-row>
              <v-col class="text-center font-weight-medium">Weight: 175 lbs</v-col>
              <v-col class="text-center font-weight-medium">Reps This Week: 320</v-col>
              <v-col class="text-center font-weight-medium">Goal Progress: 65%</v-col>
            </v-row>
          </v-card-text>
        </v-card>
      </v-container>
    </v-main>
  </v-app>
</template>

<style scoped>
.homepage {
  min-height: 100vh;
  background-color: #f9f9f9;
}

.hero-banner {
  position: relative;
}

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