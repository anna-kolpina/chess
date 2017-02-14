<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
 
<title></title>
<style>
	.black {
		background-color: #555555;
        width: 60px;
        height: 60px;
	}
	.white {
		background-color: #999999;
        width: 60px;
        height: 60px;
	}
</style>
</head>
<body>


<script type="text/javascript">
	
//function border() {
	var black = document.createElement('div');
	div.className = "black";
	var white = document.createElement('div');
	div.className = "white";
	var result = '';
//}
for (black = 1; black <= 8; black++) {
	for (white = 1; white <= 8; white++) {
		result += (black % 2 == white % 2) ? 'a' : 'b';
	}
	result += '\n';
}
alert(result);

</script>
</body>
</html>
