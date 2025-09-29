---
title: Get Started
layout: page
---
# How to Join MapleMesh
## A Beginner’s Guide to Connecting to the Local Meshtastic Network
## What is MapleMesh?
MapleMesh is a community communication network built using LoRa (long range, low power radios, called "nodes") and [Meshtastic](https://meshtastic.org/), an open-source project that lets small radios send text messages and GPS information without cell towers or Wi-Fi. Individual nodes work together to create a mesh network. The more units in use, the stronger the network!

The "mesh" part means each device passes along messages for others, so even if you’re far away from someone, your message can hop across multiple devices until it reaches them.

## What is LoRa?
LoRa is the wireless technology this network uses. It’s designed to send small amounts of data—like text messages while using very little power.

Think of it as walkie-talkies for data. Instead of voice, LoRa carries text and (sometimes) location information.

## Prerequisites
Before you can connect to MapleMesh, you’ll need:
1. A Meshtastic-capable radio device
* This is a small, consumer-purchasable device that contains a LoRa radio chip and can run the Meshtastic software.
* Several ready-to-use or kit-based options are listed later in this guide.
2. A smartphone or computer
  * You’ll use this to set up your device and send/receive messages through the free Meshtastic app or web tools.
     * [Google Play Store (for Android devices) link](https://play.google.com/store/apps/details?id=com.geeksville.mesh&hl=en_US&pli=1)
     * [iPhone app (for iPhones) link](https://apps.apple.com/us/app/meshtastic/id1586432531?ign-itscg=30200&ign-itsct=apps_box_promote_link)
3. Basic setup information
  * Region: US (to match US frequency rules)
  * Channel settings: set the modem preset to medium_fast (this balances speed and range and is what MapleMesh uses)
4. Power source
  * Most devices include a rechargeable battery or can run from USB power.

## Step-by-Step Setup
1. Get a Meshtastic Device
Pick one of the hardware options below (see "Hardware Choices"). Make sure you choose the 915 MHz / US version.

2. Install or Confirm Meshtastic Software
* Many devices come with Meshtastic already installed.
* If yours doesn’t, you’ll need to "flash" the Meshtastic firmware (instructions: [Meshtastic Docs](https://meshtastic.org/docs/getting-started/))

3. Connect Your Device
* Use the Meshtastic mobile app (Android or iOS) or connect by USB to your computer.
* The app will recognize your device and let you configure settings.
  
4. Set the Region and Modem Preset to Join the MapleMesh Network
* In the app, go to Radio Settings → Region and select United States.
   * This ensures the device uses legal frequencies (902–928 MHz).
* In Radio Settings → Modem Preset, select medium_fast.
   * This tells your device to match the settings used by the MapleMesh network.
* Scroll the the bottom of the page and click Send—the device may reboot.
* Under the Device Config menu of the app, select "Client" as the role -- this is likely already selected. Click Send-the device may reboot.

5. Test Your Connection
* From the app, try sending a text message.
* If you’re in range of another MapleMesh device, your message will hop into the network.
* Walk around or place your device outside to improve range

## Hardware Choices
## (Lowest Cost & Most DIY → Highest Cost & Easiest to Use)
Here are common options you can buy online. Prices vary by seller, but this order reflects typical price and ease of use:
* [RAK WisBlock Meshtastic Starter Kit (~$15–20)](https://store.rokland.com/products/rak-wireless-wisblock-meshtastic-starter-kit)
  * Modular kit with base + LoRa module.
  * Pros: inexpensive, flexible for hobbyists.
  * Cons: requires assembly and flashing.
* [WisMesh Pocket Mini Handheld (~$50)](https://store.rokland.com/products/rakwireless-wismesh-pocket-mini-all-in-one-meshtastic-handheld-915-mhz-radio-with-lora-antenna?_pos=1&_sid=daa68afd2&_ss=r)
  * Compact handheld pre-built node.
  * Pros: ready to use, portable.
  * Cons: smaller battery, shorter runtime.
* [Heltec LoRa32 V3 (~$55–60)](https://heltec.org/project/wifi-lora-32-v3/)
  * Small board with built-in screen.
  * Pros: compact, affordable, many tutorials.
  * Cons: less rugged, not weatherproof without a waterproof enclosure.
* [WisMesh Pocket v2 All-in-One (~$90)](https://store.rokland.com/products/wismesh-pocket?_pos=1&_sid=c9a7aebce&_ss=r)
  * Larger handheld with screen, antenna, and battery.
  * Pros: plug-and-play, user-friendly.
  * Cons: more expensive.
* [Spec5 Trekker Delta (~$145)](https://specfive.com/products/spec5-trekker-delta)
  * Rugged outdoor handheld, built for field use.
  * Pros: weather-resistant, longer battery life.
  * Cons: pricier.

## Quick Tips
* Line of sight matters: devices work best when not blocked by buildings or hills.
* Antennas make a difference: The right antenna for the right situation makes a big difference in range.
* More nodes = stronger mesh: even if you’re not chatting, just running your node helps the network grow.

### Other Relevant Documentation
* Meshtastic.org's [Introduction to LoRa and Meshtastic](https://meshtastic.org/docs/introduction/)
* Meshtastic.org's [Getting Started Guide](https://meshtastic.org/docs/getting-started/)
* Meshtastic.org's [Frequently Asked Questions](https://meshtastic.org/docs/faq/)

---