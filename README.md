# AWISSA
## Saras Agrawal, Rateb Ajamieh, Jai Pannu, Lucas Xu, Andrew Yang

## https://awissa.notion.site/AWISSA-Addressing-Wildfire-Issues-in-the-Democratic-Republic-of-Congo-fa63271a8a754d35ad680ebaa2d27f3e 
## Further detailed information and in-depth explanations will be on the notion site, this readme is a more vague summary of the project
NASA Space Apps 2023 Hackathon 

AWISSA - Created by SpaceMonkeys

AWISSA PROGRAMS ARE DEFINED TO PREDICT, CALCULATE, ASSESS, AND COMMUNICATE WILDFIRES IN THE DEMOCRATIC REPUBLIC OF CONGO

!!apps.py IS DEPENDENT ON AN API KEY!!
!!If apps.py is not able to ingest and output data, please confirm that the API key is working!!
!!If the API key is not working, please generate a FIRMS API key, and replace MAP_KEY in apps.py with your new working API key!!

TensorFlow AI's judgement could/should have been improved by joining FRP with another metric.

Please note that our TensorFlow AI's potential was unfortunately constrained by the time limit.

## How it works
Using a supervised AI learning model, the program can calculate the risk of a wildire in an area using soil moisture*, windspeed*, ambient temperature*, precipitation*, vegetation density**, and historical fire instances. This is used to help alert areas with high wildfire risk to exercise high caution. Warnings like these can help prevent wildfires from starting, which is a far better way to combat wildires than suppressing and smothering wildires after they have already occured.

For current active fires detected by FIRMS satellites, fire detection spots that have been detected to rapidly grow for the past 5 days and have a high FRP(Fire Radiative Power) will be considered an uncontrolled fire, while other fires with far less FRP and less erratic spread will be detected as slash and burn agricultre/controlled fire, and will likely die out by itself. If not, its growth to an unctrolled fire will be picked up by the fire detection

*Please do not reproduce without credit, read Liscense*

