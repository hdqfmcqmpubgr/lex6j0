# 6J0 Aviation Weather
*Experimental - Verify official sources*
Base time 12:00 EST Sat Nov 7.
Generated 12:16 EST. Winds kt, directions TRUE (magnetic = true + 7°). Sunset 17:26.

## Now
- **Wind (est.)** E 80° at **6 kt**, gust/peak est. **10 kt** — speed = mean of KCAE/KCUB/KAIK/KAGS obs (estimate); direction = KCAE METAR distance-weighted vector average.
- **RC Winds Lexington County Airport (observed; converted from mph to kt):** NE 7.6 kt, peak 10.8 kt at 12:00 EST. Last-hour mean 7.8, max peak 14.3; 3-h range 6.0–10.6.
- Feels-like next 6 h: no heat index/wind chill (wind chill only below 50 °F, heat index from 80 °F)
- Rwy 18: headwind -0, crosswind 6 L · Rwy 36: headwind 0, crosswind 6 R (sustained).
- Temp/dew **66/48 °F** (KCAE/KCUB obs; 6J0 sensor broken) · Altimeter 30.02 · **DA 1040 ft** · KCAE sky BKN044 BKN250

## Next 6 h

| Time | Wind | Gust | Rwy 36 HW / XW | Temp/Dew °F | DA ft | Mix ft AGL | Sky % | Ceiling | Decay chk |
|---|---|---|---|---|---|---|---|---|---|
| 12:00 (obs/est) | 80° 6 | 10 | 0 / 6 R (g 10 R) | 66/48 | 1040 | 2730 | 12 | 4,400 ft |  |
| 13:00 | 36° 6 | 10 | 4 / 4 R (g 7 R) | 68/50 | 1190 | 3400 | 35 | none |  |
| 14:00 | 26° 6 | 9 | 5 / 3 R (g 5 R) | 70/50 | 1310 | 3670 | 30 | 13,000 ft |  |
| 15:00 | 16° 5 | 8 | 4 / 2 R (g 4 R) | 69/50 | 1250 | 3830 | 33 | 13,000 ft |  |
| 16:00 | 10° 5 | 8 | 4 / 2 R (g 3 R) | 69/50 | 1250 | 3750 | 47 | none | 5 |
| 17:00 | 27° 3 | 6 | 2 / 2 R (g 4 R) | 68/50 | 1190 | 1370 | 44 | 13,000 ft | 3 |
| 18:00 | 34° 2 | 6 | 2 / 2 R (g 4 R) | 63/50 | 860 | 830 | 42 | 13,000 ft | 2 |

**Outlook:** wind NE–NE 2–6 kt, peak gust ~10 kt around 13:00. Max 36 crosswind 4 kt sustained / 7 kt gust. DA up to 1310 ft.

## Winds aloft (ft MSL) — speed kt, true dir, temp °C; **bold** = flagged
| ft MSL | 12:00 | 13:00 | 14:00 | 15:00 | 16:00 | 17:00 | 18:00 |
|---|---|---|---|---|---|---|---|
| 12000 | 19 kt 308° +1°C | 19 kt 309° +2°C | 20 kt 312° +2°C | 18 kt 310° +2°C | 18 kt 307° +2°C | 17 kt 300° +2°C | 17 kt 295° +2°C |
| 10500 | 18 kt 308° +5°C | 18 kt 306° +5°C | 18 kt 310° +5°C | 17 kt 307° +5°C | 17 kt 302° +5°C | 17 kt 296° +5°C | 17 kt 293° +4°C |
| 9000 | 17 kt 305° +7°C | 17 kt 300° +7°C | 17 kt 302° +7°C | 17 kt 300° +7°C | 17 kt 297° +7°C | 17 kt 294° +7°C | 17 kt 294° +7°C |
| 7500 | 13 kt 301° +9°C | 13 kt 295° +8°C | 14 kt 297° +9°C | 15 kt 296° +9°C | 15 kt 295° +9°C | 15 kt 296° +9°C | 15 kt 298° +9°C |
| 6000 | 7 kt 292° +9°C | 7 kt 287° +9°C | 9 kt 291° +10°C | 10 kt 293° +10°C | 11 kt 295° +10°C | 11 kt 302° +10°C | 11 kt 307° +10°C |
| 4500 | 1 kt 011° +10°C | 1 kt 297° +10°C | 3 kt 292° +10°C | 5 kt 308° +10°C | 6 kt 312° +10°C | 7 kt 322° +11°C | 8 kt 327° +10°C |
| 3000 | 11 kt 059° +11°C | 8 kt 052° +12°C | 6 kt 036° +12°C | 6 kt 016° +12°C | 6 kt 007° +12°C | 7 kt 008° +13°C | 8 kt 009° +12°C |
| 1500 | 14 kt 053° +14°C | 10 kt 047° +15°C | 8 kt 038° +16°C | 7 kt 025° +16°C | 7 kt 021° +17°C | 7 kt 030° +17°C | 8 kt 035° +17°C |
| Surface 452' | 6 kt 080° G10 +19°C | 6 kt 036° G10 +20°C | 6 kt 026° G9 +21°C | 5 kt 016° G8 +21°C | 5 kt 010° G8 +21°C | 3 kt 027° G6 +20°C | 2 kt 034° G6 +17°C |
Flags: none (no ≥35 kt winds, no shear by the ≥20/≥35 kt or ≥60° rules, no inversion, no lapse/ISA anomaly).
Method: ncep_hrrr_conus pressure-level profile at 6J0 (Open-Meteo), u/v/T linearly interpolated in height (geopotential, MSL); at 3000–9000 ft and 12000 ft wind is a 50/50 vector average with CAE FB winds for the valid period (FB interpolated between 3000/6000/9000 ft; 10500 ft model only). Flags: arrow yellow ≥25 kt, red ≥35 kt; shear = vector difference ≥20 kt vs the level below, ≥35 kt vs the surface, or direction change ≥60° with both ≥10 kt; inversion = ≥2 °C warmer than the level/surface below; anomaly = layer lapse >3.5 °C/1000 ft between aloft levels or ≥20 °C from ISA.

