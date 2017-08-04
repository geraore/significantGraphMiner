# significantGraphMiner

Graph data is very common among today’s datasets, especially in the field of bio-medicine. Subgroup discovery of subgraphs in graph databases hold great potential for biological datasets. In this instance, the goal will be to search for those specific subgraphs that are highly enriched in a subset of vertices compared to the remainder of the graph. Three different algorithm implementations can be used for the datamining process, a base algorithm, an adaptation of gSpan, an adaptation of FSG. The algorithms were adapted to run in the current problem domain and as well to run in both directed and undirected graphs, and single and multiple-label graphs too.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

### Prerequisites

To get the project set and ready the following tools are necessary:

* [Apache Ant](http://ant.apache.org/) - The build tool for this project
* [Java](https://www.java.com/en/) - The java language

### Installing

To build the project, run the following command on the root directory

```
ant all
```
## Running options
The following are the possible options to run the algorithm in the terminal:

* h -> help, presents all the options.
* g -> path of the graph file.
* l -> path of the labels file if available.
* p -> path of the interesting vertices file.
* b -> path of the bg file, a preselected reduced representation of the graph lo search from it.
* s -> support threshold.
* i -> when present refers to a single label run, otherwise the algorithms run in multiple-label configuration.
* u -> when present set up a undirected configuration, otherwise a directed one.
* v -> p-value.
* m -> max number of vertices allowed.
* d -> verbose.
* n -> run with a nested p-value configuration.
* o -> output file for results.
* t -> in case memory statistics are necessary.
* a -> the algorithm to run, the options are (base, gspan, fsg)

## Running the examples

Three examples are provided along with this project in the folder dataset

```
Give an example
```

## Authors

* **Gerardo Orellana** - [gero](https://github.com/geraore)


## Acknowledgments

* 
* 
* 
