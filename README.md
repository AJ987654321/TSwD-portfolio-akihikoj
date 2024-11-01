| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# TSWD-portfolio-templates
Portfolio templates for setting up your Telling Stories with Data site.  Edit these pages as you like for your own portfolio!  
Sometimes it's helpful to keep track of your web URL.  Consider putting that somewhere on your page for easy reference: 

- Web page URL: https://cmustudent.github.io/tswd-portfolio-templates/
- This repository: https://github.com/cmustudent/tswd-portfolio-templates/

# Portfolio
This is my public portfolio for Telling Stories with Data at CMU!  Here's where all my cool work will go.  You should probably hire me. 
 1. OECD Debt
    ![Debt Graph](export-2024-10-30T21_36_57.835Z.png)
 2. OECD Debt (Visualized in Tableau)
<div class='tableauPlaceholder' id='viz1730489656601' style='position: relative'><noscript><a href='#'><img alt='TableauWorkshop ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TS&#47;TSwD-AJ&#47;TableauWorkshop&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='TSwD-AJ&#47;TableauWorkshop' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TS&#47;TSwD-AJ&#47;TableauWorkshop&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
 var divElement = document.getElementById('viz1730489656601');
 var vizElement = divElement.getElementsByTagName('object')[0];
 vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
 var scriptElement = document.createElement('script');
 scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
 vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

3. OECD Debt (Visualized in my own way)
<div class='tableauPlaceholder' id='viz1730488402188' style='position: relative'><noscript><a href='#'><img alt='Which Region is the Unhelthiest? ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TS&#47;TSwD-AJ_2&#47;WhichRegionistheUnhelthiest&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'
style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='TSwD-AJ_2&#47;WhichRegionistheUnhelthiest' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TS&#47;TSwD-AJ_2&#47;WhichRegionistheUnhelthiest&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
 var divElement = document.getElementById('viz1730488402188');
 var vizElement = divElement.getElementsByTagName('object')[0];
 vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
 var scriptElement = document.createElement('script');
 scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
 vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>
The description below is how we aim to explain and how we made changes on the chart.
[Objectives]
To show the transitioning of average of th debt ratio to GDP per region.
[Points]
1. Categorized the region based on the countries. (Americas, Asia, Europe, Middle East)
   The original dataset has too many number of countries, and it might be difficult for readers to interpret the trend of the transitioning over time.
   Therefore, I have categorized the countries into 4 categories.
2. Changed the chart color not to be gradient but to distinguish by region
   Original chart was gradienting from Blue to Orange based on the percentage but this is not a good way to explain the differences between the regions.
   Therefore, I have allocated the colors to each line.
3. Drew the reference line at 100% to show the unhealthy threshold.
   In order to show which region is unhealthy, I have drawn the threshold line at 100% so that reader can understand that the area above is shown as unhealthy.
4. Greyed out the area below 100%.
   Highlight the unhealthiness of the area above the line, the area below the line is greyed out.
5. Filtered out 2019 data because that lacks Japan's data since it was the main driver of Asian average ratio.
   If I use all the data in the dataset, Asian unhealthiness looks to improve, but it is because that Japanese data is lacked. 
   Therefore, I have filtered out the data of 2019 to avoid misinterpretation.
6. Set the minimum as 30
   I have cut of the areas below 30 because the minimum value over time was 30. This emphasize the differences among regions.

Those changes could explain that the Asia was the unhelthiest region over time.

# About me
Hi, this is Akihiko Jo in MISM 16, and please call me AJ, because my full name is sometimes difficult to pronounce. I'm from Japan, and I have been working
for financial institutions for 15 years mainly as a project manager. I anticipate to obtain the skills from this course
to efficiently show the data to the executives in my company.
I am a father of 3 years old daughter, and my hobby now is to bring my daughter to the national parks in the United States.
![Self-Portrait](portrait.jpg)
# What I hope to learn
In our past career, it was always practical, and no educational backgroud about technologies. Therefore, we weould like to learn the points below for my future career: 

