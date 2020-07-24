# Web Design Homework - Web Visualization Dashboard (Latitude)

## Background
This project uses HTML and CSS to create a dashboard showing off the analysis I have done in a previous assignment. Specifically, I'll be plotting weather data (Resources/cities.csv).

## Latitude - Latitude Analysis Dashboard with Attitude
In building this dashboard, I created individual pages for each plot and a means by which you can navigate between them. These pages contain the visualizations and their corresponding explanations. It will also have a landing page, a page where you can see a comparison of all of the plots, and another page where you can view the data used to build them.

### Website Requirements
The website consists of 7 pages total, including:
* A landing-page containing:
  * An explanation of the project.
  * Links to each visualizations page.
* Four visualization pages, each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A "Comparisons" page that:
  * Contains all of the visualizations on the same page so you can easily visually compare them.
  * Uses a bootstrap grid for the visualizations.
    * The grid is two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A "Data" page that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table is a bootstrap table component. (https://getbootstrap.com/docs/4.3/content/tables/#responsive-tables)
    * The data came from exporting the `.csv` file as HTML.

The website, at the top of every page, has a navigation menu that:
* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
* Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.
* Is responsive (using media queries).

Finally, the website is deployed to GitHub pages.

### Bonuses
* Has a visualization navigation on every visualizations page with an active state.
