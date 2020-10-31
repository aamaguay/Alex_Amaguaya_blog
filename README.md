# Alex_Amaguaya_blog
Academic and professional profile

Herfindahl Index is a indicator that reports on the economic concentration of a market and presents the following formulation:

$$
HI = \sum_{i=1}^N S_i^2
$$

Where $S_i$ represents the market share of a company $i$. And $\Large S_i=\frac{Sales_i}{TotalSales}$, $Sales_i$ represents the sales of a company $i$ and $TotalSales$ is the total market sales.

Based on the previous, I propose a metric similar to Herfindahl Index. Moreover, this metric is based on user records, It's calculated for each hour of every day and has following formulation:

$$
\Large CI_{ijt} = \frac{User Records_{ijt}}{Total User Records_{it}}
$$

Where:

* $i:$ this subscript represents Manabi cantons
* $j:$ this subscript represents the hour of day $t$ 
* $t:$ this subscript represents one day
* $User Records_{ijt}:$  is the total number of clients of the canton $i$ in the hour $j$ of the day $t$
* $Total User Records_{t}:$ is the total number of clients of the canton $i$ in the day $t$

In fact, this metric is normalized by the total number of clients of the canton $i$ in the day $t$ and It's calculated for each  Manabi cantons.
