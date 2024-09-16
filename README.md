# an_le.github.io
Project website
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8" />
<title>Infraction fine </title>

<script src="06.09InfractionFineEx.js">
</script>
</head>
<body>
	<h3>Infraction fine </h3>

	<form>
		<p>
			<label>Driving Speed: </label> <input type="text" name="drivingSpeed" id="drivingSpeed"
				size="3">
		</p>
		<p>
			<label>Speed limit: </label> <input type="text" name="speedLimit"
				id="speedLimit" size="3">
		</p>
		<p>
			<input type="button" id="submit" value="Tell about the ticket" onClick="tellInfractionFine()">
		</p>
	</form>

		<!-- This is the target where the JavaScript will write the answer -->
	<div id="answer"></div>
</body>
</html>
