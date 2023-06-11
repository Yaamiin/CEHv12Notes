- Filename: eccouncil-ceh31250-v12-20-3-1-cryptography-tools.md
- Show Name: CEHv12 (312-50)
- Topic Name: Cryptography - Cryptography
- Episode Name: Cryptography Tools
================================================================================


Cryptography Tools
--------------------------------------------------------------------------------

Objectives:
--------------------------------------------------------------------------------

--------------------------------------------------------------------------------


+ Tools
  - GPG
    + https://gnupg.org
      - Create Keys
	+ `gpg --generate-key`
      - List Keys
	+ `gpg --list-keys`
      - Export Key
	+ `gpg --armor --export sophia.goodwin@acilearning.com`
      - Import Key
	+ `gpg import administrator.gpg`
	  - `--allow-non-selfsigned-uid`
      - Encrypt Document
	+ `gpg --output doc.gpg --encrypt --recipient daniel.lowrie@acilearning.com doc`
      - Decrypt Document
	+ `gpg --output doc --dycrypt doc.gpg`
  - GPG4Win
    + https://gpg4win.org/
  - BCTextEncoder
  - Mobile
    + Goolge Play
    + Apple App Store
