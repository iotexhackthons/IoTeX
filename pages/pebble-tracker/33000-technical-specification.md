## Technical Specification
| Page        | Link           |
| :-------------: | :-------------:  | 
| Technical Specification | https://docs.iotex.io/secure-hardware/pebble-tracker/technical-specification |


## Issues
| #   | Fault Category | Reviewer Comments | Evidence |
| :--: | :--: | :--: | :--: |
| 33001 | Hyperlink | Broken link: "Processor" | Link: https://docs.iotex.io/developer/hardware/pebble-data-specs.html#processor |
| 33002 | Hyperlink | Broken link: "Integrated Sensors" | Link: https://docs.iotex.io/developer/hardware/pebble-data-specs.html#integrated-sensors |
| 33003 | Hyperlink | Broken link: "Network Connectivity" | Link: https://docs.iotex.io/developer/hardware/pebble-data-specs.html#network-connectivity |
| 33004 | Hyperlink | Broken link: "Data Format" | Link: https://docs.iotex.io/developer/hardware/pebble-data-specs.html#data-format |
| 33005 | Hyperlink | Broken link: "Onboarding RGB Led" | Link: https://docs.iotex.io/developer/hardware/pebble-data-specs.html#onboard-rgb-led |
| 33006 | Hyperlink | Broken link: "2D Drawing" | Link: https://docs.iotex.io/developer/hardware/pebble-data-specs.html#_2d-drawing |
| 33007 | Textual | Formatting: "*I*OT-enabled" should be "**IOT-enabled**" | "Pebble includes a Multimode LTE-M/NB-IoT modem for cellular communication. To have your Pebble connected to the Internet you will need an *I*oT-enabled** SIM card that supports either NB-IoT or LTE standards." |
| 33008 | Example | Missmatch between JSON message object and message spec. `timestamp` spec says it's a String. Example object show's it's a Number. Recommendataion: add " " marks. | "Timestamp \ String \ Timestamp of sensor data sampling" => `{... timestamp: 3443547577, ...}` |
| 33009 | Example | Missmatch between JSON signature object and signature spec. `r` spec says it's a Number. Example object show's it's a String. Recommendataion: fix spec. | "r \ Number \ r value of an ECDSA signature" => `{... r: "D7797968EAA3FFE5F8057C9D97F707A4A96CBFC250115FE6293EBA5E90327174", ...}` |
| 33010 | Example | Missmatch between JSON signature object and signature spec. `s` spec says it's a Number. Example object show's it's a String. Recommendataion: fix spec. | "s \ Number \ s value of an ECDSA signature" => `{... s: "643A8CB823110376A5D30201463CF69CDF8CBF1C050EB85B023CABFB589C3222" ...}` |
