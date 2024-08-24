# World Happiness Visualization Project

This project visualizes the World Happiness data using Vega-Lite, showcasing various aspects of happiness scores across different countries over multiple years. The project includes interactive visualizations that allow users to explore the data in an engaging way.

Link to the webpage: https://warmhmk.github.io/Vega-Lite-project

### Files and Directories

- **`index.html`**: The main HTML file that contains the structure of the web page and includes the necessary scripts and stylesheets for the visualizations.

- **`css/styles.css`**: Contains custom CSS styles to style the web page and visualizations.

- **`data/`**: Contains the datasets used for the visualizations. The data files include:
  - `2015.csv`
  - `2019.csv`
  - `AB_NYC_2019.csv`
  - `Original_2017_full.csv`
  - `Original_2017_full2.csv`
  - `Original_2017_full3.csv`
  - `Original_2017_full4.csv`
  - `custom_NA.geo.topojson.json`: Custom TopoJSON file used for mapping.

- **`js/`**: Contains the Vega-Lite specifications for the visualizations.
  - `map.json`: Specifies the world map visualization.
  - `2019ranking.json`: Specifies the ranking visualization for 2019.
  - `year.json`: Specifies the visualization for life expectancy and social support over the years 2006-2016.

## Visualizations

The project includes three main visualizations:

1. **World's Happiness Score 2019**:
   - A map visualization showing the final happiness score of each country in 2019.

2. **World's Happiness Ranking 2019**:
   - A ranking visualization displaying the final score, GDP, freedom of life choices, and perceptions of corruption for each country in 2019.

3. **Life Expectancy and Social Support (2006-2016)**:
   - A time-series visualization showing the final score, life expectancy, social support, and democratic quality across different years.

## Technologies Used
- **Vega-Lite**: A high-level visualization grammar for producing sophisticated visualizations.
- **Vega-Embed**: Used to embed Vega-Lite visualizations into the web page.
- **HTML/CSS**: For structuring and styling the web page.
- **JavaScript**: For embedding the Vega-Lite visualizations.

## References
- [Vega-Lite Documentation](https://vega.github.io/vega-lite/)
- [Vega-Embed Documentation](https://github.com/vega/vega-embed)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

