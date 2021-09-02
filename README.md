# web-design-challenge


## Background

Data is more powerful when we share it with others! Here, I'll take what we've learned about HTML and CSS to create a dashboard showing off the analysis we've done.


## Latitude - Latitude Analysis Dashboard with Attitude

I created a visualization dashboard website using visualizations we've created in a past assignment. Specifically, we'll be plotting [weather data](Resources/cities.csv).

In building this dashboard, I create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. I also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Features

* A landingpage containing:
  * An explanation of the project.
  * Links to each visualizations page and a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
* Four visualization pages, each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A "Comparisons" page that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
* A "Data" page that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table has a bootstrap table component. (https://getbootstrap.com/docs/4.3/content/tables/#responsive-tables)
    * The data came from exporting the `.csv` file as HTML, or converting it to HTML. 
* A navigation menu that: 
  * Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
  * Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
  * Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.

Finally, the website was deployed to Githubpages. 
