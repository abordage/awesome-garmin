# Awesome Garmin

![Awesome](https://raw.githubusercontent.com/abordage/schemas/main/badges/awesome.svg)
[![Last update](https://img.shields.io/github/last-commit/abordage/awesome-garmin?label=last%20update)](README.md)
![Repositories](https://img.shields.io/badge/repositories-117-06b6d4)
![Total Stars](https://img.shields.io/badge/total%20stars-33,078-gold)
[![License](https://img.shields.io/github/license/abordage/awesome-garmin)](LICENSE)

**Automated. Curated. Ranked.**

Connect IQ apps, Garmin Connect API, FIT tools, maps, and integrations. This awesome list is automatically maintained with daily GitHub API updates. Projects are re-ranked daily based on current activity metrics.

**Daily process:** Merge community PRs -> Scan repos -> Filter stale projects -> Recalculate scores -> Rebuild list

- [API Clients](#api-clients)
- [Companion & Mobile SDK](#companion--mobile-sdk)
- [Connect IQ](#connect-iq)
  - [Data Fields](#data-fields)
  - [Games](#games)
  - [Smart Home](#smart-home)
  - [Sports & Workouts](#sports--workouts)
  - [Utilities](#utilities)
  - [Watch Faces](#watch-faces)
  - [Widgets](#widgets)
- [Data](#data)
  - [Export & Backup](#export--backup)
  - [FIT](#fit)
  - [Maps](#maps)
  - [Visualization](#visualization)
- [Developer Tools](#developer-tools)
  - [Editors & LSP](#editors--lsp)
  - [SDK & Tooling](#sdk--tooling)
- [Integrations](#integrations)
  - [Scales](#scales)
  - [Smart Home](#smart-home)
  - [Sync](#sync)
- [MCP Servers](#mcp-servers)


## API Clients

- [cyberjunky/python-garminconnect](https://github.com/cyberjunky/python-garminconnect) — Python 3 wrapper to read and write Garmin Connect ☆`3,292`
- [mkuthan/garmin-workouts](https://github.com/mkuthan/garmin-workouts) — Command line tool for managing Garmin workouts. ☆`128`
- [sealbro/dotnet.garmin.connect](https://github.com/sealbro/dotnet.garmin.connect) — Unofficial garmin connect client ☆`46`
- [lswiderski/yet-another-garmin-connect-client](https://github.com/lswiderski/yet-another-garmin-connect-client) — YAGCC: Yet Another Garmin Connect Client ☆`44`
- [bes-dev/garmy](https://github.com/bes-dev/garmy) — Python library to interact with Garmin Connect API ☆`66`
- [bpauli/gccli](https://github.com/bpauli/gccli) — CLI for Connect activities, health, workouts, and devices ☆`33`
## Companion & Mobile SDK

- [TDF-PL/TAKWatch](https://github.com/TDF-PL/TAKWatch) — TAKWatch is an ATAK plugin that communicates with Garmin devices ☆`113`
- [garmin/connectiq-companion-app-sdk-ios](https://github.com/garmin/connectiq-companion-app-sdk-ios) — iOS SDK for companion apps talking to Monkey C ☆`81`
- [garmin/connectiq-android-sdk](https://github.com/garmin/connectiq-android-sdk) — Connect IQ Mobile SDK for Android ☆`80`
- [urbandroid-team/Sleep-as-Android-Garmin-Addon](https://github.com/urbandroid-team/Sleep-as-Android-Garmin-Addon) — Android and Garmin Sleep as Android addon ☆`60`
- [gimportexportdevs/gimporter](https://github.com/gimportexportdevs/gimporter) — Garmin Connect App to import GPX and FIT files ☆`32`
- [gimportexportdevs/gexporter](https://github.com/gimportexportdevs/gexporter) — Android App to export GPX and FIT to garmin devices ☆`31`
- [pauljohnston2025/breadcrumb-mobile](https://github.com/pauljohnston2025/breadcrumb-mobile) — Garmin companion app for breadcrumb ☆`21`
- [garmin/connectiq-companion-app-example-ios](https://github.com/garmin/connectiq-companion-app-example-ios) — Example iOS app using the Companion App SDK ☆`34`
- [grigorye/Handsfree](https://github.com/grigorye/Handsfree) — Make your phone calls from Garmin watch ☆`16`
- [MatyasKriz/ios-connect-iq-comms](https://github.com/MatyasKriz/ios-connect-iq-comms) — Two-way iOS companion and Connect IQ sample ☆`17`
## Connect IQ

### Data Fields

- [maca88/SmartBikeLights](https://github.com/maca88/SmartBikeLights) — Garmin application for ANT+ bike lights ☆`173`
- [gcormier9/GRun](https://github.com/gcormier9/GRun) — Configurable Garmin Watch datafield ☆`123`
- [wwarby/walker](https://github.com/wwarby/walker) — Free walking data field with stats for Garmin watches ☆`70`
- [pauljohnston2025/breadcrumb-garmin](https://github.com/pauljohnston2025/breadcrumb-garmin) — Garmin watch datafield that shows breadcrumb trail ☆`26`
- [maca88/E-Bike-Edge-MultiField](https://github.com/maca88/E-Bike-Edge-MultiField) — ANT+ LEV e-bike fields on Garmin Edge ☆`18`
- [ActiveLook/Garmin-Datafield-sample-code](https://github.com/ActiveLook/Garmin-Datafield-sample-code) — ActiveLook Garmin Datafield ☆`16`
### Games

- [Gualor/garmin-gotchi](https://github.com/Gualor/garmin-gotchi) — Tamagotchi Gen 1 Emulator for Garmin Instinct 3. ☆`18`
### Smart Home

- [house-of-abbey/GarminHomeAssistant](https://github.com/house-of-abbey/GarminHomeAssistant) — Home Assistant dashboard on a Garmin watch ☆`382`
### Sports & Workouts

- [kartoone/mybiketraffic](https://github.com/kartoone/mybiketraffic) — Varia radar vehicle counting on Connect IQ ☆`66`
- [ydutertre/myvario](https://github.com/ydutertre/myvario) — Fork of GliderSK targeted towards paraglider pilots ☆`38`
- [dmrrlc/connectiq-sailing](https://github.com/dmrrlc/connectiq-sailing) — Sailing app with knots, heading, and race countdown ☆`37`
- [chanezgr/IQwprimebal](https://github.com/chanezgr/IQwprimebal) — Garmin Connect IQ Wprime Bal application ☆`22`
- [matco/badminton](https://github.com/matco/badminton) — Badminton application for Garmin watches ☆`37`
- [andan67/wormnav](https://github.com/andan67/wormnav) — Track navigation for Garmin watches ☆`17`
- [OpenSeizureDetector/Garmin_SD](https://github.com/OpenSeizureDetector/Garmin_SD) — Seizure detector data source for Garmin IQ watches ☆`16`
- [aiMonster/Garmin-Contrast-Shower](https://github.com/aiMonster/Garmin-Contrast-Shower) — Contrast shower timer app for Garmin watches ☆`20`
### Utilities

- [klimeryk/garmodoro](https://github.com/klimeryk/garmodoro) — Pomodoro for Garmin devices using Connect IQ ☆`111`
- [ch1bo/garmin-otp-authenticator](https://github.com/ch1bo/garmin-otp-authenticator) — HOTP, TOTP, and Steam Guard widget for Connect IQ ☆`120`
- [TDF-PL/TAKWatch-IQ](https://github.com/TDF-PL/TAKWatch-IQ) — ATAK integration for Garmin Connect IQ devices ☆`60`
- [BleachDev/Rainy](https://github.com/BleachDev/Rainy) — My Garmin weather app. ☆`33`
### Watch Faces

- [warmsound/crystal-face](https://github.com/warmsound/crystal-face) — Garmin Connect IQ watch face ☆`470`
- [ludw/Segment34mkII](https://github.com/ludw/Segment34mkII) — 34-segment watch face with moon, weather, and health ☆`228`
- [blotspot/garmin-watchface-protomolecule](https://github.com/blotspot/garmin-watchface-protomolecule) — A Watchface for Garmin Smartwatches ☆`91`
- [Laverlin/Yet-Another-WatchFace](https://github.com/Laverlin/Yet-Another-WatchFace) — Watch Face application for Garmin smartwatch ☆`69`
- [myneur/late](https://github.com/myneur/late) — Garmin Smart Watch with Calendar & Weather ☆`67`
- [fevieira27/MoveToBeActive](https://github.com/fevieira27/MoveToBeActive) — Vivomove-style face with health, weather, and comms ☆`46`
- [samuelmr/garmin-abouttime](https://github.com/samuelmr/garmin-abouttime) — A watch face for Garmin Connect IQ devices ☆`38`
- [ludw/Segment34](https://github.com/ludw/Segment34) — Watchface for Garmin Fenix 6 with a 34 Segment display ☆`61`
- [ahuggel/SwissRailwayClock](https://github.com/ahuggel/SwissRailwayClock) — Analog Swiss railway clock watch face ☆`34`
- [causeri3/fine-o-clock](https://github.com/causeri3/fine-o-clock) — Garmin Watch Face ☆`46`
- [sunpazed/garmin-nyan-cat](https://github.com/sunpazed/garmin-nyan-cat) — An animated Nyan Cat watchface for Garmin's wearable lineup. ☆`23`
- [victorpaul/garmin-watchFace](https://github.com/victorpaul/garmin-watchFace) — Watch face with stats plus phone battery ☆`35`
- [dennybiasiolli/garmin-connect-iq](https://github.com/dennybiasiolli/garmin-connect-iq) — Home for Garmin Connect IQ Projects ☆`23`
- [SylvainGa/crystal-face](https://github.com/SylvainGa/crystal-face) — Garmin Connect IQ watch face ☆`20`
### Widgets

- [hatl/hasscontrol](https://github.com/hatl/hasscontrol) — Simple garmin widget to control home assistant scenes ☆`270`
- [macherel/Barcode-Wallet](https://github.com/macherel/Barcode-Wallet) — Store and show barcodes and QR codes on the watch ☆`76`
- [haraldh/SunCalc](https://github.com/haraldh/SunCalc) — Connect IQ widget for sunrise, sunset, dawn, dusk and blue hour ☆`40`
- [uaraven/otpauth-ciq](https://github.com/uaraven/otpauth-ciq) — ConnectIQ widget for generating TOTP authentication codes. ☆`20`
- [individual-it/BatteryGuesstimate](https://github.com/individual-it/BatteryGuesstimate) — Battery estimation for Garmin sportwatches ☆`16`
- [maca88/BikeLightsControl](https://github.com/maca88/BikeLightsControl) — Garmin widget for controlling ANT+ lights ☆`22`
- [starryalley/Unquestionify](https://github.com/starryalley/Unquestionify) — Phone notifications as bitmaps on a Connect IQ widget ☆`18`
- [SylvainGa/Tesla-Link](https://github.com/SylvainGa/Tesla-Link) — ConnectIQ widget for Tesla vehicle control ☆`17`
## Data

### Export & Backup

- [tcgoetz/GarminDB](https://github.com/tcgoetz/GarminDB) — Parse Connect, FIT, Fitbit, and MS Health into SQLite ☆`3,368`
- [pe-st/garmin-connect-export](https://github.com/pe-st/garmin-connect-export) — Download Garmin Connect stats and GPX tracks ☆`498`
- [diegoscarabelli/garmin-health-data](https://github.com/diegoscarabelli/garmin-health-data) — CLI to download Connect data into local SQLite ☆`136`
### FIT

- [dtcooper/python-fitparse](https://github.com/dtcooper/python-fitparse) — Python library to parse ANT/Garmin .FIT files ☆`826`
- [polyvertex/fitdecode](https://github.com/polyvertex/fitdecode) — A FIT file parsing and decoding library written in Python3 ☆`222`
- [muktihari/fit](https://github.com/muktihari/fit) — Go FIT SDK for protocol v2 encode and decode ☆`183`
- [garmin/fit-python-sdk](https://github.com/garmin/fit-python-sdk) — Official Garmin FIT Python SDK ☆`171`
- [jat255/Fit-File-Faker](https://github.com/jat255/Fit-File-Faker) — Edit and upload virtual-cycling FIT files to Connect ☆`100`
- [garmin/fit-javascript-sdk](https://github.com/garmin/fit-javascript-sdk) — Official Garmin FIT JavaScript SDK ☆`81`
- [stadelmanma/fitparse-rs](https://github.com/stadelmanma/fitparse-rs) — Rust library to parse FIT formatted files ☆`74`
- [Nick2bad4u/FitFileViewer](https://github.com/Nick2bad4u/FitFileViewer) — Cross-platform FIT file analyzer for Windows, Mac, Linux ☆`71`
- [jpickup/GarminTools](https://github.com/jpickup/GarminTools) — Create FIT workouts, schedules, and courses ☆`67`
- [garmin/fit-sdk-tools](https://github.com/garmin/fit-sdk-tools) — Official Garmin FIT SDK Tools ☆`61`
- [openivity/openivity.github.io](https://github.com/openivity/openivity.github.io) — Client-side FIT/GPX/TCX viz, edit, convert, and merge ☆`44`
- [garmin/fit-java-sdk](https://github.com/garmin/fit-java-sdk) — Official Garmin FIT Java SDK ☆`38`
- [garmin/fit-objective-c-sdk](https://github.com/garmin/fit-objective-c-sdk) — Official Garmin FIT Objective-C SDK ☆`35`
- [garmin/fit-swift-sdk](https://github.com/garmin/fit-swift-sdk) — Official Garmin FIT Swift SDK ☆`26`
- [garmin/fit-csharp-sdk](https://github.com/garmin/fit-csharp-sdk) — Official C# SDK to encode and decode FIT files ☆`28`
- [muktihari/rustyfit](https://github.com/muktihari/rustyfit) — no_std Rust library that reads and writes Garmin FIT files ☆`17`
- [MaksVasilev/fit2gpx](https://github.com/MaksVasilev/fit2gpx) — Convert FIT to GPX, CSV, HR, HRV, SpO2, and SQLite ☆`39`
### Maps

- [ligfietser/mkgmap-style-sheets](https://github.com/ligfietser/mkgmap-style-sheets) — mkgmap style sheets for OSM Garmin vector maps ☆`53`
### Visualization

- [yihong0618/running_page](https://github.com/yihong0618/running_page) — Make your own running home page ☆`4,577`
- [arpanghosh8453/garmin-grafana](https://github.com/arpanghosh8453/garmin-grafana) — Fetch Connect health data into InfluxDB and Grafana ☆`3,566`
- [tumic0/GPXSee](https://github.com/tumic0/GPXSee) — GPS log viewer and analyzer for GPX, TCX, KML, and FIT ☆`1,269`
- [alex-hhh/ActivityLog2](https://github.com/alex-hhh/ActivityLog2) — Analyze data from swim, bike and run activities ☆`369`
- [peregin/gps-overlay-on-video](https://github.com/peregin/gps-overlay-on-video) — Telemetry (GPS) data overlay on videos ☆`363`
- [aspain/git-sweaty](https://github.com/aspain/git-sweaty) — Strava and Garmin activities as GitHub-style graphs ☆`272`
- [arpanghosh8453/fit-dashboard](https://github.com/arpanghosh8453/fit-dashboard) — Offline desktop dashboard for Garmin FIT files ☆`245`
- [jimmykane/quantified-self](https://github.com/jimmykane/quantified-self) — Central app for Garmin, Suunto, and Coros data ☆`239`
- [Aebel-Shajan/year-in-data](https://github.com/Aebel-Shajan/year-in-data) — Annual activity heatmaps from Garmin and other data ☆`107`
- [RafaTatay/garming-stats](https://github.com/RafaTatay/garming-stats) — Self-hosted activity stats as a Strava Premium stand-in ☆`83`
## Developer Tools

### Editors & LSP

- [markw65/prettier-extension-monkeyc](https://github.com/markw65/prettier-extension-monkeyc) — A VSCode extension for Garmin MonkeyC ☆`19`
- [markw65/prettier-plugin-monkeyc](https://github.com/markw65/prettier-plugin-monkeyc) — A prettier plugin for Garmin monkey-c ☆`18`
### SDK & Tooling

- [garmin/connectiq-apps](https://github.com/garmin/connectiq-apps) — A collection of Connect IQ apps. ☆`598`
- [Likenttt/garmin-connectiq-samples-brief-explanations](https://github.com/Likenttt/garmin-connectiq-samples-brief-explanations) — Connect IQ samples and FAQ notes ☆`144`
- [pcolby/connectiq-sdk-manager](https://github.com/pcolby/connectiq-sdk-manager) — Garmin's Connect IQ SDK Manager as an AppImage ☆`49`
- [flocsy/garmin-dev-tools](https://github.com/flocsy/garmin-dev-tools) — Tools for Garmin CIQ developers ☆`24`
- [markw65/monkeyc-optimizer](https://github.com/markw65/monkeyc-optimizer) — Utilities for optimizing monkeyc projects ☆`19`
## Integrations

### Scales

- [jaroslawhartman/withings-sync](https://github.com/jaroslawhartman/withings-sync) — Synchronisation of Withings weight ☆`704`
- [RobertWojtowicz/export2garmin](https://github.com/RobertWojtowicz/export2garmin) — Export Mi | Xiaomi scale & Omron data to Garmin Connect ☆`276`
- [lswiderski/mi-scale-exporter](https://github.com/lswiderski/mi-scale-exporter) — Export Mi Scale body composition to Garmin Connect ☆`244`
- [KristianP26/ble-scale-sync](https://github.com/KristianP26/ble-scale-sync) — BLE scale bridge to Connect, Strava, MQTT, and files ☆`232`
- [AlexxIT/SmartScaleConnect](https://github.com/AlexxIT/SmartScaleConnect) — Sync smart scale data between ecosystems ☆`171`
- [sodelalbert/Withings2Garmin](https://github.com/sodelalbert/Withings2Garmin) — Sync Withings scale weight to Garmin Connect ☆`116`
### Smart Home

- [cyberjunky/home-assistant-garmin_connect](https://github.com/cyberjunky/home-assistant-garmin_connect) — Garmin Connect data in Home Assistant ☆`592`
### Sync

- [endurain-project/endurain](https://github.com/endurain-project/endurain) — Self-hosted fitness tracker with full data control ☆`2,419`
- [philosowaffle/peloton-to-garmin](https://github.com/philosowaffle/peloton-to-garmin) — Convert Peloton workouts to FIT and upload ☆`360`
- [drkostas/hevy2garmin](https://github.com/drkostas/hevy2garmin) — Sync Hevy workouts, sets, and HR to Garmin Connect ☆`191`
- [mgifos/quick-plan](https://github.com/mgifos/quick-plan) — Defines and schedules Garmin workouts ☆`157`
- [simonepri/fitbit2garmin](https://github.com/simonepri/fitbit2garmin) — Export Fitbit body, activity, and GPS for Connect ☆`112`
- [alex-hhh/PiFitSync](https://github.com/alex-hhh/PiFitSync) — Sync FIT files from Garmin watch to a Raspberry PI ☆`16`
- [fulippo/share-your-garmin-workout](https://github.com/fulippo/share-your-garmin-workout) — Chrome extension to share Garmin Connect workouts ☆`27`
## MCP Servers

- [Taxuspt/garmin_mcp](https://github.com/Taxuspt/garmin_mcp) — MCP server to access Garmin data ☆`1,559`
- [Nicolasvegam/garmin-connect-mcp](https://github.com/Nicolasvegam/garmin-connect-mcp) — MCP with 61 Garmin Connect health and fitness tools ☆`193`
- [nrvim/garmin-givemydata](https://github.com/nrvim/garmin-givemydata) — Local SQLite archive of Connect data with MCP ☆`173`
- [eddmann/garmin-connect-mcp](https://github.com/eddmann/garmin-connect-mcp) — MCP for Connect activities, health, sleep, and training ☆`70`
- [matin/garth-mcp-server](https://github.com/matin/garth-mcp-server) — Garmin Connect MCP server based on Garth ☆`65`
- [etweisberg/garmin-connect-mcp](https://github.com/etweisberg/garmin-connect-mcp) — Garmin Connect MCP ☆`47`
- [Wewoc/Garmin_Local_Archive](https://github.com/Wewoc/Garmin_Local_Archive) — Local-first Windows archive of Connect health data ☆`28`


---

## 🏆 Top 50 by Stars

> The most starred projects in this list, sorted by GitHub stars.

1. [yihong0618/running_page](https://github.com/yihong0618/running_page) — Make your own running home page ☆`4,577`
1. [arpanghosh8453/garmin-grafana](https://github.com/arpanghosh8453/garmin-grafana) — Fetch Connect health data into InfluxDB and Grafana ☆`3,566`
1. [tcgoetz/GarminDB](https://github.com/tcgoetz/GarminDB) — Parse Connect, FIT, Fitbit, and MS Health into SQLite ☆`3,368`
1. [cyberjunky/python-garminconnect](https://github.com/cyberjunky/python-garminconnect) — Python 3 wrapper to read and write Garmin Connect ☆`3,292`
1. [endurain-project/endurain](https://github.com/endurain-project/endurain) — Self-hosted fitness tracker with full data control ☆`2,419`
1. [Taxuspt/garmin_mcp](https://github.com/Taxuspt/garmin_mcp) — MCP server to access Garmin data ☆`1,559`
1. [tumic0/GPXSee](https://github.com/tumic0/GPXSee) — GPS log viewer and analyzer for GPX, TCX, KML, and FIT ☆`1,269`
1. [dtcooper/python-fitparse](https://github.com/dtcooper/python-fitparse) — Python library to parse ANT/Garmin .FIT files ☆`826`
1. [jaroslawhartman/withings-sync](https://github.com/jaroslawhartman/withings-sync) — Synchronisation of Withings weight ☆`704`
1. [garmin/connectiq-apps](https://github.com/garmin/connectiq-apps) — A collection of Connect IQ apps. ☆`598`
1. [cyberjunky/home-assistant-garmin_connect](https://github.com/cyberjunky/home-assistant-garmin_connect) — Garmin Connect data in Home Assistant ☆`592`
1. [pe-st/garmin-connect-export](https://github.com/pe-st/garmin-connect-export) — Download Garmin Connect stats and GPX tracks ☆`498`
1. [warmsound/crystal-face](https://github.com/warmsound/crystal-face) — Garmin Connect IQ watch face ☆`470`
1. [house-of-abbey/GarminHomeAssistant](https://github.com/house-of-abbey/GarminHomeAssistant) — Home Assistant dashboard on a Garmin watch ☆`382`
1. [alex-hhh/ActivityLog2](https://github.com/alex-hhh/ActivityLog2) — Analyze data from swim, bike and run activities ☆`369`
1. [peregin/gps-overlay-on-video](https://github.com/peregin/gps-overlay-on-video) — Telemetry (GPS) data overlay on videos ☆`363`
1. [philosowaffle/peloton-to-garmin](https://github.com/philosowaffle/peloton-to-garmin) — Convert Peloton workouts to FIT and upload ☆`360`
1. [RobertWojtowicz/export2garmin](https://github.com/RobertWojtowicz/export2garmin) — Export Mi | Xiaomi scale & Omron data to Garmin Connect ☆`276`
1. [aspain/git-sweaty](https://github.com/aspain/git-sweaty) — Strava and Garmin activities as GitHub-style graphs ☆`272`
1. [hatl/hasscontrol](https://github.com/hatl/hasscontrol) — Simple garmin widget to control home assistant scenes ☆`270`
1. [arpanghosh8453/fit-dashboard](https://github.com/arpanghosh8453/fit-dashboard) — Offline desktop dashboard for Garmin FIT files ☆`245`
1. [lswiderski/mi-scale-exporter](https://github.com/lswiderski/mi-scale-exporter) — Export Mi Scale body composition to Garmin Connect ☆`244`
1. [jimmykane/quantified-self](https://github.com/jimmykane/quantified-self) — Central app for Garmin, Suunto, and Coros data ☆`239`
1. [KristianP26/ble-scale-sync](https://github.com/KristianP26/ble-scale-sync) — BLE scale bridge to Connect, Strava, MQTT, and files ☆`232`
1. [ludw/Segment34mkII](https://github.com/ludw/Segment34mkII) — 34-segment watch face with moon, weather, and health ☆`228`
1. [polyvertex/fitdecode](https://github.com/polyvertex/fitdecode) — A FIT file parsing and decoding library written in Python3 ☆`222`
1. [Nicolasvegam/garmin-connect-mcp](https://github.com/Nicolasvegam/garmin-connect-mcp) — MCP with 61 Garmin Connect health and fitness tools ☆`193`
1. [drkostas/hevy2garmin](https://github.com/drkostas/hevy2garmin) — Sync Hevy workouts, sets, and HR to Garmin Connect ☆`191`
1. [muktihari/fit](https://github.com/muktihari/fit) — Go FIT SDK for protocol v2 encode and decode ☆`183`
1. [maca88/SmartBikeLights](https://github.com/maca88/SmartBikeLights) — Garmin application for ANT+ bike lights ☆`173`
1. [nrvim/garmin-givemydata](https://github.com/nrvim/garmin-givemydata) — Local SQLite archive of Connect data with MCP ☆`173`
1. [garmin/fit-python-sdk](https://github.com/garmin/fit-python-sdk) — Official Garmin FIT Python SDK ☆`171`
1. [AlexxIT/SmartScaleConnect](https://github.com/AlexxIT/SmartScaleConnect) — Sync smart scale data between ecosystems ☆`171`
1. [mgifos/quick-plan](https://github.com/mgifos/quick-plan) — Defines and schedules Garmin workouts ☆`157`
1. [Likenttt/garmin-connectiq-samples-brief-explanations](https://github.com/Likenttt/garmin-connectiq-samples-brief-explanations) — Connect IQ samples and FAQ notes ☆`144`
1. [diegoscarabelli/garmin-health-data](https://github.com/diegoscarabelli/garmin-health-data) — CLI to download Connect data into local SQLite ☆`136`
1. [mkuthan/garmin-workouts](https://github.com/mkuthan/garmin-workouts) — Command line tool for managing Garmin workouts. ☆`128`
1. [gcormier9/GRun](https://github.com/gcormier9/GRun) — Configurable Garmin Watch datafield ☆`123`
1. [ch1bo/garmin-otp-authenticator](https://github.com/ch1bo/garmin-otp-authenticator) — HOTP, TOTP, and Steam Guard widget for Connect IQ ☆`120`
1. [sodelalbert/Withings2Garmin](https://github.com/sodelalbert/Withings2Garmin) — Sync Withings scale weight to Garmin Connect ☆`116`
1. [TDF-PL/TAKWatch](https://github.com/TDF-PL/TAKWatch) — TAKWatch is an ATAK plugin that communicates with Garmin devices ☆`113`
1. [simonepri/fitbit2garmin](https://github.com/simonepri/fitbit2garmin) — Export Fitbit body, activity, and GPS for Connect ☆`112`
1. [klimeryk/garmodoro](https://github.com/klimeryk/garmodoro) — Pomodoro for Garmin devices using Connect IQ ☆`111`
1. [Aebel-Shajan/year-in-data](https://github.com/Aebel-Shajan/year-in-data) — Annual activity heatmaps from Garmin and other data ☆`107`
1. [jat255/Fit-File-Faker](https://github.com/jat255/Fit-File-Faker) — Edit and upload virtual-cycling FIT files to Connect ☆`100`
1. [blotspot/garmin-watchface-protomolecule](https://github.com/blotspot/garmin-watchface-protomolecule) — A Watchface for Garmin Smartwatches ☆`91`
1. [RafaTatay/garming-stats](https://github.com/RafaTatay/garming-stats) — Self-hosted activity stats as a Strava Premium stand-in ☆`83`
1. [garmin/fit-javascript-sdk](https://github.com/garmin/fit-javascript-sdk) — Official Garmin FIT JavaScript SDK ☆`81`
1. [garmin/connectiq-companion-app-sdk-ios](https://github.com/garmin/connectiq-companion-app-sdk-ios) — iOS SDK for companion apps talking to Monkey C ☆`81`
1. [garmin/connectiq-android-sdk](https://github.com/garmin/connectiq-android-sdk) — Connect IQ Mobile SDK for Android ☆`80`


---

## 🌱 38 rising

> Updated in the last two months, and still under the star threshold. Newest first.

1. [openhab/openhab-garmin](https://github.com/openhab/openhab-garmin) — Garmin widget for an openHAB home-automation server ☆`7`
1. [mikeller/garmin-christchurch-bus-widget](https://github.com/mikeller/garmin-christchurch-bus-widget) — Bus departures in Christchurch on a Garmin watch ☆`6`
1. [bombsimon/monkey-c-rs](https://github.com/bombsimon/monkey-c-rs) — Monkey C linter, formatter, and coverage tools ☆`6`
1. [ad220/gopro-remote-connectiq](https://github.com/ad220/gopro-remote-connectiq) — Garmin ConnectIQ widget to control a GoPro from your wrist ☆`12`
1. [zetxek/garmin-qr](https://github.com/zetxek/garmin-qr) — Garmin IQ application to generate and display QR codes and barcodes ☆`7`
1. [buessow/garmin](https://github.com/buessow/garmin) — Glucose displays for Garmin devices. ☆`12`
1. [arsfabula/Insta360-Remote-CIQ](https://github.com/arsfabula/Insta360-Remote-CIQ) — Garmin Connect IQ Remote for Insta360 Cameras ☆`14`
1. [felwal/avganar](https://github.com/felwal/avganar) — Public transport watch app for Stockholm, Sweden ☆`12`
1. [matco/connectiq-tester](https://github.com/matco/connectiq-tester) — Docker image with the Connect IQ SDK and simulator for tests ☆`11`
1. [pedrorijo91/garmin-padel](https://github.com/pedrorijo91/garmin-padel) — padel scorekeeper garmin watch app ☆`6`
1. [garmin/fit-c-sdk](https://github.com/garmin/fit-c-sdk) — Official Garmin FIT C SDK ☆`5`
1. [garmin/fit-cpp-sdk](https://github.com/garmin/fit-cpp-sdk) — Official Garmin FIT C++ SDK ☆`3`
1. [tcgoetz/GarminDbPlugins](https://github.com/tcgoetz/GarminDbPlugins) — Plugins that import extra FIT fields into GarminDB ☆`11`
1. [semolina-solutions/rules_ciq](https://github.com/semolina-solutions/rules_ciq) — A Bazel module for Garmin Connect IQ development tools. ☆`0`
1. [floriangeigl/Meditate](https://github.com/floriangeigl/Meditate) — Free Meditation & Breathwork app for Garmin watches ☆`9`
1. [phil-mitchell/garmin-curling](https://github.com/phil-mitchell/garmin-curling) — A curling activity tracker for Garmin devices ☆`1`
1. [mikeller/garmin-divesite-weather-widget](https://github.com/mikeller/garmin-divesite-weather-widget) — Dive-site weather on a Garmin watch ☆`3`
1. [rexMingla/low-battery-mode](https://github.com/rexMingla/low-battery-mode) — Garmin Connect Monkey C Application for lower battery mode ☆`2`
1. [hacdias/flowfit](https://github.com/hacdias/flowfit) — Turn FIT files generated by Bosch's eBike Flow app into a valid FIT file ☆`5`
1. [landnavapp/landnavapp](https://github.com/landnavapp/landnavapp) — Homepage ☆`0`
1. [sam-dumont/GarminGoProDatafield](https://github.com/sam-dumont/GarminGoProDatafield) — Control a GoPro from a supported Garmin device ☆`15`
1. [werkkrew/ciq-hiit-tracker](https://github.com/werkkrew/ciq-hiit-tracker) — Orange Theory Fitness - Garmin Connect IQ App ☆`9`
1. [blackshadev/garmin-connectiq-release-action](https://github.com/blackshadev/garmin-connectiq-release-action) — GitHub Action that exports a Connect IQ app ☆`3`
1. [blkfribourg/WheelDash](https://github.com/blkfribourg/WheelDash) — Garmin app for Begode, Leaperkim, Kingsong, InMotion ☆`7`
1. [axl13/PowerAdjuster](https://github.com/axl13/PowerAdjuster) — Connect IQ Power Adjuster ☆`3`
1. [pyrob2142/FastingWidget](https://github.com/pyrob2142/FastingWidget) — A simple fasting tracker for Garmin devices ☆`7`
1. [dev-whiterice/Essence](https://github.com/dev-whiterice/Essence) — Essence, a watchface for Garmin devices ☆`6`
1. [Karth01/Garmin-TaskerRemote](https://github.com/Karth01/Garmin-TaskerRemote) — Garmin glance that runs actions on an Android phone ☆`0`
1. [evilwombat/HikeFieldv2](https://github.com/evilwombat/HikeFieldv2) — Hiking data field for Garmin smartwatches ☆`4`
1. [Gumix/garmin-watchfaces](https://github.com/Gumix/garmin-watchfaces) — Garmin Watch Faces ☆`3`
1. [DavidBaddeley/connectiq-tester](https://github.com/DavidBaddeley/connectiq-tester) — Docker image that builds a Connect IQ app ☆`6`
1. [flocsy/BodyBatteryDF](https://github.com/flocsy/BodyBatteryDF) — Body Battery data field for Garmin watches ☆`1`
1. [bderusha/GarminIQ-CoachCompanion](https://github.com/bderusha/GarminIQ-CoachCompanion) — GarminIQ Data Field app for using the RunWalkRun method ☆`6`
1. [ChelsWin/Tasker-Trigger](https://github.com/ChelsWin/Tasker-Trigger) — Trigger Tasker tasks from your Garmin watch ☆`5`
1. [METIQ-Solutions/evcc-garmin](https://github.com/METIQ-Solutions/evcc-garmin) — Garmin widget for evcc solar-powered EV charging ☆`7`
1. [anup-shesh/garmin-local-mcp](https://github.com/anup-shesh/garmin-local-mcp) — Local Garmin data warehouse and MCP server for Connect ☆`9`
1. [serroba/mace-clubs](https://github.com/serroba/mace-clubs) — Connect IQ workouts for steel mace and club training ☆`1`
1. [suskozaver/gkg](https://github.com/suskozaver/gkg) — Google Keep lists on the watch, via a self-hosted server ☆`1`



## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## Feedback

Found something wrong? Open an issue or submit a pull request - contributions are welcome!

## Credits

- [bombsimon/awesome-garmin](https://github.com/bombsimon/awesome-garmin)
- [All Contributors](https://github.com/abordage/awesome-garmin/graphs/contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.
