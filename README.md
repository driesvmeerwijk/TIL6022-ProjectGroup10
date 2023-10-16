# TIL6022-ProjectGroup10


# RQ:  
The influence of Covid on air travel movement in Amsterdam.
As the Covid virus resulted in chaos for both human- and producttransportation, this research will look into both these themes. 

The influence of Covid on the human traffic by plane in Europe, regarding flights to and from Eindhoven Airport.

# We are looking into the influence of COVID-19 on flight travel behavior. For this, we are first looking at the number of flights departing from Eindhoven, an airport in The Netherlands, from where only non-intercontinental flights depart. Then we compare this to flights made during the Covid years and lastly, we want to see the influence Covid had on travel behavior later. That is why we also look into the amount of flights after the pandemic was over. For this, we only take into account human traffic from and to Eindhoven airport, one year before COVID-19, the years during COVID-19, and the year after.
# For this we will be mainly using data from CBS, in this document: https://opendata.cbs.nl/statline/#/CBS/en/dataset/37478eng/table


import pandas as pd

flight_data = 'data/vliegnu.csv'
df = pd.read_csv(flight_data, encoding='latin1')
df
