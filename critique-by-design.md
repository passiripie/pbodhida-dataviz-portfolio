| [home page](https://passiripie.github.io/pbodhida-dataviz-portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique and redesign - The NOAA Annual Greenhouse Gas Index (AGGI)

## Step one: the visualization

The original visualization is from this academic article about the NOAA Annual Greenhouse Gas Index (AGGI): https://gml.noaa.gov/aggi/aggi.html

<img src="aggi.fig3.png" width="1000"/>

I chose this visualization because it contains multiple elements, such as 2 vertical axes, reference lines, legend, and annotation. I admired how the creator tried to communicate every aspects of information from the given data and added all elements mentioned, but this makes the chart very confusing. So, I find it challenging and exciting to redesign this chart. Moreover, I have never created a stacked area chart before, so I think this is a good opportunity for me to try working on that, and probably do something creative.


## Step two: the critique

The visualization attempts to show the growth in radiative forcing compositions over time with a reference period, which is an interesting idea, and the area chart helps represent overall growth. However, the way AGGI and the reference line are presented makes it hard to understand the comparison between the reference period and other years. Some elements also reduce clarity, such as the lack of a title, unclear x-axis tick marks, inconsistent gas labels, and arbitrary color choices. Although the chart may still be readable for researchers or technically familiar audiences, it does not communicate the key insight clearly and does not reach its full potential.

In my redesign, I want to focus on highlighting the changes in radiative forcing compared to the reference period. I am considering using a surplus/deficit style chart to show increases and decreases more clearly. I may still use an area chart but only for major gases like CO₂ and methane, grouping the rest as “others.” I also plan to remove the AGGI right axis and instead show AGGI as annotations for key years. Additionally, I want to improve the overall design by adding a clear title and subtitle, using more consistent labeling, and experimenting with lighter colors and outlines to make the visualization more visually pleasing and easier to read.

## Step three: Sketch a solution

<img src="JPEG image-4DCA-9B74-0D-0.jpeg" width="1000"/>

I decided that 'the radiative forcing hit 54% increase in 2024' will be my main focus to communicate for this redesign. Then, I considered doing the surplus/deficit style of stacked area chart to emphasize the change in radiative forcing relative to the reference point. This is mainly because I want to align the presentation with the AGGI definition, so I think the idea should revolve around comparisons to 1990. I decided to preserve the Radiative Forcing as vertical axis, retaining the original gas quantity information, and present AGGI index as annotations instead of an axis to reduce confusion. Because the chart shows the changes compared to 1990, I adjusted the vertical axis value to be incraeses/decreases of radiative forcing.

I grouped the other gases besides CO2 and Methan (CH4) into the 'others' group, avoiding unnecessary details that makes the chart too complex. I also changed 'Methane' to 'CH4' for consistency with 'CO2'. I used 2 distinct colors to represent CO2 and CH4, and used grey for others to de-emphasize it. The gas names were placed at the end of the area, to reduce the need of legends and lower the eye movements. Lastly, I added the title to highlight my main idea, and also the subtitle to describe the AGGI definition.

## Step four: Test the solution

These are the feedbacks I got from interviewees

| Question| Interview 1 | Interview 2 | Interview 3 | 
|----------|-------------|-------------|-------------|
|Can you describe to me what this is telling you?|Greenhouse gases increased from 1990|Greenhouse gases increased from 1990 + CO2 is the biggest component| Greenhouse gases increased from 1990 + CO2 is the biggest component|
|Is there anything you find surprising or confusing?|I am not sure where 54% is in the chart | I think the red color of CO2 seems alarming, is it intentional? | The y-axis shows the absoluate value of radiative forcing, or the changes?|
|Who do you think is the intended audience for this?          | researchers             | students, environmentalists           | researchers, students            |
|Is there anything you would change or do differently?         | No, after I read the AGGI definition, I understood how 54% increase is related, I also think the red annotations stand out well, however, I think the color legend will work better than the current gas labels  | It should use colors that are neutral, not suggesting good nor bad | The y-axis label should say that it's the change in radiative forcing  |

Synthesis: 
Overall, I think the readers get the main idea that the chart communicates, that the greenhouse gases have increased significantly from 1990. I learned that the stacked area works well to show the greengas components, and the surplus/deficit style presents the main idea very well. There're still some confusing elements, such as colors and axis labels, that should be fixed. I will try to use neutral colors for gas components, and fix the y-axis label. As for adding the legend, I am not sure because I want to limit the eye movement, although I admit that the current design may make it hard to see the gas names. I will see what I can do in Tableau.



## Step five: build the solution
<div class='tableauPlaceholder' id='viz1774989928282' style='position: relative'><noscript><a href='#'><img alt='Radiative Forcing from Greenhouse Gases is 54% greater in 2024 than it was in 1990Annual Greenhouse Gas Index (AGGI) shows the change in radiative forcing in any given year relative to 1990  ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;AG&#47;AGGI_chart&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='AGGI_chart&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;AG&#47;AGGI_chart&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1774989928282');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>



_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. When you're done with the assignment, this page should all the items mentioned in the assignment page on Canvas(a link or screenshot of the original data visualization, documentation explaining your process, a summary of your wireframes and user feedback, your final, redesigned data visualization, etc.)._

## References
_List any references you used here._

## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._

