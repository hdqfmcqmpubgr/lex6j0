# 6J0 Aviation Weather
*Experimental - Verify official sources*
Base time 11:00 EDT Sat Oct 31.
Generated 11:11 EDT. Winds kt, directions TRUE (magnetic = true + 7°). Sunset 18:33.

## Now
- **Wind (est.)** ENE 67° at **10 kt**, gust/peak est. **14 kt** — speed = mean of KCAE/KCUB/KAIK/KAGS obs (estimate); direction = KCAE/KCUB METAR distance-weighted vector average.
- **RC Winds Lexington County Airport (observed; converted from mph to kt):** NE 8.6 kt, peak 12.2 kt at 11:10 EDT. Last-hour mean 9.9, max peak 16.0; 3-h range 6.9–11.6.
- Feels-like next 6 h: no heat index/wind chill (wind chill only below 50 °F, heat index from 80 °F)
- Rwy 18: headwind -3, crosswind 10 L · Rwy 36: headwind 3, crosswind 10 R (sustained).
- Temp/dew **66/42 °F** (KCAE/KCUB obs; 6J0 sensor broken) · Altimeter 30.38 · **DA 640 ft** · KCAE sky SCT220 BKN250

## Next 6 h

| Time | Wind | Gust | Rwy 36 HW / XW | Temp/Dew °F | DA ft | Mix ft AGL | Sky % | Ceiling | Decay chk |
|---|---|---|---|---|---|---|---|---|---|
| 11:00 (obs/est) | 67° 10 | 14 | 3 / 10 R (g 13 R) | 66/42 | 640 | 1950 | 75 | 25,000 ft |  |
| 12:00 | 62° 12 | 19 | 4 / 11 R (g 18 R) | 69/49 | 840 | 2000 | 76 | 22,000 ft |  |
| 13:00 | 61° 12 | 19 | 4 / 11 R (g 18 R) | 70/48 | 900 | 2240 | 85 | 22,000 ft |  |
| 14:00 | 60° 11 | 18 | 4 / 10 R (g 17 R) | 71/48 | 960 | 2570 | 74 | 21,000 ft |  |
| 15:00 | 60° 11 | 18 | 4 / 10 R (g 17 R) | 72/48 | 1020 | 2780 | 73 | 21,000 ft |  |
| 16:00 | 61° 11 | 17 | 4 / 10 R (g 16 R) | 71/47 | 950 | 2970 | 74 | 22,000 ft | 11 |
| 17:00 | 61° 10 | 14 | 3 / 9 R (g 13 R) | 70/47 | 890 | 2770 | 79 | 21,000 ft | 10 |

**Outlook:** wind ENE–ENE 10–12 kt, peak gust ~19 kt around 13:00. Max 36 crosswind 11 kt sustained / 18 kt gust. DA up to 1020 ft.

## Winds aloft (ft MSL) — speed kt, true dir, temp °C; **bold** = flagged
| ft MSL | 11:00 | 12:00 | 13:00 | 14:00 | 15:00 | 16:00 | 17:00 |
|---|---|---|---|---|---|---|---|
| 12000 | 3 kt 315° +3°C | 2 kt 310° +3°C | 2 kt 299° +2°C | 2 kt 301° +2°C | 2 kt 309° +2°C | 2 kt 307° +2°C | 2 kt 315° +2°C |
| 10500 | 3 kt 016° +5°C | 2 kt 044° +5°C | 2 kt 100° +4°C | 1 kt 081° +4°C | 2 kt 089° +4°C | 2 kt 031° +4°C | 2 kt 037° +4°C |
| 9000 | 7 kt 086° +7°C | 7 kt 091° +7°C | 7 kt 098° +7°C | 7 kt 100° +7°C | 6 kt 104° +7°C | 6 kt 100° +7°C | 6 kt 094° +7°C |
| 7500 | 9 kt 090° +9°C | 9 kt 091° +9°C | 8 kt 096° +9°C | 8 kt 102° +9°C | 7 kt 109° +8°C | 7 kt 106° +8°C | 6 kt 105° +8°C |
| 6000 | 10 kt 095° +11°C | 9 kt 096° +11°C | 9 kt 100° +11°C | 9 kt 106° +10°C | 9 kt 113° +10°C | 9 kt 112° +10°C | 7 kt 113° +10°C |
| 4500 | 14 kt 093° +14°C | 13 kt 094° +14°C | 13 kt 094° +13°C | 13 kt 096° +13°C | 12 kt 099° +12°C | 12 kt 100° +12°C | 12 kt 095° +12°C |
| 3000 | 21 kt 087° +15°C | 19 kt 086° +15°C | 17 kt 084° +15°C | 16 kt 083° +15°C | 15 kt 086° +15°C | 15 kt 089° +15°C | 17 kt 083° +15°C |
| 1500 | 20 kt 067° +16°C | 18 kt 064° +17°C | 17 kt 060° +18°C | 16 kt 060° +18°C | 14 kt 064° +19°C | 13 kt 070° +19°C | 14 kt 069° +19°C |
| Surface 452' | 10 kt 067° G14 +19°C | 12 kt 062° G19 +21°C | 12 kt 061° G19 +21°C | 11 kt 060° G18 +22°C | 11 kt 060° G18 +22°C | 11 kt 061° G17 +22°C | 10 kt 061° G14 +21°C |
Flags: none (no ≥35 kt winds, no shear by the ≥20/≥35 kt or ≥60° rules, no inversion, no lapse/ISA anomaly).
Method: ncep_hrrr_conus pressure-level profile at 6J0 (Open-Meteo), u/v/T linearly interpolated in height (geopotential, MSL); at 3000–9000 ft and 12000 ft wind is a 50/50 vector average with CAE FB winds for the valid period (FB interpolated between 3000/6000/9000 ft; 10500 ft model only). Flags: arrow yellow ≥25 kt, red ≥35 kt; shear = vector difference ≥20 kt vs the level below, ≥35 kt vs the surface, or direction change ≥60° with both ≥10 kt; inversion = ≥2 °C warmer than the level/surface below; anomaly = layer lapse >3.5 °C/1000 ft between aloft levels or ≥20 °C from ISA.

