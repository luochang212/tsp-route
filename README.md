# TSP-Travel-Route

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Solving the Traveling Salesman Problem using google OR-Tools.

## Features

* Spend less time to visit more places of interest.

* Four modes to choose including walking, driving, bicycling and transit.

* Good visualization powered by gmaps, provide two different kinds of maps.

![route showed on the map](googlemap.JPG)

## Introduction of Travelling salesman problem

"The **travelling salesman problem** (**TSP**) asks the following question: "Given a list of cities and the distances between each pair of cities, what is the shortest possible route that visits each city and returns to the origin city?" It is an [NP-hard](https://en.wikipedia.org/wiki/NP-hardness)problem in [combinatorial optimization](https://en.wikipedia.org/wiki/Combinatorial_optimization)." (**more details on** [**Wikipedia**](https://en.wikipedia.org/wiki/Travelling_salesman_problem))

## usage

<details>
<summary>Examples</summary>

```js
const Pall = collectInto(Promise.all.bind(Promise));
let p1 = Promise.resolve(1);
let p2 = Promise.resolve(2);
let p3 = new Promise(resolve => setTimeout(resolve, 2000, 3));
Pall(p1, p2, p3).then(console.log); // [1, 2, 3] (after about 2 seconds)
```

</details>


<details>
<summary>Make sure you have already installed these packages: googleplaces, googlemaps, gmaps, ortools.</summary>

* python-google-places 1.4.1: [`pip install python-google-places`](#pip install python-google-places)
* googlemaps 3.0.2: [`pip install googlemaps`](#pip install googlemaps)
* gmaps 0.8.4: [`pip install gmaps`](#pip install gmaps)
* OR-Tools v7.0 (2019-03): [`python -m pip install --upgrade --user`](#python -m pip install --upgrade --user)

</details>

* Get Google API key from here: [https://developers.google.com/maps/documentation/distance-matrix/start#get-a-key](https://developers.google.com/maps/documentation/distance-matrix/start#get-a-key).

* Change the variable 'places' and 'location' then run all the cells.

* PS: If the fig is not showed after running all cells, try to restart the Jupyter notebook.

## Chinese

* [中文教程](https://luochang.ink/2019/04/09/%E7%94%A8Jupyter-notebook%E8%A7%84%E5%88%92%E6%97%85%E8%A1%8C%E8%B7%AF%E7%BA%BF/)

## License
MIT License
