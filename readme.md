# Device Firmware Blobs

Extra proprietary firmware and TrustZone applets for mobile Linux (Kupfer Linux, postmarketOS).

## Directory Structure

Mirrors standard Linux kernel firmware paths under `/usr/lib/firmware/`:

```
firmware/
└── qcom/
    └── <soc>/
        └── <device>/
```

### Currently Included:

- **Fairphone 4 (`qcom/sm7225/fairphone4/`)**:
  - `fingerprint.mdt` / `fingerprint.b00`–`b07`: Chipone ICNF7312 TrustZone Application (QSEE `fngap64`) required by `tz-qsee-fingerprintd`.
