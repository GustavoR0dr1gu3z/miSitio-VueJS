<template>
    <section class="fontColor">
	<div class="container py-4">
		<h1 class="h1 text-center" id="pageHeaderTitle">Mis Proyectos</h1>

		<article class="postcard">
			<a href="https://github.com/GustavoR0dr1gu3z/testServidores" class="postcard__img_link" v>
				<img class="postcard__img" src="https://i0.wp.com/codeblog.dotsandbrackets.com/wp-content/uploads/2018/01/test-server-goss.jpg?fit=709%2C487&ssl=1" alt="Servidores" />	
			</a>
			<div class="postcard__text">
				<h1 class="postcard__title red">Verificación de servidores activos en VueJS</h1>
				<div class="postcard__subtitle small">
					<time datetime="2020-05-25 12:00:00">
						<i class="fas fa-calendar-alt mr-2">04/Marzo/2022</i>
                        <br><br>
					</time>
				</div>
				<div class="postcard__bar"></div>
				<div class="postcard__preview-txt">
          Página web hecha en VueJS, donde recibo un archivo JSON de los estados activos o inactivos de los servidores para mostrarlos, así mismo para agregar nuevos servidores o eliminarlos, con un nombre y status especifico.<br> 
          Como ejercicio práctico hice que los servidores se activen y desactiven aleatoriamente, dejando de color rojo los servidores inactivos y verde los activos, esto gracias a las condiciones de clases.
        </div>

			</div>
		</article>	        

    <article class="postcard">
			<a href="https://github.com/GustavoR0dr1gu3z/webService-USD_To_MXN" class="postcard__img_link" v>
				<img class="postcard__img" src="https://coinyep.com/img/share/MXN-USD.png" alt="USD-MXN" />	
			</a>
			<div class="postcard__text">
				<h1 class="postcard__title red">Convertidor de USD a MXN en VueJS</h1>
				<div class="postcard__subtitle small">
					<time datetime="2020-05-25 12:00:00">
						<i class="fas fa-calendar-alt mr-2">24/Febrero/2022</i>
                        <br><br>
					</time>
				</div>
				<div class="postcard__bar"></div>
				<div class="postcard__preview-txt">
          Aplicación web en donde se consumen 3 API's de bancos (Banxico, Diario Oficial de Federación, Fixer) para la conversión de moneda de USD a MXN, actualizandose cada vez que el banco lo haga, mostrando día/mes/año y hasta hora en que fue actualizada por última vez. <br>
          Se le colocó botones a las cartas para mostrar la moneda actual, ya que si se actualizaban automaticamente, se excedía el numero de peticiones y tendría que obtener otro Tóken, ya que son API's de paga.
          En la API de Banxico se usó el termino de Web Scrapping, ya que mostraba los datos en una página y no en JSON, entonces obtenía el último valor que subían, para colocarlos en mi página web.
        </div>

			</div>
		</article>	

    		<article class="postcard">
			<a href="https://github.com/GustavoR0dr1gu3z/CarritoDeCompras-Vue" class="postcard__img_link" v>
				<img class="postcard__img" src="https://octopus.mx/wp-content/uploads/2019/05/comprar-en-el-carrito-de-compra.jpg" alt="Compras" />	
			</a>
			<div class="postcard__text">
				<h1 class="postcard__title red">Carrito de Compras en VueJS</h1>
				<div class="postcard__subtitle small">
					<time datetime="2020-05-25 12:00:00">
						<i class="fas fa-calendar-alt mr-2">23/Enero/2022</i>
                        <br><br>
					</time>
				</div>
				<div class="postcard__bar"></div>
				<div class="postcard__preview-txt">
          Página web realizada en VueJS, en donde el usuario se tiene que loggear a nuestra aplicación, si es un usuario normal, se le dirige a una página en donde encuentra un catálogo de productos (API), puede agregar los productos que desea al carrito, así mismo de cuantos requiere de cada uno, para hacer su cotización. <br>
          Si se loggean como administrador, le aparece otra pantalla donde tiene el control de los usuarios (CRUD).<br>
          Esta aplicación cuenta con ser una WPA (Web Progressive Application)

        </div>

			</div>
		</article>	

    		<article class="postcard">
			<a href="https://github.com/GustavoR0dr1gu3z/API-REST-Web-Service-con-Python-y-MySQL" class="postcard__img_link" v>
				<img class="postcard__img" src="https://miro.medium.com/max/702/1*BBa6MflsOYrWc_8cNa2-3g.png" alt="API-Rest Python" />	
			</a>
			<div class="postcard__text">
				<h1 class="postcard__title red"> API-REST Web-Service con Python y MySQL</h1>
				<div class="postcard__subtitle small">
					<time datetime="2020-05-25 12:00:00">
						<i class="fas fa-calendar-alt mr-2">21/Diciembre/2021</i>
                        <br><br>
					</time>
				</div>
				<div class="postcard__bar"></div>
				<div class="postcard__preview-txt">
          Curso de Udemy, en donde se realiza una web service hecha en Python, utilizando el software de PostMan, para los consumos y creaciones de las API corriendolo en un entorno virtual y utilizando como base de datos: SQL  
        </div>

			</div>
		</article>	

    <article class="postcard">
			<a href="https://github.com/GustavoR0dr1gu3z/UNAMxHack" class="postcard__img_link" v>
				<img class="postcard__img" src="https://i.ytimg.com/vi/OhnxU8xALtg/maxresdefault.jpg" alt="ArduinoHC05" />	
			</a>
			<div class="postcard__text">
				<h1 class="postcard__title red">App Control de Secuencias de Leds Usando un Modulo Bluetooth HC05</h1>
				<div class="postcard__subtitle small">
					<time datetime="2020-05-25 12:00:00">
						<i class="fas fa-calendar-alt mr-2">25/Mayo/2021</i>
                        <br><br>
					</time>
				</div>
				<div class="postcard__bar"></div>
				<div class="postcard__preview-txt">                    
                    Aplicación movil realizada en el software Android Studio, esta aplicación se conecta a un Módulo Bluetooth de Arduino HC05, esto para mostrar una secuencia de leds, dependiendo del botón que se seleccione en nuestro telefono celular, hará una acción en las secuencias de leds.
        </div>

			</div>
		</article>	

