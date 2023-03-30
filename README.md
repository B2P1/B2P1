### Hi there 👋

<!--
**B2P1/B2P1** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html>
<html>
<head>
	<meta charset="UTF-8">
	<title>Plateforme de services de bâtiment</title>
	<!-- intégrer les styles CSS ici -->
	<link rel="stylesheet" href="styles.css">
</head>
<body>
	<header>
		<!-- logo et lien vers la page d'accueil -->
		<a href="index.html"><img src="logo.png" alt="Plateforme de services de bâtiment"></a>

		<!-- barre de recherche -->
		<form>
			<input type="text" placeholder="Rechercher...">
			<button type="submit">Rechercher</button>
		</form>

		<!-- filtres -->
		<div class="filters">
			<label for="location">Emplacement :</label>
			<select id="location">
				<option value="paris">Paris</option>
				<option value="lyon">Lyon</option>
				<option value="marseille">Marseille</option>
			</select>

			<label for="service">Service :</label>
			<select id="service">
				<option value="plomberie">Plomberie</option>
				<option value="menuiserie">Menuiserie</option>
				<option value="electricite">Électricité</option>
			</select>

			<label for="rating">Avis :</label>
			<select id="rating">
				<option value="5">5 étoiles</option>
				<option value="4">4 étoiles et plus</option>
				<option value="3">3 étoiles et plus</option>
			</select>
		</div>
	</header>

	<main>
		<!-- images présentant les différents types de services -->
		<div class="services">
			<img src="salledebain.jpg" alt="Service de salle de bain">
			<img src="renovation.jpg" alt="Service de rénovation">
			<img src="isolation.jpg" alt="Service d'isolation">
		</div>

		<!-- liste des ouvriers du bâtiment avec leur nom, leur service et leur emplacement -->
		<ul class="workers">
			<li>
				<h2>Nom de l'ouvrier 1</h2>
				<p>Service : Plomberie</p>
				<p>Emplacement : Paris</p>
			</li>
			<li>
				<h2>Nom de l'ouvrier 2</h2>
				<p>Service : Menuiserie</p>
				<p>Emplacement : Lyon</p>
			</li>
			<li>
				<h2>Nom de l'ouvrier 3</h2>
				<p>Service : Électricité</p>
				<p>Emplacement : Marseille</p>
			</li>
		</ul>
	</main>

	<footer>
		<!-- lien vers les mentions légales -->
		<a href="mentions_legales.html">Mentions légales</a>
	</footer>
</body>
</html>
