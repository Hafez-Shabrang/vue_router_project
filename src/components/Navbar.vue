<template>
    <nav class="navbar navbar-expand-lg bg-body-tertiary" style="background-color: #e3f2fd;">
    <div class="container-fluid">
        <!-- <a class="navbar-brand" href="#">Navbar</a> -->
        <router-link to="/" class="navbar-brand">Project</router-link>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
            <!-- <a class="nav-link active" aria-current="page" href="#">Home</a> -->
            <router-link to="/" class="nav-link active">Home</router-link>
            </li>
            <li class="nav-item">
            <router-link to="/about" class="nav-link active">Abuot</router-link>
            </li>
            <li class="nav-item">
            <router-link to="/profile" class="nav-link active">Profile</router-link>
            </li>
        </ul>
        </div>
    </div>
    </nav>
</template>