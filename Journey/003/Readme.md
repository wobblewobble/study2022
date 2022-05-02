**Add a cover photo like:**
![placeholder image](https://via.placeholder.com/1200x600)

Certificates

## Introduction
All good cloud solutions need to be browser based.
Having a problem at work so this was a logical place to start.

✍️ (Why) Explain in one or two sentences why you choose to do this project or cloud topic for your day's study.

## Prerequisite

✍️ (What) Explain in one or two sentences the base knowledge a reader would need before describing the the details of the cloud service or topic.

## Use Case

- 🖼️ (Show-Me) Create an graphic or diagram that illustrate the use-case of how this knowledge could be applied to real-world project
- ✍️ (Show-Me) Explain in one or two sentences the use case

## Cloud Research

- ✍️ Document your trial and errors. Share what you tried to learn and understand about the cloud topic or while completing micro-project.
- 🖼️ Show as many screenshot as possible so others can experience in your cloud research.

Understand Client Server handshakes
https://blogs.sap.com/2021/07/22/how-to-troubleshoot-client-certificate-authentication-for-inbound-communication-to-cloud-integration-using-wireshark/

Find a Clent Server hello and others in a wireshark capture.

Client Hello:
ssl.handshake.type == 1

Server Hello:
ssl.handshake.type == 2

NewSessionTicket:
ssl.handshake.type == 4

Certificate:
ssl.handshake.type == 11

CertificateRequest
ssl.handshake.type == 13

ServerHelloDone:
ssl.handshake.type == 14

Note: “ServerHellpDone” means full-handshake TLS session.

Cipher Suites:
ssl.handshake.ciphersuite

The full list

Message types
Code	Description
0	HelloRequest
1	ClientHello
2	ServerHello
4	NewSessionTicket
8	EncryptedExtensions (TLS 1.3 only)
11	Certificate
12	ServerKeyExchange
13	CertificateRequest
14	ServerHelloDone
15	CertificateVerify
16	ClientKeyExchange
20	Finished
Please note:

More and more deployment require more secure 
mechnism e.g.Perfect Forward Secrecy. To provide
 PFS, cipher suite need to leverage  Ellipt
ic-curve Diffie–Hellman (ECDH) or Ephemer
al Diffie-Hellman during the key exchange. 
 In those cases, we can’t use private key
 to de-encrypt the traffic. as well.


More and more deployment require more secure mechnism e.g.Perfect Forward Secrecy. To provide PFS, cipher suite need to leverage  Elliptic-curve Diffie–Hellman (ECDH) or Ephemeral Diffie-Hellman during the key exchange.  In those cases, we can’t use private key to de-encrypt the traffic.
## Try yourself

✍️ Add a mini tutorial to encourage the reader to get started learning something new about the cloud.

### Step 1 — Summary of Step

![Screenshot](https://via.placeholder.com/500x300)

### Step 1 — Summary of Step

![Screenshot](https://via.placeholder.com/500x300)

### Step 3 — Summary of Step

![Screenshot](https://via.placeholder.com/500x300)

## ☁️ Cloud Outcome

✍️ (Result) Describe your personal outcome, and lessons learned.

## Next Steps

✍️ Describe what you think you think you want to do next.

## Social Proof

✍️ Show that you shared your process on Twitter or LinkedIn

[link](link)
