---
type: fixed
---
Image scans could not read tags, digests, or images from a registry with a certificate of a private CA, even when the CA is installed on the server, and showed it as a missing registry login. The scanner now also trusts the CA bundle of the server.
