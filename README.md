# Datathon-2019-Erhman
---
#### A deep learning model which optimizes California school districts' financial resource allocations toward different personnel categories for the purpose of academic achievement maximization. 
---

<b>Solution:</b> Our objective was to raise state-wide school achievement levels (as defined by the percent of students meeting ELA and math test score benchmarks) to maximize education proficiencies within each district in California. First, we gathered data on district achievement levels and staffing distributions (teacher/staff support/administrators/counselors/librarians/student support) through scraping multiple public websites and a search engine. Then, we ran them through a neural network to create a model which can predict student performance based on staffing. We then ran a BFGS optimization algorithm on the model to find the optimal staffing distribution for each district (based on their available budgets and current achievement levels) to inform new district-wide budgeting.

### Files:

<b>District Scraping:</b>
---
<b><i>Seena Saiedian, Edward Liu, and Mehul Raheja's project at the 2019 DSS x IBM Social Good Datathon at UC Berkeley</i></b>
