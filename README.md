### Technologies
* PySpark
* Spark ML
  
### Project description
<ul>
<li>A Taxi driver can be informed only of a neighborhood with an elevated tip, without a more precise location.That's why the solution developed was based on the administrative division of previouslyManhattan. </li>

<li>An area could be any zone of arbitrary size. Instead of partitioning Manhattan into neighborhoods, we will search for small zones with elevated tip. </li>

<li>Using PySpark, a machine learning k-means , bisecting k-means and gaussian mixture algorithms will be leveraged to obtain areas of interest,</li>

<li>Each such an area is a cluster of Taxi rides with elevated tips. A cluster of Taxi rides will be later on called cluster.</li>
</ul>
