<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cartogis Portfolio</title>
    <style>
        
body {
    font-family: Arial, sans-serif;
    background-color: #121212; /* Dark background color */
    color: #ffffff; /* White text color */
    margin: 0;
    padding: 20px;
}

h1, h2, h3, h4, p {
    margin-top: 0; /* Remove top margin */
    margin-bottom: 10px; /* Add bottom margin */
}

/* Container for sets of maps */
.iframe-set {
    margin-bottom: 20px; /* Add bottom margin for spacing */
}

/* Container for each iframe */
.iframe-container {
    display: inline-block;
    width: calc(50% - 10px); /* Adjust width for two iframes with margin */
    margin-right: 20px; /* Add margin between iframes */
    vertical-align: top; /* Align iframes at the top */
}

/* Iframe styles */
.iframe-container iframe {
    width: 100%; /* Set iframe width to fill container */
    height: 400px; /* Set iframe height */
    border: none; /* Remove iframe border */
}

.map-image {
    display: block;
    width: auto; /* Ensure the image fills its container */
    height: 500px; /* Set a fixed height */
    max-width: 100%; /* Set a maximum width */
    margin-bottom: 20px;
}

    
        

 
    </style>
</head>
<body>
    <h1>Cartogis Portfolio</h1>
    
    
    <h1>toimiik2ffffffffffffo</h1>
    
     <p>Here are some maps I created as part of my coursework.</p>
    
    
    
    <!-- Images -->
    <h3>Population density of Helsinki:</h3>
    <img src="population_density_helsinki.png" alt="Population Density Helsinki" class="map-image">

    <h3>Where people aged 55-75 feel happy in Helsinki:</h3>
    <img src="MyMap_happypoints/happy_places_map.png" alt="Happy Places Map" class="map-image">
    
    <h3>About the mobile internet latencies in Europe:</h3>
    <!-- Map of Europe -->
    <img src="hexbin_map_europe.png" alt="Mobile Internet Latencies in Europe" class="map-image">
   

    <!-- Maps -->
    <h6>And this is where the story begins...</h6>
    
    <h2>NO2:</h2>
    <!-- Embedded YouTube Video -->
    <iframe width="560" height="315" src="https://www.youtube.com/embed/GVBeY1jSG9Y?si=jR_lifNTAlhSQSE7" frameborder="0" allowfullscreen></iframe>

     <!-- Maps -->
    <h4>Change:</h4>
    <img src="gridmap_no2_2015.png" alt="Happy Places Map" class="map-image">
    <img src="gridmap_no2_2020.png" alt="Happy Places Map" class="map-image">
    <img src="gridmap_no2_2023.png" alt="Happy Places Map" class="map-image">
    
    <img src="meanvalues_bar_linechart.png" alt="Happy Places Map" class="map-image">
    <img src="trendvalues_2015_2023.png" alt="Happy Places Map" class="map-image">
    

    <h2>Let's now see some interactive maps...</h2>
      <!-- First set of maps -->
    <div class="iframe-container">
        <iframe src="map_2015.html"></iframe>
    </div>
    <div class="iframe-container">
        <iframe src="map_2020.html"></iframe>
    </div>


    <img src="no2_traffic_linechart.png" alt="Happy Places Map" class="map-image">
  
</body>    
</html>
