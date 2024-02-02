Fields:

| Column name             | Description                                                                                                                                                              |
|-------------------------|---------------------------------------------------------------------------------------------------------------------------------
| duration                | Duration of the encoding in [s]                                                                                                                                          |   			  |
| average_cpu_utilization | Average CPU utilization during the video encoding in [\%].                                                                                                               |   			  |
| cost                    | Computing cost of running encoding on the instance in [\$].                                                                                                              |  			  |
| model_cpu_energy        | CPU energy consumption estimated by Model for encoding in [kWh].                                                                                                     |  			  |
| code_carbon_ram_energy  | RAM energy consumption measured by CodeCarbon in [kWh].                                                                                                                  |   			  |
| model_cpu_co2           | CPU CO2 emissions calculated at default carbon intensity (617 g) for Frankfurt using the Model energy estimation in [g].                                             |                         |
| cpu_co2_\<country\>       | CPU CO2 emissions of the instance located in <country> calculated using the carbon intensity values provided in electricity map and the Model energy estimation [g]. |   |

CO2 impact [g] retrieved from https://app.electricitymaps.com/map  
From 19:00 13.08.2023 CEST  
To 18:00 14.08.2023 CEST  
Average CO2 emissions (in g) per country:  
&nbsp;&nbsp;&nbsp;&nbsp;Germany: 389.75  
&nbsp;&nbsp;&nbsp;&nbsp;Austria: 63.208333333333336  
&nbsp;&nbsp;&nbsp;&nbsp;Sweden: 16.5  
&nbsp;&nbsp;&nbsp;&nbsp;Poland: 732.5  
&nbsp;&nbsp;&nbsp;&nbsp;South Africa: 720.1666666666666  
&nbsp;&nbsp;&nbsp;&nbsp;Taiwan: 554.625  
&nbsp;&nbsp;&nbsp;&nbsp;Great Britain: 210.95833333333334  
