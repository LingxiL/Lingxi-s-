# Assignment 3


# Description
The data visualization I found is from the World Health Organization official website. It is a report of “Top 10 death causes in 2016” that under the Newsroom sector. And the database they use is also from their own organization. The aims of this article are to present the general idea of what is the top 10 causes of death over the world, as well as addressing the attention on public healthcare to different income groups.

Here is the link for the report: https://www.who.int/news-room/fact-sheets/detail/the-top-10-causes-of-death

To start with, listed different numbers/causes that come from the database, and also tried to make the comparison between the year 2016 with the year 2000 to see the improvement through 6 years.

![data visualization](/Screen Shot1.png)
![data visualization](/top102000.png)

The other part of the article compared the top 10 lists between different income groups. The reason for doing that is to point out what kind of factor might be ignored by public authorities since the death causes for “low-income group” are different from “high-income group,” and low-income community is always lack of data collection and always being ignored.

![data visualization](/lowincome.png)
![data visualization](/highincome.png)


# Wireframes
In order to fully present the intention of the article through data visualization, my re-design uses different colors to make the graph looked more comfortable, as well as change the major trick marks from 2000 to 1000 to increase the understandability for the bar graph. Since the article uses the year 2000 to make the comparison, I tried to add arrows next to the bar to show the change of rank of each cause (as I draw in the sketch.)

![data visualization](/sketch1.jpg)

As for the income group comparison, I only selected two colors to make the “new cause” more obvious. By saying “new cause,” I mean the cause that doesn’t exist in the high-income group but does exist in the low-income group. Those causes are critical since they are the causes always being ignored and should be noticed by public authorities.

![data visualization](/sketch2.jpg)


# Feedback

After sharing my wireframe with others, I got feedbacks/suggestions as follows:
- Can not really understand the “arrows”/ If the graph marks “ranks,” why not also mark how many ranks did they change, or the rank that didn’t change?
- Wants more explanations on “new causes.”/ Is the “new cause” only appear in the year 2016?
- Why not put low-income and high-income groups together you want to fo the comparison?

Based on the feedback, I decided to do these additional changes:

- Change the order, put the year 2000 ahead of the year 2016, to make the ranks change more understandable.
- Change the order of income groups, put the high-income group ahead, and to emphasize the low-income group
- Use a different color for the up and down arrow, use the third color to mark the ranks that did not change
- Provide more explanations for “new cause”

And the new data visualization are as follow:


# Global causes
- Year 2000
<html>
<head></head>
<body>
<div>
<p><br></p >
</div>
<div class='tableauPlaceholder' id='viz1568927765076' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Q9&#47;Q9RCCBJJ3&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;Q9RCCBJJ3' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Q9&#47;Q9RCCBJJ3&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1568927765076');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
</body>
 </html>

- Year2016

<html>
<head></head>
<body>
<div>
<p><br></p >
</div>
<div class='tableauPlaceholder' id='viz1568927673494' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;to&#47;top10-2016&#47;Sheet3&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='top10-2016&#47;Sheet3' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;to&#47;top10-2016&#47;Sheet3&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1568927673494');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
</body>
 </html>
 
 # Income group
 
<html>
<head></head>
<body>
<div>
<p><br></p >
</div>
 <div class='tableauPlaceholder' id='viz1568944491845' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;hi&#47;highincome&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='highincome&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;hi&#47;highincome&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1568944491845');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
</body>
 </html>
 
 
