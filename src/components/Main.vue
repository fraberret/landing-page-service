<script>
export default {
    name: 'Main'
}

</script>

<template>
    <main>
        <div class="jumbotron position-relative">
            <div class="container pt-5">
                <div class="row">
                    <div class="col-6 d-flex align-items-center">
                        <div class="div">
                            <h1>codecircus</h1>
                            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Iure, doloremque.</p>

                            <form class="d-flex" role="search">
                                <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                                <button class="btn btn-outline-success" type="submit">Search</button>
                            </form>
                        </div>
                    </div>
                    <div class="col-6">
                        <img src="/img/billboard-img.png" alt="">
                    </div>
                </div>
            </div>
            <div class="container px-4 text-center position-absolute top-100 start-50 translate-middle">
                <div class="row gx-5">
                    <div class="col">
                        <div class="p-3 bg-white">Custom column padding</div>
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
    </main>
</template>



<style>
.jumbotron {
    background-image: url(/public/img/billboard-bg.png);
}
</style>