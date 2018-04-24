# Homework1
First homework assignment

This repository is created as part of a project.

<!DOCTYPE html>
<html>
	<head>
		<title>Homework 1</title>
		<style>
			body {background-color: beige;}

			h1 {
				font-family: courier;
				text-align: center;
				font-size:28px;
				color: purple;
			}

			p {
				border: 1px solid purple;
				color: hsl(0, 40%, 50%);
				text-align: center;
				padding: 8px;
				margin: 18px;
			}
		</style>
	</head>

	<body>
		<h1>
			Welcome to <abbr title="Experimental Psychology Lab">EPL</abbr>!
			<sub><i>SS2018</i></sub>
		</h1>

		<form action="javascript:SayHello();">
			<p id="demo">
					Name:<br>
					<input type="text" id="nameField" value="" />
					<input type="submit" value="Go" />
			</p>
		</form>

		<script>
			function SayHello() {
				var YourName = document.getElementById('nameField').value;
				document.getElementById("demo").innerHTML = "Hello"+ ", " + YourName + "!";
			}
		</script>

		<a href="index.html">Refresh the page</a>
	</body>
</html>
