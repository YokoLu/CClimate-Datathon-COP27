# Climate-Datathon-COP27

This repo contains the visualization work done for the Global Climate Stocktake for COP 27.

### Slides
The main content for our work is present in this PowerPoint: https://docs.google.com/presentation/d/1YI9gDvCE1DEjRtZwkCesKcEe6cFkYfe0Ge14Q1u_nHY/edit#slide=id.g169d82bf8ac_0_94. It details the methodology and the work we have done throughout this Datathon.

### Excel Working Files

- Final Scores - https://docs.google.com/spreadsheets/d/1uiO3kF2j27bhb76djWVFGvNJqPj05w6En_NWgMWSNWs/edit#gid=1412219002
- Indicators 1 & 2 - https://docs.google.com/spreadsheets/d/1-zZaKf66NAovfZXGqFS_JeGfoTfxTLWtUXiTl2o2j0Y/edit#gid=479025173
- Indicators 3  https://docs.google.com/spreadsheets/d/15KJOzFkmxNZFA5-u6BIsS0rJlIVsOHc-sb5qY_-395w/edit#gid=1604765395


### Figma
This is a mockup that we created for the website to showcase our work - https://www.figma.com/file/bSNOC6INrVZyNOzCXzAZya/COP27-GST-Datathon?node-id=0%3A1


### Google Drive
Under Construction website resources have been captured here: https://drive.google.com/drive/folders/1gQxjdi0H_c5q5DzJjv9xj-kT5tBayHIA

### Installation
This repo contains the code for the 3D visualizations as well. The visualizations can be seen at - https://iofall.github.io/Climate-Datathon-COP27/ and are based on the methodology described in our slide.

To run this locally, clone the repo - `git clone https://github.com/iofall/Climate-Datathon-COP27.git` and just open the HTML file using a server (to avoid CORS issue from reading local files).

### Additional Repos
We also had some sensitive datasets that we covered in this repo - https://github.com/DavidSmithPeregrine/Climate-DataThon-2022 which has already been shared with the organizers.

### Libraries Used
- [Globe.gl](https://globe.gl/) - Used to create the rendered globe. Country GeoJSONs were also made available through this JS library.
- [d3.js](https://d3js.org/) - Used to read and parse our dataset in the form of CSVs.
- [color-legend-element](https://www.npmjs.com/package/color-legend-element) - Used to make the dynamic legend.
- [Twemoji](https://twemoji.twitter.com/) - For Favicon.
