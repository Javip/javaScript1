javaScript1
===========
<!DOCTYPE html>
<html leng="es">

<p> La hora es:<time> 00:51 </time></p>
<style type="text/css">
	body
	{
		background-color:#fff6f1;
		font-family:"Helvetica",Arial;
	}
	#contenido
	{
		width:960px;
		margin:0 auto;
		text-aling:center;
	}
	h1
	{
		color:#993300;
	}
	nav ul li
	{
		  display:inline-block;
		  margin-right:20px;
		  color:#1d1d1d;
		  cursor: pointer;
	}
	#text
	{
			width:600px;
			height:300px;
			background-color:#1d1d1d;
			color:#fff;
			margin:0 auto;
			text-align:left;
			border-radius:20px;
			padding:20px;
			box-shadow:0px 0px 20px rgba(0,0,0,2);
	}

	a
	{
		color:#99ff33;
		font-weight:bold;
	}
	#canvas
	{
		position: absolute;
		button:0px;
		left:0px;
		border:solid;	
	}
	meter
	{
		width:120px;
		margin-left:20px;
	}
	label
	{
		display:block;
	}
</style>
	<head>
		<meta charset='uft-8'>
	</head>
	<body>
		<div id="contenido">
			<header>
				<hgroup>
					<h1>Pagina Web en html5</h1>
				</hgroup>
			<nav>
				<ul>
					<li>Inicio</li>		
					<li>Contacto</li>
					<li>Media</li>				
				</ul>
			</nav>
			</header>
			<section>
				<div id="text">
					<hgroup>
						<h1>Contactanos<h1>
					</hgroup>
			        <form>
						<label for="nombre">Nombre</label>
						<input type="text" id="nombre" placeholder='Escribe tu nombre' required>

						<label for="mail">E-mail</label>
						<input type="email" id="mail" placeholder='Escribe tu email'>

						<label for="edad">Edad</label>
						<input type="number" id="edad" min='0'>

						<label for="calificacion">Calificacion</label>
						<input type="range" id="calificacion" min='0' max='10' value='0'>

						<label for="fecha">Fecha</label>
						<input type="date" id="fecha">
                        <input type="submit">
			</div>
			</section>			
		</div>
		<audio controls="controls"> 
		 <source src="audio.mp3" type="audio/mp3" />
		 <source src="">
		</audio>
		<footer>	 
		</footer>
		<input list='canales'/>
		<datalist id='canales'>
		  <option value='Php'/>
		  <option value='Html'/>
		</datalist>
		<details>
			<summary>Programacion</summary>
				Etiquetas de html5
		</details>
		<p> <figure> Se da como un enter a la 
			<img src='imagen.jpg'/>	
		</figure>imagen, se pueden hacer listas</p>		
		<p>Programacion web en <mark>html5</mark></p>

		<form oninput="result.value=parseInt(x.value) + parseInt(y.value)">
			<input type="number" name="x"/>
			<input type="number" name="y"/>
			<output name="result" for="x y"></output>
		</form>
		<progress value="50" max='100'>	
         tu navegador no soporta este control		
		</progress>
		<video width='320' height='240' controls="controls" poster='imagen.jpg'>
		<source src="video.mp4" type="video/mp4"/>
		tu navergador no e scompatible con html5
		</video>
	</body>
</html>
