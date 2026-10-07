# Expected output for AE-3

The requirement includes records classified as `SEVERE` or `LIFE THREATENING`, producing four records:

| USUBJID | AETERM | AESEV |
|---|---|---|
| 003 | Neutropenia | SEVERE |
| 004 | Anaphylaxis | LIFE THREATENING |
| 006 | Sepsis | SEVERE |
| 007 | Cardiac arrest | LIFE THREATENING |

Expected record count: **4**

If the requirement changes, this file must be updated and reviewed with the implementation and automated tests.
