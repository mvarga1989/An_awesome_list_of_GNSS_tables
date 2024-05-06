# Awesome list of useful GNSS tables [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

#### You wish to assist in making the list more useful, complete and accurate? Contributors are more than welcome. Please send me an [:e-mail:](mailto:mvarga1989@gmail.com).
#### If my content has added any value to your work, please consider giving it a :star: and/or share on your professional social networks. Thank you!
#### Other useful lists that I maintain are available on this [:link:](https://github.com/mvarga1989#community-lists-that-i-maintain)

<!-- toc -->

- [Products required for GNSS data processing](#products-required-for-gnss-data-processing)
  * [Products distributed by different institutes](#products-distributed--by-different-institutes)
    + [CDDIS](#cddis)
    + [IGN](#ign)
    + [WHU](#whu)
- [International GNSS service (IGS) Official Orbit and Clock Products](#international-gnss-service-igs-official-orbit-and-clock-products)
- [IGS Satellite Clocks](#igs-satellite-clocks)
- [IGS GLONASS Satellite Ephemerides](#igs-glonass-satellite-ephemerides)
- [Geocentric Coordinates of IGS Tracking Stations](#geocentric-coordinates-of-igs-tracking-stations)
- [IGS Earth Rotation Parameters.](#igs-earth-rotation-parameters)
- [IGS Atmospheric parameters.](#igs-atmospheric-parameters)
- [GPS/GNSS antennas](#gpsgnss-antennas)

<!-- tocstop -->

In this document I am collecting tables which are useful for GNSS community.

## Products required for GNSS data processing
- IGS daily, hourly, and high-rate observations with short file name (RINEX version 2.xx)
- MGEX daily, hourly, and high-rate observations with long file name (RINEX version 3.xx)
- IGS + MGEX (taking the union of IGS and MGEX, while the priority of MGEX sites is higher) daily, hourly, and high-rate observations
- Curtin University of Technology (CUT) daily observations with long file name (RINEX v3.xx)
- Hong Kong CORS 30s, 5s, and 1s observations with long file name (RINEX version v3.xx)
- NGS/NOAA CORS daily observations with long file name (RINEX v3.xx)
- EUREF Permanent Network (EPN) observations (long file name in RINEX v3.xx and short file name in RINEX v2.xx)
- Plate Boundary Observatory (PBO) observations (long file name in RINEX v3.xx)
- Various types of broadcast ephemeris, i.e., GPS- and GLONASS-only in RINEX v2.xx, mixed types in RINEX v3.xx and v4.xx for multiple-GNSS
- Various types of IGS, MGEX, and other analysis center (AC) final, rapid, and ultra-rapid precise orbit and clock products, CNES real-time orbit and clock products in offline file format
- Various types of IGS final and ultra-rapid earth rotation/orientation parameter (ERP/EOP)
- ORBEX (ORBit EXchange format) products from five institutions, i.e., CODE, GFZ, GRG, WHU, and CNES
- GPS and GLONASS differential code bias (DCB) products from CODE and multi-GNSS differential signal bias (DSB) products from CAS
- Code observable-specific signal bias (OSB) products from six institutions, i.e., CAS, CODE, GFZ, GRG, WHU, and CNES
- IGS weekly SINEX solutions
- Various types of final, rapid, hourly rapid, 15-min rapid, 1-day and 2-day predicted global ionosphere map (GIM) products
- Rate of TEC index (ROTI) products
- CODE and IGS final tropospheric products
- IGS ANTEX format antenna phase center corrections

### Products distributed  by different institutes

#### CDDIS
 -  IGS daily observation (30s) files 
 -  IGS hourly observation (30s) files 
 -  IGS high-rate observation (1s) files 
 -  MGEX daily observation (30s) files 
 -  MGEX hourly observation (30s) files 
 -  MGEX high-rate observation (1s) files 
 -  broadcast ephemeris files 
 -  IGS SP3 files 
 -  IGS CLK files 
 -  IGS EOP files 
 -  IGS weekly SINEX files 
 -  MGEX SP3 files 
 -  MGEX CLK files 
 -  MGEX ORBEX files 
 -  MGEX DSB files 
 -  MGEX OSB files 
 -  global ionosphere map (GIM) files 
 -  Rate of TEC index (ROTI) files 
 -  IGS final tropospheric product files 

#### IGN
 -  IGS daily observation (30s) files 
 -  IGS hourly observation (30s) files 
 -  IGS high-rate observation (1s) files 
 -  MGEX daily observation (30s) files 
 -  MGEX hourly observation (30s) files 
 -  MGEX high-rate observation (1s) files 
 -  broadcast ephemeris files 
 -  IGS SP3 files 
 -  IGS CLK files 
 -  IGS EOP files 
 -  IGS weekly SINEX files 
 -  MGEX SP3 files 
 -  MGEX CLK files 
 -  MGEX ORBEX files 
 -  MGEX DSB files 
 -  MGEX OSB files 
 -  global ionosphere map (GIM) files 
 -  Rate of TEC index (ROTI) files 
 -  IGS final tropospheric product files 
 
#### WHU
 -  IGS daily observation (30s) files 
 -  IGS hourly observation (30s) files 
 -  IGS high-rate observation (1s) files 
 -  MGEX daily observation (30s) files 
 -  MGEX hourly observation (30s) files 
 -  MGEX high-rate observation (1s) files 
 -  broadcast ephemeris files 
 -  IGS SP3 files 
 -  IGS CLK files 
 -  IGS EOP files 
 -  IGS weekly SINEX files 
 -  MGEX SP3 files 
 -  MGEX CLK files 
 -  MGEX ORBEX files 
 -  MGEX DSB files 
 -  MGEX OSB files 
 -  global ionosphere map (GIM) files 
 -  Rate of TEC index (ROTI) files 
 -  IGS final tropospheric product files 
 
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





## GPS/GNSS antennas

|       IGS Name    |      Description  |
|-----------|------------|
|       TRM105000.10 NONE    |      Zephyr 3 rover; switchable MSS filter in LNA; p/n 105000-10; L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BDS  | 
|       TRM115000.00 NONE    |      Zephyr 3 Geodetic; switchable MSS filter in LNA; p/n 115000-00; L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BDS  | 
|       TRM115000.00 TZGD    |      Zephyr 3 Geodetic; switchable MSS filter in LNA; p/n 115000-00; L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BDS  | 
|       TRM115000.00+S SCIT    |      Zephyr 3 Geodetic with SCIT spacer; switchable MSS filter in LNA; p/n 115000-00; L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BDS  | 
|       TRM115000.10 NONE    |      Zephyr 3 base; switchable MSS filter in LNA; p/n 115000-10; L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BDS  | 
|       TRM126000.00 NONE    |      Zephyr 3 Rugged  | 
|       TRM14177.00 NONE    |      4000ST L1 Geodetic, Model 14177.00  | 
|       TRM14532.00 NONE    |      4000ST L1/L2 Geodetic, Model 14532.00  | 
|       TRM14532.10 NONE    |      4000SSE Kin L1/L2, Model 14532.10  | 
|       TRM159800.00 NONE    |      Dorne Margolin with choke rings; p/n 159800-00; switchable MSS filter in LNA; GPS: L1/L2/L5; GLO: L1/L2/L3; GAL: E1/E2/E5ab/E6; BDS: B1/B2/B3  | 
|       TRM159800.00 SCIS    |      Dorne Margolin with choke rings; p/n 159800-00; switchable MSS filter in LNA; GPS: L1/L2/L5; GLO: L1/L2/L3; GAL: E1/E2/E5ab/E6; BDS: B1/B2/B3  | 
|       TRM159800.00 SCIT    |      Dorne Margolin with choke rings; p/n 159800-00; switchable MSS filter in LNA; GPS: L1/L2/L5; GLO: L1/L2/L3; GAL: E1/E2/E5ab/E6; BDS: B1/B2/B3  | 
|       TRM159900.00 NONE    |      GNSS-Ti antenna with choke rings; p/n 159900-00; switchable MSS filter in LNA; GPS: L1/L2/L5; GLO: L1/L2/L3; GAL: E1/E2/E5ab/E6; BDS: B1/B2/B3  | 
|       TRM159900.00 SCIS    |      GNSS-Ti antenna with choke rings; p/n 159900-00; switchable MSS filter in LNA; GPS: L1/L2/L5; GLO: L1/L2/L3; GAL: E1/E2/E5ab/E6; BDS: B1/B2/B3  | 
|       TRM22020.00+GP NONE    |      Geod. L1/L2 compact, with groundplane, Model 22020-00  | 
|       TRM22020.00-GP NONE    |      Geod. L1/L2 compact; w/o groundplane, Model 22020-00  | 
|       TRM23903.00 NONE    |      Permanent L1/L2, Model 23903.00, cast preamp housing  | 
|       TRM27947.00+GP NONE    |      Rugged L1/L2 with groundplane, Model 27947.00  | 
|       TRM27947.00-GP NONE    |      Rugged L1/L2 w/o groundplane, Model 27947.00  | 
|       TRM29659.00 NONE    |      Trimble L1/L2 Dorne Margolin element with chokerings Model 29659.00  | 
|       TRM29659.00 SCIS    |      Trimble L1/L2 Dorne Margolin element with chokerings Model 29659.00  | 
|       TRM29659.00 SCIT    |      Trimble L1/L2 Dorne Margolin element with chokerings Model 29659.00  | 
|       TRM29659.00 TCWD    |      Trimble L1/L2 Dorne Margolin element with chokerings Model 29659.00  | 
|       TRM29659.00 UNAV    |      Trimble L1/L2 Dorne Margolin element with chokerings Model 29659.00  | 
|       TRM33429.00+GP NONE    |      L1/L2 microcentered, Compact Geodetic, Model 33429.00 (with groundplane)  | 
|       TRM33429.00-GP NONE    |      L1/L2 microcentered, Compact Geodetic (no groundplane)  | 
|       TRM33429.20+GP NONE    |      L1/L2 microcentered, Compact Geodetic, Model 33429-20 (with groundplane)  | 
|       TRM33429.20+GP TCWD    |      L1/L2 microcentered, Compact Geodetic, Model 33429-20 (with groundplane)  | 
|       TRM33429.20+GP UNAV    |      L1/L2 microcentered, Compact Geodetic, Model 33429-20 (with groundplane)  | 
|       TRM36569.00+GP NONE    |      13" microcentered +GP  | 
|       TRM39105.00 NONE    |      Zephyr 4-point feed antenna - No Ground Plane  | 
|       TRM41249.00 NONE    |      Zephyr 4-point feed antenna - Stealth Ground Plane  | 
|       TRM41249.00 SCIT    |      Zephyr 4-point feed antenna - Stealth Ground Plane  | 
|       TRM41249.00 TZGD    |      Zephyr 4-point feed antenna - Stealth Ground Plane  | 
|       TRM41249USCG SCIT    |      Zephyr Geodetic L1/L2 +RD w/ USCG mount  | 
|       TRM44830.00 NONE    |      GA830 GNSS/MSK RXC ->North  | 
|       TRM4800 NONE    |      L1/enhanced L2 receiver, with internal antenna and radio modem, p/n: 32119-XX  | 
|       TRM53406.00 NONE    |      Zephyr (L1) A3  | 
|       TRM55970.00 NONE    |      Zephyr GNSS II - lead-based solder L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BeiDou  | 
|       TRM55971.00 NONE    |      Zephyr GNSS Geodetic II - lead-based solder L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BeiDou  | 
|       TRM55971.00 SCIT    |      Zephyr GNSS Geodetic II - lead-based solder L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BeiDou  | 
|       TRM55971.00 TZGD    |      Zephyr GNSS Geodetic II - lead-based solder L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BeiDou  | 
|       TRM57970.00 NONE    |      Zephyr GNSS II - RoHS compliant solder L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BeiDou  | 
|       TRM57971.00 NONE    |      Zephyr GNSS Geodetic II - RoHS compliant solder L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BeiDou  | 
|       TRM57971.00 SCIT    |      Zephyr GNSS Geodetic II - RoHS compliant solder L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BeiDou  | 
|       TRM57971.00 TZGD    |      Zephyr GNSS Geodetic II - RoHS compliant solder L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BeiDou  | 
|       TRM5800 NONE    |      Antenna inside Trimble 5800 and Trimble R8  | 
|       TRM59800.00 NONE    |      Dorne Margolin with chokerings, Model 59800.00 L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BeiDou, GPS, GLONASS, Galileo & BeiDou  | 
|       TRM59800.00 SCIS    |      Dorne Margolin with chokerings, Model 59800.00 L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BeiDou, GPS, GLONASS, Galileo & BeiDou  | 
|       TRM59800.00 SCIT    |      Dorne Margolin with chokerings, Model 59800.00 L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BeiDou, GPS, GLONASS, Galileo & BeiDou  | 
|       TRM59800.00 TCWD    |      Dorne Margolin with chokerings, Model 59800.00 L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BeiDou, GPS, GLONASS, Galileo & BeiDou  | 
|       TRM59800.80 NONE    |      Dorne Margolin with chokerings, Model 59800.80 L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BeiDou, GPS, GLONASS, Galileo & BeiDou. Upgraded from TRM29659.00 with GNSS low-noise amplifier  | 
|       TRM59800.80 SCIS    |      Dorne Margolin with chokerings, Model 59800.80 L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BeiDou, GPS, GLONASS, Galileo & BeiDou. Upgraded from TRM29659.00 with GNSS low-noise amplifier  | 
|       TRM59800.80 SCIT    |      Dorne Margolin with chokerings, Model 59800.80 L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BeiDou, GPS, GLONASS, Galileo & BeiDou. Upgraded from TRM29659.00 with GNSS low-noise amplifier  | 
|       TRM59800.99 NONE    |      Dorne Margolin with chokerings, Model 59800.99 L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BeiDou, GPS, GLONASS, Galileo BeiDou. Upgraded TRM29659.00 with Tallysman TW605 GNSS low-noise amplifier  | 
|       TRM59800.99 SCIT    |      Dorne Margolin with chokerings, Model 59800.99 L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BeiDou, GPS, GLONASS, Galileo BeiDou. Upgraded TRM29659.00 with Tallysman TW605 GNSS low-noise amplifier  | 
|       TRM59900.00 NONE    |      GNSS antenna with chokerings, Model 59900.00 L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BeiDou, GPS, GLONASS, Galileo & BeiDou  | 
|       TRM59900.00 SCIS    |      GNSS antenna with chokerings, Model 59900.00 L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BeiDou, GPS, GLONASS, Galileo & BeiDou  | 
|       TRM65212.00 NONE    |      Zephyr Model 2 Rugged RXC to North  | 
|       TRM68040.01 NONE    |      N/A  | 
|       TRM73004.10 NONE    |      N/A  | 
|       TRM77970.00 NONE    |      Zephyr GNSS model II rover - RoHS compliant solder, additional filter in LNA; p/n 77970-00; L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BeiDou  | 
|       TRM77971.00 NONE    |      Zephyr GNSS Geodetic II - RoHS compliant solder, additional filter in LNA; p/n 77971-00; L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BeiDou  | 
|       TRM77971.00 SCIT    |      Zephyr GNSS Geodetic II - RoHS compliant solder, additional filter in LNA; p/n 77971-00; L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BeiDou  | 
|       TRM92975.00 NONE    |      N/A  | 
|       TRM92995.00 NONE    |      N/A  | 
|       TRM99810.00 NONE    |      Trimble GA810  | 
|       TRMAV28+GP NONE    |      Trimble AV28 w/Ground Plane, PN 112735  | 
|       TRMDA2 NONE    |      Integrated GPS L1/L2/L5, GLO L1/L2, GAL E1/E5A, BDS B1/B2, IRNSS L5, QZSS L1/L2/L5, SBAS L1/L2/L5 antenna  | 
|       TRMR10 NONE    |      L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/B1/B2/B3, GPS, GLONASS, Galileo & BeiDou antenna  | 
|       TRMR10-2 NONE    |      L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/B1/B2/B3, GPS, GLONASS, Galileo & BeiDou antenna  | 
|       TRMR12 NONE    |      L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/B1/B2/B3, GPS, GLONASS, Galileo & BeiDou antenna  | 
|       TRMR12I NONE    |      L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/B1/B2/B3, GPS, GLONASS, Galileo & BeiDou antenna  | 
|       TRMR2 NONE    |      N/A  | 
|       TRMR4-2 NONE    |      Integrated GPS L1/L2 GLO L1/L2 Trimble R4 model 2  | 
|       TRMR4-3 NONE    |      Integrated GPS L1/L2 GLO L1/L2 Trimble R4 model 3  | 
|       TRMR4S NONE    |      Trimble R4s, PN 114038-00, TMT->N  | 
|       TRMR580 NONE    |      Integrated GPS: L1/L2/L5; GLO: L1/L2/L3; GAL: E1/E5ab/E5AltBoc BDS: B1/B2; QZSS: L1/L2/L5; IRNSS: L5; SBAS: L1/L5 antenna  | 
|       TRMR6 NONE    |      Integrated GPS L1/L2+L2C GLO L1/L2 Trimble R6 antenna  | 
|       TRMR6-2 NONE    |      Integrated GPS L1/L2+L2C GLO L1/L2 Trimble R6 model 2  | 
|       TRMR6-3 NONE    |      Integrated GPS L1/L2+L2C GLO L1/L2 Trimble R6 model 3  | 
|       TRMR6-4 NONE    |      Integrated GPS L1/L2+L2C GLO L1/L2 Trimble R6 model 4  | 
|       TRMR780 NONE    |      GPS: L1/L2/L5; GLO: L1/L2/L3; GAL: E1/E5ab/E6 BDS: B1/B2/B3; QZSS: L1/L2/L5/LEX; SBAS L1/L5  | 
|       TRMR8_GNSS NONE    |      Integrated GPS L1/L2+L2C/L5 GLO L1/L2 Trimble R8 GNSS antenna  | 
|       TRMR8-4 NONE    |      Integrated GPS L1/L2+L2C/L5 GLO L1/L2 Trimble R8 GNSS 3 antenna, model 4  | 
|       TRMR8S NONE    |      Integrated L1/L2/L5/G1/G2/G3/E1/E5ab/B1/B2 GPS, GLONASS, Galileo & BeiDou antenna  | 
|       TRMSPS585 NONE    |      N/A  | 
|       TRMSPS785 NONE    |      Trimble SPS785, PN 116377-00, TMT->N  | 
|       TRMSPS985 NONE    |      L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/B1/B2/B3, GPS, GLONASS, Galileo & BeiDou antenna  | 
|       TRMSPS986 NONE    |      L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/B1/B2/B3, GPS, GLONASS, Galileo & BeiDou antenna  | 
|       3S-02-TSADM NONE    |      TSA-100 assembly with Dorne Margolin antenna  | 
|       ACC_G5ANT_72AT1 NONE    |      ACTIVE GPS/GLON./OMNISTAR 7" CR, RFC->N  | 
|       ACC123CGNSSA_XN NONE    |      Active GNSS Conical choke ring, RFC->N  | 
|       ACC2G1215A_XT_1 NONE    |      ACTIVE L1/L2 GPS, 2.6", label top->N  | 
|       ACC3G1215A_XT_1 NONE    |      ACTIVE L1/L2 GPS, 3.5", top of label->N  | 
|       ACC42G1215A_XT1 NONE    |      ACTIVE L1/L2 GPS, 743 ARINC, ARROW->N  | 
|       ACC4G1215A_XT_1 NONE    |      ACTIVE L1/L2 GPS Mini ARINC, arrow->N  | 
|       ACC53G1215A_XT1 NONE    |      ACTIVE L1/L2 GPS, 5" GP survey, RFC->N  | 
|       ACC53GO1215AXT1 NONE    |      L1/L2 GPS/GLONASS, OMNISTAR, RFC->N  | 
|       ACC72CGNSSA NONE    |      P/N 72CGNSSA-XN-1 7in Conical CR RFC->N  | 
|       ACC72GNSSA_XT_1 NONE    |      ACTIVE GNSS, 7" choke ring, RFC->N  | 
|       ACCG3ANT_3AT1 NONE    |      ACTIVE L1 GPS/GLON/OMNISTR,label top->N  | 
|       ACCG3ANT_42AT1 NONE    |      ACTIVE L1 GPS/GLONASS/OMNSTR, ARROW->N  | 
|       ACCG3ANT_52AT1 NONE    |      ACTIVE L1 GPS/GLONASS/OMNISTAR, RFC->N  | 
|       ACCG5ANT_123CAN NONE    |      Active G5 Conical Choke Ring RFC->North  | 
|       ACCG5ANT_2AT1 NONE    |      ACTIVE L1/L2 GPS/GLONASS, lable top->N  | 
|       ACCG5ANT_3AT1 NONE    |      ACTIVE GPS/GLON./OMNISTAR, labeltop->N  | 
|       ACCG5ANT_42AT1 NONE    |      ACTIVE GPS/GLONASS/OMNISTAR, arrow->N  | 
|       ADVNULLANTENNA NONE    |      Nullantenna defined by AdV (Sapos)  | 
|       AERAT1675_120 NONE    |      Aeroantenna GPS chokering antenna GPS: L1/L2/L5 GLO: G1/G2  | 
|       AERAT1675_120 SPKE    |      Aeroantenna GPS chokering antenna GPS: L1/L2/L5 GLO: G1/G2  | 
|       AERAT1675_180 NONE    |      L-Band GPS Glonass Airborne  | 
|       AERAT1675_182 NONE    |      GNSS Machine Control AT1675-182, RFC->N  | 
|       AERAT1675_29 NONE    |      Aeroantenna L1/L2 GPS + GLONASS Survey Antenna Ceramic patch element,internal groundplane,chokering  | 
|       AERAT1675_382 NONE    |      TNCF-000-RG-39-NM, RF connector->North  | 
|       AERAT1675_80 NONE    |      TNCF-000-RG-43-NM, top of label->North  | 
|       AERAT2775_150 NONE    |      L1/L2  | 
|       AERAT2775_159 NONE    |      AeroAnt AT2775-159W +radome  | 
|       AERAT2775_159 SPKE    |      AeroAnt AT2775-159W +radome  | 
|       AERAT2775_160 NONE    |      L1/L2  | 
|       AERAT2775_270 NONE    |      L1/L2  | 
|       AERAT2775_41 NONE    |      Aviation L1/L2  | 
|       AERAT2775_42 NONE    |      Geodetic L1/L2  | 
|       AERAT2775_42+CR NONE    |      Marine III +CR adaptor  | 
|       AERAT2775_43 NONE    |      Aeroantenna L1/L2 GPS Survey Antenna Ceramic patch element,internal groundplane,chokering  | 
|       AERAT2775_43 SPKE    |      Aeroantenna L1/L2 GPS Survey Antenna Ceramic patch element,internal groundplane,chokering  | 
|       AERAT2775_62 NONE    |      L1/L2  | 
|       AOAD/M_B NONE    |      Dorne Margolin with chokerings (Rogue, AOA design)  | 
|       AOAD/M_T NONE    |      Dorne Margolin with chokerings (TurboRogue)/part #s 7490400-1 7490400-4 7490582-1 7490582-2 7490582-B  | 
|       AOARASCAL NONE    |      Rascal RTK  | 
|       APSAPS-3 NONE    |      Integrated GPS L1/L2+L2C, GLO L1/L2 antenna  | 
|       ASH110454 NONE    |      ProMark2 L1  | 
|       ASH111660 NONE    |      L1 GPS/GLONASS, base of RF connector->N  | 
|       ASH111661 NONE    |      L1/L2/L5 GNSS survey antenna, base of RF connector  | 
|       ASH700228A NONE    |      Geodetic L1/L2 Model 700228A 11.2 inch groundplane, handles 8 holes labeled A-H for HI measurement leveling bubble, compass, external LNA, 8 attachments for extended groundplane  | 
|       ASH700228C NONE    |      Geodetic L1/L2 Model 700228C eliminated leveling bubble  | 
|       ASH700228E NONE    |      Geodetic L1/L2 "REV. B" 700228E (same as D)  | 
|       ASH700700.A NONE    |      Dual freq. marine antenna Model 700700.A  | 
|       ASH700700.B NONE    |      Dual freq. marine antenna Model 700700.B  | 
|       ASH700718A NONE    |      Geodetic III "Whopper" Model 700718A 14.5 inch groundplane, new antenna element, compass, no handles  | 
|       ASH700829.2 SNOW    |      Geodetic III "Whopper" Model 700829.2 (USCG) same as 700718 but with "snow cone" antenna dome and weather proof paint  | 
|       ASH700936A_M NONE    |      Dorne Margolin with chokerings, Model 700936A C146 Dorne Margolin element, milled chokerings  | 
|       ASH700936A_M SNOW    |      Dorne Margolin with chokerings, Model 700936A C146 Dorne Margolin element, milled chokerings  | 
|       ASH700936B_M NONE    |      Dorne Margolin with chokerings, Model 700936B changed internal RF cabling  | 
|       ASH700936B_M SNOW    |      Dorne Margolin with chokerings, Model 700936B changed internal RF cabling  | 
|       ASH700936C_M NONE    |      Dorne Margolin with chokerings, Model 700936C improved antenna element centering  | 
|       ASH700936C_M SNOW    |      Dorne Margolin with chokerings, Model 700936C improved antenna element centering  | 
|       ASH700936D_M NONE    |      Dorne Margolin with chokerings, Model 700936D same as 700936C, logo added to antenna dome  | 
|       ASH700936D_M SCIS    |      Dorne Margolin with chokerings, Model 700936D same as 700936C, logo added to antenna dome  | 
|       ASH700936D_M SNOW    |      Dorne Margolin with chokerings, Model 700936D same as 700936C, logo added to antenna dome  | 
|       ASH700936E NONE    |      Dorne Margolin with chokerings, Model 700936 REV E  | 
|       ASH700936E SNOW    |      Dorne Margolin with chokerings, Model 700936 REV E  | 
|       ASH700936E_C NONE    |      Dorne Margolin with chokerings, Model 700936.02 REV E cast chokerings, original SCIGN design - recalled  | 
|       ASH700936E_C SNOW    |      Dorne Margolin with chokerings, Model 700936.02 REV E cast chokerings, original SCIGN design - recalled  | 
|       ASH700936F_C NONE    |      Dorne Margolin with chokerings, Model 700936.02 REV F same as ASH700936E_C - recalled  | 
|       ASH701008.01B NONE    |      Geodetic IIIA, Model 701008-01(B)  | 
|       ASH701073.1 NONE    |      GPS/GLONASS (GG) dual-frequency with chokerings Model 701073 REV 1, supplied with Z18 receiver  | 
|       ASH701073.3 NONE    |      Model 701073 REV 3  | 
|       ASH701933B_M NONE    |      Dorne Margolin with chokerings, Model 701933 REV B milled chokerings, watertight design, shallow threads  | 
|       ASH701933B_M SNOW    |      Dorne Margolin with chokerings, Model 701933 REV B milled chokerings, watertight design, shallow threads  | 
|       ASH701933C_M NONE    |      Dorne Margolin with chokerings, Model 701933 REV C milled chokerings, watertight design, shallow threads, no humidity indicator  | 
|       ASH701933C_M SCIS    |      Dorne Margolin with chokerings, Model 701933 REV C milled chokerings, watertight design, shallow threads, no humidity indicator  | 
|       ASH701933C_M SCIT    |      Dorne Margolin with chokerings, Model 701933 REV C milled chokerings, watertight design, shallow threads, no humidity indicator  | 
|       ASH701933C_M SNOW    |      Dorne Margolin with chokerings, Model 701933 REV C milled chokerings, watertight design, shallow threads, no humidity indicator  | 
|       ASH701941.1 NONE    |      Dual Frequency GPS/GLONASS Model 701941-NN REV 1  | 
|       ASH701941.B NONE    |      Dual Frequency GPS/GLONASS Model 701941-NN REV B  | 
|       ASH701941.B SCIS    |      Dual Frequency GPS/GLONASS Model 701941-NN REV B  | 
|       ASH701945.02B NONE    |      N/A  | 
|       ASH701945.02B SCIS    |      N/A  | 
|       ASH701945.02B SCIT    |      N/A  | 
|       ASH701945.02B SNOW    |      N/A  | 
|       ASH701945B_M NONE    |      Dorne Margolin with chokerings, Model 701945-NN REV B milled chokerings, watertight design (replaces recalled SCIGN ASH700936E_C antenna)  | 
|       ASH701945B_M SCIS    |      Dorne Margolin with chokerings, Model 701945-NN REV B milled chokerings, watertight design (replaces recalled SCIGN ASH700936E_C antenna)  | 
|       ASH701945B_M SCIT    |      Dorne Margolin with chokerings, Model 701945-NN REV B milled chokerings, watertight design (replaces recalled SCIGN ASH700936E_C antenna)  | 
|       ASH701945B_M SNOW    |      Dorne Margolin with chokerings, Model 701945-NN REV B milled chokerings, watertight design (replaces recalled SCIGN ASH700936E_C antenna)  | 
|       ASH701945C_M NONE    |      Dorne Margolin with chokerings, Model 701945-NN REV C milled chokerings, watertight design  | 
|       ASH701945C_M PFAN    |      Dorne Margolin with chokerings, Model 701945-NN REV C milled chokerings, watertight design  | 
|       ASH701945C_M SCIS    |      Dorne Margolin with chokerings, Model 701945-NN REV C milled chokerings, watertight design  | 
|       ASH701945C_M SCIT    |      Dorne Margolin with chokerings, Model 701945-NN REV C milled chokerings, watertight design  | 
|       ASH701945C_M SNOW    |      Dorne Margolin with chokerings, Model 701945-NN REV C milled chokerings, watertight design  | 
|       ASH701945D_M NONE    |      Dorne Margolin with chokerings, Model 701945-NN REV D (only a few manufactured)  | 
|       ASH701945D_M SCIS    |      Dorne Margolin with chokerings, Model 701945-NN REV D (only a few manufactured)  | 
|       ASH701945D_M SCIT    |      Dorne Margolin with chokerings, Model 701945-NN REV D (only a few manufactured)  | 
|       ASH701945D_M SNOW    |      Dorne Margolin with chokerings, Model 701945-NN REV D (only a few manufactured)  | 
|       ASH701945E_M NONE    |      Dorne Margolin with chokerings, Model 701945-NN REV E milled chokerings, watertight design (includes E1)  | 
|       ASH701945E_M SCIS    |      Dorne Margolin with chokerings, Model 701945-NN REV E milled chokerings, watertight design (includes E1)  | 
|       ASH701945E_M SCIT    |      Dorne Margolin with chokerings, Model 701945-NN REV E milled chokerings, watertight design (includes E1)  | 
|       ASH701945E_M SNOW    |      Dorne Margolin with chokerings, Model 701945-NN REV E milled chokerings, watertight design (includes E1)  | 
|       ASH701945G_M NONE    |      Dorne Margolin with chokerings, Model 701945-NN REV G (no physical changes from REV E)  | 
|       ASH701945G_M SCIS    |      Dorne Margolin with chokerings, Model 701945-NN REV G (no physical changes from REV E)  | 
|       ASH701945G_M SCIT    |      Dorne Margolin with chokerings, Model 701945-NN REV G (no physical changes from REV E)  | 
|       ASH701945G_M SNOW    |      Dorne Margolin with chokerings, Model 701945-NN REV G (no physical changes from REV E)  | 
|       ASH701946.2 NONE    |      Dorne Margolin with chokerings,Model 701946-NN REV 2 (GPS + GLONASS)  | 
|       ASH701946.3 NONE    |      Dorne Margolin with chokerings,Model 701946-NN REV 3 (GPS + GLONASS)  | 
|       ASH701975.01A NONE    |      Geodetic IV, Rev A  | 
|       ASH701975.01AGP NONE    |      Geodetic IV, Rev A with groundplane  | 
|       ASH701975.01BGP NONE    |      Geodetic IV, w/Groundplane  | 
|       ASH802129 NONE    |      GNSS receiver, ProMark 500, ctrl pnl->N  | 
|       ASH802147_A NONE    |      N/A  | 
|       CHCA220GR NONE    |      Multi-purpose compact geodetic antenna with integrated radome. GPS: L1/L2/L5, GLO: L1/L2/L3, GAL: E2-L1-E1/E5a/E5b/E6/AltBOC, BDS: B1/B2/B3, L-Band  | 
|       CHCA300GNSS NONE    |      Multi-purpose compact geodetic antenna with integrated radome. GPS: L1/L2, GLO: L1/L2  | 
|       CHCC220GR CHCD    |      Multi-purpose machined copper alloy chokering antenna with Dorne Margolin element & LNA (Rev. 1; serial number starting with 12 or 13; w/o north mark). GPS: L1/L2/L5, GLO: L1/L2/L3, BDS: B1/B2/B3, GAL: E2-L1-E1/E5a/E5b/E6/AltBOC, L-band  | 
|       CHCC220GR NONE    |      Multi-purpose machined copper alloy chokering antenna with Dorne Margolin element & LNA (Rev. 1; serial number starting with 12 or 13; w/o north mark). GPS: L1/L2/L5, GLO: L1/L2/L3, BDS: B1/B2/B3, GAL: E2-L1-E1/E5a/E5b/E6/AltBOC, L-band  | 
|       CHCI80 NONE    |      Internal geodetic antenna. GPS: L1/L2/L5, GLO: L1/L2/L3, GAL: E1/E5a/E5b, BDS: B1/B2  | 
|       CHCX900B NONE    |      Internal geodetic antenna. GPS: L1/L2/L5, GLO: L1/L2/L3, BDS: B1/B2/B3, GAL: E2-L1-E1/E5a/E5b/E6/AltBOC, L-Band  | 
|       CHCX900R NONE    |      Internal geodetic antenna. GPS: L1/L2/L5, GLO: L1/L2/L3, BDS: B1/B2/B3, GAL: E2-L1-E1/E5a/E5b/E6/AltBOC, L-Band  | 
|       CHCX900S-OPUS NONE    |      MMI->N  | 
|       CHCX90D-OPUS NONE    |      Internal geodetic antenna with large ground plane & integrated radome. GPS: L1/L2, L-Band  | 
|       CHCX91+S NONE    |      Internal geodetic antenna. GPS: L1/L2/L5, GLO: L1/L2/L3, BDS: B1/B2/B3, GAL: E2-L1-E1/E5a/E5b/E6/AltBOC, L-Band  | 
|       CHCX91B NONE    |      Internal geodetic antenna. GPS: L1/L2/L5, GLO: L1/L2/L3, BDS: B1/B2/B3, GAL: E2-L1-E1/E5a/E5b/E6/AltBOC, L-Band  | 
|       CHCX91R NONE    |      Internal geodetic antenna. GPS: L1/L2/L5, GLO: L1/L2/L3, BDS: B1/B2/B3, GAL: E2-L1-E1/E5a/E5b/E6/AltBOC, L-Band  | 
|       HEMA631 NONE    |      Model:A631,PN:804-0168-10 Rev A, DAC->N  | 
|       HEMS320 NONE    |      Integrated GNSS ant/receiver display ->N  | 
|       HEMS631 NONE    |      Integrated GPS L1/L2+L2C/L5, GLO L1/L2/L3, GAL E1/E5a/E5b/AltBOC/E6, BDS B1/B2a/B2b/ACEBOC/B3, QZSS L1/L2/L5, SBAS L1/L5, L-Band Atlas  | 
|       HITV30 NONE    |      Hi-Target V30 P/N 0201010223 DSP->North  | 
|       HXCCA7607A NONE    |      Model HX-CA7607A NOM->N  | 
|       HXCCG7601A HXCG    |      Model HX-CG7601A RXC->N  | 
|       HXCCG7601A NONE    |      Model HX-CG7601A RXC->N  | 
|       HXCCG7602A HXCG    |      Model HX-CG7602A NOM->N  | 
|       HXCCG7602A NONE    |      Model HX-CG7602A NOM->N  | 
|       HXCCGX601A HXCS    |      Model HX-CGX601A RXC->N  | 
|       HXCCGX601A NONE    |      Model HX-CGX601A RXC->N  | 
|       HXCCSX601A NONE    |      Model HX-CSX601A RXC->South Arrow->N  | 
|       HXCGG486A HXCS    |      Model HX-GG486A GNSS RXC->N  | 
|       HXCGG486A NONE    |      Model HX-GG486A GNSS RXC->N  | 
|       HXCGS488A NONE    |      Model HX-GS488A GNSS RFC->South Arrow->N  | 
|       ITT3750323 NONE    |      Chokering antenna with low noise amplifier  | 
|       ITT3750323 SCIS    |      Chokering antenna with low noise amplifier  | 
|       JAV_GRANT-G3T NONE    |      External GPS L1/L2/L5, GLO L1/L2, GAL E1/E5A  | 
|       JAV_RINGANT_G3T JAVC    |      External GPS L1/L2/L5, GLO L1/L2, GAL E1/E5A chokering antenna  | 
|       JAV_RINGANT_G3T NONE    |      External GPS L1/L2/L5, GLO L1/L2, GAL E1/E5A chokering antenna  | 
|       JAV_TRIUMPH-1 NONE    |      Integrated GPS L1/L2/L2C/L5, GLONASS L1/L2, Galileo E1/E5A Triumph1 antenna  | 
|       JAV_TRIUMPH-1R NONE    |      Integrated GPS L1/L2/L5, GAL E1/E5A/E5B, GLO L1/L2/L3, BDS B1/B2, QZSS L1/L2/L5 Triumph1 antenna with radio modem antenna  | 
|       JAVGRANT_G5T+GP JVSD    |      External GPS L1/L2/L5, GLO L1/L2/L3, GAL E1/E5A/E5B/E6, BDS B1/B2/B3, QZSS L1/L2/L5/LEX with ground plane  | 
|       JAVRINGANT_DM JVDM    |      External GPS L1/L2/L5, GLO L1/L2, GAL E1/E5/E6 chokering antenna with Dorne Margolin element  | 
|       JAVRINGANT_DM NONE    |      External GPS L1/L2/L5, GLO L1/L2, GAL E1/E5/E6 chokering antenna with Dorne Margolin element  | 
|       JAVRINGANT_DM SCIS    |      External GPS L1/L2/L5, GLO L1/L2, GAL E1/E5/E6 chokering antenna with Dorne Margolin element  | 
|       JAVRINGANT_DM SCIT    |      External GPS L1/L2/L5, GLO L1/L2, GAL E1/E5/E6 chokering antenna with Dorne Margolin element  | 
|       JAVRINGANT_G5T JAVC    |      External GPS L1/L2/L5, GLO L1/L2/L3, GAL E1/E5A/E5B/E6, BDS B1/B2/B3, QZSS L1/L2/L5/LEX chokering antenna  | 
|       JAVRINGANT_G5T JAVD    |      External GPS L1/L2/L5, GLO L1/L2/L3, GAL E1/E5A/E5B/E6, BDS B1/B2/B3, QZSS L1/L2/L5/LEX chokering antenna  | 
|       JAVRINGANT_G5T NONE    |      External GPS L1/L2/L5, GLO L1/L2/L3, GAL E1/E5A/E5B/E6, BDS B1/B2/B3, QZSS L1/L2/L5/LEX chokering antenna  | 
|       JAVRT_G3T+A2 JAVC    |      AXIONET External GPS L1/L2/L5, GLO L1/L2, GAL E1/E5A chokering antenna  | 
|       JAVRT_G3T+A2 NONE    |      AXIONET External GPS L1/L2/L5, GLO L1/L2, GAL E1/E5A chokering antenna  | 
|       JAVTRIUMPH_VS NONE    |      Integrated GPS L1/L2/L5, GLONASS L1/L2, Galileo E1/E5 Triumph V.S. antenna  | 
|       JNSCHOKERING_DM NONE    |      Choke Ring -Radome  | 
|       JNSCR_C146-22-1 NONE    |      External GPS L1/L2, GLO L1/L2 chokering antenna with C146-22-1 element  | 
|       JNSMARANT_GGD NONE    |      low-profile, waterproof GPS/GLONASS external antenna  | 
|       JPLD/M_R NONE    |      Dorne Margolin element with chokerings (Rogue, JPL design)  | 
|       JPSLEGANT_E NONE    |      Antenna on flat groundplane  | 
|       JPSREGANT_DD_E NONE    |      Dual-depth chokering antenna, external  | 
|       JPSREGANT_SD_E NONE    |      Single-depth chokering antenna, external  | 
|       LEIAR10 NONE    |      Multi-purpose geodetic reference station antenna with large groundplane and integrated radome. GPS: L1,L2,L5 GLONASS: L1,L2,L3 Galileo: E2-L1-E1, E5a,E5b,E6,AltBOC BeiDou: B1,B2,B3 L-BAND  | 
|       LEIAR20 LEIM    |      Multi purpose GNSS choke ring antenna GPS: L1,L2,L5; GLO: L1,L2,L3; BDS: B1,B2,B3; GAL: E2-L1-E1,E5a,E5b,E6,AltBOC; L-BAND  | 
|       LEIAR20 NONE    |      Multi purpose GNSS choke ring antenna GPS: L1,L2,L5; GLO: L1,L2,L3; BDS: B1,B2,B3; GAL: E2-L1-E1,E5a,E5b,E6,AltBOC; L-BAND  | 
|       LEIAR25 LEIT    |      Dorne Margolin with 3D choke ring (Revision 2) GPS: L1,L2,L5 GLONASS: L1,L2,L3 Galileo: E2-L1-E1, E5a,E5b,E6,AltBOC BeiDou: B1,B2,B3 L-BAND [Note: Revision 1 was never released to public.]  | 
|       LEIAR25 NONE    |      Dorne Margolin with 3D choke ring (Revision 2) GPS: L1,L2,L5 GLONASS: L1,L2,L3 Galileo: E2-L1-E1, E5a,E5b,E6,AltBOC BeiDou: B1,B2,B3 L-BAND [Note: Revision 1 was never released to public.]  | 
|       LEIAR25.R3 BEVA    |      Dorne Margolin with 3D choke ring (Revision 3) GPS: L1,L2,L5 GLONASS: L1,L2,L3 Galileo: E2-L1-E1, E5a,E5b,E6,AltBOC BeiDou: B1,B2,B3 L-BAND Includes insert for enhanced L5 performance.  | 
|       LEIAR25.R3 LEIT    |      Dorne Margolin with 3D choke ring (Revision 3) GPS: L1,L2,L5 GLONASS: L1,L2,L3 Galileo: E2-L1-E1, E5a,E5b,E6,AltBOC BeiDou: B1,B2,B3 L-BAND Includes insert for enhanced L5 performance.  | 
|       LEIAR25.R3 NONE    |      Dorne Margolin with 3D choke ring (Revision 3) GPS: L1,L2,L5 GLONASS: L1,L2,L3 Galileo: E2-L1-E1, E5a,E5b,E6,AltBOC BeiDou: B1,B2,B3 L-BAND Includes insert for enhanced L5 performance.  | 
|       LEIAR25.R3 SCIS    |      Dorne Margolin with 3D choke ring (Revision 3) GPS: L1,L2,L5 GLONASS: L1,L2,L3 Galileo: E2-L1-E1, E5a,E5b,E6,AltBOC BeiDou: B1,B2,B3 L-BAND Includes insert for enhanced L5 performance.  | 
|       LEIAR25.R3 SCIT    |      Dorne Margolin with 3D choke ring (Revision 3) GPS: L1,L2,L5 GLONASS: L1,L2,L3 Galileo: E2-L1-E1, E5a,E5b,E6,AltBOC BeiDou: B1,B2,B3 L-BAND Includes insert for enhanced L5 performance.  | 
|       LEIAR25.R4 LEIT    |      Dorne Margolin with 3D choke ring (Revision 4) GPS: L1,L2,L5 GLONASS: L1,L2,L3 Galileo: E2-L1-E1, E5a,E5b,E6,AltBOC BeiDou: B1,B2,B3 L-BAND Includes insert for enhanced L5 performance.  | 
|       LEIAR25.R4 NONE    |      Dorne Margolin with 3D choke ring (Revision 4) GPS: L1,L2,L5 GLONASS: L1,L2,L3 Galileo: E2-L1-E1, E5a,E5b,E6,AltBOC BeiDou: B1,B2,B3 L-BAND Includes insert for enhanced L5 performance.  | 
|       LEIAR25.R4 SCIT    |      Dorne Margolin with 3D choke ring (Revision 4) GPS: L1,L2,L5 GLONASS: L1,L2,L3 Galileo: E2-L1-E1, E5a,E5b,E6,AltBOC BeiDou: B1,B2,B3 L-BAND Includes insert for enhanced L5 performance.  | 
|       LEIAS10 NONE    |      External geodetic multi-frequency antenna, GPS/GLO/GAL/BDS/L-band  | 
|       LEIAS11 NONE    |      External geodetic multi-frequency antenna, GPS/GLO/GAL/BDS/QZSS/L-band  | 
|       LEIAT202-GP NONE    |      External micropulse antenna L1/L2, no groundplane with series 200 receivers  | 
|       LEIAT302+GP NONE    |      External micropulse antenna L1/L2, with groundplane with series 300 receivers  | 
|       LEIAT302-GP NONE    |      External micropulse antenna L1/L2, no groundplane with series 300 receivers  | 
|       LEIAT303 LEIC    |      Micropulse antenna L1/L2, with chokerings  | 
|       LEIAT303 NONE    |      Micropulse antenna L1/L2, with chokerings  | 
|       LEIAT502 NONE    |      External antenna with Aero element L1/L2, with series 500 receivers  | 
|       LEIAT503 LEIC    |      Micropulse antenna with chokerings, L1/L2 (identical to LEICA AT303)  | 
|       LEIAT503 NONE    |      Micropulse antenna with chokerings, L1/L2 (identical to LEICA AT303)  | 
|       LEIAT504 LEIS    |      L1/L2 Dorne Margolin antenna with chokerings (designed after DORNE MARGOLIN T)  | 
|       LEIAT504 NONE    |      L1/L2 Dorne Margolin antenna with chokerings (designed after DORNE MARGOLIN T)  | 
|       LEIAT504 OLGA    |      L1/L2 Dorne Margolin antenna with chokerings (designed after DORNE MARGOLIN T)  | 
|       LEIAT504GG LEIS    |      L1/L2 Dorne Margolin antenna with chokerings (designed after DORNE MARGOLIN T), GPS & GLONASS  | 
|       LEIAT504GG NONE    |      L1/L2 Dorne Margolin antenna with chokerings (designed after DORNE MARGOLIN T), GPS & GLONASS  | 
|       LEIAT504GG SCIS    |      L1/L2 Dorne Margolin antenna with chokerings (designed after DORNE MARGOLIN T), GPS & GLONASS  | 
|       LEIAT504GG SCIT    |      L1/L2 Dorne Margolin antenna with chokerings (designed after DORNE MARGOLIN T), GPS & GLONASS  | 
|       LEIATX1230 NONE    |      Internal geodetic antenna L1/L2, SmartTrack, GPS  | 
|       LEIATX1230+GNSS NONE    |      Internal geodetic antenna, SmartTrack+, GPS L1/L2/L5, GLONASS, Galileo, BeiDou  | 
|       LEIATX1230GG NONE    |      Internal geodetic antenna L1/L2, SmartTrack, GPS & GLONASS  | 
|       LEIAX1202 NONE    |      External geodetic antenna L1/L2, SmartTrack with series 1200 receivers  | 
|       LEIAX1202A NONE    |      L1/L2  | 
|       LEIAX1202GG NONE    |      External geodetic antenna L1/L2, SmartTrack with series 1200 receivers, GPS & GLONASS  | 
|       LEIAX1203+GNSS NONE    |      External geodetic antenna, SmartTrack+ with series 1200 receivers, GPS L1/L2/L5, GLONASS, Galileo, BeiDou  | 
|       LEIGS08 NONE    |      Internal geodetic antenna L1/L2, SmartTrack+, GPS & GLONASS  | 
|       LEIGS08PLUS NONE    |      Internal geodetic antenna L1/L2, SmartTrack, GPS & GLONASS  | 
|       LEIGS09 NONE    |      Internal geodetic antenna L1/L2, SmartTrack+, GPS & GLONASS  | 
|       LEIGS12 NONE    |      Internal geodetic antenna L1/L2, SmartTrack+, GPS & GLONASS  | 
|       LEIGS14 NONE    |      Internal geodetic antenna, SmartTrack, GPS: L1,L2,L2C; GLO: L1,L2; GAL: E1; SBAS  | 
|       LEIGS15 NONE    |      Internal geodetic antenna, SmartTrack+, GPS L1/L2/L5, GLONASS, Galileo, BeiDou  | 
|       LEIICG60 NONE    |      Internal geodetic antenna, SmartTrack+, GPS L1/L2/L5, GLONASS, Galileo, BeiDou  | 
|       LEIMNA950GG NONE    |      Internal geodetic antenna L1/L2, SmartTrack, GPS & GLONASS (PowerAntenna)  | 
|       LEISR299_INT NONE    |      Internal antenna with Ball element L1/L2, part of the SR299 receiver  | 
|       LEISR399_INT NONE    |      Revised antenna with modified mount design L1/L2, part of the SR399 receiver, made or serviced *after* Aug 97 (see http://www.ngs.noaa.gov/ANTCAL) Warning: Descriptions interchanged in June 2009.  | 
|       MAC4647942 MMAC    |      Crossed-dipole antenna with large groundplane, Model Number 4647942  | 
|       MAG105645 NONE    |      L1/L2 GPS  | 
|       MAG111406 NONE    |      (AT1675-7MW),North: RF CONN  | 
|       MAG990596 NONE    |      PROMARK500, TNC CONNECTOR TO NORTH  | 
|       MPL_WAAS_2224NW NONE    |      MicroPulse WAAS Unit 2224NW  | 
|       MPL_WAAS_2225NW NONE    |      MicroPulse WAAS L1/L2/L5 2225NW  | 
|       MPL1230 NONE    |      L1/L2 Surveying, Choke Ring  | 
|       MPL1370W NONE    |      L1  | 
|       NAV_ANT3001BR SPKE    |      GPS L1/L2/L2C/L5, GLONASS G1/G2, Galileo E1/E5a, choke ring antenna  | 
|       NAVAN2004T NONE    |      GPS L1/L2/L-Band Antenna, Survey Mount  | 
|       NAVAN2008T NONE    |      GPS L1/L2/L-Band Antenna, Aircraft Mount FAA Cert.  | 
|       NAVRT3010S NONE    |      RTK GPS Antenna+Receiver  | 
|       NAVSF2040G NONE    |      GPS L1/L2/SBAS/StarFire Antenna  | 
|       NAX3G+C NONE    |      NavXperience  | 
|       NOV_WAAS_600 NONE    |      NOV600 element in MPL assembly (used by WAAS/NGS)  | 
|       NOV501 NONE    |      GPS-501 L1  | 
|       NOV501+CR NONE    |      GPS-501 L1 with chokerings  | 
|       NOV502 NONE    |      GPS-502 L1/L2  | 
|       NOV502+CR NONE    |      GPS-502 L1/L2 with chokerings  | 
|       NOV503+CR NONE    |      GPS-503 L1/L2 with chokerings  | 
|       NOV503+CR SPKE    |      GPS-503 L1/L2 with chokerings  | 
|       NOV531 NONE    |      GPS-531 L1  | 
|       NOV531+CR NONE    |      GPS-531 L1 with chokerings  | 
|       NOV533 RADM    |      L1/L2 compact CR, ANT-533 w/radome  | 
|       NOV600 NONE    |      L1/L2 GPS Antenna (Pinwheel Technology)  | 
|       NOV701GG_1.03 NONE    |      GPS-701-GG  | 
|       NOV701GGL NONE    |      GPS-701GG GPS L1, GLONASS L1, L-Band (Pinwheel Tech.)  | 
|       NOV702 NONE    |      GPS-702 RoHS-compliant GPS L1/L2 (Pinwheel Tech.)  | 
|       NOV702_3.00 NONE    |      GPS-702 L1/L2  | 
|       NOV702GG NONE    |      GPS-702GG GPS L1/L2, GLONASS L1/L2 (Pinwheel Tech.)  | 
|       NOV702GG_1.02 NONE    |      GPS-702-GG  | 
|       NOV702GG_1.03 NONE    |      GPS-702-GG  | 
|       NOV702GGL_1.01 NONE    |      GPS-702-GGL  | 
|       NOV702L_1.01 NONE    |      GPS-702L  | 
|       NOV702L_1.03 NONE    |      GPS-702L  | 
|       NOV750.R4 NONE    |      Dorne Margolin with 3D choke ring ground plane rev. 4 GPS: L1,L2,L2C,L5 GLONASS: L1,L2,L3 Galileo: L1, E5a,E5b,E6,AltBOC BeiDou: B1,B2,B3 L-BAND  | 
|       NOV750.R4 NOVS    |      Dorne Margolin with 3D choke ring ground plane rev. 4 GPS: L1,L2,L2C,L5 GLONASS: L1,L2,L3 Galileo: L1, E5a,E5b,E6,AltBOC BeiDou: B1,B2,B3 L-BAND  | 
|       NOV750.R4 SCIS    |      Dorne Margolin with 3D choke ring ground plane rev. 4 GPS: L1,L2,L2C,L5 GLONASS: L1,L2,L3 Galileo: L1, E5a,E5b,E6,AltBOC BeiDou: B1,B2,B3 L-BAND  | 
|       NOV750.R4 SCIT    |      Dorne Margolin with 3D choke ring ground plane rev. 4 GPS: L1,L2,L2C,L5 GLONASS: L1,L2,L3 Galileo: L1, E5a,E5b,E6,AltBOC BeiDou: B1,B2,B3 L-BAND  | 
|       RNG80971.00 NONE    |      Boreas GNSS antenna L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BeiDou  | 
|       RNG80971.00 SCIT    |      Boreas GNSS antenna L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BeiDou  | 
|       RNG80971.00 TZGD    |      Boreas GNSS antenna L1/L2/L5/G1/G2/G3/E1/E2/E5ab/E6/BeiDou  | 
|       RNGSMAXGEO-A NONE    |      S-MAX GEO, 240 channels GPS L1/L2, GLONASS, BeiDou, Galileo, QZSS, SBAS, L-band integrated receiver/ant.  | 
|       SEN67157514 NONE    |      L1/L2, (+26dB amp)  | 
|       SEN67157514+CR NONE    |      L1/L2, (+26dB amp), +cr  | 
|       SEN67157549 NONE    |      L1  | 
|       SEN67157549+CR NONE    |      L1, +chokerings  | 
|       SEN67157596 NONE    |      L1/L2  | 
|       SEN67157596+CR NONE    |      Sensor Systems L1/L2, PN:S67-1575-96 + chokerings  | 
|       SEP_POLANT+ NONE    |      GPS L1/L2, AT2775-229S, N arrow on top  | 
|       SEP_POLANT+_GG NONE    |      GNSS L1/L2, AT1675-29S, N arrow on top  | 
|       SEPCHOKE_B3E6 NONE    |      multi-constellation choke ring GPS L1/L2/L5, GLO L1/L2/L3, GAL E1/E5a/E5b/E6, | BDS B1/B2/B3, QZSS L1/L2/L5/LEX, L-band  | 
|       SEPCHOKE_B3E6 SPKE    |      multi-constellation choke ring GPS L1/L2/L5, GLO L1/L2/L3, GAL E1/E5a/E5b/E6, | BDS B1/B2/B3, QZSS L1/L2/L5/LEX, L-band  | 
|       SEPCHOKE_MC NONE    |      multi-constellation choke ring GPS/GAL/BDS:L1+L2+L5/E5 GLO:L1+L2+L3 L-band  | 
|       SEPCHOKE_MC SPKE    |      multi-constellation choke ring GPS/GAL/BDS:L1+L2+L5/E5 GLO:L1+L2+L3 L-band  | 
|       SEPPOLANT_X_MF NONE    |      multi-constellation antenna GPS/GAL:L1/E1+L2+L5/E5 BDS:B1/B2 GLO:L1+L2+L3 L-band  | 
|       SEPPOLANT_X_SF NONE    |      AT1675-339S, GPS/GLONASS L1, arrow to N  | 
|       SOK_GSR2700IS NONE    |      Sokkia GSR2700 IS (L1/L2) Pinwheel Tech  | 
|       SOK_GSR2700ISX NONE    |      Sokkia GSR2700 ISX, 14 GPS L1, 14 GPS L2, 6 GPS L5 12 GLONASS L1, 12 GLONASS L2 + 2 SBAS  | 
|       SOK_RADIAN_IS NONE    |      Radian IS L1/L2 RTK GPS integrated receiver+antenna  | 
|       SOK502 NONE    |      Sokkia SK520 L1/L2 GPS antenna  | 
|       SOK600 NONE    |      Sokkia SK600 L1/L2 GPS antenna  | 
|       SOK702 NONE    |      Sokkia SK702 L1/L2 GPS antenna  | 
|       SOKA110 NONE    |      Sokkia A110 (L1)  | 
|       SOKA120 NONE    |      Sokkia A120 (L1/L2)  | 
|       SOKGRX1 NONE    |      L1L2, TPS ctrl pnl->N  | 
|       SOKGRX1+10 NONE    |      10-cm standoff#808100  | 
|       SOKGRX2 NONE    |      GRX2 Display to North  | 
|       SOKGRX2+10 NONE    |      cm standoff P/N 808100  | 
|       SOKSTRATUS NONE    |      Sokkia Stratus (L1)  | 
|       SPP101861 NONE    |      SP60 TMT to North  | 
|       SPP39105.90 NONE    |      Epoch L1/L2 w/o GP  | 
|       SPP571212238+GP NONE    |      Spectra Precision groundplane  | 
|       SPP571908273+CR SPKE    |      chokerings, oblong antenna element  | 
|       SPP68410_10 NONE    |      EPOCH 50, 220 channels GPS L1/L2/L5, GLONASS, Galileo, SBAS integrated receiver/antenna  | 
|       SPP89823_10 NONE    |      ProMark 700, 220 channel GPS/GLONASS L1/L2, SBAS integrated receiver/antenna  | 
|       SPP91564_1 NONE    |      SP80, 240 channels GPS L1/L2/L5, GLONASS, BeiDou, Galileo, QZSS, SBAS integrated receiver/antenna  | 
|       SPP91564_2 NONE    |      SP80 with comm module MMI to North  | 
|       SPP98147_10 NONE    |      SPP98147_10  | 
|       SPPSP85 NONE    |      Integrated GPS: L1/L2/L5; GLO: L1/L2/L3; GAL: E1/E2/ E5ab; BDS: B1/B2; QZSS: L1/L2/L5; IRNSS L5; SBAS L1/ L5; L-band antenna  | 
|       SPPSP85 UHF NONE    |      Integrated GPS: L1/L2/L5; GLO: L1/L2/L3; GAL: E1/E2/ E5ab; BDS: B1/B2; QZSS: L1/L2/L5; IRNSS L5; SBAS L1/ L5; L-band antenna  | 
|       STH82VHX-BS601A NONE    |      Integrated GPS L1/L2+L2C/L5, GLONASS, BDS, SBAS SOUTH S82V2 GNSS antenna  | 
|       STHS82_7224V3.0 NONE    |      Integrated GPS L1/L2+L2C/L5, GLONASS, SBAS SOUTH S82T/S82V GNSS antenna  | 
|       STHS82HX-BS601A NONE    |      Integrated GPS L1/L2+L2C/L5, GLONASS, BDS, SBAS SOUTH S82-2013 GNSS antenna  | 
|       STHS86_7224V3.1 NONE    |      Integrated GPS L1/L2+L2C/L5, GLONASS, BDS, SBAS SOUTH S86T GNSS antenna  | 
|       STHS86HX-BS611A NONE    |      Integrated GPS L1/L2+L2C/L5, GLONASS, BDS, SBAS SOUTH S86-2013 GNSS antenna  | 
|       STXG5ANT_72AT1 NONE    |      ACTIVE GPS/GLON./OMNISTAR 7" CR, RXC->N  | 
|       STXS9PX001A NONE    |      Integrated GPS L1/L2+L2C/L5, GLONASS, Galileo, BeiDou, SBAS STONEX S9III+ GNSS antenna  | 
|       STXS9SA7224V3.0 NONE    |      Integrated GPS L1/L2+L2C/L5, GLONASS, Galileo, BeiDou, SBAS STONEX S9II GNSS antenna  | 
|       THA800961+REC NONE    |      Z-Max receiver + ant  | 
|       THA800961+RTK NONE    |      Z-Max w/RTK adaptor  | 
|       THA800961RECUHF NONE    |      Z-Max receiver +UHF Vortex adaptor  | 
|       THA800961RTKUHF NONE    |      Z-Max Receiver+RTK+UHF Vortex adaptors  | 
|       THANAP002 NONE    |      microstrip, Geodetic  | 
|       TOP700779A NONE    |      Model 700779.A (same as ASH700718A)  | 
|       TOP72110 NONE    |      Model 72110, used with the TURBO-SII receiver small radius with Dorne Margolin element  | 
|       TPS_CR.3 SCIS    |      radome #0010  | 
|       TPS_CR4+RD SCIS    |      Choke Ring+rd  | 
|       TPS_MC.A5 NONE    |      Topcon MC-A5 L1  | 
|       TPSCR.G3 NONE    |      Topcon GPS/GLONASS/Galileo choke ring antenna  | 
|       TPSCR.G3 SCIS    |      Topcon GPS/GLONASS/Galileo choke ring antenna  | 
|       TPSCR.G3 SCIT    |      Topcon GPS/GLONASS/Galileo choke ring antenna  | 
|       TPSCR.G3 TPSH    |      Topcon GPS/GLONASS/Galileo choke ring antenna  | 
|       TPSCR.G5 NONE    |      Topcon Multi-Constellation Geodetic Choke Ring Ant.  | 
|       TPSCR.G5 SCIS    |      Topcon Multi-Constellation Geodetic Choke Ring Ant.  | 
|       TPSCR.G5 SCIT    |      Topcon Multi-Constellation Geodetic Choke Ring Ant.  | 
|       TPSCR.G5 TPSH    |      Topcon Multi-Constellation Geodetic Choke Ring Ant.  | 
|       TPSCR.G5C NONE    |      GPS L1/L2/L5, GLO G1/G2/G3, GAL E1/E5ab/E6, BDS B1/B2/B3, SBAS geodetic choke ring antenna with enhanced interference suppression, P/N 01-070801-02LF  | 
|       TPSCR.G5C TPSH    |      GPS L1/L2/L5, GLO G1/G2/G3, GAL E1/E5ab/E6, BDS B1/B2/B3, SBAS geodetic choke ring antenna with enhanced interference suppression, P/N 01-070801-02LF  | 
|       TPSCR3_GGD CONE    |      Part No. 01-031401-01  | 
|       TPSCR3_GGD NONE    |      Part No. 01-031401-01  | 
|       TPSCR3_GGD OLGA    |      Part No. 01-031401-01  | 
|       TPSCR3_GGD PFAN    |      Part No. 01-031401-01  | 
|       TPSCR4 CONE    |      P/N 01-840002-01 Choke ring L1/L2  | 
|       TPSCR4 NONE    |      P/N 01-840002-01 Choke ring L1/L2  | 
|       TPSG3_A1 NONE    |      Topcon GPS/GLONASS/Galileo antenna with ground plane  | 
|       TPSG3_A1 TPSD    |      Topcon GPS/GLONASS/Galileo antenna with ground plane  | 
|       TPSG5_A1 NONE    |      GPS L1/L2/L5, GLO G1/G2/G3, GAL E1/E5ab/E6, BDS B1/B2/B3, SBAS antenna with integrated ground plane, P/N 1004478-01  | 
|       TPSGR3 NONE    |      Integrated antenna/receiver/modem GNSS L1/L2  | 
|       TPSGR5 NONE    |      GNSS integrated antenna/receiver 216 channel  | 
|       TPSHIPER_GD NONE    |      P/N 01-830401-01 Integrated antenna+receiver  | 
|       TPSHIPER_GGD NONE    |      P/N 01-840401-01 Antenna+receiver GPS/GLONASS  | 
|       TPSHIPER_II NONE    |      HiPerII, ctrl pnl->N  | 
|       TPSHIPER_II+10 NONE    |      10-cm standoff #51949  | 
|       TPSHIPER_LITE NONE    |      P/N 01-840802-03 Antenna+receiver+wireless, GPS  | 
|       TPSHIPER_PLUS NONE    |      P/N 01-840801-01 Antenna+receiver+wireless, G/G  | 
|       TPSHIPER_SR NONE    |      DSP/LCD notch to North  | 
|       TPSHIPER_SR+10 NONE    |      10cm standoff P/N:51949  | 
|       TPSHIPER_V NONE    |      Hiper V,Display to North  | 
|       TPSHIPER_V+10 NONE    |      10cm standoff P/N:51949  | 
|       TPSHIPER_XT NONE    |      Model TPSHIPER_LITE with SIMM card  | 
|       TPSLEGANT NONE    |      LegAnt, P/N : 01-830004-01,Arrow->N  | 
|       TPSLEGANT_G NONE    |      P/N 01-830005-01 L1  | 
|       TPSLEGANT2 NONE    |      P/N 01-830004-02 L1/L2  | 
|       TPSLEGANT3_UHF NONE    |      P/N 01-830004-03 L1/L2  | 
|       TPSMAPANT_B NONE    |      L1  | 
|       TPSMG_A2 NONE    |      L1/L2  | 
|       TPSODYSSEY_I NONE    |      Integrated antenna/receiver L1/L2  | 
|       TPSPG_A1 NONE    |      P/N 01-840201-04 L1/L2 without groundplane  | 
|       TPSPG_A1 TPSD    |      P/N 01-840201-04 L1/L2 without groundplane  | 
|       TPSPG_A1_6 NONE    |      PG-A1 arrow->N  | 
|       TPSPG_A1_6+GP NONE    |      PG-A1 w/GP, arrow->N  | 
|       TPSPG_A1+GP NONE    |      P/N 01-840201-04 L1/L2 with groundplane  | 
|       TPSPG_A2 NONE    |      microstrip  | 
|       TPSPG_A5 NONE    |      L1  | 
|       TPSPG_F1 NONE    |      P/N 01-080201-01 without GP Arrow->N  | 
|       TPSPG_F1+GP NONE    |      P/N 01-080201-01 w/ground plane Arrow->N  | 
|       TPSPG_S1 NONE    |      P/N 01-100301-01 without groundplane  | 
|       TPSPG_S1+GP NONE    |      P/N 01-100301-01 with groundplane  | 
|       TPSPN.A5 NONE    |      Topcon Multi-Constellation Geodetic Antenna with convex impedance ground plane  | 
|       TPSPN.A5 SCIS    |      Topcon Multi-Constellation Geodetic Antenna with convex impedance ground plane  | 
|       TPSPN.A5 SCIT    |      Topcon Multi-Constellation Geodetic Antenna with convex impedance ground plane  | 
|       TPSPN.A5 TPSH    |      Topcon Multi-Constellation Geodetic Antenna with convex impedance ground plane  | 
|       TWIVC6050 NONE    |      VeraChoke 6050 with 50 dB LNA, GPS/QZSS L1/L2/L5 GLONASS G1/G2/G3, Galileo E1/E5a/ E5b/E6, BDS B1/ B2/B2a/B3, QZSS L6, NavIC L5, L-band corrections  | 
|       TWIVC6050 SCIS    |      VeraChoke 6050 with 50 dB LNA, GPS/QZSS L1/L2/L5 GLONASS G1/G2/G3, Galileo E1/E5a/ E5b/E6, BDS B1/ B2/B2a/B3, QZSS L6, NavIC L5, L-band corrections  | 
|       TWIVC6050 SCIT    |      VeraChoke 6050 with 50 dB LNA, GPS/QZSS L1/L2/L5 GLONASS G1/G2/G3, Galileo E1/E5a/ E5b/E6, BDS B1/ B2/B2a/B3, QZSS L6, NavIC L5, L-band corrections  | 
|       TWIVC6150 NONE    |      VeraChoke 6150 with 50 dB LNA, GPS/QZSS L1/L2/L5 GLONASS G1/G2/G3, Galileo E1/E5a/ E5b/E6, BDS B1/ B2/B2a/B3, QZSS L6, NavIC L5, L-band corrections  | 
|       TWIVC6150 SCIS    |      VeraChoke 6150 with 50 dB LNA, GPS/QZSS L1/L2/L5 GLONASS G1/G2/G3, Galileo E1/E5a/ E5b/E6, BDS B1/ B2/B2a/B3, QZSS L6, NavIC L5, L-band corrections  | 
|       TWIVP6000 NONE    |      VeraPhase 6000 with 35 dB LNA in flat housing, P/N 33-603500-xx-01-11, GPS L1/L2/L5, GLO G1/G2/G3, GAL E1/E5/E5a+b/E6, BDS B1/B2/B3, L-band corrections  | 
|       TWIVP6050_CONE NONE    |      VeraPhase 6000 with 50 dB LNA in conical housing, P/N 33-605000-xx-01-01, GPS L1/L2/L5, GLO G1/G2/G3, GAL E1/E5/E5a+b/E6, BDS B1/B2/B3, L-band corrections  | 
|       TWIVSP6037L NONE    |      VeroStar VSP6037L with 37 dB LNA, GPS/QZSS L1/L2/L5, GLONASS G1/G2/G3, Galileo E1/E5a/E5b/E6, BDS B1/ B2/B2a/B3, QZSS L6, NavIC L5, L-band corrections
