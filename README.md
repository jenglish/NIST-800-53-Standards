# NIST-800-53 Standard

NIST-800-53 Standard Controls for [Compliance Masonry],
updated to work better with [ssptool].

This is a fork of https://github.com/opencontrol/NIST-800-53-Standards/.

## Main changes

- Names of control families are spelled out in full
  (i.e., "Access control" instead of "AC").

## Data source

Data set was generated from the upstream source
https://csrc.nist.gov/CSRC/media/Projects/risk-management/800-53%20Downloads/800-53r4/800-53-rev4-controls.xml
found at
https://csrc.nist.gov/projects/risk-management/sp800-53-controls/downloads

## Usage

To import these data into a OpenControl project add the following
your opencontrol.yaml file:

```yaml
dependencies:
  standards:
    - url: https://github.com/jenglish/NIST-800-53-Standards
      revision: master
```

[Compliance Masonry]: https://github.com/opencontrol/compliance-masonry
[ssptool]: https://github.com/jenglish/ssptool
