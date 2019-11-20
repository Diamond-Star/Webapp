<!DOCTYPE html>
<html>
<body>

<script>
$.getJSON( "http://mytest1000.000webhostapp.com/index.php?name=pen", function( data ) {
  var items = [];
  $.each( data, function( key, val ) {
    items.push( "<li id='" + key + "'>" + val + "</li>" );
  });
 
  $( "<ul/>", {
    "class": "my-new-list",
    html: items.join( "" )
  }).appendTo( "body" );
});
</script>



</body>
</html>
