### Assignment 3 and 4

## Original Data
<iframe allow="geolocation" src="https://datahub.transportation.gov/dataset/NHTSA-Recalls-by-Manufacturer/mu99-t4jn/embed?width=800&height=600" width="800" height="600" style="border:0; padding: 0; margin: 0;"></iframe>
[Original Data](https://datahub.transportation.gov/Automobiles/NHTSA-Recalls-by-Manufacturer/mu99-t4jn)
This original chart represents the number of calls per manufacturers. However, there are some issues in this chart.
1. Coloring rule is not clear, and too much colors are used.
2. There is only information about the number of recalls. No ifnroamtion about the number of vehicles affected by recalls.
3. This chart doesn't tell the story but just the raw data.

## Additional data
The additional inforamtion might be necessary to show the information about the number of vehicles produced in 2024 in the USA per manufacturer.<br>
I have found the additional data as follows.
1. Car Production Data in 1st half of 2024(Except for Tesla)
[Addiitonal Data](https://www.carpro.com/blog/mid-year-2024-u.s-auto-sales-report-all-automakers-reporting)<br>
2. Car Production Data by 2Q of 2024 for Tesla
[Tesla](https://ir.tesla.com/press-release/tesla-vehicle-production-deliveries-and-date-financial-results-webcast-second-quarter-2024)<br>

I created the Pivot Table to represent the number of recalls and number of vehicles affected by recalls and have added the column to represent the number of car production in 1st half of 2024.
In creating this data, I addressed the points below.
1. Double the car production info to virtually show the entire year production. However, not the actual figure might be misinterpreted, then I used 1st half information as it is.
2. The information about the car production is divided into brand level, so I have combined all those data into company level.
3. For Major brands, I have added the column of region to USA, Asia, and Europe.

## Revised Chart
<div class='tableauPlaceholder' id='viz1731527060106' style='position: relative'><noscript><a href='#'><img alt='Which Region is the Safest to Buy a Car? ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ca&#47;CarRecalls_17315270468600&#47;WhichRegionistheSafesttoBuyaCar&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='CarRecalls_17315270468600&#47;WhichRegionistheSafesttoBuyaCar' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ca&#47;CarRecalls_17315270468600&#47;WhichRegionistheSafesttoBuyaCar&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1731527060106');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>
In order to better visualize the data, I have revised as follows.
1. To change the title to clearly show the story. The revised title is 'Which region is the safest to buy a car?'
2. Filter the information as follows.
    -Car Production Information is filled 
    -# of recalls is greater than 10.
3. To change the chart type to scatter plot to represent 3 factors: Car Production, Number of Affected Vehicles by recalls, Number of Recalls.
    -Car Production in 1st half of 2024: X-Axis
    -Number of Vehicles affected by Recalls: Y-Axis
    -Number of Recalls: Size of Bubble
4. To define the region as Asia, Europe and USA and categorized the manufacturers into the regions.
5. To define coloring rules per regions.

What I would like to do but I couldn't was as follows.
1. To add the reference line with Y=2X which represents that the doubled number of car production in 1st half of 2024 equals the number of vehicles affected by the recalls, but I couldn't figure out the way to draw this line.
