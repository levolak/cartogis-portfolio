<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
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
            height: 600px; /* Maintain aspect ratio */
            max-width: 100%; /* Set a maximum width */
            margin-bottom: 20px;
        }
        

       
        /* Existing CSS rules */

        .wide-map-image {
            width: 1200px; /* Set a wider width */
            height: 600px; /* Maintain aspect ratio */
            max-width: 100%; /* Set a maximum width */
            display: block;
            margin-bottom: 20px;
        }
        
        .kuvaaja-map-image {
            width: 1300px; /* Set a wider width */
            height: 400px; /* Maintain aspect ratio */
            max-width: 100%; /* Set a maximum width */
            display: block;
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
            height: 500px; /* Set iframe height */
            border: none; /* Remove iframe border */
        }

        /* Flex container for iframes */
        .iframe-flex-container {
            display: flex; /* Use flexbox */
            flex-wrap: wrap; /* Wrap items to next line if necessary */
        }
        
        /* Adjust iframe size for interactive map */
        .iframe-container.interactive iframe {
            width: 1000px; /* Set fixed width */
            height: 700px; /* Set fixed height */
        }
    </style>
</head>
<body>
    <h1>This is the portfolio page for the Helsinki University Cartogis course made by Lauri Levomäki</h1>
    
    <h3>In this page, you can see some maps made during the course, and the storytelling section about air quality in Helsinki, Finland.</h3>
    
    <p>First, some maps I created as part of my coursework.</p>

    <!-- Images -->
    <h3>Population density of Helsinki:</h3>
    <img src="population_density_helsinki.png" alt="Population Density Helsinki" class="map-image">

    <h3>Where people aged 55-75 feel happy in Helsinki:</h3>
    <img src="MyMap_happypoints/happy_places_map.png" alt="Happy Places Map" class="map-image">
    
    <h3>About the mobile internet latencies in Europe:</h3>
    <!-- Map of Europe -->
    <img src="hexbin_map_europe.png" alt="Mobile Internet Latencies in Europe" class="wide-map-image">
    
    <h4> Sightings of flying squirrels in Uusimaa between 2010-2023</h4>
    <div class="iframe-container interactive">
        <iframe src="e4_squirrels.html"></iframe>
    </div>
    
   
    <!-- Maps -->
    <h6>And this is where the story begins...</h6>
    
    <h1>Air quality data explore in Helsinki city</h1>
    
    <p>Air pollution, particularly from nitrogen dioxide (NO2), is a significant environmental and public health concern in urban areas like Helsinki. NO2 is primarily emitted from vehicles, industrial processes, and combustion of fossil fuels. Exposure to NO2 and other air pollutants can have detrimental effects on human health, including respiratory issues, cardiovascular diseases, and even premature death.</p>
    <p></p>
    
     <!-- Embedded YouTube Video -->
    <iframe width="560" height="315" src="https://www.youtube.com/embed/GVBeY1jSG9Y?si=jR_lifNTAlhSQSE7" frameborder="0" allowfullscreen></iframe>
    <p></p>
     
    <p>Taking the detrimental impact of air pollution on public health, it's crucial to monitor and analyze air quality data. By conducting such analyses and creating maps, policymakers, urban planners, and citizens can better understand the spatial and temporal distribution of air pollution within the city. This understanding can inform targeted interventions and policies aimed at reducing pollution levels, mitigating public health risks, and improving overall urban livability.</p>
    
  

    <!-- Maps -->
    <h4>Change testi:</h4>
    <img src="gridmap_no2_2015.png" alt="NO2 Levels 2015" class="map-image">
    <img src="gridmap_no2_2020.png" alt="NO2 Levels 2020" class="map-image">
    <img src="gridmap_no2_2023.png" alt="NO2 Levels 2023" class="map-image">
    
    <img src="meanvalues_bar_linechart.png" alt="Mean Values Bar Linechart" class="kuvaaja-map-image">
    <img src="trendvalues_2015_2023.png" alt="Trend Values 2015-2023" class="kuvaaja-map-image">
    
    <h2>Let's now see some interactive maps...</h2>
    <h4>Let's first see the changes between 2015 and 2020 (COVID-19 year)</h4>
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
    
    <h4>To explore air quality changes during every year (2015-2023)</h4>
    <div class="iframe-container interactive">
        <iframe src="slider_and_markers.html"></iframe>
    </div>
    
    <h4>Let´s invite an other dataset to the party, and see how is the traffic been changing in Helsinki during these years. 
in an urban environment, traffic is the most significant cause of air pollution and thus degrades air quality the most. (lisää lähde hsy) The traffic values show yearly average amount of vehicles per hour. </h4>
    <img src="trendvalues_2015_2023.png" class="kuvaaja-map-image">
    <img src="no2_traffic_linechart.png" class="kuvaaja-map-image">
    
    <h4>Traffic slider alle</h4>
    <div class="iframe-container interactive">
        <iframe src="traffic_map_with_slider.html"></iframe>
    </div>
    
    <h4>We can see how these factors are correlating, and the effect of COVID-19</h4>
    <img src="no2_traffic_linechart.png" class="kuvaaja-map-image">
    
    <h4>Scatterplot here</h4>
    
    <h4>And finally, air quality and traffic together between 2015-2023</h4>
    <div class="iframe-container interactive">
        <iframe src="combined_map_with_slider.html"></iframe>
    </div>
    
    <h3>Conclusion</h3>
    <p>As can be seen from the data, the air quality values are still relatively good in Helsinki. Understanding the correlation between traffic and air pollution is essential for addressing environmental and public health challenges and make the city better. The average NO2-values vary between 15-35 (µg/m³) and these are still acceptable levels. The correlation between traffic emissions and air quality can be seen.</p>
    
    <p>Even though the coronavirus disrupted the trends, it can be clearly seen that the green transition of traffic has reduced emission values. It is still important to monitor and analyze air quality and the factors affecting it in the future. This approach will not only enhance the city's air quality but also improve the overall quality of life for its residents. By prioritizing sustainable transportation and efficient traffic management, Helsinki can pave the way for a healthier, more sustainable urban environment.</p>
    <p></p>
    <h4>Datasources:</h4>
    <p>Air quality data is managed by HSY. The dataset includes the average NO2 values and the measurement point for the year in. Shapefiles were used for this study.</p>
    <p><a href="https://www.hsy.fi/en/environmental-information/open-data/avoin-data---sivut/air-quality-monitoring-sites-and-annual-nitrogen-dioxide-no2-averages-in-the-helsinki-metropolitan-area/">HSY Air Quality Data</a></p>
   
    <p>HSY: https://www.hsy.fi/en/air-quality-and-climate/air-quality-in-different-environments/ </p>
    
    
    
    <p>The traffic dataset includes average traffic volumes each year in Helsinki. The traffic data is managed by Helsingin kaupunkiynpäristö and is downloaded in csv-format from:</p>
    <p><a href="https://www.avoindata.fi/data/en_GB/dataset/liikennemaarat-helsingissa/resource/a652b375-548a-4ebe-a396-18500595244f">Helsinki Traffic Data</a></p>
    
    <h1>All the data is handled with Python 3.5 and these libraries for the maps and charts: pandas, geopandas, matplotlib, osmnx, pathlib, contextily, numpy, shapely, mapclassify, os, mpl_toolkits, folium, branca, seaborn, mpl_toolkits, pyproj.</h1>
</body>    
</html>
