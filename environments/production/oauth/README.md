# OAuth Configuration
Configures OAuth and LDAP sync for managed clusters

## Dependencies
  - None

## Details
ACM Minimal Version: 2.12

Configures OAuth resource, CA cert bundle and synchronizes bind credentials for LDAP sync task.

The 'ldap-secret.yaml' file is not for providing credentials, it is to check if the secret exists.

---
**Notes:**
  - At environment level this assumes all clusters have the same OAuth
  - For per cluster configuration move to cluster directories.

