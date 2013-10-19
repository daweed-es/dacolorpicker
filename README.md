dacolorpicker
=============

jQuery colorpicker plugin


Example
```html
<html>
<head>
  <link rel="stylesheet" href="jquery.dacolorpicker.css" type="text/css"/>
  <script src="jquery-1.9.1.js"></script>
  <script src="jquery.dacolorpicker.js"></script>
  <script>
    $(document).ready(function(){
		$("#trigger1").dacolorpicker({triggerDest: "dest1",paletteType: "palettePattern2"});
	});
  </script>
</head>
<body>
  <p>
  <input type="text" id="dest1" />
  <img src="images/cpicker.png" name="trigger1" id="trigger1" class="cpicker">
  </p>
</body>
</html>
```
