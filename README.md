# HW3
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projections</title>
</head>
<body>
    <h1>In this project I learned how to display images in different projections</h1>
    <h2 style="color:red">Describe in your own words how you displayed the map in different projections using QGIS</h2>
    <p>I downloaded the data from the git.hub website provided, after extracting and opening the shapefile with the base map, 
        I took the map and created a new layer, exporting the entire vector layer as a Geojson with the new projection 
        by changing the input projection in export set up window. After this, the new layer populates ontop of the old and I changed the view by changing the projection being rendered. 

    </p>
    
    <h2>WGS84 Projection</h2>
    <h3>Some observations
        This projection distorts area but conserves direction, it does distort shape but does so in a way that is intuative, by stretching things horizontally.
   <img src="4326.png" alt="WGS84" width='500px'>
   
    </h3>
    <a href="4326.png">
  </a>
    <h2>Aitoff Projection</h2>
  <a href=".//maps/54043.png">
    <img src="54043.png" alt="Aitoff" width='500px'>
    <h3>Some observations
        This projection conserves shape at the expense of everything else, distance, size, and direction. Not my favorite projection in all honesty
    </h3>
   
    </a>
    <h2 style="color:red">Now, you should <u>add the following projections on your own:</u></h2>

    <h3>EPSG: 3857, 53018, 54034, 54027, 102016, and two additional projections that you choose.</h3>

<h2>EPSG: 3857 Psuedo Mercator </h2>
 <p>This projection is very similar to the mercator, It seems to apply more vertical stretch to the poles</p>
 <img src="3857.png"  width='500px'>
   <h2>ESRI 53018 Winkle 1 Projection</h2>
    <p> This projection appears to accept minimul distortions in all aspects, creates a nice aestheic map that does not change any one aspect drastically but also doesn't preserve any.</p>
    <img src="53018.png"  width='500px'>   
   <h2> ESRI 54034-Sphere Equal Areas Cylindrical</h2>
   <p>Similar to the mercator but has a drastic distortion at the poles, with no distortion in other places, thus priortizes the tropics and mid latitudes </p>
    <img src="54034.png"  width='500px'>
   <h2>ESRI 54027-World Equal Distance Conic</h2> 
   <p> View from north pole, squishes the northern hemisphere and stretches the southern in an interesting flip from tradition, also focuses on europe putting the US and Asia on the sides and cuts off their connection via the pacific ocean</p>
    <img src="54027.png"  width='500px'>
    <h2>ESRI 102016- North Pole Azimuthal</h2> 
    <p>Similar to the last one except preseves distance from the poles. </p>
    <img src="102016.png"  width='500px'>
    <h2>ESRI-54074 - World Wagner 4</h2> 
    <p>Conserves area</p>
    <img src="54074.png"  width='500px'>
    <h2>ESRI-53079 - World Patterson</h2> 
    <p>Conserves shape at the expense of area</p>
    <img src="53079.png"  width='500px'>
    
   
    <h2>Data used for this project</h2>


    <a href="https://www.naturalearthdata.com/http//www.naturalearthdata.com/download/10m/cultural/ne_10m_admin_0_countries.zip"> Download Natrual Earth 1:10m Cultural Vector </a>
</body>
</html>