## Method & sources
- Wind = ½ NWS gridpoint (6J0) + ½ mean of NBM/LAMP sustained wind at KCAE, KCUB, KAIK, KAGS. Gust = mean of NWS grid gust, the 4-station gust fit, and (17:00–21:00) 4.7+0.61·KCAE; ≥ wind+3. Decay column = sunset wind-decay model (sanity check only, ⚠ = differs >3 kt).
- Components (table and 6J0 Runway winds panel): true runway headings 171°/351° with true winds (≡ 178°/358° magnetic). XW R/L = wind from the right/left of the landing aircraft. DA uses forecast T/Td and current KCAE/KCUB altimeter 30.38 held constant (moist-air density: station pressure from the altimeter, Buck vapour pressure from Td; winds-aloft cells use the model level pressure and T/Td; surface cell = this DA).
- KCAE webcam (EarthCam live stream): ok (VM): 1920x1080, captured 11:11 EDT
- WPC Day 1 national forecast chart: ok; details from map.php
- GOES-19 GLM FED+GeoColor (STAR CDN): ok: 20263041451 2400x2400 crop (910, 318, 1772, 866)
- METAR (aviationweather.gov): ok: KAGS, KAIK, KCAE, KCUB
- KCAE METAR today (hi/lo so far): ok: 11 reports since midnight
- TAF KCAE/KAGS: ok
- KCAE NEXRAD L2 + GLM (radar_panel.py): KCAE KCAE20261031_150017_V06 0.5deg, GLM 46 files, 0 flashes, 12.1s
- TAF KCAE cloud layers (json): ok
- FB winds aloft (CAE): ok
- FB winds aloft CAE (06/12/24 products): ok: 06h use 14-21Z, 12h use 21-06Z, 24h use 06-18Z
- Open-Meteo pressure levels: ok: model ncep_hrrr_conus
- NWS gridpoint raw: ok: https://api.weather.gov/gridpoints/CAE/58,51 (updated 2026-10-31T06:21:11+00:00)
- GFS LAMP (NOMADS lavtxt): ok: 2026-10-31 1430Z cycle
- NBM NBH text (NOMADS): ok: 2026-10-31 14Z cycle
- RC Winds Lexington County Airport 5-min: ok: 36 rows, latest 11:10 EDT (speeds converted from mph to kt)
- AWC G-AIRMET Tango LLWS/TURB-LO: ok

```
TAF KAGS 311123Z 3112/0112 04006KT P6SM BKN200 
  FM311400 07010G18KT P6SM BKN200 
  FM312300 06004KT P6SM BKN200
TAF KCAE 311123Z 3112/0112 06010G18KT P6SM BKN200 
  FM312300 06004KT P6SM BKN200
```

Winds aloft (FB, CAE):
```
DATA BASED ON 311200Z    
VALID 311800Z   FOR USE 1400-2100Z. TEMPS NEG ABV 24000
FT  3000    6000    9000   12000
CAE 1018 1109+10 1007+07 9900+0
```
