<template>
<div>
    <header>

        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="container-fluid">

                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                        <li class="nav-item">
                            <nuxt-link to="/" class="nav-link">Home</nuxt-link>
                        </li>
                        <li class="nav-item">
                            <nuxt-link to="products" class="nav-link">Products</nuxt-link>
                        </li>
                        <li class="nav-item">
                            <nuxt-link to="/about" class="nav-link">About</nuxt-link>
                        </li>
                        <li class="nav-item">
                            <nuxt-link to="/contact" class="nav-link">Contact</nuxt-link>
                        </li>
                        <li class="nav-item">
                            <nuxt-link to="/service" class="nav-link">Service</nuxt-link>
                        </li>
                    </ul>
                    <form class="d-flex">
                        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                        <button class="btn btn-outline-success" type="submit">Search</button>
                    </form>
                </div>
            </div>
        </nav>
    </header>
    <main>
        <slot>

        </slot>

    </main>
    <footer>
        <section>
            <div class="container">
                <div class="row">
                    <div class="col-md-3">
                        <img src="https://codeit.com.np/images/1642171339codeIT logo.png" style="width: 180px;" alt="">
                        <p>900000</p>
                        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Eligendi, asperiores deleniti voluptas vitae laudantium totam impedit sint ex.</p>
                        <h6>We are on</h6>
                    </div>
                    <div class="col-md-3">
                        <h1>Quick Link</h1>
                        <p>
                            About us
                            
                           
                          
                        </p>
                        <p>
                             Contact us
                        </p>
                        <p>
                             Gallery
                        </p>
                        <p>
                              Blog  
                        </p>
                    </div>
                    <div class="col-md-3">
                       <h1> Bank account detail</h1>
                       <p>Bank:Nepal bank limited</p>
                       <p>Account:Code it</p>
                       <p>account no.00000</p>
                       <p>Branch:dharan</p>
                       <img src="https://www.bing.com/images/search?q=FonePay+Logo&FORM=IRTRRL" alt="">



                    </div>
                    <div class="col-md-3">
                        <h1>Download app</h1>
                        <p>Download our mobile app</p>
                        <img src="https://codeit.com.np/mobile/appstore.png" alt="">
                        <img src="https://codeit.com.np/mobile/googleplay.png" alt="">

                    </div>
                </div>
            </div>
        </section>

    </footer>

</div>
</template>

<script setup>

</script>

<style  scoped>

</style>
