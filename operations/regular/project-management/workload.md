[&laquo; Back to Project Management](index.md)

Workload Planning and Tracking
=====

Podio allows a base for us to track what needs to be done and when, but we have extended it to also allow us to plan our workload.
But these plans and our actual records work hand-in hand.


Tracking with Podio Containers and Work Order Apps
-----

Most of our Podio "apps" (see the section on [knowledge management]()) can be categorized either container apps or work order apps.
(The rest could be consider strictly data apps.)
* *Container apps* are those that establish larger, ongoing projects. They provide a label and description for organizing more details through the Work Order apps.
* *Work order apps* are where the actual work occurs as these track more modular chunks of individual staff members' workload.
  They contain the following fields:
  * Name
  * Point person -
    the individual employee who will be responsible for completing the order and for requesting any related work to another employee.
  * Start date -
    the date we plan to begin working on the order.
  * End date (deadline) -
    the date we plan to complete all work on the order.
  * Estimated hours -
    an estimation of how many hours the order will take one person to complete.
    This should not include hours that will be delegated to someone else through a sub-work order.
  * Estimated progress -
    the point person's estimate of how far along the order is towards completion.
    See more about estimating progress below.
  * Timelogs -
    the separate Timelogs app is connected to work orders, allowing you to quickly enter a log for time on task.
    See more about using timelogs below.
  * Actual hours -
    a calculated field in which Podio displays the sum of all timelogs enterred on a word order.
  * Actual progress -
    a calculated field in which Podio takes the actual hours and divides it by the estimated hours.
    This gives a mathematical sense of "progress."
    However, since estimated hours is indeed an estimate, this "actual progress" is more a reflection of how much we've used of the time we estimated we'd use.


Planning with Eagle
-----

These Podio apps contribute allow us to forecast workload through our custom application Eagle.
Eagle access Podio data through an API and was developed in 2016 by then-interiem Director and web developer Phil Schanely.
Eagle adds the following layers of benefit:

* A gantt-like display of all containers and their nested work orders
* A gantt-like display of each employee's planned work
* Indicators of actual progress of time logged alongside estimated progress
* Ability to drag to adjust start dates, end dates, and estimated progress
* Color coding to give a sense of how much work is planned for an item on a daily basis
* Aggregated daily workload for each employee to aid with planning and avoiding overload

### Ideal Workload Philosophy

Eagle works on the assumption that a healthy employee workload is one that is approximately 80% planned, leaving 20% margin for the unexpected.
Unexpected work can come from work orders that took longer than planned, from last-minute support work, or from other unplanned emergency work.
Therefore, Eagle's color-coding displays an 80%-loaded workday as "green" to indicate a healthy workload. With this in mind:

* 0-1.9 hours is colored purple and considered "underloaded"
* 2-3.9 hours is colored blue and considered "light"
* 4-5.9 hours is colored green and considered "healthy"
* 6-7.9 hours is colored yellow and considered "fully loaded"
* 8+ hours is colored red and considered "overloaded"

### Approach to Workload Planning

Since Eagle provides a live view of work that is happening and planned work, employees can easily get a sense of what is on their plate.
We can also use it to forecast future work in order to avoid both slumps and overtime.

* Grey and purple bars for an employee in the Workload Gantt view indicate there is little work planned that day.
  * Other employees that are overloaded could perhaps delegate work to such an employee for a time.
  * Internal projects could be identified to fill such a gap in planned work.
  * Future work could perhaps be pulled up to start sooner.
  * Professional development activities could be planned that better prepare the employee for future work or provide an opportunity to experiment with relevant innovations.
* Yellow and red bars in the same view indicate the employee is working with no margin or is overbooked.
  * Start and end dates could be adjusted to shift work into lower zones.
  * Estimated time could be adjusted to better acount for the work needed.
    Perhaps the time was overestimated.
    On the other hand, perhaps an MVP mindset could lead to reducing the time needed for the order.


Common Practices
-----

### Estimating Progress on Word Orders

Coming soon.

### Entering Timelogs

Coming soon.

