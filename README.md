# Sankey diagram with Highcharts and Python

Highcharts' new release will contain a lot of cool stuff. Among them, Sankey Diagrams !
An Early release for testing propose was shared - thanks [@MusMekh](https://twitter.com/MusMekh)!
You can find it on this [JSfiddle](http://jsfiddle.net/gh/get/library/pure/highcharts/highcharts/tree/samples/highcharts/studies/sankey-diagram/)

This folder contain a python script to clean, prepare the data and write the HTML file hosting the diagram.

For this example we will use data from the United Nations High Commissioner for Refugees, more precisely, data from the [population statistics](http://popstats.unhcr.org/en/overview) which take account of the number of Syrian refugees and asylum seekers in 2016 and their destination.

The data extracted were displaced people considered as 'Refugees (incl. refugee-like situations)' or 'Asylum-seekers (pending cases)') from Syrian to all other countries. The corresponding database is available as a CSV in this folder

For readibilty purpose we decided to display only the countries for which more than 1,000 refugees or asylum seekers arrived. 
