# 6J0 Aviation Weather
*Experimental - Always verify official sources.*
Base time 09:00 EDT Sat Oct 24.
Generated 09:14 EDT. Winds kt, directions TRUE (magnetic = true + 7°). Sunset 18:40.

## Now
- **Wind (est.)** NNE 20° at **6 kt**, gust/peak est. **12 kt** — speed = mean of KCAE/KCUB/KAIK/KAGS obs (estimate); direction = KCAE METAR distance-weighted vector average.
- **RC Winds Lexington County Airport (observed; converted from mph to kt):** N 7.1 kt, peak 9.7 kt at 09:10 EDT. Last-hour mean 6.3, max peak 10.8; 3-h range 5.0–7.1.
- Feels-like next 6 h: no heat index/wind chill (wind chill only below 50 °F, heat index from 80 °F)
- Rwy 18: headwind -5, crosswind 3 L · Rwy 36: headwind 5, crosswind 3 R (sustained).
- Temp/dew **55/49 °F** (KCAE/KCUB obs; 6J0 sensor broken) · Altimeter 30.41 · **DA -100 ft** · KCAE sky FEW030

## Next 6 h

| Time | Wind | Gust | Rwy 36 HW / XW | Temp/Dew °F | DA ft | Mix ft AGL | Sky % | Ceiling | Decay chk |
|---|---|---|---|---|---|---|---|---|---|
| 09:00 (obs/est) | 20° 6 | 12 | 5 / 3 R (g 6 R) | 55/49 | -100 | 730 | 20 | none |  |
| 10:00 | 39° 11 | 17 | 7 / 8 R (g 13 R) | 57/51 | 40 | 1520 | 15 | none |  |
| 11:00 | 40° 12 | 18 | 8 / 9 R (g 14 R) | 61/51 | 300 | 2120 | 22 | none |  |
| 12:00 | 40° 13 | 19 | 8 / 10 R (g 15 R) | 65/51 | 560 | 2660 | 15 | none |  |
| 13:00 | 39° 12 | 20 | 8 / 9 R (g 15 R) | 67/50 | 690 | 3130 | 18 | none |  |
| 14:00 | 39° 12 | 20 | 8 / 9 R (g 15 R) | 69/49 | 810 | 3680 | 16 | none |  |
| 15:00 | 38° 12 | 20 | 8 / 9 R (g 14 R) | 69/49 | 810 | 3820 | 14 | none |  |

**Outlook:** wind NE–NE 11–13 kt, peak gust ~20 kt around 13:00. Max 36 crosswind 10 kt sustained / 15 kt gust. DA up to 810 ft.

## Winds aloft (ft MSL) — speed kt, true dir, temp °C; **bold** = flagged
| ft MSL | 09:00 | 10:00 | 11:00 | 12:00 | 13:00 | 14:00 | 15:00 |
|---|---|---|---|---|---|---|---|
| 12000 | 15 kt 039° +0°C | 14 kt 042° +0°C | 13 kt 047° +0°C | 12 kt 050° -0°C | 12 kt 048° -0°C | 12 kt 048° +0°C | 11 kt 048° +0°C |
| 10500 | 13 kt 045° +3°C | 12 kt 054° +3°C | 12 kt 054° +3°C | 11 kt 059° +2°C | 10 kt 057° +2°C | 10 kt 057° +2°C | 9 kt 056° +3°C |
| 9000 | 11 kt 060° +5°C | 11 kt 064° +4°C | 10 kt 059° +4°C | 10 kt 061° +4°C | 9 kt 060° +4°C | 9 kt 058° +4°C | 9 kt 059° +4°C |
| 7500 | 12 kt 066° +6°C | 12 kt 072° +6°C | 11 kt 071° +6°C | 11 kt 072° +6°C | 10 kt 073° +6°C | 9 kt 071° +6°C | 9 kt 071° +6°C |
| 6000 | 13 kt 067° +8°C | 13 kt 074° +8°C | 13 kt 076° +8°C | 12 kt 076° +8°C | 11 kt 077° +8°C | 10 kt 075° +8°C | 10 kt 072° +8°C |
| 4500 | 20 kt 064° +9°C | 19 kt 068° +9°C | 16 kt 063° +10°C | 15 kt 060° +10°C | 14 kt 058° +10°C | 13 kt 055° +10°C | 13 kt 052° +10°C |
| 3000 | 26 kt 063° +11°C | 26 kt 064° +11°C | 20 kt 052° +11°C | 19 kt 046° +11°C | 17 kt 043° +11°C | 17 kt 043° +12°C | 16 kt 042° +12°C |
| 1500 | 24 kt 057° +11°C | 20 kt 056° +11°C | 18 kt 048° +12°C | 19 kt 044° +13°C | 17 kt 043° +14°C | 16 kt 045° +16°C | 16 kt 044° +16°C |
| Surface 452' | 6 kt 020° G12 +13°C | 11 kt 039° G17 +14°C | 12 kt 040° G18 +16°C | 13 kt 040° G19 +18°C | 12 kt 039° G20 +19°C | 12 kt 039° G20 +21°C | 12 kt 038° G20 +21°C |
Flags: none (no ≥35 kt winds, no shear by the ≥20/≥35 kt or ≥60° rules, no inversion, no lapse/ISA anomaly).
Method: ncep_hrrr_conus pressure-level profile at 6J0 (Open-Meteo), u/v/T linearly interpolated in height (geopotential, MSL); at 3000–9000 ft and 12000 ft wind is a 50/50 vector average with CAE FB winds for the valid period (FB interpolated between 3000/6000/9000 ft; 10500 ft model only). Flags: arrow yellow ≥25 kt, red ≥35 kt; shear = vector difference ≥20 kt vs the level below, ≥35 kt vs the surface, or direction change ≥60° with both ≥10 kt; inversion = ≥2 °C warmer than the level/surface below; anomaly = layer lapse >3.5 °C/1000 ft between aloft levels or ≥20 °C from ISA.

