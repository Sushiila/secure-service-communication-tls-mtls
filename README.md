# Secure Service Communication using TLS and Mutual TLS (mTLS)
Secure service-to-service communication using TLS, mutual TLS (mTLS), OpenSSL, and certificate-based authentication.



## Objective

This project demonstrates secure service-to-service communication using TLS and Mutual TLS (mTLS).

The implementation focused on:
- certificate generation
- encrypted communication
- mutual authentication
- secure backend communication
- traffic interception testing

## Tools Used

- OpenSSL
- Linux
- tcpdump
- TLS Certificates
- mTLS Authentication
- Docker Networking

## Key Security Concepts

### TLS Encryption
Implemented encrypted communication between services.

### Mutual TLS Authentication
Configured client certificate validation to prevent unauthorized service access.

### Certificate Authority (CA)
Generated internal CA certificates for secure trust establishment.

### Traffic Inspection
Captured and analyzed unencrypted traffic using tcpdump to validate encryption effectiveness.

## Skills Demonstrated

- Cloud Security
- Secure Communication
- PKI Concepts
- TLS/mTLS
- Network Security
- Linux Administration

  ## Screenshots
1. Unencrypted Backend Communication
  (https://github.com/Sushiila/secure-service-communication-tls-mtls/blob/4d9feff150e95b45b21402c541b8602a4d1ade93/01%20-%20Backend%20Communication%20Over%20HTTP%20Without%20Encryption.png)

2. Traffic Interception using tcpdump
(https://github.com/Sushiila/secure-service-communication-tls-mtls/blob/445d1a31f625429138065417c66de163d08ba919/02-%20Intercepting%20Unencrypted%20Backend%20Traffic%20Using%20tcpdump.png)


3. Certificate Authority Setup
(https://github.com/Sushiila/secure-service-communication-tls-mtls/blob/3cd0761deb2fcff7df81d5d22bd66f3b7c90b786/03%20-%20Internal%20Certificate%20Authority%20(CA)%20Setup%20for%20Secure%20Service%20Communication.png)

4. TLS Encryption Successfully Established
(https://github.com/Sushiila/secure-service-communication-tls-mtls/blob/d29068cf6cbf530fff096d3c12a834f31541065d/04%20-%20Encrypted%20Communication%20Established%20Between%20Services%20Using%20TLS.png)

5. Unauthorized Client Blocked using mTLS
(https://github.com/Sushiila/secure-service-communication-tls-mtls/blob/57f7b300185e8379824bf0549e1f963344e91428/05%20-%20Unauthorized%20Service%20Blocked%20Without%20Valid%20Client%20Certificate%20(mTLS%20Enforcement).png)
