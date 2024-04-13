<template>
    <div>
        <Banner title="About Us"></Banner>
    </div>

    <div class="banner p-4 p-md-5 mb-4 text-white">
        <div class="container col-md-6 px-0">
            <h1 class="display-4 font-italic">Background</h1>
            <p class="lead my-3">We are in the pet shop market since 2002. We started out selling just collars and clothes, and after just two years of opening, we started to conquer the sale of feed and treats, accessories and toys. Today we have two stores and fifty employees.</p>
        </div>
    </div>        
    <div class="container">
        <div class="row">
            <div class="col-md-8">
                <div class="blog-post">
                    <h2 class="blog-post-title">Our Mission</h2>
                    <p>At Pet Fun, we are passionate about enhancing the lives of pets and their owners alike. Our mission is to provide not only the best products but also expert guidance and support to ensure that every pet and their human companion experience joy, comfort, and fulfillment.</p>
                    
                    <hr>

                    <h2>Why Choose Pet Fun?</h2>
                    <p>Wide Range of Products: From trendy apparel to nutritious feeds and everything in between, we offer a diverse range of high-quality products to cater to every pet's needs and preferences.</p>
                    <p>Expert Advice: Our knowledgeable staff members are not just salespeople; they are passionate pet enthusiasts trained to provide expert advice and guidance on pet care, nutrition, and training.</p>
                    <p>Exceptional Service: We prioritize customer satisfaction above all else, striving to create a welcoming and enjoyable shopping experience for every visitor to our stores.</p>
                    <p>Community Engagement: We believe in giving back to the community that supports us. Through various initiatives and partnerships, we actively contribute to the well-being of pets in need and promote responsible pet ownership.</p>
                </div>
                <div class="blog-post">
                    <h2 class="blog-post-title">Welcome to Pet Fun: A Haven for Pet Lovers</h2>
                    <p>At Pet Fun, we're more than just a pet shop - we're a destination for pet lovers. Whether you're seeking the perfect accessory to pamper your furry friend or expert advice on pet care, our team is here to make your experience delightful and fulfilling.</p>
                </div>
                <div class="blog-post">
                    <h2 class="blog-post-title">Discovering Pet Fun</h2>
                    <p>From fashionable collars and cozy clothes to delicious treats and stimulating toys, Pet Fun offers a treasure trove of products to cater to every pet's desires. Our shelves are stocked with top-of-the-line brands known for their quality and innovation, ensuring that your pet receives nothing but the best.</p>
                </div>
                <div class="blog-post">
                    <h2 class="blog-post-title">Creating Moments of Joy</h2>
                    <p>Pets bring immeasurable joy into our lives, and at Pet Fun, we're dedicated to enhancing that bond. From exciting new product launches to community events and pet adoption drives, we're constantly striving to create memorable experiences that celebrate the special connection between pets and their owners.</p>
                </div>
            </div>

            <aside class="col-md-4">
                <div class="p-4 mb-3 bg-light rounded">
                    <h4 class="font-italic">Join the Pet Fun Family</h4>
                    <p class="mb-0">Whether you're shopping for your beloved companion or simply seeking inspiration for your next pet adventure, we invite you to experience the magic of Pet Fun. Visit us today and discover why we're more than just a pet shop - we're a celebration of all things furry, feathered, and fabulous!</p>
                </div>

                <div class="p-4">
                    <h4 class="font-italic">Archives</h4>
                    <ol class="list-unstyled mb-0">
                        <li><a href="#">March 2014</a></li>
                        <li><a href="#">February 2014</a></li>
                        <li><a href="#">January 2014</a></li>
                        <li><a href="#">December 2013</a></li>
                        <li><a href="#">November 2013</a></li>
                        <li><a href="#">October 2013</a></li>
                        <li><a href="#">September 2013</a></li>
                        <li><a href="#">August 2013</a></li>
                        <li><a href="#">July 2013</a></li>
                        <li><a href="#">June 2013</a></li>
                        <li><a href="#">May 2013</a></li>
                        <li><a href="#">April 2013</a></li>
                    </ol>
                </div>
            </aside>
        </div>
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

    /* stylelint-disable selector-list-comma-newline-after */

    .blog-header {
        line-height: 1;
        border-bottom: 1px solid #e5e5e5;
    }

    .blog-header-logo:hover {
        text-decoration: none;
    }

    .nav-scroller {
        position: relative;
        z-index: 2;
        height: 2.75rem;
        overflow-y: hidden;
    }

    .nav-scroller .nav {
        display: flex;
        flex-wrap: nowrap;
        padding-bottom: 1rem;
        margin-top: -1px;
        overflow-x: auto;
        text-align: center;
        white-space: nowrap;
        -webkit-overflow-scrolling: touch;
    }

    .nav-scroller .nav-link {
        padding-top: .75rem;
        padding-bottom: .75rem;
    }

    .card-img-right {
        height: 100%;
        border-radius: 0 3px 3px 0;
    }

    .flex-auto {
        flex: 0 0 auto;
    }

    .h-250 {
        height: 250px;
    }

    @media (min-width: 768px) {
        .h-md-250 {
            height: 250px;
        }
    }

    /* Pagination */
    .blog-pagination {
        margin-bottom: 4rem;
    }

    .blog-pagination>.btn {
        border-radius: 2rem;
    }

    /*
    * Blog posts
    */
    .blog-post {
        margin-bottom: 4rem;
    }

    .blog-post-title {
        margin-bottom: .25rem;
    }

    .blog-post-meta {
        margin-bottom: 1.25rem;
        color: #727272;
    }

    /*
    * Footer
    */
    .blog-footer {
        padding: 2.5rem 0;
        color: #727272;
        text-align: center;
        background-color: #f9f9f9;
        border-top: .05rem solid #e5e5e5;
    }

    .blog-footer p:last-child {
        margin-bottom: 0;
    }
</style>