## Method & sources
- Wind = ½ NWS gridpoint (6J0) + ½ mean of NBM/LAMP sustained wind at KCAE, KCUB, KAIK, KAGS. Gust = mean of NWS grid gust, the 4-station gust fit, and (17:00–21:00) 4.7+0.61·KCAE; ≥ wind+3. Decay column = sunset wind-decay model (sanity check only, ⚠ = differs >3 kt).
- Components (table and 6J0 Runway winds panel): true runway headings 171°/351° with true winds (≡ 178°/358° magnetic). XW R/L = wind from the right/left of the landing aircraft. DA uses forecast T/Td and current KCAE/KCUB altimeter 30.41 held constant (moist-air density: station pressure from the altimeter, Buck vapour pressure from Td; winds-aloft cells use the model level pressure and T/Td; surface cell = this DA).
- WPC Day 1 national forecast chart: ok; details from map.php
- GOES-19 GLM FED+GeoColor (STAR CDN): ok: 20262971251 2400x2400 crop (910, 318, 1772, 866)
- KCAE webcam (EarthCam live stream): ok: 1920x1080, captured 09:14 EDT
- METAR (aviationweather.gov): ok: KAGS, KAIK, KCAE, KCUB
- KCAE NEXRAD L2 + GLM (radar_panel.py): KCAE KCAE20261024_130426_V06 0.5deg, GLM 46 files, 0 flashes, 12.5s
- KCAE METAR today (hi/lo so far): FAILED: 504 Server Error: Gateway Time-out for url: https://aviationweather.gov/api/data/metar?ids=KCAE&format=json&hours=24
- TAF KCAE/KAGS: ok
- TAF KCAE cloud layers (json): ok
- FB winds aloft (CAE): ok
- FB winds aloft CAE (06/12/24 products): ok: 06h use 08-15Z, 12h use 15-00Z, 24h use 00-12Z
- Open-Meteo pressure levels: ok: model ncep_hrrr_conus
- NWS gridpoint raw: ok: https://api.weather.gov/gridpoints/CAE/58,51 (updated 2026-10-24T06:21:12+00:00)
- GFS LAMP (NOMADS lavtxt): ok: 2026-10-24 1230Z cycle
- NBM NBH text (NOMADS): ok: 2026-10-24 12Z cycle
- RC Winds Lexington County Airport 5-min: ok: 36 rows, latest 09:10 EDT (speeds converted from mph to kt)

```
TAF KAGS 241224Z 2412/2512 02004KT P6SM SKC 
  FM241500 05012G21KT P6SM SKC 
  FM242200 02007KT P6SM SKC
TAF KCAE 241224Z 2412/2512 03004KT P6SM SKC 
  FM241400 04012G20KT P6SM FEW250 
  FM242100 04008KT P6SM SKC
```

Winds aloft (FB, CAE):
```
DATA BASED ON 240600Z    
VALID 241200Z   FOR USE 0800-1500Z. TEMPS NEG ABV 24000
FT  3000    6000    9000   12000
CAE 0626 0709+08 0610+04 0414+0
```
