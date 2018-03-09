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
      
      Improvements (Please go to Update.MD)
      
      Conclusion

      Resources and credits 


## Source of data: ENEDIS open data

Enedis is a public service company, which manage the electricity distribution network to more than 35 million client. It developes, implementes and modernise the electricity. It particularly works on data from electricity meters. With the energy transiton and the talks about smartcities and modernisation, ENEDIS created a website, in whcih they let free acces to their data. 

[If you are curious and you are interested in learning more about ENEDIS Open data ! Click now ](https://data.enedis.fr/page/accueil/?flg=fr)

The data  available is consisting of the eletricity consumption sorted by total number of people using it, regions and activity sectors. But also the sum of electricity production for many years sorted by the way of producuction (solar, hydraulic, Cogeneration or others)  

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

The map shown below allows to the user the control of the radar chart because they are both synchronized. It means that when you click on a region, you can see the radar chart for the one selected. 

It allows also the user to the get an idea of clients of Enedis in France regions.

<figure>
  <p align="center"> <img src="/Img_project_final/cartefr.JPG" width=60% />
</figure>

# Radar chart :

The Radar chart, as it’s shown below, presents the electricity consumption per field. We manage to change the scale of this chart in a way that the max of the radar chart change with Region changing. 

<figure>
  <p align="center"> <img src="/Img_project_final/radarchart.JPG"  />
</figure>
            
Even if residential field consume the most of electricity, its average consumption lower than the industrial average, and which is normal, due to the fact, that industries have many machines, and electrical installations .

# Sankey diagram:

<figure>
  <p align="center"> <img src="/Img_project_final/sankey.JPG"  />
</figure>

The Sankey chart, presents Electricity general consumption in France.
It contains two dynamic ribs. The left one, allows the user to select and move a specific region, while the right one, allows to select and move the field (residential, industrial….) 
Of course you can select a specific target ( e.g. Ile de France -> Conso tertiaire) and just put the mouse pointer over it , and get some details, like the annual electricity consumption of this target .


# Stacked/Grouped Bar chart :

This bart chart shows the evolution of electricty production (MWh) in France from 2011 to 2016.

It is sorted by years and the way in which the electrical energy was produced.

The grouped version, shown below,  allows the user to compare the amount of energy produced by different methods (Cogeneration, Hydraulic, Solar..)

The Stacked version is also important because it gives the sum energy produced every year and also the part of every way of production.

<figure>
  <p align="center"> <img src="/Img_project_final/grouped.JPG" width=100%/>
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

## Improvements: 

[Please go to Update.MD !](https://github.com/hichamelhady/ConsoElec/blob/master/Update.md)

However, there are still some improvement that we can make to increase the insatiability and functionality of our project. At first, we can add the alarming consummation level for each sector and in each region. In this case, the companies will receive the notification when the electricity supply might be not enough. Besides, we can also add a pie chart of produced electricity sorted by ways of production and synchronised with the map. When you click on a region you will have not only the radar chart of consumption and sectors but also a pie chart of electric energy produced sorted by ways. Unfortunately the data is too heavy ! So we are now limited to the global stacked / grouped bar chart where a a comparison between the years were presented.

## Conclusion: 

Overall, our ConsoElec project can gave the public, the electricity companies and the client companies a direct view for the data.

With these interactive graphics, the public can understand the electricity distribution and level of consummation in their region. they can also find how the electricity was distributed and organized in an easy way. 

For the electricity companies, they will be able to find the consummation changes and the electricity distributions in different regions and in different sectors. besides, these indicator and visualizations can gave them a direct and first-hand feedback for their work. They can make the necessary changes and controls during the high-demanded season in order stabilize the electricity supply. The electricity company can also use the different graphics to change the strategy of the electricity supply , to improve the electricity supply network As well as to decides the electricity price and possible offer. 

To the client companies, especially for the search engine companies like google, Facebook, Yahoo, who has the huge need of electricity to take care of the server and cool down the machine, they need to have a good analyze of the electricity distribution and organization while choosing their local server and set up the subsidiary. 

## Resources and credits :

* [Interactive Data Visualization course (ECL MOS 5.5) - Romain Vuillemot](https://github.com/LyonDataViz/MOS5.5-Dataviz)

* [Stacked / grouped bar chart inspired from Mike Bostock’s Block 3943967](http://bl.ocks.org/mbostock/3943967)

* [Radar chart inspired from alandunning’s Block ](http://blockbuilder.org/alandunning/4c36eb1abdb248de34c64f5672afd857)

* [Sankey diagram inspired from HarryStevens’s Block ](http://blockbuilder.org/HarryStevens/0a437a96e9a2aa2408adbd32b1853cc3)

* [ENEDIS Open DATA webesite](https://data.enedis.fr/page/accueil/?flg=fr)

