<html lang="ru">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<meta http-equiv="X-UA-Compatible" content="ie=edge">
	<title>AR in Web</title>
</head>
<body>
	<script src="https://aframe.io/releases/1.0.4/aframe.min.js"></script>
	<script src="https://raw.githack.com/AR-js-org/AR.js/master/aframe/build/aframe-ar.js"></script>
	<a-scene embedded arjs>
		<a-marker url="https://github.com/UNL0G1C/unl0g1c.github.io/tree/main/QR-Code.png">
			<a-entity
				position="0 0 0"
				scale="1 1 1"
				gltf-model="https://github.com/UNL0G1C/unl0g1c.github.io/tree/main/scene.gltf"
			></a-entity>
		</a-marker>
		<a-entity camera></a-entity>
	</a-scene>
</body>
</html>
