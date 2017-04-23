# CanvasAndImageMaps

In this lab you will use jQuery, the HTML5 Canvas element and an image map to create a Hamilton-area information map as in the working solution. Hovering over any of the area bounded by one city must highlight that city in a different colour. Clicking within the area bounded by one city must highlight that city in a different colour and display information about the city below the map.

Use the HTML5 Boilerplate template for this lab. Use the classic theme of HTML5 Boilerplate available at: http://www.initializr.com/. Don't select any of the options, as they won't be needed.

Ensure that you are using a standard directory layout. You should have a directory structure similar to this: css/ , img/, js/, js/vendor, js/main.js, js/plugins.js . Ensure that both Modernizr and jQuery JavaScript libraries are installed with HTML5 Boilerplate, as you will be needing these libraries for the lab. Style the page so that it looks similar to the working solution.

Use the following image of the Hamilton-area: hamilton.png. Create an image map for each of the regions. It is recommended that you use an online image map tool (Google search) such as Easy ImageMap Generator to help create the image map.

When the user hovers within the area bounded by any city, the color of the city area must change: 02_canvas1_flamborough_hover.jpg.

When the user clicks within the area bounded by any city, the color of the city area must change (and this color must be different than the hover color). Also, an information panel beneath the photo must display information about the city: 03_canvas1_flamborough_clicked.jpg. When a city is clicked the following three pieces of information must be displayed at the bottom of the image: Name of City, Population, Text. Store this information in HTML somewhere on the page, and when a city is clicked, use jQuery hide()/show() functions to display the information about the city.

There is no required behaviour for the 2nd click on a city (i.e. no marks for handling this situation). However, you should try to come up with some reasonable way of handling this situation. For example, removing the color over the city and returning it to its previous state. Similarly, there is no required behaviour for when a user moves the pointer off of a city, but you should try to handle this situation as well.
