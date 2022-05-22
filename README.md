# Climate Analysis
## Overview of the analysis:
In this analysis we use Jupyter notebook together with Pandas and SQLite to analyze temperature data understand the **temperature trends** in Oahu for the months of **June** and **December** in order to determine if a surf and ice cream shop would be viable business.
## Purpose:
The main purpose of this analysis is to analyze the temperature data from a span of 7 years, from 2010 to 2016 for June and December. 
## Results:
* the temperature analyses for June and December show very similar results
* lower over all temps in December, and 
* a lower precipitation in June. 
## Summary:
* The temperature stats for the months of June and December are summarized bellow:

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>june_temps</th>
      <th>december_temps</th>
    </tr>
    <tr>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>count</th>
      <td>1700.00</td>
      <td>1517.00</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>74.94</td>
      <td>71.04</td>
    </tr>
    <tr>
      <th>std</th>
      <td>3.26</td>
      <td>3.75</td>
    </tr>
    <tr>
      <th>min</th>
      <td>64.00</td>
      <td>56.00</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>73.00</td>
      <td>69.00</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>75.00</td>
      <td>71.00</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>77.00</td>
      <td>74.00</td>
    </tr>
    <tr>
      <th>max</th>
      <td>85.00</td>
      <td>83.00</td>
    </tr>
  </tbody>
</table>

- As per this summary table, apart from December having a lightly lower values for both the maximum and minimum temperatures, the temperature patterns remain the same for the months of June and December. Promising a sustainable business for the surf and ice cream shop.
- A similar analysis on the **precipitation** would likely give a better picture on the overall weather trends. 