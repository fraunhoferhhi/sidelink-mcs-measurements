# Measurement data for the paper "From Empirical Measurements to Augmented Data Rates: A Machine Learning Approach for MCS Adaptation in Sidelink Communication"

[1] Rokoni, A. A., Schäufele, D., Kasparick, M. and Stańczak, S., 2023. From Empirical Measurements to Augmented Data Rates: A Machine Learning Approach for MCS Adaptation in Sidelink Communication. Submitted to VTC2023-Fall.

## Usage

Data is saved as pandas dataframe and can be loaded using

```
df = pd.read_parquet('dataset_merged.parquet')
```

## Data columns

| Column | Unit | Notes |
| --- | --- | --- |
| new_time_epoch | s | from GPS |
| latitude_user1 | ° | from GPS |
| longitude_user1 | ° | from GPS |
| speed_user1 | km/h | from GPS |
| latitude_user2 | ° | from GPS |
| longitude_user2 | ° |from GPS |
| speed_user2 | km/h | from GPS |
| distance | m | from GPS |
| SNR | dB |from UE |
| RSRP | dBm |from UE |
| RSSI | dBm |from UE |
| NOISE POWER | dBm |from UE |
| RX_GAIN | dBm |from UE |
| Rx_Power | dBm |from UE |
| MCS |  |from UE |
| round |  | |




