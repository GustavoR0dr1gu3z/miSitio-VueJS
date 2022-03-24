<template>
    <nav class="navbar navbar-expand-lg navbar-light bg-success bg-gradient" style="--bs-bg-opacity: .8;">
        <div class="container-fluid">
            <router-link to="/"> 
                <img src="http://www.ignia.mx/wp-content/uploads/2018/10/CredijustoLogo-1024x184.png" alt="" width="125" height="35" class="d-inline-block align-text-top">                
            </router-link>
                
            
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
        
            <div class="collapse navbar-collapse   justify-content-end" id="navbarNavAltMarkup">
                <div class="navbar-nav fw-bold">

                    <li class="nav-item me-4">
                        <router-link to="/" class="nav-link active">                            
                            ¿Quién Soy?
                        </router-link>
                    </li>
                    <li class="nav-item me-4">
                        <router-link class="nav-link active " to="/experiencia-laboral">
                            Experiencia Laboral
                        </router-link>
                    </li>
                    <li class="nav-item me-4">                
                        <router-link class="nav-link active" to="/participaciones"> 
                            Participaciones
                        </router-link>
                    </li>   
                    <li class="nav-item me-4">                
                        <router-link class="nav-link active" to="/proyectos"> 
                            Proyectos
                        </router-link>
                    </li>   
                    <li class="nav-item me-4">                
                        <router-link class="nav-link active" to="/servicios"> 
                            Servicios
                        </router-link>
                    </li>   
                    <li class="nav-item me-4">                
                        <router-link class="nav-link active" to="/contacto"> 
                            Contactame
                        </router-link>
                    </li> 

                </div>
            </div>

        </div>
</nav>

</template>

<script>
export default {
}
</script>

<style>
</style>