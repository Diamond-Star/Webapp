<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>jQuery.getJSON demo</title>
  <style>
  img {
    height: 100px;
    float: left;
  }
  </style>
  <script src="https://code.jquery.com/jquery-3.4.1.js"></script>
</head>
<body>
 
<div id="images"></div>
 
<script>
(function() {
  var flickerAPI = "http://mytest1000.000webhostapp.com/index.php?name=pen";
  $.getJSON( flickerAPI
  })
    .done(function( data ) {
     print(data);
          return false;
        }
      });
    });
})();
</script>
 
</body>
</html>
