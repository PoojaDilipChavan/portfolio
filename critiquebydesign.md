

# Critique by Design

### Source Data Visualization

I chose the visulization representing the gun death rate in US according to state wise breakdown.
The source link : https://giffords.org/lawcenter/resources/scorecard/

The source visulization looks like below -

<img src="/portfolio/assets/gunmap.JPG">

### Critique Related to the visualization

This graph shows the gun death rate per state in the year 2021.
Overall, I would rate this visualization better than average due to the following characteristics -
1. It uses the correct type of visualization i.e. map to represent the state-wise gun death rate.
2. It categorizes data depending on the death rate and uses this information in legends to guide the user. It also mentions the scale of the death rate i.e. per 100k.

Characteristics that did not work well are as follows –
1. Although the US map is familiar to some audiences, it assumes that state names are understood by users and does not mention them on the map.
2. The graph shows data redundancy on the scale for legends with 100k written for each category.
3. The color formatting of the map is not intuitive. It uses dark purple/blue color for fewer deaths which is not intuitive to users. 
4. It does not have a clear title mentioning the purpose of visualization and the year in which data is collected. It also does not have a footnote mentioning the source of the information.

The things I would do differently for this visualization include –
1. Add the state name abbreviations on top of the state map. 
2. I will add an appropriate title like ‘ Gun death rates in 2021 state-wise breakdown’ and also add a footnote with the data source link.
3. I will choose a suitable color theme like shades of red/orange to depict the death rate. 
4.	I will also reformat the legends by removing the per 100k notion and adding it on the top of the scale.


### Wireframe of the Solution

I developed the wireframe for the solution using balsamiq wirframe tool. I used different components of the tool here like image, shapes, textbox and subtitles to craete the wireframe. 

<img src="/portfolio/assets/heatmap.JPG">

### Testing of the solution
The wireframe of this solution was tested with 2 users. The process I followed for this, involved showing them the visualization without guiding them and then asking the following questions.

##### User 1 : Student 22 years old
1. Can you tell me what you think this is?\
It’s a heatmap.\
2. Can you describe to me what this is telling you?\
The darker the color gets, the more deaths happen per 100k.\
3. Is there anything you find surprising or confusing?\
The inclusive text is not self-explanatory, takes time to understand what it is.\
4. Who do you think is the intended audience for this?\
Police departments, government, or anyone who wants to know how safe states are\
5. Is there anything you would change or do differently?\
It looks fine, legends position can be changed to the right to follow the eye movement.

##### User 2: Student 25 years old (aspiring data analyst) 
1. Can you tell me what you think this is?\
It is a geographical map of the US denoting the death rate per state in 2021 per 100k people.\
2. Can you describe to me what this is telling you?\
Some states have higher and lower numbers depending on the gradient of the color. The red states have the highest risk of people getting shot by a gun as compared to yellow states.\
3. Is there anything you find surprising or confusing?\
Adding a continuous gradient scale than a categorization is better.\
4. Who do you think is the intended audience for this?\
The police department for stricter patrolling, government body who is intending to bring about a change in the gun laws or using it as a reference to pass a gun law, an immigrant who is moving to the USA.\
5. Is there anything you would change or do differently?\
I would want an explanation of the graph in 1-2 lines which is a clear explanation of what the graph wants to convey. I would want an abstract/summary which would be the key takeaway of the graphic.


### Building the final solution

The final solution was built using tableau tool. I used my visulization type here and formatted the background layers to whitwash the unwanted portion of the map.
I incorported the comments by the users and used continous gradient scale to show the death rates. I also added the appropriate header and source of the dataset.
I faced few limitation of tableau like not being able to add state abbrivations of the data, I look forward to find the ways as I get more familiar with the tool.

<div class='tableauPlaceholder' id='viz1663720563555' style='position: relative'><noscript><a href='#'><img alt='Dashboard 2 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;5H&#47;5H9ZZTSWB&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;5H9ZZTSWB' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;5H&#47;5H9ZZTSWB&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
 var divElement = document.getElementById('viz1663720563555');                    
 var vizElement = divElement.getElementsByTagName('object')[0];                    
 if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1200px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1200px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='727px';}                     
 var scriptElement = document.createElement('script');                    
 scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
 vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

Source : Center for Disease Control and Prevention - https://wonder.cdc.gov/WelcomeT.html

