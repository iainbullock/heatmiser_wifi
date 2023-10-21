This repository is forked from the original ([https://github.com/midstar/heatmiser_wifi_ha](https://github.com/midstar/heatmiser_wifi)) and updated for my personal requirements only. Feel free to use it as is or clone and take over the responsibility for public maintenance.

# Heatmiser WiFi - python library and tool
[![AppVeyor](https://ci.appveyor.com/api/projects/status/github/midstar/heatmiser_wifi?svg=true)](https://ci.appveyor.com/api/projects/status/github/midstar/heatmiser_wifi)

## Overview
A [Heatmiser](http://www.heatmiser.com/) WiFi Thermostat communication tool and library for python.

Supported Heatmiser Thermostats are DT, DT-E, PRT and PRT-E.

This fork adds support for the PRT-HW WiFi thermostat, and adds the following functionality (for PRT-HW, maybe others):
* TBA 
* TBA

The main class of the library is Heatmiser. It supports retrieval of all Thermostat parameters as a dictionary. It also supports setting of some (but not all) of the Thermostat parameters. 

## Supported platforms
The application is written in Python and has been successfully tested with Python version 2.7 and 3.4.

Both Windows and Linux has been tested successfully. Mac OS X has not been tested, but should work as well.

## Installation
Run 

    python -m pip install heatmiser_wifi

This will install both the library and the command line tool.

Alternatively, since this is just one python file, you can download heatmiser_wifi.py and include it in your project.
  
### Using libary

See how the library/class is used in the main() function of heatmiser_wifi.py.

### Using command line tool

To list all parameters write:

    heatmiser_wifi -c <pincode> <themostat_ip_address> -l 

It is also possible to read and write specific parameters. For instructions, write:

    heatmiser_wifi -h
 
### Author and license
This application is written by Joel Midstjärna and is licensed under the MIT License. This fork is updated by Iain Bullock and licensed under the MIT License.
