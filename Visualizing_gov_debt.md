| [home page](https://kjmattso.github.io/Mattson-portfolio/) | [visualizing-government-debt](https://kjmattso.github.io/Mattson-portfolio/Visualizing_gov_debt.html) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Visualizing Government Debt

This assignment includes two recreations of the OECD graph of government debt in 2016. 

### Original Visualization

<iframe src="https://data.oecd.org/chart/7kiw" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/7kiw" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2016</a></iframe>

### Recreation 1

The graph below is a basic recreation of the OECD bar graphs, created in Tableau. This shows each country as a heatmap.

<div class='tableauPlaceholder' id='viz1706384568763' style='position: relative'><noscript><a href='#'><img alt='Viz_Gov_Debt_TSWD ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Vi&#47;Viz-Gov-Debt-Assignment&#47;Viz_Gov_Debt_TSWD&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Viz-Gov-Debt-Assignment&#47;Viz_Gov_Debt_TSWD' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Vi&#47;Viz-Gov-Debt-Assignment&#47;Viz_Gov_Debt_TSWD&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
var divElement = document.getElementById('viz1706384568763');                    
var vizElement = divElement.getElementsByTagName('object')[0];                    
vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
var scriptElement = document.createElement('script');                    
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

### Recreation 2: COVID-19 and Government Debt

For the final recreation, I wanted to isolate the effects of the COVID-19 pandemic on Government Debt. The WHO COVID-19 timeline lists 12/31/2019 as the beginnings of the recognized pandemic, and a demarcation line was placed at 2020 to divide pre- and post- pandemic declaration.The graph indicates that government spending was universally on a sharp incline in the year prior to the pandemic. It is unknown if this would have continued in the absense of COVID-19. Regardless, all countries appeared to change behavior to halt, and even begin shrinking, growth in the total new debt they borrowed in the years prior.  

Axis titles were removed to avoid redundancy, and tick marks were minimized as they also add little to the narrative of the graph. Finally, an insightful title was added to add further context. A caption was included at the bottom with sources and citations to add credibility and allow further recreation of the data. Data was subsected fro 2016-most recent data to show highlight recent trends, and avoid further visual distractions from spending post the 2008 recession. Finally, a "Highlight Country" bar was added to allow the audience to isolate a country if they wished to, without adding distracting elements. To make the user experience better, the OECD country acronyms were given aliases that reflecte the country's full name in English. 

I feel this new visualization is far easier to read than the prior two. There is a clear narrative being created, and style choices enhance the main objective the visualization, with extemporaneous aspects excluded. The other visualizations added unnecessary clutter, and presented overwhelming amounts of data.

<div class='tableauPlaceholder' id='viz1706392238825' style='position: relative'><noscript><a href='#'><img alt='Countries borrowed more right before the COVID-19 pandemic, but slowed new spending after. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;CO&#47;COVID19_Debt&#47;COVID19_Debt&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='COVID19_Debt&#47;COVID19_Debt' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;CO&#47;COVID19_Debt&#47;COVID19_Debt&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
var divElement = document.getElementById('viz1706392238825');                    
var vizElement = divElement.getElementsByTagName('object')[0];                    
vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                   
var scriptElement = document.createElement('script');                    
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
