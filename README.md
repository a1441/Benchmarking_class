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