1. Technical Background<br>
   I aim to develop IT skills, including coding, which I have not studied systematically before. My goal is to acquire the skills
   necessary to make informed decisions when I eventually move into a management role.
2. Strategical Skills<br>
   I want to learn how to use technology in alignment with a company’s vision, enabling me to make decisions that reflect this vision.
   I’m interested in understanding how to incorporate the vision into daily activities and make sound strategic decisions
   in a volatile market environment.
3. Soft Skills<br>
   I want to develop knowledge in negotiation and conflict resolution,
   essential for implementing the decisions I make. This will equip me with the capability to execute my decisions effectively.
   

# Portfolio

# Examples
You can keep this section for stuff from in-class demos or your other work, or remove it. 

## Assignment: [Visualizing overnment Debt](visualizing-government-debt)
For this assignment, make sure you set up and link to a new page.  This page is linking to a new Markdown document called `visualizing-government-debt.md`.  For links to Markdown files in your repository, you can just include the name of the page without the `.md` extension. 

## Assignment 3&4: [Critique by Design](critique-by-design)
For this assignment, make sure you set up and link to a new page.  This page is linking to a new Markdown document called `critique-by-design.md`.  

## Final project
Here it might be helpful to include a high-level description of your final project. 
[Part I](final-project-part-one)
[Part II](final-project-part-two)
Part III(final-project-part-three)

---
## Other stuff you can do (you can remove this section - it's just for your reference.)

### Changing text

You can change text, like this: 

**Here's some bold** text.  Here's some *italic* text. Here's some ~~strikethrough~~ text. 

### Creating tables

You can build tables like this: 

| Name         | Type of pet | Favority activity 1 | FA 2   | FA 3            | FA 4                                |
|--------------|-------------|---------------------|--------|-----------------|-------------------------------------|
| Eli          | cat         | Sleeping            | Eating | Being pet       | Plotting to overthow dog empire     |
| Howard       | dog         | You                 | You    | You             | Eating                              |
| Frankenstein | fish        | Swimming            | Eating | Blowing bubbles | Forgetting                          |

An easy-to-use template generator tool [can be found here](https://www.tablesgenerator.com/markdown_tables)

You can use different headings, like this: 

# Here's a large title (H1)
## Here's a subtitle (H2)
### ...and so on (H3)
You get the idea - just don't forget the space between the # and your title.  `#Title` won't work, but `# Title` will. 

### Adding images

Here's an example of how to add an image to my portfolio.  

![funny dog picture](funny-dog-unsplash.jpg)
> Photo by <a href="https://unsplash.com/pt-br/@charlesdeluvio?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">charlesdeluvio</a> on <a href="https://unsplash.com/photos/K4mSJ7kc0As?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  

Alternately, you can set the size of the image using just a bit of HTML: 

<img src="funny-dog-unsplash.jpg" width="200"/>

Remember that you'll need to upload the image into your repository, or include a link to the image somewhere else.  

### Setting up a separate page

So here's the code you'll need to add to your own site to create a second page. 

1. First, create a new page in your repository (for example, dataviz1.md)
2. Next, add a link to that page by inserting the following into your readme.md page:

`[title](dataviz)` or `[dataviz](https://cmustudent.github.io/portfolio/dataviz.html)` or `[CMU](https://www.cmu.edu)`

Any of those formats will work. Here's some examples of working links: 

`[title](dataviz)` = [title](dataviz)  
`[dataviz](https://cmustudent.github.io/portfolio/dataviz.html)` = [dataviz](https://cmustudent.github.io/portfolio/dataviz.html)  
`[CMU](https://www.cmu.edu)` = [CMU](https://www.cmu.edu)   

Make sure to check these from your publicly accessible URL to make sure they're working correctly (not from the preview tab). 

Looking for more?  A nice Markdown guide [can be found here](https://www.markdownguide.org/cheat-sheet/)
