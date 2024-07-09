<script>
export default {
    name: 'Header'
}

</script>

<template>
    <header>
        <div class="header-banner text-center py-2">
            <p class="m-0">Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime, hic?</p>
        </div>

        <nav class="py-4 navbar navbar-expand-lg ">
            <div class="container-fluid ">
                <a class="navbar-brand p-0" href="#">
                    <img src="/img/logo.png" alt=""></a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                    data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
                    aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse justify-content-center" id="navbarSupportedContent">
                    <ul class="navbar-nav  mb-lg-0">
                        <li class="nav-item">
                            <a class="nav-link active" aria-current="page" href="#">Home</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Link</a>
                        </li>
                        <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown"
                                aria-expanded="false">
                                Dropdown
                            </a>
                            <ul class="dropdown-menu">
                                <li><a class="dropdown-item" href="#">Action</a></li>
                                <li><a class="dropdown-item" href="#">Another action</a></li>
                                <li>
                                    <hr class="dropdown-divider">
                                </li>
                                <li><a class="dropdown-item" href="#">Something else here</a></li>
                            </ul>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link disabled" aria-disabled="true">Disabled</a>
                        </li>
                    </ul>

                </div>
            </div>
            <div class="mx-3 d-flex align-items-center">
                <ul class=" d-flex m-0 gap-2 list-unstyled">
                    <li><i class="fa fa-user-circle" aria-hidden="true"></i></li>
                    <li><i class="fa fa-heart" aria-hidden="true"></i></li>
                    <li><i class="fa fa-shopping-bag" aria-hidden="true"></i></li>
                    <li><i class="fa fa-search" aria-hidden="true"></i></li>
                </ul>
            </div>

            
        </nav>
    </header>
</template>



<style></style>