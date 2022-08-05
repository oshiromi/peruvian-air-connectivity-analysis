# Peruvian Air Connectivity Analysis 

How well connected is Peru by air? Which are its most important airports to keep Peruvian regions connected and what would happen if they were to shut down? Which are the key airports to keep the country accesible by air to the rest of the world? This project answers these questions by visualizing and analyzing the network of national and international commercial flights and airports in Peru. The network was built using airport and flight data from "Open Flights", visualizing airports as nodes and flights as edges between them. 

The analysis was done by comparing two network visualizations: 1) including all Peruvian commercial airports and domestic flights; 2) the same network, but without the most important airport. The size of the vertix indicates the degree. That is, the bigger the vertix, the more Peruvian domestic destinations you can fly to from that airport. The width of the edges indicate the number of total flights (back and forth) offered for that route. That is, the thicker the edge, the easiest it is to find a flight between those two destinations. 

The comparison showed that air connectivity between Peruvian regions is highly dependent on the functioning of the airport in Lima. Nevertheless, it also highlights that in a potential destruction or inhabilitation of the Lima airport, most of the commercial air traffic in Peru would be paralyzed. Therefore, it would be advisable to reduce the dependency to the airport in Lima and try to establish more direct routes between regions.

![alt text](https://raw.githubusercontent.com/oshiromi/peruvian-air-connectivity-analysis/main/joint.png)

## References (data and shapefiles)

Geo GPS Perú. _Límite Borde Perú_. https://www.geogpsperu.com/2020/07/limite-peru-perimetro-borde-poligono.html

Geo GPS Perú. _Límite Departamental_. https://www.geogpsperu.com/2018/02/limite-departamental-politico-shapefile.html

OpenFlights. _Airport database_. January 2017. Distributed by OpenFligts.org. https://openflights.org/data.html

OpenFlights. _Route database_. June 2014. Distributed by OpenFlights.org. https://openflights.org/data.html

Wikipedia. _List of Airports in Peru_. March 4th, 2022. https://en.wikipedia.org/wiki/List_of_airports_in_Peru#:~:text=Of%20a%20total%20of%20234,which%2027%20feature%20scheduled%20services
