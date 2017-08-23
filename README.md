# D3 v4 Polygon Approximate Circle

Adapted from a [stackoverflow](https://stackoverflow.com/questions/45830617/d3-circle-points-dont-update-when-changing-slider) question.

gh-pages [demo](https://shanegibney.github.io/d3-v4-Polygon-Approximate-Circle/)

The stages of the update pattern are:

* JOIN the new data with old elements
* EXIT old elements not present in new data
* UPDATE old elements present in new data
* ENTER new elements present in new data

<img width="470" alt="screen shot 2017-08-23 at 12 02 55" src="https://user-images.githubusercontent.com/17167992/29612815-0c76c636-87fb-11e7-9d24-8129e4380663.png">
