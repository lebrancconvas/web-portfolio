<template>
    <div>
       <nav class="navbar navbar-expand-lg navbar-dark bg-dark"> 
            <div class="container-fluid">
                <a class="navbar-brand" href="#">Poomkun</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#" tabindex="-1" aria-disabled="true">Project</a> 
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Skill</a> 
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Contact</a>
                    </li> 
                </ul>
                </div>
            </div>
        </nav> 
    </div>
</template>

<script>
export default {
    name: "Navbar"
}
</script>

<style scoped>

</style>