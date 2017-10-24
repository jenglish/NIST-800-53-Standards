# NIST-800-53 Standard

NIST-800-53 Standard Controls for [Compliance Masonry],
updated to work better with [ssptool].

This is a fork of https://github.com/opencontrol/NIST-800-53-Standards/.

## Main changes

- Names of control families are spelled out in full
  (i.e., "Access control" instead of "AC").
- Control descriptions are stored as structured narratives,
  using an [ssptool] extension to the standard schema.

Data set was generated from the upstream source
https://nvd.nist.gov/static/feeds/xml/sp80053/rev4/800-53-controls.xml
found at
https://csrc.nist.gov/publications/detail/sp/800-53/rev-4/final

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

