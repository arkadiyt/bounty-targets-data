# bounty-targets-data [![Last commit](https://img.shields.io/github/last-commit/arkadiyt/bounty-targets-data.svg)](https://github.com/arkadiyt/bounty-targets-data/commits/master) [![License](https://img.shields.io/github/license/arkadiyt/bounty-targets-data.svg)](https://github.com/arkadiyt/bounty-targets-data/blob/master/LICENSE.md)

### What's it for

This repo contains data dumps of Hackerone and Bugcrowd scopes (i.e. the domains that are eligible for bug bounty reports). The files provided are:

Main files:
- [domains.txt](https://github.com/arkadiyt/bounty-targets-data/blob/master/data/domains.txt): full list of domains, without wildcards.
- [wildcards.txt](https://github.com/arkadiyt/bounty-targets-data/blob/master/data/wildcards.txt): full list of wildcard domains. **Note:** A program might have `*.example.com` in-scope but `excluded.example.com` out-of-scope so check your program rules before submitting reports.

Extra files:
- [bugcrowd_data.json](https://github.com/arkadiyt/bounty-targets-data/blob/master/data/bugcrowd_data.json): raw [Bugcrowd](https://bugcrowd.com) data.
- [hackerone_data.json](https://github.com/arkadiyt/bounty-targets-data/blob/master/data/hackerone_data.json): raw [Hackerone](https://hackerone.com) data.
- [federacy_data.json](https://github.com/arkadiyt/bounty-targets-data/blob/master/data/federacy_data.json): raw [Federacy](https://federacy.com) data.
- [hackenproof_data.json](https://github.com/arkadiyt/bounty-targets-data/blob/master/data/hackenproof_data.json): raw [Hackenproof](https://hackenproof.com) data.
- [intigriti_data.json](https://github.com/arkadiyt/bounty-targets-data/blob/master/data/intigriti_data.json): raw [Intigriti](https://www.intigriti.com) data.
- [yeswehack_data.json](https://github.com/arkadiyt/bounty-targets-data/blob/master/data/yeswehack_data.json): raw [YesWeHack](https://www.yeswehack.com/) data.
- [hackerone_schema.graphql](https://github.com/arkadiyt/bounty-targets-data/blob/master/data/hackerone_schema.graphql): Hackerone's graphql api schema.

### Status

The last change was detected on `Sunday 10/02/2022 19:30 (UTC)`. New changes (if any) are picked up hourly.

### Code

The code used to generate these files lives in the [bounty-targets](https://github.com/arkadiyt/bounty-targets) repo.

### Getting in touch

Feel free to contact me on twitter: https://twitter.com/arkadiyt
