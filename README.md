# Titanic Survival Analysis
#### ijim

``` sql
       SELECT c.product as product1, r.product as product2, COUNT(c.`Order ID`)AS total_order
       FROM dna.`datadna dataset challenge - december 2022` c
        JOIN
        dna.`datadna dataset challenge - december 2022` r
        ON
        c.`Order ID`= r.`Order ID`
        WHERE c.product > r.product AND c.product > r.product
        GROUP BY c.product,r.product
        ORDER BY total_order DESC
```
