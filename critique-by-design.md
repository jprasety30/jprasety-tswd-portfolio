| [home page](https://jprasety30.github.io/jprasety-tswd-portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique by Design

## Step one: the visualization

_Include link to the original data visualization (or screenshot - make sure to correctly cite your sources, etc.).  Include paragraph or two on why you selected this particular data visualization.  For obvious reasons, the data visualization you select should come from a publicly accessible source._

- Title: Top 10 Countries by Military Spending 
- Link: (https://www.visualcapitalist.com/ranked-top-10-countries-by-military-spending/)

The reason why I chose this particular data visualization is because military expenditure is a controversial discourse that is often talked about in social media, but I've never seen concrete data behind these claims until this visualization. This visualization manages to tell a serious and controversial topic, in a simple and compelling way, which peaked my interest.

## Step two: the critique

### Describe your overall observations about the data visualization here.  What stood out to you?  What did you find worked really well?  What didn't work well?

What stood out immediately was the big pie chart taking center stage and the strong thematic coherence throughout the infographic. The use of toy soldiers, military green color palette, and stencil-style fonts reinforce the subject matter in a compelling way. These elements, while playful, create a visual metaphor that makes complex topics like global military expenditure more approachable and appealing to the broader audience.

I think what really worked well in this chart is its clear labeling for each of the top 10 countries, as it includes the absolute dollar value and percentage of global spending. The visual prominence of the U.S. and China reflects their dominating roles in global military spending. The supplementary details, such as China and U.S. accounting for more than 50% of global spending, China’s continuous growth, and the total spending in 2021 being $2.1 trillion, are helpful in providing context to the numbers further and add depth without overwhelming the primary focus of the chart.

However, the visualization lacked in some aspects. The use of radial partition layout within the pie chart makes it hard to compare countries with similar expenditures. For example, France, Germany, and Saudi Arabia all fall into similar spending range, but irregular shapes of their wedges distort direct comparisons. While this issue is mitigated with clear proportion labelling for each country portion, the viewers might visually misinterpret relative sizes. Another limitation is the lack of historical data or trend. The visualization is static, only presents 2021. This misses an opportunity to highlight how military expenditures have evolved over time or which countries are rapidly increasing their budgets. 

### Who is the primary audience for this tool?  Do you think this visualization is effective for reaching that audience?  Why or why not?

The primary audience would likely be the general, educated public with some interest in global affairs, international relations, defense economics, or politics in general. It’s relevant to journalists, students, researchers, and educators who want a quick and brief understanding of the global military spending landscape by the most dominant military driven countries.

For this purpose, I think the visualization is highly effective. It meets the audience’s needs by simplifying the complex topic of military expenditure into a single, visually compelling pie chart. The use of country flags, clear numerical values, and annotations highlighting trends/context supports casual exploration into the topic. Furthermore, it’s visually appeal and polish is good enough for use in media, presentations, and educational materials, appropriate for the wider audience.

### Based on your critique, what do you think you'll try to focus on in your redesign?   Any ideas or inspiration for how you can make a better data visualization?  What are you excited to try next?

For my redesign, I would focus on first trying to fix the radial area wedges layout used in the pie chart. While a regular pie chart might not work because it would stack the countries close together giving no room to add labels, something like a tree-map might work to better show the proportions accurately and leaves room for labeling. Given the target audience being the general public, I think that simplifying the information shown would be crucial to appeal to them. So, I think that re-focusing narrative of showing the U.S. and China's dominance in the world military spending would be a good start to redesign this chart.

I would also aim to fix the missed opportunity to show historical data and trends. This could be incorporated by a simple slider that would allow users to filter the expenditure based on a set range of years. This would allow for more historical context and reveal long-term patterns, which were otherwise not shown. 

That being said, I am excited to try out the various interactive features that I can incorporate in my redesign such as slider filters, hover over segments to get deeper insights, or filtering by region. I think by adding a layer of interactivity to the audience, it help add depth to the chart and broaden the engagement of the chart to both the casual and expert segment of the audience. 

## Step three: Sketch a solution

So for my solution, I feel like the important story that I would like to tell is the dominance of U.S.A. in the world military expenditure, particularly by how much they take up the total world military spending. I decided to redesign the visualization from a pie chart to a tree map. I feel like this chart would help me place emphasis on the dominance of United States, taking up almost half of the total military spending. This would help improve the visual perceptibility and comparative accuracy aspect of the chart that is limited in the original. Tree map also leaves more space for me to add tooltips so I could further add clarity to the chart by adding relevant information such as percentage and the exact dollar amount of spending.

<div class='tableauPlaceholder' id='viz1743640595143' style='position: relative'><noscript><a href='#'><img alt='Top 10 Countries by Military Spending (2021) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Mi&#47;MilitarySpendingSketch&#47;Sheet12&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MilitarySpendingSketch&#47;Sheet12' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Mi&#47;MilitarySpendingSketch&#47;Sheet12&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    
  var divElement = document.getElementById('viz1743640595143');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

## Step four: Test the solution

### Questions used for interviews: 

- Can you tell me what you think this is?

- Can you describe to me what this is telling you?

- Is there anything you find surprising or confusing?

- Who do you think is the intended audience for this?

- Is there anything you would change or do differently?

### Results: 

| Question | Interview 1 (In-class Critique) | Interview 2 (UW HCDE student)|
|----------|-------------|-------------|
|What is this?|A chart showing countries' military spending|Top 10 countries by military spending|
|What is it telling you?|The U.S. spends the most by far|The U.S. dominates in military spending|
|Anything surprising/confusing?|Surprised how much higher the U.S. is|Russia is surprisingly low, expected higher|
|Who is the intended audience?|General public or students in politics/econ|General public, people with some interest in politics|
|What would you change? |Use green colors, enlarge text, add dollar labels, |More relevant title to the narrative, add description to emphasize story, add country icons|

### Synthesis: 
Patterns in Feedback:
- Both users clearly understood the core message of the visualization.
- They identified the intended audience as the general public or those with interest in world affairs.
- Feedback highlighted the need for stronger visual emphasis and storytelling—including a more descriptive title and use of thematic colors.
- Both users suggested improving legibility by enlarging text and adding data labels.
- One interviewee recommended adding icons or country markers for quicker recognition.

Key Takeaways & Design Changes:
- Switch to military green tones for thematic coherence.
- Create a narrative-driven title that reinforces the key insight (e.g., "How the U.S. and China Outspend the World").
- Increase font size to improve readability.
- Add total dollar amounts inside each box to reinforce data accuracy.
- Explore adding icons (such as flags or military symbols) for visual interest and clearer country identification.

## Step five: build the solution

In the final version of the visualization, I redesigned the chart using a tree map layout to improve perceptibility and comparison between countries. I changed the color palette to military-themed green tones to better align with the topic. The title was updated to be more narrative and informative, reflecting the central story of disproportionate global military spending. I also increased the font size for readability and included dollar amounts and percentage values directly within each country's box to provide clear, at-a-glance data. These changes enhance both the clarity and visual impact of the chart while making it easier for viewers to interpret and engage with the information. I decided to add a description to provide more emphasis and clarity to the story I'm trying to highlight. While adding country flags as icons was suggested during my interviews, I decided against it because it makes the blocks too cluttered and could be distracting, having the country names I believe is sufficient enough.

<div class='tableauPlaceholder' id='viz1743643073023' style='position: relative'><noscript><a href='#'><img alt='Global Military Spending in 2021: The US Outspends the WorldThe United States alone accounts for over half of all global military spending, with China and India rounding out the top three. This chart reveals how military budgets are distributed among leading nations.(Source: https:&#47;&#47;www.visualcapitalist.com&#47;ranked-top-10-countries-by-military-spending&#47;) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Mi&#47;MilitarySpendingFinal&#47;Sheet13&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MilitarySpendingFinal&#47;Sheet13' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Mi&#47;MilitarySpendingFinal&#47;Sheet13&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1743643073023');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

## References
- https://www.visualcapitalist.com/ranked-top-10-countries-by-military-spending/
- https://data.world/makeovermonday/2022w35 

## AI acknowledgements
I used AI to fix grammar and workflow for some of my answers.
