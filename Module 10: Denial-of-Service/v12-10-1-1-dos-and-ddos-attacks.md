- Filename: eccouncil-ceh31250-v12-10-1-1-dos-and-ddos-attacks.md
- Show Name: CEHv12 (312-50)
- Topic Name: Network and Perimeter Hacking: Denial of Service
- Episode Name: DoS and DDoS Attacks
================================================================================


DoS and DDoS Attacks
--------------------------------------------------------------------------------

Objectives:
--------------------------------------------------------------------------------
- Define DoS and DDoS attacks
- List and explain DoS attack types
- List and define the different DoS/DDoS categories
- Identify commonly used DoS/DDoS attack tools for different platforms
--------------------------------------------------------------------------------


+ What is a DoS attack?
+ What is the difference between DoS and DDoS? (attack types)
+ Common attack techniques?
  - Categories
    + Volumetric (depletion of bandwidth, bits-per-second)
      - Amplification attacks
        + UDP Flood
        + ICMP Flood
        + Ping of Death
        + Smurf
        + Pulse Wave
	  - Effective against hybrid-cloud environments
    + Protocol (packets-per-second)
      - SYN Flood
      - ACK Flood
      - Fragmentation
    + Application Layer (resource starvation, requests-per-second)
      - SlowLoris
      - UDP app-layer flood
    + Multi-Vector
      - Volumetric + Protocol + Application-Layer
    + Permanent DoS
      - Bricking
      - Phlashing
    + Reflective
      - Hides the true source of attack
      - Distributed Reflection DoS or DRDDoS
        + Multiple distributed attacking devices
        + Utilizing Reflective DoS attacks
    + Ransom DDoS
+ DoS/DDoS Tools
  - High/Low Orbit Ion Cannon
    + LOIC has mobile version
    + https://sourceforge.net/projects/highorbitioncannon/
    + https://sourceforge.net/projects/loic/
  - hping3
  - Metasploit
