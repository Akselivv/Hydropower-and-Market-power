# Hydropower and market power in the Nordic countries
Replication data for Väliviita (2024) [Hydropower and market power in the Nordic countries].

Market_data-csv contains market data on the Nordic day-ahead electricity market (Elspot), as well as other auxiliary data from the ENTSO-E transparency platform and other miscallenious sources. The variables are:
-date
-hour
-price (Nord Pool system price)
-Cournot volume (Volume of Cournot supply bids calculated using the method propsoed by Lundin & Tangerås (2020))
-Cournot volume spec 2 (Volume of Cournot supply bids calculated using the method propsoed by Lundin & Tangerås (2020) using an alternative specification of 0.5€ instead of the original 5€ for the price identification limit)
-Equilibrium supply (Equilibrium supply of electricity in the Elspot)
-Forecasted demand Denmark
-Forecasted demand Norway
-Forecasted demand Sweden
-Forecasted demand Finland
-Total forecasted demand
-Total forecasted demand squared
-Wind production Denmark
-Wind production Norway
-Wind production Sweden
-Wind production Finland
-Total wind production
-Total wind production squared
-Temperature (Stockholm)
-Week number
-Week day
-Cournot volume with wind production subtracted
-Cournot volume spec 2 with wind production subtracted
-Semielasticity, windsorized
-Semielasticity, windsorized (alternative windsorization specification)
-Semielasticity, windsorized 2 (alternative windsorization specification)
-Across-reservoir variance in water level in the largest hydropower plants in Norway

reservoir_levels.csv contains monthly data on the reservoir levels of over 300 hydropower plants in the NO5 pricing area of western Norway estimated using a remote sensing algorithm.
