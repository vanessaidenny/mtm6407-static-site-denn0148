<template>
    <div>
        <Banner title="Products"></Banner>
    </div>

    <div class="d-md-flex flex-md-equal w-100 mb-md-3 pl-md-3">
        <div class="bg-dark mr-md-3 pt-3 px-3 pt-md-5 px-md-5 text-center text-white overflow-hidden">
            <div class="my-3 py-3">
                <h2 class="display-5">Designer Pet Apparel</h2>
                <p class="lead">Dress your pet in style with our collection of designer apparel.</p>
            </div>
            <div class="bg-dark shadow-sm mx-auto" style="width: 80%; height: 300px; border-radius: 21px 21px 0 0;">
            <img
                class="bd-placeholder-img bd-placeholder-img-lg featurette-image img-fluid mx-auto rounded"
                width="100%"
                height="500"
                src="https://images.pexels.com/photos/5731801/pexels-photo-5731801.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
            >
            </div>
        </div>
        <div class="bg-light mr-md-3 pt-3 px-3 pt-md-5 px-md-5 text-center overflow-hidden">
            <div class="my-3 p-3">
                <h2 class="display-5">Premium Pet Food</h2>
                <p class="lead">Nourish your pet from the inside out with our selection of premium pet food.</p>
            </div>
            <div class="bg-dark shadow-sm mx-auto" style="width: 80%; height: 300px; border-radius: 21px 21px 0 0;">
            <img
                class="bd-placeholder-img bd-placeholder-img-lg featurette-image img-fluid mx-auto rounded"
                width="100%"
                height="500"
                src="https://images.pexels.com/photos/8434725/pexels-photo-8434725.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
            >
            </div>
        </div>
    </div>

    <div class="d-md-flex flex-md-equal w-100 my-md-3 pl-md-3">
        <div class="bg-light mr-md-3 pt-3 px-3 pt-md-5 px-md-5 text-center overflow-hidden">
            <div class="my-3 p-3">
                <h2 class="display-5">Interactive Toys</h2>
                <p class="lead">Keep your pet entertained and engaged with our range of interactive toys.</p>
            </div>
            <div class="bg-dark shadow-sm mx-auto" style="width: 80%; height: 300px; border-radius: 21px 21px 0 0;">
            <img
                class="bd-placeholder-img bd-placeholder-img-lg featurette-image img-fluid mx-auto rounded"
                width="100%"
                height="500"
                src="https://images.pexels.com/photos/39388/chihuahua-dog-puppy-cute-39388.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
            >
            </div>
        </div>
        <div class="bg-dark mr-md-3 pt-3 px-3 pt-md-5 px-md-5 text-center text-white overflow-hidden">
            <div class="my-3 py-3">
                <h2 class="display-5">Cozy Pet Beds</h2>
                <p class="lead">Provide your pet with a comfortable place to rest and relax with our cozy pet beds.</p>
            </div>
            <div class="bg-dark shadow-sm mx-auto" style="width: 80%; height: 300px; border-radius: 21px 21px 0 0;">
            <img
                class="bd-placeholder-img bd-placeholder-img-lg featurette-image img-fluid mx-auto rounded"
                width="100%"
                height="500"
                src="https://images.pexels.com/photos/4545195/pexels-photo-4545195.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
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