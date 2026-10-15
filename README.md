# cr-racing-speedcam-data

Published speed-camera database for the **CR-Racing** app — the over-the-air
(OTA) source so camera data updates without an app release.

- `cameras.bin` — the packed `SCD1` v0.1 database of fixed speed cameras
  (固定式測速相機). The app fetches and caches this file over HTTP.

**Data only — no application source.** The binary is rebuilt by the CR-Racing
build pipeline from **[data.gov.tw dataset 7320](https://data.gov.tw/dataset/7320)**
(內政部警政署「測速執法設置點」, open data) and published here automatically.

Raw URL the app fetches:

```
https://raw.githubusercontent.com/Brad-Cat/cr-racing-speedcam-data/main/cameras.bin
```
