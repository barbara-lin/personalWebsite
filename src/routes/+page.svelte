<script>
	export let name;
	//import './styles.css';
</script>


<main>    

	<h1>Barbara Lin</h1>
	
	<h2>
		"for what is a map but a way of emphasizing some things and making others invisible?"
	</h2>

	<div class="backWall">
	</div>
	
</main>


<body>
</body>



'<!--css style section-->'

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	body {
	}

	h1 {
		color: #d4880c;
		text-transform: uppercase;
		font-size: 45em;
		font-family:Georgia, 'Times New Roman', Times, serif;
		font-weight: 900;
		font-stretch: 125%;
		padding: 0;
	}

	h2 {
		color:rgb(208, 157, 39);
		text-decoration-thickness: 10em;
		font-stretch: 90%;
		text-transform:uppercase;
		font-size: 6em;
	}

	.backWall {
    position: absolute;
    height: 100%;
    width: 100%;
	top:0;
	background-image: url("https://images.unsplash.com/photo-1551908325-9bd4c5c33171?ixlib=rb-4.0.3&q=85&fm=jpg&crop=entropy&cs=srgb&dl=lachlan-thompson-SwgiWNurMuM-unsplash.jpg");
    background: size 50%;
    z-index: -1;
    }

	span {
		font-size: 2em;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>