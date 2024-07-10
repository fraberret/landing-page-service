<script>
export default {
    name: 'Main'
}

</script>

<template>
    <main>
        <div class="jumbotron position-relative">
            <div class="container pt-5">
                <div class="row row-cols-1 row-cols-sm-2">
                    <div class="col d-flex align-items-center">
                        <div class="div">
                            <h1>codecircus</h1>
                            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Iure, doloremque.</p>

                            <form class="d-flex" role="search">
                                <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                                <button class="btn btn-outline-success" type="submit">Search</button>
                            </form>
                        </div>
                    </div>
                    <div class="col">
                        <img class="img-fluid"  src="/img/billboard-img.png" alt="">
                    </div>
                </div>
            </div>
            <div class="w-100 px-sm-5 position-absolute top-100 start-50 translate-middle">
                <div class="row row-cols-1 row-cols-sm-4 gx-sm-5 gy-1">
                    <div class="col">
                        <div class="border rounded p-3 bg-white">Custom column padding</div>
                    </div>
                    <div class="col">
                        <div class="p-3 bg-white">Custom column padding</div>
                    </div>
                    <div class="col">
                        <div class="p-3 bg-white">Custom column padding</div>
                    </div>
                    <div class="col">
                        <div class="p-3 bg-white">Custom column padding</div>
                    </div>
                </div>
            </div>
        </div>

        <div class="chisiamo mt-5 ">
            <div class="container pt-5">
                <div class="row row-cols-1 row-cols-sm-2">
                     <div class="col">
                        <img class="about-img img-fluid" src="/img/about-img.jpg" alt="">
                    </div>
                    <div class="col d-flex align-items-center">
                        <div class="div">
                            <h1>codecircus</h1>
                            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Iure, doloremque.</p>

                            <form class="d-flex" role="search">
                                <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                                <button class="btn btn-outline-success" type="submit">Search</button>
                            </form>
                        </div>
                    </div>
                   
                </div>
            </div>
           
        </div>


    </main>
</template>



<style>
.jumbotron {
    background-image: url(/public/img/billboard-bg.png);
}

.about-img{
    border-radius: 100%;
}





</style>