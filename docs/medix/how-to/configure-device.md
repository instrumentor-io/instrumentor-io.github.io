---
layout: default
title: How to? Guide
parent: MediX Vitual Assistant
has_children: true
---

## Configure your own Android Device for using with MediX

You can use any Android device (OS Level > 11) to install and use MediX. There are 2 pre-requisite steps involved in configuring your device.

### Allow APK install from unknown sources

MediX is not (yet) available on any commerical playstores. So you will be downloading the MediX software from Instrumentor site. You need to tell you Android device it is ok to install MediX from non play store locations. These instructions assume a Samsun device, if you are using a different device - please search internet on how to accomplish this.

- Navigate to "Settings"
- Search for "Install Unknown Apps" in the search bar for settings: ![Settings](/assets/images/medix/unknown-app-suggestions.png)
- Select "Install Unknown Apps" from "Specical Access" section: ![SpecialAccess] (/assets/images/medix/special-access-unknown-apps.png)
- Select "My Files" from list of suggestions, telling Android it's ok to install apps that are stored locally on your device. We recommend downloading APK file to your local storage and installing from these. ![LocationSuggestions](/assets/images/medix/unknown-apps-selections.png)

### Allow MediX to listen to on-board microphone

When you connect your OR equipment's video feed to your Android device, it'll try to listen to voice commands from that source. Of course, there's no audio source and hence you need to configure your Android Device to use on-board microphone/bluetooth.

- Enable Developer Mode
- Disable USB audio routing

& that's it, you can now proceed to install MediX on your Android device.
