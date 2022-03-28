<template>
    <section class="dark">
	<div class="container py-4">
		<h1 class="h1 text-center" id="pageHeaderTitle">Mi Trayectoria Laboral</h1>

		<article class="postcard dark red">
			<a class="postcard__img_link" href="#">
				<img class="postcard__img" src="https://ushuaiacontenidos.com/wp-content/uploads/2018/03/logo-ok-1.png" alt="Image Title" />	
			</a>
			<div class="postcard__text">
				<h1 class="postcard__title red"><a href="#">Podcast Title</a></h1>
				<div class="postcard__subtitle small">
					<time datetime="2020-05-25 12:00:00">
						<i class="fas fa-calendar-alt mr-2"></i>Mon, May 25th 2020
					</time>
				</div>
				<div class="postcard__bar"></div>
				<div class="postcard__preview-txt">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eligendi, fugiat asperiores inventore beatae accusamus odit minima enim, commodi quia, doloribus eius! Ducimus nemo accusantium maiores velit corrupti tempora reiciendis molestiae repellat vero. Eveniet ipsam adipisci illo iusto quibusdam, sunt neque nulla unde ipsum dolores nobis enim quidem excepturi, illum quos!</div>
				<ul class="postcard__tagbox">
					<li class="tag__item"><i class="fas fa-tag mr-2"></i>Podcast</li>
					<li class="tag__item"><i class="fas fa-clock mr-2"></i>55 mins.</li>
					<li class="tag__item play red">
						<a href="#"><i class="fas fa-play mr-2"></i>Play Episode</a>
					</li>
				</ul>
			</div>
		</article>	        
	</div>
</section>
</template>


<style scoped>

/* Imagen de la carta */
.postcard__img{
    background-color: #ffffff;
    border-radius: 10px;
    padding: 30px;
}

/* Color del fondo */
.dark {
	background: #110f16;
}

/* Titulo de la empresa */
a,
a:hover {
	text-decoration: none;
	transition: color 0.3s ease-in-out;
}

#pageHeaderTitle {
	margin: 2rem 0;
	text-transform: uppercase;
	text-align: center;
	font-size: 2.5rem;
}

/* Cards */
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

/* COLORS */
.postcard .postcard__tagbox .green.play:hover {
	background: #79dd09 ;
	color: black;
}
.green .postcard__title:hover {
	color: #79dd09 ;
}
.green .postcard__bar {
	background-color: #79dd09 ;
}
.green::before {
	background-image: linear-gradient(
		-30deg,
		rgba(121, 221, 9, 0.1) ,
		transparent 50%
	);
}
.green:nth-child(2n)::before {
	background-image: linear-gradient(30deg, rgba(121, 221, 9, 0.1) , transparent 50%);
}

.postcard .postcard__tagbox .blue.play:hover {
	background: #0076bd ;
}
.blue .postcard__title:hover {
	color: #0076bd ;
}
.blue .postcard__bar {
	background-color: #0076bd ;
}
.blue::before {
	background-image: linear-gradient(-30deg, rgba(0, 118, 189, 0.1) , transparent 50%);
}
.blue:nth-child(2n)::before {
	background-image: linear-gradient(30deg, rgba(0, 118, 189, 0.1) , transparent 50%);
}

.postcard .postcard__tagbox .red.play:hover {
	background: #bd150b ;
}
.red .postcard__title:hover {
	color: #bd150b ;
}
.red .postcard__bar {
	background-color: #bd150b ;
}
.red::before {
	background-image: linear-gradient(-30deg, rgba(189, 21, 11, 0.1) , transparent 50%);
}
.red:nth-child(2n)::before {
	background-image: linear-gradient(30deg, rgba(189, 21, 11, 0.1) , transparent 50%);
}

.postcard .postcard__tagbox .yellow.play:hover {
	background: #bdbb49 ;
	color: black;
}
.yellow .postcard__title:hover {
	color: #bdbb49 ;
}
.yellow .postcard__bar {
	background-color: #bdbb49 ;
}
.yellow::before {
	background-image: linear-gradient(
		-30deg,
		rgba(189, 187, 73, 0.1) ,
		transparent 50%
	);
}
.yellow:nth-child(2n)::before {
	background-image: linear-gradient(
		30deg,
		rgba(189, 187, 73, 0.1) ,
		transparent 50%
	);
}

@media screen and (min-width: 769px) {
	.green::before {
		background-image: linear-gradient(
			-80deg,
			rgba(121, 221, 9, 0.1) ,
			transparent 50%
		);
	}
	.green:nth-child(2n)::before {
		background-image: linear-gradient(
			80deg,
			rgba(121, 221, 9, 0.1) ,
			transparent 50%
		);
	}

	.blue::before {
		background-image: linear-gradient(
			-80deg,
			rgba(0, 118, 189, 0.1) ,
			transparent 50%
		);
	}
	.blue:nth-child(2n)::before {
		background-image: linear-gradient(80deg, rgba(0, 118, 189, 0.1) , transparent 50%);
	}

	.red::before {
		background-image: linear-gradient(-80deg, rgba(189, 21, 11, 0.1) , transparent 50%);
	}
	.red:nth-child(2n)::before {
		background-image: linear-gradient(80deg, rgba(189, 21, 11, 0.1) , transparent 50%);
	}

	.yellow::before {
		background-image: linear-gradient(
			-80deg,
			rgba(189, 187, 73, 0.1) ,
			transparent 50%
		);
	}
	.yellow:nth-child(2n)::before {
		background-image: linear-gradient(
			80deg,
			rgba(189, 187, 73, 0.1) ,
			transparent 50%
		);
	}
}

</style>