# Self Organizing Maps


## Plan of Attack

* What we will learn in this section:
    * How do Self-Organizing Maps work?
    * K-Means Clustering
    * How do Self-Organizing Maps Learn? (*Part 1*)
    * How do Self-Organizing Maps Learn? (*Part 2*)
    * Live SOM Example
    * Reading an Advanced SOM
<hr>

## How Do SOMs Work?

<table>
    <tr>
        <th>Supervised</th>
        <td>Artificial Neural Networks</td>
        <td>Used for Regression & Classification</td>
    </tr>
    <tr>
        <th></th>
        <td>Convolutional Neural Networks</td>
        <td>Used for Computer Vision</td>
    </tr>
    <tr>
        <th></th>
        <td>Recurrent Neural Networks</td>
        <td>Used for Time Series Analysis</td>
    </tr>
</table>
<br>
<table>
    <tr>
        <th>Unsupervised</th>
        <td>Self-Organizing Maps</td>
        <td>Used for Feature Detection</td>
    </tr>
    <tr>
        <th></th>
        <td>Deep Boltzmann Machines</td>
        <td>Used for Recommendation Systems</td>
    </tr>
    <tr>
        <th></th>
        <td>AutoEncoders</td>
        <td>Used for Recommendation Systems</td>
    </tr>
</table>
<hr>

### Additional Reading

#### *The Self-Organizing Map*

*By Tuevo Kohonen (1990)*

<img src = "Images/Additional Reading - The Self-Organizing Map.png" alt = "The Self-Organizing Map" width="500px">

#### [The Self-Organizing Map - Tuevo Kohonen](http://sci2s.ugr.es/keel/pdf/algorithm/articulo/1990-Kohonen-PIEEE.pdf)
<hr>

## K-Means Intuition - Understanding K-Means (Refresher)

### What K-Means does for you
<img src = "Images/K-Means Clustering Work.png" alt = "What K-Means does for you" width="500px">

### How did it do that?

* **STEP 1:** Choose the number *K* of clusters

* **STEP 2:** Select at random *K* points, the centroids (not necessarily from your dataset)

* **STEP 3:** Assign each data point to the closest centroid **→** That forms *K* clusters

* **STEP 4:** Compute and place the new centroid of each cluster

* **STEP 5:** Reassign each data point to the new closest centroid.<br>&emsp;&emsp;&emsp;&emsp;If any reassignment took place, go to **STEP 4**, otherwise go to **FIN**.

* **FIN:** Your Model is Ready
<hr>

## How do Self-Organizing Maps Learn?

* Important to know:
    * SOMs retain topology of the input set
    * SOMs reveal correlations that are not easily identified
    * SOMs classify data without supervision
    * No target vector → no backpropagation
    * No lateral connections between output nodes
<hr>

### Additional Reading

#### *Kohonen's Self Organizing Feature Maps*

*By Mat Buckland (2004)*

<img src = "Images/Additional Reading - Kohonen's Self Organizing Feature Maps.png" alt = "Kohonen's Self Organizing Feature Maps" width="500px">

#### [Kohonen's Self Organizing Feature Maps - Mat Buckland](http://www.ai-junkie.com/ann/som/som1.html)
<hr>

## Reading an Advanced SOM

### Additional Reading

#### *SOM - Creating hexagonal heatmaps with D3.js*

*By Nadieh Bremer (2003)*

<img src = "Images/Additional Reading - SOM - Creating hexagonal heatmaps with D3.js.png" alt = "SOM - Creating hexagonal heatmaps with D3.js" width="500px">

#### [SOM - Creating hexagonal heatmaps with D3.js - Nadieh Bremer](https://www.visualcinnamon.com/2013/07/self-organizing-maps-creating-hexagonal.html)
<hr>
