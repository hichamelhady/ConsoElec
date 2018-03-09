# ConsoElec  - An interactive way to understand the electricity consumption

Project done by : 
- EL BOUJDAINI Idriss 
- EL-HADY Hicham 
- LIU Kun  

## Table of contents :

      Source of data: ENEDIS open data

      Data visualisation - Goal of the project

      Data visualisation - Results of the project ConsoElec

      Link to Video 

      Resources and credits 


## Source of data: ENEDIS open data

Enedis is a public service company, which manage the electricity distribution network to more than 35 million client. It developes, implementes and modernise the electricity. It particularly works on data from electricity meters. With the energy transiton and the talks about smartcities and modernisation, ENEDIS created a website, in whcih they let free acces to their data. 

[If you are curious and you are interested in learning more about ENEDIS Open data ! Click now ](https://data.enedis.fr/page/accueil/?flg=fr)

The data is available is consisting of the eletricity consumption sorted by total number of people using it, regions and activity sectors. But also the sum of electricity production for many years sorted by the way of producuction (solar, hydraulic, Cogeneration or others)  

## Data visualisation - Goal of the project
Our work aim to help producers of energy, the users and also public function services to control their consumption of electricla energy and to predicte the amont of production basing on demand history for each region. To do this, we represented the data that we have in four ways : 

- Diagram of sankey representing the flow of electrical energy consumption in different sectors of activity sorted by regions

- Geomapping with a visualization of demography of each region and when we choose a region, an other graph appears to presesnts the energy consumption for the selected region, sorted by sector of activity for each unit.

- A grouped/stacked bar chart visualising the temporal evolution of the energy production in france.

## Data visualisation - Results of the project ConsoElec

Our website looks like this :

![Sheet1](/Img_project_final/1.JPG)
![Sheet2](/Img_project_final/2.JPG)

# France map :

![Sheet3](/Img_project_final/cartefr.JPG)

The map is a tool that allows the user the control the radar chart (both are synchronized), and at the same time, allows the user the get an idea of population of a region.

# Radar chart :

![Sheet4](/Img_project_final/radarchart.JPG)

The Radar chart, as it’s shown above, present the electricity consumption per field. We manage to change the scale of this chart in a way that the max of the radar chart change with Region changing. 
            
            Interpretation:
            Even if residential field consume the most of electricity, its average consumption lower than the industrial average, and which is normal, due to the fact, that industries have many machines, and electrical installations .

# Sankey diagram:

![Sheet5](/Img_project_final/sankey.JPG)

The Sankey chart, presents Electricity general consumption in France.
It contains two dynamic ribs. The left one, allows the user to select and move a specific region, while the right one, allows to select and move the field (residential, industrial….) 
Of course you can select a specific target ( e.g. Ile de France -> Conso tertiaire) and just put the mouse pointer over it , and get some details, like the annual electricity consumption of this target .


# Stacked/Grouped Bar chart :

<figure>
  <p align="center"> <img src="/Img_project_final/grouped.JPG" width=80% />
</figure>

## Link to Video : 

[Here it is !! Thanks you for watching and feel free to ask us](https://www.youtube.com/watch?v=3WGgQxnGbuw&feature=youtu.be)

  </p>
<a href="https://www.youtube.com/watch?v=3WGgQxnGbuw&feature=youtu.be">
<figure>
  <p align="center"> <img src="/Img_project_final/youtube.JPG" width=80% />
</figure>
</a>

<p align="center"> <i>Youtube </i> </p>
    <p align=justify>
</p>


## Resources and credits :

* [Interactive Data Visualization course (ECL MOS 5.5) - Romain Vuillemot](https://github.com/LyonDataViz/MOS5.5-Dataviz)

* [Stacked / grouped bar chart inspired from Mike Bostock’s Block 3943967](http://bl.ocks.org/mbostock/3943967)

* [Radar chart inspired from alandunning’s Block ](http://blockbuilder.org/alandunning/4c36eb1abdb248de34c64f5672afd857)

* [Sankey diagram inspired from HarryStevens’s Block ](http://blockbuilder.org/HarryStevens/0a437a96e9a2aa2408adbd32b1853cc3)

* [ENEDIS Open DATA webesite](https://data.enedis.fr/page/accueil/?flg=fr)

