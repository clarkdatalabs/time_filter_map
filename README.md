
>by Julie Cruz, Rheagan Martin, Jordan Earnest, Lihan (Neil) Zhu

[!["example outcome"](https://github.com/clarkdatalabs/time_filter_map/blob/master/img/Final1.png )](https://clarkdatalabs.github.io/time_filter_map/MapSite)

___

## Introduction
A client of ours had a set of data about the accommodation information of a group of UMich students in Ann Arbor for decades, and they wanted the information to be visualized so that the audience have a straight-forward understanding of "**During When**, **How many** students live **Where**."

Our client was satisfied with our final outcome. Due to NDA, the original project is not supposed to be shared by us. However, we find its core function, the map with time filter, has a lot of potentials for scalability. In addition, although there are existing examples of either Leaflet Map or Range Selector, few of them applying the selector to maps exist. 

Therefore, we have modified the project to share the core function as an handy example while not showing any confidential information.


## Check the Example Map
Following the steps below, you can easily run a map with a time filter on your local server, and further customize it as your will.

#### Download the Code
[Download the Zip file](https://github.com/clarkdatalabs/time_filter_map/blob/master/MapSite.zip).
Unzip the file and you will get a folder named "MapSite" with following folders/files:
1. Folder "data": the data formatted as GEOJSON is inside here.
2. Folder "forSlider": the JS and CSS files needed for the time filter.
3. File "index.html"
4. File "script.js"
5. File "style.css"

#### Run on the Local Server

Typically, you'd be able to right click on the index.html file and open it with a web browser to render the webpage. If you try this, you'll likely notice that D3 doesn't render. This is because we need a server to run D3:

1. Open your terminal(Mac) or Command Prompt(Windows).
2. Cd into the dir your html is currently at. For example: `cd Desktop/MapSite`
3. Enter:`python -m SimpleHTTPServer 8000` or `python3 -m http.server`

Now you&#39;re ready to render the HTML files. Click on [local host](http://localhost:8000) to have a look. 

## Customize for Your Data
