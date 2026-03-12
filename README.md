# VoIP Lab – Kamailio + Asterisk

This project demonstrates a basic VoIP architecture using Kamailio as a SIP proxy and Asterisk as the backend PBX.

The goal of this lab is to understand SIP routing, registration handling, and RTP media flow.

---

## Architecture

SIP Phone
   |
   v
Kamailio (Registrar + Proxy)
   |
   v
Asterisk (PBX)
   |
   v
Destination Endpoint

---

## Components

Kamailio – SIP proxy and registrar  
Asterisk – PBX for call routing  
SIP Clients – Softphones or SIP endpoints  
RTP – Media transport

---

## Features

SIP registration  
Call routing  
Authentication  
RTP media exchange  
Basic dial plan

---

## Technologies

Linux  
SIP  
RTP  
Kamailio  
Asterisk

---

## Setup Steps

1 Install Kamailio  
2 Configure SIP proxy  
3 Configure Asterisk PBX  
4 Register SIP clients  
5 Test calls

---

## Debugging Tools

tcpdump  
Wireshark  
SIP logs

---

## Learning Outcomes

Understanding SIP call flow  
VoIP system architecture  
Linux network debugging
