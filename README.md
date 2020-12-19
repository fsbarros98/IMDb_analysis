# Data Visualization Project
## IMDb Datasets Analysis

Authors:

 - Bruno Vaz
 - Fátima Barros
 - Maria João Lavoura


The Internet Movie Database [(IMDb)](https://www.imdb.com/pressroom/) is a well-known source for obtaining information about titles, TV shows, celebrities, etc. People are accustomed to selecting their next film or program according to its ratings and reviews. This database comprehends this and much more data. For instance, we have an insight of the crew members with details on some personal information. It also specifies different labels for each instance according to world region and even describes the duration and genres of each title. 

In this report, we will be analysing the [IMDb datasets](https://www.imdb.com/interfaces/), which are publicly available and updated daily. First, a description of the dataset will be presented, detailing the features of each dataset for a better understanding of the material within it. Then, we will review the specifications of the processing techniques used for filtering and cleaning the data, making it useful for visual analysis. At last, we will explore and prove, or refute, the proposed hypothesis based on the EDA.


All the implementation was done using R programming language, with libraries 

 - dplyr
 - tidyverse
 - stringr
 - ggplot2
 - igraph
 - plotly
 - maps
 
 Graphic Results present [here](/graphic_results)

Main Conclusions:

 - Concerning the regions of titles, the US is the country to which most titles are translated. Furthermore, titles that are translated to more than one region are typically translated to a European country. 
As the number of regions increases, the average ratings get higher and the frequency of translated titles diminishes. 

 - Concerning cast and crew, from the analysis performed we concluded that actors are the most relevant people for characterizing the title's success, that is, the average ratings. Despite this, there may be some specific members of the crew, more exactly directors, that can be related to a title's success.

 - Titles that win any type of the awards explored (Emmy, Golden Globes, or Oscars) have significantly higher ratings. Drama is clearly the predominant genre for titles that win awards, and genre features may determine the type of nominee of an award.
