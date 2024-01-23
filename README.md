# charts
## General information
These are Helm charts for personal use. Feel free to use them, and if you spot an error, I encourage you to open an issue. I am not giving any guarantees or promising any support, but since I use them personally I do try to avoid breaking changes. I use these in a home(lab) environment, so their general applicability and stability are not necessarily priorities.

## Charts included
### DeCONZ
Links: https://github.com/deconz-community/deconz-docker
State: WIP
DeCONZ is a controller for dresden-elektronik's ConBee series of ZigBee bridges. This chart enables running DeCONZ in a kubernetes cluster instead of as an individual Docker container. Why? Because you can. 
### OpenHAB
Links: https://www.openhab.org/
State: Not yet functional
OpenHAB is a powerful home automation suite. With this chart you can run OpenHAB in a cluster, achieving higher availability. Using a persistence database is highly recommended.
The chart is still in its infancy and doesn't work yet.
