# temples
This project was done to help view the progress of Temples across the United States for the Church of Jesus Christ of Latter Day Saints. New Temples are announced every six months to be built, so I wanted to create a way to scrape this data from https://churchofjesuschristtemples.org/maps/ to update a visual to show all those Temples that have been built and will be built. I wanted to create a process in which this can be be done quickly and easily.

To scrape this data into a csv we utilized a Python script within Jupyter Notebook. After that we read and stored the data into a MYSQL Database. This way we have it stored in two separate locations (Github and MYSQL).

Afterwards, we took the data and created a visualization within Tableau that not only shows you the Temples that are currently announced, but has the functionality to show you all the Temples near your inputted Zip Code. By inputting you Zip Code and selecting the State, you can visualize statistics on Temples within that area and view a map of all Temples in the State selected.
