<template>
  <div>
    <Banner title="Home"></Banner>
  </div>

  <div class="banner p-4 p-md-5 mb-4 text-white">
    <div class="container col-md-6 px-0">
      <h1 class="display-4 font-italic">
        Unveiling the Wonders of Interactive Pet Toys: Engaging Your Furry
        Friend's Playful Spirit
      </h1>
      <p class="lead mb-0">
        <NuxtLink to="/about" class="text-white font-weight-bold">Read more</NuxtLink>
      </p>
    </div>
  </div>
  <div class="container marketing mt-5">
    <div class="row">
      <div class="col-lg-4">
        <img
          class="bd-placeholder-img rounded-circle"
          width="200"
          height="140"
          src="https://images.pexels.com/photos/5749776/pexels-photo-5749776.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
        >

        <h2>Importance of Quality Care</h2>
        <p>
            Your pet's well-being is paramount. Find the finest products and services tailored to their needs, ensuring a happy and healthy life filled with joy and vitality.
        </p>
      </div>
      <div class="col-lg-4">
        <img
          class="bd-placeholder-img rounded-circle"
          width="200"
          height="140"
          src="https://images.pexels.com/photos/4000603/pexels-photo-4000603.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
        >

        <h2>Enhancing Happiness</h2>
        <p>
            Quality matters when it comes to your pet's care. Discover premium products and services designed to enhance their comfort and happiness, because your pet deserves nothing but the best.
        </p>
      </div>
      <div class="col-lg-4">
        <img
          class="bd-placeholder-img rounded-circle"
          width="200"
          height="140"
          src="https://images.pexels.com/photos/4011276/pexels-photo-4011276.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
        >

        <h2>Start with the Right Choices</h2>
        <p>
            Your pet's happiness starts with the right choices. Invest in superior products and services that cater to their unique needs, ensuring a fulfilling and enriching life by your side.
        </p>
      </div>
    </div>

    <hr class="featurette-divider" />

    <div class="row featurette">
      <div class="col-md-7">
        <h2 class="featurette-heading">
          Experience the Joy of Playtime
          <span class="text-muted">with Pet Fun!</span>
        </h2>
        <p class="lead">
          At Pet Fun, we're passionate about enriching the lives of pets and
          their owners through interactive play and quality products. Join us in
          our mission to bring joy and happiness to pets everywhere, one playful
          moment at a time.
        </p>
      </div>
      <div class="col-md-5">
        <img
          class="bd-placeholder-img bd-placeholder-img-lg featurette-image img-fluid mx-auto"
          width="500"
          height="500"
          src="https://images.pexels.com/photos/1262441/pexels-photo-1262441.jpeg"
        >
      </div>
    </div>

    <hr class="featurette-divider" />

    <div class="row featurette">
      <div class="col-md-7 order-md-2">
        <h2 class="featurette-heading">
          Choosing the Perfect Interactive Toy<span class="text-muted">
            for Your Pet</span
          >
        </h2>
        <p class="lead">
          Navigate through our expert recommendations and reviews of the top
          interactive pet toys on the market. Whether you have a curious cat or
          an energetic dog, we've got you covered with our curated selection of
          toys designed to engage and entertain your pet for hours on end.
        </p>
      </div>
      <div class="col-md-5 order-md-1">
        <img
          class="bd-placeholder-img bd-placeholder-img-lg featurette-image img-fluid mx-auto"
          width="500"
          height="500"
          src="https://images.pexels.com/photos/906065/pexels-photo-906065.jpeg"
        >
      </div>
    </div>

    <hr class="featurette-divider" />
  </div>
</template>

<script setup>
</script>

<style scoped>
.banner {
    background-color: #897B7A;
}

.bd-placeholder-img {
  text-anchor: middle;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

/* Carousel base class */
.carousel {
  margin-bottom: 4rem;
}

/* Since positioning the image, we need to help out the caption */
.carousel-caption {
  bottom: 3rem;
  z-index: 10;
}

/* Declare heights because of positioning of img element */
.carousel-item {
  height: 32rem;
}

.carousel-item > img {
  position: absolute;
  top: 0;
  left: 0;
  min-width: 100%;
  height: 32rem;
}

/* MARKETING CONTENT
    -------------------------------------------------- */

/* Center align the text within the three columns below the carousel */
.marketing .col-lg-4 {
  margin-bottom: 1.5rem;
  text-align: center;
}

.marketing h2 {
  font-weight: 400;
}

.marketing .col-lg-4 p {
  margin-right: 0.75rem;
  margin-left: 0.75rem;
}

/* Featurettes
    ------------------------- */

.featurette-divider {
  margin: 5rem 0;
  /* Space out the Bootstrap <hr> more */
}

/* Thin out the marketing headings */
.featurette-heading {
  font-weight: 300;
  line-height: 1;
  letter-spacing: -0.05rem;
}

/* RESPONSIVE CSS
    -------------------------------------------------- */

@media (min-width: 40em) {
  /* Bump up size of carousel content */
  .carousel-caption p {
    margin-bottom: 1.25rem;
    line-height: 1.4;
  }
}

@media (min-width: 62em) {
  .featurette-heading {
    margin-top: 7rem;
  }
}
</style>
