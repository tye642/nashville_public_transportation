## **Nashville Public transportation**
*Capstone Project for Data Analytics Cohort #4 program at Nashville Software School.*

### **Contents**  
- [Motivation](#Motivation)
- [Data Questions](#Data-Questions)
- [Known Issues and Challenges](#Known-Issues-and-Challenges)
- [Data Sources and Tools](#Data-Sources-and-Tools)
- [Links to Tableau Public and Video](#Links-to-Tableau-Public-and-Video)

Nashville is a growing city and with that comes stress on our infrastructure. Is there a need to improve and upgrade our public transportation? How does Nashville compare to other cities in similar size and trajectory? Is it worth it? These are some of the questions I will try to answer.

### **Motivation**   
I moved to Nashville in 2016, and have watched it grow quickly. As more people moved here, the traffic has increased and commutes have gotten longer. I believe that there needs to be more investment in our infrastructure, specifically public transportation. I have travelled to cities around the US as well as abroad, and I'm amazed by some of the public transportations systems out there. Places like Japan heavily rely on their public transportation. It is reliable and efficient.

### **Data Questions**   
* Does Nashville need to invest more into public transportation?
* Looking at cities similar size to Nashville, what do their public transportation look like?
* What are the ridership metrics for these cities?
* What are the costs for building and operating these systems?
* What are the benefits? Return on investment?
* Looking at cities that are larger, what is in store for us down the road?

### **Known Issues and Challenges**   
* The Census data needs cleaning because the city names are not just the city, but may include other names. ie. "Nashville-Davidson metropolitan government.."
  * I want to join this to my other datasets and will need a clean column to join to.
* Due to time constraints, I couldn't clean my 'city' column to a point to join my 2 datasets. Instead, I joined them in a more manual fashion.
* Since the my data was from several different sources, things didn't always line up. As an example, the public transportation dataset includes their own estimate on the population in the city. Those numbers do not always line up with the census numbers.

### **Data Sources and Tools**  
* Census data: this dataset could be used to find cities similar to Nashville. Would be useful to ‘join’ this to other datasets to see what their public transportation system looks like.
    * https://www.census.gov/data/datasets/time-series/demo/popest/2010s-total-cities-and-towns.html
* Public Transportation Dataset: includes ridership, operating costs/revenue, time series, safety data.
    * https://www.transit.dot.gov/ntd/data-product/monthly-module-raw-data-release (ridership)
    * https://www.transit.dot.gov/ntd/data-product/2019-data-tables ("Metric Static" contains operating costs and fare revenue)
* Tools
  * Python (Jupyter Notebook)
  * Excel
  * Tableau

### **Links to Tableau Public and Video**
* https://public.tableau.com/app/profile/teng.ye/viz/Public_Transportation_Ridership/Story1
