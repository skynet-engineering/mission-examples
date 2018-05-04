# Waypoint Goto Mission

This mission demonstrates and tests the accuracy of goto.
Starting at some location, the drone will go to some specified GPS coordinate and land.

The landing location can then be compared to the specified location to determine the accuracy of the system.

## Required dependencies

GPS sensor.

## Usage

```bash
$ python waypoint-goto.py --fc-addr <flight controller MAV proxy address> --log-file <name of output log file>
```
