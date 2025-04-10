| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |


# FINAL PROJECT 1: STUDENT LOAN DEBT by Major and Earnings

## Outline
The cost of higher education in the U.S. has been rising steadily, but not all degrees offer equal financial returns. For many students, taking on debt is a necessity, yet whether that debt pays off can vary wildly by major. This project will explore the relationship between college majors, student loan debt, and post-graduation earnings, with the goal of answering a critical question: 

Which degrees offer the best return on investment, and which leave graduates financially underwater?

By visualizing this tradeoff across majors, I aim to help future students and families make more informed decisions about college.
This data story will use government-provided and publicly accessible datasets and be presented as an interactive web visualization to make the information digestible and actionable for students, educators, and policymakers alike.

1. Introduction – The Debt Dilemma
   - Quick context: average student loan debt, public concern.
   - Key stat teaser: “The average student borrows $XXXXX but what they earn after depends on their major.”

2. Degrees of Debt: What Students Owe by Major
   - Visualization: Bar chart of average loan amounts by major.
   - Highlight: Arts vs. STEM vs. Business vs. Health

3. The Payoff: Median Earnings After Graduation
   - Visualization: Scatterplot of major vs. median earnings (1-year and 5-year)
   - Layer in gender and race if data allows.

4. Debt-to-Income Ratio: Which Majors Are Trapped?
   - Visualization: Debt-to-income ratio heatmap or quadrant plot
   - Highlight which majors have the worst (and best) ROI

5. Outliers & Surprises
   - Pull out interesting anomalies: e.g. Nursing vs. Biology, CS vs. Physics
   - Quotes/stories from alumni or survey responses if possible

6. What majors are working to close the gap?
   - Visualization: Line chart highlighting debt-to-income ratio growth for majors with growing income.
   - Context: Have a list of colleges with free tuition for related majors, more funding, increased income, etc.

7. Conclusion: What This Means for Students Today
   - Pull it all together — key takeaways
   - Potential call to action for schools or policymakers


## Initial sketches

- Chart 1: Average Median Debt Across Fields of Study

<div class='tableauPlaceholder' id='viz1744258221408' style='position: relative'><noscript><a href='#'><img alt='Average Median Loan Amount by Area of Study ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Fi&#47;FinalProjectChart1&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='FinalProjectChart1&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Fi&#47;FinalProjectChart1&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    
 var divElement = document.getElementById('viz1744258221408');                    
 var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
 var scriptElement = document.createElement('script');                    
 scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
 vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

- Chart 2: Student earnings post grad by Area of Study

<div class='tableauPlaceholder' id='viz1744258483650' style='position: relative'><noscript><a href='#'><img alt='Median Earnings of Areas of Study ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Fi&#47;FinalProjectChart2_17442584742100&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='FinalProjectChart2_17442584742100&#47;Sheet2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Fi&#47;FinalProjectChart2_17442584742100&#47;Sheet2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
 var divElement = document.getElementById('viz1744258483650');                    
 var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
 var scriptElement = document.createElement('script');                    
 scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
 vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

- Chart 3: Debt-to-income Ratio by Area of Study

<div class='tableauPlaceholder' id='viz1744258777620' style='position: relative'><noscript><a href='#'><img alt='Debt-to-Income Ratio by Area of Study ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Fi&#47;FinalProjectChart3&#47;Sheet3&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='FinalProjectChart3&#47;Sheet3' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Fi&#47;FinalProjectChart3&#47;Sheet3&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    
 var divElement = document.getElementById('viz1744258777620');                    
 var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
 var scriptElement = document.createElement('script');                    
 scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
 vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

## The data
The primary dataset used in this project is the "Most Recent Cohorts Field of Study" file from the U.S. Department of Education's College Scorecard. This dataset includes detailed information on student loan debt and post-graduation earnings by academic major (identified through CIP codes) and degree level. It provides data across all U.S. institutions participating in federal financial aid programs and is updated regularly to reflect the most recent cohorts of graduates. The version used in this project was obtained in Excel format and includes loan amounts, earnings at 1 and 5 years post-graduation, and additional calculated fields.

To make the data suitable for analysis and visualization, the raw dataset was cleaned to remove entries marked as "Privacy Suppressed" (due to low student counts) and filtered to focus specifically on Bachelor's degree programs. A new column called area_of_study was created by grouping 2-digit CIP codes into broader categories such as Arts, Business, STEM, and Health Professions, enabling clearer comparisons across major academic domains. Additional metrics, including debt-to-income ratios, were calculated to assess the financial return on investment for each area of study. This cleaned and enriched dataset serves as the foundation for all visual storytelling components in the final project.

Link to dataset = https://collegescorecard.ed.gov/data

## Method and medium

In terms of cleaning the data, I will be using python to filter out NA or privacy secured data. I will be using Tableau to create the multiple data visualizations. Finally, results and findings will be presented with Shorthand. 

## References
- Dataset = https://collegescorecard.ed.gov/data
- Dataset Documentation = https://collegescorecard.ed.gov/data/data-documentation/

## AI acknowledgements
Used ChatGPT to fix grammar and word flow.
