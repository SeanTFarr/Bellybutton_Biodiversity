<img src=static\images\title.png>

## Overview of Project
-----------------
Labs across the country have had success in synthesizing meat from algae, fungi, and microorganisms found on plant roots, but is that the only place to find a source of bacteria? This question prompted a biological reasearcher to look into the possibility of finding a useful bacteria on the human body. To test this hypothesis, samples were taken from the navels of people across the nation to identify bacterial species that live in our belly buttons. An ID number was assigned to the test subjects  to allow them to stay anonymous. This dashboard was created using JavaScipt to read and parse through a JSON data file to ultimately display the data to both the participants and the researchers.
#### Tools used to build the page:
- JavaScript
- Plotly
- D3.js
- HTML
- Bootstrap
----------
## Navigating the page:
Before sending you straight to the page, here is what to look for and some clarity about what you are about to see.

 First select ID# from dropdown list. This will give you the demographic information of the test subject and will set up the interactive charts.
 
<img src=static\images\dropdown.png>

The three charts on the dashboard are:
1. "Top 10 Bacteria Cultures Found" This bar chart shows you the top 10 Operational Taxonomic Units or OTUs (species or bacteria types) found in each sample. By moving the cursor over the bar the OTU name(s) is(are) revealed. 
 
 <img src=static\images\top_10.png>


2. "Belly Button Washing Frequency" is a gauge chart that displays the amount of "Scrubs" per week.

<img src=static\images\gauge.png>

3. "Bacteria Cultures Per Sample" is a bubble chart that shows all of the cultrures found in a sample. the bubbles are sized based on the amount of the culture and the color is based on the ID numbers.

<img src=static\images\bubble.png>

## Now you are ready! To view the interactive page [Click here](https://seantfarr.github.io/Bellybutton_Biodiversity/)
