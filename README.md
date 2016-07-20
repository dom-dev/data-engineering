
# 1:Project of Group16

This data engineering project is based on the sources of the movie database "imdb" the visitor list 
of the "whitehouse" and the dblp database, which lists the researchers.

The aim of the integration of this three sources is to show an correlation regarding the visitation
of the whitehouse, the rating of movies and the composition of an research paper by the cast of the movie.

## Description
We tried to show that a composition of an research paper by persons of the cast of a movie and/or the visitation
of the whitehouse are in correlation with the rating of a movie. Therefore the best and worst rated movies of the
Imdb database were taken and integrated with the dblp dataset and the list of the whitehouse visitors. The result
is shown in 5 plots:
Figure 1: Correlation between the number of visitations of the whitehous by the cast of a movie and the rating of the movie
Figure 2: Correlation between the number of compositions of research paper by the cast of a movie and the rating of the movie
Figure 3: Average visits of whitehouse in comparison of top/bottom movies
Figure 4: Average amount of compositions of research papers (dblp entry) in comparison of top/bottom movies
Figure 5: Comparison of visitations of the whitehouse and authors of research papers

Contributor: Alexander Szilagyi and Dominik Bäßler

## Installation
For preparation of the environment Python (min. 2.7) have to be installed and the following packages have to be added
to the python installation:
 - from xml.sax import make_parser, handler
 - BeautifulSoup4 (bs4)
 - django
 - pandas
 - lxml
 - matplotlib.pyplot
 - urllib2
 - imdb
 
The following datasets have to be located in the directory of the script:
 - dblp.dtd
 - dblp.xml
 - White_House_Visitor_Records_Request.csv

## Usage

For the usage of this tool follow the installation instructions of the previous chapter
and invoke the IPython Notebook (solution_notebook).
