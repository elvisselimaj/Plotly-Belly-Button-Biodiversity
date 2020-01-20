{\rtf1\ansi\ansicpg1252\deff0\nouicompat{\fonttbl{\f0\fnil\fcharset0 Calibri;}{\f1\fnil\fcharset0 Courier New;}}
{\colortbl ;\red0\green0\blue255;}
{\*\generator Riched20 10.0.18362}\viewkind4\uc1 
\pard\sa200\sl276\slmult1\f0\fs28\lang9 # Publish HomeWork \par
{{\field{\*\fldinst{HYPERLINK https://elvisselimaj.github.io/Plotly-Belly-Button-Biodiversity-ES/ }}{\fldrslt{https://elvisselimaj.github.io/Plotly-Belly-Button-Biodiversity-ES/\ul0\cf0}}}}\f0\fs28\par
\fs22\par

\pard\f1\lang1033 # Plot.ly Homework - Belly Button Biodiversity\par
\par
![Bacteria by filterforge.com](Images/bacteria.jpg)\par
\par
In this assignment, you will build an interactive dashboard to explore the [Belly Button Biodiversity dataset](http://robdunnlab.com/projects/belly-button-biodiversity/), which catalogs the microbes that colonize human navels.\par
\par
The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.\par
\par
## Step 1: Plotly\par
\par
1. Use the D3 library to read in `samples.json`.\par
\par
2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.\par
\par
* Use `sample_values` as the values for the bar chart.\par
\par
* Use `otu_ids` as the labels for the bar chart.\par
\par
* Use `otu_labels` as the hovertext for the chart.\par
\par
  ![bar Chart](Images/hw01.png)\par
\par
3. Create a bubble chart that displays each sample.\par
\par
* Use `otu_ids` for the x values.\par
\par
* Use `sample_values` for the y values.\par
\par
* Use `sample_values` for the marker size.\par
\par
* Use `otu_ids` for the marker colors.\par
\par
* Use `otu_labels` for the text values.\par
\par
![Bubble Chart](Images/bubble_chart.png)\par
\par
4. Display the sample metadata, i.e., an individual's demographic information.\par
\par
5. Display each key-value pair from the metadata JSON object somewhere on the page.\par
\par
![hw](Images/hw03.png)\par
\par
6. Update all of the plots any time that a new sample is selected.\par
\par
Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown below:\par
\par
![hw](Images/hw02.png)\par
\par
## Advanced Challenge Assignment (Optional)\par
\par
The following task is advanced and therefore optional.\par
\par
* Adapt the Gauge Chart from <{{\field{\*\fldinst{HYPERLINK "https://plot.ly/javascript/gauge-charts/"}}{\fldrslt{https://plot.ly/javascript/gauge-charts/\ul0\cf0}}}}\f1\fs22 > to plot the weekly washing frequency of the individual.\par
\par
* You will need to modify the example gauge code to account for values ranging from 0 through 9.\par
\par
* Update the chart whenever a new sample is selected.\par
\par
![Weekly Washing Frequency Gauge](Images/gauge.png)\par
\par
## Deployment\par
\par
Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo.\par
\par
## Hints\par
\par
* Use `console.log` inside of your JavaScript code to see what your data looks like at each step.\par
\par
* Refer to the [Plotly.js documentation](https://plot.ly/javascript/) when building the plots.\par
\par
### About the Data\par
\par
Hulcr, J. et al.(2012) _A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable_. Retrieved from: [{{\field{\*\fldinst{HYPERLINK http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/](http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/) }}{\fldrslt{http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/](http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/)\ul0\cf0}}}}\f1\fs22\par
\par
- - -\par
\par
\'c2\'a9 2019 Trilogy Education Services\par
\par

\pard\sa200\sl276\slmult1\f0\lang9\par
}
 