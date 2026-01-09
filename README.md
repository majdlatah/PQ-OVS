# PQ-OVS
The goal of repo is to test [OVS](https://github.com/openvswitch/ovs)
 with PQ-TLS using [OpenSSL](https://github.com/openssl/openssl) and [liboqs](https://github.com/open-quantum-safe/liboqs)
.

My Setup:

| Component         | Specification             |
|-------------------|---------------------------|
| Operating System  | Ubuntu 25.04              |
| CPU               | AMD Ryzen 7 7840HS        |


Hybrid Post-Quantum TLS Latency for OVS switch:

| Algorithm       | Latency (ms) |
|-----------------|--------------|
| p256_mldsa44    | 290.7        |
| rsa3072_mldsa44 | 321.8        |
| p384_mldsa65    | 345.9        |
| p521_mldsa87    | 417.9        |
