# TrainDashboard
Grafana Train Departure and Station-Info System

The dashboard provides information about departures at a station listed by Deutsche Bahn. 
The desired station can be find via a free text input and provides additional information such as the availability of parking, bicycle parking, Wifi or toilets.
It also includes a small statistics section. 

## Dependencies

API Data

In order to get data for the dashboard, a Developer account on the Api marketplace of Deutsche Bahn is necessary.

You can create one here: https://developers.deutschebahn.com/db-api-marketplace/apis/frontpage

To get Api Crendtials you have to add an Appliaction and add the subscription for following APIs:

- StaDa - Station Data
- Timetables


Grafana Data Source

The Dasboard uses the Infinity Plugin, additional Information can be find here:

https://grafana.com/grafana/plugins/yesoreyeram-infinity-datasource/

It is important to use the Authentication over Headers:

![image](https://github.com/SaintPatrick86/TrainDashboard/assets/5153820/96b2568e-2171-4737-be8f-4e4bce3249c6)

Fell Free to contribute or Fork this Project.
