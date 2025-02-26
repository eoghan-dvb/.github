# Welcome to the OSMART Community 👋
Raise an [issue](https://github.com/osmart-community/.github/issues) and give us your contact (GitHub handle) if you wish to be added to the Team.
## Contents
- [CTA WAVE](https://github.com/osmart-community#cta-wave)
- [DASH-IF](https://github.com/osmart-community#dash-if)
- [DVB](https://github.com/osmart-community#dvb-project)
- [5G-MAG](https://github.com/osmart-community#5g-mag)
- [HbbTV](https://github.com/osmart-community#hbbtv-association)
- [MPEG](https://github.com/osmart-community#mpeg)
- [SVTA](https://github.com/osmart-community#svta)

***
  
## CTA WAVE
### Media Streaming Test Suite
#### SUMMARY
CTA WAVE Streaming Media Test Suite - Devices, check the hardware capability of playback on devices split into mezzanine content, test content generation encoding different variations and profiles, test runner for different devices and an observation framework for determining pass or fail results from camera recordings
#### SCOPE
TS/TV - Test Vectors and Test Suite (For Device Playback Capabilities)
#### WHO IS USING
CTA WAVE, HbbTV, ATSC
#### WHERE TO FIND
- Main Test Suite Repo: https://github.com/cta-wave/dpctf-deploy (uses the individual repos below)
- Mezzanine Repo: https://github.com/cta-wave/mezzanine
- Test Content Repo: https://github.com/cta-wave/Test-Content
- Test Runner Repos: https://github.com/cta-wave/dpctf-tests; https://github.com/cta-wave/dpctf-test-runner 
- Observation Framework: https://github.com/cta-wave/device-observation-framework

***

## DASH-IF
### Joint Content Conformance Project (JCCP)
#### SUMMARY
JCCP has developed a conformance tool to validate DASH and HLS content against different guidelines and profiles. There are specs, implementers and users and this tool allows e.g. vendors to check MPDs and segments, they provide test vectors to validate players…
Worth highlighting a big effort in additional details, documentation to make the project more understandable and usable.

#### SCOPE
CS - Conformance
#### WHO IS USING
DASH-IF, DVB, HbbTV,CMAF, CTA-WAVE
#### WHERE TO FIND
- https://github.com/Dash-Industry-Forum/DASH-IF-Conformance
- https://conformance.dashif.org/

### DASH-IF livesim2
#### SUMMARY
Livesim is a reference tool and testbed for live DASH timing testing. It allows creating live streams coming from VoD assets. In particular, livesim2 is a complete rewrite of livesim which also makes it easier to deploy locally and in the cloud. Worth highlighting possibility to generate streams with particular features, refragmentation to generate low-latency DASH, also an interactive UI which makes configuration easy
#### SCOPE
TV - Live Test Vectors to test timing aspects but also as a source of live streams
#### WHO IS USING
DASH-IF, HbbTV, DVB, 5G-MAG
#### WHERE TO FIND
- Available source code including short test content at https://github.com/Dash-Industry-Forum/livesim2
- Live at https://livesim2.dashif.org (limited to 10000 requests/24h/IP)
- An example is live also at https://refapp.hbbtv.org/testing/catalogue/ under “Live”-tab

### Dash.js
#### SUMMARY
dash.js is the official open-source DASH Reference Player. It is used as a reference client for standardization and can also be used as the foundation for production grade video applications and research purposes. The player supports a wide set of features (ABR, DRM, CMCD, CMSD, Content Steering,…)
#### SCOPE
RS - Reference implementation, available for testing and also commercial products
#### WHO IS USING
DASH-IF, DVB, HbbTV, CTA-WAVE, 5G-MAG
#### WHERE TO FIND
- https://github.com/Dash-Industry-Forum/dash.js/

***

## DVB Project
### DVB-I Reference Application
#### SUMMARY
DVB-I tools implementing several specifications (Service Discovery and Metadata, DVB MPEG-DASH Profile, implementation guidelines). 
DVB-I Backend for generating and editing DVB-I service lists and instances ; DVB-I app frontend with service list navigation, selection of services, banner, EPG, version for Android Mobile and HbbTV
DVB CSR skeleton implementation to support testing feasibility and features of a CSR
#### SCOPE
RS - Reference implementation, V&V
#### WHO IS USING
DVB, HbbTV
#### WHERE TO FIND
- CSR: https://github.com/DVBProject/DVB-I-Reference-CSR
- DVB-I Reference Client: https://github.com/DVBproject/DVB-I-Reference-Client

***

## 5G-MAG
### Reference Tools for 5G Media Streaming
#### SUMMARY
Reference Implementation of 5G Media Streaming components. Key features include content hosting, networks assistance (thoughput estimation, delivery boost,...) dynamic QoS policy, QoE metrics reporting, Consumption reporting.Implementation consist of 5GMS Application Server (wrapping OpenResty (Nginx)), 5GMS Application Function (built in the Open5GS framework), 5G Media Streaming Client (Android, Exoplayer,...).
#### SCOPE
RS - Reference implementation
#### WHO IS USING
5G-MAG
#### WHERE TO FIND
- https://www.5g-mag.com/repositories
- https://github.com/5G-MAG/Getting-Started/wiki/5G-Downlink-Media-Streaming
- https://github.com/5G-MAG/Getting-Started/wiki/5G-Core-Network

### Reference Tools for 5G Broadcast
#### SUMMARY
Reference Implementation of 5G Broadcast components. Key features include: Rel-16 numerologies, receive-only mode, improved signaling performnance, Rel-17 6/7/8 MHz bandwidths. End-to-end chain with ffmpeg as streamer, FLUTE library, mbms-gw, transmitters, SDR based middleware and modem and Android based middleware and simple application.
#### SCOPE
RS - Reference implementation
#### WHO IS USING
5G-MAG
#### WHERE TO FIND
- https://www.5g-mag.com/repositories
- https://github.com/5G-MAG/Getting-Started/wiki/Multimedia-content-delivery
- https://github.com/5G-MAG/Getting-Started/wiki/MBMS-&-LTE-based-5G-Broadcast

### Reference Tools for 3D and XR over 5G
#### SUMMARY
Immersive streaming experiences for entertainment,gaming,... test capabilities of 5G communication systems starting with 3D scenes for XR and different components that need to be delivered, streamed, etc. Real-time communication between participants, avatars, in AR environments. Projects on content playback (XR Player, XR Web Player based n Unity and Unreal Engine 5), content creation (Blender with support for glTF)
#### SCOPE
RS - Reference implementation
#### WHO IS USING
5G-MAG, MPEG
#### WHERE TO FIND
- https://www.5g-mag.com/repositories
- https://github.com/5G-MAG/Getting-Started/wiki/3D-and-XR-based-on-MPEG%E2%80%90I-Scene-Description

***

## HbbTV Association
### DASH-DRM Reference Application
#### SUMMARY
DASH-DRM Reference Application allows to showcase HbbTV technology together with MPEG-DASH and DRM.  It includes a complete workflow with MPEG-DASH content generation tools. Includes an HbbTV client application with a video catalogue and a video player.
#### SCOPE
RS/TV - Reference implementations and Test Vectors, device coverage tests
#### WHO IS USING
DVB, HbbTV
#### WHERE TO FIND
- https://refapp.hbbtv.org/ 
- https://github.com/HbbTV-Association/ReferenceApplication
- https://www.hbbtv.org/resource-library/#developer-support 
- Test material: https://refapp.hbbtv.org/videos

***

## MPEG
### MPEG Systems File Format Conformance Framework
#### SUMMARY
MPEG File Format Conformance Framework. Aim is to elevate the quality of standards developed by MPEG, identify issues early enough. MPEG has adopted that all incoming technologies need to be supported by conformance files together with metadata,… Files available can be searched in a board that allows developers to filter and find what they need.
#### SCOPE
TS/CS - Conformance Tools
#### WHO IS USING
MPEG
#### WHERE TO FIND
- https://github.com/MPEGGroup/FileFormatConformance
- https://mpeggroup.github.io/FileFormatConformance/

***

## SVTA
### Open Caching
#### SUMMARY
Open Caching aims at creating a single control plane for multi CDNs (centralized control plane for open caching nodes), a testbed initiative for interoperability between independent implementations has been created. For the moment available to SVTA members
#### SCOPE
RS - Conformance and Interoperability
#### WHO IS USING
SVTA members
#### WHERE TO FIND
Internal

## Common Media Player library
### SUMMARY
Library for media playback with a series of modules implementing features that can be imported as needed. Reduce duplicate code for different players and have a central place for reference implementations of standards-based features that end up in different players.
### SCOPE
RS - Reference implementations (CMCD, CMSD, ID23 parsing, Common Media Request/Response interfaces), web video players
### WHO IS USING
SVTA, hls.js, dash.js, video.js, Shaka Player
### WHERE TO FIND
- Github: https://github.com/streaming-video-technology-alliance/common-media-library
- NPM: @svta/common-media-library
- Docs: https://streaming-video-technology-alliance.github.io/common-media-library/
- Open call for new features: https://github.com/streaming-video-technology-alliance/common-media-library/discussions/54