<article class="postcard">
			<a href="https://github.com/GustavoR0dr1gu3z/UNAMxHack" class="postcard__img_link" v>
				<img class="postcard__img" src="https://gustavor0dr1gu3z.github.io/img/difusion.png" alt="Ushuaia Contenidos" />	
			</a>
			<div class="postcard__text">
				<h1 class="postcard__title red">Página web realizada en UNAMxHacks</h1>
				<div class="postcard__subtitle small">
					<time datetime="2020-05-25 12:00:00">
						<i class="fas fa-calendar-alt mr-2">26/Octubre/2019</i>
                        <br><br>
					</time>
				</div>
				<div class="postcard__bar"></div>
				<div class="postcard__preview-txt">
                    Página web donde nosotros impartimos cultura de toda la república mexicana, anexandop dicho mapa y dividiendo los estados en botones, y cada uno de ellos tendrá información (Monumentos importantes, Datos interesantes) así como una imagen que deberá ser escaneada con una aplicación móvil que realizamos, y se verá en realidad aumentada. <br> Además contiene un audiolibro para la fácil lectura de algunas personas.
        </div>

			</div>
		</article>	

<article class="postcard">
			<a href="https://github.com/GustavoR0dr1gu3z/UNAMxHack" class="postcard__img_link" v>
				<img class="postcard__img" src="https://gustavor0dr1gu3z.github.io/img/difusion.png" alt="Ushuaia Contenidos" />	
			</a>
			<div class="postcard__text">
				<h1 class="postcard__title red">Página web realizada en UNAMxHacks</h1>
				<div class="postcard__subtitle small">
					<time datetime="2020-05-25 12:00:00">
						<i class="fas fa-calendar-alt mr-2">26/Octubre/2019</i>
                        <br><br>
					</time>
				</div>
				<div class="postcard__bar"></div>
				<div class="postcard__preview-txt">
                    Página web donde nosotros impartimos cultura de toda la república mexicana, anexandop dicho mapa y dividiendo los estados en botones, y cada uno de ellos tendrá información (Monumentos importantes, Datos interesantes) así como una imagen que deberá ser escaneada con una aplicación móvil que realizamos, y se verá en realidad aumentada. <br> Además contiene un audiolibro para la fácil lectura de algunas personas.
        </div>

			</div>
		</article>	

