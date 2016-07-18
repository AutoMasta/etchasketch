# etchasketch
<!DOCTYPE html>
<html>

	<head>
		<link rel="stylesheet" type="text/css" href="etchasketch.css">
		<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.0/jquery.min.js"></script>
		<script type="text/javascript" src="javascript.js"></script>
	</head>
	<body>
		
		<div id="container">
		<div class="grid"></div>
		
		</div>

	</body>

</html>
#container {
	width: 960px;
	height: 960px;

}
.grid {
	display: inline-block;
	float: left;
	padding: 25px;
	border-style: solid;
	border: 1px 0px solid #000000;
}

.grid:hover {
	background-color: blue;
}
