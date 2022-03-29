<template>
    <div id="nav">
        <section id="work" class="portfolio-mf sect-pt4 route">
            <div class="container">
                <div class="row">
                    <div class="col-sm-12">
                        <div class="title-box text-center">
                            <h3 class="title-a">
                                Proyectos
                            </h3>
                            <p class="subtitle-a">
                                A continuación colocaré los proyectos que he realizado, si dan clic en la imagen los direccionará a una plataforma llamada GitHub, ahí estaré subiendo todos mis proyectos.
                                Una vez dado clic lo que harán es buscar el boton "Clone", seguidamente "Download ZIP" para que comience la descarga.
                            </p>
                            <div class="line-mf"></div>
                        </div>
                    </div>
                </div>
            <div class="tarjetas">              
                    <div class="col-md-4">
                        <div class="work-box">
                            <a href="https://github.com/GustavoR0dr1gu3z/UNAMxHack">
                                <div class="work-img">
                                    <img src="../../public/img/imgWeb/difusion.png" alt="" class="img-fluid">
                                </div>
                            </a>
                                <div class="work-content">
                                    <div class="row">
                                        <div class="col-sm-8">
                                            <h2 class="w-title">Página web realizada en UNAMxHacks</h2>
                                            <div class="w-more">
                                                <h6>
                                                    Página web donde nosotros impartimos cultura de toda la república mexicana, anexandop dicho mapa y dividiendo los estados en botones, y cada uno de ellos tendrá información (Monumentos importantes, Datos interesantes) así como una imagen que deberá ser escaneada con una aplicación móvil que realizamos, y se verá en realidad aumentada. <br> Además contiene un audiolibro para la fácil lectura de algunas personas.
                                                </h6>
                                                <span class="w-ctegory">Web Design</span> / <span class="w-date">26 Oct. 2019</span>
                                            </div>
                                        </div>                 
                                    </div>
                                </div>           
                        </div>                            
                </div>

                <div class="col-md-4">
                    <div class="work-box">
                        <a href="https://github.com/GustavoR0dr1gu3z/Blender_Espada">
                            <div class="work-img">
                                <img src="../../public/img/imgWeb/espada.png" alt="" class="img-fluid">
                            </div>
                        </a>
                            <div class="work-content">
                                <div class="row">
                                    <div class="col-sm-8">
                                        <h2 class="w-title">Espada 3D hecha en Blender</h2>
                                        <div class="w-more">
                                            <h6>
                                                Réplica de una Espada Jedi, de la saga Star Wars lista para ser usada para diferentes proyectos como por ejemplo para Unity3D o diferentes plataformas que te permitan usar objetos 3D.
                                            </h6>
                                            <span class="w-ctegory">3D Animation</span> / <span class="w-date">22 Apr. 2020</span>
                                        </div>
                                    </div>                  
                                </div>
                            </div>
                    </div>                    
                </div>   
                
                
                <div class="col-md-4">
                    <div class="work-box">
                        <a href="https://github.com/GustavoR0dr1gu3z/Detector_Personas_RNN">
                            <div class="work-img">
                                <img src="../../public/img/imgWeb/personas.jpg" alt="" class="img-fluid">
                            </div>
                        </a>
                                <div class="work-content">
                                    <div class="row">
                                        <div class="col-sm-8">
                                            <h2 class="w-title">Detector de personas con una neurona</h2>        
                                            <div class="w-more">
                                                <h6>
                                                    Proyecto de un detector de personas usando una neurona, donde se escoge una imagen y predice si es un humano o no.
                                                </h6>
                                                <span class="w-ctegory">Detector de personas</span> / <span class="w-date">01 Dic. 2020</span>
                                            </div>
                                        </div>                 
                                    </div>
                                </div>                        
                    </div>          
                </div>   
            </div> 
            </div> 
        </section>
    </div>

</template>


<style scoped>

.box-shadow,
.paralax-mf,
.service-box,
.work-box,
.card-blog {
  box-shadow: 0 13px 8px -10px rgba(0, 0, 0, 0.1);
}

.title-s {
  font-weight: 600;
  color: #1e1e1e;
  font-size: 1.1rem;
}

/*--/ Title A /--*/

.title-box {
  margin-bottom: 4rem;
}

.title-a {
  font-size: 3rem;
  font-weight: bold;
  text-transform: uppercase;
}

.subtitle-a {
  color: #4e4e4e;
}

.line-mf {
  width: 40px;
  height: 5px;
  background-color: #0078ff;
  margin: 0 auto;
}

/*--/ Title Left /--*/

.title-box-2 {
  margin-bottom: 3rem;
}

.title-left {
  font-size: 2rem;
  position: relative;
}

.title-left:before {
  content: '';
  position: absolute;
  height: 3px;
  background-color: #0078ff;
  width: 100px;
  bottom: -12px;
}

.work-box {
  margin-bottom: 3rem;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
  background-color: #fff;
}

.work-box:hover img {
  -webkit-transform: scale(1.3);
  transform: scale(1.3);
}

.work-img {
  display: block;
  overflow: hidden;
}

.work-img img {
  transition: all 1s;
}

.work-content {
  padding: 2rem 3% 1rem 4%;
}

.work-content .w-more {
  color: #4e4e4e;
  font-size: .8rem;
}

.work-content .w-more .w-ctegory {
  color: #0078ff;
}

.work-content .w-like {
  font-size: 2.5rem;
  color: #0078ff;
  float: right;
}

.work-content .w-like a {
  color: #0078ff;
}

.work-content .w-like .num-like {
  font-size: .7rem;
}

.w-title {
  font-size: 1.2rem;
}

.tarjetas {    
    display: flex;
    justify-content: space-between;
}

</style>