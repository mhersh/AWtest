AWtest
======
<!--Trying to add CartoDB table integrated with Google Maps -->
<!--I don't know how to make a new branch so my script will awkwardly be put into this readme for now -->

<html>
<head>
<script>
<!DOCTYPE html>

http://mkoo.cartodb.com/api/v2/sql?q==SELECT*FROM private_table&api_key={1568825e0544383cc3971f520c2db0b671e877e7}

<iframe src='https://mvz.cartodb.com/tables/playing_with_holotype_map/embed_map?sql=SELECT%20*%20FROM%20playing_with_holotype_map%20WHERE%20year=2008
' width=600 height=400></iframe>


<link href="css/cartodb-gmapsv3.css" rel="stylesheet" type="text/css">
<link href="http://code.google.com/apis/maps/documentation/javascript/examples/default.css" rel="stylesheet" type="text/css" />          
<script type="text/javascript" src="http://maps.googleapis.com/maps/api/js?key=1568825e0544383cc3971f520c2db0b671e877e7&sensor=TRUE"></script>
<script type="text/javascript" src="js/wax.g.min-6.2.0-touched.js"></script>
<script type="text/javascript" src="dist/cartodb-gmapsv3-min.js"></script>




  <head>
    <meta name="viewport" content="initial-scale=1.0, user-scalable=no" />
    <style type="text/css">
      html { height: 100% }
      body { height: 100%; margin: 0; padding: 0 }
      #map_canvas { height: 100% }
    </style>
    <script type="text/javascript"
      src="https://maps.googleapis.com/maps/api/js?key=AIzaSyAQy695UVS-XMVBCpwpByUngbmJaOuE9ts&sensor=FALSE">
    </script>
    <script type="text/javascript">
      function initialize() {
        var mapOptions = {
          center: new google.maps.LatLng(-34.397, 150.644),
          zoom: 8,
          mapTypeId: google.maps.MapTypeId.ROADMAP
        };
        var map = new google.maps.Map(document.getElementById("aw_newspecies_holotype_map_updated"),
            mapOptions);
      }
    </script>
  </head>
  <body onload="initialize()">
    <div id="map_canvas" style="width:100%; height:100%"></div>
  </body>
</html>