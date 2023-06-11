- Filename: eccouncil-ceh31250-v12-14-6-1-input-filtering-evasion.md
- Show Name: CEHv12 (312-50)
- Topic Name: Web Application Hacking - Hacking Web Applications
- Episode Name: Input Filtering Evasion
================================================================================


Input Filtering Evasion
--------------------------------------------------------------------------------

Objectives:
--------------------------------------------------------------------------------

--------------------------------------------------------------------------------


+ List of filtering evasion techniques
  - Character Encoding
    + https://www.asciitable.com
    + HTML Elements
      - `&#x6A;` (hex) or `&#106;` (decimal)
        + Starts with **&#**
        + Ends with **;**
      - Further aided by zero padding
        + `&#000000x6A;`
        + Zeros are ignored, but change the string for filter evasion
    + Base64
    + Whitespace
      - Space
      - Tab
      - Newline
    + Script Tag Manipulation
      - Get weird
        + Mixed case
        + script in script
          `<sc<script>ript>`
    + Polyglots
      - https://github.com/0xSobsky/HackVault/wiki/Unleashing-an-Ultimate-XSS-Polyglot
