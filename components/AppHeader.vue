<template>
    <div>
        <b-navbar toggleable="lg" variant="light" fixed="top">
            <div class="mx-auto w-75 d-flex">
                <b-navbar-brand href="#" class="font-weight-bold">JongKreatif</b-navbar-brand>

                <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

                <b-collapse id="nav-collapse" is-nav>

                    <b-navbar-nav class="ml-auto">
                        <b-nav-item class="mr-3">
                            <nuxt-link to="/" class="font-weight-bold" active-class="text-danger">Home</nuxt-link>
                        </b-nav-item>
                        <b-nav-item class="mr-3">
                            <nuxt-link to="/reports" class="font-weight-bold" active-class="text-danger">Reports</nuxt-link>
                        </b-nav-item>
                        <b-nav-item class="mr-3">
                            <nuxt-link to="/news" class="font-weight-bold" active-class="text-danger">News</nuxt-link>
                        </b-nav-item>
                        <b-nav-item class="mr-3">
                            <nuxt-link to="/mentors" class="font-weight-bold" active-class="text-danger">Mentors</nuxt-link>
                        </b-nav-item>
                        <b-nav-item class="mr-3">
                            <nuxt-link to="/about" class="font-weight-bold" active-class="text-danger">About Us</nuxt-link>
                        </b-nav-item>
                        <b-nav-item class="mr-3">
                            <nuxt-link to="/gallery" class="font-weight-bold" active-class="text-danger">Gallery</nuxt-link>
                        </b-nav-item>
                        <b-nav-item class="rounded btn-danger">
                            <nuxt-link to="/login" class="text-white font-weight-bold">Sign In</nuxt-link>
                        </b-nav-item>
                    </b-navbar-nav>
                </b-collapse>
            </div>
        </b-navbar>
    </div>
</template>