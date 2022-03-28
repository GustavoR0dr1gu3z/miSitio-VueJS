<template>
    <section class="fontColor">
	<div class="container py-4">
		<h1 class="h1 text-center" id="pageHeaderTitle">Mi Trayectoria Laboral</h1>

		<article class="postcard">
			<a class="postcard__img_link">
				<img class="postcard__img" src="https://ushuaiacontenidos.com/wp-content/uploads/2018/03/logo-ok-1.png" alt="Ushuaia Contenidos" />	
			</a>
			<div class="postcard__text">
				<h1 class="postcard__title red">Ushuaia Contenidos</h1>
				<div class="postcard__subtitle small">
					<time datetime="2020-05-25 12:00:00">
						<i class="fas fa-calendar-alt mr-2">Lunes, 7 de Mayo del 2022</i>
                        <br><br>
					</time>
				</div>
				<div class="postcard__bar"></div>
				<div class="postcard__preview-txt">
                    Empresa que se encarga de redactar contenidos especializados en un área en específico.<br>     
                    <hr>
                    Mi cargo en Ushuaia Contenidos es: <br>
                    <ul>                    
                        - Mantenimiento de la aplicación web alojada en WordPress, en sus diferentes servicios que ofrecen la empresa. <br>
                        - Desarrollo de nuevas funcionalidades en la aplicación web. <br>
                        - Soporte técnico a los empleados de la empresa en remoto y presencial.
                    </ul>
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
    font-size: 18px;
    border-radius: 10px;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);        
}

/* Imagen de la carta */
.postcard__img{
    background-color: #ffffff;
    border-radius: 10px;
    padding: 30px;
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
	margin: 2rem 0;
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