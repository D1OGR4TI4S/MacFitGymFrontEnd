<script setup>

</script>

<template>
    <v-container max-width="100%">
        <v-row>
            <v-carousel>
                <v-carousel-item src="carousel1.jpg" cover></v-carousel-item>
                <v-carousel-item src="carousel2.jpg" cover></v-carousel-item>
                <v-carousel-item src="carousel3.jpg" cover></v-carousel-item>
            </v-carousel>
        </v-row>
    </v-container>

    <!-- About Us -->
    <v-container style="background-color: #CFD0D6;" max-width="100%">
        <v-row >
            <v-col md="8" class="text-center">
                <div class="text-display-medium mb-12">Who we are</div>
                <div class="text-title-large font-weight light text-medium emphasis mb-8">We are a team of passionate creators driven by curiosity, innovation, and a commitment to building meaningful digital experiences. Our journey began with a simple idea: to make technology more human, more engaging, and more accessible.</div>
                <div class="text-title-large font-weight light text-medium emphasis mb-8">Collaboration is at the heart of everything we do. We thrive on diverse perspectives, blending technical expertise with creativity to solve challenges in unique ways. Whether it’s developing intuitive user interfaces, optimizing performance, or exploring new possibilities, we approach each project with dedication and a spirit of continuous learning.</div>
                <div class="text-title-large font-weight light text-medium emphasis mb-8">Looking ahead, our mission is to keep pushing boundaries while staying true to our values of transparency, ethical design, and user-first thinking. We're not just building products—we’re building trust, communities, and experiences that inspire.</div>
                <v-btn color="#690000">LEARN MORE</v-btn>
            </v-col>
            <v-col md="4">
                <v-container class="d-flex align-center justify-center fill height">
                    <v-img src="aboutUs.jpg" cover></v-img>
                </v-container>
            </v-col>
        </v-row>
    </v-container>
    <v-container>
        <v-row>
            <v-col md="4">
                <v-card>
                    <v-img src="news1.jpg" cover></v-img>
                    <v-card-title>Protein in Smoothies</v-card-title>
                    <v-card-text>Protein in smoothies helps make them more satisfying and nourishing by supporting muscle repair, boosting energy, and keeping you fuller for longer. Ingredients such as Greek yogurt, protein powder, nut butter, or seeds can both enhance the texture and balance the natural sweetness of your smoothie.</v-card-text>
                    <v-btn color="#690000">READ MORE</v-btn>
                </v-card>
            </v-col>
            <v-col md="4">
                <v-card>
                    <v-img src="news2.jpg" cover></v-img>
                    <v-card-title>Too old to have fun?</v-card-title>
                    <v-card-text>For older adults, gentle exercises like walking, swimming, non-contact sports, and light strength training can greatly improve balance, flexibility, and overall mobility. These activities help reduce the risk of falls, and support heart health without putting too much strain on the body.</v-card-text>
                    <v-btn color="#690000">READ MORE</v-btn>
                </v-card>
            </v-col>
            <v-col md="4">
                <v-card>
                    <v-img src="news3.jpg" cover></v-img>
                    <v-card-title>Hiking in the woods</v-card-title>
                    <v-card-text>Hiking is a fantastic way to combine exercise with nature, offering both physical and mental benefits. It strengthens muscles, improves cardiovascular health, and enhances balance, while also reducing stress through time spent outdoors. Plus, the fresh air and scenic views add a sense of joy that’s hard to replicate in indoor workouts.</v-card-text>
                    <v-btn color="#690000">READ MORE</v-btn>
                </v-card>
            </v-col>
        </v-row>
    </v-container>

    <!-- Reviews -->
    <v-container>
        <v-row>
            <v-col md="3">
                <v-card color="#CFD0D6">
                    <v-card-text>Wow! This app has really helped me lose 18kg in 6 months. I highly recommend everyone to try this.</v-card-text>
                    <v-rating :length="5" :size="32" :model-value="4" active-color="primary"></v-rating>
                </v-card>
            </v-col>
            <v-col md="3">
                <v-card color="#CFD0D6">
                    <v-card-text>My doctors have commended me for improving my health at home, however it was because of this app that I was able to achieve this.</v-card-text>
                    <v-rating :length="5" :size="32" :model-value="3" active-color="primary"></v-rating>
                </v-card>
            </v-col>
            <v-col md="3">
                <v-card color="#CFD0D6">
                    <v-card-text>My life has never felt as good as now thanks to this app. I feel less worried and much happier than I ever was.</v-card-text>
                    <v-rating :length="5" :size="32" :model-value="5" active-color="primary"></v-rating>
                </v-card>
            </v-col>
            <v-col md="3">
                <v-card color="#CFD0D6">
                    <v-card-text>My friends and I have tried this app and it has helped us a lot. We have seen improvements but we still do not see anything special about this app.</v-card-text>
                    <v-rating :length="5" :size="32" :model-value="3" active-color="primary"></v-rating>
                </v-card>
            </v-col>
        </v-row>
    </v-container>

    <!-- Contact Us -->
    <v-container style="background-color: #CFD0D6;" max-width="100%">
        <v-row class="text-center">
            <div class="text-title-large font-weight light text-medium emphasis mb-8">Get in Touch:</div>
            <div class="text-title-large font-weight light text-medium emphasis mb-8">0725 467 694 | macfitgym@gmail.com</div>
            <div class="text-title-large font-weight light text-medium emphasis mb-8">Opening Hours:</div>
            <div class="text-title-large font-weight light text-medium emphasis mb-8">Mon-Fri: 5:00am - 9:00pm | Sat: 5:30am - 6pm | Sun: 8:00am - 2:00pm</div>
            <div class="text-title-large font-weight light text-medium emphasis mb-8">MacFit Gym, 3rd Floor Nairobi Mall, Nairobi Road</div>
            <div class="text-title-large font-weight light text-medium emphasis mb-8"> &copy; 2025 MacFit Gym. Designed by Deo Gratias Designs</div>
        </v-row>
    </v-container>

</template>
