<template>
    <div id="nav">
        <section class="paralax-mf footer-paralax bg-image sect-mt4 route" style="background-image: url(img/overlay-bg.jpg)">
        <div class="overlay-mf"></div>
        <div class="container">
        <div class="row">
            <div class="col-sm-12">
            <div class="contact-mf">
                <div id="contact" class="box-shadow-full">
                <div class="row">
                    <div class="col-md-6">
                    <div class="title-box-2">
                        <h5 class="title-left">
                        ¡Enviame un  Mensaje!
                        </h5>
                    </div>
                    <div>


                    </div>
                    </div>
                    <div class="col-md-6">
                        <div class="title-box-2 pt-4 pt-md-0">
                        <h5 class="title-left">
                        Ponerse en contacto
                        </h5>
                    </div>
                    <div class="more-info">
                        <p class="lead">
                        Si tiene alguna duda acerca de lo que realizo, mande mensaje le responderé lo más pronto posible, de igual forma si requiere de mi servicio no dude en contactarme.
                        </p>
                        <ul class="list-ico">
                        <li><span class="ion-ios-location"></span> San Juan Zitlaltepec, Zumpango. Estado de México</li>
                        <li><span class="ion-ios-telephone"></span> (+52) 5611290464</li>
                        <li><span class="ion-email"></span> gustavo.soader.cx@gmail.com</li>
                        </ul>
                    </div>
                    <div class="socials">
                        <ul>
                        <li><a href="https://www.facebook.com/Gustavo.Calzada1710"><span class="ico-circle"><i class="ion-social-facebook"></i></span></a></li>
                        <li><a href="https://www.instagram.com/gustavo_calzada/?hl=es-la"><span class="ico-circle"><i class="ion-social-instagram"></i></span></a></li>
                        <li><a href="https://twitter.com/GustavoCal17"><span class="ico-circle"><i class="ion-social-twitter"></i></span></a></li>
                        <li><a href="https://github.com/GustavoR0dr1gu3z"><span class="ico-circle"><i class="ion-social-github"></i></span></a></li>
                        <li><a href="https://www.youtube.com/channel/UC6jTSoykQbaNwTI5VlEptvw?view_as=subscriber"><span class="ico-circle"><i class="ion-social-youtube"></i></span></a></li>
                        <li><a href="https://www.linkedin.com/in/gustavo-rodriguez-calzada-9a0720196/"><span class="ico-circle"><i class="ion-social-linkedin"></i></span></a></li>
                        </ul>
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

/*Parrafos*/
.title-box-2 {
  margin-bottom: 3rem;
}

/*Titulos*/
.title-left {
  font-size: 2rem;
  position: relative;
}

/*Linea debajo de los titulos */
.title-left:before {
  content: '';
  position: absolute;
  height: 3px;
  background-color: #0078ff;
  width: 100px;
  bottom: -12px;
}

/*Carta donde se ubica el formulario*/
.box-shadow-full {
  padding: 3rem 1.25rem;
  position: relative;
  background-color:#FEF7E4;
  margin-bottom: 3rem;
  z-index: 2;
  box-shadow: 0 1px 1px 0 rgba(0, 0, 0, 0.06), 0 2px 5px 0 rgba(0, 0, 0, 0.2);
}

/*Circulos de las redes sociales*/
.socials {
  padding: 1.5rem 0;
}

/*Orientación de las redes sociales*/
.socials ul li {
  display: inline-block;
}
/*Icono en circulo de las RS*/
.socials .ico-circle {
  height: 40px;
  width: 40px;
  font-size: 1.7rem;
  border-radius: 50%;
  line-height: 1.4;
  margin: 0 15px 0 0;
  box-shadow: 0 0 0 3px #0078ff;
  transition: all 500ms ease;
}

/*Over de las RS*/
.socials .ico-circle:hover {
  background-color: #0078ff;
  color: #fff;
  box-shadow: 0 0 0 3px #cde1f8;
  transition: all 500ms ease;
}

/*Estilo a las listas*/
.ul-resect,
.socials ul,
.list-ico,
.blog-wrapper .post-meta ul,
.box-comments .list-comments,
.widget-sidebar .list-sidebar,
.widget-tags ul {
  list-style: none;
  padding-left: 0;
  margin-bottom: 0;
}

/*Espacio entre listas*/
.list-ico {
  line-height: 2;
}

/*Tabulacion a las listas*/
.list-ico span {
  color: #0078ff;
  margin-right: 10px;
}

/*Circulo de las RS*/
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

/*Contacto cartas*/
.footer-paralax {
  padding: 4rem 0 0 0;
}

.contact-mf {
  margin-top: 4rem;
}

@media (min-width: 577px) {
  .counter-box {
    margin-bottom: 1.8rem;
  }
}

@media (min-width: 767px) {
  .about-mf .box-pl2 {
    margin-top: 3rem;
    padding-left: 0rem;
  }

  .card-blog {
    margin-bottom: 3rem;
  }

  .contact-mf .box-pl2 {
    margin-top: 3rem;
    padding-left: 0rem;
  }
}

@media (min-width: 768px) {
  .box-shadow-full {
    padding: 3rem;
  }
}

@media (min-width: 992px) {
}

@media (min-width: 1200px) {

}

@media (max-width: 1024px) {

}

@media (max-width: 768px) {
  .back-to-top {
    bottom: 15px;
  }
}


</style>