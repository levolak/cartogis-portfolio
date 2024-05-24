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

        .map-image {
            display: block;
            width: 600px; /* Set a fixed width */
            height: auto; /* Maintain aspect ratio */
            max-width: 100%; /* Set a maximum width */
            margin-bottom: 20px;
        }

        /* Container for each iframe */
        .iframe-container {
            width: calc(50% - 10px); /* Adjust width for two iframes with margin */
            margin-right: 10px; /* Add margin between iframes */
            margin-bottom: 30px; /* Increase bottom margin to separate iframes more */
        }

        /* Iframe styles */
        .iframe-container iframe {
            width: 100%; /* Set iframe width to fill container */
            height: 400px; /* Set iframe height */
            border: none; /* Remove iframe border */
        }

        /* Flex container for iframes */
        .iframe-flex-container {
            display: flex; /* Use flexbox */
            flex-wrap: wrap; /* Wrap items to next line if necessary */
        }
    </style>
</head>
<body>
    <h1>Cartogis Portfolio</h1>
    
    <h1>letsmake</h1>
    
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
    
    <h1>Air quality data explore in Helsinki city</h1>
    
      <p>Air pollution, particularly from nitrogen dioxide (NO2), is a significant environmental and public health concern in urban areas like Helsinki. NO2 is primarily emitted from vehicles, industrial processes, and combustion of fossil fuels. Exposure to NO2 and other air pollutants can have detrimental effects on human health, including respiratory issues, cardiovascular diseases, and even premature death.
       <p></p>
     
  <p>Given the detrimental impact of air pollution on public health, it's crucial to monitor and analyze air quality data. By conducting such analyses and creating maps, policymakers, urban planners, and citizens can better understand the spatial and temporal distribution of air pollution within the city. This understanding can inform targeted interventions and policies aimed at reducing pollution levels, mitigating public health risks, and improving overall urban livability.</p>
    <p>And this is where the story begins...</p>
    
    <!-- Embedded YouTube Video -->
    <iframe width="560" height="315" src="https://www.youtube.com/embed/GVBeY1jSG9Y?si=jR_lifNTAlhSQSE7" frameborder="0" allowfullscreen></iframe>

    <h6>And this is where the story begins...</h6>
    <!-- Maps -->
    <h4>Change:</h4>
    <img src="gridmap_no2_2015.png" alt="Happy Places Map" class="map-image">
    <img src="gridmap_no2_2020.png" alt="Happy Places Map" class="map-image">
    <img src="gridmap_no2_2023.png" alt="Happy Places Map" class="map-image">
    
    <img src="meanvalues_bar_linechart.png" alt="Happy Places Map" class="map-image">
    <img src="trendvalues_2015_2023.png" alt="Happy Places Map" class="map-image">
    
    <!-- next to each other-->
    <div class="iframe-flex-container">
        <!-- First set of maps -->
        <div class="iframe-container">
            <iframe src="gridmap_no2_2015.png"></iframe>
        </div>
        <div class="iframe-container">
            <iframe src="gridmap_no2_2020.png"></iframe>
        </div>
    </div>
    
    
    
    
    
    <h2>Let's now see some interactive maps...</h2>
    <h4>Let´s first see the changes between 2015 and 2020 (covid-19 year)</h4>
    <!-- Flex container for iframes -->
    <div class="iframe-flex-container">
        <!-- First set of maps -->
        <div class="iframe-container">
            <iframe src="map_2015.html"></iframe>
        </div>
        <div class="iframe-container">
            <iframe src="map_2020.html"></iframe>
        </div>
    </div>
    
    <h4>And next the changes between 2020 and 2023</h4>
    <!-- Flex container for iframes another set -->
    <div class="iframe-flex-container">
        <!-- First set of maps -->
        <div class="iframe-container">
            <iframe src="map_2020.html"></iframe>
        </div>
        <div class="iframe-container">
            <iframe src="map_2023.html"></iframe>
        </div>
    </div>
    
    <h4>We can see the how covid-19 affected the amount of No2-values and traffic</h4>
    <img src="no2_traffic_linechart.png"  class="map-image">
    
    <img src="combined_map_with_slider.html"  class="map-image">
    
    
    
    
    
    <h4>Change:</h4>
    
    <h4>Datasources: remember slider and markers and traffic map with slider</h4>
    
     <h4>Python libraries:</h4>
    
  
</body>    
</html>
