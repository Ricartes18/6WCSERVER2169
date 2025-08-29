<template>
    <div class="card mb-3 mx-auto" style="max-width: 540px; ">
  <div class="row g-0">
    <div class="col-md-4">
      <img src="E:\2169CLRD\MIDTERMS\resume-vue\public\ricartes.png" class="img-fluid rounded-start" alt="...">
    </div>
    <div class="col-md-8">
      <div class="card-body">
        <h5 class="card-title">{{ name }}</h5>
        <p class="card-text">{{ course }}</p>
        <p class="card-text">{{ specialization }}</p>
        <p class="card-text"><small class="text-body-secondary">3rd Year Student</small></p>
      </div>
    </div>
  </div>
</div>
</template>

<script>
    export default {
        name: 'Profile',
        data () {
            return {
                name: 'Cedric Luis Dungca',
                course: 'Bachelor of Science in Information Technology',
                specialization: 'Specialization in Web Development'
            }
        }
    }
</script>