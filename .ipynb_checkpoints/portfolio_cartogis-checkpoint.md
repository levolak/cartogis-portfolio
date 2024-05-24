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

        h1, h2 {
            color: #ffffff; /* White text color for headings */
        }

        .iframe-container {
            display: inline-block;
            margin-right: 10px;
            margin-bottom: 10px;
        }

        .iframe-container iframe {
            width: 400px; /* Adjust the width as needed */
            height: 300px;
        }

        img {
            display: block;
            max-width: 100%; /* Ensure images scale down to fit their container */
            height: auto; /* Maintain aspect ratio */
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <h1>Cartogis Portfolio</h1>
    
     <p>Here are some maps I created as part of my coursework.</p>
    
    
    
    <!-- Images -->
    <h2>Population density of Helsinki:</h2>
    <img src="population_density_helsinki.png" alt="Population Density Helsinki">

    <h2>Where people aged 55-75 feel happy in Helsinki:</h2>
    <img src="MyMap_happypoints/happy_places_map.png" alt="Happy Places Map">
    
    <h2>About the mobile internet latencies in Europe:</h2>
    <img src="MyMap_hexbin_map_europe.png" alt="Mobile Internet Latencies in Europe">

    <!-- Maps -->
    <h2>And this is where the story begins...</h2>
    <div class="iframe-container">
        <iframe src="gridmap_no2_2015.png"></iframe>
    </div>
    <div class="iframe-container">
        <iframe src="gridmap_no2_2020.png"></iframe>
    </div>
    <div class="iframe-container">
        <iframe src="gridmap_no2_2023.png"></iframe>
    </div>

    <h2>Let's now see some interactive maps...</h2>
    
    <div class="iframe-container">
        <iframe src="map_2015.html" width="800" height="600"></iframe>
    </div>
    <div class="iframe-container">
        <iframe src="map_2020.html" width="800" height="600"></iframe>
    </div>
    <div class="iframe-container">
        <iframe src="map_2023.html" width="800" height="600"></iframe>
    </div>
</body>
</html>
