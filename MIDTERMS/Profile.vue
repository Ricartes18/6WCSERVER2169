<template>
    <div class="col">
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

        <div class="card">
            <div class="card-body">
                Address: {{ address }}
            </div>
        </div>
        <div class="card">
            <div class="card-body">
                Phone Number: {{ number }}
            </div>
        </div>

        <div class="card">
            <div class="card-body">
                Email: {{ email }}
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
                specialization: 'Specialization in Web Development',
                address: '2098 Gen. Grant St. Sta. Teresita Angeles City Pampanga',
                number: "0981-332-0360",
                email: "cedricluis18@gmail.com"
            }
        }
    }

</script>
