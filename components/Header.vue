
<template>
<no-ssr>
    <header>

        <!-- Start Navigation -->
        <nav class="navbar navbar-default navbar-sticky bootsnav">

            <div class="container-full">

                <!-- Start Atribute Navigation -->
                <div class="attr-nav">
                    <div class="call">
                        <div class="icon">
                            <i class="fas fa-phone"></i>
                        </div>
                        <div class="info">
                            <span>Have any question?</span>
                            <h5><a href="tel:+94 11 291 1934">(+94)11 291 1934</a></h5>
                        </div>
                    </div>
                </div>
                <!-- End Atribute Navigation -->

                <!-- Start Header Navigation -->
                <div class="navbar-header">
                    <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#navbar-menu">
                        <i class="fa fa-bars"></i>
                    </button>
                    <a class="navbar-brand" href="index.html">
                        <img src="assets/img/logo-red.png" class="logo" alt="Logo">
                    </a>
                </div>
                <!-- End Header Navigation -->

                <!-- Collect the nav links, forms, and other content for toggling -->
                <div class="collapse navbar-collapse" id="navbar-menu">
                    <ul class="nav navbar-nav navbar-center" data-in="#" data-out="#">
                        <li >
                            <n-link to="/" class="dropdown-toggle active" data-toggle="dropdown" >Home</n-link>

                        </li>
                        <li>
                            <NuxtLink to="about" class="dropdown-toggle " data-toggle="dropdown">About Us</NuxtLink>

                        </li>
                        <li >
                            <NuxtLink to="company" class="dropdown-toggle " data-toggle="dropdown" >Companies</NuxtLink>

                        </li>

                        <li >
                            <NuxtLink to="career"  class="dropdown-toggle" data-toggle="dropdown" >Careers</NuxtLink>

                        </li>
                        <li >
                            <NuxtLink to="/contact" class="dropdown-toggle" data-toggle="dropdown" >Contact Us</NuxtLink>

                        </li>
                        <li >
                            <NuxtLink to="media" class="dropdown-toggle" data-toggle="dropdown" >Media</NuxtLink>

                        </li>
                    </ul>
                </div><!-- /.navbar-collapse -->
            </div>

        </nav>
        <!-- End Navigation -->


    </header>
</no-ssr>

</template>

<script>
export default {

}
</script>

<style>

</style>
