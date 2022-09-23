<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Raleway:wght@300;400;500;600;700;800;900&display=swap"
	   rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.2/css/all.css">
    <link rel="stylesheet" href="css/normalize.css" />
    <link rel="stylesheet" href="css/style.css" />
    <link rel="stylesheet" href="css/media.css" />
    <title>Booki</title>
</head>
<body>
	<header>
    	<img class="logo" src="Images/logo/Booki.png" alt="logo">
		<nav>
	   		<ul>
		  		<li class="menu"><a href="#hebergements">Hébergements</a></li>
		  		<li class="menu"><a href="#activites">Activités</a></li>
	   		</ul>
    	</nav>
	</header>
	<main>
	   <div class="formulaire">
			<div>
		  		<h2 class="titre">Trouvez votre hébergement pour des vacances de rêve</h2>
		  		<p class="titre" >En plein centre ville ou en pleine nature</p>
			</div>
	  	    <form>
				<div class="rechercher">
					<i class="fas fa-map-marker-alt"></i>
					<input type="text" id="Ville" name="Ville" placeholder="Marseille, France">
					<button class="rechercher" type="submit" id="rechercher" name="Rechercher">
						<span class="text">Rechercher</span>
						<span class="icone"><i class="fas fa-search"></i></span>
					</button>
				</div>
			 	<div class="filtres">
					<h4>Filtres</h4> 
					<button><i class="fas fa-money-bill-wave-alt"></i>Economique</button>
					<button><i class="fas fa-child"></i>Familial</button>
					<button><i class="fas fa-heart"></i>Romantique</button>
					<button><i class="fas fa-dog"></i>Animaux autorisés</button>
				</div>
		  </form>      
		  <div class="info">
			 	<p><i class="fas fa-info"></i></p>
			 	<p>Plus de 500 logements sont disponibles dans cette ville</p>
		  </div>
	   </div>
	   <article id="hebergements">
			<h2>Hébergements à Marseille</h2>
			<div class="album_hebergements">
				<div class="element">
					<a href="#">
				    <img src="Images/hebergements/3_medium/marcus-loke-WQJvWU_HZFo-unsplash.jpg" alt="Auberbe La Cannebière">
				    <h3>Auberbe La Cannebière</h3>
				    <p>Nuit à partir de 25 €</p>
				    <p class="rating">
					   <i class="fa-solid fa-star blue_star"></i>
					   <i class="fa-solid fa-star blue_star"></i>
					   <i class="fa-solid fa-star blue_star"></i>
					   <i class="fa-solid fa-star blue_star"></i>
					   <i class="fa-solid fa-star grey_star"></i>
				    </p> 
					</a>    
				</div>   
		  		<div class="element">
			 		<a href="#">
					<img src="Images/hebergements/3_medium/fred-kleber-gTbaxaVLvsg-unsplash.jpg" alt="Hôtel du port">
					<h3>Hôtel du port</h3>
					<p>Nuit à partir de 52 €</p>
					<p class="rating">
				    	<i class="fa-solid fa-star blue_star"></i>
				   		<i class="fa-solid fa-star blue_star"></i>
				   		<i class="fa-solid fa-star blue_star"></i>
				    	<i class="fa-solid fa-star blue_star"></i>
				    	<i class="fa-solid fa-star blue_star"></i>
					</p>
			 		</a>
		  		</div>
		  		<div class="element">
			 		<a href="#">
					<img src="Images/hebergements/3_medium/reisetopia-B8WIgxA_PFU-unsplash.jpg" alt="Hôtel Les mouettes">
					<h3>Hôtel Les mouettes</h3>
					<p>Nuit à partir de 76 €</p>
					<p class="rating">
				    <i class="fa-solid fa-star blue_star"></i>
				    <i class="fa-solid fa-star blue_star"></i>
				    <i class="fa-solid fa-star blue_star"></i>
				    <i class="fa-solid fa-star blue_star"></i>
				    <i class="fa-solid fa-star grey_star"></i>
					</p>
			 		</a>
		  		</div>
		  		<div class="element">
			 		<a href="#">
					<img src="Images/hebergements/3_medium/annie-spratt-Eg1qcIitAuA-unsplash.jpg" alt="Hôtel de la mer">
					<h3>Hôtel de la mer</h3>
					<p>Nuit à partir de 46 €</p>
					<p class="rating">
				    <i class="fa-solid fa-star blue_star"></i>
				    <i class="fa-solid fa-star blue_star"></i>
				    <i class="fa-solid fa-star blue_star"></i>
				    <i class="fa-solid fa-star grey_star"></i>
				    <i class="fa-solid fa-star grey_star"></i>
					</p>
			 		</a>
		  		</div>    
		  		<div class="element">
			 		<a href="#">
					<img src="Images/hebergements/3_medium/nicate-lee-kT-ZyaiwBe0-unsplash.jpg" alt="Auberge le Panier">
					<h3>Auberge le Panier</h3>
					<p>Nuit à partir de 23 €</p>
					<p class="rating">
				    <i class="fa-solid fa-star blue_star"></i>
				    <i class="fa-solid fa-star blue_star"></i>
				    <i class="fa-solid fa-star blue_star"></i>
				    <i class="fa-solid fa-star blue_star"></i>
				    <i class="fa-solid fa-star grey_star"></i>
					</p>
			 		</a>
		  		</div>
		  		<div class="element">
					<a href="#">
					<img src="Images/hebergements/3_medium/febrian-zakaria-M6S1WvfW68A-unsplash.jpg" alt="Hôtel chez Amina">
					<h3>Hôtel chez Amina</h3>
					<p>Nuit à partir de 96 €</p>
					<p class="rating">
				    <i class="fa-solid fa-star blue_star"></i>
				    <i class="fa-solid fa-star blue_star"></i>
				    <i class="fa-solid fa-star blue_star"></i>
				    <i class="fa-solid fa-star blue_star"></i>
				    <i class="fa-solid fa-star blue_star"></i>
					</p>
			 		</a>
		  		</div>
	   		</div>
		  	<p class="plus"> <a href="#">Afficher plus</a></p> 
    	</article>
		<aside id="populaires">
	   		<div class="titretoil">
		  		<h2 class="titretoil">Les plus populaires</h2>
		  		<p><i class="fas fa-star"></i></p>
	   		</div>
	   		<div class="album_populaires">
		    	<div class="element">
			 		<a href="#">
			 			<img src="Images/hebergements/4_small/emile-guillemot-Bj_rcSC5XfE-unsplash.jpg" alt="Hôtel Le soleil du matin">
			 			<div class="description">
							<div class="titre_prix">
								<h3>Hôtel Le soleil du matin</h3>
				    			<p>Nuit à partir de 128 €</p> 
							</div>
							<div class="rating">
				    			<i class="fa-solid fa-star blue_star"></i>
				   				<i class="fa-solid fa-star blue_star"></i>
				    			<i class="fa-solid fa-star blue_star"></i>
				    			<i class="fa-solid fa-star blue_star"></i>
				    			<i class="fa-solid fa-star blue_star"></i>
							</div>
						</div>
					</a>
				</div>
				<div class="element">
					<a href="#">
			 			<img src="Images/hebergements/4_small/aw-creative-VGs8z60yT2c-unsplash.jpg" alt="Au coeur de l'eau Chambres d'hôtes">
			 			<div class="description">
							<div class="titre_prix">
				    			<h3>Au coeur de l'eau Chambres d'hôtes</h3>
				    			<p>Nuit à partir de 71 €<p>
							</div>
							<div class="rating">
				    			<i class="fa-solid fa-star blue_star"></i>
				    			<i class="fa-solid fa-star blue_star"></i>
				    			<i class="fa-solid fa-star blue_star"></i>
				    			<i class="fa-solid fa-star blue_star"></i>
				    			<i class="fa-solid fa-star grey_star"></i>
							</div>
						</div>
					</a> 
				</div> 
		  		<div class="element">
					<a href="#">
			 			<img src="Images/hebergements/4_small/febrian-zakaria-sjvU0THccQA-unsplash.jpg" alt="Hôtel tout bleu et blanc">
						<div class="description">
							<div class="titre_prix">
				    			<h3>Hôtel tout bleu et blanc</h3>
				    			<p>Nuit à partir de 68 €</p>
							</div>
							<div class="rating">
				    			<i class="fa-solid fa-star blue_star"></i>
				    			<i class="fa-solid fa-star blue_star"></i>
				    			<i class="fa-solid fa-star blue_star"></i>
				    			<i class="fa-solid fa-star blue_star"></i>
				   				<i class="fa-solid fa-star grey_star"></i>
							</div> 
					</div>
		 		</a>
	   		</div> 
		</div> 
	</aside>
    <div class="activites" id="activites">
			<h2>Activités à Marseille</h2>
			<div class="album_activites">
				<div class="element full">
					<div class="photo">
					  <img src="Images/activites/2_large/reno-laithienne-QUgJhdY5Fyk-unsplash.jpg" alt="Vieux Port">
					  <h3>Vieux Port</h3>
					</div>
				</div>
				<div class="element bigger">
					<div class="photo">
						<img src="Images/activites/3_medium/paul-hermann-QFTrLdQIRhI-unsplash.jpg" alt="Fort de Pomègues">
						<h3>Fort de Pomègues</h3>
					</div>
				</div>
				<div class="element smaller">
					<div class="photo">
					 	<img src="Images/activites/3_medium/kevin-hikari-rV_Qd1l-VXg-unsplash.jpg" alt="Iles de Frioul">
						 <h3>Iles de Frioul</h3>
					</div>
				</div>
				<div class="element full">
					<div class="photo">
					 	<img src="Images/activites/2_large/kilyan-sockalingum-NR8-cBCN3aI-unsplash.jpg" alt="Parc National des Calanques">
						 <h3>Parc National des Calanques</h3>
					</div>
				</div>
				<div class="element smaller">
					<div class="photo">
						<img src="Images/activites/2_large/florian-wehde-xW9e8gdotxI-unsplash.jpg" alt="Notre-Dame-de-Garde">
						<h3>Notre-Dame-de-Garde</h3>
					</div>
				</div>
				<div class="element bigger">
					<div class="photo">
						<img src="Images/activites/3_medium/lena-paulin-wH2-EJoDcV0-unsplash.jpg" alt="Parc Longchamp">
						<h3>Parc Longchamp</h3>
					</div>	
				</div>
			</div>
		</div>
	</main>

	<footer>
    	<div class="footul">
			<h4>A propos</h4>
			<ul>
		  		<li><a href="">Fonctionnement du site</a></li>
		  		<li><a href="">Conditions générales de vente</a></li>
		  		<li><a href="">Données et confidentialité</a></li>
	   		</ul>
    	</div>
    	<div class="footul">
			<h4>Nos hébergements</h4>
	   		<ul>
			   <li><a href="">Charte qualité</a></li>
		  	   <li><a href="">Soumettre votre hôtel</a></li>
	   		</ul>
    	</div>
    	<div class="footul">
			<h4>Assistance</h4>
	   		<ul>
		  		<li><a href="">Centre d'aide</a></li>
		  		<li><a href="mailto:email">Nous contacter</a></li>
	   		</ul>
		</div>
		<div class="hidden">
	   		<ul>
		 		<li><a href="http://jigsaw.w3.org/css-validator/check/referer">
					<img style="border:0;width:88px;height:31px"
					src="http://jigsaw.w3.org/css-validator/images/vcss-blue"
					alt="CSS Valide !" />
			 		</a>
				</li>
		 		<li><a href="https://github.com/lysianebo/LBO">Github</a></li>
			</ul>
    	</div>
	</footer>
</body>
</html>

