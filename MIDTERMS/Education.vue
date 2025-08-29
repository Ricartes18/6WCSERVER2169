<template>
    <div class="row">
    <div class="col-sm-6 mb-3 mb-sm-0">
        <div class="card">
        <div class="card-body">
            <h5 class="card-title">{{ elementary }}</h5>
            <p class="card-text">{{ eleminfo }}</p>
            <a href="#" class="btn btn-primary">Elementary</a>
        </div>
        </div>
    </div>
    <div class="col-sm-6 mb-6 mt-7">
        <div class="card">
        <div class="card-body">
            <h5 class="card-title">{{ hs }}</h5>
            <p class="card-text">{{ hsad }}</p>
            <a href="#" class="btn btn-primary">Junior & Senior Highschool</a>
        </div>
        </div>
    </div>
    <div class="col-sm-6">
        <div class="card">
        <div class="card-body">
            <h5 class="card-title">{{ college }}</h5>
            <p class="card-text">{{ hsad }}</p>
            <a href="#" class="btn btn-primary">College</a>
        </div>
        </div>
    </div>
    </div>
</template>

<script>
    export default {
        name: 'education',
        data () {
            return {
                elementary: 'Sto. Rosario Elementary School',
                eleminfo: '4HPR+V29, Miranda St, Angeles, 2009 Pampanga',
                hs: 'Holy Angel University',
                college: 'Holy Angel University',
                hsad: '#1 Holy Angel St, Angeles, 2009 Pampanga'
            }
            
        }
    }
</script>