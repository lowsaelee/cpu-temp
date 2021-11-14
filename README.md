# cpu-temp

Processor: AMD FX-8320 Eight-Core (Vishera)

Exploratory Data Analysis of cpu temperature and load before and after applying new thermal paste.

Computer was overheating and shutting down quite often with the old thermal paste when cpu is running on heavy load. The computer shutdowns down when the temperature reaches a little above 80 degree celcius.

After applying a new thermal paste, the computer was not overheating and shutting down anymore. The max temperature was around 62 degree celcius with loads around 100%.

Update: 1/14/2021
Version 2 of the notebook doesn't require modifying the data. It takes the log from CoreTemp without modifying it and reads it into a dataframe. Before and after applying thermal paste is not define. Only analyzes all data from one log file.
