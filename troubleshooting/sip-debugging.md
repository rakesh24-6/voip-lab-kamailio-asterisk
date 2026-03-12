# SIP Debugging

Common troubleshooting steps for VoIP systems.

## Capture SIP packets

tcpdump -i eth0 port 5060 -n

## Analyze RTP packets

tcpdump -i eth0 udp portrange 10000-20000

## Check SIP logs in Asterisk

asterisk -rvvv

pjsip set logger on

## Verify registration

pjsip show endpoints
