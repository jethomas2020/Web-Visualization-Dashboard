# Web-Visualization-Dashboard

# City Latitude Dashboard

-----------------
# Background 

-----------------
Data is more powerful when we share it with others! Let's take HTML and CSS to create a dashboard showing off the analysis we've done! 

Latitude - Latitude Analysis Dashboard with Attitude

For this project, we'll be creating a visualization dashboard website using visualizations we've created previously. 
Specifically, we'll be plotting weather data.

In building this dashboard, we'll create individual pages for each plot and a means by which we can navigate between them. 
These pages will contain the visualizations and their corresponding explanations. 

We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can 
view the data used to build them.

----------------------------
# Website Features

The website consists of 7 pages total, including:

    - A landing page containing:
        An explanation of the project.
        Links to each visualizations page. There is a sidebar containing preview images of each plot, and clicking an 
        image should takes the user to that visualization.
        
    - Four visualization pages, each with:
        A descriptive title and heading tag.
        The plot/visualization itself for the selected comparison.
        A paragraph describing the plot and its significance.
        
    - A "Comparisons" page that:
        Contains all of the visualizations on the same page so we can easily visually compare them.
        Uses a Bootstrap grid for the visualizations.
            
    - A "Data" page that:
        Displays a responsive table containing the data used in the visualizations.
            The table is a bootstrap table component.
            The data comes from exporting the .csv file as HTML, and converting it to HTML. 
            We used Pandas that also has a nifty method approprately called to_html that allows us to generate 
                a HTML table from a Pandas dataframe.
                
Finally, the website has been deployed to GitHub pages.  https://jethomas2020.github.io/Web-Visualization-Dashboard/

The website, at the top of every page, has a navigation menu that:

    - Has the name of the site on the left of the nav which allows users to return to the 
        landing page from any page.
    - Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each 
        individual visualization page.
    - Provides two more text links on the right: "Comparisons," which links to the comparisons page, and 
        "Data," which links to the data page.

-------
# Site published at: 
https://jethomas2020.github.io/Web-Visualization-Dashboard/


