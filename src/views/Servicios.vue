<template>
    <div id="nav">
        <section id="service" class="services-mf route">
            <div class="container">
            <div class="row">
                <div class="col-sm-12">
                <div class="title-box text-center">
                    <h3 class="title-a">
                    Servicios
                    </h3>
                    <p class="subtitle-a">
                    Si tiene duda alguna o requiera algún servicio de los que se presentan a continuación, no dude en contactarme  
                    </p>
                    
                    <div class="line-mf"></div>
                </div>
                </div>
            </div>
            <div class="row">
                <div class="col-md-4">
                <div class="service-box">
                    <div class="service-ico">
                    <span class="ico-circle"><i class="bi bi-display"></i></span>
                    </div>
                    <div class="service-content">
                    <h2 class="s-title">Diseño Web</h2>
                    <p class="s-description text-center">
                    </p>
                    </div>
                </div>
                </div>
                
                <div class="col-md-4">
                <div class="service-box">
                    <div class="service-ico">
                    <span class="ico-circle"><i class="bi bi-file-earmark-code-fill"></i></span>
                    </div>
                    <div class="service-content">
                    <h2 class="s-title">Desarrollo Web</h2>
                    <p class="s-description text-center">
                    </p>
                    </div>
                </div>
                </div>


                <div class="col-md-4">
                <div class="service-box">
                    <div class="service-ico">
                    <span class="ico-circle"><i class="bi bi-hammer"></i></span>
                    </div>
                    <div class="service-content">
                    <h2 class="s-title">Mantenimiento de aplicaciones web</h2>
                    <p class="s-description text-center">
                    </p>
                    </div>
                </div>
                </div>


                <div class="col-md-4">
                <div class="service-box">
                    <div class="service-ico">
                    <span class="ico-circle"><i class="bi bi-phone"></i></span>
                    </div>
                    <div class="service-content">
                    <h2 class="s-title">Aplicaciones Móviles</h2>
                    <p class="s-description text-center">
                    </p>
                    </div>
                </div>
                </div>
                
                <div class="col-md-4">
                <div class="service-box">
                    <div class="service-ico">
                    <span class="ico-circle"><i class="bi bi-gear"></i></span>
                    </div>
                    <div class="service-content">
                    <h2 class="s-title">Mantenimiento de Computadoras</h2>
                    <p class="s-description text-center">
                    </p>
                    </div>
                </div>
                </div>


                <div class="col-md-4">
                <div class="service-box">
                    <div class="service-ico">
                    <span class="ico-circle"><i class="bi bi-pc-display-horizontal"></i></span>
                    </div>
                    <div class="service-content">
                    <h2 class="s-title">Aplicaciones de Escritorio</h2>
                    <p class="s-description text-center">
                    </p>
                    </div>
                </div>
                </div>
            </div>
            </div>
        </section>
    </div>
</template>

<style scoped>

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

.ico-circle {
  height: 100px;
  width: 100px;
  font-size: 2rem;
  border-radius: 50%;
  line-height: 1.55;
  margin: 0 auto;
  text-align: center;
  box-shadow: 0 0 0 10px #0078ff;
  display: block;
}
.service-box {
  background-color: #fff;
  padding: 2rem 1rem;
  border-radius: 1rem;
  margin-bottom: 3rem;
}

.service-box:hover .ico-circle {
  transition: all 500ms ease;
  color: #fff;
  background-color: #0078ff;
  box-shadow: 0 0 0 10px #cde1f8;
}

.service-box .service-ico {
  margin-bottom: 1rem;
  color: #1e1e1e;
}

.service-box .ico-circle {
  transition: all 500ms ease;
  font-size: 4rem;
}

.service-box .s-title {
  font-size: 1.4rem;
  text-transform: uppercase;
  text-align: center;
  padding: .4rem 0;
}

.service-box .s-description {
  color: #4e4e4e;
}


</style>