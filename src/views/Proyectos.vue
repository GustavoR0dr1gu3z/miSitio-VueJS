<template>
    <section class="fontColor">
	<div class="container py-4">
		<h1 class="h1 text-center" id="pageHeaderTitle">Mis Proyectos</h1>

		<article class="postcard">
			<a class="postcard__img_link">
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