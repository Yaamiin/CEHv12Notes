- Filename: eccouncil-ceh31250-v12-18-1-1-iot-basics.md
- Show Name: CEHv12 (312-50)
- Topic Name: Mobile Platform, IoT, and OT Hacking -  IoT and OT Hacking
- Episode Name: IoT Basics
================================================================================


IoT Basics
--------------------------------------------------------------------------------

Objectives:
--------------------------------------------------------------------------------

--------------------------------------------------------------------------------


+ Define IoT
  - "The process of connecting everyday objects and systems to networks in order
     to make them globally available and interactive." - Daniel Miessler
  - Consumer IoT
  - Industrial IoT (IIoT)
    + https://danielmiessler.com/blog/the-differences-and-similarities-between-iot-and-ics-security/

+ IoT Components
  - The IoT "THING"
    + Sensor
    + Camera
  - IoT Gateway
    + Connects IoT Devices to...
      - each other
      - end-user
      - cloud/internet
    + https://www.dell.com/en-us/work/shop/gateways-embedded-computing/sf/edge-gateway
  - Cloud Server
    + Stores and/or Processes IoT Data
  - Remote Apps
    + End-user control panel/dashboard

+ IoT Architecture
  - Edge Technology
    + IoT Hardware Components
  - Access Gateway
    + Inter-technology communication devices
  - Internet Layer
    + IP-based communication
  - Middleware
    + Services that run in the background of application layer software
  - Application Layer
    + Provides end-user operation and interaction

+ IoT Deployment Areas
  - Commercial/Industrial
  - Consumer
  - Heathcare
  - Transportation
  - Energy
  - Military/Law Enforcement
  - IT

+ Common IoT Technologies and Protocols
  - Communication
    + Wi-Fi
    + Zigbee
    + RFID
    + LTE-Advanced (medium-range)
    + Low-Power Wide Area Networking (LPWAN) (Long-Range)
    + Sigfox (long range)
    + Ethernet (wired)
  - Operating Systems for IoT
    + ARM mbed OS
      - https://os.mbed.com/mbed-os/
    + Win10 IoT
      - https://learn.microsoft.com/en-us/windows/iot-core/windows-iot
    + Contiki
      - https://www.contiki-ng.org/
    + Ubuntu Core
      - https://ubuntu.com/core

+ Communication Models
  - Device-to-Device
  - Device-to-Cloud
    + Devices --> App Service Provider
  - Device-to-Gateway
    + Devices --> IoT Gateway --> App Service Provider
  - Back-End Data-Sharing
    + Device --> App Service Provider1 --> App Service Provider2/3/4/etc

+ IoT Security Challenges
  - Weak or no intrinsic security
    + Weak authentication
    + Poor access control implementation
    + Vulnerable web apps
    + Clear-text communications
    + Buffer Overflows (RCE)
  - Support could be lacking or non-existent
  - Device theft
