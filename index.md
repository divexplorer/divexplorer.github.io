# DivExplorer

Machine learning models may perform differently on different data subgroups. 
We propose the notion of divergence over itemsets (i.e., conjunctions of simple predicates) as a measure of different classification behavior on data subgroups, and the use of frequent pattern mining techniques for their identification. 
We quantify the contribution of different attribute values to divergence with the notion of Shapley values to identify both critical and peculiar behaviors of attributes. 
See our [paper](#citations) for details and citations.

DivExplorer is available as a python [package](#DivExplorer-package) and as a interactive cloud-based [web app](#DivExplorer-web-app).

## DivExplorer web app

DivExplorer is a web app for analyzing datasets and finding subgroups of data where a classifier behaves differently than on the overall data. 


<p align="center">
  <a href="https://raw.githubusercontent.com/divexplorer/divexplorer.github.io/main/divexplorer-webapp-teaser.png" target="_blank"><img src="https://raw.githubusercontent.com/divexplorer/divexplorer.github.io/main/divexplorer-webapp-teaser.png" width="100" alt="Demonstration screenshot"/></a>
</p>


### Watch the demonstration video :

<iframe width="300" src="https://www.youtube.com/embed/C5IUNvgWHhU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<p align="center">
  <a href="https://www.youtube.com/watch?v=oBzGuh_COmU" target="_blank"><img src="https://raw.githubusercontent.com/divexplorer/divexplorer.github.io/main/demo-screenshot.png" width="450" alt="Demonstration video"/></a>
</p>


You can try DivExplorer [here](https://divexplorer.org/). You can use the preprocessed [discretized COMPAS](https://raw.githubusercontent.com/divexplorer/divexplorer.github.io/main/compas_discretized.csv) dataset as demo dataset.


Source code and documentation are available at the following [link](https://bitbucket.org/luca_de_alfaro/divexplorer). 

DivExplorer is designed by [Eliana Pastor](https://github.com/elianap), [Andrew Gavgavian](https://gavgavian.com), [Elena Baralis](https://dbdmg.polito.it/wordpress/people/elena-baralis/), [Luca de Alfaro](https://luca.dealfaro.com)




## DivExplorer package

DivExplorer is available as a python package at the following [link](https://github.com/elianap/divexplorer).


## Citations

Looking for Trouble: Analyzing Classifier Behavior via Pattern Divergence. Eliana Pastor, Luca de Alfaro, Elena Baralis.
Proceedings of the 2021 International Conference on Management of Data (SIGMOD '21). June 20--25, 2021, Virtual Event, China. (to appear)
