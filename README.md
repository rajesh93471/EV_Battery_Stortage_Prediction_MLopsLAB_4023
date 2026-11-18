# Predicting Battery Shortages at an Electric Scooter Swapping Station

An end-to-end MLOps system that predicts whether a university-area electric scooter battery-swapping station will experience a battery shortage during the evening rush window (**5:00 PM – 7:00 PM**).

---

## Overview & Problem Statement

Between **5:00 PM and 7:00 PM**, battery swap demand rises sharply as students leave campus and delivery riders return from shifts. A **battery shortage** (`battery_shortage = 1`) occurs when total customer swap requests exceed the station's available charged battery supply during that two-hour period.

To prevent operational stockouts, this system prioritizes **Recall for `battery_shortage = 1`** so station operators receive early alerts to rebalance inventory or throttle walk-ins.

---

