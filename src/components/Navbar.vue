<template>
    <nav class="navbar navbar-expand-lg navbar-light bg-success bg-gradient" style="--bs-bg-opacity: .8;">
        <div class="container-fluid">

            <div class="collapse navbar-collapse   justify-content-end" id="navbarNavAltMarkup">
                <div class="navbar-nav fw-bold">

                    <li class="nav-item me-5">
                        <router-link to="/" class="nav-item nav-link">
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