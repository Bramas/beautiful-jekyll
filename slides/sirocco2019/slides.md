name: inverse
layout: true
class: center, middle, inverse
---
layout: false
class: center, middle


# Infinite Grid Exploration <br/> by Disoriented Robots

<br/>
__Quentin Bramas__ (University of Strasbourg, ICUBE)<br/>
Stéphane Devismes (Université Grenoble Alpes, VERIMAG)<br/>
Pascal Lafourcade (University Clermont Auvergne, LIMOS)<br/>

<br/>
SIROCCO 2019, L'Aquilla, July 4<sup>th</sup>, 2019

<br/>
<a href="mailto:bramas@unistra.fr">bramas@unistra.fr</a>
---
Mobile Robots:

* Move on the infinite grid
* Synchronous
* No Memory
* No Communication
* Execute the same algorithm
* Exclusive (no robots at the same position)
* May have lights with finite number of colors
* Limited Visibility
* Disoriented (but common on chirality)
---
Mobile Robots:

* Look at the nodes of the grid at distance d
* Compute a destination (Up,Left,Down,Right,Idle) based on the snapshot
* Move

Problem:

* Start with a predetermined initial configuration
* Each node of the grid should be visited by a robot in finite time.

<br/>
<br/>
<br/>
<br/>
*Emek, Y., Langner, T., Stolz, D., Uitto, J., & Wattenhofer, R. (2015).<br/>
How many ants does it take to find the food?.*
---
## View

<img style="width:30%" src="./global-ex.png" />

---
## View

<img style="width:30%" src="./global-ex.png" />

<img style="width:25%" src="./view1.png" />

---
## View

<img style="width:30%" src="./global-ex.png" />

<img style="width:25%" src="./view2.png" />

---
## Algorithm 1

* 6 robots
* lights with fixed colors (3 colors)
* visibility range = one.

<iframe style="margin:0; width:100%; border:0; height:70%" src="./6-robots-fixed-colors.html" />

---
### Rules
<img style="width:50%" src="./rules1.png" />


---
### Rules
<img style="width:50%" src="./rules1.png" />
### Global view
<img style="width:20%" src="./global1-.png" />

---
### Rules
<img style="width:50%" src="./rules1.png" />
### Global view
<img style="width:20%" src="./global1.png" />

---
### Rules
<img style="width:50%" src="./rules1.png" />
### Global view
<img style="width:20%" src="./global1.png" />
<img style="width:20%;margin-left:5%" src="./global2-.png" />

---
### Rules
<img style="width:50%" src="./rules1.png" />
### Global view
<img style="width:20%" src="./global1.png" />
<img style="width:20%;margin-left:5%" src="./global2.png" />


---
### Rules
<img style="width:45%" src="./rules1.png" />
### Global view
<img style="width:20%" src="./global1.png" />
<img style="width:20%;margin-left:5%" src="./global2.png" />
<img style="width:20%;margin-left:5%" src="./global3-.png" />

---
### Rules
<img style="width:45%" src="./rules1.png" />
<img style="width:40%" src="./rules2.png" />
### Global view
<img style="width:20%" src="./global1.png" />
<img style="width:20%;margin-left:5%" src="./global2.png" />
<img style="width:20%;margin-left:5%" src="./global3-.png" />
---
### Rules
<img style="width:45%" src="./rules1.png" />
<img style="width:40%" src="./rules2.png" />
### Global view
<img style="width:20%" src="./global1.png" />
<img style="width:20%;margin-left:5%" src="./global2.png" />
<img style="width:20%;margin-left:5%" src="./global3.png" />

---
### Rules
<img style="width:45%" src="./rules1.png" />
<img style="width:40%" src="./rules2.png" />
### Global view
<img style="width:20%" src="./global1.png" />
<img style="width:20%;margin-left:5%" src="./global2.png" />
<img style="width:20%;margin-left:5%" src="./global3.png" />
<img style="width:20%;margin-left:5%" src="./global4-.png" />
---
### Rules
<img style="width:32%" src="./rules1.png" />
<img style="width:30%" src="./rules2.png" />
<img style="width:30%" src="./rules3.png" />
### Global view
<img style="width:20%" src="./global1.png" />
<img style="width:20%;margin-left:5%" src="./global2.png" />
<img style="width:20%;margin-left:5%" src="./global3.png" />
<img style="width:20%;margin-left:5%" src="./global4-.png" />
---
### Rules
<img style="width:32%" src="./rules1.png" />
<img style="width:30%" src="./rules2.png" />
<img style="width:30%" src="./rules3.png" />
### Global view
<img style="width:20%" src="./global1.png" />
<img style="width:20%;margin-left:5%" src="./global2.png" />
<img style="width:20%;margin-left:5%" src="./global3.png" />
<img style="width:20%;margin-left:5%" src="./global4.png" />

---
## Turn and Push

<img style="width:20%" src="./global1-.png" />
<span style="margin:5%"> → </span>
<img style="width:20%" src="./global5.png" />
---
## Initial configuration

<img style="width:70%" src="./initial.png" />

---
## Algorithm 1

* 6 robots
* lights with fixed colors (3 colors)
* visibility range = one.

<iframe style="margin:0; width:100%; border:0; height:70%" src="./6-robots-fixed-colors.html" />

---
## Impossibility Results

Theorem: Impossible with 4 robots or less.

<br/>
<br/>
*Bramas, Q., Devismes, S., & Lafourcade, P. (2019).<br/>
Infinite Grid Exploration by Disoriented Robots. arXiv preprint arXiv:1905.09271.*

---
## Algorithm 2

* 5 robots (optimal)
* lights with modifiable colors (5 colors)
* visibility range = one.

<iframe style="margin:0; width:100%; border:0; height:70%" src="./5-robots-5-modifiable-colors.html" />
---

## Algorithm 3

* 7 robots
* no lights
* visibility range = two.

<iframe style="margin:0; width:100%; border:0; height:70%" src="./range2-7-robots.html" />

---

## Conclusion

Optimal infinite grid exploration with finite number of disoriented robots with limited visibility.

## Future Work

Find algorithms for robots without common chirality

Prove that **all** our algorithms are optimal


---

## Conclusion

Optimal infinite grid exploration with finite number of disoriented robots with limited visibility.

## Future Work

Find algorithms for robots without common chirality

Prove that **all** our algorithms are optimal


### Thank you

*Bramas, Q., Devismes, S., & Lafourcade, P. (2019).<br/>
Infinite Grid Exploration by Disoriented Robots. arXiv preprint arXiv:1905.09271.*
