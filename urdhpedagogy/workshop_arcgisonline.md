# ArcGIS Online Basic Map Workshop

## Signing In

The University of Richmond provides students along with instructors the opportunity to login to ArcGIS online using their netid's and passwords.  As a result, ArcGIS online is a relatively simple tool to get setup for class assignments, but its interface is admittedly clunky.  It is largely meant for more high-end GIS analysis but we can also use it to create other visualizations like StoryMaps.  In ArcGIS, we need to create a map before importing it to ArcGIS' "StoryMap" application, or any other application for that matter.  

Let's go ahead [login](https://urichmond.maps.arcgis.com).  Once you have logged in, click "Map" at the top. ArcGIS will create a default map for us.

![](https://github.com/nolauren/workshops/blob/master/img/arcgis_create_map.png)

## Setting the Foundation for Our Map

At the top of the interface, you will see three buttons: Details, Add, and Basemap.  Basemap allows us to change the look of our maps.  The most common type of basemaps are listed here.  We are going to choose the one labeled "Streets."     

![](https://github.com/nolauren/workshops/blob/master/img/arcgis_basic_layout.png)

## Creating Points of Interest

Now that we have changed the basemap, we need to add points to the map.  ArcGIS uses the concept of "layers" to add features to a map.  You may have seen similar terminology in programs, such as Photoshop.  We can toggle these layers on and off to show different points in our map along with importing layers online.  In this tutorial, we are going to create a map of Richmond that shows where we work, our favorite restaurants, and sites of interests for visitors to see.

Type in the "University of Richmond" into our search bar.  As you will see, when you begin typing, ArcGIS automatically shows a list of results.  Hit enter when you find the University of Richmond, and the map will zoom in to show the location.  

![](https://github.com/nolauren/workshops/blob/master/img/arcgis_university_of_richmond.png)

We now need to now add the point to our layer by clicking "Add to Map Notes."  

![](https://github.com/nolauren/workshops/blob/master/img/arcgis_add_work_map_notes.png)

On the left-hand side of the navigation, you can see that our new layer.  We can rename the layer by clicking the three dots under Map Notes and choosing "Rename".  We are going to change the name for this layer to "Work."  

1. To edit the popup for the point itself, we can click on it and choose "Edit." 
2. A new popup window will appear allowing us to configure our point.  Type in any title or description that you find accurate for the university.  
3. We are also going to change the symbol by clicking the "Change Symbol" button.  A display of available symbols for our project will now show.  
4. Pick your favorite and click "Ok."  

![](https://github.com/nolauren/workshops/blob/master/img/arcgis_edit_symbol.png)

## Saving Maps

It is important to always save our map in case we run into technical problems or want to get back to it later.  
1. Click the button at the top that says "Save" and give your map a title and summary.  
2. You will need to provide at least one tag.  At the University of Richmond, your map is automatically placed in your default folder.

## Add Additional Layers 

Now that we have created the foundation for our map and saved it, we will add additional layers.  In this tutorial, we are going to add a list of places to eat and any places of interest.  

1. Follow the same process of searching for addresses and adjusting the pop-up that is outlined above.  
2. When we add a new point this time, we need to put it in a new layer.  Next to the text that reads "Add to Map Notes" after you click on the point, you should see a small arrow.  
3. Click the small arrow and click on the "New Map Notes" layer.  

![](https://github.com/nolauren/workshops/blob/master/img/arcgis_new_map_notes_restaurants.png)

On the left-hand side, you should see a new section with our map note.  Rename it as you did above to "Restaurants" and add four or five additional points.  Each time, make sure that you are clicking the small arrow and adding to the correct layer.

Follow the same process for places of interest around the city but rename this map layer "Sites of Interest."

## Add Layers from the Internet

We have created our own layer and the map is now starting to take shape.  The power of ArcGIS Online, however, really starts to shine when we start adding layers from the internet and sharing our own.  

1. At the top of the interface, click "Add" and then "Browse Living Atlas Layers."  
2. Click the drop-down arrow next to the words "Living Atlas" 
3. Click on ArcGIS Online.  

![](https://github.com/nolauren/workshops/blob/master/img/arcgis_browse_living_atlas.png)

This will show you a list of over a million layers that are available for us to use.  Before you add a layer, it may be helpful to see what is available and to get ideas.  

Search "Richmond_region_poverty" and select the map. 

![](https://github.com/nolauren/workshops/blob/master/img/arcgis_richmond_poverty.png)

The new layer will add to your map along with the layers we have created.  You may need to zoom out/in to view the new layer, which shows poverty in the region.  

We can manipulate this data to show it in different ways.  Underneath the layer name on the left, you will see four symbols.  Hovering over them will display what each button does.  Let's go ahead and click on the left most symbol to see a legend of our data.

To see the raw data, click the table icon and a new window will pop up underneath the map.  We are not going to manipulate this data for this tutorial, but you may want to look at it to familiarize yourself.

Next to the table icon, you should see a symbol made up of a triangle, square, and circle.  This allows us to easily change the style of our map.

![](https://github.com/nolauren/workshops/blob/master/img/arcgis_change_style.png)

Click on the change style button and go to "Counts and Amounts."  

![](https://github.com/nolauren/workshops/blob/master/img/arcgis_counts_and_amounts.png)

After that, click on Options and then Symbols.  Choose your favorite color scheme and go back to your map.

## Conclusion

By creating our map, we can now ask questions visually that were difficult to examine before.  ArcGIS Online and ArcGIS Desktop provide us tools for advance GIS analysis but just viewing our data spatially already opens up interesting questions:  

* Is there a relationship between the restaurants you chose and the poverty of the population that surrounds them?  
* How does the income of the population around the University of Richmond compare to those around your favorite sites and restaurants?  
* Is there a relationship between the sites of interest and poverty? 

ArcGIS is a powerful tool, so see what other questions you can come up with and explore.  

