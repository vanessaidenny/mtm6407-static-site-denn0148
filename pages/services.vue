<template>
    <div>
        <Banner title="Services"></Banner>
    </div>

    <div class="d-md-flex flex-md-equal w-100 mb-md-3 pl-md-3">
        <div class="bg-dark mr-md-3 pt-3 px-3 pt-md-5 px-md-5 text-center text-white overflow-hidden">
            <div class="my-3 py-3">
                <h2 class="display-5">Pet Grooming</h2>
                <p class="lead">Treat your furry friend to a spa day with our professional grooming services.</p>
            </div>
            <div class="bg-dark shadow-sm mx-auto" style="width: 80%; height: 300px; border-radius: 21px 21px 0 0;">
            <img
                class="bd-placeholder-img bd-placeholder-img-lg featurette-image img-fluid mx-auto rounded"
                width="100%"
                height="500"
                src="https://images.pexels.com/photos/1436139/pexels-photo-1436139.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
            >
            </div>
        </div>
        <div class="bg-light mr-md-3 pt-3 px-3 pt-md-5 px-md-5 text-center overflow-hidden">
            <div class="my-3 p-3">
                <h2 class="display-5">Training Workshops</h2>
                <p class="lead">Enroll your pet in our training workshops led by certified experts.</p>
            </div>
            <div class="bg-dark shadow-sm mx-auto" style="width: 80%; height: 300px; border-radius: 21px 21px 0 0;">
            <img
                class="bd-placeholder-img bd-placeholder-img-lg featurette-image img-fluid mx-auto rounded"
                width="100%"
                height="500"
                src="https://images.pexels.com/photos/8081417/pexels-photo-8081417.jpeg"
            >
            </div>
        </div>
    </div>

    <div class="d-md-flex flex-md-equal w-100 my-md-3 pl-md-3">
        <div class="bg-light mr-md-3 pt-3 px-3 pt-md-5 px-md-5 text-center overflow-hidden">
            <div class="my-3 p-3">
                <h2 class="display-5">Pet Boarding</h2>
                <p class="lead">Planning a trip? Leave your pet in good hands with our reliable pet boarding services.</p>
            </div>
            <div class="bg-dark shadow-sm mx-auto" style="width: 80%; height: 300px; border-radius: 21px 21px 0 0;">
            <img
                class="bd-placeholder-img bd-placeholder-img-lg featurette-image img-fluid mx-auto rounded"
                width="100%"
                height="500"
                src="https://images.pexels.com/photos/2133108/pexels-photo-2133108.jpeg"
            >
            </div>
        </div>
        <div class="bg-dark mr-md-3 pt-3 px-3 pt-md-5 px-md-5 text-center text-white overflow-hidden">
            <div class="my-3 py-3">
                <h2 class="display-5">Veterinary Consultations</h2>
                <p class="lead">Schedule a veterinary consultation with our experienced team about your pet's well-being.</p>
            </div>
            <div class="bg-dark shadow-sm mx-auto" style="width: 80%; height: 300px; border-radius: 21px 21px 0 0;">
            <img
                class="bd-placeholder-img bd-placeholder-img-lg featurette-image img-fluid mx-auto rounded"
                width="100%"
                height="500"
                src="https://images.pexels.com/photos/5731866/pexels-photo-5731866.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
            >
            </div>
        </div>
    </div>
</template>

<script setup>
</script>

<style scoped>
    .flex-equal>* {
        flex: 1;
    }

    @media (min-width: 768px) {
        .flex-md-equal>* {
            flex: 1;
        }
    }
</style>