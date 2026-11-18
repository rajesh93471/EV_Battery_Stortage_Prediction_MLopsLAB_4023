# Predicting Battery Shortages at an Electric Scooter Swapping Station

An end-to-end MLOps system that predicts whether a university-area electric scooter battery-swapping station will experience a battery shortage during the evening rush window (**5:00 PM – 7:00 PM**).
| Topic          | Colab Notebook |
|----------------|----------------|
| EV_Battery_Stortage_Prediction| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/11k5ukTMvRYxfc_kEcQXMbVjNw1u-6G7m?usp=sharing) |

---

## Overview & Problem Statement

Between **5:00 PM and 7:00 PM**, battery swap demand rises sharply as students leave campus and delivery riders return from shifts. A **battery shortage** (`battery_shortage = 1`) occurs when total customer swap requests exceed the station's available charged battery supply during that two-hour period.

To prevent operational stockouts, this system prioritizes **Recall for `battery_shortage = 1`** so station operators receive early alerts to rebalance inventory or throttle walk-ins.

---

