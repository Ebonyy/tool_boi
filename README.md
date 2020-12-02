<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8' />
    <title>Test_Context</title>
    <meta name='viewport' content='initial-scale=1,maximum-scale=1,user-scalable=no' />
    <script src='https://api.tiles.mapbox.com/mapbox-gl-js/v0.48.0/mapbox-gl.js'></script>
    <link href='https://api.tiles.mapbox.com/mapbox-gl-js/v0.48.0/mapbox-gl.css' rel='stylesheet' />
    <script src='./GeoBoi.js'></script>
    <style>
        body { margin:0; padding:0; }
        #map { position: absolute; right:200; top:0; bottom:0; width:100%; }
    </style>
    <script type="text/javascript" 
    src="http://ajax.googleapis.com/ajax/libs/jquery/1.5.2/jquery.min.js"></script>

</head>

<body>

<div id='map'></div>

<script>
mapboxgl.accessToken = 'pk.eyJ1IjoiZXdlYnkiLCJhIjoiY2tpN2V3bzR5MDk2djM0bjBsbHQ3a2djbSJ9.674Gjb8Uc7gMIgLqpdE8wQ';
var map = new mapboxgl.Map({
    container: 'map', // container id
    style:  'mapbox://styles/eweby/ckhbv51iq0vko19pcs3llpr4k', // stylesheet location 
    center: [151.003105, -33.823002], // starting position [lng, lat]
    pitch: 45,
    bearing: -17.6,
    zoom: 16.24 // starting zoom
});

</script>

    <!-- begin wwww.htmlcommentbox.com -->
 <div id="HCB_comment_box"><a href="http://www.htmlcommentbox.com">Comment Form</a> is loading comments...</div>
 <link rel="stylesheet" type="text/css" href="https://www.htmlcommentbox.com/static/skins/bootstrap/twitter-bootstrap.css?v=0" />
 <style> 
 #HCB_comment_box {
     position: absolute;

  </style>
 <script type="text/javascript" id="hcb"> /*<!--*/ if(!window.hcb_user){hcb_user={};} (function(){var s=document.createElement("script"), l=hcb_user.PAGE || (""+window.location).replace(/'/g,"%27"), h="https://www.htmlcommentbox.com";s.setAttribute("type","text/javascript");s.setAttribute("src", h+"/jread?page="+encodeURIComponent(l).replace("+","%2B")+"&mod=%241%24wq1rdBcg%24qhGrL.babvjoai8HdNGfS%2F"+"&opts=16862&num=10&ts=1606908239904");if (typeof s!="undefined") document.getElementsByTagName("head")[0].appendChild(s);})(); /*-->*/ </script>
<!-- end www.htmlcommentbox.com -->

</body>


</html>
