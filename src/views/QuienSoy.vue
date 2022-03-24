<template>
    <div id="nav">
        <div class="card" style="width: 25rem;">
            <img src="../../public/img/imgWeb/gus.jpg" class="card-img-top" alt="niñoGuapo">            
            
            <div class="card-body">
                <p class="card-text">
                    <b>Name:</b> Gustavo Rodríguez Calzada <br>
                    <b>Profile:</b> Web Developer | Computer Engineer <br>
                    <b>Email:</b> gustavo.soader.cx@gmail.com <br>
                    <b>Phone:</b> (+52) 5611290464 <br>
                </p>
            </div>
        </div>

        <div class="cardMio" style="width: 25rem;">
            <div class="card-body">
                <p class="card-text">
                    <b>Acerca de mí</b>
                </p>
                <p>
                    Soy un pasante de Ingeniería en Computación de la Universidad Autónoma del Estado de México (UAEMex), en estos momentos me encuentro en proceso de titulación para obtener mi titulo realizando una tesis "Chatbot", realizo diversos proyectos fuera de lo académico pues resulta enriquecedor en cuanto a experiencia y conocimientos.
                    <br><br>He participado en varios eventos, como por ejemplo en el UNAMxHacks (Hackaton), donde mi proyecto fue realizar una página web con realidad aumentada y audiolibros, el fin de dicha página era transmitir conocimiento a los usuarios, específicamente de "Cultura".
                </p>
            </div>
        </div>
        
        <div class="cardMio" style="width: 25rem;">
            <div class="card-body">
                <p class="card-text">
                    Recientemente he ido a varias platicas, que me pueden ayudar a tener más conocimiento y así enriquecerme de las diferentes tecnologías que hay en el mundo laboral, así como sus aplicaciones.
                    <br><br>El fin de mi página es darme a conocer, dar a conocer mi trabajo y poder adquirir experiencia en el ámbito laboral, poniendo a la entera disposición mis datos de contacto para quien requiera de mis conocimientos y servicios.
                </p>

                <p class="card-text">
                    <a class="cv" download="GesCV_GustavoRodriguezCalzada" href="/GesCV_GustavoRodriguezCalzada.pdf">Descarga mi CV</a>
                </p>
                

                <router-link class="btn btn-primary" to="/contacto"> 
                    Contáctame
                </router-link>
                <!--Descargar un documento pdf en vue-->
                

    
            </div>
        </div>



            
    </div>
</template>

<style scoped>

/*Diseño de las cards*/
.card, .cardMio{
    /*Margen en el top*/
    margin-top: 5%;
    /*Margen del lado izquierdo*/
    margin-left: 5%;
    /*Borde*/
    border: 1px solid rgb(142, 209, 221);
    /*Color de fondo*/
    background-color: #a1d0db;
    /*Color de texto*/
    color: black;
    /*Alineación del texto*/
    text-align: left;
    /*Tamaño de fuente*/
    font-size: 18px;
    /* Borde redondo */
    border-radius: 10px;
    /* Sombra en la carta */
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);        
}


/*Display flex a las cartas*/
#nav{
    display: flex;            
    justify-content: space-around;
    
}

/*Diseño del boton en las cartas*/
.btn{
    margin-top: 15%;
    margin-left: 33%;
    background-color: #a1d0db;
    color: black;
    text-align: center;
    font-size: 18px;
    border-radius: 10px;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}

.cv{
    background-color: #4396a7;
    text-decoration: none;
    color: black;
    padding: 5px;
    text-align: center;
    font-size: 18px;
    border-radius: 5px;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}


/*Diseño del boton cuando pasa el cursor de las cartas*/
.btn:hover{
    background-color: #00C9FF;
    color: black;
    text-align: center;
    font-size: 18px;
    border-radius: 10px;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}

</style>