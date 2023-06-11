- Filename: eccouncil-ceh31250-v12-8-4-1-dns-poisoning.md
- Show Name: CEHv12 (312-50)
- Topic Name: Network and Perimeter Hacking: Sniffing
- Episode Name: DNS Poisoning
================================================================================


DNS Poisoning
--------------------------------------------------------------------------------

Objectives:
--------------------------------------------------------------------------------
- List and describe common DNS poisoning attack techniques and tools
--------------------------------------------------------------------------------


+ DNS basics
  - Resolve domains to IP
    + Windows DNS Lookup order
      - Checks self (am I the device I'm looking for?)
      - Checks DNS Resolver Cache
      - Checks the Hosts file (do I already know where this is?)
      - Checks with DNS Servers

+ DNS Attacks
  - Modifying hosts DNS info
  - Tricks hosts to query malicious DNS
    + Host file entries
    + Malicious proxy
+ DNS cache poisoning
  - Tricking clients into thinking that attacker is legit DNS
    + Redirect targets to malicious sites
  - **DEMO: Ettercap for DNS poisoning**
    1. Modify `etter.dns` file to have fake A records
      - Add `www.twitter.com A <AttackerIP>`
    2. Use *ettercap* to DNS Poison and ARP Spoof
      - Scan for hosts
      - Add hosts to Targets list
      - Start DNS_Poisoning Plugin
	+ 3 Dots Menu > Plugins > Manage Plugins
      - MiTM Menu > ARP Poisoning
    3. Ping `www.twitter.com` from Target
      - IP address in reply will be that of AttackerIP

+ DNS Poisoning and Spoofing Tools
  - Ettercap
  - DerpNSpoof
    + https://github.com/Trackbool/DerpNSpoof
