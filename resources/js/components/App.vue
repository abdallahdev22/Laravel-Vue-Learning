<template>
    <div>
        <nav class="navbar navbar-expand-md navbar-light bg-white shadow-sm">
            <div class="container">
                <a class="navbar-brand" href="/">
                    Laravel
                </a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
                        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>

                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <!-- Left Side Of Navbar -->
                    <ul class="navbar-nav mr-auto">
                        <li class="nav-item">
                            <router-link to="/" class="nav-link">Posts</router-link>
                        </li>
                        <li class="nav-item">
                            <router-link to="/posts/create" class="nav-link">Add new post</router-link>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
        <main class="py-4 container">
            <router-view/>
        </main>
    </div>
</template>

<script>
export default {
    name: "App"
}
</script>

<style scoped>

</style>
