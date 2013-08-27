# Global Mapping Applications

![Screenshot of Map using LeafletJS under Google Chrome in OS X](Map/Screenshot.png)

This repository contains two folders: Mapbox.js Webpage and LeafletJS webpage. 
They both produce an interactive map of the world using different JavaScript libraries and mapping providers,
though they are all based on the D3.js similar JavaScript techniques.

## Differences

The main differences are the JavaScript libraries used to create the map in both cases. Mapbox.js uses mapbox.js and 
LeafletJS uses Leaflet.js. The former runs well under WebKit browsers but falls short under Firefox or IE. 

The latter however works under all browsers. Some versions of Internet Explorer have difficulty in rendering 
the SVG and interactive layer graphics though it still performs amicably under most circumstances and remains
usable throughout. ActiveX controls run through Internet Explorer and these systems will initially block the 
JavaScript content. 

## Data

Data was collected using a survey that was sent electronically to all academics (excluding post doctoral researchers 
and post graduate students) with the aim of surveying the nationalities of Cardiff University's academic staff. It
was also used to obtain data on the number of worldwide collaborative research projects that links Cardiff to other
universities around the world. 

Alumni data was also used to showcase the university's links with undergraduate students from countries across
the globe. This is data valid for academic year 2012/2013

## What To Do When Things Go Wrong

Every effort has been made to test these applications under a wide variety of browsers and ecosystems. Inevitably 
minor bugs may fall through the cracks. 
