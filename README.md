# Awesome list of useful GNSS tables
In this document we collect tables which are useful for GNSS community.

## International GNSS service (IGS) Official Orbit and Clock Products
| Type      | Accuracy   | Latency     | Updates   | Interval  |
|-----------|------------|-------------|-----------|-----------|
| Broadcast | ~100 cm    | real time   | N/A       | daily     |
| Ultra-Rapid (p) | ~5 cm   | real time   | 4 per day | 15 min    |
| Ultra-Rapid (o) | ~3 cm   | 3–9 hours   | 4 per day | 15 min    |
| Rapid      | ~2.5 cm    | 17–41 hours | Daily     | 15 min    |
| Final      | ~2.5 cm    | 12–18 days  | Weekly    | 15 min    |

## IGS Satellite Clocks
| Type          | Accuracy      | Latency       | Updates | Interval  |
| ------------  | ------------- | ------------- | ------- | --------  |
| Broadcast     | ~5 ns         | real time     | N/A     | daily     |
| Ultra-Rapid (p) | ~3 ns real time | 4 per day   | 15 min |
| Ultra-Rapid (o) | ~150 ps 3–9 hours | 4 per day | 15 min |
| Rapid         | ~75 ps        | 17–41 hours   | Daily   | 5 min     |
| Final         | ~75 ps        | 12–18 days    | Weekly  | 30s       |


## IGS GLONASS Satellite Ephemerides
| Type          | Accuracy      | Latency       | Updates | Interval  |
| ------------  | ------------- | ------------- | ------- | --------  |
| Broadcast     | ~5 ns         | real time     | N/A     | daily     |

Orbit accuracies are 1D mean RMS values over the three XYZ geocentric components. IGS accuracy limits, except for predicted orbits, are based on comparisons with independent
laser ranging results and discontinuities between consecutive days. The precision is better.


## Geocentric Coordinates of IGS Tracking Stations
| Type         |      | Accuracy | Latency | Updates | Sample Interval |
|--------------|------|----------|---------|---------|-----------------|
| Final positions | horizontal | 3 mm | 11–17 days | weekly | weekly |
|               | vertical   | 6 mm | 11–17 days | weekly | weekly |
| Final velocities | horizontal | 2 mm/yr | 11–17 days | weekly | weekly |
|                 | vertical   | 3 mm/yr | 11–17 days | weekly | weekly |

## IGS Earth Rotation Parameters.

| Type                        | Accuracy   | Latency           | Updates  | Sample interval                                        |
|----------------------------|------------|------------------|----------|-------------------------------------------------------|
| Ultra-Rapid (p)            | PM         | 200 μas          | real time| daily integrations at 00, 06 12, 18 UTC, 4 times/day |
|                            | PM rate    | 300 μas/day      |          |                                                       |
|                            | LOD        | 50 μs            |          |                                                       |
| Ultra-Rapid (o)            | PM         | 50 μas           | 3–9 hours| daily integrations at 00, 06, 12, 18 UTC, 4 times/day |
|                            | PM rate    | 250 μas/day      |          |                                                       |
|                            | LOD        | 10 μs            |          |                                                       |
| Rapid                       | PM         | 40 μas           | 17–41 hours| daily integrations at 12 UTC, daily                  |
|                            | PM rate    | 200 μas/day      |          |                                                       |
|                            | LOD        | 10 μs            |          |                                                       |
| Final                       | PM         | 30 μas           | 11–17 days| daily integrations at 12 UTC, weekly                  |
|                            | PM rate    | 150 μas/day      |          |                                                       |
|                            | LOD        | 10 μs            |          |                                                       |

## IGS Atmospheric parameters.
| Type                                                     | Accuracy   | Latency   | Updates | Sample Interval                      |
|----------------------------------------------------------|------------|-----------|---------|--------------------------------------|
| Final tropospheric zenith path delay with N, E gradients | 4 mm (ZPD) | < 4 weeks | daily   | 5 minutes                            |
| Final ionospheric TEC grid                               | 2–8 TECU   | ~11 days  | weekly  | 2 hours; 5 deg (lon) x 2.5 deg (lat) |
| Rapid ionospheric TEC grid                               | 2–9 TECU   | <24 hours | daily   | 2 hours; 5 deg (lon) x 2.5 deg (lat) |
