## Analyze A/B Test Results

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

### Introduction


A/B tests are very commonly performed by data analysts and data scientists. For this project, the goal is to understand the results of an A/B test run by an e-commerce website. 


The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. Current work is to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.


| Table of Contents |
| :--- |
| <a href='#Prerequisites'> Prerequisites </a> 🔍📜 | 
| <a href='#Design'> Design </a>  📐 |
| <a href='#Conclusions'> Conclusions </a>  📌 |
| <a href='#License'> License </a> 🔖 |


<a id='Prerequisites'></a>

### Prerequisites


![](https://img.shields.io/badge/platform-ios-green.svg?colorA=abcdef)


- Python 3.6.3
- Jupyter Notebook
- Anaconda-Navigator


<a id='Design'></a>

### Design


![](https://img.shields.io/badge/language-Python-orange.svg)


**_Step One_** - Compare


Through mathematics calculation to find out the conversion rates difference between new and old pages.


**_Step Two_** - A/B test


Further examine with an A/B test to see if the results match arithmetic analyze.


**_Step Three_** - Country


Investigate the impact of countries on P-value and hypothesis.


<a id='Conclusions'></a>

### Conclusions


- Through comparison, there is a decreasing of conversion rates in new pages versus old ones. A/B test confirmed  new page's poorer performance, thus we don't have enough evidence to reject the null hypothesis, suggesting new pages has no advantages over old ones on conversion rates.
- We had also noticed that country did have some bearing on conversion rate, but not high enough to be  statistically significant.
- In sum, I would suggest the e-commerce company at least not to consider the current new page, but trying to figure out the reason of its poor performance in order to launch another feasible page.


<a id='License'></a>

## License 

[![PyPI license](https://img.shields.io/pypi/l/ansicolortags.svg)](https://pypi.python.org/pypi/ansicolortags/)
