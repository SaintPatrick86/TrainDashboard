# TrainDashboard(s)
Grafana Train Departure and Station-Info System

I've build two different Boards:

DepartureBoard_DB_API based on the official API of Deutsche Bahn
![image](https://github.com/SaintPatrick86/TrainDashboard/assets/5153820/3409c2f4-c5c5-46ae-8540-df754cc7ccd0)

DepartureBoard_WrapperAPI based on an WrapperAPI from https://transport.rest/ build by https://github.com/derhuerst

![grafik](https://github.com/SaintPatrick86/TrainDashboard/assets/5153820/99a5e1e6-1105-40b8-9d93-cea7d77079c3)

The dashboards provide information about departures at a station listed by Deutsche Bahn. 
The desired station can be find via a free text input and provides additional information such as the availability of parking, bicycle parking, Wifi or toilets.
It also includes a small statistics section. 

## Dependencies

API Data

DepartureBoard_WrapperAPI

https://transport.rest/ -> no authentication required

DepartureBoard_DB_API

In order to get data for the  dashboard, a Developer account on the Api marketplace of Deutsche Bahn is necessary.

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
