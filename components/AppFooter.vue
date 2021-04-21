<template>
    <div class="p-3 bg-dark">
        <div class="container p-5">
            <div class="row">
                <div class="col-4 text-light">
                    <h2 class="text-arvo font-weight-bolder">
                        JongKreatif
                    </h2>
                </div>
                <div class="mt-4 col-8">
                    <div class="row">
                        <div class="col text-light d-flex flex-column justify-content-center">
                            <h5 class="text-center text-baloo font-weight-bold text-uppercase">
                                About JongKreatif
                            </h5>
                            <div class="mt-3 text-center text-opacity-50 d-flex flex-column justify-content-center">
                                <nuxt-link class="text-light" to="/about">About Us</nuxt-link>
                                <nuxt-link class="text-light" to="/faq">FAQ</nuxt-link>
                                <nuxt-link class="text-light" to="/tos">Terms of Service</nuxt-link>
                                <nuxt-link class="text-light" to="/contact">Contact Us</nuxt-link>
                                <nuxt-link class="text-light" to="/sitemap">Sitemap</nuxt-link>
                            </div>
                        </div>
                        <div class="col d-flex flex-column justify-content-center text-light">
                            <h5 class="text-center text-baloo font-weight-bold text-uppercase">
                                Contact Us
                            </h5>
                            <p class="mt-3 text-center text-opacity-50 text-nunito">
                                Email Us: jongkreatif@jongkreatif.id
                                <br>
                                Jl. Jalanin aja Pasti Sampai No.007
                            </p>
                            <b-button variant="danger" class="text-baloo">
                                Contact Now
                            </b-button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>