<article class="postcard">
			<a href="https://github.com/GustavoR0dr1gu3z/UNAMxHack" class="postcard__img_link" v>
				<img class="postcard__img" src="https://gustavor0dr1gu3z.github.io/img/difusion.png" alt="Ushuaia Contenidos" />	
			</a>
			<div class="postcard__text">
				<h1 class="postcard__title red">Página web realizada en UNAMxHacks</h1>
				<div class="postcard__subtitle small">
					<time datetime="2020-05-25 12:00:00">
						<i class="fas fa-calendar-alt mr-2">26/Octubre/2019</i>
                        <br><br>
					</time>
				</div>
				<div class="postcard__bar"></div>
				<div class="postcard__preview-txt">
                    Página web donde nosotros impartimos cultura de toda la república mexicana, anexandop dicho mapa y dividiendo los estados en botones, y cada uno de ellos tendrá información (Monumentos importantes, Datos interesantes) así como una imagen que deberá ser escaneada con una aplicación móvil que realizamos, y se verá en realidad aumentada. <br> Además contiene un audiolibro para la fácil lectura de algunas personas.
        </div>

			</div>
		</article>	

<article class="postcard">
			<a href="https://github.com/GustavoR0dr1gu3z/UNAMxHack" class="postcard__img_link" v>
				<img class="postcard__img" src="https://gustavor0dr1gu3z.github.io/img/difusion.png" alt="Ushuaia Contenidos" />	
			</a>
			<div class="postcard__text">
				<h1 class="postcard__title red">Página web realizada en UNAMxHacks</h1>
				<div class="postcard__subtitle small">
					<time datetime="2020-05-25 12:00:00">
						<i class="fas fa-calendar-alt mr-2">26/Octubre/2019</i>
                        <br><br>
					</time>
				</div>
				<div class="postcard__bar"></div>
				<div class="postcard__preview-txt">
                    Página web donde nosotros impartimos cultura de toda la república mexicana, anexandop dicho mapa y dividiendo los estados en botones, y cada uno de ellos tendrá información (Monumentos importantes, Datos interesantes) así como una imagen que deberá ser escaneada con una aplicación móvil que realizamos, y se verá en realidad aumentada. <br> Además contiene un audiolibro para la fácil lectura de algunas personas.
        </div>

			</div>
		</article>	

        
	</div>
</section>

</template>


<style scoped>

/* Diseño de la carta */
.postcard{
    margin-top: 5%;
    margin-left: 5%;
    border: 1px solid rgb(142, 209, 221);
    background-color: #a1d0db;
    color: black;
    text-align: left;
    font-size: 16px;
    border-radius: 10px;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);        
}

/* Imagen de la carta */
.postcard__img{
    background-color: #ffffff;
    border-radius: 10px;
    width: 100%;
    height: 100%;
}

/* Color del fondo 
.fontColor {
	background: #8879ad;
}
*/

/* Titulo de la empresa */
 .postcard__title{
    color: #142a2e;
    font-size: 30px;
    font-weight: bold;
    margin-bottom: 10px;
    text-align: left;
}

.postcard__preview-txt, .fas{
    color: #142a2e;
    font-weight: bold;
    margin-bottom: 10px;
    text-align: left;
}

/* Titulo de MI TRAYECTORIA LABORAL */
#pageHeaderTitle {
	
	text-transform: uppercase;
	text-align: center;
	font-size: 2.5rem;
    color: #310b0b;
    font-size: 2.5rem;
    font-weight: 700;
    text-align: center;
    margin-bottom: 2rem;
}

/* Cartas */
.postcard {
	flex-wrap: wrap;
	display: flex;
	box-shadow: 0 4px 21px -12px rgba(0, 0, 0, 0.66);
	border-radius: 10px;
	margin: 0 0 2rem 0;
	overflow: hidden;
	position: relative;
	color: #ffffff;
}

@media screen and (min-width: 769px) {
	.postcard {
		flex-wrap: inherit;
	}
}

@media screen and (min-width: 1024px) {
	.postcard__text {
		padding: 2rem 3.5rem;
	}
}


</style>