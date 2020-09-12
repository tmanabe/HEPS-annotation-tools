# HEPS annotation tools

All the details are in [our paper](http://www.vldb.org/pvldb/vol8/p1606-manabe.pdf).

## Notes

* Our paper does not include a link to this repository because we did not plan to publish these tools.
  * These tools are unofficial in this sense.
* These tools may not work correctly and securely, especially in modern environments.
* You cannot annotate your data sets by using our working examples because of cross-origin frame.
  * Please download the tools and put them into the domain which includes your data sets.

## ContentMarker

is for annotation of *content body*.

* [Working Example](https://tmanabe.github.io/HEPS-annotation-tools/ContentMarker.html?url=https://tmanabe.github.io/HEPS-annotation-tools/example.html&name=ContentMarker-example-output.json)
* [Example Output](https://tmanabe.github.io/HEPS-annotation-tools/ContentMarker-example-output.json)

## BlockMarker

is for annotation of *hierarchical heading structure* inside *content body*.

* [Working Example](https://tmanabe.github.io/HEPS-annotation-tools/BlockMarker.html?url=https://tmanabe.github.io/HEPS-annotation-tools/example.html&x=/html/body/./descendant-or-self::node()[15+<=+position()][position()+<=+791]&name=BlockMarker-example-output.json)
* [Example Output](https://tmanabe.github.io/HEPS-annotation-tools/BlockMarker-example-output.json)

## Links

* [Reference implementation of *HEPS*](https://github.com/tmanabe/HEPS)
* [Our data set](https://github.com/tmanabe/HEPS-data-set)
