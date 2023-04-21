# n3uron IIoT gateway running on balena

This is a reference architecture to run on your Industrial ioT Edge gateway using N3uron, HiveMQ on balena.

N3uron is an IIoT edge platform which provides data acquisition from multiple industrial protocols (e.g. Modbus, OPC UA, and more), connectivity with Historian or MQTT brokers, data processing and more. It also includes features such as real-time monitoring and data visualization. N3uron works as a swiss knife designed to help industrial organizations to make data-driven decisions based on insights collected from their IIoT data.

## Disclaimer

This project is for educational purposes only. Do not deploy it into your premises without understanding what you are doing. USE THE SOFTWARE AT YOUR OWN RISK. THE AUTHORS AND ALL AFFILIATES ASSUME NO RESPONSIBILITY FOR YOUR SECURITY.

We strongly recommend you to have some coding and networking knowledge. Do not hesitate to read the source code and understand the mechanism of this project or contact the authors.


## Deploy the code

Running this project is as simple as deploying it to a balenaCloud application. You can do it in just one click by using the button below:

[![](https://www.balena.io/deploy.png)](https://dashboard.balena-cloud.com/deploy?repoUrl=https://github.com/mpous/n3uron-balena)

Follow instructions, click Add a Device and flash an SD card with that OS image dowloaded from balenaCloud. Enjoy the magic 🌟Over-The-Air🌟!

## Log in

The N3uron service is exposed in the port 443 (`https://`). It is running the default configuration they use the default port and credentials to access them. Check the documentation for each of them to know how to change them using variables.

|Service|Port|Username|Password|
|:--|---|---|---|
|HiveMQ|8080 (http)|admin|hivemq|
|N3uron|443 (https)|admin|n3uron|


## Attribution

This is in part working thanks of the work and support of Jose Granero and Daniel Paesa from N3uron and Marc Pous from balena.io.

## Troubleshooting

If you detect any issue using this block, feel free to contact us at the [forums.balena.io](https://forums.balena.io).

