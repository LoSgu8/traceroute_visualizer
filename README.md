# Traceroute Visualizer

## About the project
Traceroute Visualizer is a tool written as a Python Notebook that, given a destination URL, it performs an enriched traceroute.

The traceroute result consists in plotting the path taken to reach the destination in the world map.
In addition, it prints a table where for each IP hop is indicated the organization, the city and the coordinates.

The destination hostname can be modified by changing the variable hostname, actually set to the Debian's australian ftp server 'ftp.au.debian.org'.

All the hops information is obtained using ip-api.com APIs (https://ip-api.com/docs/api:json).

![Image example](https://github.com/LoSgu8/traceroute_visualizer/blob/main/example.png?raw=true)
