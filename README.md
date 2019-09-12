# Mode-S Workshop

This repository contains a set of tutorials that helps you to explore and decode common types of Mode-S data.

# Tutorials

## 1_quick_start
A quick view on what kind of useful information contains in ADS-B and Mode-S Comm-B communications.

## 2_understand_ADS-B_data
ADS-B is the most common open surveillance data. This tutorial walks you through the processing of decoding RAW ADS-B messages using `pyModeS` library.

## 3_understand_Comm-B_data
More state information are interrogated by air traffic control secondary surveillance data. These reply messages can be intercepted conveniently using the low-cost receivers. However, the challenge lies in estimating the Comm-B message types. This tutorial walks you through the processes of inferring Comm-B message types, as well as decoding them.

## 4_explore_trajectory
This turorial provides examples of using `pymodes-opensky` and `traffic` libraries to fetch and visualizing surveillance data from `opensky-network`.

# Dependencies

- `pyModeS`: https://github.com/junzis/pyModeS
- `pymodes-opensky`: https://github.com/junzis/pymodes-opensky
- `traffic`: https://github.com/xoolive/traffic
