<!DOCTYPE html>
<html>

<head>

	<!-- Font Awesome -->
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css">

	<!-- Google Font -->

	<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+SC:wght@600&family=Delius&display=swap" rel="stylesheet">

	<!-------->

	<style>
		* {
			margin: 0;
			padding: 0;
			-webkit-box-sizing: border-box;
			box-sizing: border-box;
		}


		.navMenu {
			font-family: 'Cormorant SC', serif;
font-family: 'Delius', cursive;
			padding: 8px;
			text-align: center;
			margin: 7px auto;
			width: fit-content;
		}

		.navMenu a {
			color: #272727;
			text-decoration: none;
			text-transform: lettercase;
			display: inline-block;
			padding: 6px;
		}

		.background {
			background-color: #ece5f0;
		}

		.border {
			border: 1px solid #cccccc;

		}

		.navMenu a:hover {

			color: #d09c0b;
		}
	</style>
</head>

<body>

	<nav class="navMenu  border">
                <a id="&nbsp; Study Log" onclick="navigate(this.id)" href="#"> <i class="fa-solid fa-book-open"></i> &nbsp; Study Log</a>

	</nav>


	<script>

		let direction = "vertical";
		if (direction === "vertical") {
			document.head.insertAdjacentHTML("beforeend", `<style>.navMenu a {display: block; text-align:left; margin:7px} i{width:15px; margin-right:5px} .navMenu{margin:3px}</style>`)
		}


		function navigate(id) {

                        if (id == 'study log')
				window.open("https://example.com", '_blank').focus();

		}
	</script>


</body>

</html>
