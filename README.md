# Secure Service Communication using TLS and Mutual TLS (mTLS)

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
  ## 1. Unencrypted Backend Communication
  (https://github.com/Sushiila/secure-service-communication-tls-mtls/blob/4d9feff150e95b45b21402c541b8602a4d1ade93/01%20-%20Backend%20Communication%20Over%20HTTP%20Without%20Encryption.png))

## 2. Traffic Interception using tcpdump


## 3. Certificate Authority Setup

(image)

## 4. TLS Encryption Successfully Established

(image)

## 5. Unauthorized Client Blocked using mTLS

(image)