## Method & sources
- Wind = ½ NWS gridpoint (6J0) + ½ mean of NBM/LAMP sustained wind at KCAE, KCUB, KAIK, KAGS. Gust = mean of NWS grid gust, the 4-station gust fit, and (17:00–21:00) 4.7+0.61·KCAE; ≥ wind+3. Decay column = sunset wind-decay model (sanity check only, ⚠ = differs >3 kt).
- Components (table and 6J0 Runway winds panel): true runway headings 171°/351° with true winds (≡ 178°/358° magnetic). XW R/L = wind from the right/left of the landing aircraft. DA uses forecast T/Td and current KCAE/KCUB altimeter 30.02 held constant (moist-air density: station pressure from the altimeter, Buck vapour pressure from Td; winds-aloft cells use the model level pressure and T/Td; surface cell = this DA).
- KCAE webcam (EarthCam live stream): ok (VM): 1920x1080, captured 12:09 EST
- WPC Day 1 national forecast chart: ok; details from map.php
- GOES-19 GLM FED+GeoColor (STAR CDN): ok: 20263111651 2400x2400 crop (910, 318, 1772, 866)
- METAR (aviationweather.gov): ok: KAGS, KAIK, KCAE, KCUB
- KCAE METAR today (hi/lo so far): ok: 15 reports since midnight
- TAF KCAE/KAGS: ok
- KCAE NEXRAD L2 + GLM (radar_panel.py): KCAE KCAE20261107_170431_V06 0.5deg, GLM 46 files, 0 flashes, 7.0s
- TAF KCAE cloud layers (json): ok
- FB winds aloft (CAE): FAILED: 400 Client Error: Bad Request for url: https://aviationweather.gov/api/data/windtemp?region=all&level=low&fcst=06
- FB winds aloft CAE (06/12/24 products): FAILED: none parsed
- Open-Meteo pressure levels: ok: model ncep_hrrr_conus
- NWS gridpoint raw: ok: https://api.weather.gov/gridpoints/CAE/58,51 (updated 2026-11-07T11:16:08+00:00)
- GFS LAMP (NOMADS lavtxt): ok: 2026-11-07 1630Z cycle
- NBM NBH text (NOMADS): ok: 2026-11-07 16Z cycle
- RC Winds Lexington County Airport 5-min: ok: 33 rows, latest 12:00 EST (speeds converted from mph to kt)
- AWC G-AIRMET Tango LLWS/TURB-LO: ok
- WeatherNext 3 PoP (6J0, derived from 1 h precip percentiles): ok: 8 hour bins from 6J0_wn_20261107_00Z_full.csv

```
TAF KAGS 071126Z 0712/0812 32005KT P6SM BKN035 
  TEMPO 0712/0714 5SM BR SCT008 BKN012 
  FM071500 04006KT P6SM SCT250 
  FM072200 36003KT P6SM FEW250
TAF KCAE 071126Z 0712/0812 30004KT P6SM BKN035 
  TEMPO 0712/0713 5SM BR BKN012 
  FM071500 03007KT P6SM SCT250 
  FM072200 36003KT P6SM FEW250
```
