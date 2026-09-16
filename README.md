# Awesome Garmin

![Awesome](https://raw.githubusercontent.com/abordage/schemas/main/badges/awesome.svg)
[![Last update](https://img.shields.io/github/last-commit/abordage/awesome-garmin?label=last%20update)](README.md)
![Repositories](https://img.shields.io/badge/repositories-106-06b6d4)
![Total Stars](https://img.shields.io/badge/total%20stars-26,638-gold)
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

- [cyberjunky/python-garminconnect](https://github.com/cyberjunky/python-garminconnect) — Python 3 API wrapper for Garmin Connect to get statistics and set activities ☆`3,010`
- [Pythe1337N/garmin-connect](https://github.com/Pythe1337N/garmin-connect) — Makes it simple to interface with Garmin Connect to get or set any data point. ☆`193`
- [mkuthan/garmin-workouts](https://github.com/mkuthan/garmin-workouts) — Command line tool for managing Garmin workouts. ☆`126`
- [sealbro/dotnet.garmin.connect](https://github.com/sealbro/dotnet.garmin.connect) — Unofficial garmin connect client ☆`45`
- [bes-dev/garmy](https://github.com/bes-dev/garmy) — Python library to interact with Garmin Connect API ☆`65`
## Companion & Mobile SDK

- [TDF-PL/TAKWatch](https://github.com/TDF-PL/TAKWatch) — TAKWatch is an ATAK plugin that communicates with Garmin devices ☆`108`
- [garmin/connectiq-android-sdk](https://github.com/garmin/connectiq-android-sdk) — Connect IQ Mobile SDK for Android ☆`78`
- [urbandroid-team/Sleep-as-Android-Garmin-Addon](https://github.com/urbandroid-team/Sleep-as-Android-Garmin-Addon) — Code for both Android part and Garmin part of the Sleep as Android Garmin smartwatch integration ☆`60`
- [garmin/connectiq-companion-app-sdk-ios](https://github.com/garmin/connectiq-companion-app-sdk-ios) — The Connect IQ Companion App SDK allows companion iOS applications to be created that interact with Monkey C applications running on Garmin wearable devices. ☆`76`
- [gimportexportdevs/gimporter](https://github.com/gimportexportdevs/gimporter) — Garmin Connect App to import GPX and FIT files ☆`30`
- [gimportexportdevs/gexporter](https://github.com/gimportexportdevs/gexporter) — Android App to export GPX and FIT to garmin devices ☆`30`
- [MatyasKriz/ios-connect-iq-comms](https://github.com/MatyasKriz/ios-connect-iq-comms) — An example of a two way communication between an iOS companion app and a ConnectIQ app on a Garmin device. ☆`17`
## Connect IQ

### Data Fields

- [maca88/SmartBikeLights](https://github.com/maca88/SmartBikeLights) — Garmin application for ANT+ bike lights ☆`171`
- [gcormier9/GRun](https://github.com/gcormier9/GRun) — Configurable Garmin Watch datafield ☆`123`
- [wwarby/walker](https://github.com/wwarby/walker) — A free data field for Garmin watches to provide stats for walking activities ☆`69`
- [pauljohnston2025/breadcrumb-garmin](https://github.com/pauljohnston2025/breadcrumb-garmin) — Garmin watch datafield that shows breadcrumb trail ☆`21`
- [maca88/E-Bike-Edge-MultiField](https://github.com/maca88/E-Bike-Edge-MultiField) —  ☆`18`
- [ActiveLook/Garmin-Datafield-sample-code](https://github.com/ActiveLook/Garmin-Datafield-sample-code) — ActiveLook Garmin Datafield ☆`16`
- [fabiobaltieri/ciq-nrf-blinky](https://github.com/fabiobaltieri/ciq-nrf-blinky) — Connect IQ application client for Nordic nRF Blinky BLE example ☆`17`
### Games

- [Gualor/garmin-gotchi](https://github.com/Gualor/garmin-gotchi) — Tamagotchi Gen 1 Emulator for Garmin Instinct 3. ☆`16`
### Smart Home

- [house-of-abbey/GarminHomeAssistant](https://github.com/house-of-abbey/GarminHomeAssistant) — Garmin application to provide a dashboard to control your Home Assistant ☆`362`
### Sports & Workouts

- [kartoone/mybiketraffic](https://github.com/kartoone/mybiketraffic) — ConnectIQ app for processing Garmin Varia radar data and counting vehicles. ☆`66`
- [ydutertre/myvario](https://github.com/ydutertre/myvario) — Fork of GliderSK targeted towards paraglider pilots ☆`38`
- [matco/badminton](https://github.com/matco/badminton) — Badminton application for Garmin watches ☆`37`
- [chanezgr/IQwprimebal](https://github.com/chanezgr/IQwprimebal) — Garmin Connect IQ Wprime Bal application ☆`22`
- [OpenSeizureDetector/Garmin_SD](https://github.com/OpenSeizureDetector/Garmin_SD) — Garmin Watch Seizure Detector - A seizure detector data source based on Garmin IQ watches such as Vivoactive HR ☆`16`
- [Laverlin/Yet-Another-Sailing-App](https://github.com/Laverlin/Yet-Another-Sailing-App) — Sailing application for Garmin smartwatches ☆`27`
- [andan67/wormnav](https://github.com/andan67/wormnav) — Track navigation for Garmin watches ☆`17`
- [aiMonster/Garmin-Contrast-Shower](https://github.com/aiMonster/Garmin-Contrast-Shower) — An application for Garmin watches to take a contrast shower ☆`21`
### Utilities

- [ch1bo/garmin-otp-authenticator](https://github.com/ch1bo/garmin-otp-authenticator) — Garmin ConnectIQ Widget for One Time Passwords (HOTP / TOTP / Steam Guard) ☆`120`
- [klimeryk/garmodoro](https://github.com/klimeryk/garmodoro) — Pomodoro for Garmin devices using Connect IQ ☆`108`
- [TDF-PL/TAKWatch-IQ](https://github.com/TDF-PL/TAKWatch-IQ) — TAKWatch-IQ is a Garmin ConnectIQ application that integrates ATAK with Garmin devices ☆`58`
- [BleachDev/Rainy](https://github.com/BleachDev/Rainy) — My Garmin weather app. ☆`33`
### Watch Faces

- [warmsound/crystal-face](https://github.com/warmsound/crystal-face) — Garmin Connect IQ watch face ☆`467`
- [ludw/Segment34mkII](https://github.com/ludw/Segment34mkII) —  ☆`216`
- [blotspot/garmin-watchface-protomolecule](https://github.com/blotspot/garmin-watchface-protomolecule) — A Watchface for Garmin Smartwatches ☆`91`
- [myneur/late](https://github.com/myneur/late) — Garmin Smart Watch with Calendar & Weather ☆`67`
- [fevieira27/MoveToBeActive](https://github.com/fevieira27/MoveToBeActive) — An open source Garmin Watch Face inspired by the design of the Vivomove series, but adding extra data points that are useful for daily usage (like health, weather and communication) on newer Garmin Smartwatches. ☆`46`
- [Laverlin/Yet-Another-WatchFace](https://github.com/Laverlin/Yet-Another-WatchFace) — Watch Face application for Garmin smartwatch ☆`69`
- [samuelmr/garmin-abouttime](https://github.com/samuelmr/garmin-abouttime) — A watch face for Garmin Connect IQ devices ☆`37`
- [ludw/Segment34](https://github.com/ludw/Segment34) — Watchface for Garmin Fenix 6 with a 34 Segment display ☆`62`
- [victorpaul/garmin-watchFace](https://github.com/victorpaul/garmin-watchFace) —  ☆`34`
- [ahuggel/SwissRailwayClock](https://github.com/ahuggel/SwissRailwayClock) — An analog watchface for Garmin smartwatches, implementing the iconic Swiss railway clock design ☆`31`
- [causeri3/fine-o-clock](https://github.com/causeri3/fine-o-clock) — Garmin Watch Face ☆`44`
- [dennybiasiolli/garmin-connect-iq](https://github.com/dennybiasiolli/garmin-connect-iq) — Home for Garmin Connect IQ Projects ☆`25`
- [sunpazed/garmin-nyan-cat](https://github.com/sunpazed/garmin-nyan-cat) — An animated Nyan Cat watchface for Garmin's wearable lineup. ☆`24`
- [SylvainGa/crystal-face](https://github.com/SylvainGa/crystal-face) — Garmin Connect IQ watch face ☆`18`
### Widgets

- [hatl/hasscontrol](https://github.com/hatl/hasscontrol) — Simple garmin widget to control home assistant scenes ☆`258`
- [macherel/Barcode-Wallet](https://github.com/macherel/Barcode-Wallet) —  ☆`75`
- [maca88/BikeLightsControl](https://github.com/maca88/BikeLightsControl) — Garmin widget for controlling ANT+ lights ☆`22`
- [uaraven/otpauth-ciq](https://github.com/uaraven/otpauth-ciq) — ConnectIQ widget for generating TOTP authentication codes. ☆`20`
- [starryalley/Unquestionify](https://github.com/starryalley/Unquestionify) — A Garmin Connect IQ widget for displaying phone notifications as bitmap ☆`18`
- [jctim/otp-ciq](https://github.com/jctim/otp-ciq) — OTP Auth Widget for Garmin Connect IQ ☆`20`
- [SylvainGa/Tesla-Link](https://github.com/SylvainGa/Tesla-Link) — ConnectIQ widget for Tesla vehicle control ☆`16`
## Data

### Export & Backup

- [tcgoetz/GarminDB](https://github.com/tcgoetz/GarminDB) — Download and parse data from Garmin Connect or a Garmin watch, FitBit CSV, and MS Health CSV files into and analyze data in Sqlite serverless databases with Jupyter notebooks. ☆`3,304`
- [pe-st/garmin-connect-export](https://github.com/pe-st/garmin-connect-export) — Download a copy of your Garmin Connect data, including stats and GPX tracks. ☆`499`
- [diegoscarabelli/garmin-health-data](https://github.com/diegoscarabelli/garmin-health-data) — A simple Python CLI to download Garmin Connect data as local files and load them into a SQLite database for analysis ☆`116`
### FIT

- [dtcooper/python-fitparse](https://github.com/dtcooper/python-fitparse) — Python library to parse ANT/Garmin .FIT files ☆`820`
- [tormoder/fit](https://github.com/tormoder/fit) — A Go package for decoding and encoding Garmin FIT files ☆`266`
- [polyvertex/fitdecode](https://github.com/polyvertex/fitdecode) — A FIT file parsing and decoding library written in Python3 ☆`218`
- [muktihari/fit](https://github.com/muktihari/fit) — A FIT SDK for decoding and encoding Garmin FIT files in Go supporting FIT Protocol V2. ☆`179`
- [garmin/fit-python-sdk](https://github.com/garmin/fit-python-sdk) — Official Garmin FIT Python SDK ☆`163`
- [jat255/Fit-File-Faker](https://github.com/jat255/Fit-File-Faker) — A tool to edit and upload FIT files produced by virtual cycling apps to Garmin Connect ☆`100`
- [garmin/fit-javascript-sdk](https://github.com/garmin/fit-javascript-sdk) — Official Garmin FIT JavaScript SDK ☆`76`
- [jpickup/GarminTools](https://github.com/jpickup/GarminTools) — A suite of tools for creating Garmin FIT files for workouts, schedules and courses ☆`66`
- [Nick2bad4u/FitFileViewer](https://github.com/Nick2bad4u/FitFileViewer) — Fit File Viewer - Cross-Platform application to analyze Fit files. Builds available for Windows, Mac, and Linux in a variety of formats. ☆`64`
- [stadelmanma/fitparse-rs](https://github.com/stadelmanma/fitparse-rs) — Rust library to parse FIT formatted files ☆`73`
- [garmin/fit-sdk-tools](https://github.com/garmin/fit-sdk-tools) — Official Garmin FIT SDK Tools ☆`50`
- [openivity/openivity.github.io](https://github.com/openivity/openivity.github.io) — An open-source fitness analytic platform offering data visualization (with OpenStreetMap), edit, convert, and combine multiple FIT, GPX, and TCX activity files. 100% client-side power! (WebAssembly) ☆`43`
- [garmin/fit-objective-c-sdk](https://github.com/garmin/fit-objective-c-sdk) — Official Garmin FIT Objective-C SDK ☆`35`
- [garmin/fit-java-sdk](https://github.com/garmin/fit-java-sdk) — Official Garmin FIT Java SDK ☆`35`
- [garmin/fit-csharp-sdk](https://github.com/garmin/fit-csharp-sdk) —  ☆`26`
- [garmin/fit-swift-sdk](https://github.com/garmin/fit-swift-sdk) — Official Garmin FIT Swift SDK ☆`21`
- [MaksVasilev/fit2gpx](https://github.com/MaksVasilev/fit2gpx) — Converter Garmin FIT files to GPX, CVS, HR, HRV, SpO2: fit2gpx, fit2csv, fit2sqlite, fit2db. Standalone application, not a shell script to gpsbabel, redy to use (Java). ☆`39`
### Maps

- [ligfietser/mkgmap-style-sheets](https://github.com/ligfietser/mkgmap-style-sheets) — This project aims to improve the vector maps for Garmin GPS created with the mkgmap compiler from http://OpenStreetMap.org data for the world routable maps at http://garmin.openstreetmap.nl ☆`52`
### Visualization

- [yihong0618/running_page](https://github.com/yihong0618/running_page) — Make your own running home page ☆`4,515`
- [arpanghosh8453/garmin-grafana](https://github.com/arpanghosh8453/garmin-grafana) — A Dockerized python Script to fetch Garmin health data and populate that in a InfluxDB Database, for visualization long term health trends with Grafana ☆`3,462`
- [aspain/git-sweaty](https://github.com/aspain/git-sweaty) — Turn your Strava and Garmin activities into GitHub-style contribution graphs. ☆`261`
- [jimmykane/quantified-self](https://github.com/jimmykane/quantified-self) — Analyze your data from Garmin, Suunto, Coros to one centralized app ☆`228`
- [arpanghosh8453/fit-dashboard](https://github.com/arpanghosh8453/fit-dashboard) — Standalone offline local desktop application to process, store, and visualize Garmin FIT file data in a comprehensive dashboard. ☆`218`
## Developer Tools

### Editors & LSP

- [markw65/prettier-extension-monkeyc](https://github.com/markw65/prettier-extension-monkeyc) — A VSCode extension for Garmin MonkeyC ☆`19`
- [markw65/prettier-plugin-monkeyc](https://github.com/markw65/prettier-plugin-monkeyc) — A prettier plugin for Garmin monkey-c ☆`18`
### SDK & Tooling

- [garmin/connectiq-apps](https://github.com/garmin/connectiq-apps) — A collection of Connect IQ apps. ☆`589`
- [AndrewKhassapov/connect-iq](https://github.com/AndrewKhassapov/connect-iq) — Creating a Garmin watch-face 101 ☆`79`
- [pcolby/connectiq-sdk-manager](https://github.com/pcolby/connectiq-sdk-manager) — Garmin's Connect IQ SDK Manager as an AppImage ☆`44`
- [flocsy/garmin-dev-tools](https://github.com/flocsy/garmin-dev-tools) — Tools for Garmin CIQ developers ☆`24`
- [markw65/monkeyc-optimizer](https://github.com/markw65/monkeyc-optimizer) — Utilities for optimizing monkeyc projects ☆`19`
## Integrations

### Scales

- [RobertWojtowicz/export2garmin](https://github.com/RobertWojtowicz/export2garmin) — Export Mi | Xiaomi scale & Omron data to Garmin Connect ☆`270`
- [lswiderski/mi-scale-exporter](https://github.com/lswiderski/mi-scale-exporter) — Mobile App to export data from Mi Body Composition Scale and upload it to Garmin Connect Cloud ☆`234`
- [KristianP26/ble-scale-sync](https://github.com/KristianP26/ble-scale-sync) — Universal BLE Smart Scale bridge. Captures body composition from Renpho, Xiaomi & 20+ others, syncs to Garmin Connect, Strava, MQTT (Home Assistant), InfluxDB, Webhooks, Ntfy & local files (CSV/JSONL). Headless CLI for Raspberry Pi, Linux, macOS & Windows. ☆`172`
- [AlexxIT/SmartScaleConnect](https://github.com/AlexxIT/SmartScaleConnect) — Application for sync smart scale data between different ecosystems ☆`145`
- [sodelalbert/Withings2Garmin](https://github.com/sodelalbert/Withings2Garmin) — Are you wondering how to sync data from Withings weight to Garmin Connect? Here is the answer! ☆`115`
### Smart Home

- [cyberjunky/home-assistant-garmin_connect](https://github.com/cyberjunky/home-assistant-garmin_connect) — This Garmin Connect integration allows you to expose and upload data from and to Garmin Connect to Home Assistant. ☆`564`
### Sync

- [philosowaffle/peloton-to-garmin](https://github.com/philosowaffle/peloton-to-garmin) — Convert workout data from Peloton into JSON/TCX/FIT files and automatically upload to Garmin Connect ☆`359`
- [drkostas/hevy2garmin](https://github.com/drkostas/hevy2garmin) — Sync Hevy gym workouts to Garmin Connect with exercise names, sets, reps, weights, HR overlay, and calorie estimation ☆`136`
- [mgifos/quick-plan](https://github.com/mgifos/quick-plan) — Defines and schedules Garmin workouts ☆`156`
- [chloevoyer/garmin-to-notion](https://github.com/chloevoyer/garmin-to-notion) — Import data from GarminConnect to Notion database ☆`56`
- [simonepri/fitbit2garmin](https://github.com/simonepri/fitbit2garmin) — Downloads lifetime Fitbit data and exports it into the format supported by Garmin Connect data importer. This includes historical body composition data (weight, BMI, and fat percentage), activity data (calories burned, steps, distance, active minutes, and floors climbed), and individual GPS exercises (TCX). ☆`112`
- [fulippo/share-your-garmin-workout](https://github.com/fulippo/share-your-garmin-workout) — Chrome extension to share your Garmin Connect workout with your friends ☆`27`
## MCP Servers

- [Taxuspt/garmin_mcp](https://github.com/Taxuspt/garmin_mcp) — MCP server to access Garmin data ☆`1,179`
- [Nicolasvegam/garmin-connect-mcp](https://github.com/Nicolasvegam/garmin-connect-mcp) — MCP server for Garmin Connect — access 61 health, fitness and activity tools from any AI assistant ☆`179`
- [nrvim/garmin-givemydata](https://github.com/nrvim/garmin-givemydata) — It's YOUR data. Take it back. Get your Garmin Connect data into a local SQLite database and AI ready (MCP server) ☆`151`
- [eddmann/garmin-connect-mcp](https://github.com/eddmann/garmin-connect-mcp) — MCP server enabling LLMs to interact with Garmin Connect - activities, health metrics, sleep data, and training analysis ☆`63`
- [matin/garth-mcp-server](https://github.com/matin/garth-mcp-server) — Garmin Connect MCP server based on Garth ☆`63`
- [etweisberg/garmin-connect-mcp](https://github.com/etweisberg/garmin-connect-mcp) — Garmin Connect MCP ☆`43`
- [Wewoc/Garmin_Local_Archive](https://github.com/Wewoc/Garmin_Local_Archive) — Secure, local-first archive for Garmin Connect health data. Preserve your data before Garmin's historical data decay. Private & offline. Windows desktop app, no setup needed. Built for long-term local analysis, dashboards ,local AI and MCP-Server. ☆`19`


---

## 🏆 Top 50 by Stars

> The most starred projects in this list, sorted by GitHub stars.

1. [yihong0618/running_page](https://github.com/yihong0618/running_page) — Make your own running home page ☆`4,515`
1. [arpanghosh8453/garmin-grafana](https://github.com/arpanghosh8453/garmin-grafana) — A Dockerized python Script to fetch Garmin health data and populate that in a InfluxDB Database, for visualization long term health trends with Grafana ☆`3,462`
1. [tcgoetz/GarminDB](https://github.com/tcgoetz/GarminDB) — Download and parse data from Garmin Connect or a Garmin watch, FitBit CSV, and MS Health CSV files into and analyze data in Sqlite serverless databases with Jupyter notebooks. ☆`3,304`
1. [cyberjunky/python-garminconnect](https://github.com/cyberjunky/python-garminconnect) — Python 3 API wrapper for Garmin Connect to get statistics and set activities ☆`3,010`
1. [Taxuspt/garmin_mcp](https://github.com/Taxuspt/garmin_mcp) — MCP server to access Garmin data ☆`1,179`
1. [dtcooper/python-fitparse](https://github.com/dtcooper/python-fitparse) — Python library to parse ANT/Garmin .FIT files ☆`820`
1. [garmin/connectiq-apps](https://github.com/garmin/connectiq-apps) — A collection of Connect IQ apps. ☆`589`
1. [cyberjunky/home-assistant-garmin_connect](https://github.com/cyberjunky/home-assistant-garmin_connect) — This Garmin Connect integration allows you to expose and upload data from and to Garmin Connect to Home Assistant. ☆`564`
1. [pe-st/garmin-connect-export](https://github.com/pe-st/garmin-connect-export) — Download a copy of your Garmin Connect data, including stats and GPX tracks. ☆`499`
1. [warmsound/crystal-face](https://github.com/warmsound/crystal-face) — Garmin Connect IQ watch face ☆`467`
1. [house-of-abbey/GarminHomeAssistant](https://github.com/house-of-abbey/GarminHomeAssistant) — Garmin application to provide a dashboard to control your Home Assistant ☆`362`
1. [philosowaffle/peloton-to-garmin](https://github.com/philosowaffle/peloton-to-garmin) — Convert workout data from Peloton into JSON/TCX/FIT files and automatically upload to Garmin Connect ☆`359`
1. [RobertWojtowicz/export2garmin](https://github.com/RobertWojtowicz/export2garmin) — Export Mi | Xiaomi scale & Omron data to Garmin Connect ☆`270`
1. [tormoder/fit](https://github.com/tormoder/fit) — A Go package for decoding and encoding Garmin FIT files ☆`266`
1. [aspain/git-sweaty](https://github.com/aspain/git-sweaty) — Turn your Strava and Garmin activities into GitHub-style contribution graphs. ☆`261`
1. [hatl/hasscontrol](https://github.com/hatl/hasscontrol) — Simple garmin widget to control home assistant scenes ☆`258`
1. [lswiderski/mi-scale-exporter](https://github.com/lswiderski/mi-scale-exporter) — Mobile App to export data from Mi Body Composition Scale and upload it to Garmin Connect Cloud ☆`234`
1. [jimmykane/quantified-self](https://github.com/jimmykane/quantified-self) — Analyze your data from Garmin, Suunto, Coros to one centralized app ☆`228`
1. [arpanghosh8453/fit-dashboard](https://github.com/arpanghosh8453/fit-dashboard) — Standalone offline local desktop application to process, store, and visualize Garmin FIT file data in a comprehensive dashboard. ☆`218`
1. [polyvertex/fitdecode](https://github.com/polyvertex/fitdecode) — A FIT file parsing and decoding library written in Python3 ☆`218`
1. [ludw/Segment34mkII](https://github.com/ludw/Segment34mkII) ☆`216`
1. [Pythe1337N/garmin-connect](https://github.com/Pythe1337N/garmin-connect) — Makes it simple to interface with Garmin Connect to get or set any data point. ☆`193`
1. [Nicolasvegam/garmin-connect-mcp](https://github.com/Nicolasvegam/garmin-connect-mcp) — MCP server for Garmin Connect — access 61 health, fitness and activity tools from any AI assistant ☆`179`
1. [muktihari/fit](https://github.com/muktihari/fit) — A FIT SDK for decoding and encoding Garmin FIT files in Go supporting FIT Protocol V2. ☆`179`
1. [KristianP26/ble-scale-sync](https://github.com/KristianP26/ble-scale-sync) — Universal BLE Smart Scale bridge. Captures body composition from Renpho, Xiaomi & 20+ others, syncs to Garmin Connect, Strava, MQTT (Home Assistant), InfluxDB, Webhooks, Ntfy & local files (CSV/JSONL). Headless CLI for Raspberry Pi, Linux, macOS & Windows. ☆`172`
1. [maca88/SmartBikeLights](https://github.com/maca88/SmartBikeLights) — Garmin application for ANT+ bike lights ☆`171`
1. [garmin/fit-python-sdk](https://github.com/garmin/fit-python-sdk) — Official Garmin FIT Python SDK ☆`163`
1. [mgifos/quick-plan](https://github.com/mgifos/quick-plan) — Defines and schedules Garmin workouts ☆`156`
1. [nrvim/garmin-givemydata](https://github.com/nrvim/garmin-givemydata) — It's YOUR data. Take it back. Get your Garmin Connect data into a local SQLite database and AI ready (MCP server) ☆`151`
1. [AlexxIT/SmartScaleConnect](https://github.com/AlexxIT/SmartScaleConnect) — Application for sync smart scale data between different ecosystems ☆`145`
1. [drkostas/hevy2garmin](https://github.com/drkostas/hevy2garmin) — Sync Hevy gym workouts to Garmin Connect with exercise names, sets, reps, weights, HR overlay, and calorie estimation ☆`136`
1. [mkuthan/garmin-workouts](https://github.com/mkuthan/garmin-workouts) — Command line tool for managing Garmin workouts. ☆`126`
1. [gcormier9/GRun](https://github.com/gcormier9/GRun) — Configurable Garmin Watch datafield ☆`123`
1. [ch1bo/garmin-otp-authenticator](https://github.com/ch1bo/garmin-otp-authenticator) — Garmin ConnectIQ Widget for One Time Passwords (HOTP / TOTP / Steam Guard) ☆`120`
1. [diegoscarabelli/garmin-health-data](https://github.com/diegoscarabelli/garmin-health-data) — A simple Python CLI to download Garmin Connect data as local files and load them into a SQLite database for analysis ☆`116`
1. [sodelalbert/Withings2Garmin](https://github.com/sodelalbert/Withings2Garmin) — Are you wondering how to sync data from Withings weight to Garmin Connect? Here is the answer! ☆`115`
1. [simonepri/fitbit2garmin](https://github.com/simonepri/fitbit2garmin) — Downloads lifetime Fitbit data and exports it into the format supported by Garmin Connect data importer. This includes historical body composition data (weight, BMI, and fat percentage), activity data (calories burned, steps, distance, active minutes, and floors climbed), and individual GPS exercises (TCX). ☆`112`
1. [TDF-PL/TAKWatch](https://github.com/TDF-PL/TAKWatch) — TAKWatch is an ATAK plugin that communicates with Garmin devices ☆`108`
1. [klimeryk/garmodoro](https://github.com/klimeryk/garmodoro) — Pomodoro for Garmin devices using Connect IQ ☆`108`
1. [jat255/Fit-File-Faker](https://github.com/jat255/Fit-File-Faker) — A tool to edit and upload FIT files produced by virtual cycling apps to Garmin Connect ☆`100`
1. [blotspot/garmin-watchface-protomolecule](https://github.com/blotspot/garmin-watchface-protomolecule) — A Watchface for Garmin Smartwatches ☆`91`
1. [AndrewKhassapov/connect-iq](https://github.com/AndrewKhassapov/connect-iq) — Creating a Garmin watch-face 101 ☆`79`
1. [garmin/connectiq-android-sdk](https://github.com/garmin/connectiq-android-sdk) — Connect IQ Mobile SDK for Android ☆`78`
1. [garmin/connectiq-companion-app-sdk-ios](https://github.com/garmin/connectiq-companion-app-sdk-ios) — The Connect IQ Companion App SDK allows companion iOS applications to be created that interact with Monkey C applications running on Garmin wearable devices. ☆`76`
1. [garmin/fit-javascript-sdk](https://github.com/garmin/fit-javascript-sdk) — Official Garmin FIT JavaScript SDK ☆`76`
1. [macherel/Barcode-Wallet](https://github.com/macherel/Barcode-Wallet) ☆`75`
1. [stadelmanma/fitparse-rs](https://github.com/stadelmanma/fitparse-rs) — Rust library to parse FIT formatted files ☆`73`
1. [wwarby/walker](https://github.com/wwarby/walker) — A free data field for Garmin watches to provide stats for walking activities ☆`69`
1. [Laverlin/Yet-Another-WatchFace](https://github.com/Laverlin/Yet-Another-WatchFace) — Watch Face application for Garmin smartwatch ☆`69`
1. [myneur/late](https://github.com/myneur/late) — Garmin Smart Watch with Calendar & Weather ☆`67`


## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## Feedback

Found something wrong? Open an issue or submit a pull request - contributions are welcome!

## Credits

- [bombsimon/awesome-garmin](https://github.com/bombsimon/awesome-garmin)
- [All Contributors](https://github.com/abordage/awesome-garmin/graphs/contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.
