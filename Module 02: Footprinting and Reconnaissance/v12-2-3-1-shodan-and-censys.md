- Filename: eccouncil-ceh31250-v12-2-3-1-shodan-and-censys.md
- Show Name: CEHv12 (312-50)
- Topic Name: Footprinting and Recon
- Episode Name: Shodan and Censys

================================================================================


Shodan and Censys
--------------------------------------------------------------------------------

Objectives:
--------------------------------------------------------------------------------
- Footprint a target using IoT search engines for details such as deployed
  technologies, VoIP, and VPN
--------------------------------------------------------------------------------

+ We've looked at many different ways to gather information about a client/target,
  but we've mostly talked about searching for user/org/web info. What about the
  actual technologies and internet connected devices? How would we get that kind
  of info?
  - Shodan and Censys
+ Let's start off with Shodan. What are some of the details about Shodan we need
  to know?
  - https://help.shodan.io/the-basics/what-is-shodan
  - Shodan Demo
    + https://beta.shodan.io/search/filters
      - **filter_name**:*search_string*
	+ `printer port:21`
	+ `camera has_screenshot:true`
    + https://www.shodan.io/explore
+ Shodan seems pretty useful, but you mentioned Censys. How does Censys differ?
  - https://about.censys.io/
  - Censys Demo
    + https://search.censys.io
      - Search for **itpro.tv**
	+ Summary
	  - View All Data
	+ Explore
	+ History
	+ WHOIS
