# GHG_data_NAICS
Finding Greenhouse Gas (GHG) Emissions Benchmark data for Businesses

The goal is to create industrial GHG benchmarks via the North American Industry Classification System(NAICS). Data is available online on public registries however there is data missing for the more recent years. Mostly the data online has total GHG emissions for each NAICS for each year, so a simple linear regression (with machine learning) to find recent dates and projected into the future. Think of the project like stock market index to compare if your stocks performed well in a year, it all depends on how the index did.

Also we have found data for the average number of businesses for each NAICS category that we divide by totals in the sectors. Here too I need to do a simple linear regression (with machine learning) because I am missing for the average number of businesses in the industries.

Keep in mind that these are not the most accurate models because of the lack of data but they perform at times better than I had believed.
