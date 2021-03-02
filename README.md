# bigquery_test
Business Analytics assignment

-- finding the average popultion in the year 1963
SELECT avg(year_1963)
FROM `bigquery-public-data.world_bank_global_population.population_by_country` LIMIT 100
	1.2439692089615382E8

--finding out max load weight 
SELECT max(load_weight)
FROM `bigquery-public-data.austin_waste.waste_and_diversion` LIMIT 1000
1562821.0

--finding out min load weight 
SELECT min(load_weight)
FROM `bigquery-public-data.austin_waste.waste_and_diversion` LIMIT 1000
-4480.0

--finding the minimum fertility rate between 20-24 yrs old
select min(fertility_rate_20_24) 
FROM `bigquery-public-data.census_bureau_international.age_specific_fertility_rates` LIMIT 100
9.5

--finding average of crude death rate
SELECT avg(crude_death_rate)
FROM `bigquery-public-data.census_bureau_international.birth_death_growth_rates` LIMIT 1000
8.960886210799584

--finding max growth rate
SELECT max(growth_rate)
FROM `bigquery-public-data.census_bureau_international.birth_death_growth_rates` LIMIT 1000
168.887

--finding the average life expectancy of a female
SELECT avg(life_expectancy_female)
FROM `bigquery-public-data.census_bureau_international.mortality_life_expectancy` LIMIT 1000
74.2671250665959

--finding the average of infant mortality of a female
SELECT avg(infant_mortality_female)
FROM `bigquery-public-data.census_bureau_international.mortality_life_expectancy` LIMIT 1000
26.23020444858819

-- calculating the avegrage fare
SELECT avg(fare)
FROM `bigquery-public-data.chicago_taxi_trips.taxi_trips` LIMIT 1000
13.125161161374535

-- calculating maximum tips given in a fare
SELECT max(tips)
FROM `bigquery-public-data.chicago_taxi_trips.taxi_trips` LIMIT 1000
999.99



