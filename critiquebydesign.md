

# Critique by Design

### Source Data Visualization

### Critique Related to the visualization

### Wireframe of the Solution

### Testing of the solution
The wireframe of this solution was tested with 2 users. The process I followed for this, involved showing them the visualization without guiding them and then asking the following questions.

##### User 1 : Student 22 years old
Q.Can you tell me what you think this is?
- > It’s a heatmap.
Q.Can you describe to me what this is telling you?
- > The darker the color gets, the more deaths happen per 100k.
-Q.Is there anything you find surprising or confusing?
- > The inclusive text is not self-explanatory, takes time to understand what it is.
Q.Who do you think is the intended audience for this?
- > Police departments, government, or anyone who wants to know how safe states are
-Q.Is there anything you would change or do differently?
- > It looks fine, legends position can be changed to the right to follow the eye movement.

##### User 2: Student 25 years old (aspiring data analyst) 
Q.Can you tell me what you think this is?
- > It is a geographical map of the US denoting the death rate per state in 2021 per 100k people. 
Q.Can you describe to me what this is telling you?
- > Some states have higher and lower numbers depending on the gradient of the color. The red states have the highest risk of people getting shot by a gun as compared to yellow states.
Q.Is there anything you find surprising or confusing?
- > Adding a continuous gradient scale than a categorization is better.
Q.Who do you think is the intended audience for this?
- >The police department for stricter patrolling, government body who is intending to bring about a change in the gun laws or using it as a reference to pass a gun law, an immigrant who is moving to the USA.
Q.Is there anything you would change or do differently?
- > I would want an explanation of the graph in 1-2 lines which is a clear explanation of what the graph wants to convey. I would want an abstract/summary which would be the key takeaway of the graphic.


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

