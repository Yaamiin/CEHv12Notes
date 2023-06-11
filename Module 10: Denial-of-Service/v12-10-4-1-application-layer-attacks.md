- Filename: eccouncil-ceh31250-v12-10-4-1-application-layer-attacks.md
- Show Name: CEHv12 (312-50)
- Topic Name: Network and Perimeter Hacking: Denial of Service
- Episode Name: Application Layer Attacks
================================================================================


Application Layer Attacks
--------------------------------------------------------------------------------

Objectives:
--------------------------------------------------------------------------------
- List and describe common types of Application Layer DoS/DDoS attacks
--------------------------------------------------------------------------------


+ Application Layer (resource starvation, requests-per-second)
  - HTTP
    + Web services utilize HTTP Methods
      - GET
      - POST
    + Attacker overwhelms Server by flooding it with GET/POST requests
      - LOIC DEMO
    + Unintentional attack
      - Death of Michael Jackson
        + Stopped, slowed and even crashed
          - Google
          - Twitter
      - News/Link sites
        + Link goes viral and site gets overloaded by visits
          - Reddit Hug of Death
          - Digg Effect

  - SlowLoris
    + METASPLOIT DEMO
      - Read description in 'info' section

  - UDP App-layer flood
    + UDP Flood attacks against services like...
      - TFTP
      - VoIP
      - Steam protocol
      - RPC
      - SNMPv2
      - NetBIOS
