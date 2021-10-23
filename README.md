# Benchmarking_class
Benchmarking Video Class to rank, compare &amp; visuallize numeric data per indexed category

You really need to know the following:

Class takes a dataframe (numeric only) with categories set as index.

-Create a class and fit it with your dataframe e.g.:
`Benchmark_Analysis = Benchmark_ranking.fit(df)`

-To show overall rankings:
`Benchmark_Analysis.Bench.Bar_show`

-To benchmark a certain category through a radar chart:
`Benchmark_Analysis.radar_chart('XXXX')`

------------------------------------------------------------------------------------------------

`Benchmark_Analysis.benchmark_df` -> fitted df with a mean Benchmark row

![image](https://user-images.githubusercontent.com/49153959/138554658-fed53c6c-f157-4f8f-9ebe-14eb74482397.png)

`Benchmark_Analysis.ranked_df` -> all values ranked (alphabetically in case of ties)

![image](https://user-images.githubusercontent.com/49153959/138554682-fdf532bd-6740-4256-997b-29fc440e181b.png)

`Benchmark_Analysis.bar_graph` -> barchart for general overview

![image](https://user-images.githubusercontent.com/49153959/138554728-c9f3e272-7389-449c-85f1-6aff9f9dad4f.png)

`Benchmark_Analysis.radar_chart('Bulgaria')` -> radar chart comparing a category of choice to the benchmark 

![image](https://user-images.githubusercontent.com/49153959/138554759-566546a4-a6ca-4e1a-a270-5da1ec5ac5a6.png)

`Benchmark_Analysis.radar_chart('Bulgaria','Russian Federation')` -> radar chart comparing a 2 categories of choice

![image](https://user-images.githubusercontent.com/49153959/138554786-e975618a-157e-4e99-bdd4-821234697c17.png)

