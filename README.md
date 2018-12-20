# Workshop on Large Scale RDF Analytics - LASCAR - [website](lascar.sda.tech)

### About
This workshop on Large Scale RDF Analytics (LASCAR) invites papers and posters related to the problems faced when dealing with the enormous growth of linked datasets, and by the advancement of semantic web technologies in the domain of large scale and distributed computing. We will particularly welcome research efforts exploring the use of generic big data frameworks like Apache Spark, Apache Flink, or specialized libraries like Giraph, Tinkerpop, SparkSQL etc. for Semantic Web technologies. The goal is to demonstrate the use of existing frameworks and libraries to exploit Knowledge Graph processing and to discuss the solutions to the challenges and issues arising therein. Moreover, we will organize a related talk by an expert speaker, and also arrange a panel discussion among experts and scientists working in the area of distributed semantic analytics. LASCAR targets a range of interesting research areas in large scale processing of Knowledge Graphs, like querying, inference, and analytics, therefore we expect a wider audience interested in attending the workshop.

This website is build on top of [Jekyll](http://jekyllrb.com/) and uses the [Project Zeppelin](https://github.com/gdg-x/zeppelin) template which is released under the [MIT License](LICENSE.txt).

## Local development

Check if you have [all requirements for local environment](http://jekyllrb.com/docs/installation/).
To install all development dependencies install [Bundler](http://bundler.io/).
```bash
    gem install bundler
```
and run next command from root folder:

```bash
  bundle install
```  

To start Jekyll run:
```bash
    bundle exec jekyll serve -w
```
Site will be available at http://localhost:4000/