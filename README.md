# secure-service-communication-tls-mtls
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

(image)

## 2. Traffic Interception using tcpdump

(image)

## 3. Certificate Authority Setup

(image)

## 4. TLS Encryption Successfully Established

(image)

## 5. Unauthorized Client Blocked using mTLS

(image)
